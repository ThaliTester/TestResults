#### Test 63680118f1433de_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-22 15:37:58.982  1549  2414 I CheckinService: Done disabling old GoogleServicesFramework version
,03-22 15:37:59.268  3481  3481 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-22 15:37:59.270  3481  3481 D AndroidRuntime: CheckJNI is OFF
03-22 15:37:59.372  3481  3481 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-22 15:37:59.375   762  1100 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-22 15:37:59.380   762  1100 V WindowManager: addAppToken: AppWindowToken{42291dc token=Token{9fc264f ActivityRecord{53448ae u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-22 15:37:59.385   762   835 V WindowManager: Adding window Window{2f309047 u0 Starting com.test.thalitest} at 2 of 7 (after Window{13ed5d1e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-22 15:37:59.389  1373  1395 W SearchService: Abort, client detached.
03-22 15:37:59.391  3481  3481 D AndroidRuntime: Shutting down VM
03-22 15:37:59.407   762   952 I ActivityManager: Start proc 3502:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-22 15:37:59.418   201   201 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 207us total 11.333ms
03-22 15:37:59.445  1373  1373 I MicroDetector: Keeping mic open: false
03-22 15:37:59.445  1373  1373 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@3a9ce079
03-22 15:37:59.445  1373  1581 I DeviceStateChecker: DeviceStateChecker cancelled
03-22 15:37:59.459   201   201 I art     : Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 394us total 21.515ms
03-22 15:37:59.482   201   201 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 209us total 13.696ms
03-22 15:37:59.487   190  1590 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-22 15:37:59.487   190  1590 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-22 15:37:59.493  1373  1586 I MicroRecognitionRunner: Detection finished
03-22 15:37:59.494  1373  1580 I MicroRecognitionRunner: Stopping hotword detection.
03-22 15:37:59.530  3502  3502 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
03-22 15:37:59.539  3502  3502 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 7744-7745)
03-22 15:37:59.539  3502  3502 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-22 15:37:59.548  3502  3502 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {231970e6}
03-22 15:37:59.548  3502  3502 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-22 15:37:59.549  3502  3502 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
03-22 15:37:59.557   762  1165 I ActivityManager: Killing 3092:com.google.android.deskclock/u0a33 (adj 15): empty #17
03-22 15:37:59.558  3502  3502 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
03-22 15:37:59.572  3502  3502 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-22 15:37:59.610   762   834 D BluetoothManagerService: Message: 20
,03-22 15:37:59.610   762   834 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b9c2a0c:true
,03-22 15:37:59.633  3502  3502 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-22 15:37:59.633  3502  3502 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-22 15:37:59.677  3502  3502 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-22 15:37:59.677  3502  3502 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-22 15:37:59.688  3502  3502 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-22 15:37:59.689  3502  3502 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-22 15:37:59.695  3502  3502 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-22 15:37:59.696  3502  3502 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
03-22 15:37:59.696  3502  3502 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,03-22 15:37:59.697  3502  3502 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-22 15:37:59.702  3502  3502 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,03-22 15:37:59.706  3502  3502 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-22 15:37:59.711  3502  3502 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-22 15:37:59.711  3502  3502 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-22 15:37:59.809   762  1165 I art     : Explicit concurrent mark sweep GC freed 21712(1040KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.166ms total 83.864ms
,03-22 15:37:59.813  3502  3565 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-22 15:37:59.822  3502  3502 D Atlas   : Validating map...
,03-22 15:37:59.930   176   176 D SurfaceFlinger: shader cache generated - 24 shaders in 130.280624 ms
,03-22 15:37:59.952   762  1164 V WindowManager: Adding window Window{3d5e8a7d u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2f309047 u0 Starting com.test.thalitest})
,03-22 15:37:59.959   762   858 D WifiService: New client listening to asynchronous messages
,03-22 15:37:59.973   762   952 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-22 15:37:59.974   762   859 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,03-22 15:37:59.974   762   859 D ConnectivityService: apparently satisfied.  currentScore=60
,03-22 15:37:59.976  3502  3567 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-22 15:38:00.007  3502  3565 I OpenGLRenderer: Initialized EGL, version 1.4
,03-22 15:38:00.014  3502  3565 D OpenGLRenderer: Enabling debug mode 0
,03-22 15:38:00.052  3502  3569 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-22 15:38:00.089   762   835 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +699ms
,03-22 15:38:00.089  3502  3502 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-22 15:38:00.106  1098  1098 I Keyboard.Facilitator: onFinishInput()
,03-22 15:38:00.137  3502  3502 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-22 15:38:00.138  3502  3502 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3502
,03-22 15:38:00.337  3502  3502 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-22 15:38:00.446  3502  3578 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362628480
03-22 15:38:00.456  3502  3578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-22 15:38:00.456  3502  3578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-22 15:38:00.456  3502  3578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-22 15:38:00.456  3502  3578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-22 15:38:00.456  3502  3578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-22 15:38:00.456  3502  3578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1da43991 added. We now have 1 listener(s)
03-22 15:38:00.456   762  1164 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-22 15:38:00.459  3502  3578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
03-22 15:38:00.461  3502  3578 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
03-22 15:38:00.462  3502  3578 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-22 15:38:00.463  3502  3578 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-22 15:38:00.466  3502  3578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12345764 added. We now have 1 listener(s)
03-22 15:38:00.467  3502  3578 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-22 15:38:00.469  3502  3578 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
03-22 15:38:00.471  3502  3578 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-22 15:38:00.471  3502  3578 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-22 15:38:00.473  3502  3578 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-22 15:38:00.474   762   777 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-22 15:38:00.475  3502  3578 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-22 15:38:00.480  3502  3578 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-22 15:38:00.480  3502  3578 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-22 15:38:00.480  3502  3578 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-22 15:38:00.480  3502  3578 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-22 15:38:00.480  3502  3578 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-22 15:38:00.480  3502  3578 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-22 15:38:00.480  3502  3578 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-22 15:38:00.480  3502  3578 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-22 15:38:00.480  3502  3578 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-22 15:38:00.480  3502  3578 D io.jxcore.node.ConnectivityMonitor: start: OK
03-22 15:38:00.480  3502  3578 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-22 15:38:00.494  3502  3502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-22 15:38:00.496  3502  3502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-22 15:38:00.517  3502  3502 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-22 15:38:01.048   762   857 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-60
,03-22 15:38:01.099  3502  3579 W jxcore-log: Initializing JXcore engine
03-22 15:38:01.099  3502  3579 W jxcore-log: JXcore engine is ready
,03-22 15:38:01.124  3579  3579 W Thread-357: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9608]" dev="sockfs" ino=9608 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-22 15:38:01.124  3579  3579 W Thread-357: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-22 15:38:01.124  3579  3579 W Thread-357: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[9696]" dev="sockfs" ino=9696 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-22 15:38:01.124  3579  3579 W Thread-357: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[19613]" dev="sockfs" ino=19613 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-22 15:38:01.156  3502  3579 W jxcore-log: Starting JXcore engine
,03-22 15:38:01.273  3502  3579 W jxcore-log: Platform android
03-22 15:38:01.273  3502  3579 W jxcore-log: 
03-22 15:38:01.273  3502  3579 W jxcore-log: Process ARCH arm
03-22 15:38:01.273  3502  3579 W jxcore-log: 
,03-22 15:38:01.484  3502  3579 I jxcore-log: JXcore Cordova bridge is ready!
03-22 15:38:01.484  3502  3579 I jxcore-log: 
03-22 15:38:01.484  3502  3579 W jxcore-log: JXcore engine is started
,03-22 15:38:01.489  3502  3578 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-22 15:38:01.490  3502  3502 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-22 15:38:03.718  3361  3385 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-22 15:38:03.719  3361  3387 W Babel   : aye TOOK TOO LONG! (15034ms > 10000ms)
,03-22 15:38:03.746   762  3275 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-22 15:38:03.749   762  1164 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-22 15:38:03.751  3361  3361 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-22 15:38:03.751  3361  3361 W Babel   : BAM#gBA: invalid account id: -1
03-22 15:38:03.751  3361  3361 W Babel   : BAM#gBA: invalid account id: -1
03-22 15:38:03.751  3361  3361 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-22 15:38:03.752   762   777 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-22 15:38:03.754   762  1165 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-22 15:38:03.774  3361  3395 W Babel   : aye TOOK TOO LONG! (15033ms > 10000ms)
,03-22 15:38:03.876  1645  1716 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
03-22 15:38:03.876  1645  1645 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-22 15:38:04.644  1549  1563 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-22 15:38:10.106  1645  1645 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-22 15:38:10.126  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 15:38:10.134  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 15:38:10.136  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 15:38:10.548  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 15:38:10.759  1645  1700 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-22 15:38:10.759  1645  1700 I qtaguid : Untagging socket 38 failed errno=-22
03-22 15:38:10.759  1645  1700 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-22 15:38:10.762  1645  1645 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-22 15:38:10.807  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 15:38:10.827  3502  3579 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-22 15:38:10.827  3502  3579 I jxcore-log: 
03-22 15:38:10.829  3502  3579 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-22 15:38:10.829  3502  3579 I jxcore-log: 
,03-22 15:38:10.844  3502  3579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-22 15:38:10.844  3502  3579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-22 15:38:10.844  3502  3579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-22 15:38:10.844  3502  3579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-22 15:38:10.844  3502  3579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-22 15:38:10.844  3502  3579 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-22 15:38:10.844  3502  3579 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-22 15:38:10.844  3502  3579 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-22 15:38:10.846  3502  3579 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-22 15:38:10.847  3502  3579 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-22 15:38:10.847  3502  3579 I jxcore-log: 
03-22 15:38:10.848   762  1189 I ActivityManager: Start proc 3642:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
03-22 15:38:10.849  3502  3579 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-22 15:38:10.849  3502  3579 I jxcore-log: 
,03-22 15:38:10.886  3642  3642 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-22 15:38:10.887  3642  3642 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-22 15:38:10.910  3642  3642 I MultiDex: VM with version 2.1.0 has multidex support
03-22 15:38:10.910  3642  3642 I MultiDex: install
03-22 15:38:10.910  3642  3642 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-22 15:38:10.924  3642  3642 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-22 15:38:10.955  3642  3642 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-22 15:38:10.965  3642  3642 D ChimeraCfgMgr: Reading stored module config
,03-22 15:38:10.970  1511  1511 D WearableService: callingUid 10007, callindPid: 1511
,03-22 15:38:10.975  1511  1947 E MDM     : [177] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-22 15:38:10.977  1511  1511 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-22 15:38:10.977  1549  3669 D LocationInitializer: Restart initialization of location
,03-22 15:38:10.985  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 15:38:11.000  1511  1623 W GCoreFlp: No location to return for getLastLocation()
,03-22 15:38:11.000  1511  3670 W FusedLocationProvider: location=null
,03-22 15:38:11.084  3642  3642 D CAR.SERVICE: Connecting to CarCallService...
,03-22 15:38:11.098  3642  3668 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-22 15:38:11.099  3642  3642 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-22 15:38:11.100  3642  3642 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-22 15:38:11.109  3642  3642 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-22 15:38:11.115  3642  3642 D CAR.TEL.Service: Creating a new CarCallService.
,03-22 15:38:11.116  3642  3642 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
03-22 15:38:11.118   762   777 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-22 15:38:11.118  3642  3642 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@17ab01e7
,03-22 15:38:11.119   762  2225 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-22 15:38:11.119  3642  3642 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-22 15:38:11.119  3642  3642 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-22 15:38:11.192  1645  1701 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-22 15:38:11.192  1645  1701 I qtaguid : Untagging socket 38 failed errno=-22
03-22 15:38:11.192  1645  1701 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-22 15:38:11.225  3642  3662 D CAR.SERVICE: Package validated; name: com.android.vending
,03-22 15:38:11.391  3502  3579 I jxcore-log: Unit Test app is loaded
03-22 15:38:11.391  3502  3579 I jxcore-log: 
,03-22 15:38:11.395  3502  3579 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-22 15:38:11.395  3502  3579 I jxcore-log: 
,03-22 15:38:11.399  3502  3502 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-22 15:38:11.401  3502  3579 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
03-22 15:38:11.403  3502  3579 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-22 15:38:11.403  3502  3579 I jxcore-log: 
,03-22 15:38:11.405  3502  3579 I jxcore-log: logCallback not set !!!!
03-22 15:38:11.405  3502  3579 I jxcore-log: 
,03-22 15:38:11.408  3502  3579 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-22 15:38:11.408  3502  3579 I jxcore-log:   bluetooth: 'on',
03-22 15:38:11.408  3502  3579 I jxcore-log:   wifi: 'on',
03-22 15:38:11.408  3502  3579 I jxcore-log:   cellular: 'doNotCare',
03-22 15:38:11.408  3502  3579 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-22 15:38:11.408  3502  3579 I jxcore-log: 
03-22 15:38:11.408  3502  3579 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-22 15:38:11.408  3502  3579 I jxcore-log: 
,03-22 15:38:11.629  3691  3691 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-22 15:38:11.632  3691  3691 D AndroidRuntime: CheckJNI is OFF
,03-22 15:38:11.718  3691  3691 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-22 15:38:11.724   762   830 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-22 15:38:11.724   762   830 I ActivityManager: Killing 3502:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-22 15:38:11.759   762  3275 I WindowState: WIN DEATH: Window{3d5e8a7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-22 15:38:11.759   762  1190 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3b409ad7)
03-22 15:38:11.759   762   858 D WifiService: Client connection lost with reason: 4
03-22 15:38:11.759   762   859 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-22 15:38:11.759   762   859 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-22 15:38:11.763   762   841 W PackageSettings: Skipping PackageSetting{9a622e8 com.example.hello/10116} due to missing metadata
,03-22 15:38:11.834   762   830 W ActivityManager: Force removing ActivityRecord{53448ae u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-22 15:38:11.838   762  1100 W ActivityManager: Spurious death for ProcessRecord{288eeead 3502:com.test.thalitest/u0a49}, curProc for 3502: null
,03-22 15:38:11.840   762   841 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-22 15:38:11.842  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 15:38:11.855   762   883 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-22 15:38:11.869  1511  1633 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-22 15:38:11.869   762   849 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-22 15:38:11.884  1098  1098 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-22 15:38:11.904   904   904 I art     : Explicit concurrent mark sweep GC freed 7288(333KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 695us total 53.268ms
,03-22 15:38:11.920  1549  1549 I art     : Explicit concurrent mark sweep GC freed 4821(215KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 23MB/38MB, paused 1.014ms total 76.603ms
,03-22 15:38:11.932  1098  3713 I Keyboard.Facilitator.DecoderInitializer: run()
,03-22 15:38:11.935  1098  3713 I Decoder : createOrResetDecoder
,03-22 15:38:11.943   762   762 I art     : Explicit concurrent mark sweep GC freed 27809(1800KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.056ms total 91.521ms
03-22 15:38:11.944   762   841 I art     : WaitForGcToComplete blocked for 25.109ms for cause Explicit
,03-22 15:38:11.951  3030  3714 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-22 15:38:11.955  1373  1373 I art     : Explicit concurrent mark sweep GC freed 3269(285KB) AllocSpace objects, 7(154KB) LOS objects, 40% free, 22MB/37MB, paused 1.014ms total 110.601ms
,03-22 15:38:11.964   762   952 I ActivityManager: Start proc 3718:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-22 15:38:11.988  1511  1511 I ConfigService: onCreate
,03-22 15:38:12.002  3718  3718 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-22 15:38:12.017  1549  3738 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-22 15:38:12.017  1549  3738 D AccountUtils: Clearing selected account for com.test.thalitest
,03-22 15:38:12.031  1098  3713 I Keyboard.Facilitator.MainLanguageModelLoader: run()
03-22 15:38:12.032  1549  3738 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-22 15:38:12.037   762   762 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-22 15:38:12.037   762   762 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-22 15:38:12.045   762   777 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3502 uid 10049
,03-22 15:38:12.050  1098  1098 I Keyboard.Facilitator: onFinishInput()
,03-22 15:38:12.061  1511  1511 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-22 15:38:12.061  1511  1511 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-22 15:38:12.077  1549  3742 W BaseAppContext: Using Auth Proxy for data requests.
,03-22 15:38:12.084  1373  1373 W LocationOracle: Best location was null
03-22 15:38:12.084  1373  1373 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-22 15:38:12.089  1549  3742 W BaseAppContext: Using Auth Proxy for data requests.
,03-22 15:38:12.098  1549  3738 I GMPM-SVC: App measurement is starting up, version: 8703
03-22 15:38:12.099  1549  3738 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-22 15:38:12.101  1373  3747 I MicroRecognitionRunner: Starting detection.
03-22 15:38:12.102  1373  3748 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@2f3ce373
,03-22 15:38:12.107   190  3750 I AudioFlinger: AudioFlinger's thread 0xb4d34000 ready to run
,03-22 15:38:12.111  1220  1220 I art     : Explicit concurrent mark sweep GC freed 2864(161KB) AllocSpace objects, 7(612KB) LOS objects, 38% free, 25MB/41MB, paused 2.178ms total 39.744ms
,03-22 15:38:12.117  1373  3748 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@2f3ce373
,03-22 15:38:12.123  1098  3713 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-22 15:38:12.126  1098  3713 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-22 15:38:12.126  1098  3713 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-22 15:38:12.127   190  3750 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-22 15:38:12.127   190  3750 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-22 15:38:12.127   190  3750 D         : Failed to fetch the lookup information of the device 0000003E 
03-22 15:38:12.127   190  3750 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-22 15:38:12.127   190  3750 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-22 15:38:12.132   190  3750 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-22 15:38:12.135  1098  3713 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-22 15:38:12.135  1098  3713 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-22 15:38:12.136  1098  3713 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-22 15:38:12.136  1098  3713 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-22 15:38:12.137  1098  3713 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-22 15:38:12.137  1098  3713 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-22 15:38:12.137  1098  3713 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-22 15:38:12.137  1098  3713 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-22 15:38:12.137  1098  3713 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-22 15:38:12.137  1098  3713 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-22 15:38:12.155  1549  1610 I Icing   : doRemovePackageData com.test.thalitest
,03-22 15:38:12.174  1549  3738 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-22 15:38:12.194  1511  1623 W GCoreFlp: No location to return for getLastLocation()
,03-22 15:38:12.195  1549  3760 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-22 15:38:12.195  1549  3760 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,03-22 15:38:12.195  1549  3760 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-22 15:38:12.195  1549  3760 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-22 15:38:12.200  1549  3760 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-22 15:38:12.200  1549  3760 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-22 15:38:12.200  1373  3763 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
03-22 15:38:12.200  1549  3760 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-22 15:38:12.206  1549  3760 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-22 15:38:12.206  1549  3760 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-22 15:38:12.206  1549  3760 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
03-22 15:38:12.207  1549  3760 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
03-22 15:38:12.207  1549  3760 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,03-22 15:38:12.207  1549  3760 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-22 15:38:12.223  1373  1373 I MicroDetectionWorker: onReady
03-22 15:38:12.223  1511  1623 W GCoreFlp: No location to return for getLastLocation()
,03-22 15:38:12.233   762   841 I art     : Explicit concurrent mark sweep GC freed 15784(1032KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 3.135ms total 284.813ms
,03-22 15:38:12.235  1511  1623 W GCoreFlp: No location to return for getLastLocation()
,03-22 15:38:12.258   762   762 I ActivityManager: Start proc 3768:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,03-22 15:38:12.265  1511  1623 W GCoreFlp: No location to return for getLastLocation()
,03-22 15:38:12.267   762  2225 I ActivityManager: Killing 3114:com.google.android.keep/u0a52 (adj 15): empty #17
,03-22 15:38:12.290  1220  1439 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-22 15:38:12.329  1511  1623 W GCoreFlp: No location to return for getLastLocation()
,03-22 15:38:12.333   762  3762 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-22 15:38:12.333   762   859 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-22 15:38:12.333   762   859 D ConnectivityService: apparently satisfied.  currentScore=60
03-22 15:38:12.334  1549  3785 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-22 15:38:12.342  1511  1623 W GCoreFlp: No location to return for getLastLocation()
,03-22 15:38:12.345  1373  3763 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 145 ms] updated apps [took 145 ms] 
,03-22 15:38:12.346  3691  3691 I art     : System.exit called, status: 0
03-22 15:38:12.346  3691  3691 I AndroidRuntime: VM exiting with result code 0.
,03-22 15:38:12.377   762   841 I ActivityManager: Start proc 3787:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-22 15:38:12.412   762  1100 I ActivityManager: Killing 3144:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-22 15:38:12.470   762  1164 I ActivityManager: Start proc 3809:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-22 15:38:12.475  1645  1700 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-22 15:38:12.475  1645  1700 I qtaguid : Untagging socket 38 failed errno=-22
03-22 15:38:12.475  1645  1700 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-22 15:38:12.485   762  3761 I ActivityManager: Killing 2546:com.google.android.gm/u0a41 (adj 15): empty #17
,03-22 15:38:12.520  1549  3740 W DriveInitializer: Awaiting to be initialized
,03-22 15:38:12.522  1549  3828 W DriveInitializer: Background init thread started
,03-22 15:38:12.523   762  3761 I ActivityManager: Killing 2927:com.google.android.apps.photos/u0a83 (adj 15): empty #17
,03-22 15:38:12.544  3809  3809 D ExternalStorage: After updating volumes, found 1 active roots
,03-22 15:38:12.554  1549  3828 E DocListDatabase: Failed to delete from ContentFileDeletionLock163 table
03-22 15:38:12.554  1549  3828 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-22 15:38:12.554  1549  3828 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-22 15:38:12.554  1549  3828 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-22 15:38:12.554  1549  3828 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-22 15:38:12.554  1549  3828 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-22 15:38:12.554  1549  3828 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-22 15:38:12.554  1549  3828 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-22 15:38:12.554  1549  3828 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-22 15:38:12.554  1549  3828 E DocListDatabase: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-22 15:38:12.554  1549  3828 W DriveInitializer: Background init thread ended
03-22 15:38:12.555  1549  3740 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-22 15:38:12.556  1549  3740 E DriveAsyncService: disk I/O error (code 3850)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(:com.google.android.gms:486)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(:com.google.android.gms:461)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(:com.google.android.gms:1519)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(:com.google.android.gms:16)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-22 15:38:12.556  1549  3740 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-22 15:38:12.566  1220  1501 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-22 15:38:12.566  1220  1501 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-22 15:38:12.575  1549  3828 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-22 15:38:12.575  1549  3828 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-22 15:38:12.575  1549  3828 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-22 15:38:12.575  1549  3828 I GCore-Chimera-Crash: ==
03-22 15:38:12.575  1549  3828 I GCore-Chimera-Crash: GCore-Chimera-Crash
,--------- beginning of crash
03-22 15:38:12.575  1549  3828 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-22 15:38:12.575  1549  3828 E AndroidRuntime: Process: com.google.android.gms, PID: 1549
03-22 15:38:12.575  1549  3828 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-22 15:38:12.575  1549  3828 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-22 15:38:12.575  1549  3828 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-22 15:38:12.575  1549  3828 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-22 15:38:12.575  1549  3828 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-22 15:38:12.575  1549  3828 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-22 15:38:12.575  1549  3828 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-22 15:38:12.575  1549  3828 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-22 15:38:12.575  1549  3828 E AndroidRuntime: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
,03-22 15:38:12.578   925  2094 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10049)] disk I/O error
03-22 15:38:12.579  1645  1714 E PlayEventLogger: Could not write string (a: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: b: 3600
03-22 15:38:12.579  1645  1714 E PlayEventLogger: c: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: e: ""
03-22 15:38:12.579  1645  1714 E PlayEventLogger: f: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: g: 0
03-22 15:38:12.579  1645  1714 E PlayEventLogger: h: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: j: 0
03-22 15:38:12.579  1645  1714 E PlayEventLogger: k: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: a: 1458657492573
03-22 15:38:12.579  1645  1714 E PlayEventLogger: b: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: c: 0
03-22 15:38:12.579  1645  1714 E PlayEventLogger: d: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: e: 0
03-22 15:38:12.579  1645  1714 E PlayEventLogger: f: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: g: "4"
03-22 15:38:12.579  1645  1714 E PlayEventLogger: h: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: i: 0
03-22 15:38:12.579  1645  1714 E PlayEventLogger: j: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: k: 0
03-22 15:38:12.579  1645  1714 E PlayEventLogger: l: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: m: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: n: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: p: ""
03-22 15:38:12.579  1645  1714 E PlayEventLogger: q: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: s: "\"\031\010\203\001\032\015daily_hygiene\222\001\004h\000p\003"
03-22 15:38:12.579  1645  1714 E PlayEventLogger: t: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: u: ""
03-22 15:38:12.579  1645  1714 E PlayEventLogger: v: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: w: ""
03-22 15:38:12.579  1645  1714 E PlayEventLogger: x: false
03-22 15:38:12.579  1645  1714 E PlayEventLogger: z: ""
03-22 15:38:12.579  1645  1714 E PlayEventLogger: ar: 42
03-22 15:38:12.579  1645  1714 E PlayEventLogger: ) to file: write failed: EBADF (Bad file number)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: java.io.IOException: write failed: EBADF (Bad file number)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at libcore.io.IoBridge.write(IoBridge.java:502)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at java.io.FileOutputStream.write(FileOutputStream.java:191)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at com.google.android.play.a.v.a(SourceFile:12591)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at com.google.android.play.a.v.a(SourceFile:14289)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at com.google.android.play.a.w.dispatchMessage(SourceFile:267)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at android.os.Looper.loop(Looper.java:135)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file number)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at libcore.io.Posix.writeBytes(Native Method)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at libcore.io.Posix.write(Posix.java:258)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	at libcore.io.IoBridge.write(IoBridge.java:497)
03-22 15:38:12.579  1645  1714 E PlayEventLogger: 	... 7 more
,03-22 15:38:12.580   925  2094 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
03-22 15:38:12.580   925  2094 E AndroidRuntime: Process: android.process.media, PID: 925
03-22 15:38:12.580   925  2094 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1175)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-22 15:38:12.580   925  2094 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-22 15:38:12.585  1645  1645 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
03-22 15:38:12.588   762   830 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-22 15:38:12.588   762   830 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-22 15:38:12.592   762  3833 E DropBoxManagerService: Can't write: system_app_crash
03-22 15:38:12.592   762  3833 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
03-22 15:38:12.592   762  3833 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-22 15:38:12.592   762  3833 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-22 15:38:12.592   762  3833 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-22 15:38:12.592   762  3833 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-22 15:38:12.592   762  3833 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-22 15:38:12.592   762  3833 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-22 15:38:12.592   762  3833 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-22 15:38:12.592   762  3833 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-22 15:38:12.592   762  3833 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-22 15:38:12.592   762  3833 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-22 15:38:12.592   762  3833 E DropBoxManagerService: 	... 5 more
03-22 15:38:12.592   762  3834 E DropBoxManagerService: Can't write: system_app_crash
03-22 15:38:12.592   762  3834 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-22 15:38:12.592   762  3834 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-22 15:38:12.592   762  3834 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-22 15:38:12.592   762  3834 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-22 15:38:12.592   762  3834 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-22 15:38:12.592   762  3834 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-22 15:38:12.592   762  3834 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-22 15:38:12.592   762  3834 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-22 15:38:12.592   762  3834 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-22 15:38:12.592   762  3834 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-22 15:38:12.592   762  3834 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-22 15:38:12.592   762  3834 E DropBoxManagerService: 	... 5 more
03-22 15:38:12.594  1645  1692 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
03-22 15:38:12.602   762  3835 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-22 15:38:12.603   762   830 D Atlas   : Validating map...
,03-22 15:38:12.611  1645  1692 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
03-22 15:38:12.631  1511  1627 D DeviceConnectionService: client connected with version: 8298000
03-22 15:38:12.637   176   176 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-22 15:38:12.637   176   176 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
03-22 15:38:12.637   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
03-22 15:38:12.637   176   176 E qdoverlay: MdpData failed to play
03-22 15:38:12.637   176   176 E qdoverlay: == Dump MdpData start ==
03-22 15:38:12.637   176   176 E qdoverlay: == Dump OvFD fd=76 path=/dev/graphics/fb0 start/end ==
03-22 15:38:12.637   176   176 E qdoverlay: mOvData msmfb_overlay_data id=64
03-22 15:38:12.637   176   176 E qdoverlay: data msmfb_data offset=0 memid=47 id=0 flags=0x0 priv=0
03-22 15:38:12.637   176   176 E qdoverlay: == Dump MdpData end ==
03-22 15:38:12.637   176   176 E qdhwcomposer: draw: queueBuffer failed for display:0 
03-22 15:38:12.637   176   176 E qdhwcomposer: hwc_set_primary: MDPComp draw failed
03-22 15:38:12.637   176   176 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-22 15:38:12.637   176   176 E qdhwcomposer: hwc_set_primary: display commit fail!
03-22 15:38:12.640   762  3835 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
03-22 15:38:12.640   762  3835 I OpenGLRenderer: Initialized EGL, version 1.4
03-22 15:38:12.640  1373  1373 E LocationReceiver: Received bad location: null
03-22 15:38:12.643   762  3835 D OpenGLRenderer: Enabling debug mode 0
,03-22 15:38:12.654   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-22 15:38:12.654   176   176 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
,03-22 15:38:12.654   176   176 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-22 15:38:12.654   176   176 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-22 15:38:12.654   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-22 15:38:12.654   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-22 15:38:12.654   176   176 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-22 15:38:12.654   176   176 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-22 15:38:12.654   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-22 15:38:12.654   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-22 15:38:12.654   176   176 E qdoverlay: Ctrl commit failed set overlay
03-22 15:38:12.654   176   176 E qdhwcomposer: configureLowRes: commit failed for low res panel
03-22 15:38:12.654   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-22 15:38:12.654   176   176 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-22 15:38:12.654   176   176 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
03-22 15:38:12.654   176   176 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
03-22 15:38:12.654   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-22 15:38:12.654   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-22 15:38:12.654   176   176 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
03-22 15:38:12.654   176   176 E qdoverlay: src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
03-22 15:38:12.654   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=75
03-22 15:38:12.654   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=75
03-22 15:38:12.654   176   176 E qdoverlay: Ctrl commit failed set overlay
03-22 15:38:12.654   176   176 E qdhwcomposer: configure: commit fails
03-22 15:38:12.654   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-22 15:38:12.654   176   176 E qdoverlay: MdpCtrl close error in unset

```
