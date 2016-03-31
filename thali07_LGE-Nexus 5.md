#### Test 646138038b5bc7c_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-31 17:39:10.134  1545  2579 I CheckinService: Done disabling old GoogleServicesFramework version
,03-31 17:39:10.388  3546  3546 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 17:39:10.391  3546  3546 D AndroidRuntime: CheckJNI is OFF
03-31 17:39:10.484  3546  3546 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-31 17:39:10.487   762  1099 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 17:39:10.493   762  1099 V WindowManager: addAppToken: AppWindowToken{163ef3e2 token=Token{278054ad ActivityRecord{26d8ddc4 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-31 17:39:10.498   762   835 V WindowManager: Adding window Window{2ac46c65 u0 Starting com.test.thalitest} at 2 of 7 (after Window{8149fee u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 17:39:10.501  3546  3546 D AndroidRuntime: Shutting down VM
03-31 17:39:10.507  1397  1414 W SearchService: Abort, client detached.
03-31 17:39:10.540   762  1193 I ActivityManager: Start proc 3567:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-31 17:39:10.558  1397  1397 I MicroDetector: Keeping mic open: false
03-31 17:39:10.558  1397  1603 I DeviceStateChecker: DeviceStateChecker cancelled
03-31 17:39:10.558  1397  1397 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@36775691
03-31 17:39:10.561  1397  1594 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
03-31 17:39:10.605   187  1608 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 17:39:10.605   187  1608 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 17:39:10.610  1397  1605 I MicroRecognitionRunner: Detection finished
03-31 17:39:10.612  1397  1602 I MicroRecognitionRunner: Stopping hotword detection.
03-31 17:39:10.636  3567  3567 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
03-31 17:39:10.648  3567  3567 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 1077-1078)
03-31 17:39:10.648  3567  3567 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 17:39:10.656  3567  3567 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1dc1fa78}
03-31 17:39:10.656  3567  3567 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 17:39:10.657  3567  3567 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 17:39:10.658   762  1099 I ActivityManager: Killing 3019:com.android.settings/1000 (adj 15): empty #17
03-31 17:39:10.665   762   869 D WifiService: Client connection lost with reason: 4
03-31 17:39:10.682  3567  3567 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
03-31 17:39:10.695  3567  3567 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-31 17:39:10.740  3567  3567 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-31 17:39:10.740  3567  3567 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-31 17:39:10.743   762   834 D BluetoothManagerService: Message: 20
03-31 17:39:10.744   762   834 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@327f87db:true
,03-31 17:39:10.778  3567  3567 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-31 17:39:10.778  3567  3567 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-31 17:39:10.790  3567  3567 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-31 17:39:10.796  3567  3567 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 17:39:10.797  3567  3567 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-31 17:39:10.807  3567  3567 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-31 17:39:10.828  3567  3623 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 17:39:10.834  3567  3567 D Atlas   : Validating map...
,03-31 17:39:10.838   762   777 V WindowManager: Adding window Window{321f4c66 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2ac46c65 u0 Starting com.test.thalitest})
,03-31 17:39:10.846   762   869 D WifiService: New client listening to asynchronous messages
,03-31 17:39:10.859   762   964 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 17:39:10.859   762   870 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 17:39:10.859   762   870 D ConnectivityService: apparently satisfied.  currentScore=60
,03-31 17:39:10.860  3567  3627 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 17:39:10.904  3567  3623 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 17:39:10.909  3567  3623 D OpenGLRenderer: Enabling debug mode 0
,03-31 17:39:10.993   762   835 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +474ms
,03-31 17:39:11.001  1100  1100 I Keyboard.Facilitator: onFinishInput()
,03-31 17:39:11.022  3567  3634 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-31 17:39:11.059  3567  3567 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3567
,03-31 17:39:11.189  3567  3567 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 17:39:11.280  3567  3639 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1263053952
,03-31 17:39:11.286  3567  3639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 17:39:11.286  3567  3639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 17:39:11.286  3567  3639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 17:39:11.286  3567  3639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 17:39:11.286  3567  3639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-31 17:39:11.286  3567  3639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24fc75ab added. We now have 1 listener(s)
03-31 17:39:11.286   762  2299 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 17:39:11.290  3567  3639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,03-31 17:39:11.293  3567  3639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-31 17:39:11.294  3567  3639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 17:39:11.294  3567  3639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-31 17:39:11.298  3567  3639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@286bedc6 added. We now have 1 listener(s)
03-31 17:39:11.298  3567  3639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 17:39:11.300  3567  3639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-31 17:39:11.302  3567  3639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,03-31 17:39:11.302  3567  3639 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-31 17:39:11.304  3567  3639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 17:39:11.305   762  2338 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 17:39:11.305  3567  3639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-31 17:39:11.310  3567  3639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:39:11.310  3567  3639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:39:11.310  3567  3639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 17:39:11.310  3567  3639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:39:11.310  3567  3639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:39:11.310  3567  3639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:39:11.310  3567  3639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:39:11.310  3567  3639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:39:11.310  3567  3639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 17:39:11.310  3567  3639 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 17:39:11.312  3567  3567 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 17:39:11.312  3567  3639 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 17:39:11.313  3567  3567 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 17:39:11.336  3567  3567 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 17:39:12.023  3567  3640 W jxcore-log: Initializing JXcore engine
03-31 17:39:12.023  3567  3640 W jxcore-log: JXcore engine is ready
,03-31 17:39:12.067  3640  3640 W Thread-352: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[6790]" dev="sockfs" ino=6790 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-31 17:39:12.067  3640  3640 W Thread-352: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,03-31 17:39:12.067  3640  3640 W Thread-352: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[7710]" dev="sockfs" ino=7710 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-31 17:39:12.067  3640  3640 W Thread-352: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[18158]" dev="sockfs" ino=18158 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-31 17:39:12.085  3567  3640 W jxcore-log: Starting JXcore engine
,03-31 17:39:12.212  3567  3640 W jxcore-log: Platform android
03-31 17:39:12.212  3567  3640 W jxcore-log: 
03-31 17:39:12.212  3567  3640 W jxcore-log: Process ARCH arm
03-31 17:39:12.212  3567  3640 W jxcore-log: 
,03-31 17:39:12.454  3567  3640 I jxcore-log: JXcore Cordova bridge is ready!
03-31 17:39:12.454  3567  3640 I jxcore-log: 
03-31 17:39:12.454  3567  3640 W jxcore-log: JXcore engine is started
,03-31 17:39:12.458  3567  3639 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 17:39:12.461  3567  3567 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 17:39:12.519  3295  3324 W Babel   : aye TOOK TOO LONG! (15019ms > 10000ms)
,03-31 17:39:12.520  3295  3322 W Babel   : aye TOOK TOO LONG! (15034ms > 10000ms)
,03-31 17:39:12.523   762  1098 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 17:39:12.527   762  1193 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 17:39:12.529  3295  3295 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-31 17:39:12.529  3295  3295 W Babel   : BAM#gBA: invalid account id: -1
03-31 17:39:12.530  3295  3295 W Babel   : BAM#gBA: invalid account id: -1
03-31 17:39:12.530  3295  3295 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-31 17:39:12.532   762  1099 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 17:39:12.533   762  3408 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 17:39:12.580  3295  3340 W Babel   : aye TOOK TOO LONG! (15035ms > 10000ms)
,03-31 17:39:12.639  1656  1759 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-31 17:39:12.640  1656  1656 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 17:39:15.714  1545  1556 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-31 17:39:19.887   762  1099 I ActivityManager: Killing 3121:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-31 17:39:19.950   762  1099 I ActivityManager: Killing 2654:com.google.android.keep/u0a52 (adj 15): empty #18
,03-31 17:39:21.352  1656  1656 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-31 17:39:21.372  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:39:21.383   762   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 17:39:21.383   762   868 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 17:39:21.439   762  1196 I art     : Explicit concurrent mark sweep GC freed 30502(1499KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.559ms total 51.567ms
,03-31 17:39:21.470  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:39:21.472  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:39:22.101  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:39:22.239  1656  1733 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-31 17:39:22.239  1656  1733 I qtaguid : Untagging socket 38 failed errno=-22
03-31 17:39:22.239  1656  1733 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-31 17:39:22.241  1656  1656 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-31 17:39:22.278  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:39:22.319   762  1099 I ActivityManager: Start proc 3708:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-31 17:39:22.328   198   198 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 194us total 8.358ms
,03-31 17:39:22.347   198   198 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 643us total 9.341ms
,03-31 17:39:22.366   198   198 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 197us total 17.703ms
,03-31 17:39:22.374  3708  3708 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 17:39:22.374  3708  3708 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 17:39:22.406  3708  3708 I MultiDex: VM with version 2.1.0 has multidex support
03-31 17:39:22.406  3708  3708 I MultiDex: install
03-31 17:39:22.406  3708  3708 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 17:39:22.420  3708  3708 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-31 17:39:22.453  3708  3708 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 17:39:22.467  1519  1519 D WearableService: callingUid 10007, callindPid: 1519
,03-31 17:39:22.473  1519  2058 E MDM     : [172] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-31 17:39:22.477  3708  3708 D ChimeraCfgMgr: Reading stored module config
,03-31 17:39:22.481  1519  1519 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 17:39:22.483  1545  3739 D LocationInitializer: Restart initialization of location
,03-31 17:39:22.492  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:39:22.512  1519  1616 W GCoreFlp: No location to return for getLastLocation()
03-31 17:39:22.513  1519  3742 W FusedLocationProvider: location=null
,03-31 17:39:22.570  3708  3738 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-31 17:39:22.606  3708  3708 D CAR.SERVICE: Connecting to CarCallService...
,03-31 17:39:22.618  3708  3708 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 17:39:22.618  3708  3708 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 17:39:22.623  3708  3708 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-31 17:39:22.628  3708  3708 D CAR.TEL.Service: Creating a new CarCallService.
,03-31 17:39:22.629  3708  3708 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-31 17:39:22.631   762  1098 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-31 17:39:22.631  3708  3708 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@77c4b11
03-31 17:39:22.631   762   777 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-31 17:39:22.631  3708  3708 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
,03-31 17:39:22.631  3708  3708 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-31 17:39:22.691  3708  3729 D CAR.SERVICE: Package validated; name: com.android.vending
,03-31 17:39:22.707  1656  1735 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-31 17:39:22.707  1656  1735 I qtaguid : Untagging socket 38 failed errno=-22
03-31 17:39:22.707  1656  1735 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-31 17:39:23.195  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:39:23.576  1656  1733 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-31 17:39:23.576  1656  1733 I qtaguid : Untagging socket 38 failed errno=-22
03-31 17:39:23.576  1656  1733 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-31 17:39:23.658  1656  1656 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,03-31 17:39:23.685  1519  1647 D DeviceConnectionService: client connected with version: 8298000
,03-31 17:39:23.699  1656  1656 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-31 17:39:23.699  1656  1656 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,03-31 17:39:24.828  3567  3640 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 17:39:24.828  3567  3640 I jxcore-log: 
,03-31 17:39:24.831  3567  3640 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 17:39:24.831  3567  3640 I jxcore-log: 
,03-31 17:39:24.835  3567  3640 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 17:39:24.835  3567  3640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 17:39:24.835  3567  3640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 17:39:24.835  3567  3640 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 17:39:24.835  3567  3640 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 17:39:24.835  3567  3640 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 17:39:24.835  3567  3640 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 17:39:24.835  3567  3640 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 17:39:24.837  3567  3640 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 17:39:24.839  3567  3640 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 17:39:24.839  3567  3640 I jxcore-log: 
,03-31 17:39:24.841  3567  3640 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 17:39:24.841  3567  3640 I jxcore-log: 
,03-31 17:39:24.911  1656  3762 I Finsky  : [145] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-31 17:39:24.918  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:39:25.486  3567  3640 I jxcore-log: Unit Test app is loaded
03-31 17:39:25.486  3567  3640 I jxcore-log: 
,03-31 17:39:25.493  3567  3640 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 17:39:25.493  3567  3640 I jxcore-log: 
,03-31 17:39:25.495  3567  3567 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 17:39:25.498  3567  3640 I jxcore-log: My device name is: LGE-Nexus 5
03-31 17:39:25.498  3567  3640 I jxcore-log: 
,03-31 17:39:27.752  3708  3708 D CAR.SERVICE: mConnectedToCar = false, abort
,03-31 17:39:27.754   762   777 I ActivityManager: Killing 3141:com.android.musicfx/u0a13 (adj 15): empty #17
,03-31 17:39:27.763  3708  3708 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@22de39d9 that was originally bound here
03-31 17:39:27.763  3708  3708 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@22de39d9 that was originally bound here
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-31 17:39:27.763  3708  3708 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,03-31 17:39:27.836  3708  3708 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@16b2df38 that was originally bound here
03-31 17:39:27.836  3708  3708 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@16b2df38 that was originally bound here
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-31 17:39:27.836  3708  3708 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,03-31 17:39:27.837   762  1099 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@27d84bf8
,03-31 17:39:30.521  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 17:39:30.521  3567  3640 I jxcore-log: 
,03-31 17:39:30.996  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 17:39:30.996  3567  3640 I jxcore-log: 
,03-31 17:39:31.010  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 17:39:31.010  3567  3640 I jxcore-log: 
03-31 17:39:31.015  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 17:39:31.015  3567  3640 I jxcore-log: 
,03-31 17:39:31.067  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 17:39:31.067  3567  3640 I jxcore-log: 
,03-31 17:39:31.087  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 17:39:31.087  3567  3640 I jxcore-log: 
,03-31 17:39:31.092  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 17:39:31.092  3567  3640 I jxcore-log: 
,03-31 17:39:33.637  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 17:39:33.637  3567  3640 I jxcore-log: 
,03-31 17:39:33.659  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 17:39:33.659  3567  3640 I jxcore-log: 
,03-31 17:39:33.669  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 17:39:33.669  3567  3640 I jxcore-log: 
,03-31 17:39:34.001  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 17:39:34.001  3567  3640 I jxcore-log: 
,03-31 17:39:34.099  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 17:39:34.099  3567  3640 I jxcore-log: 
,03-31 17:39:34.170  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 17:39:34.170  3567  3640 I jxcore-log: 
03-31 17:39:34.177  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 17:39:34.177  3567  3640 I jxcore-log: 
,03-31 17:39:34.189  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 17:39:34.189  3567  3640 I jxcore-log: 
,03-31 17:39:34.194  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 17:39:34.194  3567  3640 I jxcore-log: 
,03-31 17:39:34.201  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 17:39:34.201  3567  3640 I jxcore-log: 
,03-31 17:39:34.221  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 17:39:34.221  3567  3640 I jxcore-log: 
,03-31 17:39:34.246  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 17:39:34.246  3567  3640 I jxcore-log: 
,03-31 17:39:34.359  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 17:39:34.359  3567  3640 I jxcore-log: 
,03-31 17:39:34.365  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 17:39:34.365  3567  3640 I jxcore-log: 
,03-31 17:39:34.397  3567  3640 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 17:39:34.397  3567  3640 I jxcore-log: 
,03-31 17:39:34.405  3567  3640 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
03-31 17:39:34.407  3567  3640 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-31 17:39:34.407  3567  3640 I jxcore-log: 
,03-31 17:39:38.145  1656  1759 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-31 17:39:38.145  1656  1656 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 17:39:41.386   762   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,03-31 17:39:57.342  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:39:57.345  1519  3807 I VacuumService: Vacuum at: now=1459438797345 tag=VacuumService
,03-31 17:39:57.620  1519  1647 I art     : Explicit concurrent mark sweep GC freed 57294(3MB) AllocSpace objects, 36(576KB) LOS objects, 39% free, 22MB/37MB, paused 895us total 36.902ms
,03-31 17:39:58.363  1519  3821 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 8054 seconds from now (1459438798363)
,03-31 17:39:58.437  1519  3816 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-31 17:39:58.440  1519  3816 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 17:39:59.661  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:39:59.662  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 17:40:00.810  2064  2154 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 17:40:00.867  2064  2154 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 17:40:01.388   762   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 17:40:01.388   762   868 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 17:40:11.010  1100  1305 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-31 17:40:11.010  1100  1305 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 17:40:21.392   762   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 17:40:21.392   762   868 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 17:40:38.011   762   837 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
03-31 17:40:38.016   762   837 I PowerManagerService: Sleeping (uid 1000)...
,03-31 17:40:38.070   187   876 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-31 17:40:38.072   762   837 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-31 17:40:38.086   180  1464 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (114 us)
,03-31 17:40:38.095   762   868 E WifiStateMachine: cancelDelayedScan -> 11
,03-31 17:40:38.103   762   868 E native  : do suspend false
,03-31 17:40:38.256  1100  1100 I Keyboard.Facilitator: onFinishInput()
,03-31 17:40:38.257   187   187 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,03-31 17:40:38.265   762   868 E WifiStateMachine: cancelDelayedScan -> 13
,03-31 17:40:38.267   762   868 E native  : do suspend true
,03-31 17:40:38.597   762   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 17:40:38.597   762   868 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,03-31 17:40:38.632   762   835 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-31 17:40:38.636   762   762 V ActivityManager: Display changed displayId=0
03-31 17:40:38.646   180   180 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-31 17:40:38.646   180   180 D qdhwcomposer: hwc_blank: Blanking display: 0
,03-31 17:40:38.765   181   181 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
03-31 17:40:38.765   181   181 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
03-31 17:40:38.765   181   181 I rmt_storage: wakelock acquired: 1, error no: 2
03-31 17:40:38.765   181   530 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236802816)
,03-31 17:40:38.841   181   530 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
03-31 17:40:38.841   181   530 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
03-31 17:40:38.841   181   530 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236802816) wakelock released: 1, error no: 0
03-31 17:40:38.841   181   530 I rmt_storage: 
,03-31 17:40:38.843   181   181 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,03-31 17:40:38.920   180   180 D qdhwcomposer: hwc_blank: Done blanking display: 0
03-31 17:40:38.920   762   885 D SurfaceControl: Excessive delay in setPowerMode(): 289ms
03-31 17:40:38.920  1691  1692 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,03-31 17:40:38.934  3567  3567 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
03-31 17:40:38.934  3567  3567 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-31 17:40:38.952  3567  3567 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2d33caf9 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@33da060d, 16908290=android.view.AbsSavedState$1@33da060d}, android:focusedViewId=100}]}]
03-31 17:40:38.952  3567  3567 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
03-31 17:40:38.952  3567  3567 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
03-31 17:40:38.952  3567  3567 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,03-31 17:40:41.395   762   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 17:40:41.396   762   868 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,03-31 17:40:54.407  1519  2028 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-31 17:41:21.294  3567  3640 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-31 17:41:21.294  3567  3640 I jxcore-log: 
,03-31 17:41:21.686  3905  3905 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-31 17:41:21.688  3905  3905 D AndroidRuntime: CheckJNI is OFF
,03-31 17:41:21.777  3905  3905 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 17:41:21.783   762   830 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
,03-31 17:41:21.784   762   830 I ActivityManager: Killing 3567:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-31 17:41:21.818   762   869 D WifiService: Client connection lost with reason: 4
,03-31 17:41:21.819   762   964 I WindowState: WIN DEATH: Window{321f4c66 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-31 17:41:21.820   762  1099 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2ca92658)
03-31 17:41:21.821   762   870 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 17:41:21.821   762   870 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 17:41:21.836   762   841 W PackageSettings: Skipping PackageSetting{257bc150 com.example.hello/10116} due to missing metadata
,03-31 17:41:21.996   762   830 I ActivityManager:   Force finishing activity 3 ActivityRecord{26d8ddc4 u0 com.test.thalitest/.MainActivity t19}
,03-31 17:41:21.999   762  1193 W ActivityManager: Spurious death for ProcessRecord{dc453b1 3567:com.test.thalitest/u0a49}, curProc for 3567: null
03-31 17:41:21.999   762   841 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-31 17:41:22.002   762   841 I ActivityManager:   Force finishing activity 3 ActivityRecord{26d8ddc4 u0 com.test.thalitest/.MainActivity t19 f}
,03-31 17:41:22.002   762   841 W ActivityManager: Duplicate finish request for ActivityRecord{26d8ddc4 u0 com.test.thalitest/.MainActivity t19 f}
,03-31 17:41:22.075  1232  1232 I art     : Explicit concurrent mark sweep GC freed 1760(109KB) AllocSpace objects, 4(369KB) LOS objects, 38% free, 25MB/41MB, paused 871us total 67.541ms
,03-31 17:41:22.077   909   909 I art     : Explicit concurrent mark sweep GC freed 42483(1749KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 885us total 29.036ms
,03-31 17:41:22.097  1545  1545 I art     : Explicit concurrent mark sweep GC freed 2761(158KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 23MB/30MB, paused 433us total 91.824ms
03-31 17:41:22.099  1397  1397 I art     : Explicit concurrent mark sweep GC freed 2929(234KB) AllocSpace objects, 7(154KB) LOS objects, 24% free, 22MB/30MB, paused 501us total 92.448ms
,03-31 17:41:22.113   762   887 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
03-31 17:41:22.113   762   887 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,03-31 17:41:22.115  1100  1100 I Keyboard.Facilitator: resetDictionaries() : en_US
03-31 17:41:22.118   762   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 17:41:22.119  1519  1631 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-31 17:41:22.121   762   762 I art     : Explicit concurrent mark sweep GC freed 60785(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 29MB/44MB, paused 1.320ms total 74.397ms
,03-31 17:41:22.125  1100  3937 I Keyboard.Facilitator.DecoderInitializer: run()
,03-31 17:41:22.127  1100  3937 I Decoder : createOrResetDecoder
,03-31 17:41:22.148  1307  3938 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-31 17:41:22.151   762  1197 I ActivityManager: Start proc 3939:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-31 17:41:22.200  1100  3937 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-31 17:41:22.230  1100  3937 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-31 17:41:22.230   762   762 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-31 17:41:22.230   762   762 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-31 17:41:22.232  1100  3937 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 17:41:22.232  1100  3937 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-31 17:41:22.240  1100  3937 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-31 17:41:22.240  1100  3937 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-31 17:41:22.241  1100  3937 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 17:41:22.241  1100  3937 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-31 17:41:22.242  1100  3937 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 17:41:22.242  1100  3937 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 17:41:22.242  1100  3937 I Keyboard.Facilitator.Delight2FileSweeper: run()
,03-31 17:41:22.243  1100  3937 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 17:41:22.243  1100  3937 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 17:41:22.243  1100  3937 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-31 17:41:22.247   762  2338 I ActivityManager: Start proc 3963:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-31 17:41:22.249   762   777 I ActivityManager: Killing 3177:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,03-31 17:41:22.263   762  3408 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3567 uid 10049
03-31 17:41:22.264  1100  1100 I Keyboard.Facilitator: onFinishInput()
,03-31 17:41:22.265   762   841 I art     : Explicit concurrent mark sweep GC freed 15152(1434KB) AllocSpace objects, 2(1312KB) LOS objects, 33% free, 28MB/42MB, paused 2.229ms total 100.987ms
,03-31 17:41:22.275  1232  1232 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-31 17:41:22.302  3963  3963 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-31 17:41:22.312  1545  3981 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-31 17:41:22.312  1545  3981 D AccountUtils: Clearing selected account for com.test.thalitest
,03-31 17:41:22.324  1519  1519 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,03-31 17:41:22.324  1519  1519 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-31 17:41:22.340  3905  3905 I art     : System.exit called, status: 0
03-31 17:41:22.340  3905  3905 I AndroidRuntime: VM exiting with result code 0.
,03-31 17:41:22.353   762  2299 I ActivityManager: Start proc 3987:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-31 17:41:22.400   762   841 I ActivityManager: Start proc 4004:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-31 17:41:22.402  1545  3981 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest,
,03-31 17:41:22.450  1545  4024 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 17:41:22.451   762  1098 I ActivityManager: Killing 3242:com.quickoffice.android/u0a65 (adj 15): empty #17
,03-31 17:41:22.481  1232  1448 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
