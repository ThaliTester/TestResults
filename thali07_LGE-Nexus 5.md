#### Test 6568167646f0d89_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
04-07 21:52:14.634  1560  2460 I CheckinService: Done disabling old GoogleServicesFramework version
,04-07 21:52:14.878  3401  3401 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-07 21:52:14.881  3401  3401 D AndroidRuntime: CheckJNI is OFF
04-07 21:52:14.989  3401  3401 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
04-07 21:52:14.992   740  3225 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-07 21:52:14.998   740  3225 V WindowManager: addAppToken: AppWindowToken{3063dcd6 token=Token{a3c38f1 ActivityRecord{2a85898 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
04-07 21:52:15.004   740   833 V WindowManager: Adding window Window{1b881529 u0 Starting com.test.thalitest} at 2 of 7 (after Window{17f171f7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-07 21:52:15.008  3401  3401 D AndroidRuntime: Shutting down VM
04-07 21:52:15.020  1407  1425 W SearchService: Abort, client detached.
04-07 21:52:15.070   740  1124 I ActivityManager: Start proc 3422:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
04-07 21:52:15.095  1407  1585 I DeviceStateChecker: DeviceStateChecker cancelled
04-07 21:52:15.095  1407  1407 I MicroDetector: Keeping mic open: false
04-07 21:52:15.095  1407  1407 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@1ed81a52
04-07 21:52:15.099  1407  1559 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
04-07 21:52:15.150   190  1592 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-07 21:52:15.150   190  1592 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-07 21:52:15.154  1407  1589 I MicroRecognitionRunner: Detection finished
04-07 21:52:15.155  1407  1584 I MicroRecognitionRunner: Stopping hotword detection.
04-07 21:52:15.193  3422  3422 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
04-07 21:52:15.203  3422  3422 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 9573-9575)
04-07 21:52:15.203  3422  3422 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-07 21:52:15.206   740  3225 I ActivityManager: Killing 2574:com.google.android.keep/u0a52 (adj 15): empty #17
04-07 21:52:15.217  3422  3422 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f28d99d}
04-07 21:52:15.217  3422  3422 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-07 21:52:15.217  3422  3422 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,04-07 21:52:15.240  3422  3422 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,04-07 21:52:15.254  3422  3422 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-07 21:52:15.307   740   832 D BluetoothManagerService: Message: 20
04-07 21:52:15.307   740   832 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2398893f:true
,04-07 21:52:15.309  3422  3422 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
04-07 21:52:15.309  3422  3422 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,04-07 21:52:15.347  3422  3422 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-07 21:52:15.347  3422  3422 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,04-07 21:52:15.359  3422  3422 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,04-07 21:52:15.365  3422  3422 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-07 21:52:15.366  3422  3422 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,04-07 21:52:15.375  3422  3422 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,04-07 21:52:15.404  3422  3474 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-07 21:52:15.409  3422  3422 D Atlas   : Validating map...
,04-07 21:52:15.413   740   756 V WindowManager: Adding window Window{33c30d1a u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1b881529 u0 Starting com.test.thalitest})
,04-07 21:52:15.419   740   865 D WifiService: New client listening to asynchronous messages
,04-07 21:52:15.481   740   846 I art     : Explicit concurrent mark sweep GC freed 25098(1224KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 2.287ms total 52.400ms
04-07 21:52:15.482   740   846 D ConnectivityService: listenForNetwork for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-07 21:52:15.482   740   866 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-07 21:52:15.482   740   866 D ConnectivityService: apparently satisfied.  currentScore=60
,04-07 21:52:15.484  3422  3476 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-07 21:52:15.618   178   178 D SurfaceFlinger: shader cache generated - 24 shaders in 165.795776 ms
,04-07 21:52:15.656  3422  3474 I OpenGLRenderer: Initialized EGL, version 1.4
,04-07 21:52:15.658  3422  3474 D OpenGLRenderer: Enabling debug mode 0
,04-07 21:52:15.731  1096  1096 I Keyboard.Facilitator: onFinishInput()
,04-07 21:52:15.738   740   833 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +703ms
,04-07 21:52:15.743  3422  3481 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,04-07 21:52:15.776  3422  3422 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3422
,04-07 21:52:15.943  3422  3422 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-07 21:52:16.048  3422  3494 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362694016
,04-07 21:52:16.051  3422  3494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-07 21:52:16.051  3422  3494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-07 21:52:16.051  3422  3494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-07 21:52:16.051  3422  3494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-07 21:52:16.051  3422  3494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-07 21:52:16.051  3422  3494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c9ceced added. We now have 1 listener(s)
,04-07 21:52:16.052   740  1245 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-07 21:52:16.054  3422  3494 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
04-07 21:52:16.055  3422  3494 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,04-07 21:52:16.056  3422  3494 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
04-07 21:52:16.056  3422  3494 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-07 21:52:16.060  3422  3494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@faeb770 added. We now have 1 listener(s)
04-07 21:52:16.060  3422  3494 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-07 21:52:16.062  3422  3494 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,04-07 21:52:16.064  3422  3494 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
04-07 21:52:16.064  3422  3494 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,04-07 21:52:16.066  3422  3494 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,04-07 21:52:16.066   740  1245 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-07 21:52:16.067  3422  3494 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,04-07 21:52:16.076  3422  3494 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-07 21:52:16.076  3422  3494 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-07 21:52:16.076  3422  3494 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-07 21:52:16.076  3422  3494 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-07 21:52:16.076  3422  3494 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-07 21:52:16.076  3422  3494 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-07 21:52:16.076  3422  3494 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-07 21:52:16.076  3422  3494 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-07 21:52:16.076  3422  3494 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-07 21:52:16.076  3422  3494 D io.jxcore.node.ConnectivityMonitor: start: OK
04-07 21:52:16.076  3422  3494 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-07 21:52:16.078  3422  3422 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-07 21:52:16.080  3422  3422 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-07 21:52:16.122  3422  3422 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-07 21:52:16.754  3422  3496 W jxcore-log: Initializing JXcore engine
04-07 21:52:16.754  3422  3496 W jxcore-log: JXcore engine is ready
,04-07 21:52:16.814  3496  3496 W Thread-347: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[8124]" dev="sockfs" ino=8124 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-07 21:52:16.814  3496  3496 W Thread-347: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
04-07 21:52:16.814  3496  3496 W Thread-347: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8372]" dev="sockfs" ino=8372 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-07 21:52:16.814  3496  3496 W Thread-347: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[16304]" dev="sockfs" ino=16304 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,04-07 21:52:16.829  3422  3496 W jxcore-log: Starting JXcore engine
,04-07 21:52:16.916  3422  3496 W jxcore-log: Platform android
04-07 21:52:16.916  3422  3496 W jxcore-log: 
04-07 21:52:16.916  3422  3496 W jxcore-log: Process ARCH arm
04-07 21:52:16.916  3422  3496 W jxcore-log: 
,04-07 21:52:17.118  3422  3496 I jxcore-log: JXcore Cordova bridge is ready!
04-07 21:52:17.118  3422  3496 I jxcore-log: 
04-07 21:52:17.118  3422  3496 W jxcore-log: JXcore engine is started
,04-07 21:52:17.124  3422  3494 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-07 21:52:17.125  3422  3422 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-07 21:52:19.797  3253  3276 W Babel   : aye TOOK TOO LONG! (15030ms > 10000ms)
,04-07 21:52:19.798  3253  3274 W Babel   : aye TOOK TOO LONG! (15035ms > 10000ms)
,04-07 21:52:19.802   740  1022 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-07 21:52:19.806   740  1245 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-07 21:52:19.809  3253  3253 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
04-07 21:52:19.809  3253  3253 W Babel   : BAM#gBA: invalid account id: -1
04-07 21:52:19.809  3253  3253 W Babel   : BAM#gBA: invalid account id: -1
04-07 21:52:19.809  3253  3253 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,04-07 21:52:19.811   740   756 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-07 21:52:19.813   740  1285 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-07 21:52:19.878  3253  3296 W Babel   : aye TOOK TOO LONG! (15039ms > 10000ms)
,04-07 21:52:19.947  1518  1613 I Finsky  : [118] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-07 21:52:19.948  1518  1518 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-07 21:52:20.241  1560  1571 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,04-07 21:52:22.183  1518  1518 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(151): Beginning daily hygiene
,04-07 21:52:22.204  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:52:22.212  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:52:22.214  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:52:22.756  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:52:22.895  1518  1518 I Finsky  : [1] com.google.android.finsky.m.e.a(156): Skipping DFE self-update. Local Version [80631600] >= Server Version [-1]
,04-07 21:52:22.945  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:52:22.982   740  1124 I ActivityManager: Start proc 3537:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,04-07 21:52:23.011  3537  3537 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-07 21:52:23.011  3537  3537 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-07 21:52:23.049  3537  3537 I MultiDex: VM with version 2.1.0 has multidex support
,04-07 21:52:23.049  3537  3537 I MultiDex: install
04-07 21:52:23.049  3537  3537 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-07 21:52:23.069  3537  3537 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,04-07 21:52:23.101  3537  3537 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-07 21:52:23.113  3537  3537 D ChimeraCfgMgr: Reading stored module config
,04-07 21:52:23.120  1622  1622 D WearableService: callingUid 10007, callindPid: 1622
04-07 21:52:23.121  1622  1622 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-07 21:52:23.125  1560  3568 D LocationInitializer: Restart initialization of location
,04-07 21:52:23.126  1622  2489 E MDM     : [192] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,04-07 21:52:23.129  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:52:23.147  1622  1695 W GCoreFlp: No location to return for getLastLocation()
,04-07 21:52:23.148  1622  3572 W FusedLocationProvider: location=null
,04-07 21:52:23.207  3537  3567 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,04-07 21:52:23.235  3537  3537 D CAR.SERVICE: Connecting to CarCallService...
,04-07 21:52:23.245  3537  3537 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
04-07 21:52:23.246  3537  3537 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-07 21:52:23.251  3537  3537 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,04-07 21:52:23.254  3537  3537 D CAR.TEL.Service: Creating a new CarCallService.
,04-07 21:52:23.255  3537  3537 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,04-07 21:52:23.256   740   846 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
04-07 21:52:23.257  3537  3537 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@3fbbbcd2
,04-07 21:52:23.257   740  1123 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
04-07 21:52:23.257  3537  3537 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
,04-07 21:52:23.257  3537  3537 D CAR.TEL.Service: Starting CarCallService with initial phone null
,04-07 21:52:23.361  3537  3552 D CAR.SERVICE: Package validated; name: com.android.vending
,04-07 21:52:23.888  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:52:24.279  1518  1518 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(9405): Logging device features
,04-07 21:52:24.296   740  3225 I ActivityManager: Killing 2924:com.android.settings/1000 (adj 15): empty #17
,04-07 21:52:24.304   740   865 D WifiService: Client connection lost with reason: 4
,04-07 21:52:24.387  1622  1716 D DeviceConnectionService: client connected with version: 8298000
,04-07 21:52:24.391  1518  1518 E Finsky  : [1] com.google.android.finsky.wear.bf.a(728): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
04-07 21:52:24.392  1518  1518 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6337): Dropping command=hygiene due to Gms not connected
,04-07 21:52:26.311  3422  3496 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-07 21:52:26.311  3422  3496 I jxcore-log: 
,04-07 21:52:26.313  3422  3496 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-07 21:52:26.313  3422  3496 I jxcore-log: 
,04-07 21:52:26.317  3422  3496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-07 21:52:26.317  3422  3496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-07 21:52:26.317  3422  3496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-07 21:52:26.317  3422  3496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-07 21:52:26.317  3422  3496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-07 21:52:26.317  3422  3496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-07 21:52:26.317  3422  3496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-07 21:52:26.317  3422  3496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-07 21:52:26.319  3422  3496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,04-07 21:52:26.321  3422  3496 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-07 21:52:26.321  3422  3496 I jxcore-log: 
04-07 21:52:26.322  3422  3496 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-07 21:52:26.322  3422  3496 I jxcore-log: 
,04-07 21:52:26.802  3422  3496 I jxcore-log: Unit Test app is loaded
04-07 21:52:26.802  3422  3496 I jxcore-log: 
,04-07 21:52:26.809  3422  3422 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-07 21:52:26.811  3422  3496 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-07 21:52:26.811  3422  3496 I jxcore-log: 
,04-07 21:52:26.815  3422  3496 I jxcore-log: My device name is: LGE-Nexus 5
04-07 21:52:26.815  3422  3496 I jxcore-log: 
,04-07 21:52:27.086   740   864 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
04-07 21:52:27.086   740   864 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-07 21:52:28.147   740  1285 I ActivityManager: Killing 2365:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
,04-07 21:52:28.421  3537  3537 D CAR.SERVICE: mConnectedToCar = false, abort
,04-07 21:52:28.424   740  1285 I ActivityManager: Killing 3045:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,04-07 21:52:28.434  3537  3537 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@17a6987a that was originally bound here
04-07 21:52:28.434  3537  3537 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@17a6987a that was originally bound here
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-07 21:52:28.434  3537  3537 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-07 21:52:28.569  3537  3537 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@279feb5d that was originally bound here
04-07 21:52:28.569  3537  3537 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@279feb5d that was originally bound here
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-07 21:52:28.569  3537  3537 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-07 21:52:28.570   740  3225 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@9e2d0a9
,04-07 21:52:29.312  1518  3613 I Finsky  : [132] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-07 21:52:29.326  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:52:29.333  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:52:29.335  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:52:30.503  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-07 21:52:30.503  3422  3496 I jxcore-log: 
,04-07 21:52:30.844  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-07 21:52:30.844  3422  3496 I jxcore-log: 
,04-07 21:52:30.868  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-07 21:52:30.868  3422  3496 I jxcore-log: 
,04-07 21:52:30.872  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-07 21:52:30.872  3422  3496 I jxcore-log: 
,04-07 21:52:30.887  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-07 21:52:30.887  3422  3496 I jxcore-log: 
,04-07 21:52:30.891  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-07 21:52:30.891  3422  3496 I jxcore-log: 
,04-07 21:52:31.665  1560  3633 V CheckinService: No Subscriptions found on the device
,04-07 21:52:31.667  1560  3633 I CheckinService: Checking schedule, now: 1460058751667 next: 1460058750614
,04-07 21:52:31.667  1560  3633 I CheckinService: active receiver: enabled
,04-07 21:52:31.685  1560  3633 I CheckinService: Preparing to send checkin request
04-07 21:52:31.685  1560  3633 I EventLogService: Accumulating logs since 1460058718522
,04-07 21:52:31.699  1560  3633 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,04-07 21:52:31.700  1560  3633 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,04-07 21:52:31.779  1560  3633 V CheckinRequestBuilder: No Subscriptions found on the device
,04-07 21:52:31.835   190   871 D WVCdm   : Instantiating CDM.
,04-07 21:52:31.835   190   872 I WVCdm   : CdmEngine::OpenSession
04-07 21:52:31.836   190   872 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,04-07 21:52:31.859   190   872 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
04-07 21:52:31.860   190   872 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
,04-07 21:52:31.860   190   872 D DrmWidevineDash: Service_Initialize: starts!
04-07 21:52:31.860   190   872 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
04-07 21:52:31.860   190   872 D QSEECOMAPI: : App is not loaded in QSEE
,04-07 21:52:31.874   190   872 D QSEECOMAPI: : Loaded image: APP id = 3
,04-07 21:52:31.875   190   872 D DrmWidevineDash: Service_Initialize: ends! returns 0
04-07 21:52:31.875   190   872 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb417d000
04-07 21:52:31.875   190   872 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb417d000
,04-07 21:52:31.884   190   872 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
04-07 21:52:31.884   190   872 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,04-07 21:52:31.889   190   872 D DrmWidevineDash: hlos api version =  9
04-07 21:52:31.889   190   872 D DrmWidevineDash: tz api version =  9
04-07 21:52:31.889   190   872 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
04-07 21:52:31.889   190   872 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,04-07 21:52:31.900   190   872 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
04-07 21:52:31.900   190   872 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
04-07 21:52:31.900   190   872 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb43ff940
,04-07 21:52:31.905   190   872 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
04-07 21:52:31.905   190   872 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
04-07 21:52:31.906   190   872 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb4c267a8, dataLength=8
,04-07 21:52:31.911   190   872 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,04-07 21:52:31.912   190   872 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb58b5000, wrapped_rsa_key_length=1280
,04-07 21:52:31.918   190   872 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
04-07 21:52:31.918   190   872 I WVCdm   : CdmEngine::QueryKeyControlInfo
,04-07 21:52:31.919   190   190 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
04-07 21:52:31.919   190   190 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
04-07 21:52:31.919   190   190 I WVCdm   : CdmEngine::GenerateKeyRequest
04-07 21:52:31.919   190   190 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb583ec60, idLength=0xbe99a2f0
,04-07 21:52:31.929   190   190 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
04-07 21:52:31.929   190   190 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,04-07 21:52:31.934   190   190 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
04-07 21:52:31.934   190   190 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 21
04-07 21:52:31.934   190   190 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
04-07 21:52:31.934   190   190 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
,04-07 21:52:31.939   190   190 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
04-07 21:52:31.939   190   190 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,04-07 21:52:31.944   190   190 D DrmWidevineDash: hlos api version =  9
04-07 21:52:31.944   190   190 D DrmWidevineDash: tz api version =  9
04-07 21:52:31.944   190   190 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
04-07 21:52:31.944   190   190 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,04-07 21:52:31.946  2774  2793 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-07 21:52:31.950   190   190 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
04-07 21:52:31.950   190   190 D WVCdm   : PrepareKeyRequest: nonce=351216304
04-07 21:52:31.950   190   190 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb58cb900
04-07 21:52:31.950   190   190 D DrmWidevineDash: message_length=1618, signature=0xb587f5c0, signature_length=3197739732
,04-07 21:52:32.019   190   190 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,04-07 21:52:32.020   190   871 I WVCdm   : CdmEngine::CloseSession
04-07 21:52:32.020   190   871 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,04-07 21:52:32.025   190   871 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
04-07 21:52:32.025   190   871 I WVCdm   : L3 Terminate.
04-07 21:52:32.025   190   871 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,04-07 21:52:32.029   190   871 D DrmWidevineDash: Service_Uninitialize: starts!
04-07 21:52:32.029   190   871 D QSEECOMAPI: : QSEECom_dealloc_memory 
04-07 21:52:32.029   190   871 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
04-07 21:52:32.030   190   871 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
04-07 21:52:32.030   190   871 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,04-07 21:52:32.070  2774  2793 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-07 21:52:32.109  2774  2793 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-07 21:52:32.149   190   190 I WVCdm   : CdmEngine::OpenSession
04-07 21:52:32.149   190   190 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,04-07 21:52:32.167   190   190 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,04-07 21:52:32.167   190   190 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
,04-07 21:52:32.168   190   190 D DrmWidevineDash: Service_Initialize: starts!
04-07 21:52:32.168   190   190 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
04-07 21:52:32.168   190   190 D QSEECOMAPI: : App is not loaded in QSEE
,04-07 21:52:32.179   190   190 D QSEECOMAPI: : Loaded image: APP id = 3
,04-07 21:52:32.179   190   190 D DrmWidevineDash: Service_Initialize: ends! returns 0
04-07 21:52:32.179   190   190 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb417d000
,04-07 21:52:32.179   190   190 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb417d000
,04-07 21:52:32.187   190   190 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
04-07 21:52:32.187   190   190 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,04-07 21:52:32.192   190   190 D DrmWidevineDash: hlos api version =  9
,04-07 21:52:32.192   190   190 D DrmWidevineDash: tz api version =  9
04-07 21:52:32.192   190   190 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
04-07 21:52:32.192   190   190 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,04-07 21:52:32.201   190   190 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0,
04-07 21:52:32.201   190   190 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
04-07 21:52:32.201   190   190 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbe99a520
,04-07 21:52:32.206   190   190 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
04-07 21:52:32.206   190   190 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,04-07 21:52:32.206   190   190 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb4c26dc8, dataLength=8
,04-07 21:52:32.210   190   190 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,04-07 21:52:32.213   190   190 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb58b2000, wrapped_rsa_key_length=1280
,04-07 21:52:32.220   190   190 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,04-07 21:52:32.220   190   190 I WVCdm   : CdmEngine::QueryKeyControlInfo
,04-07 21:52:32.221   190   851 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
04-07 21:52:32.221   190   851 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
04-07 21:52:32.221   190   851 I WVCdm   : CdmEngine::GenerateKeyRequest
04-07 21:52:32.221   190   851 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb583ec80, idLength=0xb49ff710,
,04-07 21:52:32.232   190   851 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
04-07 21:52:32.232   190   851 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,04-07 21:52:32.237   190   851 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,04-07 21:52:32.237   190   851 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 21
04-07 21:52:32.237   190   851 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
04-07 21:52:32.237   190   851 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!,
,04-07 21:52:32.242   190   851 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0,
04-07 21:52:32.242   190   851 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,04-07 21:52:32.247   190   851 D DrmWidevineDash: hlos api version =  9,
04-07 21:52:32.247   190   851 D DrmWidevineDash: tz api version =  9
04-07 21:52:32.247   190   851 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
04-07 21:52:32.247   190   851 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,04-07 21:52:32.252   190   851 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0,
04-07 21:52:32.252   190   851 D WVCdm   : PrepareKeyRequest: nonce=3441969180
04-07 21:52:32.252   190   851 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb58c9d00
04-07 21:52:32.252   190   851 D DrmWidevineDash: message_length=1649, signature=0xb4c64f00, signature_length=3030382324,
,04-07 21:52:32.339   190   851 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,04-07 21:52:32.340   190   872 I WVCdm   : CdmEngine::CloseSession
04-07 21:52:32.340   190   872 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,04-07 21:52:32.344   190   872 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
04-07 21:52:32.344   190   872 I WVCdm   : L3 Terminate.
04-07 21:52:32.344   190   872 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,04-07 21:52:32.349   190   872 D DrmWidevineDash: Service_Uninitialize: starts!
04-07 21:52:32.349   190   872 D QSEECOMAPI: : QSEECom_dealloc_memory 
04-07 21:52:32.349   190   872 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,04-07 21:52:32.350   190   872 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
04-07 21:52:32.350   190   872 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,04-07 21:52:32.587  1560  3633 I CheckinTask: Sending checkin request (8063 bytes)
,04-07 21:52:32.889  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-07 21:52:32.889  3422  3496 I jxcore-log: 
,04-07 21:52:32.900  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-07 21:52:32.900  3422  3496 I jxcore-log: 
,04-07 21:52:32.909  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-07 21:52:32.909  3422  3496 I jxcore-log: 
,04-07 21:52:33.060  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-07 21:52:33.060  3422  3496 I jxcore-log: 
,04-07 21:52:33.133  1560  3633 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,04-07 21:52:33.134  1560  3633 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,04-07 21:52:33.235  1560  3633 I art     : WaitForGcToComplete blocked for 6.429ms for cause DisableMovingGc
,04-07 21:52:33.296   740  1291 I art     : Explicit concurrent mark sweep GC freed 27794(1285KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 1.370ms total 52.342ms
,04-07 21:52:33.344  1560  3633 V CheckinRequestBuilder: No Subscriptions found on the device
,04-07 21:52:33.377  1560  3633 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,04-07 21:52:33.379  1560  3633 V CheckinService: No Subscriptions found on the device
,04-07 21:52:33.380  1560  3633 I CheckinService: Checking schedule, now: 1460058753380 next: 1460101242377
04-07 21:52:33.380  1560  3633 I CheckinService: active receiver: disabled
,04-07 21:52:33.407  1560  1560 D CheckinService: Recording last checkin time for package unspecified as 1460058753407
,04-07 21:52:33.456  1622  3227 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,04-07 21:52:33.994  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-07 21:52:33.994  3422  3496 I jxcore-log: 
,04-07 21:52:34.051  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-07 21:52:34.051  3422  3496 I jxcore-log: 
04-07 21:52:34.057  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
04-07 21:52:34.057  3422  3496 I jxcore-log: 
,04-07 21:52:34.190  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-07 21:52:34.190  3422  3496 I jxcore-log: 
,04-07 21:52:34.211  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-07 21:52:34.211  3422  3496 I jxcore-log: 
04-07 21:52:34.215  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-07 21:52:34.215  3422  3496 I jxcore-log: 
,04-07 21:52:34.220  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-07 21:52:34.220  3422  3496 I jxcore-log: 
,04-07 21:52:34.235  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-07 21:52:34.235  3422  3496 I jxcore-log: 
,04-07 21:52:34.254  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-07 21:52:34.254  3422  3496 I jxcore-log: 
,04-07 21:52:34.340  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-07 21:52:34.340  3422  3496 I jxcore-log: 
,04-07 21:52:34.345  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-07 21:52:34.345  3422  3496 I jxcore-log: 
,04-07 21:52:34.369  3422  3496 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-07 21:52:34.369  3422  3496 I jxcore-log: 
,04-07 21:52:34.390  3422  3496 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
04-07 21:52:34.391  3422  3496 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
04-07 21:52:34.391  3422  3496 I jxcore-log: 
,04-07 21:52:38.899  1518  1613 I Finsky  : [118] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-07 21:52:38.900  1518  1518 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-07 21:52:41.749   740   856 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-07 21:52:41.806  3253  3253 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,04-07 21:52:41.822  3253  3253 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-07 21:52:41.822  3253  3253 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-07 21:52:41.829  3253  3708 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,04-07 21:52:41.831  3253  3708 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,04-07 21:52:41.832   740   740 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
04-07 21:52:41.832   740   740 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
04-07 21:52:41.833  1560  3710 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
04-07 21:52:41.833  1560  3710 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,04-07 21:52:41.835   740   740 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
04-07 21:52:41.835  3253  3253 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,04-07 21:52:41.845  1560  1648 I Icing   : updateResources: need to parse f{com.google.android.gms}
,04-07 21:52:41.845  1560  3710 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,04-07 21:52:41.855   740   740 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,04-07 21:52:41.856   740   740 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@105f9175
,04-07 21:52:41.863  1407  3717 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,04-07 21:52:41.881  1622  1622 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,04-07 21:52:41.896  1407  3717 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 33 ms] updated apps [took 33 ms] 
,04-07 21:52:41.922  1622  1695 W GCoreFlp: No location to return for getLastLocation()
,04-07 21:52:42.039  1292  1442 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-07 21:52:43.004  1560  1648 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,04-07 21:52:43.079  1560  1648 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,04-07 21:52:46.840  3253  3253 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,04-07 21:52:47.087   740   864 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
,04-07 21:53:04.668  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:53:04.672  1622  3747 I VacuumService: Vacuum at: now=1460058784672 tag=VacuumService
,04-07 21:53:05.017   740   828 W ProcessCpuTracker: Skipping unknown process pid 3735
04-07 21:53:05.017   740   828 W ProcessCpuTracker: Skipping unknown process pid 3738
,04-07 21:53:07.093   740   864 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
04-07 21:53:07.093   740   864 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-07 21:53:15.735  1096  1334 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-07 21:53:15.735  1096  1334 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-07 21:53:27.097   740   864 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
,04-07 21:53:27.101   740   864 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-07 21:53:45.664   740   835 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,04-07 21:53:45.674   740   835 I PowerManagerService: Sleeping (uid 1000)...
,04-07 21:53:45.723   740   835 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-07 21:53:45.733   190   190 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-07 21:53:45.743   740   864 E WifiStateMachine: cancelDelayedScan -> 11
,04-07 21:53:45.746   740   864 E native  : do suspend false
,04-07 21:53:45.755   178  1492 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (104 us)
,04-07 21:53:45.885  2036  2105 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-07 21:53:45.903  2036  2105 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-07 21:53:45.989  1096  1096 I Keyboard.Facilitator: onFinishInput()
,04-07 21:53:45.990   190   871 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,04-07 21:53:46.000   740   864 E WifiStateMachine: cancelDelayedScan -> 13
,04-07 21:53:46.004   740   864 E native  : do suspend true
,04-07 21:53:46.247   740   864 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
04-07 21:53:46.247   740   864 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,04-07 21:53:46.371   740   833 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,04-07 21:53:46.375   740   740 V ActivityManager: Display changed displayId=0
,04-07 21:53:46.406   178   178 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
,04-07 21:53:46.406   178   178 D qdhwcomposer: hwc_blank: Blanking display: 0
,04-07 21:53:46.510   182   182 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
04-07 21:53:46.510   182   182 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
04-07 21:53:46.510   182   182 I rmt_storage: wakelock acquired: 1, error no: 2
04-07 21:53:46.510   182   573 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236802816)
,04-07 21:53:46.583   182   573 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
04-07 21:53:46.583   182   573 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
04-07 21:53:46.583   182   573 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236802816) wakelock released: 1, error no: 0
04-07 21:53:46.583   182   573 I rmt_storage: 
,04-07 21:53:46.585   182   182 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,04-07 21:53:46.678   178   178 D qdhwcomposer: hwc_blank: Done blanking display: 0
04-07 21:53:46.678   740   881 D SurfaceControl: Excessive delay in setPowerMode(): 272ms
04-07 21:53:46.679  1750  1754 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,04-07 21:53:46.700  3422  3422 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
04-07 21:53:46.700  3422  3422 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,04-07 21:53:46.732  3422  3422 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1526851a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3c554492, 16908290=android.view.AbsSavedState$1@3c554492}, android:focusedViewId=100}]}]
04-07 21:53:46.733  3422  3422 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
04-07 21:53:46.733  3422  3422 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
04-07 21:53:46.733  3422  3422 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,04-07 21:53:47.101   740   864 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-45
04-07 21:53:47.101   740   864 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,04-07 21:54:16.144  1622  1635 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34a85408)
04-07 21:54:16.144  1622  1635 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3b7667a1)
04-07 21:54:16.144  1622  1635 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c835dc6)
04-07 21:54:16.144  1622  1635 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7a57187)
04-07 21:54:16.145  1622  1635 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3f72a8b4)
,04-07 21:54:16.155  1622  1622 I art     : Explicit concurrent mark sweep GC freed 57386(3MB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 22MB/37MB, paused 1.120ms total 37.360ms
,04-07 21:54:16.814  1622  3804 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 7178 seconds from now (1460058856814)
,04-07 21:54:16.888  1622  3795 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,04-07 21:54:16.892  1622  3795 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-07 21:54:18.214  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:54:18.215  1622  1622 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-07 21:54:31.793  1622  1993 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,04-07 21:54:36.696  3422  3496 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-07 21:54:36.696  3422  3496 I jxcore-log: 
,04-07 21:54:37.056  3849  3849 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-07 21:54:37.062  3849  3849 D AndroidRuntime: CheckJNI is OFF
,04-07 21:54:37.198  3849  3849 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-07 21:54:37.204   740   828 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
04-07 21:54:37.205   740   828 I ActivityManager: Killing 3422:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,04-07 21:54:37.238   740   839 W PackageSettings: Skipping PackageSetting{1722ccf6 com.example.hello/10116} due to missing metadata
,04-07 21:54:37.243   740  3225 I WindowState: WIN DEATH: Window{33c30d1a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,04-07 21:54:37.243   740  1124 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@d2455b1)
,04-07 21:54:37.243   740   866 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-07 21:54:37.243   740   865 D WifiService: Client connection lost with reason: 4
04-07 21:54:37.243   740   866 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-07 21:54:37.425   740   828 I ActivityManager:   Force finishing activity 3 ActivityRecord{2a85898 u0 com.test.thalitest/.MainActivity t19}
,04-07 21:54:37.428   740   755 W ActivityManager: Spurious death for ProcessRecord{227a9a96 3422:com.test.thalitest/u0a49}, curProc for 3422: null
04-07 21:54:37.428   740   839 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
04-07 21:54:37.429   740   839 I ActivityManager:   Force finishing activity 3 ActivityRecord{2a85898 u0 com.test.thalitest/.MainActivity t19 f}
04-07 21:54:37.429   740   839 W ActivityManager: Duplicate finish request for ActivityRecord{2a85898 u0 com.test.thalitest/.MainActivity t19 f}
,04-07 21:54:37.477   904   904 I art     : Explicit concurrent mark sweep GC freed 42571(1752KB) AllocSpace objects, 2(27KB) LOS objects, 21% free, 58MB/74MB, paused 695us total 26.848ms
,04-07 21:54:37.514  1560  1560 I art     : Explicit concurrent mark sweep GC freed 21089(1303KB) AllocSpace objects, 8(128KB) LOS objects, 24% free, 23MB/30MB, paused 10.581ms total 69.794ms
,04-07 21:54:37.516  1292  1292 I art     : Explicit concurrent mark sweep GC freed 3945(214KB) AllocSpace objects, 6(512KB) LOS objects, 38% free, 25MB/41MB, paused 1.279ms total 70.409ms
,04-07 21:54:37.517   740   883 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,04-07 21:54:37.517   740   883 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,04-07 21:54:37.520  1407  1407 I art     : Explicit concurrent mark sweep GC freed 9113(612KB) AllocSpace objects, 7(154KB) LOS objects, 24% free, 21MB/29MB, paused 439us total 85.660ms
,04-07 21:54:37.523  1096  1096 I Keyboard.Facilitator: resetDictionaries() : en_US
04-07 21:54:37.523   740   856 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-07 21:54:37.526  1622  1702 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,04-07 21:54:37.529  1096  3882 I Keyboard.Facilitator.DecoderInitializer: run()
,04-07 21:54:37.535  1355  3884 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,04-07 21:54:37.555   740   846 I ActivityManager: Start proc 3886:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,04-07 21:54:37.564  1096  3882 I Decoder : createOrResetDecoder
,04-07 21:54:37.567   201   201 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 201us total 10.816ms
,04-07 21:54:37.582   201   201 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 215us total 14.627ms
04-07 21:54:37.583   740   740 I art     : Explicit concurrent mark sweep GC freed 63354(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 29MB/44MB, paused 2.697ms total 125.209ms
,04-07 21:54:37.584   740   839 I art     : WaitForGcToComplete blocked for 55.409ms for cause Explicit
,04-07 21:54:37.594   201   201 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 379us total 11.738ms
,04-07 21:54:37.615  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-07 21:54:37.625  1518  1518 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(268): Wear auto uninstall disabled for package com.test.thalitest
,04-07 21:54:37.627  1096  3882 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,04-07 21:54:37.635  1560  3906 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,04-07 21:54:37.636  1560  3906 D AccountUtils: Clearing selected account for com.test.thalitest
,04-07 21:54:37.647  1560  3906 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,04-07 21:54:37.657  1096  3882 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,04-07 21:54:37.658  1096  3882 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
04-07 21:54:37.658  1096  3882 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,04-07 21:54:37.660  1096  3882 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
04-07 21:54:37.660  1096  3882 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,04-07 21:54:37.661  1096  3882 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,04-07 21:54:37.661   740   740 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-07 21:54:37.661   740   740 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,04-07 21:54:37.663  1096  3882 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
04-07 21:54:37.664  1096  3882 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-07 21:54:37.664  1096  3882 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-07 21:54:37.664  1096  3882 I Keyboard.Facilitator.Delight2FileSweeper: run()
,04-07 21:54:37.665  1096  3882 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-07 21:54:37.665  1096  3882 I StatsUtilsManager: startPeriodStatsRecorder() : Success
04-07 21:54:37.665  1096  3882 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
04-07 21:54:37.665  1622  1622 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-07 21:54:37.665  1622  1622 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-07 21:54:37.675   740  1022 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3422 uid 10049
,04-07 21:54:37.681  1096  1096 I Keyboard.Facilitator: onFinishInput()
,04-07 21:54:37.695  1292  1292 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-07 21:54:37.700  1407  3916 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,04-07 21:54:37.728   740   740 I ActivityManager: Start proc 3918:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,04-07 21:54:37.745  1560  3913 W BaseAppContext: Using Auth Proxy for data requests.
,04-07 21:54:37.751  1560  3913 W BaseAppContext: Using Auth Proxy for data requests.
,04-07 21:54:37.754   740   839 I art     : Explicit concurrent mark sweep GC freed 14052(1101KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 29MB/44MB, paused 3.673ms total 168.568ms
,04-07 21:54:37.754  1560  3906 I GMPM-SVC: App measurement is starting up, version: 8703
04-07 21:54:37.754  1560  3906 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,04-07 21:54:37.781  1560  3906 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,04-07 21:54:37.788  1560  1648 I Icing   : doRemovePackageData com.test.thalitest
,04-07 21:54:37.842  1560  3943 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
04-07 21:54:37.843  1560  3943 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
04-07 21:54:37.843  1560  3943 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
04-07 21:54:37.843  1560  3943 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,04-07 21:54:37.847   740  1291 I ActivityManager: Start proc 3948:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,04-07 21:54:37.852  1560  3943 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
04-07 21:54:37.852  1560  3943 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,04-07 21:54:37.853  1560  3943 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,04-07 21:54:37.856  3849  3849 I art     : System.exit called, status: 0
04-07 21:54:37.856  3849  3849 I AndroidRuntime: VM exiting with result code 0.
,04-07 21:54:37.867  1560  3943 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
04-07 21:54:37.867  1560  3943 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,04-07 21:54:37.868  1560  3943 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,04-07 21:54:37.868  1560  3943 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
04-07 21:54:37.869  1560  3943 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
04-07 21:54:37.869  1560  3943 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,04-07 21:54:37.874  1292  1442 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-07 21:54:37.913   740   839 I ActivityManager: Start proc 3966:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,04-07 21:54:37.933  1407  3916 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 233 ms] updated apps [took 233 ms] 
,04-07 21:54:37.935   740  3225 I ActivityManager: Killing 3307:com.google.android.apps.photos/u0a83 (adj 15): empty #17
,04-07 21:54:37.943  3948  3948 D ExternalStorage: After updating volumes, found 1 active roots
,04-07 21:54:37.969   740  1123 I ActivityManager: Killing 2401:com.google.android.calendar/u0a28 (adj 15): empty #17
,04-07 21:54:38.006   740  1245 I ActivityManager: Killing 2998:com.google.android.gm/u0a41 (adj 15): empty #17
,04-07 21:54:38.036   740  1245 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-07 21:54:38.036   740   866 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-07 21:54:38.036   740   866 D ConnectivityService: apparently satisfied.  currentScore=60
,04-07 21:54:38.038  1560  3990 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290

```
