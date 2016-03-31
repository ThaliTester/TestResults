#### Test 646138038d447f5_thali07_LGE-Nexus 5 Logs


```
--------- beginning of system
03-31 09:41:25.950   741   842 W PackageSettings: Skipping PackageSetting{7534b29 com.example.hello/10116} due to missing metadata
,--------- beginning of main
03-31 09:41:26.457  3508  3508 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 09:41:26.461  3508  3508 D AndroidRuntime: CheckJNI is OFF
03-31 09:41:26.566  3508  3508 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-31 09:41:26.569   741  1266 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 09:41:26.576   741  1266 V WindowManager: addAppToken: AppWindowToken{8e2fb37 token=Token{75f4036 ActivityRecord{30038dd1 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-31 09:41:26.584   741   833 V WindowManager: Adding window Window{11f2200e u0 Starting com.test.thalitest} at 2 of 7 (after Window{3d585a57 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 09:41:26.586  3508  3508 D AndroidRuntime: Shutting down VM
03-31 09:41:26.586  1410  1426 W SearchService: Abort, client detached.
03-31 09:41:26.630   741  1261 I ActivityManager: Start proc 3529:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-31 09:41:26.641  1410  1516 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
03-31 09:41:26.653  1410  1410 I MicroDetector: Keeping mic open: false
03-31 09:41:26.653  1410  1593 I DeviceStateChecker: DeviceStateChecker cancelled
03-31 09:41:26.653  1410  1410 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@13825819
03-31 09:41:26.720   191  1601 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 09:41:26.720   191  1601 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 09:41:26.736  3529  3529 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
03-31 09:41:26.746  3529  3529 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 7291-7292)
03-31 09:41:26.747  3529  3529 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 09:41:26.756  3529  3529 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2588d531}
03-31 09:41:26.756  3529  3529 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 09:41:26.756  3529  3529 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 09:41:26.764  1410  1598 I MicroRecognitionRunner: Detection finished
03-31 09:41:26.766  1410  1592 I MicroRecognitionRunner: Stopping hotword detection.
03-31 09:41:26.767  3529  3529 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
03-31 09:41:26.782  3529  3529 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-31 09:41:26.843  3529  3529 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-31 09:41:26.844  3529  3529 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-31 09:41:26.844   741   832 D BluetoothManagerService: Message: 20
03-31 09:41:26.844   741   832 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27eb986c:true
03-31 09:41:26.883  3529  3529 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-31 09:41:26.883  3529  3529 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-31 09:41:26.895  3529  3529 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
03-31 09:41:26.901  3529  3529 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
03-31 09:41:26.902  3529  3529 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
03-31 09:41:26.911  3529  3529 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
03-31 09:41:26.941  3529  3586 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-31 09:41:26.947  3529  3529 D Atlas   : Validating map...
03-31 09:41:26.953   741  3222 V WindowManager: Adding window Window{1936aa2b u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{11f2200e u0 Starting com.test.thalitest})
03-31 09:41:26.962   741   860 D WifiService: New client listening to asynchronous messages
03-31 09:41:26.972   741  1112 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 09:41:26.972   741   861 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 09:41:26.972   741   861 D ConnectivityService: apparently satisfied.  currentScore=60
03-31 09:41:26.973  3529  3591 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-31 09:41:26.977   741   925 I ActivityManager: Killing 2006:com.android.defcontainer/u0a4 (adj 15): empty #17
03-31 09:41:27.135   184   184 D SurfaceFlinger: shader cache generated - 24 shaders in 130.290421 ms
03-31 09:41:27.158  3529  3586 I OpenGLRenderer: Initialized EGL, version 1.4
03-31 09:41:27.163  3529  3586 D OpenGLRenderer: Enabling debug mode 0
03-31 09:41:27.244   741   833 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +638ms
03-31 09:41:27.248  1100  1100 I Keyboard.Facilitator: onFinishInput()
03-31 09:41:27.254  3529  3599 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 09:41:27.302  3529  3529 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3529
03-31 09:41:27.382  3529  3529 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 09:41:27.581  3529  3606 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1569321088
,03-31 09:41:27.586  3529  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 09:41:27.586  3529  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 09:41:27.586  3529  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 09:41:27.586  3529  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 09:41:27.586  3529  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 09:41:27.586  3529  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1314cf81 added. We now have 1 listener(s)
,03-31 09:41:27.588   741   925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 09:41:27.593  3529  3606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,03-31 09:41:27.600  3529  3606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-31 09:41:27.601  3529  3606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 09:41:27.603  3529  3606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 09:41:27.607  3529  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f1a9a14 added. We now have 1 listener(s)
03-31 09:41:27.608  3529  3606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 09:41:27.614  3529  3606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-31 09:41:27.616  3529  3606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,03-31 09:41:27.616  3529  3606 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-31 09:41:27.620  3529  3606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 09:41:27.621   741  1258 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 09:41:27.621  3529  3606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-31 09:41:27.629  3529  3606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 09:41:27.629  3529  3606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 09:41:27.629  3529  3606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 09:41:27.629  3529  3606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 09:41:27.629  3529  3606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 09:41:27.629  3529  3606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 09:41:27.629  3529  3606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 09:41:27.629  3529  3606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 09:41:27.629  3529  3606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 09:41:27.629  3529  3606 D io.jxcore.node.ConnectivityMonitor: start: OK
03-31 09:41:27.630  3529  3606 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 09:41:27.631  3529  3529 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 09:41:27.636  3529  3529 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 09:41:27.682  3529  3529 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 09:41:27.695  1566  2477 I CheckinService: Done disabling old GoogleServicesFramework version
,03-31 09:41:27.884   741   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,03-31 09:41:28.020  3029  3058 W Babel   : aye TOOK TOO LONG! (15032ms > 10000ms)
03-31 09:41:28.020  3029  3060 W Babel   : aye TOOK TOO LONG! (15024ms > 10000ms)
,03-31 09:41:28.031   741  1258 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 09:41:28.034   741  1227 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 09:41:28.036  3029  3029 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-31 09:41:28.036  3029  3029 W Babel   : BAM#gBA: invalid account id: -1
03-31 09:41:28.036  3029  3029 W Babel   : BAM#gBA: invalid account id: -1
03-31 09:41:28.036  3029  3029 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-31 09:41:28.038   741   756 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 09:41:28.040   741   925 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 09:41:28.117  3029  3068 W Babel   : aye TOOK TOO LONG! (15037ms > 10000ms)
,03-31 09:41:28.316  3529  3607 W jxcore-log: Initializing JXcore engine
03-31 09:41:28.316  3529  3607 W jxcore-log: JXcore engine is ready
,03-31 09:41:28.345  3607  3607 W Thread-347: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[6358]" dev="sockfs" ino=6358 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-31 09:41:28.345  3607  3607 W Thread-347: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,03-31 09:41:28.345  3607  3607 W Thread-347: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[6443]" dev="sockfs" ino=6443 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-31 09:41:28.345  3607  3607 W Thread-347: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[19534]" dev="sockfs" ino=19534 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-31 09:41:28.366  3529  3607 W jxcore-log: Starting JXcore engine
,03-31 09:41:28.443  3529  3607 W jxcore-log: Platform android
03-31 09:41:28.443  3529  3607 W jxcore-log: 
03-31 09:41:28.443  3529  3607 W jxcore-log: Process ARCH arm
03-31 09:41:28.443  3529  3607 W jxcore-log: 
,03-31 09:41:28.639  3529  3607 I jxcore-log: JXcore Cordova bridge is ready!
03-31 09:41:28.639  3529  3607 I jxcore-log: 
,03-31 09:41:28.640  3529  3607 W jxcore-log: JXcore engine is started
,03-31 09:41:28.644  3529  3606 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 09:41:28.645  3529  3529 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 09:41:29.455  1649  1698 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-31 09:41:29.456  1649  1649 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 09:41:37.536   741  1126 I ActivityManager: Start proc 3688:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,03-31 09:41:37.563  3688  3688 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-31 09:41:37.585  3688  3688 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@590bdd8(com.android.providers.calendar.CalendarProvider2@2588d531)
,03-31 09:41:37.591   741  1266 I ActivityManager: Killing 3139:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,03-31 09:41:37.666  3529  3607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 09:41:37.666  3529  3607 I jxcore-log: 
03-31 09:41:37.668  3529  3607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 09:41:37.668  3529  3607 I jxcore-log: 
,03-31 09:41:37.672   741  1261 I ActivityManager: Killing 2599:com.google.android.keep/u0a52 (adj 15): empty #17
,03-31 09:41:37.673  3529  3607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 09:41:37.673  3529  3607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 09:41:37.673  3529  3607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 09:41:37.673  3529  3607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 09:41:37.673  3529  3607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 09:41:37.673  3529  3607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 09:41:37.673  3529  3607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 09:41:37.673  3529  3607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 09:41:37.675  3529  3607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 09:41:37.676  3529  3607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 09:41:37.676  3529  3607 I jxcore-log: 
,03-31 09:41:37.678  3529  3607 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 09:41:37.678  3529  3607 I jxcore-log: 
,03-31 09:41:37.774   741  1261 I ActivityManager: Killing 2415:com.google.android.calendar/u0a28 (adj 15): empty #18
,03-31 09:41:38.170  3529  3607 I jxcore-log: Unit Test app is loaded
03-31 09:41:38.170  3529  3607 I jxcore-log: 
,03-31 09:41:38.174  3529  3607 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 09:41:38.174  3529  3607 I jxcore-log: 
,03-31 09:41:38.180  3529  3607 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
03-31 09:41:38.181  3529  3607 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-31 09:41:38.181  3529  3607 I jxcore-log: 
03-31 09:41:38.182  3529  3529 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 09:41:38.184  3529  3607 I jxcore-log: logCallback not set !!!!
03-31 09:41:38.184  3529  3607 I jxcore-log: 
03-31 09:41:38.186  3529  3607 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-31 09:41:38.186  3529  3607 I jxcore-log:   bluetooth: 'on',
03-31 09:41:38.186  3529  3607 I jxcore-log:   wifi: 'on',
03-31 09:41:38.186  3529  3607 I jxcore-log:   cellular: 'doNotCare',
03-31 09:41:38.186  3529  3607 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-31 09:41:38.186  3529  3607 I jxcore-log: 
03-31 09:41:38.187  3529  3607 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-31 09:41:38.187  3529  3607 I jxcore-log: 
,03-31 09:41:38.427  3706  3706 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 09:41:38.429  3706  3706 D AndroidRuntime: CheckJNI is OFF
,03-31 09:41:38.532  3706  3706 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 09:41:38.537   741   822 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-31 09:41:38.537   741   822 I ActivityManager: Killing 3529:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-31 09:41:38.571   741  1227 I WindowState: WIN DEATH: Window{1936aa2b u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-31 09:41:38.571   741  1261 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@abc9a0b)
,03-31 09:41:38.571   741   861 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 09:41:38.571   741   860 D WifiService: Client connection lost with reason: 4
03-31 09:41:38.572   741   861 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 09:41:38.579   741   842 W PackageSettings: Skipping PackageSetting{7534b29 com.example.hello/10116} due to missing metadata
,03-31 09:41:38.642   741   822 W ActivityManager: Force removing ActivityRecord{30038dd1 u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-31 09:41:38.648   741  1126 W ActivityManager: Spurious death for ProcessRecord{38bf20e8 3529:com.test.thalitest/u0a49}, curProc for 3529: null
,03-31 09:41:38.649   741   842 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-31 09:41:38.657   741   886 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-31 09:41:38.660  1100  1100 I Keyboard.Facilitator: resetDictionaries() : en_US
03-31 09:41:38.660  1518  1638 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-31 09:41:38.674   741   849 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 09:41:38.720   906   906 I art     : Explicit concurrent mark sweep GC freed 7225(336KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 1.327ms total 65.676ms
,03-31 09:41:38.721  1377  3731 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-31 09:41:38.736   741  1261 I ActivityManager: Start proc 3733:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-31 09:41:38.737  1100  3720 I Keyboard.Facilitator.DecoderInitializer: run()
,03-31 09:41:38.747  1100  3720 I Decoder : createOrResetDecoder
,03-31 09:41:38.757   202   202 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 461us total 20.244ms
,03-31 09:41:38.781   202   202 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 462us total 21.858ms
,03-31 09:41:38.784  1410  1410 I art     : Explicit concurrent mark sweep GC freed 3172(245KB) AllocSpace objects, 7(154KB) LOS objects, 24% free, 22MB/30MB, paused 551us total 131.962ms
,03-31 09:41:38.787  1566  1566 I art     : Explicit concurrent mark sweep GC freed 1695(64KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 23MB/30MB, paused 448us total 135.691ms
,03-31 09:41:38.799   202   202 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 206us total 14.867ms
,03-31 09:41:38.801  1518  1518 I ConfigService: onCreate
,03-31 09:41:38.803   741   741 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 09:41:38.803   741   741 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-31 09:41:38.833   741  3222 I ActivityManager: Start proc 3757:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-31 09:41:38.835   741  1112 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3529 uid 10049
,03-31 09:41:38.841  1100  1100 I Keyboard.Facilitator: onFinishInput()
,03-31 09:41:38.876  1288  1288 I art     : Explicit concurrent mark sweep GC freed 2924(161KB) AllocSpace objects, 5(450KB) LOS objects, 38% free, 25MB/41MB, paused 1.258ms total 22.557ms
,03-31 09:41:38.883  1649  1649 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-31 09:41:38.889  3757  3757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-31 09:41:38.898   741   842 I art     : Explicit concurrent mark sweep GC freed 40536(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 28MB/42MB, paused 1.678ms total 131.483ms
,03-31 09:41:38.900   741   741 I art     : WaitForGcToComplete blocked for 95.521ms for cause Explicit
,03-31 09:41:38.904  1410  1410 W LocationOracle: Best location was null
03-31 09:41:38.904  1410  1410 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
03-31 09:41:38.905  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:41:38.908  1100  3720 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-31 09:41:38.925  1410  3782 I MicroRecognitionRunner: Starting detection.
,03-31 09:41:38.927  1410  3783 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@18694a9b
,03-31 09:41:38.928  1566  3780 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-31 09:41:38.928  1566  3780 D AccountUtils: Clearing selected account for com.test.thalitest
,03-31 09:41:38.945   191  3786 I AudioFlinger: AudioFlinger's thread 0xb44a0000 ready to run
,03-31 09:41:38.946  1566  3780 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-31 09:41:38.954  3688  3688 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-31 09:41:38.954  3688  3688 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-31 09:41:38.956  1410  3783 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@18694a9b
,03-31 09:41:38.964   741   741 I art     : Explicit concurrent mark sweep GC freed 7355(381KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 2.227ms total 63.866ms
,03-31 09:41:38.966   191  3786 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-31 09:41:38.966   191  3786 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-31 09:41:38.966   191  3786 D         : Failed to fetch the lookup information of the device 0000003E 
03-31 09:41:38.966   191  3786 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-31 09:41:38.966   191  3786 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-31 09:41:38.971   191  3786 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-31 09:41:38.986  1518  1619 W GCoreFlp: No location to return for getLastLocation()
,03-31 09:41:38.989  1518  1518 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-31 09:41:38.989  1518  1518 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-31 09:41:38.992  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:41:38.997  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:41:39.004  1100  3720 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-31 09:41:39.006  1100  3720 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 09:41:39.006  1100  3720 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-31 09:41:39.007  1100  3720 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,03-31 09:41:39.008  1100  3720 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-31 09:41:39.008  1100  3720 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 09:41:39.008  1100  3720 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-31 09:41:39.010  1100  3720 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 09:41:39.010  1100  3720 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 09:41:39.010  1100  3720 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-31 09:41:39.010  1100  3720 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 09:41:39.010  1100  3720 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 09:41:39.010  1100  3720 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-31 09:41:39.020   741   757 I ActivityManager: Start proc 3795:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-31 09:41:39.032  1518  1619 W GCoreFlp: No location to return for getLastLocation()
,03-31 09:41:39.034  1518  1619 W GCoreFlp: No location to return for getLastLocation()
,03-31 09:41:39.035  1518  1619 W GCoreFlp: No location to return for getLastLocation()
,03-31 09:41:39.036  1566  3780 I GMPM-SVC: App measurement is starting up, version: 8703
03-31 09:41:39.036  1566  3780 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-31 09:41:39.057  1410  1410 I MicroDetectionWorker: onReady
,03-31 09:41:39.061  1566  3812 E SQLiteLog: (539) recovered 3 pages from /data/data/com.google.android.gms/databases/DocList.db-journal
,03-31 09:41:39.068  1566  3788 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 09:41:39.070  1566  3780 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-31 09:41:39.071  3706  3706 I art     : System.exit called, status: 0
03-31 09:41:39.071  3706  3706 I AndroidRuntime: VM exiting with result code 0.
,03-31 09:41:39.082  1566  3788 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 09:41:39.089  1518  1619 W GCoreFlp: No location to return for getLastLocation()
,03-31 09:41:39.099   741  1126 D ConnectivityService: listenForNetwork for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 09:41:39.100   741   861 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 09:41:39.100   741   861 D ConnectivityService: apparently satisfied.  currentScore=60
03-31 09:41:39.100  1566  3819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 09:41:39.105  1566  3818 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-31 09:41:39.105  1566  3818 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-31 09:41:39.105  1566  3818 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-31 09:41:39.105  1566  3818 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-31 09:41:39.114  1566  3818 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-31 09:41:39.114  1566  3818 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-31 09:41:39.114  1566  3818 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-31 09:41:39.120  1566  3818 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-31 09:41:39.120  1566  3818 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-31 09:41:39.121  1566  3818 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
03-31 09:41:39.121  1566  3818 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,03-31 09:41:39.121  1566  3818 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-31 09:41:39.122  1566  3818 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-31 09:41:39.130   741   842 I ActivityManager: Start proc 3820:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-31 09:41:39.146  1518  1619 W GCoreFlp: No location to return for getLastLocation()
,03-31 09:41:39.163  1566  1622 I Icing   : doRemovePackageData com.test.thalitest
,03-31 09:41:39.184   741  1261 I ActivityManager: Killing 3201:com.quickoffice.android/u0a65 (adj 15): empty #17
,03-31 09:41:39.235  1288  1450 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-31 09:41:39.305  1566  3787 W DriveInitializer: Awaiting to be initialized
,03-31 09:41:39.307  1566  3847 W DriveInitializer: Background init thread started
,03-31 09:41:39.309  1566  3847 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
,03-31 09:41:39.311  1566  3847 E DocListDatabase: Failed to delete from ContentFileDeletionLock163 table
03-31 09:41:39.311  1566  3847 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 09:41:39.311  1566  3847 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 09:41:39.311  1566  3847 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 09:41:39.311  1566  3847 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 09:41:39.311  1566  3847 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 09:41:39.311  1566  3847 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 09:41:39.311  1566  3847 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-31 09:41:39.311  1566  3847 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-31 09:41:39.311  1566  3847 E DocListDatabase: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
,03-31 09:41:39.311  1566  3847 W DriveInitializer: Background init thread ended
,03-31 09:41:39.312  1566  3787 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-31 09:41:39.312  1566  3787 E DriveAsyncService: disk I/O error (code 3850)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(:com.google.android.gms:486)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(:com.google.android.gms:461)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(:com.google.android.gms:1519)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(:com.google.android.gms:16)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-31 09:41:39.312  1566  3787 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-31 09:41:39.316  3795  3846 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
03-31 09:41:39.316  3795  3846 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 09:41:39.316  3795  3846 I GAv4    :   adb logcat -s GAv4
03-31 09:41:39.319  1566  3847 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-31 09:41:39.319  1566  3847 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-31 09:41:39.319  1566  3847 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-31 09:41:39.319  1566  3847 I GCore-Chimera-Crash: ==
03-31 09:41:39.319  1566  3847 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
03-31 09:41:39.319  1566  3847 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-31 09:41:39.319  1566  3847 E AndroidRuntime: Process: com.google.android.gms, PID: 1566
03-31 09:41:39.319  1566  3847 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 09:41:39.319  1566  3847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 09:41:39.319  1566  3847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 09:41:39.319  1566  3847 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 09:41:39.319  1566  3847 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 09:41:39.319  1566  3847 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 09:41:39.319  1566  3847 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-31 09:41:39.319  1566  3847 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-31 09:41:39.319  1566  3847 E AndroidRuntime: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: Can't write: system_app_crash
03-31 09:41:39.329   741  3851 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 09:41:39.329   741  3851 E DropBoxManagerService: 	... 5 more
03-31 09:41:39.343   741  3854 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-31 09:41:39.344   741   822 D Atlas   : Validating map...
,03-31 09:41:39.347   184   184 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-31 09:41:39.347   184   184 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
03-31 09:41:39.347   184   184 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
03-31 09:41:39.347   184   184 E qdoverlay: MdpData failed to play
03-31 09:41:39.347   184   184 E qdoverlay: == Dump MdpData start ==
03-31 09:41:39.347   184   184 E qdoverlay: == Dump OvFD fd=67 path=/dev/graphics/fb0 start/end ==
03-31 09:41:39.347   184   184 E qdoverlay: mOvData msmfb_overlay_data id=64
03-31 09:41:39.347   184   184 E qdoverlay: data msmfb_data offset=0 memid=49 id=0 flags=0x0 priv=0
03-31 09:41:39.347   184   184 E qdoverlay: == Dump MdpData end ==
03-31 09:41:39.347   184   184 E qdhwcomposer: draw: queueBuffer failed for display:0 
03-31 09:41:39.347   184   184 E qdhwcomposer: hwc_set_primary: MDPComp draw failed
03-31 09:41:39.347   184   184 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-31 09:41:39.347   184   184 E qdhwcomposer: hwc_set_primary: display commit fail!
03-31 09:41:39.350  3795  3846 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
03-31 09:41:39.354  1288  1502 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-31 09:41:39.354  1288  1502 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-31 09:41:39.359  3795  3846 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-31 09:41:39.360  3795  3855 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 09:41:39.361  3795  3855 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 09:41:39.364   184   184 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-31 09:41:39.364   184   184 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
03-31 09:41:39.364   184   184 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
03-31 09:41:39.364   184   184 E qdoverlay: MdpData failed to play
03-31 09:41:39.364   184   184 E qdoverlay: == Dump MdpData start ==
03-31 09:41:39.364   184   184 E qdoverlay: == Dump OvFD fd=67 path=/dev/graphics/fb0 start/end ==
03-31 09:41:39.364   184   184 E qdoverlay: mOvData msmfb_overlay_data id=64
03-31 09:41:39.364   184   184 E qdoverlay: data msmfb_data offset=0 memid=49 id=0 flags=0x0 priv=0
03-31 09:41:39.364   184   184 E qdoverlay: == Dump MdpData end ==
03-31 09:41:39.364   184   184 E qdhwcomposer: draw: queueBuffer failed for display:0 
03-31 09:41:39.364   184   184 E qdhwcomposer: hwc_set_primary: MDPComp draw failed
03-31 09:41:39.364   184   184 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-31 09:41:39.364   184   184 E qdhwcomposer: hwc_set_primary: display commit fail!
03-31 09:41:39.365  3795  3856 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-31 09:41:39.366  3795  3855 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 09:41:39.381   184   184 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-31 09:41:39.381   184   184 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
03-31 09:41:39.381   184   184 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
03-31 09:41:39.381   184   184 E qdoverlay: MdpData failed to play
03-31 09:41:39.381   184   184 E qdoverlay: == Dump MdpData start ==
03-31 09:41:39.381   184   184 E qdoverlay: == Dump OvFD fd=67 path=/dev/graphics/fb0 start/end ==
03-31 09:41:39.381   184   184 E qdoverlay: mOvData msmfb_overlay_data id=64
03-31 09:41:39.381   184   184 E qdoverlay: data msmfb_data offset=0 memid=49 id=0 flags=0x0 priv=0
03-31 09:41:39.381   184   184 E qdoverlay: == Dump MdpData end ==
03-31 09:41:39.381   184   184 E qdhwcomposer: draw: queueBuffer failed for display:0 
03-31 09:41:39.381   184   184 E qdhwcomposer: hwc_set_primary: MDPComp draw failed
03-31 09:41:39.381   184   184 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-31 09:41:39.381   184   184 E qdhwcomposer: hwc_set_primary: display commit fail!
03-31 09:41:39.382   741  3854 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
03-31 09:41:39.382   741  3854 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 09:41:39.386   741  3854 D OpenGLRenderer: Enabling debug mode 0
03-31 09:41:39.398   184   184 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-31 09:41:39.398   184   184 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-31 09:41:39.398   184   184 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-31 09:41:39.398   184   184 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-31 09:41:39.398   184   184 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 09:41:39.398   184   184 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 09:41:39.398   184   184 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-31 09:41:39.398   184   184 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-31 09:41:39.398   184   184 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 09:41:39.398   184   184 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 09:41:39.398   184   184 E qdoverlay: Ctrl commit failed set overlay
03-31 09:41:39.398   184   184 E qdhwcomposer: configureLowRes: commit failed for low res panel
03-31 09:41:39.398   184   184 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-31 09:41:39.398   184   184 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-31 09:41:39.398   184   184 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
03-31 09:41:39.398   184   184 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
03-31 09:41:39.398   184   184 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 09:41:39.398   184   184 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 09:41:39.398   184   184 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
03-31 09:41:39.398   184   184 E qdoverlay: src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
03-31 09:41:39.398   184   184 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=75
03-31 09:41:39.398   184   184 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=75
03-31 09:41:39.398   184   184 E qdoverlay: Ctrl commit failed set overlay
03-31 09:41:39.398   184   184 E qdhwcomposer: configure: commit fails
03-31 09:41:39.398   184   184 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-31 09:41:39.398   184   184 E qdoverlay: MdpCtrl close error in unset
,03-31 09:41:39.499   741  1258 I ActivityManager: Killing 3070:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-31 09:41:39.548  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:41:39.551  3795  3848 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
,03-31 09:41:39.562  1410  3871 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-31 09:41:39.594   741   756 I ActivityManager: Start proc 3873:com.quickoffice.android/u0a65 for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver

```
