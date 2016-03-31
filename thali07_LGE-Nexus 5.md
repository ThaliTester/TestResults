#### Test 64613803717efd7_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-31 12:57:35.832  1533  2435 I CheckinService: Done disabling old GoogleServicesFramework version
,03-31 12:57:36.076  3497  3497 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 12:57:36.078  3497  3497 D AndroidRuntime: CheckJNI is OFF
03-31 12:57:36.200  3497  3497 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-31 12:57:36.203   761  1173 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 12:57:36.209   761  1173 V WindowManager: addAppToken: AppWindowToken{e98baab token=Token{11a744fa ActivityRecord{4715b25 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-31 12:57:36.214   761   834 V WindowManager: Adding window Window{3a957952 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2eaa66fe u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 12:57:36.216  3497  3497 D AndroidRuntime: Shutting down VM
03-31 12:57:36.225  1400  1559 W SearchService: Abort, client detached.
03-31 12:57:36.259   761   776 I ActivityManager: Start proc 3518:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-31 12:57:36.277  1400  1594 I DeviceStateChecker: DeviceStateChecker cancelled
03-31 12:57:36.283  1400  1400 I MicroDetector: Keeping mic open: false
03-31 12:57:36.283  1400  1400 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@3d095284
03-31 12:57:36.343   187  1623 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 12:57:36.343   187  1623 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 12:57:36.351  1400  1620 I MicroRecognitionRunner: Detection finished
03-31 12:57:36.352  1400  1593 I MicroRecognitionRunner: Stopping hotword detection.
03-31 12:57:36.361  3518  3518 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
03-31 12:57:36.376  3518  3518 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 8567-8568)
03-31 12:57:36.377  3518  3518 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 12:57:36.391  3518  3518 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {37e97289}
03-31 12:57:36.391  3518  3518 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 12:57:36.392  3518  3518 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 12:57:36.407  3518  3518 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
03-31 12:57:36.424  3518  3518 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-31 12:57:36.430   761  1209 I ActivityManager: Killing 2520:com.google.android.keep/u0a52 (adj 15): empty #17
,03-31 12:57:36.473   761   833 D BluetoothManagerService: Message: 20
03-31 12:57:36.473   761   833 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@225e5d76:true
,03-31 12:57:36.500  3518  3518 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-31 12:57:36.500  3518  3518 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-31 12:57:36.539  3518  3518 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-31 12:57:36.539  3518  3518 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-31 12:57:36.551  3518  3518 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-31 12:57:36.558  3518  3518 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 12:57:36.559  3518  3518 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-31 12:57:36.568  3518  3518 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-31 12:57:36.590  3518  3574 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 12:57:36.595  3518  3518 D Atlas   : Validating map...
,03-31 12:57:36.601   761  1193 V WindowManager: Adding window Window{3df4b95f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3a957952 u0 Starting com.test.thalitest})
,03-31 12:57:36.609   761   866 D WifiService: New client listening to asynchronous messages
,03-31 12:57:36.614   761   865 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,03-31 12:57:36.679   761   777 I art     : Explicit concurrent mark sweep GC freed 22253(1064KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 2.082ms total 58.752ms
,03-31 12:57:36.682   761   776 D ConnectivityService: listenForNetwork for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 12:57:36.682   761   867 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 12:57:36.682   761   867 D ConnectivityService: apparently satisfied.  currentScore=60
,03-31 12:57:36.683  3518  3577 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 12:57:36.722  3518  3574 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 12:57:36.726  3518  3574 D OpenGLRenderer: Enabling debug mode 0
,03-31 12:57:36.790   761   834 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +555ms
,03-31 12:57:36.797  1097  1097 I Keyboard.Facilitator: onFinishInput()
,03-31 12:57:36.801  3518  3586 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-31 12:57:36.828  3518  3518 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3518
,03-31 12:57:37.000  3518  3518 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 12:57:37.103  3518  3593 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362789760
,03-31 12:57:37.107  3518  3593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 12:57:37.107  3518  3593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 12:57:37.107  3518  3593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 12:57:37.107  3518  3593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 12:57:37.107  3518  3593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-31 12:57:37.108  3518  3593 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f47fed9 added. We now have 1 listener(s)
,03-31 12:57:37.109   761  1095 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 12:57:37.114  3518  3593 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
03-31 12:57:37.115  3518  3593 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-31 12:57:37.116  3518  3593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 12:57:37.116  3518  3593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 12:57:37.125  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 12:57:37.125  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 12:57:37.125  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 12:57:37.125  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-31 12:57:37.125  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 12:57:37.125  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 12:57:37.125  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 12:57:37.125  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 12:57:37.125  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 12:57:37.125  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 12:57:37.125  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-31 12:57:37.126  3518  3593 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2407b34c added. We now have 1 listener(s)
,03-31 12:57:37.127  3518  3593 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 12:57:37.129  3518  3593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-31 12:57:37.132  3518  3593 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-31 12:57:37.132  3518  3593 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-31 12:57:37.134  3518  3593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 12:57:37.135   761   776 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 12:57:37.136  3518  3593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-31 12:57:37.139  3518  3593 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 12:57:37.139  3518  3593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 12:57:37.139  3518  3593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 12:57:37.139  3518  3593 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 12:57:37.139  3518  3593 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 12:57:37.139  3518  3593 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 12:57:37.139  3518  3593 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 12:57:37.139  3518  3593 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 12:57:37.139  3518  3593 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 12:57:37.139  3518  3593 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 12:57:37.140  3518  3518 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-31 12:57:37.142  3518  3518 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 12:57:37.143  3518  3593 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 12:57:37.169  3518  3518 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 12:57:37.798  3518  3595 W jxcore-log: Initializing JXcore engine
03-31 12:57:37.798  3518  3595 W jxcore-log: JXcore engine is ready
,03-31 12:57:37.825  3595  3595 W Thread-362: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9682]" dev="sockfs" ino=9682 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-31 12:57:37.825  3595  3595 W Thread-362: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,03-31 12:57:37.825  3595  3595 W Thread-362: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[7574]" dev="sockfs" ino=7574 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-31 12:57:37.825  3595  3595 W Thread-362: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[18020]" dev="sockfs" ino=18020 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-31 12:57:37.844  3518  3595 W jxcore-log: Starting JXcore engine
,03-31 12:57:37.920  3518  3595 W jxcore-log: Platform android
03-31 12:57:37.920  3518  3595 W jxcore-log: 
,03-31 12:57:37.920  3518  3595 W jxcore-log: Process ARCH arm
03-31 12:57:37.920  3518  3595 W jxcore-log: 
,03-31 12:57:38.117  3518  3595 I jxcore-log: JXcore Cordova bridge is ready!
03-31 12:57:38.117  3518  3595 I jxcore-log: 
03-31 12:57:38.117  3518  3595 W jxcore-log: JXcore engine is started
,03-31 12:57:38.124  3518  3593 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 12:57:38.126  3518  3518 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 12:57:38.369  1017  1017 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,03-31 12:57:40.328  3357  3383 W Babel   : aye TOOK TOO LONG! (15041ms > 10000ms)
,03-31 12:57:40.330  3357  3381 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-31 12:57:40.333   761  1173 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 12:57:40.337   761   776 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 12:57:40.341  3357  3357 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-31 12:57:40.341  3357  3357 W Babel   : BAM#gBA: invalid account id: -1
03-31 12:57:40.341  3357  3357 W Babel   : BAM#gBA: invalid account id: -1
03-31 12:57:40.341  3357  3357 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-31 12:57:40.343   761  1245 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 12:57:40.346   761  1209 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 12:57:40.377  3357  3399 W Babel   : aye TOOK TOO LONG! (15039ms > 10000ms)
,03-31 12:57:40.456  1650  1700 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-31 12:57:40.459  1650  1650 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 12:57:41.467  1533  1544 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-31 12:57:45.686   761  1244 I ActivityManager: Killing 3094:com.android.musicfx/u0a13 (adj 15): empty #17
,03-31 12:57:45.798   761  1244 I ActivityManager: Killing 3067:com.google.android.partnersetup/u0a11 (adj 15): empty #18
,03-31 12:57:46.261  1650  1650 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-31 12:57:46.299  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 12:57:46.304  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 12:57:46.306  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 12:57:46.983  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 12:57:47.097  1650  1688 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-31 12:57:47.097  1650  1688 I qtaguid : Untagging socket 37 failed errno=-22
03-31 12:57:47.097  1650  1688 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-31 12:57:47.100  1650  1650 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-31 12:57:47.114  3518  3595 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 12:57:47.114  3518  3595 I jxcore-log: 
03-31 12:57:47.116  3518  3595 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 12:57:47.116  3518  3595 I jxcore-log: 
,03-31 12:57:47.120  3518  3595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 12:57:47.120  3518  3595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 12:57:47.120  3518  3595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 12:57:47.120  3518  3595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 12:57:47.120  3518  3595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 12:57:47.120  3518  3595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 12:57:47.120  3518  3595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 12:57:47.120  3518  3595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 12:57:47.123  3518  3595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-31 12:57:47.125  3518  3595 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 12:57:47.125  3518  3595 I jxcore-log: 
03-31 12:57:47.128  3518  3595 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 12:57:47.128  3518  3595 I jxcore-log: 
,03-31 12:57:47.152   761  1095 I ActivityManager: Start proc 3667:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-31 12:57:47.171  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 12:57:47.191  3667  3667 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 12:57:47.191  3667  3667 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 12:57:47.223  3667  3667 I MultiDex: VM with version 2.1.0 has multidex support
03-31 12:57:47.223  3667  3667 I MultiDex: install
03-31 12:57:47.223  3667  3667 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 12:57:47.241  3667  3667 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-31 12:57:47.298  3667  3667 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 12:57:47.311  1533  3692 D LocationInitializer: Restart initialization of location
,03-31 12:57:47.314  1503  1503 D WearableService: callingUid 10007, callindPid: 1503
,03-31 12:57:47.318  1503  1503 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 12:57:47.322  1503  1922 E MDM     : [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-31 12:57:47.324  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 12:57:47.339  1503  1627 W GCoreFlp: No location to return for getLastLocation()
,03-31 12:57:47.339  1503  3693 W FusedLocationProvider: location=null
,03-31 12:57:47.342  3667  3667 D ChimeraCfgMgr: Reading stored module config
,03-31 12:57:47.422  3667  3667 D CAR.SERVICE: Connecting to CarCallService...
,03-31 12:57:47.423  3667  3696 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-31 12:57:47.432  3667  3667 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 12:57:47.432  3667  3667 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 12:57:47.438  3667  3667 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-31 12:57:47.445  3667  3667 D CAR.TEL.Service: Creating a new CarCallService.
,03-31 12:57:47.446  3667  3667 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
03-31 12:57:47.447   761  1244 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-31 12:57:47.450  3667  3667 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@db39d4e
,03-31 12:57:47.451   761  1193 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-31 12:57:47.451  3667  3667 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-31 12:57:47.451  3667  3667 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-31 12:57:47.469  1650  1687 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-31 12:57:47.469  1650  1687 I qtaguid : Untagging socket 37 failed errno=-22
03-31 12:57:47.469  1650  1687 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-31 12:57:47.507  3667  3682 D CAR.SERVICE: Package validated; name: com.android.vending
,03-31 12:57:47.679  3518  3595 I jxcore-log: Unit Test app is loaded
03-31 12:57:47.679  3518  3595 I jxcore-log: 
03-31 12:57:47.683  3518  3595 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 12:57:47.683  3518  3595 I jxcore-log: 
03-31 12:57:47.685  3518  3518 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 12:57:47.687  3518  3595 I jxcore-log: My device name is: LGE-Nexus 5
03-31 12:57:47.687  3518  3595 I jxcore-log: 
,03-31 12:57:47.988  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 12:57:48.431  1650  1688 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-31 12:57:48.431  1650  1688 I qtaguid : Untagging socket 37 failed errno=-22
03-31 12:57:48.431  1650  1688 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-31 12:57:48.506  1650  1650 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,03-31 12:57:48.530  1503  1672 D DeviceConnectionService: client connected with version: 8298000
,03-31 12:57:48.544  1650  1650 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-31 12:57:48.544  1650  1650 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,03-31 12:57:50.713  1650  3712 I Finsky  : [145] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-31 12:57:50.721  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 12:57:51.461  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 12:57:51.461  3518  3595 I jxcore-log: 
,03-31 12:57:51.806  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 12:57:51.806  3518  3595 I jxcore-log: 
,03-31 12:57:51.817  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 12:57:51.817  3518  3595 I jxcore-log: 
,03-31 12:57:51.821  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 12:57:51.821  3518  3595 I jxcore-log: 
,03-31 12:57:51.858  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 12:57:51.858  3518  3595 I jxcore-log: 
,03-31 12:57:51.873  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 12:57:51.873  3518  3595 I jxcore-log: 
,03-31 12:57:51.877  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 12:57:51.877  3518  3595 I jxcore-log: 
,03-31 12:57:52.569  3667  3667 D CAR.SERVICE: mConnectedToCar = false, abort
,03-31 12:57:52.570   761  3259 I ActivityManager: Killing 3126:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,03-31 12:57:52.577  3667  3667 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@24db5576 that was originally bound here
03-31 12:57:52.577  3667  3667 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@24db5576 that was originally bound here
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-31 12:57:52.577  3667  3667 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,03-31 12:57:52.673  3667  3667 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37195049 that was originally bound here
03-31 12:57:52.673  3667  3667 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37195049 that was originally bound here
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-31 12:57:52.673  3667  3667 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,03-31 12:57:52.675   761   777 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@1febab15
,03-31 12:57:53.829  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 12:57:53.829  3518  3595 I jxcore-log: 
,03-31 12:57:53.845  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 12:57:53.845  3518  3595 I jxcore-log: 
,03-31 12:57:53.852  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 12:57:53.852  3518  3595 I jxcore-log: 
,03-31 12:57:54.095  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 12:57:54.095  3518  3595 I jxcore-log: 
,03-31 12:57:54.165  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 12:57:54.165  3518  3595 I jxcore-log: 
,03-31 12:57:54.217  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 12:57:54.217  3518  3595 I jxcore-log: 
,03-31 12:57:54.223  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 12:57:54.223  3518  3595 I jxcore-log: 
,03-31 12:57:54.232  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 12:57:54.232  3518  3595 I jxcore-log: 
03-31 12:57:54.236  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 12:57:54.236  3518  3595 I jxcore-log: 
,03-31 12:57:54.241  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 12:57:54.241  3518  3595 I jxcore-log: 
,03-31 12:57:54.256  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 12:57:54.256  3518  3595 I jxcore-log: 
,03-31 12:57:54.274  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 12:57:54.274  3518  3595 I jxcore-log: 
,03-31 12:57:54.356  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 12:57:54.356  3518  3595 I jxcore-log: 
,03-31 12:57:54.360  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 12:57:54.360  3518  3595 I jxcore-log: 
,03-31 12:57:54.384  3518  3595 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 12:57:54.384  3518  3595 I jxcore-log: 
,03-31 12:57:54.390  3518  3595 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
03-31 12:57:54.392  3518  3595 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-31 12:57:54.392  3518  3595 I jxcore-log: 
,03-31 12:57:56.617   761   865 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,03-31 12:57:56.623   761   865 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 12:58:03.008  1650  1700 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-31 12:58:03.009  1650  1650 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 12:58:16.621   761   865 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
,03-31 12:58:19.355  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 12:58:19.358  1503  3741 I VacuumService: Vacuum at: now=1459421899358 tag=VacuumService
,03-31 12:58:20.359  1503  3756 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 5660 seconds from now (1459421900359)
,03-31 12:58:20.438  1503  3754 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-31 12:58:20.441  1503  3754 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 12:58:21.134  1503  3754 I art     : Explicit concurrent mark sweep GC freed 144445(8MB) AllocSpace objects, 35(560KB) LOS objects, 38% free, 25MB/41MB, paused 1.180ms total 92.219ms
,03-31 12:58:21.804  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 12:58:21.805  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 12:58:36.625   761   865 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
03-31 12:58:36.625   761   865 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 12:58:36.838  1097  1296 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-31 12:58:36.838  1097  1296 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 12:58:36.907  1503  1503 I ConfigService: onCreate
,03-31 12:58:41.946  1503  1503 I ConfigService: onDestroy
,03-31 12:58:56.629   761   865 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
03-31 12:58:56.630   761   865 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 12:59:12.721   761   836 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
03-31 12:59:12.726   761   836 I PowerManagerService: Sleeping (uid 1000)...
,03-31 12:59:12.785   761   836 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-31 12:59:12.797   187   857 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-31 12:59:12.812   176   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (104 us)
,03-31 12:59:12.823   761   865 E WifiStateMachine: cancelDelayedScan -> 11
,03-31 12:59:12.827   761   865 E native  : do suspend false
,03-31 12:59:12.946  1097  1097 I Keyboard.Facilitator: onFinishInput()
,03-31 12:59:12.947   187   872 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,03-31 12:59:12.961   761   865 E WifiStateMachine: cancelDelayedScan -> 13
,03-31 12:59:12.964   761   865 E native  : do suspend true
,03-31 12:59:13.325   761   865 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 12:59:13.325   761   865 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,03-31 12:59:13.394   761   834 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-31 12:59:13.398   761   761 V ActivityManager: Display changed displayId=0
,03-31 12:59:13.428   176   176 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
03-31 12:59:13.429   176   176 D qdhwcomposer: hwc_blank: Blanking display: 0
,03-31 12:59:13.524   177   177 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
03-31 12:59:13.524   177   177 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
03-31 12:59:13.524   177   177 I rmt_storage: wakelock acquired: 1, error no: 2
,03-31 12:59:13.524   177   572 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236802816)
,03-31 12:59:13.596   177   572 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
03-31 12:59:13.596   177   572 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
03-31 12:59:13.596   177   572 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236802816) wakelock released: 1, error no: 0
03-31 12:59:13.596   177   572 I rmt_storage: 
,03-31 12:59:13.598   177   177 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,03-31 12:59:13.709   176   176 D qdhwcomposer: hwc_blank: Done blanking display: 0
03-31 12:59:13.710   761   883 D SurfaceControl: Excessive delay in setPowerMode(): 316ms
03-31 12:59:13.711  1926  1928 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,03-31 12:59:13.749  3518  3518 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
03-31 12:59:13.749  3518  3518 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-31 12:59:13.776  3518  3518 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21201416 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3718f01a, 16908290=android.view.AbsSavedState$1@3718f01a}, android:focusedViewId=100}]}]
03-31 12:59:13.776  3518  3518 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
03-31 12:59:13.776  3518  3518 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
03-31 12:59:13.776  3518  3518 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,03-31 12:59:16.633   761   865 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 12:59:16.633   761   865 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,03-31 12:59:50.732  1503  1919 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-31 13:00:01.073   761   829 I ActivityManager: Start proc 3815:com.google.android.deskclock/u0a33 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,03-31 13:00:01.177   761  1173 I art     : Explicit concurrent mark sweep GC freed 64683(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 29MB/44MB, paused 1.570ms total 64.500ms
,03-31 13:00:01.211  3815  3815 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
03-31 13:00:01.211  3815  3815 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 13:00:01.211  3815  3815 I GAv4    :   adb logcat -s GAv4
,03-31 13:00:01.227   761  1244 I ActivityManager: Killing 3214:com.quickoffice.android/u0a65 (adj 15): empty #17
,03-31 13:00:08.137  3518  3595 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-31 13:00:08.137  3518  3595 I jxcore-log: 
,03-31 13:00:08.446  3865  3865 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-31 13:00:08.449  3865  3865 D AndroidRuntime: CheckJNI is OFF
,03-31 13:00:08.541  3865  3865 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 13:00:08.546   761   829 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-31 13:00:08.546   761   829 I ActivityManager: Killing 3518:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-31 13:00:08.582   761  1095 I WindowState: WIN DEATH: Window{3df4b95f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-31 13:00:08.583   761   866 D WifiService: Client connection lost with reason: 4
03-31 13:00:08.583   761  1244 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@d987fe2)
03-31 13:00:08.583   761   867 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 13:00:08.584   761   867 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 13:00:08.602   761   840 W PackageSettings: Skipping PackageSetting{1567d381 com.example.hello/10116} due to missing metadata
,03-31 13:00:08.656   761   829 I ActivityManager:   Force finishing activity 3 ActivityRecord{4715b25 u0 com.test.thalitest/.MainActivity t19}
,03-31 13:00:08.659   761  1193 W ActivityManager: Spurious death for ProcessRecord{bb17f73 3518:com.test.thalitest/u0a49}, curProc for 3518: null
,03-31 13:00:08.661   761   840 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-31 13:00:08.708  1248  1248 I art     : Explicit concurrent mark sweep GC freed 1708(106KB) AllocSpace objects, 6(531KB) LOS objects, 38% free, 25MB/41MB, paused 740us total 26.383ms
,03-31 13:00:08.722   907   907 I art     : Explicit concurrent mark sweep GC freed 42276(1741KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 943us total 26.483ms
,03-31 13:00:08.732  1400  1400 I art     : Explicit concurrent mark sweep GC freed 4245(305KB) AllocSpace objects, 7(154KB) LOS objects, 25% free, 21MB/29MB, paused 402us total 70.046ms
,03-31 13:00:08.736   761   885 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
03-31 13:00:08.736   761   885 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,03-31 13:00:08.740   761   849 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-31 13:00:08.741  1503  1636 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-31 13:00:08.751  1097  1097 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-31 13:00:08.772  1097  3886 I Keyboard.Facilitator.DecoderInitializer: run()
,03-31 13:00:08.774  1097  3886 I Decoder : createOrResetDecoder
,03-31 13:00:08.779  1533  1533 I art     : Explicit concurrent mark sweep GC freed 2405(146KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 23MB/30MB, paused 856us total 114.402ms
,03-31 13:00:08.781  2986  3895 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-31 13:00:08.790   761   761 I art     : Explicit concurrent mark sweep GC freed 14754(1311KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 29MB/44MB, paused 1.643ms total 92.702ms
03-31 13:00:08.791   761   840 I art     : WaitForGcToComplete blocked for 20.122ms for cause Explicit
,03-31 13:00:08.797   761   776 I ActivityManager: Start proc 3897:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-31 13:00:08.804  1503  1503 I ConfigService: onCreate
,03-31 13:00:08.849  1097  3886 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-31 13:00:08.862   761   761 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 13:00:08.862   761   761 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-31 13:00:08.867  1097  3886 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-31 13:00:08.868  1097  3886 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 13:00:08.868  1097  3886 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-31 13:00:08.870  1097  3886 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-31 13:00:08.870  1097  3886 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-31 13:00:08.870  1097  3886 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 13:00:08.870  1097  3886 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-31 13:00:08.870   761  1193 I ActivityManager: Start proc 3922:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-31 13:00:08.873  1097  3886 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 13:00:08.873  1097  3886 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 13:00:08.873  1097  3886 I Keyboard.Facilitator.Delight2FileSweeper: run()
,03-31 13:00:08.873  1097  3886 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 13:00:08.874   761  1095 I ActivityManager: Killing 3282:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
,03-31 13:00:08.875  1097  3886 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 13:00:08.875  1097  3886 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-31 13:00:08.888   761  1244 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3518 uid 10049
,03-31 13:00:08.889  1097  1097 I Keyboard.Facilitator: onFinishInput()
,03-31 13:00:08.908   761   840 I art     : Explicit concurrent mark sweep GC freed 8702(764KB) AllocSpace objects, 2(1312KB) LOS objects, 33% free, 28MB/42MB, paused 1.594ms total 116.781ms
,03-31 13:00:08.914  1248  1248 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-31 13:00:08.952  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-31 13:00:08.967  1533  3943 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-31 13:00:08.967  1533  3943 D AccountUtils: Clearing selected account for com.test.thalitest
,03-31 13:00:08.979  1533  3943 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-31 13:00:08.980  1503  1503 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-31 13:00:08.980  1503  1503 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-31 13:00:08.989  3865  3865 I art     : System.exit called, status: 0
03-31 13:00:08.989  3865  3865 I AndroidRuntime: VM exiting with result code 0.
,03-31 13:00:08.992  1248  1462 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-31 13:00:09.008   761  1207 I ActivityManager: Start proc 3949:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-31 13:00:09.038   761   840 I ActivityManager: Start proc 3966:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-31 13:00:09.089  1533  3976 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 13:00:09.097  1533  3976 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 13:00:09.098   761  1245 I ActivityManager: Killing 2877:com.google.android.apps.photos/u0a83 (adj 15): empty #17
,03-31 13:00:09.133  1533  3943 I GMPM-SVC: App measurement is starting up, version: 8703
03-31 13:00:09.133  1533  3943 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-31 13:00:09.157  1533  3989 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(:com.google.android.gms:223)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(:com.google.android.gms:601)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(:com.google.android.gms:595)
03-31 13:00:09.157  1533  3989 E SQLiteDatabase: 	at com.google.android.gms.drive.database.o.run(:com.google.android.gms:616)
,03-31 13:00:09.161  1533  3943 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-31 13:00:09.165  1533  3991 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-31 13:00:09.172  1533  3990 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2307)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:418)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.a(:com.google.android.gms:357)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.s(:com.google.android.gms:1591)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.p(:com.google.android.gms:1605)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.c(:com.google.android.gms:306)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ar.run(:com.google.android.gms:195)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 13:00:09.172  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ap.run(:com.google.android.gms:294)
,03-31 13:00:09.172  1533  3990 E GMPM-SVC: Opening the database failed, dropping and recreating it
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:418)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.a(:com.google.android.gms:357)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.s(:com.google.android.gms:1591)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.p(:com.google.android.gms:1605)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.c(:com.google.android.gms:306)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ar.run(:com.google.android.gms:195)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 13:00:09.175  1533  3990 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ap.run(:com.google.android.gms:294)
03-31 13:00:09.175  1533  3990 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-31 13:00:09.175  1533  3990 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-31 13:00:09.175  1533  3990 E GMPM-SVC: Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-31 13:00:09.176  1533  3991 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-31 13:00:09.176  1533  3991 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-31 13:00:09.176  1533  3991 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-31 13:00:09.176  1533  3991 I GCore-Chimera-Crash: ==
03-31 13:00:09.176  1533  3991 I GCore-Chimera-Crash: GCore-Chimera-Crash
03-31 13:00:09.176  1533  3989 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-31 13:00:09.176  1533  3989 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-31 13:00:09.176  1533  3989 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-31 13:00:09.176  1533  3989 I GCore-Chimera-Crash: ==
03-31 13:00:09.176  1533  3989 I GCore-Chimera-Crash: GCore-Chimera-Crash
03-31 13:00:09.176  1533  3989 I Process : Sending signal. PID: 1533 SIG: 9
03-31 13:00:09.196   761   866 D WifiService: Client connection lost with reason: 4

```
