#### Test 656816764cf5745_thali07_LGE-Nexus 5 Logs


```
--------- beginning of system
04-07 21:23:15.214   768   843 W PackageSettings: Skipping PackageSetting{112f90ec com.example.hello/10116} due to missing metadata
,--------- beginning of main
04-07 21:23:15.441  3623  3623 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-07 21:23:15.443  3623  3623 D AndroidRuntime: CheckJNI is OFF
04-07 21:23:15.546  3623  3623 D AndroidRuntime: Calling main entry com.android.commands.am.Am
04-07 21:23:15.549   768  1239 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-07 21:23:15.555   768  1239 V WindowManager: addAppToken: AppWindowToken{22b528da token=Token{2bfae285 ActivityRecord{3c801bfc u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
04-07 21:23:15.560   768   837 V WindowManager: Adding window Window{1b97dd3d u0 Starting com.test.thalitest} at 2 of 7 (after Window{37872551 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-07 21:23:15.563  3623  3623 D AndroidRuntime: Shutting down VM
04-07 21:23:15.565  1379  1394 W SearchService: Abort, client detached.
04-07 21:23:15.605   768   783 I ActivityManager: Start proc 3644:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
04-07 21:23:15.635   199   199 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 468us total 13.076ms
04-07 21:23:15.637  1379  1568 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
04-07 21:23:15.651   199   199 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 196us total 9.470ms
04-07 21:23:15.655  1379  1591 I DeviceStateChecker: DeviceStateChecker cancelled
04-07 21:23:15.658  1379  1379 I MicroDetector: Keeping mic open: false
04-07 21:23:15.658  1379  1379 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@20fb7b41
04-07 21:23:15.664   199   199 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 1.767ms total 11.285ms
04-07 21:23:15.694  3644  3644 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
04-07 21:23:15.704  3644  3644 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 8717-8718)
04-07 21:23:15.704  3644  3644 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-07 21:23:15.706  1570  2559 I CheckinService: Done disabling old GoogleServicesFramework version
04-07 21:23:15.713  3644  3644 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a93190b}
04-07 21:23:15.713  3644  3644 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-07 21:23:15.713  3644  3644 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
04-07 21:23:15.713   188  1596 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-07 21:23:15.714   188  1596 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-07 21:23:15.719  1379  1590 I MicroRecognitionRunner: Stopping hotword detection.
04-07 21:23:15.719  1379  1593 I MicroRecognitionRunner: Detection finished
04-07 21:23:15.728  3644  3644 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
04-07 21:23:15.744  3644  3644 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-07 21:23:15.780   768   784 I ActivityManager: Killing 3244:com.quickoffice.android/u0a65 (adj 15): empty #17
,04-07 21:23:15.784   768   836 D BluetoothManagerService: Message: 20
04-07 21:23:15.784   768   836 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15424c4:true
,04-07 21:23:15.826  3644  3644 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
04-07 21:23:15.826  3644  3644 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,04-07 21:23:15.893  3644  3644 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-07 21:23:15.893  3644  3644 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,04-07 21:23:15.905  3644  3644 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,04-07 21:23:15.911  3644  3644 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-07 21:23:15.912  3644  3644 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,04-07 21:23:15.921  3644  3644 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,04-07 21:23:15.942  3644  3702 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-07 21:23:15.948  3644  3644 D Atlas   : Validating map...
,04-07 21:23:15.952   768   784 V WindowManager: Adding window Window{13bd0bde u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1b97dd3d u0 Starting com.test.thalitest})
,04-07 21:23:15.960   768   868 D WifiService: New client listening to asynchronous messages
,04-07 21:23:15.970   768  1312 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-07 21:23:15.970   768   869 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-07 21:23:15.970   768   869 D ConnectivityService: apparently satisfied.  currentScore=60
,04-07 21:23:15.971  3644  3705 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-07 21:23:16.000  3644  3702 I OpenGLRenderer: Initialized EGL, version 1.4
,04-07 21:23:16.003  3644  3702 D OpenGLRenderer: Enabling debug mode 0
,04-07 21:23:16.030  3644  3707 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,04-07 21:23:16.057   768   837 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +477ms
,04-07 21:23:16.063  1084  1084 I Keyboard.Facilitator: onFinishInput()
,04-07 21:23:16.093  3644  3644 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3644
,04-07 21:23:16.317  3644  3644 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-07 21:23:16.499  3644  3717 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362677632
,04-07 21:23:16.504  3644  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-07 21:23:16.504  3644  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-07 21:23:16.504  3644  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-07 21:23:16.504  3644  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-07 21:23:16.504  3644  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-07 21:23:16.504  3644  3717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aef2db added. We now have 1 listener(s)
04-07 21:23:16.505   768   938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-07 21:23:16.507  3644  3717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,04-07 21:23:16.510  3644  3717 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,04-07 21:23:16.511  3644  3717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,04-07 21:23:16.512  3644  3717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-07 21:23:16.517  3644  3717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bfdb0b6 added. We now have 1 listener(s)
04-07 21:23:16.517  3644  3717 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-07 21:23:16.521  3644  3717 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,04-07 21:23:16.524  3644  3717 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
04-07 21:23:16.524  3644  3717 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,04-07 21:23:16.527  3644  3717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,04-07 21:23:16.527   768  2295 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-07 21:23:16.528  3644  3717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,04-07 21:23:16.534  3644  3717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-07 21:23:16.534  3644  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-07 21:23:16.534  3644  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-07 21:23:16.534  3644  3717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-07 21:23:16.534  3644  3717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-07 21:23:16.534  3644  3717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-07 21:23:16.534  3644  3717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-07 21:23:16.534  3644  3717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-07 21:23:16.534  3644  3717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-07 21:23:16.534  3644  3717 D io.jxcore.node.ConnectivityMonitor: start: OK
,04-07 21:23:16.535  3644  3717 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-07 21:23:16.536  3644  3644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-07 21:23:16.540  3644  3644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-07 21:23:16.564  3644  3644 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-07 21:23:17.258  3644  3723 W jxcore-log: Initializing JXcore engine
04-07 21:23:17.258  3644  3723 W jxcore-log: JXcore engine is ready
,04-07 21:23:17.296  3723  3723 W Thread-357: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[6623]" dev="sockfs" ino=6623 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,04-07 21:23:17.296  3723  3723 W Thread-357: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
04-07 21:23:17.296  3723  3723 W Thread-357: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8509]" dev="sockfs" ino=8509 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-07 21:23:17.296  3723  3723 W Thread-357: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[17835]" dev="sockfs" ino=17835 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,04-07 21:23:17.318  3644  3723 W jxcore-log: Starting JXcore engine
,04-07 21:23:17.401  3644  3723 W jxcore-log: Platform android
04-07 21:23:17.401  3644  3723 W jxcore-log: 
,04-07 21:23:17.401  3644  3723 W jxcore-log: Process ARCH arm
04-07 21:23:17.401  3644  3723 W jxcore-log: 
,04-07 21:23:17.611  1548  1623 I Finsky  : [123] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-07 21:23:17.612  1548  1548 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-07 21:23:17.618  3644  3723 I jxcore-log: JXcore Cordova bridge is ready!
04-07 21:23:17.618  3644  3723 I jxcore-log: 
04-07 21:23:17.618  3644  3723 W jxcore-log: JXcore engine is started
,04-07 21:23:17.620  3644  3717 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-07 21:23:17.621  3644  3644 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-07 21:23:19.736  3285  3312 W Babel   : aye TOOK TOO LONG! (15037ms > 10000ms)
,04-07 21:23:19.737  3285  3314 W Babel   : aye TOOK TOO LONG! (15023ms > 10000ms)
,04-07 21:23:19.806  3285  3322 W Babel   : aye TOOK TOO LONG! (15035ms > 10000ms)
,04-07 21:23:19.807   768  1312 I art     : Explicit concurrent mark sweep GC freed 22592(1319KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.426ms total 67.173ms
,04-07 21:23:19.823   768   783 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-07 21:23:19.825   768  1241 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-07 21:23:19.826  3285  3285 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
04-07 21:23:19.826  3285  3285 W Babel   : BAM#gBA: invalid account id: -1
04-07 21:23:19.826  3285  3285 W Babel   : BAM#gBA: invalid account id: -1
04-07 21:23:19.826  3285  3285 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,04-07 21:23:19.827   768   938 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-07 21:23:19.829   768   784 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-07 21:23:22.784  1548  1548 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(151): Beginning daily hygiene
,04-07 21:23:22.872  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:23:22.878  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:23:22.879  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:23:22.928  1626  1681 I art     : Explicit concurrent mark sweep GC freed 28734(1705KB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 22MB/37MB, paused 1.162ms total 34.488ms
,04-07 21:23:23.539  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:23:23.697  1548  1548 I Finsky  : [1] com.google.android.finsky.m.e.a(156): Skipping DFE self-update. Local Version [80631600] >= Server Version [-1]
,04-07 21:23:23.740  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:23:23.783   768  1177 I ActivityManager: Start proc 3755:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,04-07 21:23:23.820  3755  3755 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-07 21:23:23.820  3755  3755 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-07 21:23:23.845  3755  3755 I MultiDex: VM with version 2.1.0 has multidex support
04-07 21:23:23.845  3755  3755 I MultiDex: install
04-07 21:23:23.845  3755  3755 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-07 21:23:23.861  3755  3755 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,04-07 21:23:23.894  3755  3755 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-07 21:23:23.907  3755  3755 D ChimeraCfgMgr: Reading stored module config
,04-07 21:23:23.910  1570  3788 D LocationInitializer: Restart initialization of location
04-07 21:23:23.912  1626  1626 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-07 21:23:23.924  1626  1626 D WearableService: callingUid 10007, callindPid: 1626
,04-07 21:23:23.931  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:23:23.939  1626  3126 E MDM     : [213] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,04-07 21:23:23.944  1626  1676 W GCoreFlp: No location to return for getLastLocation()
04-07 21:23:23.945  1626  3789 W FusedLocationProvider: location=null
,04-07 21:23:24.016  3755  3787 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,04-07 21:23:24.019  3755  3755 D CAR.SERVICE: Connecting to CarCallService...
,04-07 21:23:24.029  3755  3755 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-07 21:23:24.030  3755  3755 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-07 21:23:24.036  3755  3755 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,04-07 21:23:24.045  3755  3755 D CAR.TEL.Service: Creating a new CarCallService.
,04-07 21:23:24.046  3755  3755 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,04-07 21:23:24.047   768  1167 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
04-07 21:23:24.048  3755  3755 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@174508a8
,04-07 21:23:24.048   768  1177 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,04-07 21:23:24.049  3755  3755 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
04-07 21:23:24.049  3755  3755 D CAR.TEL.Service: Starting CarCallService with initial phone null
,04-07 21:23:24.103  3755  3770 D CAR.SERVICE: Package validated; name: com.android.vending
,04-07 21:23:24.629  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:23:25.048  1548  1548 I Finsky  : [1] com.google.android.finsky.autoupdate.w.e(289): Notifying user that 3 applications have outstanding updates.
,04-07 21:23:25.107  1548  1548 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(9405): Logging device features
,04-07 21:23:25.162  1626  1740 D DeviceConnectionService: client connected with version: 8298000
,04-07 21:23:25.184  1548  1548 E Finsky  : [1] com.google.android.finsky.wear.bf.a(728): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,04-07 21:23:25.185  1548  1548 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6337): Dropping command=hygiene due to Gms not connected
,04-07 21:23:25.383   768  1177 I ActivityManager: Killing 3128:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,04-07 21:23:26.181   768   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
04-07 21:23:26.181   768   867 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-07 21:23:27.015  3644  3723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-07 21:23:27.015  3644  3723 I jxcore-log: 
,04-07 21:23:27.017  3644  3723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-07 21:23:27.017  3644  3723 I jxcore-log: 
,04-07 21:23:27.021  3644  3723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-07 21:23:27.021  3644  3723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-07 21:23:27.021  3644  3723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-07 21:23:27.021  3644  3723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-07 21:23:27.021  3644  3723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-07 21:23:27.021  3644  3723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-07 21:23:27.021  3644  3723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-07 21:23:27.021  3644  3723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-07 21:23:27.023  3644  3723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
04-07 21:23:27.024  3644  3723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-07 21:23:27.024  3644  3723 I jxcore-log: 
04-07 21:23:27.026  3644  3723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-07 21:23:27.026  3644  3723 I jxcore-log: 
,04-07 21:23:27.515  3644  3723 I jxcore-log: Unit Test app is loaded
04-07 21:23:27.515  3644  3723 I jxcore-log: 
,04-07 21:23:27.521  3644  3644 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-07 21:23:27.521  3644  3723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-07 21:23:27.521  3644  3723 I jxcore-log: 
,04-07 21:23:27.528  3644  3723 I jxcore-log: My device name is: LGE-Nexus 5
04-07 21:23:27.528  3644  3723 I jxcore-log: 
,04-07 21:23:28.945   768  1167 I ActivityManager: Killing 3353:com.google.android.configupdater/u0a2 (adj 15): empty #17
,04-07 21:23:29.150  3755  3755 D CAR.SERVICE: mConnectedToCar = false, abort
,04-07 21:23:29.153   768   783 I ActivityManager: Killing 3388:com.google.android.apps.gcs/u0a37 (adj 15): empty #17
,04-07 21:23:29.158  3755  3755 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1155d790 that was originally bound here
04-07 21:23:29.158  3755  3755 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1155d790 that was originally bound here
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-07 21:23:29.158  3755  3755 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-07 21:23:29.306  3755  3755 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3b0e48cb that was originally bound here
04-07 21:23:29.306  3755  3755 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3b0e48cb that was originally bound here
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-07 21:23:29.306  3755  3755 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-07 21:23:29.307   768  2295 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@3bab3a67
,04-07 21:23:30.123  1548  3849 I Finsky  : [136] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-07 21:23:30.133  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:23:30.141  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:23:30.144  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:23:31.221  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-07 21:23:31.221  3644  3723 I jxcore-log: 
,04-07 21:23:31.560  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-07 21:23:31.560  3644  3723 I jxcore-log: 
,04-07 21:23:31.584  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-07 21:23:31.584  3644  3723 I jxcore-log: 
,04-07 21:23:31.588  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-07 21:23:31.588  3644  3723 I jxcore-log: 
,04-07 21:23:31.603  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-07 21:23:31.603  3644  3723 I jxcore-log: 
,04-07 21:23:31.607  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-07 21:23:31.607  3644  3723 I jxcore-log: 
,04-07 21:23:33.507  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-07 21:23:33.507  3644  3723 I jxcore-log: 
,04-07 21:23:33.518  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-07 21:23:33.518  3644  3723 I jxcore-log: 
,04-07 21:23:33.526  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-07 21:23:33.526  3644  3723 I jxcore-log: 
,04-07 21:23:33.677  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-07 21:23:33.677  3644  3723 I jxcore-log: 
,04-07 21:23:34.576  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-07 21:23:34.576  3644  3723 I jxcore-log: 
,04-07 21:23:34.633  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-07 21:23:34.633  3644  3723 I jxcore-log: 
,04-07 21:23:34.639  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
04-07 21:23:34.639  3644  3723 I jxcore-log: 
,04-07 21:23:34.772  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-07 21:23:34.772  3644  3723 I jxcore-log: 
,04-07 21:23:34.792  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-07 21:23:34.792  3644  3723 I jxcore-log: 
,04-07 21:23:34.796  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-07 21:23:34.796  3644  3723 I jxcore-log: 
,04-07 21:23:34.801  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-07 21:23:34.801  3644  3723 I jxcore-log: 
,04-07 21:23:34.816  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-07 21:23:34.816  3644  3723 I jxcore-log: 
,04-07 21:23:34.835  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-07 21:23:34.835  3644  3723 I jxcore-log: 
,04-07 21:23:34.918  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-07 21:23:34.918  3644  3723 I jxcore-log: 
,04-07 21:23:34.922  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-07 21:23:34.922  3644  3723 I jxcore-log: 
,04-07 21:23:34.946  3644  3723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-07 21:23:34.946  3644  3723 I jxcore-log: 
,04-07 21:23:34.968  3644  3723 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
04-07 21:23:34.969  3644  3723 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
04-07 21:23:34.969  3644  3723 I jxcore-log: 
,04-07 21:23:39.672  1548  1623 I Finsky  : [123] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-07 21:23:39.674  1548  1548 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-07 21:23:46.185   768   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
,04-07 21:24:04.587  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:24:04.591  1626  3909 I VacuumService: Vacuum at: now=1460057044591 tag=VacuumService
,04-07 21:24:05.024   768   832 W ProcessCpuTracker: Skipping unknown process pid 3894
04-07 21:24:05.024   768   832 W ProcessCpuTracker: Skipping unknown process pid 3895
04-07 21:24:05.025   768   832 W ProcessCpuTracker: Skipping unknown process pid 3898
04-07 21:24:05.025   768   832 W ProcessCpuTracker: Skipping unknown process pid 3899
,04-07 21:24:05.027   768   832 W ProcessCpuTracker: Skipping unknown process pid 3902
04-07 21:24:05.027   768   832 W ProcessCpuTracker: Skipping unknown process pid 3903
,04-07 21:24:05.028   768   832 W ProcessCpuTracker: Skipping unknown process pid 3904
,04-07 21:24:05.029   768   832 W ProcessCpuTracker: Skipping unknown process pid 3907
04-07 21:24:05.030   768   832 W ProcessCpuTracker: Skipping unknown process pid 3908
04-07 21:24:05.030   768   832 W ProcessCpuTracker: Skipping unknown process pid 3910
04-07 21:24:05.031   768   832 W ProcessCpuTracker: Skipping unknown process pid 3914
04-07 21:24:05.031   768   832 W ProcessCpuTracker: Skipping unknown process pid 3917
,04-07 21:24:05.558  1626  3921 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 4918 seconds from now (1460057045558)
,04-07 21:24:05.641  1626  3913 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,04-07 21:24:05.644  1626  3913 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-07 21:24:06.186   768   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
04-07 21:24:06.186   768   867 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-07 21:24:07.121  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:24:07.122  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:24:08.746  1626  1641 I art     : Background sticky concurrent mark sweep GC freed 164731(9MB) AllocSpace objects, 49(807KB) LOS objects, 22% free, 27MB/35MB, paused 1.570ms total 135.642ms
,04-07 21:24:08.767   768   783 I art     : Explicit concurrent mark sweep GC freed 45650(2021KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.087ms total 82.506ms
,04-07 21:24:16.084  1084  1275 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-07 21:24:16.084  1084  1275 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-07 21:24:26.190   768   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
04-07 21:24:26.190   768   867 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-07 21:24:46.024   768   839 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,04-07 21:24:46.033   768   839 I PowerManagerService: Sleeping (uid 1000)...
,04-07 21:24:46.080   768   839 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-07 21:24:46.094   188   865 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-07 21:24:46.109   181   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (117 us)
,04-07 21:24:46.122   768   867 E WifiStateMachine: cancelDelayedScan -> 11
,04-07 21:24:46.130   768   867 E native  : do suspend false
,04-07 21:24:46.191   768   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
04-07 21:24:46.191   768   867 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 12 -> obsolete
,04-07 21:24:46.259   188   188 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,04-07 21:24:46.260  1084  1084 I Keyboard.Facilitator: onFinishInput()
,04-07 21:24:46.268   768   867 E WifiStateMachine: cancelDelayedScan -> 13
,04-07 21:24:46.269   768   867 E native  : do suspend true
,04-07 21:24:46.637   768   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
04-07 21:24:46.637   768   867 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,04-07 21:24:46.641   768   837 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
04-07 21:24:46.643   768   768 V ActivityManager: Display changed displayId=0
,04-07 21:24:46.660   181   181 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
,04-07 21:24:46.674   181   181 D qdhwcomposer: hwc_blank: Blanking display: 0
,04-07 21:24:46.757   182   182 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
04-07 21:24:46.757   182   182 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
04-07 21:24:46.757   182   182 I rmt_storage: wakelock acquired: 1, error no: 2
,04-07 21:24:46.757   182   560 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236802816)
,04-07 21:24:46.834   182   560 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
04-07 21:24:46.834   182   560 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
04-07 21:24:46.834   182   560 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236802816) wakelock released: 1, error no: 0
04-07 21:24:46.834   182   560 I rmt_storage: 
,04-07 21:24:46.837   182   182 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,04-07 21:24:46.918  2071  2138 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-07 21:24:46.946   181   181 D qdhwcomposer: hwc_blank: Done blanking display: 0
04-07 21:24:46.946   768   885 D SurfaceControl: Excessive delay in setPowerMode(): 305ms
04-07 21:24:46.947  1759  1763 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,04-07 21:24:46.959  3644  3644 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
04-07 21:24:46.959  3644  3644 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,04-07 21:24:46.977  3644  3644 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5720130 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3ad8de68, 16908290=android.view.AbsSavedState$1@3ad8de68}, android:focusedViewId=100}]}]
04-07 21:24:46.977  3644  3644 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
04-07 21:24:46.977  3644  3644 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
04-07 21:24:46.977  3644  3644 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,04-07 21:25:01.425  1626  2021 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,04-07 21:25:46.261  1084  1275 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-07 21:25:46.261  1084  1275 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-07 21:25:47.307  3644  3723 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-07 21:25:47.307  3644  3723 I jxcore-log: 
,04-07 21:25:47.685  4021  4021 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-07 21:25:47.687  4021  4021 D AndroidRuntime: CheckJNI is OFF
,04-07 21:25:47.807  4021  4021 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-07 21:25:47.818   768   832 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
04-07 21:25:47.818   768   832 I ActivityManager: Killing 3644:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,04-07 21:25:47.870   768   843 W PackageSettings: Skipping PackageSetting{112f90ec com.example.hello/10116} due to missing metadata
,04-07 21:25:47.889   768   783 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1214763c)
,04-07 21:25:47.889   768   784 I WindowState: WIN DEATH: Window{13bd0bde u0 com.test.thalitest/com.test.thalitest.MainActivity}
04-07 21:25:47.889   768   869 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-07 21:25:47.890   768   869 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-07 21:25:47.890   768   868 D WifiService: Client connection lost with reason: 4
,04-07 21:25:48.037   768   832 I ActivityManager:   Force finishing activity 3 ActivityRecord{3c801bfc u0 com.test.thalitest/.MainActivity t19}
,04-07 21:25:48.042   768   783 W ActivityManager: Spurious death for ProcessRecord{1d24cfc5 3644:com.test.thalitest/u0a49}, curProc for 3644: null
,04-07 21:25:48.042   768   843 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,04-07 21:25:48.086  1213  1213 I art     : Explicit concurrent mark sweep GC freed 1767(109KB) AllocSpace objects, 5(450KB) LOS objects, 38% free, 25MB/41MB, paused 958us total 39.505ms
,04-07 21:25:48.107   908   908 I art     : Explicit concurrent mark sweep GC freed 12572(567KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 41MB/57MB, paused 836us total 25.656ms
,04-07 21:25:48.111   768   887 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
04-07 21:25:48.112   768   887 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
04-07 21:25:48.114  1626  1690 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
04-07 21:25:48.115   768   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-07 21:25:48.136  1084  1084 I Keyboard.Facilitator: resetDictionaries() : en_US
,04-07 21:25:48.154   768   768 I art     : Explicit concurrent mark sweep GC freed 26236(1589KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 29MB/43MB, paused 1.787ms total 63.477ms
,04-07 21:25:48.166  1084  4043 I Keyboard.Facilitator.DecoderInitializer: run()
,04-07 21:25:48.168  1084  4043 I Decoder : createOrResetDecoder
,04-07 21:25:48.177  1292  4042 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,04-07 21:25:48.188   768  1082 I ActivityManager: Start proc 4056:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,04-07 21:25:48.202  1570  1570 I art     : Explicit concurrent mark sweep GC freed 2706(155KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 23MB/31MB, paused 3.014ms total 149.671ms
,04-07 21:25:48.223  1379  1379 I art     : Explicit concurrent mark sweep GC freed 4003(281KB) AllocSpace objects, 7(154KB) LOS objects, 25% free, 22MB/30MB, paused 607us total 173ms
,04-07 21:25:48.238  1084  4043 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,04-07 21:25:48.257  1084  4043 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
04-07 21:25:48.259  1084  4043 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
04-07 21:25:48.259  1084  4043 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,04-07 21:25:48.260  1084  4043 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
04-07 21:25:48.260  1084  4043 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
04-07 21:25:48.261  1084  4043 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
04-07 21:25:48.261  1084  4043 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
04-07 21:25:48.262  1084  4043 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-07 21:25:48.262  1084  4043 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-07 21:25:48.262  1084  4043 I Keyboard.Facilitator.Delight2FileSweeper: run()
,04-07 21:25:48.263  1084  4043 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-07 21:25:48.263  1084  4043 I StatsUtilsManager: startPeriodStatsRecorder() : Success
04-07 21:25:48.263  1084  4043 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,04-07 21:25:48.267   768   768 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-07 21:25:48.267   768   768 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,04-07 21:25:48.274   768  1239 I ActivityManager: Start proc 4078:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,04-07 21:25:48.277   768  1241 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3644 uid 10049
,04-07 21:25:48.278  1084  1084 I Keyboard.Facilitator: onFinishInput()
,04-07 21:25:48.278   768  1167 I ActivityManager: Killing 2948:com.google.android.gms.unstable/u0a7 (adj 15): empty #17
,04-07 21:25:48.302  1213  1213 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-07 21:25:48.316   768   843 I art     : Explicit concurrent mark sweep GC freed 13177(1271KB) AllocSpace objects, 1(1296KB) LOS objects, 33% free, 28MB/42MB, paused 1.528ms total 119.635ms
,04-07 21:25:48.349  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-07 21:25:48.353  1548  1548 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(268): Wear auto uninstall disabled for package com.test.thalitest
,04-07 21:25:48.369  1570  4098 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-07 21:25:48.370  1570  4098 D AccountUtils: Clearing selected account for com.test.thalitest
,04-07 21:25:48.374  4021  4021 I art     : System.exit called, status: 0
04-07 21:25:48.374  4021  4021 I AndroidRuntime: VM exiting with result code 0.
,04-07 21:25:48.392   768   843 I ActivityManager: Start proc 4103:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,04-07 21:25:48.393  1626  1626 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-07 21:25:48.393  1626  1626 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-07 21:25:48.394  1213  1416 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-07 21:25:48.403  1570  4098 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,04-07 21:25:48.449   768   938 I ActivityManager: Start proc 4127:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,04-07 21:25:48.462   768  1082 I ActivityManager: Killing 2925:com.google.android.apps.photos/u0a83 (adj 15): empty #17
,04-07 21:25:48.502  1570  4098 I GMPM-SVC: App measurement is starting up, version: 8703
04-07 21:25:48.502  1570  4098 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,04-07 21:25:48.506  1570  4124 W BaseAppContext: Using Auth Proxy for data requests.
,04-07 21:25:48.507  1570  4124 W BaseAppContext: Using Auth Proxy for data requests.
,04-07 21:25:48.511  1570  4124 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-07 21:25:48.511  1570  4124 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: Runtime exception while performing operation
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-07 21:25:48.512  1570  4124 E ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-07 21:25:48.513  1570  4124 F ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
04-07 21:25:48.525  1570  4148 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
04-07 21:25:48.531   768  4146 E DropBoxManagerService: Can't write: system_app_wtf
04-07 21:25:48.531   768  4146 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
04-07 21:25:48.531   768  4146 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-07 21:25:48.531   768  4146 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-07 21:25:48.531   768  4146 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-07 21:25:48.531   768  4146 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-07 21:25:48.531   768  4146 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-07 21:25:48.531   768  4146 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-07 21:25:48.531   768  4146 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-07 21:25:48.531   768  4146 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-07 21:25:48.531   768  4146 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-07 21:25:48.531   768  4146 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-07 21:25:48.531   768  4146 E DropBoxManagerService: 	... 5 more
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(:com.google.android.gms:223)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(:com.google.android.gms:601)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(:com.google.android.gms:595)
04-07 21:25:48.533  1570  4145 E SQLiteDatabase: 	at com.google.android.gms.drive.database.o.run(:com.google.android.gms:616)
04-07 21:25:48.534  1570  4098 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-07 21:25:48.537  1570  2037 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
04-07 21:25:48.537  1570  2037 E Icing   : Failed to open Apps corpus file.
04-07 21:25:48.537  1570  2037 E Icing   : Failed to open Apps corpus file.
04-07 21:25:48.538  1570  2037 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
04-07 21:25:48.541  1570  1654 I Icing   : doRemovePackageData com.test.thalitest
04-07 21:25:48.541  1570  4145 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
04-07 21:25:48.541  1570  4145 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
04-07 21:25:48.541  1570  4145 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
04-07 21:25:48.541  1570  4145 I GCore-Chimera-Crash: ==
04-07 21:25:48.541  1570  4145 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
04-07 21:25:48.542  1570  4145 E AndroidRuntime: FATAL EXCEPTION: Open database in background
04-07 21:25:48.542  1570  4145 E AndroidRuntime: Process: com.google.android.gms, PID: 1570
04-07 21:25:48.542  1570  4145 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at com.google.android.gms.drive.database.c.getWritableDatabase(:com.google.android.gms:223)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.b(:com.google.android.gms:601)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.a(:com.google.android.gms:595)
04-07 21:25:48.542  1570  4145 E AndroidRuntime: 	at com.google.android.gms.drive.database.o.run(:com.google.android.gms:616)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: Can't write: system_app_crash
04-07 21:25:48.544   768  4153 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-07 21:25:48.544   768  4153 E DropBoxManagerService: 	... 5 more
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2307)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:418)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.a(:com.google.android.gms:357)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.s(:com.google.android.gms:1591)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.p(:com.google.android.gms:1605)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.c(:com.google.android.gms:306)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ar.run(:com.google.android.gms:195)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-07 21:25:48.545  1570  4147 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ap.run(:com.google.android.gms:294)
04-07 21:25:48.545  1570  4147 E GMPM-SVC: Opening the database failed, dropping and recreating it
04-07 21:25:48.546  1570  4145 I Process : Sending signal. PID: 1570 SIG: 9
,04-07 21:25:48.561   768   868 D WifiService: Client connection lost with reason: 4

```
