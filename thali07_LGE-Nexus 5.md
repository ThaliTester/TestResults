#### Test 65745020fc66909_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
04-08 10:09:01.720  1557  2462 I CheckinService: Done disabling old GoogleServicesFramework version
,04-08 10:09:01.994  3435  3435 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-08 10:09:01.996  3435  3435 D AndroidRuntime: CheckJNI is OFF
04-08 10:09:02.097  3435  3435 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
04-08 10:09:02.099   764   930 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-08 10:09:02.106   764   930 V WindowManager: addAppToken: AppWindowToken{128f9dc6 token=Token{3d0ba7a1 ActivityRecord{164a9408 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
04-08 10:09:02.110   764   833 V WindowManager: Adding window Window{37a0a9d9 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2981b15 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-08 10:09:02.115  3435  3435 D AndroidRuntime: Shutting down VM
04-08 10:09:02.125  1424  1442 W SearchService: Abort, client detached.
04-08 10:09:02.179   764  1119 I ActivityManager: Start proc 3456:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
04-08 10:09:02.195  1424  1575 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
04-08 10:09:02.225  1424  1424 I MicroDetector: Keeping mic open: false
04-08 10:09:02.225  1424  1424 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@197f4f4e
04-08 10:09:02.226  1424  1581 I DeviceStateChecker: DeviceStateChecker cancelled
04-08 10:09:02.272  3456  3456 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
04-08 10:09:02.276   188  1586 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-08 10:09:02.276   188  1586 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-08 10:09:02.280  1424  1583 I MicroRecognitionRunner: Detection finished
04-08 10:09:02.281  1424  1580 I MicroRecognitionRunner: Stopping hotword detection.
04-08 10:09:02.285  3456  3456 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 7103-7105)
04-08 10:09:02.285  3456  3456 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-08 10:09:02.298  3456  3456 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21ca3109}
04-08 10:09:02.298  3456  3456 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-08 10:09:02.299  3456  3456 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
04-08 10:09:02.320  3456  3456 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,04-08 10:09:02.329   764  2246 I ActivityManager: Killing 2525:com.google.android.deskclock/u0a33 (adj 15): empty #17
04-08 10:09:02.336  3456  3456 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
04-08 10:09:02.423   764   780 I art     : Explicit concurrent mark sweep GC freed 23438(1124KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.318ms total 53.614ms
04-08 10:09:02.424   764   832 D BluetoothManagerService: Message: 20
04-08 10:09:02.424   764   832 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29688d50:true
04-08 10:09:02.444  3456  3456 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
04-08 10:09:02.444  3456  3456 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
04-08 10:09:02.490  3456  3456 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-08 10:09:02.490  3456  3456 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-08 10:09:02.506  3456  3456 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
04-08 10:09:02.514  3456  3456 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
04-08 10:09:02.515  3456  3456 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
04-08 10:09:02.526  3456  3456 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
04-08 10:09:02.703   175   175 D SurfaceFlinger: shader cache generated - 24 shaders in 175.483597 ms
04-08 10:09:02.718  3456  3515 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
04-08 10:09:02.726  3456  3456 D Atlas   : Validating map...
04-08 10:09:02.766   764  1120 V WindowManager: Adding window Window{244db30a u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{37a0a9d9 u0 Starting com.test.thalitest})
04-08 10:09:02.814   764   857 D WifiService: New client listening to asynchronous messages
04-08 10:09:02.832   764  1216 D ConnectivityService: listenForNetwork for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-08 10:09:02.833   764   858 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-08 10:09:02.833   764   858 D ConnectivityService: apparently satisfied.  currentScore=60
04-08 10:09:02.834  3456  3523 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
04-08 10:09:02.869  3456  3515 I OpenGLRenderer: Initialized EGL, version 1.4
04-08 10:09:02.875  3456  3515 D OpenGLRenderer: Enabling debug mode 0
04-08 10:09:02.910  3456  3525 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
04-08 10:09:02.934   764   833 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +808ms
04-08 10:09:02.945  1096  1096 I Keyboard.Facilitator: onFinishInput()
04-08 10:09:02.958  3456  3456 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3456
,04-08 10:09:03.098  3456  3456 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-08 10:09:03.166  3456  3538 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362822528
,04-08 10:09:03.171  3456  3538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-08 10:09:03.171  3456  3538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-08 10:09:03.171  3456  3538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-08 10:09:03.171  3456  3538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-08 10:09:03.171  3456  3538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-08 10:09:03.171  3456  3538 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31269d59 added. We now have 1 listener(s)
,04-08 10:09:03.173   764  1119 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-08 10:09:03.176  3456  3538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,04-08 10:09:03.179  3456  3538 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,04-08 10:09:03.180  3456  3538 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
04-08 10:09:03.180  3456  3538 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-08 10:09:03.191  3456  3538 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1753c3cc added. We now have 1 listener(s)
,04-08 10:09:03.200  3456  3538 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-08 10:09:03.202  3456  3538 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,04-08 10:09:03.205  3456  3538 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
04-08 10:09:03.205  3456  3538 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,04-08 10:09:03.207  3456  3538 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
04-08 10:09:03.208   764  1119 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
04-08 10:09:03.210  3456  3538 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
04-08 10:09:03.215  3456  3538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-08 10:09:03.215  3456  3538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-08 10:09:03.215  3456  3538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-08 10:09:03.215  3456  3538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-08 10:09:03.215  3456  3538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-08 10:09:03.215  3456  3538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-08 10:09:03.215  3456  3538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-08 10:09:03.215  3456  3538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-08 10:09:03.215  3456  3538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-08 10:09:03.215  3456  3538 D io.jxcore.node.ConnectivityMonitor: start: OK
04-08 10:09:03.217  3456  3456 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
04-08 10:09:03.218  3456  3456 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
04-08 10:09:03.219  3456  3538 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-08 10:09:03.244  3456  3456 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-08 10:09:03.410   764   856 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
,04-08 10:09:03.890  3456  3540 W jxcore-log: Initializing JXcore engine
04-08 10:09:03.890  3456  3540 W jxcore-log: JXcore engine is ready
,04-08 10:09:03.912  3540  3540 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[7348]" dev="sockfs" ino=7348 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-08 10:09:03.912  3540  3540 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
04-08 10:09:03.912  3540  3540 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[7417]" dev="sockfs" ino=7417 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-08 10:09:03.912  3540  3540 W Thread-337: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[19780]" dev="sockfs" ino=19780 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,04-08 10:09:03.934  3456  3540 W jxcore-log: Starting JXcore engine
,04-08 10:09:04.007  3456  3540 W jxcore-log: Platform android
04-08 10:09:04.007  3456  3540 W jxcore-log: 
,04-08 10:09:04.007  3456  3540 W jxcore-log: Process ARCH arm
04-08 10:09:04.007  3456  3540 W jxcore-log: 
,04-08 10:09:04.243  3456  3540 I jxcore-log: JXcore Cordova bridge is ready!
04-08 10:09:04.243  3456  3540 I jxcore-log: 
,04-08 10:09:04.244  3456  3540 W jxcore-log: JXcore engine is started
,04-08 10:09:04.248  3456  3538 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-08 10:09:04.250  3456  3456 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-08 10:09:06.142  3295  3328 W Babel   : aye TOOK TOO LONG! (15039ms > 10000ms)
,04-08 10:09:06.143  3295  3330 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,04-08 10:09:06.172   764  1119 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-08 10:09:06.174   764   930 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-08 10:09:06.180  3295  3295 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
04-08 10:09:06.180  3295  3295 W Babel   : BAM#gBA: invalid account id: -1
04-08 10:09:06.180  3295  3295 W Babel   : BAM#gBA: invalid account id: -1
04-08 10:09:06.180  3295  3295 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,04-08 10:09:06.186   764   779 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-08 10:09:06.187   764  2243 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-08 10:09:06.210  3295  3340 W Babel   : aye TOOK TOO LONG! (15035ms > 10000ms)
,04-08 10:09:06.249  1515  1610 I Finsky  : [118] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-08 10:09:06.250  1515  1515 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-08 10:09:07.361  1557  1568 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,04-08 10:09:10.240  1515  1515 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(151): Beginning daily hygiene
,04-08 10:09:10.273  1614  1614 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-08 10:09:10.279  1614  1614 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-08 10:09:10.280  1614  1614 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-08 10:09:10.958  1614  1614 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-08 10:09:11.075  1515  1515 I Finsky  : [1] com.google.android.finsky.m.e.a(156): Skipping DFE self-update. Local Version [80631600] >= Server Version [-1]
,04-08 10:09:11.124  1614  1614 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-08 10:09:11.152   764   780 I ActivityManager: Start proc 3593:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,04-08 10:09:11.194  3593  3593 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-08 10:09:11.194  3593  3593 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-08 10:09:11.218  3593  3593 I MultiDex: VM with version 2.1.0 has multidex support
04-08 10:09:11.218  3593  3593 I MultiDex: install
04-08 10:09:11.218  3593  3593 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-08 10:09:11.243  3593  3593 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,04-08 10:09:11.278  3593  3593 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-08 10:09:11.295  1614  1614 D WearableService: callingUid 10007, callindPid: 1614
,04-08 10:09:11.299  1614  1926 E MDM     : [186] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,04-08 10:09:11.302  3593  3593 D ChimeraCfgMgr: Reading stored module config
,04-08 10:09:11.305  1614  1614 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-08 10:09:11.306  1557  3619 D LocationInitializer: Restart initialization of location
,04-08 10:09:11.319  1614  1614 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-08 10:09:11.333  1614  1661 W GCoreFlp: No location to return for getLastLocation()
,04-08 10:09:11.333  1614  3620 W FusedLocationProvider: location=null
,04-08 10:09:11.412  3593  3618 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,04-08 10:09:11.424  3593  3593 D CAR.SERVICE: Connecting to CarCallService...
,04-08 10:09:11.440  3593  3593 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-08 10:09:11.440  3593  3593 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-08 10:09:11.449  3593  3593 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,04-08 10:09:11.454  3593  3593 D CAR.TEL.Service: Creating a new CarCallService.
,04-08 10:09:11.456  3593  3593 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,04-08 10:09:11.457   764   930 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,04-08 10:09:11.458  3593  3593 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@1b2039ce
04-08 10:09:11.458   764   780 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
04-08 10:09:11.458  3593  3593 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
04-08 10:09:11.458  3593  3593 D CAR.TEL.Service: Starting CarCallService with initial phone null
,04-08 10:09:11.508   764  1120 I ActivityManager: Start proc 3638:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,04-08 10:09:11.521  3593  3609 D CAR.SERVICE: Package validated; name: com.android.vending
,04-08 10:09:11.531  3638  3638 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,04-08 10:09:11.558  3638  3638 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@39c14210(com.android.providers.calendar.CalendarProvider2@21ca3109)
,04-08 10:09:11.565   764  1210 I ActivityManager: Killing 3091:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,04-08 10:09:12.016  1614  1614 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-08 10:09:12.364  1515  1515 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(9405): Logging device features
,04-08 10:09:12.424  1614  1630 D DeviceConnectionService: client connected with version: 8298000
,04-08 10:09:12.438  1515  1515 E Finsky  : [1] com.google.android.finsky.wear.bf.a(728): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
04-08 10:09:12.439  1515  1515 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6337): Dropping command=hygiene due to Gms not connected
,04-08 10:09:12.810  3638  3638 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
04-08 10:09:12.810  3638  3638 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,04-08 10:09:13.506  3456  3540 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-08 10:09:13.506  3456  3540 I jxcore-log: 
04-08 10:09:13.508  3456  3540 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-08 10:09:13.508  3456  3540 I jxcore-log: 
,04-08 10:09:13.512  3456  3540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-08 10:09:13.512  3456  3540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-08 10:09:13.512  3456  3540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-08 10:09:13.512  3456  3540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-08 10:09:13.512  3456  3540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-08 10:09:13.512  3456  3540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-08 10:09:13.512  3456  3540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-08 10:09:13.512  3456  3540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-08 10:09:13.516  3456  3540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,04-08 10:09:13.519  3456  3540 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-08 10:09:13.519  3456  3540 I jxcore-log: 
04-08 10:09:13.520  3456  3540 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-08 10:09:13.520  3456  3540 I jxcore-log: 
,04-08 10:09:14.006  3456  3540 I jxcore-log: Unit Test app is loaded
04-08 10:09:14.006  3456  3540 I jxcore-log: 
,04-08 10:09:14.012  3456  3456 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-08 10:09:14.015  3456  3540 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-08 10:09:14.015  3456  3540 I jxcore-log: 
,04-08 10:09:14.020  3456  3540 I jxcore-log: My device name is: LGE-Nexus 5
04-08 10:09:14.020  3456  3540 I jxcore-log: 
,04-08 10:09:16.547  3593  3593 D CAR.SERVICE: mConnectedToCar = false, abort
,04-08 10:09:16.550   764  1119 I ActivityManager: Killing 2551:com.google.android.keep/u0a52 (adj 15): empty #17
,04-08 10:09:16.557  3593  3593 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1172e1f6 that was originally bound here
04-08 10:09:16.557  3593  3593 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1172e1f6 that was originally bound here
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-08 10:09:16.557  3593  3593 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-08 10:09:16.684  3593  3593 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@f1c8ec9 that was originally bound here
04-08 10:09:16.684  3593  3593 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@f1c8ec9 that was originally bound here
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-08 10:09:16.684  3593  3593 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-08 10:09:16.686   764   779 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@3ef7c691
,04-08 10:09:16.710  3638  3687 E SQLiteLog: (284) automatic index on view_events(_id)
,04-08 10:09:16.792  1515  3692 I Finsky  : [131] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-08 10:09:16.797  1614  1614 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-08 10:09:17.717  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-08 10:09:17.717  3456  3540 I jxcore-log: 
,04-08 10:09:17.983   764  2245 I ActivityManager: Killing 2091:com.android.defcontainer/u0a4 (adj 15): empty #17
,04-08 10:09:18.062  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-08 10:09:18.062  3456  3540 I jxcore-log: 
,04-08 10:09:18.070   764  2245 I ActivityManager: Killing 3113:com.android.musicfx/u0a13 (adj 15): empty #18
,04-08 10:09:18.087  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-08 10:09:18.087  3456  3540 I jxcore-log: 
,04-08 10:09:18.091  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-08 10:09:18.091  3456  3540 I jxcore-log: 
,04-08 10:09:18.106  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-08 10:09:18.106  3456  3540 I jxcore-log: 
,04-08 10:09:18.110  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-08 10:09:18.110  3456  3540 I jxcore-log: 
,04-08 10:09:20.005  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-08 10:09:20.005  3456  3540 I jxcore-log: 
,04-08 10:09:20.016  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-08 10:09:20.016  3456  3540 I jxcore-log: 
,04-08 10:09:20.025  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-08 10:09:20.025  3456  3540 I jxcore-log: 
,04-08 10:09:20.176  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-08 10:09:20.176  3456  3540 I jxcore-log: 
,04-08 10:09:21.075  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-08 10:09:21.075  3456  3540 I jxcore-log: 
,04-08 10:09:21.132  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-08 10:09:21.132  3456  3540 I jxcore-log: 
,04-08 10:09:21.138  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
04-08 10:09:21.138  3456  3540 I jxcore-log: 
,04-08 10:09:21.272  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-08 10:09:21.272  3456  3540 I jxcore-log: 
,04-08 10:09:21.292  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-08 10:09:21.292  3456  3540 I jxcore-log: 
,04-08 10:09:21.296  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-08 10:09:21.296  3456  3540 I jxcore-log: 
,04-08 10:09:21.301  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-08 10:09:21.301  3456  3540 I jxcore-log: 
,04-08 10:09:21.316  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-08 10:09:21.316  3456  3540 I jxcore-log: 
,04-08 10:09:21.335  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-08 10:09:21.335  3456  3540 I jxcore-log: 
,04-08 10:09:21.422  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-08 10:09:21.422  3456  3540 I jxcore-log: 
04-08 10:09:21.427  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-08 10:09:21.427  3456  3540 I jxcore-log: 
,04-08 10:09:21.452  3456  3540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-08 10:09:21.452  3456  3540 I jxcore-log: 
,04-08 10:09:21.473  3456  3540 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
04-08 10:09:21.474  3456  3540 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
04-08 10:09:21.474  3456  3540 I jxcore-log: 
,04-08 10:09:23.414   764   856 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-46
,04-08 10:09:23.415   764   856 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-08 10:09:29.969  1515  1610 I Finsky  : [118] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-08 10:09:29.970  1515  1515 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-08 10:09:30.028  1936  2001 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-08 10:09:43.418   764   856 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
,04-08 10:09:45.971  1614  1614 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-08 10:09:45.974  1614  3730 I VacuumService: Vacuum at: now=1460102985974 tag=VacuumService
,04-08 10:10:02.946  1096  1266 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-08 10:10:02.947  1096  1266 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-08 10:10:02.999  1614  1614 I ConfigService: onCreate
,04-08 10:10:03.421   764   856 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
04-08 10:10:03.422   764   856 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-08 10:10:08.045  1614  1614 I ConfigService: onDestroy
,04-08 10:10:23.427   764   856 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-46
04-08 10:10:23.428   764   856 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-08 10:10:37.644   764   835 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
04-08 10:10:37.645   764   835 I PowerManagerService: Sleeping (uid 1000)...
,04-08 10:10:37.656   764   835 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-08 10:10:37.661   188   871 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-08 10:10:37.666   175  1552 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (108 us)
,04-08 10:10:37.691   764   856 E WifiStateMachine: cancelDelayedScan -> 11
,04-08 10:10:37.697   764   856 E native  : do suspend false
,04-08 10:10:37.913   188   870 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
04-08 10:10:37.913  1096  1096 I Keyboard.Facilitator: onFinishInput()
,04-08 10:10:37.927   764   856 E WifiStateMachine: cancelDelayedScan -> 13
04-08 10:10:37.928   764   856 E native  : do suspend true
,04-08 10:10:38.009   764  1095 I art     : Explicit concurrent mark sweep GC freed 58320(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.705ms total 87.393ms
,04-08 10:10:38.191   764   856 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-46
04-08 10:10:38.191   764   856 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,04-08 10:10:38.238   175   175 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
04-08 10:10:38.238   175   175 D qdhwcomposer: hwc_blank: Blanking display: 0
,04-08 10:10:38.239   764   833 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,04-08 10:10:38.240   764   764 V ActivityManager: Display changed displayId=0
,04-08 10:10:38.361   176   176 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
04-08 10:10:38.361   176   176 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
04-08 10:10:38.361   176   176 I rmt_storage: wakelock acquired: 1, error no: 2
04-08 10:10:38.361   176   562 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236802816)
,04-08 10:10:38.446   176   562 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
04-08 10:10:38.446   176   562 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
04-08 10:10:38.446   176   562 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236802816) wakelock released: 1, error no: 0
04-08 10:10:38.446   176   562 I rmt_storage: 
,04-08 10:10:38.449   176   176 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,04-08 10:10:38.521   175   175 D qdhwcomposer: hwc_blank: Done blanking display: 0
04-08 10:10:38.523   764   880 D SurfaceControl: Excessive delay in setPowerMode(): 285ms
,04-08 10:10:38.526  1871  1872 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,04-08 10:10:38.551  3456  3456 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
04-08 10:10:38.551  3456  3456 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,04-08 10:10:38.569  3456  3456 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1176096 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@11efed8e, 16908290=android.view.AbsSavedState$1@11efed8e}, android:focusedViewId=100}]}]
04-08 10:10:38.569  3456  3456 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
04-08 10:10:38.569  3456  3456 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
04-08 10:10:38.569  3456  3456 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,04-08 10:10:43.432   764   856 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-46
04-08 10:10:43.432   764   856 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,04-08 10:10:44.203  1614  1856 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,04-08 10:11:08.778  1614  3788 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 5344 seconds from now (1460103068778)
,04-08 10:11:08.853  1614  3779 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,04-08 10:11:08.856  1614  3779 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-08 10:11:10.114  1614  1614 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-08 10:11:10.115  1614  1614 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-08 10:11:12.065  1614  1624 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3a5e08b2)
,04-08 10:11:12.065  1614  1624 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c5c2003)
04-08 10:11:12.065  1614  1624 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3a4cbb80)
04-08 10:11:12.066  1614  1624 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@38cd05b9)
,04-08 10:11:12.066  1614  1624 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d1ffdfe)
,04-08 10:11:35.615  3456  3540 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-08 10:11:35.615  3456  3540 I jxcore-log: 
,04-08 10:11:36.003  3842  3842 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-08 10:11:36.007  3842  3842 D AndroidRuntime: CheckJNI is OFF
,04-08 10:11:36.098  3842  3842 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-08 10:11:36.103   764   828 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
04-08 10:11:36.103   764   828 I ActivityManager: Killing 3456:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,04-08 10:11:36.141   764   839 W PackageSettings: Skipping PackageSetting{383f3932 com.example.hello/10116} due to missing metadata
,04-08 10:11:36.165   764   930 I WindowState: WIN DEATH: Window{244db30a u0 com.test.thalitest/com.test.thalitest.MainActivity}
04-08 10:11:36.165   764  1119 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2ea04da9)
,04-08 10:11:36.166   764   857 D WifiService: Client connection lost with reason: 4
04-08 10:11:36.166   764   858 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-08 10:11:36.166   764   858 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-08 10:11:36.313   764   828 I ActivityManager:   Force finishing activity 3 ActivityRecord{164a9408 u0 com.test.thalitest/.MainActivity t19}
,04-08 10:11:36.317   764  1216 W ActivityManager: Spurious death for ProcessRecord{2ba0bf2e 3456:com.test.thalitest/u0a49}, curProc for 3456: null
,04-08 10:11:36.317   764   839 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,04-08 10:11:36.350  1250  1250 I art     : Explicit concurrent mark sweep GC freed 1770(110KB) AllocSpace objects, 5(450KB) LOS objects, 38% free, 25MB/41MB, paused 814us total 27.348ms
,04-08 10:11:36.372   903   903 I art     : Explicit concurrent mark sweep GC freed 9653(424KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 1.193ms total 44.551ms
,04-08 10:11:36.397   764   847 I InputReader: Reconfiguring input devices.  changes=0x00000010
04-08 10:11:36.397  1614  1669 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,04-08 10:11:36.398   764   882 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
04-08 10:11:36.399   764   882 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,04-08 10:11:36.400  1096  1096 I Keyboard.Facilitator: resetDictionaries() : en_US
,04-08 10:11:36.403  1424  1424 I art     : Explicit concurrent mark sweep GC freed 4201(301KB) AllocSpace objects, 7(154KB) LOS objects, 24% free, 21MB/29MB, paused 434us total 68.240ms
,04-08 10:11:36.404  1096  3871 I Keyboard.Facilitator.DecoderInitializer: run()
,04-08 10:11:36.407  1096  3871 I Decoder : createOrResetDecoder
,04-08 10:11:36.411  3043  3873 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,04-08 10:11:36.417  1557  1557 I art     : Explicit concurrent mark sweep GC freed 2516(150KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 23MB/30MB, paused 456us total 90.818ms
,04-08 10:11:36.428   764  2243 I ActivityManager: Start proc 3877:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,04-08 10:11:36.440  1614  1614 I ConfigService: onCreate
,04-08 10:11:36.441   764   764 I art     : Explicit concurrent mark sweep GC freed 19206(1190KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 29MB/43MB, paused 1.931ms total 110.524ms
,04-08 10:11:36.486  1096  3871 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,04-08 10:11:36.496   764  1120 I ActivityManager: Start proc 3898:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,04-08 10:11:36.501   764  1095 I ActivityManager: Killing 3162:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,04-08 10:11:36.506   199   199 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 195us total 9.896ms
,04-08 10:11:36.517   199   199 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 195us total 9.004ms
,04-08 10:11:36.527   199   199 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 194us total 9.189ms
,04-08 10:11:36.530  1096  3871 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
04-08 10:11:36.532  1096  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
04-08 10:11:36.532  1096  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
04-08 10:11:36.533  1096  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
04-08 10:11:36.533  1096  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,04-08 10:11:36.534  1096  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
04-08 10:11:36.534  1096  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
04-08 10:11:36.535  1096  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-08 10:11:36.535  1096  3871 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-08 10:11:36.535  1096  3871 I Keyboard.Facilitator.Delight2FileSweeper: run()
04-08 10:11:36.535  1096  3871 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-08 10:11:36.535  1096  3871 I StatsUtilsManager: startPeriodStatsRecorder() : Success
04-08 10:11:36.535  1096  3871 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,04-08 10:11:36.545   764   780 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3456 uid 10049
,04-08 10:11:36.548  1096  1096 I Keyboard.Facilitator: onFinishInput()
,04-08 10:11:36.558  1250  1250 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-08 10:11:36.566   764   764 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-08 10:11:36.566   764   764 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,04-08 10:11:36.569   764   839 I art     : Explicit concurrent mark sweep GC freed 11399(1202KB) AllocSpace objects, 2(1312KB) LOS objects, 33% free, 28MB/42MB, paused 3.686ms total 116.489ms
,04-08 10:11:36.585  3898  3898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-08 10:11:36.589  1515  1515 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(268): Wear auto uninstall disabled for package com.test.thalitest
,04-08 10:11:36.606  1557  3919 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-08 10:11:36.606  1557  3919 D AccountUtils: Clearing selected account for com.test.thalitest
,04-08 10:11:36.610  1614  1614 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-08 10:11:36.610  1614  1614 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-08 10:11:36.619  1557  3919 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,04-08 10:11:36.647  3842  3842 I art     : System.exit called, status: 0
04-08 10:11:36.647  3842  3842 I AndroidRuntime: VM exiting with result code 0.
,04-08 10:11:36.651   764  1119 I ActivityManager: Start proc 3927:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,04-08 10:11:36.679   764   839 I ActivityManager: Start proc 3945:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,04-08 10:11:36.719   764   780 I ActivityManager: Killing 3219:com.quickoffice.android/u0a65 (adj 15): empty #17
,04-08 10:11:36.721  1557  3919 I GMPM-SVC: App measurement is starting up, version: 8703
,04-08 10:11:36.721  1557  3919 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,04-08 10:11:36.729  1250  1446 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-08 10:11:36.748  1557  3937 W BaseAppContext: Using Auth Proxy for data requests.
,04-08 10:11:36.753  1557  3937 W BaseAppContext: Using Auth Proxy for data requests.
,04-08 10:11:36.761  1557  3919 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,04-08 10:11:36.769  1557  1649 I Icing   : doRemovePackageData com.test.thalitest
,04-08 10:11:36.812  1557  3973 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
04-08 10:11:36.812  1557  3973 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,04-08 10:11:36.812  1557  3973 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
04-08 10:11:36.812  1557  3973 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,04-08 10:11:36.876  3927  3978 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
04-08 10:11:36.876  3927  3978 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
04-08 10:11:36.876  3927  3978 I GAv4    :   adb logcat -s GAv4
04-08 10:11:36.876  1557  3973 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
04-08 10:11:36.876  1557  3973 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,04-08 10:11:36.877  1557  3973 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,04-08 10:11:36.879  1557  3966 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,04-08 10:11:36.881   764  1210 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-08 10:11:36.881   764   858 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-08 10:11:36.881   764   858 D ConnectivityService: apparently satisfied.  currentScore=60
,04-08 10:11:36.882  1557  3975 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-08 10:11:36.885  1557  3966 E GMPM-SVC: Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(:com.google.android.gms:321)
,04-08 10:11:36.887  1557  1890 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/auto_complete_suggestions.db'.
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.search.b.a(:com.google.android.gms:42)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.b.a.b(:com.google.android.gms:52)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.search.b.e(:com.google.android.gms:102)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:46)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
04-08 10:11:36.887  1557  3973 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: Couldn't open auto_complete_suggestions.db for writing (will try read-only):
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209),
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.search.b.a(:com.google.android.gms:42)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.b.a.b(:com.google.android.gms:52)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.search.b.e(:com.google.android.gms:102)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:46)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
04-08 10:11:36.888  1557  3973 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-08 10:11:36.890  1557  3974 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/databases/DocList.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
04-08 10:11:36.891  1557  3973 W SQLiteOpenHelper: Opened auto_complete_suggestions.db in read-only mode
04-08 10:11:36.892  1557  3973 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
04-08 10:11:36.892  1557  3973 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
04-08 10:11:36.893  1557  3973 E SQLiteLog: (8) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
04-08 10:11:36.893  1557  3973 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
04-08 10:11:36.895  3927  3978 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
04-08 10:11:36.906  3927  3978 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
04-08 10:11:36.906  3927  3985 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-08 10:11:36.906  3927  3985 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-08 10:11:36.910  3927  3986 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
04-08 10:11:36.910  3927  3985 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,04-08 10:11:36.920  3927  3986 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at hfa$a.getWritableDatabase(Unknown Source)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at hfa.l(Unknown Source)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at hfa.a(Unknown Source)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at hfa.j(Unknown Source)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at hff.run(Unknown Source)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
04-08 10:11:36.920  3927  3986 E SQLiteDatabase: 	at ioo$c.run(Unknown Source)
04-08 10:11:36.920  3927  3986 E GAv4    : Opening the database failed, dropping the table and recreating it
04-08 10:11:36.921  3927  3985 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at hfa$a.getWritableDatabase(Unknown Source)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at hfa.l(Unknown Source)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at hfa.a(Unknown Source)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at hfa.j(Unknown Source)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at hff.run(Unknown Source)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
04-08 10:11:36.921  3927  3986 E SQLiteDatabase: 	at ioo$c.run(Unknown Source)
04-08 10:11:36.922  3927  3986 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-08 10:11:36.922  3927  3986 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-08 10:11:36.922  3927  3985 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-08 10:11:36.922  3927  3986 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-08 10:11:36.922  3927  3985 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-08 10:11:36.923  3927  3985 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-08 10:11:36.934  1557  3973 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
04-08 10:11:36.934  1557  3973 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
04-08 10:11:36.934  1557  3973 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
04-08 10:11:36.934  1557  3973 I GCore-Chimera-Crash: ==
04-08 10:11:36.934  1557  3973 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
04-08 10:11:36.935  1557  3973 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryChimeraIntentService]
04-08 10:11:36.935  1557  3973 E AndroidRuntime: Process: com.google.android.gms, PID: 1557
04-08 10:11:36.935  1557  3973 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
04-08 10:11:36.935  1557  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
04-08 10:11:36.935  1557  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
04-08 10:11:36.935  1557  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
04-08 10:11:36.935  1557  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
04-08 10:11:36.935  1557  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
04-08 10:11:36.935  1557  3973 E AndroidRuntime: 	at com.google.android.gms.googlehelp.search.b.e(:com.google.android.gms:105)
04-08 10:11:36.935  1557  3973 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:46)
04-08 10:11:36.935  1557  3973 E AndroidRuntime: 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
04-08 10:11:36.935  1557  3973 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-08 10:11:36.935  1557  3973 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
04-08 10:11:36.935  1557  3973 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-08 10:11:36.939  1557  3973 I Process : Sending signal. PID: 1557 SIG: 9
04-08 10:11:36.942   764  3989 E DropBoxManagerService: Can't write: system_app_crash
04-08 10:11:36.942   764  3989 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
04-08 10:11:36.942   764  3989 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-08 10:11:36.942   764  3989 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-08 10:11:36.942   764  3989 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-08 10:11:36.942   764  3989 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-08 10:11:36.942   764  3989 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-08 10:11:36.942   764  3989 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-08 10:11:36.942   764  3989 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-08 10:11:36.942   764  3989 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-08 10:11:36.942   764  3989 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-08 10:11:36.942   764  3989 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-08 10:11:36.942   764  3989 E DropBoxManagerService: 	... 5 more
04-08 10:11:36.954   764  2245 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@e449e75)
04-08 10:11:36.955   764   858 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-08 10:11:36.955   764   858 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-08 10:11:36.956   764   857 D WifiService: Client connection lost with reason: 4
,04-08 10:11:36.960  3927  3993 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at bec.getWritableDatabase(PG:244)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at bds.a(PG:1605)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at jwi$b.a(PG:123)
04-08 10:11:36.960  3927  3993 E SQLiteDatabase: 	at bdu.run(PG:620)
04-08 10:11:36.976  3927  3978 W FileUtils: Failed to chmod(/data/data/com.google.android.apps.docs/app_filecache2): android.system.ErrnoException: chmod failed: ENOENT (No such file or directory)

```
