#### Test 64746945aaa3c62_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-31 10:10:38.527  1533  2511 I CheckinService: Done disabling old GoogleServicesFramework version
,03-31 10:10:38.791  3445  3445 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 10:10:38.793  3445  3445 D AndroidRuntime: CheckJNI is OFF
03-31 10:10:38.919  3445  3445 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-31 10:10:38.922   763   943 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 10:10:38.927   763   943 V WindowManager: addAppToken: AppWindowToken{1beccfd4 token=Token{2be14127 ActivityRecord{2a5427e6 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-31 10:10:38.935   763   836 V WindowManager: Adding window Window{34932e1f u0 Starting com.test.thalitest} at 2 of 7 (after Window{23965163 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 10:10:38.939  1448  1575 W SearchService: Abort, client detached.
03-31 10:10:38.941  3445  3445 D AndroidRuntime: Shutting down VM
03-31 10:10:38.964   763  1285 I ActivityManager: Start proc 3466:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-31 10:10:39.014  1448  1590 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
03-31 10:10:39.014  1448  1448 I MicroDetector: Keeping mic open: false
03-31 10:10:39.014  1448  1448 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@2382da62
03-31 10:10:39.016  1448  1600 I DeviceStateChecker: DeviceStateChecker cancelled
03-31 10:10:39.069   190  1611 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 10:10:39.069   190  1611 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 10:10:39.073  1448  1605 I MicroRecognitionRunner: Detection finished
03-31 10:10:39.074  1448  1599 I MicroRecognitionRunner: Stopping hotword detection.
03-31 10:10:39.075  3466  3466 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
03-31 10:10:39.092  3466  3466 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 9836-9840)
03-31 10:10:39.092  3466  3466 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 10:10:39.103  3466  3466 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {eb0dfed}
03-31 10:10:39.103  3466  3466 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 10:10:39.103  3466  3466 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 10:10:39.116  3466  3466 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
03-31 10:10:39.134   763   778 I ActivityManager: Killing 2583:com.google.android.keep/u0a52 (adj 15): empty #17
03-31 10:10:39.142  3466  3466 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-31 10:10:39.181   763   835 D BluetoothManagerService: Message: 20
03-31 10:10:39.181   763   835 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3aab68b3:true
,03-31 10:10:39.200  3466  3466 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-31 10:10:39.200  3466  3466 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-31 10:10:39.240  3466  3466 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-31 10:10:39.240  3466  3466 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-31 10:10:39.254  3466  3466 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-31 10:10:39.261  3466  3466 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 10:10:39.262  3466  3466 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-31 10:10:39.272  3466  3466 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-31 10:10:39.301  3466  3517 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 10:10:39.308  3466  3466 D Atlas   : Validating map...
,03-31 10:10:39.313   763  1165 V WindowManager: Adding window Window{44cd6b8 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{34932e1f u0 Starting com.test.thalitest})
,03-31 10:10:39.323   763   869 D WifiService: New client listening to asynchronous messages
,03-31 10:10:39.336   763  3314 D ConnectivityService: listenForNetwork for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 10:10:39.337   763   870 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 10:10:39.337   763   870 D ConnectivityService: apparently satisfied.  currentScore=60
03-31 10:10:39.338  3466  3520 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 10:10:39.445   763  1039 I art     : Explicit concurrent mark sweep GC freed 23145(1117KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 2.362ms total 94.686ms
,03-31 10:10:39.468   176   176 D SurfaceFlinger: shader cache generated - 24 shaders in 135.881622 ms
,03-31 10:10:39.517  3466  3517 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 10:10:39.522  3466  3517 D OpenGLRenderer: Enabling debug mode 0
,03-31 10:10:39.592  1129  1129 I Keyboard.Facilitator: onFinishInput()
,03-31 10:10:39.598  3466  3524 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-31 10:10:39.601   763   836 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +661ms
,03-31 10:10:39.642  3466  3466 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3466
,03-31 10:10:39.716  3466  3466 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 10:10:39.899  3466  3531 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362804480
,03-31 10:10:39.902  3466  3531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 10:10:39.902  3466  3531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 10:10:39.902  3466  3531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 10:10:39.902  3466  3531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 10:10:39.902  3466  3531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-31 10:10:39.902  3466  3531 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a68f3d added. We now have 1 listener(s)
03-31 10:10:39.903   763  1311 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:10:39.905  3466  3531 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,03-31 10:10:39.908  3466  3531 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-31 10:10:39.909  3466  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 10:10:39.909  3466  3531 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-31 10:10:39.913  3466  3531 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc13a00 added. We now have 1 listener(s)
03-31 10:10:39.913  3466  3531 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 10:10:39.918  3466  3531 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-31 10:10:39.919  3466  3531 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-31 10:10:39.919  3466  3531 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-31 10:10:39.923  3466  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:10:39.924   763   779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 10:10:39.924  3466  3531 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-31 10:10:39.928  3466  3531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:10:39.928  3466  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:10:39.928  3466  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 10:10:39.928  3466  3531 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:10:39.928  3466  3531 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:10:39.928  3466  3531 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:10:39.928  3466  3531 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:10:39.928  3466  3531 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 10:10:39.928  3466  3531 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 10:10:39.928  3466  3531 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 10:10:39.929  3466  3466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-31 10:10:39.929  3466  3531 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 10:10:39.931  3466  3466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 10:10:39.952  3466  3466 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 10:10:40.658  3466  3533 W jxcore-log: Initializing JXcore engine
03-31 10:10:40.658  3466  3533 W jxcore-log: JXcore engine is ready
,03-31 10:10:40.692  3533  3533 W Thread-353: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9476]" dev="sockfs" ino=9476 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-31 10:10:40.692  3533  3533 W Thread-353: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,03-31 10:10:40.692  3533  3533 W Thread-353: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[6572]" dev="sockfs" ino=6572 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-31 10:10:40.692  3533  3533 W Thread-353: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[19500]" dev="sockfs" ino=19500 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-31 10:10:40.723  3466  3533 W jxcore-log: Starting JXcore engine
,03-31 10:10:40.816  3466  3533 W jxcore-log: Platform android
03-31 10:10:40.816  3466  3533 W jxcore-log: 
03-31 10:10:40.816  3466  3533 W jxcore-log: Process ARCH arm
03-31 10:10:40.816  3466  3533 W jxcore-log: 
,03-31 10:10:41.057  3466  3533 I jxcore-log: JXcore Cordova bridge is ready!
03-31 10:10:41.057  3466  3533 I jxcore-log: 
03-31 10:10:41.057  3466  3533 W jxcore-log: JXcore engine is started
,03-31 10:10:41.060  3466  3531 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 10:10:41.061  3466  3466 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 10:10:42.071  3214  3240 W Babel   : aye TOOK TOO LONG! (15036ms > 10000ms)
,03-31 10:10:42.072  3214  3238 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-31 10:10:42.075   763  1305 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 10:10:42.079   763  3314 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 10:10:42.082  3214  3214 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-31 10:10:42.082  3214  3214 W Babel   : BAM#gBA: invalid account id: -1
03-31 10:10:42.083  3214  3214 W Babel   : BAM#gBA: invalid account id: -1
03-31 10:10:42.083  3214  3214 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-31 10:10:42.085   763   779 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 10:10:42.087   763  1285 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 10:10:42.171  1687  1736 I Finsky  : [140] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-31 10:10:42.172  3214  3251 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-31 10:10:42.172  1687  1687 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 10:10:44.171  1533  1548 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-31 10:10:48.332   763  3314 I ActivityManager: Killing 3037:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-31 10:10:48.421   763  3314 I ActivityManager: Killing 2960:com.android.settings/1000 (adj 15): empty #18
,03-31 10:10:48.429   763   869 D WifiService: Client connection lost with reason: 4
,03-31 10:10:49.570  1687  1687 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-31 10:10:49.592  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:10:49.597  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:10:49.598  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:10:49.992   763   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 10:10:49.992   763   868 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 10:10:50.123  3466  3533 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:10:50.123  3466  3533 I jxcore-log: 
03-31 10:10:50.125  3466  3533 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:10:50.125  3466  3533 I jxcore-log: 
,03-31 10:10:50.128  3466  3533 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:10:50.128  3466  3533 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:10:50.128  3466  3533 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 10:10:50.128  3466  3533 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:10:50.128  3466  3533 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:10:50.128  3466  3533 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:10:50.128  3466  3533 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:10:50.128  3466  3533 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:10:50.130  3466  3533 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:10:50.132  3466  3533 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:10:50.132  3466  3533 I jxcore-log: 
03-31 10:10:50.133  3466  3533 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:10:50.133  3466  3533 I jxcore-log: 
,03-31 10:10:50.246  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:10:50.369  1687  1723 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-31 10:10:50.369  1687  1723 I qtaguid : Untagging socket 37 failed errno=-22
03-31 10:10:50.369  1687  1723 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-31 10:10:50.373  1687  1687 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-31 10:10:50.446   763   943 I ActivityManager: Start proc 3586:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-31 10:10:50.449  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:10:50.472   201   201 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 198us total 12.172ms
,03-31 10:10:50.493   201   201 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 197us total 19.200ms
,03-31 10:10:50.515   201   201 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 444us total 21.078ms
,03-31 10:10:50.527  3586  3586 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 10:10:50.528  3586  3586 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 10:10:50.559  3586  3586 I MultiDex: VM with version 2.1.0 has multidex support
,03-31 10:10:50.559  3586  3586 I MultiDex: install
03-31 10:10:50.559  3586  3586 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 10:10:50.573  3586  3586 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-31 10:10:50.609  3586  3586 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 10:10:50.623  3586  3586 D ChimeraCfgMgr: Reading stored module config
,03-31 10:10:50.624  1511  1511 D WearableService: callingUid 10007, callindPid: 1511
,03-31 10:10:50.629  1511  2029 E MDM     : [170] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-31 10:10:50.631  1511  1511 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 10:10:50.635  1533  3620 D LocationInitializer: Restart initialization of location
,03-31 10:10:50.639  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:10:50.653  3466  3533 I jxcore-log: Unit Test app is loaded
03-31 10:10:50.653  3466  3533 I jxcore-log: 
,03-31 10:10:50.657  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-31 10:10:50.657  3466  3533 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:10:50.657  3466  3533 I jxcore-log: 
03-31 10:10:50.657  1511  3622 W FusedLocationProvider: location=null
,03-31 10:10:50.662  3466  3466 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 10:10:50.664  3466  3533 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
03-31 10:10:50.666  3466  3533 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-31 10:10:50.666  3466  3533 I jxcore-log: 
,03-31 10:10:50.669  3466  3533 I jxcore-log: logCallback not set !!!!
03-31 10:10:50.669  3466  3533 I jxcore-log: 
,03-31 10:10:50.672  3466  3533 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-31 10:10:50.672  3466  3533 I jxcore-log:   bluetooth: 'on',
03-31 10:10:50.672  3466  3533 I jxcore-log:   wifi: 'on',
03-31 10:10:50.672  3466  3533 I jxcore-log:   cellular: 'doNotCare',
03-31 10:10:50.672  3466  3533 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-31 10:10:50.672  3466  3533 I jxcore-log: 
,03-31 10:10:50.672  3466  3533 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-31 10:10:50.672  3466  3533 I jxcore-log: 
,03-31 10:10:50.721  3586  3618 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-31 10:10:50.727  3586  3586 D CAR.SERVICE: Connecting to CarCallService...
,03-31 10:10:50.739  3586  3586 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 10:10:50.739  3586  3586 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 10:10:50.747  3586  3586 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-31 10:10:50.752  3586  3586 D CAR.TEL.Service: Creating a new CarCallService.
,03-31 10:10:50.757  3586  3586 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-31 10:10:50.763   763  1166 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-31 10:10:50.763  3586  3586 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@6095ce2
03-31 10:10:50.764   763  1311 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-31 10:10:50.764  3586  3586 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-31 10:10:50.764  3586  3586 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-31 10:10:50.771  1687  1722 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-31 10:10:50.771  1687  1722 I qtaguid : Untagging socket 37 failed errno=-22
03-31 10:10:50.772  1687  1722 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-31 10:10:50.826  3586  3601 D CAR.SERVICE: Package validated; name: com.android.vending
,03-31 10:10:50.895  3629  3629 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 10:10:50.897  3629  3629 D AndroidRuntime: CheckJNI is OFF
,03-31 10:10:50.989  3629  3629 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 10:10:50.995   763   831 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-31 10:10:50.995   763   831 I ActivityManager: Killing 3466:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-31 10:10:51.030   763   869 D WifiService: Client connection lost with reason: 4
,03-31 10:10:51.031   763  1165 I WindowState: WIN DEATH: Window{44cd6b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-31 10:10:51.031   763  3314 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1589519a)
,03-31 10:10:51.032   763   870 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 10:10:51.032   763   870 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 10:10:51.053   763   842 W PackageSettings: Skipping PackageSetting{3c2e4d65 com.example.hello/10116} due to missing metadata
,03-31 10:10:51.262   763   831 W ActivityManager: Force removing ActivityRecord{2a5427e6 u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-31 10:10:51.267   763  1285 W ActivityManager: Spurious death for ProcessRecord{3970dacb 3466:com.test.thalitest/u0a49}, curProc for 3466: null
03-31 10:10:51.267   763   842 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-31 10:10:51.283  1129  1129 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-31 10:10:51.285  1511  1640 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-31 10:10:51.288   763   886 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-31 10:10:51.291   763   850 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 10:10:51.316  1533  1533 I art     : Explicit concurrent mark sweep GC freed 4226(181KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 23MB/38MB, paused 2.008ms total 46.468ms
,03-31 10:10:51.334   908   908 I art     : Explicit concurrent mark sweep GC freed 11790(577KB) AllocSpace objects, 3(17MB) LOS objects, 28% free, 40MB/56MB, paused 2.194ms total 60.420ms
,03-31 10:10:51.338  1388  3650 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-31 10:10:51.340  1129  3648 I Keyboard.Facilitator.DecoderInitializer: run()
,03-31 10:10:51.350  1129  3648 I Decoder : createOrResetDecoder
,03-31 10:10:51.354   763   763 I art     : Explicit concurrent mark sweep GC freed 24675(1396KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 1.768ms total 76.904ms
,03-31 10:10:51.366   763   943 I ActivityManager: Start proc 3652:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-31 10:10:51.374   763  1039 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3466 uid 10049
,03-31 10:10:51.380  1129  1129 I Keyboard.Facilitator: onFinishInput()
,03-31 10:10:51.385  1448  1448 I art     : Explicit concurrent mark sweep GC freed 4979(362KB) AllocSpace objects, 7(154KB) LOS objects, 40% free, 21MB/36MB, paused 899us total 115.432ms
,03-31 10:10:51.423  1129  3648 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-31 10:10:51.430  1312  1312 I art     : Explicit concurrent mark sweep GC freed 2854(161KB) AllocSpace objects, 4(369KB) LOS objects, 38% free, 25MB/41MB, paused 1.491ms total 28.618ms
,03-31 10:10:51.439   763   763 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 10:10:51.439   763   763 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-31 10:10:51.445  3652  3652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-31 10:10:51.456  1533  3672 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-31 10:10:51.456  1533  3672 D AccountUtils: Clearing selected account for com.test.thalitest
,03-31 10:10:51.464  1129  3648 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-31 10:10:51.465  1511  1511 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-31 10:10:51.465  1511  1511 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-31 10:10:51.468  1448  1448 W LocationOracle: Best location was null
03-31 10:10:51.469  1448  1448 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-31 10:10:51.471  1533  3672 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-31 10:10:51.485  1448  3680 I MicroRecognitionRunner: Starting detection.
,03-31 10:10:51.486  1448  3681 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@18c33a6a
,03-31 10:10:51.487  1129  3648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 10:10:51.487  1129  3648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-31 10:10:51.491  1129  3648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-31 10:10:51.491  1129  3648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-31 10:10:51.492   190  3683 I AudioFlinger: AudioFlinger's thread 0xb447f000 ready to run
,03-31 10:10:51.496  1129  3648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 10:10:51.496  1129  3648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-31 10:10:51.503  1129  3648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 10:10:51.503  1129  3648 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 10:10:51.503  1129  3648 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-31 10:10:51.503  1129  3648 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 10:10:51.503  1129  3648 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 10:10:51.503  1129  3648 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-31 10:10:51.518  1448  3681 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@18c33a6a
,03-31 10:10:51.527   190  3683 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-31 10:10:51.527   190  3683 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-31 10:10:51.527   190  3683 D         : Failed to fetch the lookup information of the device 0000003E 
03-31 10:10:51.527   190  3683 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-31 10:10:51.527   190  3683 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-31 10:10:51.534   190  3683 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-31 10:10:51.552  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-31 10:10:51.554  1533  3672 I GMPM-SVC: App measurement is starting up, version: 8703
03-31 10:10:51.554  1533  3672 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-31 10:10:51.561  1448  3688 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-31 10:10:51.581  1511  1615 W GCoreFlp: No location to return for getLastLocation()
03-31 10:10:51.581  1533  3679 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:10:51.582  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-31 10:10:51.594  1533  3679 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 10:10:51.611   763   842 I art     : Explicit concurrent mark sweep GC freed 18863(1582KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 4.368ms total 238.512ms
,03-31 10:10:51.625  1448  1448 I MicroDetectionWorker: onReady
,03-31 10:10:51.630   763   763 I ActivityManager: Start proc 3699:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,03-31 10:10:51.639  1533  3672 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-31 10:10:51.656  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-31 10:10:51.663  1533  3715 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,03-31 10:10:51.663  1533  3715 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,03-31 10:10:51.663  1533  3715 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-31 10:10:51.663  1533  3715 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-31 10:10:51.669  1533  3715 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,03-31 10:10:51.669  1533  3715 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-31 10:10:51.670  1533  3715 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-31 10:10:51.674  1533  3715 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-31 10:10:51.674  1533  3715 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-31 10:10:51.675  1533  3715 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,03-31 10:10:51.676  1533  3715 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,03-31 10:10:51.677  1533  3715 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,03-31 10:10:51.677  1533  3715 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-31 10:10:51.683   763  3698 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 10:10:51.683   763   870 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 10:10:51.683   763   870 D ConnectivityService: apparently satisfied.  currentScore=60
,03-31 10:10:51.684  1533  3718 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 10:10:51.698  1533  1654 I Icing   : doRemovePackageData com.test.thalitest
,03-31 10:10:51.705  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-31 10:10:51.716  1448  3688 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 156 ms] updated apps [took 156 ms] 
,03-31 10:10:51.719  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-31 10:10:51.742  3629  3629 I art     : System.exit called, status: 0
03-31 10:10:51.742  3629  3629 I AndroidRuntime: VM exiting with result code 0.
,03-31 10:10:51.778  1312  1437 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-31 10:10:51.798   763   842 I ActivityManager: Start proc 3724:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-31 10:10:51.845   763  1305 I ActivityManager: Start proc 3744:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-31 10:10:51.867   763  1039 I ActivityManager: Killing 3194:com.android.providers.calendar/u0a1 (adj 15): empty #17
,03-31 10:10:51.896  1312  1504 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-31 10:10:51.896  1312  1504 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-31 10:10:51.918  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:10:51.921  1533  3677 W DriveInitializer: Awaiting to be initialized
,03-31 10:10:51.922   763  1285 I ActivityManager: Killing 2817:com.google.android.gms.unstable/u0a7 (adj 15): empty #17
,03-31 10:10:51.923  1533  3765 W DriveInitializer: Background init thread started
,03-31 10:10:51.925  1533  3765 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
,03-31 10:10:51.927  1533  3765 E DocListDatabase: Failed to delete from ContentFileDeletionLock163 table
03-31 10:10:51.927  1533  3765 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 10:10:51.927  1533  3765 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 10:10:51.927  1533  3765 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 10:10:51.927  1533  3765 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 10:10:51.927  1533  3765 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 10:10:51.927  1533  3765 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 10:10:51.927  1533  3765 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-31 10:10:51.927  1533  3765 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-31 10:10:51.927  1533  3765 E DocListDatabase: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-31 10:10:51.927  1533  3765 W DriveInitializer: Background init thread ended
03-31 10:10:51.928  1533  3677 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-31 10:10:51.928  1533  3677 E DriveAsyncService: disk I/O error (code 3850)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(:com.google.android.gms:486)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(:com.google.android.gms:461)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(:com.google.android.gms:1519)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(:com.google.android.gms:16)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-31 10:10:51.928  1533  3677 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-31 10:10:51.945  3744  3744 D ExternalStorage: After updating volumes, found 1 active roots
,03-31 10:10:51.981  1533  3765 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-31 10:10:51.981  1533  3765 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-31 10:10:51.981  1533  3765 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-31 10:10:51.981  1533  3765 I GCore-Chimera-Crash: ==
03-31 10:10:51.981  1533  3765 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
03-31 10:10:51.981  1533  3765 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-31 10:10:51.981  1533  3765 E AndroidRuntime: Process: com.google.android.gms, PID: 1533
03-31 10:10:51.981  1533  3765 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 10:10:51.981  1533  3765 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 10:10:51.981  1533  3765 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 10:10:51.981  1533  3765 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 10:10:51.981  1533  3765 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 10:10:51.981  1533  3765 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 10:10:51.981  1533  3765 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-31 10:10:51.981  1533  3765 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-31 10:10:51.981  1533  3765 E AndroidRuntime: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
,03-31 10:10:51.982  1448  1448 E LocationReceiver: Received bad location: null
,03-31 10:10:51.990   763  3768 E DropBoxManagerService: Can't write: system_app_crash
03-31 10:10:51.990   763  3768 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
03-31 10:10:51.990   763  3768 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 10:10:51.990   763  3768 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 10:10:51.990   763  3768 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 10:10:51.990   763  3768 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 10:10:51.990   763  3768 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 10:10:51.990   763  3768 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 10:10:51.990   763  3768 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 10:10:51.990   763  3768 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 10:10:51.990   763  3768 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 10:10:51.990   763  3768 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 10:10:51.990   763  3768 E DropBoxManagerService: 	... 5 more
,03-31 10:10:52.001   763  3769 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 10:10:52.002   763   831 D Atlas   : Validating map...
,03-31 10:10:52.034   176   176 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-31 10:10:52.034   176   176 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
03-31 10:10:52.034   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
03-31 10:10:52.034   176   176 E qdoverlay: MdpData failed to play
03-31 10:10:52.034   176   176 E qdoverlay: == Dump MdpData start ==
03-31 10:10:52.034   176   176 E qdoverlay: == Dump OvFD fd=58 path=/dev/graphics/fb0 start/end ==
03-31 10:10:52.034   176   176 E qdoverlay: mOvData msmfb_overlay_data id=64
03-31 10:10:52.034   176   176 E qdoverlay: data msmfb_data offset=0 memid=42 id=0 flags=0x0 priv=0
03-31 10:10:52.034   176   176 E qdoverlay: == Dump MdpData end ==
03-31 10:10:52.034   176   176 E qdhwcomposer: draw: queueBuffer failed for display:0 
03-31 10:10:52.034   176   176 E qdhwcomposer: hwc_set_primary: MDPComp draw failed
03-31 10:10:52.034   176   176 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-31 10:10:52.034   176   176 E qdhwcomposer: hwc_set_primary: display commit fail!
,03-31 10:10:52.036   763  3769 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
03-31 10:10:52.036   763  3769 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 10:10:52.039   763  3769 D OpenGLRenderer: Enabling debug mode 0
,03-31 10:10:52.050   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-31 10:10:52.050   176   176 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
,03-31 10:10:52.050   176   176 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-31 10:10:52.050   176   176 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-31 10:10:52.051   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 10:10:52.051   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 10:10:52.051   176   176 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-31 10:10:52.051   176   176 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-31 10:10:52.051   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 10:10:52.051   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 10:10:52.051   176   176 E qdoverlay: Ctrl commit failed set overlay
03-31 10:10:52.051   176   176 E qdhwcomposer: configureLowRes: commit failed for low res panel
03-31 10:10:52.051   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-31 10:10:52.051   176   176 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-31 10:10:52.051   176   176 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
03-31 10:10:52.051   176   176 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
03-31 10:10:52.051   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 10:10:52.051   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 10:10:52.051   176   176 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
03-31 10:10:52.051   176   176 E qdoverlay: src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
03-31 10:10:52.051   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=75
03-31 10:10:52.051   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=75
03-31 10:10:52.051   176   176 E qdoverlay: Ctrl commit failed set overlay
03-31 10:10:52.051   176   176 E qdhwcomposer: configure: commit fails
03-31 10:10:52.051   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-31 10:10:52.051   176   176 E qdoverlay: MdpCtrl close error in unset
,03-31 10:10:52.271   176   176 E qdoverlay: GenericPipe failed to close ctrl

```
