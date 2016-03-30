#### Test 64613803f00187f_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-30 14:11:28.330  1559  2467 I CheckinService: Done disabling old GoogleServicesFramework version
,03-30 14:11:28.610  3530  3530 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-30 14:11:28.612  3530  3530 D AndroidRuntime: CheckJNI is OFF
03-30 14:11:28.717  3530  3530 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-30 14:11:28.720   762   778 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-30 14:11:28.726   762   778 V WindowManager: addAppToken: AppWindowToken{92efb74 token=Token{ba85747 ActivityRecord{324f4286 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-30 14:11:28.731   762   836 V WindowManager: Adding window Window{3322e83f u0 Starting com.test.thalitest} at 2 of 7 (after Window{2834a6c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-30 14:11:28.735  3530  3530 D AndroidRuntime: Shutting down VM
03-30 14:11:28.745  1405  1667 W SearchService: Abort, client detached.
03-30 14:11:28.772   762  1284 I ActivityManager: Start proc 3551:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-30 14:11:28.789  1405  1585 I DeviceStateChecker: DeviceStateChecker cancelled
03-30 14:11:28.790  1405  1405 I MicroDetector: Keeping mic open: false
03-30 14:11:28.791  1405  1405 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@dae59d1
03-30 14:11:28.844   188  1597 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-30 14:11:28.844   188  1597 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-30 14:11:28.849  1405  1584 I MicroRecognitionRunner: Stopping hotword detection.
03-30 14:11:28.852  1405  1590 I MicroRecognitionRunner: Detection finished
03-30 14:11:28.888  3551  3551 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
03-30 14:11:28.901  3551  3551 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 8346-8350)
03-30 14:11:28.901  3551  3551 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-30 14:11:28.911  3551  3551 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {162163ae}
03-30 14:11:28.912  3551  3551 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-30 14:11:28.912   762  1169 I ActivityManager: Killing 3078:com.android.providers.calendar/u0a1 (adj 15): empty #17
03-30 14:11:28.912  3551  3551 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
03-30 14:11:28.942  3551  3551 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,03-30 14:11:28.958  3551  3551 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-30 14:11:29.011   762   835 D BluetoothManagerService: Message: 20
03-30 14:11:29.012   762   835 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34f66c5:true
,03-30 14:11:29.016  3551  3551 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-30 14:11:29.016  3551  3551 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-30 14:11:29.054  3551  3551 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-30 14:11:29.054  3551  3551 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-30 14:11:29.066  3551  3551 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
03-30 14:11:29.073  3551  3551 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
03-30 14:11:29.074  3551  3551 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
03-30 14:11:29.083  3551  3551 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-30 14:11:29.105  3551  3609 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-30 14:11:29.110  3551  3551 D Atlas   : Validating map...
,03-30 14:11:29.114   762  1021 V WindowManager: Adding window Window{4f28058 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3322e83f u0 Starting com.test.thalitest})
,03-30 14:11:29.126   762   861 D WifiService: New client listening to asynchronous messages
,03-30 14:11:29.138   762   938 D ConnectivityService: listenForNetwork for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-30 14:11:29.139   762   868 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-30 14:11:29.139   762   868 D ConnectivityService: apparently satisfied.  currentScore=60
,03-30 14:11:29.140  3551  3611 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-30 14:11:29.274   762   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-48
,03-30 14:11:29.287   175   175 D SurfaceFlinger: shader cache generated - 24 shaders in 148.145111 ms
,03-30 14:11:29.308  3551  3609 I OpenGLRenderer: Initialized EGL, version 1.4
,03-30 14:11:29.311  3551  3609 D OpenGLRenderer: Enabling debug mode 0
,03-30 14:11:29.359   762   836 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +607ms
,03-30 14:11:29.371  1098  1098 I Keyboard.Facilitator: onFinishInput()
,03-30 14:11:29.382  3551  3620 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-30 14:11:29.407  3551  3551 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3551
,03-30 14:11:29.650  3551  3551 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-30 14:11:29.754  3551  3628 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1265507840
,03-30 14:11:29.757  3551  3628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-30 14:11:29.757  3551  3628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-30 14:11:29.757  3551  3628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-30 14:11:29.757  3551  3628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-30 14:11:29.757  3551  3628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-30 14:11:29.757  3551  3628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fb519be added. We now have 1 listener(s)
03-30 14:11:29.757   762  1284 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:11:29.760  3551  3628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,03-30 14:11:29.765  3551  3628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
03-30 14:11:29.765  3551  3628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-30 14:11:29.765  3551  3628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-30 14:11:29.767  3551  3628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22bce335 added. We now have 1 listener(s)
03-30 14:11:29.768  3551  3628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-30 14:11:29.769  3551  3628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-30 14:11:29.771  3551  3628 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-30 14:11:29.771  3551  3628 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-30 14:11:29.775  3551  3628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:11:29.776   762  1169 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:11:29.777  3551  3628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-30 14:11:29.782  3551  3628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:11:29.782  3551  3628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:11:29.782  3551  3628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-30 14:11:29.782  3551  3628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:11:29.782  3551  3628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:11:29.782  3551  3628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:11:29.782  3551  3628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:11:29.782  3551  3628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-30 14:11:29.783  3551  3628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-30 14:11:29.783  3551  3628 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-30 14:11:29.785  3551  3551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-30 14:11:29.785  3551  3628 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-30 14:11:29.786  3551  3551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-30 14:11:29.826  3551  3551 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-30 14:11:30.447  3551  3633 W jxcore-log: Initializing JXcore engine
03-30 14:11:30.447  3551  3633 W jxcore-log: JXcore engine is ready
,03-30 14:11:30.480  3633  3633 W Thread-364: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[7280]" dev="sockfs" ino=7280 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-30 14:11:30.480  3633  3633 W Thread-364: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3097 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-30 14:11:30.480  3633  3633 W Thread-364: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[9591]" dev="sockfs" ino=9591 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-30 14:11:30.480  3633  3633 W Thread-364: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[20593]" dev="sockfs" ino=20593 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-30 14:11:30.501  3551  3633 W jxcore-log: Starting JXcore engine
,03-30 14:11:30.576  3551  3633 W jxcore-log: Platform android
03-30 14:11:30.576  3551  3633 W jxcore-log: 
,03-30 14:11:30.576  3551  3633 W jxcore-log: Process ARCH arm
03-30 14:11:30.576  3551  3633 W jxcore-log: 
,03-30 14:11:30.819  3551  3633 I jxcore-log: JXcore Cordova bridge is ready!
03-30 14:11:30.819  3551  3633 I jxcore-log: 
03-30 14:11:30.819  3551  3633 W jxcore-log: JXcore engine is started
,03-30 14:11:30.822  3551  3628 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-30 14:11:30.823  3551  3551 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-30 14:11:31.046  1018  1018 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,03-30 14:11:32.197  3365  3393 W Babel   : aye TOOK TOO LONG! (15020ms > 10000ms)
,03-30 14:11:32.199  3365  3391 W Babel   : aye TOOK TOO LONG! (15033ms > 10000ms)
,03-30 14:11:32.202   762   778 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-30 14:11:32.205   762  1197 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-30 14:11:32.208  3365  3365 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-30 14:11:32.208  3365  3365 W Babel   : BAM#gBA: invalid account id: -1
03-30 14:11:32.208  3365  3365 W Babel   : BAM#gBA: invalid account id: -1
03-30 14:11:32.208  3365  3365 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-30 14:11:32.210   762  1021 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-30 14:11:32.212   762  1284 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-30 14:11:32.260  3365  3402 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-30 14:11:32.338  1641  1699 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-30 14:11:32.339  1641  1641 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-30 14:11:33.966  1559  1570 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-30 14:11:38.240   762  1169 I ActivityManager: Start proc 3682:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,03-30 14:11:38.289  3682  3682 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-30 14:11:38.313  3682  3682 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2ae2b429(com.android.providers.calendar.CalendarProvider2@162163ae)
,03-30 14:11:38.320   762  1170 I ActivityManager: Killing 3097:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-30 14:11:38.423   762  1168 I ActivityManager: Killing 3119:com.android.musicfx/u0a13 (adj 15): empty #17
,03-30 14:11:38.660   762  1168 I ActivityManager: Killing 2567:com.google.android.keep/u0a52 (adj 15): empty #18
,03-30 14:11:39.536  1641  1641 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-30 14:11:39.556  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:11:39.564  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:11:39.567  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:11:39.819  3682  3682 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-30 14:11:39.819  3682  3682 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-30 14:11:39.929  3551  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:11:39.929  3551  3633 I jxcore-log: 
,03-30 14:11:39.931   762  1284 I art     : Explicit concurrent mark sweep GC freed 28882(1405KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.611ms total 90.150ms
03-30 14:11:39.931  3551  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:11:39.931  3551  3633 I jxcore-log: 
,03-30 14:11:39.942  3551  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:11:39.942  3551  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:11:39.942  3551  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-30 14:11:39.942  3551  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:11:39.942  3551  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:11:39.942  3551  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:11:39.942  3551  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:11:39.942  3551  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:11:39.945  3551  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:11:39.946  3551  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:11:39.946  3551  3633 I jxcore-log: 
,03-30 14:11:39.948  3551  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:11:39.948  3551  3633 I jxcore-log: 
,03-30 14:11:40.339  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:11:40.444  3551  3633 I jxcore-log: Unit Test app is loaded
03-30 14:11:40.444  3551  3633 I jxcore-log: 
,03-30 14:11:40.450  3551  3551 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-30 14:11:40.454  3551  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:11:40.454  3551  3633 I jxcore-log: 
,03-30 14:11:40.462  3551  3633 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,03-30 14:11:40.465  3551  3633 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-30 14:11:40.465  3551  3633 I jxcore-log: 
,03-30 14:11:40.472  3551  3551 I chromium: [INFO:CONSOLE(86)] "logCallback Device did not have required hardware capabilities!", source: file:///android_asset/www/js/thali_main.js (86)
,03-30 14:11:40.477  3551  3633 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-30 14:11:40.477  3551  3633 I jxcore-log:   bluetooth: 'on',
03-30 14:11:40.477  3551  3633 I jxcore-log:   wifi: 'on',
03-30 14:11:40.477  3551  3633 I jxcore-log:   cellular: 'doNotCare',
03-30 14:11:40.477  3551  3633 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-30 14:11:40.477  3551  3633 I jxcore-log: 
03-30 14:11:40.479  3551  3633 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-30 14:11:40.479  3551  3633 I jxcore-log: 
,03-30 14:11:40.527  1641  1682 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-30 14:11:40.527  1641  1682 I qtaguid : Untagging socket 37 failed errno=-22
03-30 14:11:40.527  1641  1682 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-30 14:11:40.529  1641  1641 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-30 14:11:40.578   762  1197 I ActivityManager: Start proc 3764:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-30 14:11:40.591  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:11:40.615  3764  3764 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-30 14:11:40.615  3764  3764 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 14:11:40.653  3764  3764 I MultiDex: VM with version 2.1.0 has multidex support
03-30 14:11:40.653  3764  3764 I MultiDex: install
03-30 14:11:40.653  3764  3764 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-30 14:11:40.666  3764  3764 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-30 14:11:40.700  3764  3764 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-30 14:11:40.712  3764  3764 D ChimeraCfgMgr: Reading stored module config
,03-30 14:11:40.715  1510  1510 D WearableService: callingUid 10007, callindPid: 1510
,03-30 14:11:40.719  1510  1921 E MDM     : [166] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-30 14:11:40.723  1510  1510 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-30 14:11:40.725  1559  3796 D LocationInitializer: Restart initialization of location
,03-30 14:11:40.731  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:11:40.747  1510  1612 W GCoreFlp: No location to return for getLastLocation()
,03-30 14:11:40.747  1510  3797 W FusedLocationProvider: location=null
,03-30 14:11:40.752  3761  3761 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-30 14:11:40.754  3761  3761 D AndroidRuntime: CheckJNI is OFF
,03-30 14:11:40.809  3764  3764 D CAR.SERVICE: Connecting to CarCallService...
,03-30 14:11:40.820  3764  3764 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-30 14:11:40.821  3764  3764 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-30 14:11:40.827  3764  3764 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-30 14:11:40.832  3764  3764 D CAR.TEL.Service: Creating a new CarCallService.
,03-30 14:11:40.834  3764  3764 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-30 14:11:40.835   762  1021 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-30 14:11:40.836  3764  3764 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@202db90f
,03-30 14:11:40.837   762   778 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-30 14:11:40.837  3764  3764 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-30 14:11:40.837  3764  3764 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-30 14:11:40.843  3761  3761 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-30 14:11:40.851  3764  3795 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-30 14:11:40.854   762   831 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-30 14:11:40.854   762   831 I ActivityManager: Killing 3551:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-30 14:11:40.886   762  1021 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@263a7c1d)
03-30 14:11:40.886   762   868 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-30 14:11:40.886   762   868 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-30 14:11:40.887   762  1284 I WindowState: WIN DEATH: Window{4f28058 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-30 14:11:40.888   762   861 D WifiService: Client connection lost with reason: 4
,03-30 14:11:40.898  3764  3779 D CAR.SERVICE: Package validated; name: com.android.vending
,03-30 14:11:40.908   762   842 W PackageSettings: Skipping PackageSetting{315d6146 com.example.hello/10116} due to missing metadata
,03-30 14:11:40.952  1641  1681 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-30 14:11:40.952  1641  1681 I qtaguid : Untagging socket 37 failed errno=-22
03-30 14:11:40.952  1641  1681 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-30 14:11:41.112   762   831 W ActivityManager: Force removing ActivityRecord{324f4286 u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-30 14:11:41.119   762  1021 W ActivityManager: Spurious death for ProcessRecord{3425de92 3551:com.test.thalitest/u0a49}, curProc for 3551: null
,03-30 14:11:41.121   762   842 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-30 14:11:41.149   762   885 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-30 14:11:41.163  1510  1628 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-30 14:11:41.164  1098  1098 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-30 14:11:41.166  1559  1559 I art     : Explicit concurrent mark sweep GC freed 3672(160KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 23MB/38MB, paused 2.490ms total 35.920ms
,03-30 14:11:41.167   762   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-30 14:11:41.195   907   907 I art     : Explicit concurrent mark sweep GC freed 6626(310KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 606us total 49.178ms
,03-30 14:11:41.207  1098  3826 I Keyboard.Facilitator.DecoderInitializer: run()
,03-30 14:11:41.221  2711  3828 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-30 14:11:41.235   762   777 I ActivityManager: Start proc 3829:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-30 14:11:41.239  1098  3826 I Decoder : createOrResetDecoder
,03-30 14:11:41.243  1405  1405 I art     : Explicit concurrent mark sweep GC freed 4237(338KB) AllocSpace objects, 7(154KB) LOS objects, 40% free, 21MB/36MB, paused 3.658ms total 109.155ms
,03-30 14:11:41.270  1510  1510 I ConfigService: onCreate
,03-30 14:11:41.288   762   762 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-30 14:11:41.288   762   762 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-30 14:11:41.302   762  1168 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3551 uid 10049
,03-30 14:11:41.303  1098  1098 I Keyboard.Facilitator: onFinishInput()
,03-30 14:11:41.310  1098  3826 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-30 14:11:41.314   762   778 I ActivityManager: Start proc 3855:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-30 14:11:41.341  1405  1405 W LocationOracle: Best location was null
03-30 14:11:41.341  1405  1405 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-30 14:11:41.350  1229  1229 I art     : Explicit concurrent mark sweep GC freed 2833(160KB) AllocSpace objects, 6(531KB) LOS objects, 38% free, 25MB/41MB, paused 757us total 24.789ms
,03-30 14:11:41.361  1405  3875 I MicroRecognitionRunner: Starting detection.
,03-30 14:11:41.362  1405  3876 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@c86799
,03-30 14:11:41.363  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-30 14:11:41.364   188  3878 I AudioFlinger: AudioFlinger's thread 0xb449e000 ready to run
,03-30 14:11:41.378  1405  3876 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@c86799
,03-30 14:11:41.387  1559  3882 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-30 14:11:41.387  1559  3882 D AccountUtils: Clearing selected account for com.test.thalitest
,03-30 14:11:41.388   188  3878 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-30 14:11:41.388   188  3878 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-30 14:11:41.388   188  3878 D         : Failed to fetch the lookup information of the device 0000003E 
03-30 14:11:41.388   188  3878 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-30 14:11:41.388   188  3878 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-30 14:11:41.394   188  3878 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-30 14:11:41.398  1510  1612 W GCoreFlp: No location to return for getLastLocation()
,03-30 14:11:41.399  1510  1612 W GCoreFlp: No location to return for getLastLocation()
,03-30 14:11:41.402  1510  1612 W GCoreFlp: No location to return for getLastLocation()
,03-30 14:11:41.410  1559  3882 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-30 14:11:41.416  1098  3826 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-30 14:11:41.419  1098  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-30 14:11:41.419  1098  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-30 14:11:41.423  1098  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-30 14:11:41.423  1098  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-30 14:11:41.424  1510  1612 W GCoreFlp: No location to return for getLastLocation()
,03-30 14:11:41.425  1510  1510 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-30 14:11:41.425  1510  1510 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-30 14:11:41.427  1098  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-30 14:11:41.427  1098  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-30 14:11:41.427  1098  3826 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-30 14:11:41.427  1098  3826 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-30 14:11:41.427  1098  3826 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-30 14:11:41.428  1098  3826 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-30 14:11:41.428  1098  3826 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-30 14:11:41.428  1098  3826 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-30 14:11:41.448  1510  1612 W GCoreFlp: No location to return for getLastLocation()
03-30 14:11:41.450  1559  3888 W BaseAppContext: Using Auth Proxy for data requests.
,03-30 14:11:41.454  1559  3888 W BaseAppContext: Using Auth Proxy for data requests.
,03-30 14:11:41.466  1510  1612 W GCoreFlp: No location to return for getLastLocation()
,03-30 14:11:41.474  1559  3882 I GMPM-SVC: App measurement is starting up, version: 8703
03-30 14:11:41.474  1559  3882 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-30 14:11:41.478  1405  3892 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-30 14:11:41.485  1405  1405 I MicroDetectionWorker: onReady
,03-30 14:11:41.505   762   762 I ActivityManager: Start proc 3894:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,03-30 14:11:41.530  1559  3882 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-30 14:11:41.534   762   842 I art     : Explicit concurrent mark sweep GC freed 29375(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 3.371ms total 324.691ms
,03-30 14:11:41.555  1559  1616 I Icing   : doRemovePackageData com.test.thalitest
,03-30 14:11:41.568   762   778 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-30 14:11:41.569   762   868 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-30 14:11:41.569   762   868 D ConnectivityService: apparently satisfied.  currentScore=60
,03-30 14:11:41.569  1559  3920 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-30 14:11:41.603  1559  3919 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-30 14:11:41.603  1559  3919 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-30 14:11:41.603  1559  3919 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-30 14:11:41.603  1559  3919 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-30 14:11:41.615  1559  3919 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-30 14:11:41.615  1559  3919 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-30 14:11:41.615  1559  3919 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-30 14:11:41.622  1559  3919 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-30 14:11:41.622  1559  3919 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-30 14:11:41.624  1559  3919 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
03-30 14:11:41.625  1559  3919 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,03-30 14:11:41.625  1559  3919 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-30 14:11:41.625  1559  3919 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-30 14:11:41.646  1229  1448 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-30 14:11:41.649  1510  1623 I art     : Explicit concurrent mark sweep GC freed 34184(2MB) AllocSpace objects, 43(688KB) LOS objects, 40% free, 22MB/37MB, paused 1.687ms total 58.303ms
,03-30 14:11:41.650  1510  1523 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@39a7d8c4)
,03-30 14:11:41.651  1510  1523 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c1b33ad)
,03-30 14:11:41.651  1510  1523 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2621e6e2)
03-30 14:11:41.651  1510  1523 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@5945a73)
03-30 14:11:41.651  1510  1523 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3babbd30)
03-30 14:11:41.652  1510  1523 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3ee45da9)
,03-30 14:11:41.662  3761  3761 I art     : System.exit called, status: 0
03-30 14:11:41.662  3761  3761 I AndroidRuntime: VM exiting with result code 0.
,03-30 14:11:41.676  1405  3892 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 198 ms] updated apps [took 198 ms] 
,03-30 14:11:41.720   762   842 I ActivityManager: Start proc 3924:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-30 14:11:41.769   762  1197 I ActivityManager: Start proc 3947:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-30 14:11:41.788   762  1170 I ActivityManager: Killing 3306:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
,03-30 14:11:41.828  1229  1494 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-30 14:11:41.828  1229  1494 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-30 14:11:41.840  1559  3887 W DriveInitializer: Awaiting to be initialized
03-30 14:11:41.841  1559  3966 W DriveInitializer: Background init thread started
03-30 14:11:41.841   762  3165 I ActivityManager: Killing 2986:com.google.android.apps.photos/u0a83 (adj 15): empty #17
,03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: writeToFile: Got exception:
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: java.io.IOException: write failed: EBADF (Bad file number)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at libcore.io.IoBridge.write(IoBridge.java:502)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at com.android.internal.util.FastXmlSerializer.flushBytes(FastXmlSerializer.java:232)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:253)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at com.android.internal.util.FastXmlSerializer.endDocument(FastXmlSerializer.java:198)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at com.android.internal.util.XmlUtils.writeMapXml(XmlUtils.java:188)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at android.app.SharedPreferencesImpl.writeToFile(SharedPreferencesImpl.java:597)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at android.app.SharedPreferencesImpl.access$800(SharedPreferencesImpl.java:51)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at android.app.SharedPreferencesImpl$2.run(SharedPreferencesImpl.java:512)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file number)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at libcore.io.Posix.writeBytes(Native Method)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at libcore.io.Posix.write(Posix.java:258)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	at libcore.io.IoBridge.write(IoBridge.java:497)
03-30 14:11:41.870  1641  1674 W SharedPreferencesImpl: 	... 11 more
,03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: writeToFile: Got exception:
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: java.io.IOException: write failed: EBADF (Bad file number)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at libcore.io.IoBridge.write(IoBridge.java:502)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at com.android.internal.util.FastXmlSerializer.flushBytes(FastXmlSerializer.java:232)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:253)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at com.android.internal.util.FastXmlSerializer.endDocument(FastXmlSerializer.java:198)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at com.android.internal.util.XmlUtils.writeMapXml(XmlUtils.java:188)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at android.app.SharedPreferencesImpl.writeToFile(SharedPreferencesImpl.java:597)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at android.app.SharedPreferencesImpl.access$800(SharedPreferencesImpl.java:51)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at android.app.SharedPreferencesImpl$2.run(SharedPreferencesImpl.java:512)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file number)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at libcore.io.Posix.writeBytes(Native Method)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at libcore.io.Posix.write(Posix.java:258)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	at libcore.io.IoBridge.write(IoBridge.java:497)
03-30 14:11:41.871  1641  1674 W SharedPreferencesImpl: 	... 11 more
,03-30 14:11:41.871  1641  1674 E SharedPreferencesImpl: Couldn't clean up partially-written file /data/data/com.android.vending/shared_prefs/finsky.xml
03-30 14:11:41.872  1641  1674 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.android.vending/shared_prefs/finsky.xml
03-30 14:11:41.872  1641  1674 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.android.vending/shared_prefs/finsky.xml
03-30 14:11:41.875  3947  3947 D ExternalStorage: After updating volumes, found 1 active roots
03-30 14:11:41.890  1405  1405 E LocationReceiver: Received bad location: null
03-30 14:11:41.896  1559  3966 E DocListDatabase: Failed to delete from ContentFileDeletionLock163 table
03-30 14:11:41.896  1559  3966 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-30 14:11:41.896  1559  3966 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-30 14:11:41.896  1559  3966 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-30 14:11:41.896  1559  3966 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-30 14:11:41.896  1559  3966 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-30 14:11:41.896  1559  3966 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-30 14:11:41.896  1559  3966 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-30 14:11:41.896  1559  3966 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-30 14:11:41.896  1559  3966 E DocListDatabase: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-30 14:11:41.896  1559  3966 W DriveInitializer: Background init thread ended
03-30 14:11:41.897  1559  3887 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-30 14:11:41.898  1559  3887 E DriveAsyncService: disk I/O error (code 3850)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(:com.google.android.gms:486)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(:com.google.android.gms:461)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(:com.google.android.gms:1519)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(:com.google.android.gms:16)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-30 14:11:41.898  1559  3887 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:11:41.901  1559  3966 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-30 14:11:41.901  1559  3966 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-30 14:11:41.901  1559  3966 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-30 14:11:41.901  1559  3966 I GCore-Chimera-Crash: ==
03-30 14:11:41.901  1559  3966 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
03-30 14:11:41.901  1559  3966 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-30 14:11:41.901  1559  3966 E AndroidRuntime: Process: com.google.android.gms, PID: 1559
03-30 14:11:41.901  1559  3966 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-30 14:11:41.901  1559  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-30 14:11:41.901  1559  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-30 14:11:41.901  1559  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-30 14:11:41.901  1559  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-30 14:11:41.901  1559  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-30 14:11:41.901  1559  3966 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-30 14:11:41.901  1559  3966 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-30 14:11:41.901  1559  3966 E AndroidRuntime: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: Can't write: system_app_crash
03-30 14:11:41.904   762  3968 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 14:11:41.904   762  3968 E DropBoxManagerService: 	... 5 more
,03-30 14:11:41.924   762  3969 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-30 14:11:41.925   762   831 D Atlas   : Validating map...
03-30 14:11:41.927  1229  1556 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/reflection_multi_process.xml to backup file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/reflection_multi_process.xml.bak
03-30 14:11:41.931  3894  3921 D Documents: Update found 7 roots in 273ms
,03-30 14:11:41.948  1510  1510 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:11:41.954   175   175 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-30 14:11:41.954   175   175 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
03-30 14:11:41.954   175   175 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
03-30 14:11:41.954   175   175 E qdoverlay: MdpData failed to play
03-30 14:11:41.954   175   175 E qdoverlay: == Dump MdpData start ==
03-30 14:11:41.954   175   175 E qdoverlay: == Dump OvFD fd=60 path=/dev/graphics/fb0 start/end ==
03-30 14:11:41.954   175   175 E qdoverlay: mOvData msmfb_overlay_data id=64
03-30 14:11:41.954   175   175 E qdoverlay: data msmfb_data offset=0 memid=44 id=0 flags=0x0 priv=0
03-30 14:11:41.954   175   175 E qdoverlay: == Dump MdpData end ==
03-30 14:11:41.954   175   175 E qdhwcomposer: draw: queueBuffer failed for display:0 
03-30 14:11:41.954   175   175 E qdhwcomposer: hwc_set_primary: MDPComp draw failed
03-30 14:11:41.954   175   175 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-30 14:11:41.954   175   175 E qdhwcomposer: hwc_set_primary: display commit fail!
,03-30 14:11:41.955   762  3969 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
03-30 14:11:41.955   762  3969 I OpenGLRenderer: Initialized EGL, version 1.4
,03-30 14:11:41.959   762  3969 D OpenGLRenderer: Enabling debug mode 0
,03-30 14:11:41.971   175   175 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-30 14:11:41.971   175   175 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
,03-30 14:11:41.971   175   175 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-30 14:11:41.971   175   175 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-30 14:11:41.971   175   175 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-30 14:11:41.971   175   175 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-30 14:11:41.971   175   175 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-30 14:11:41.971   175   175 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-30 14:11:41.971   175   175 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-30 14:11:41.971   175   175 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-30 14:11:41.971   175   175 E qdoverlay: Ctrl commit failed set overlay
03-30 14:11:41.971   175   175 E qdhwcomposer: configureLowRes: commit failed for low res panel
03-30 14:11:41.971   175   175 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-30 14:11:41.971   175   175 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
,03-30 14:11:41.971   175   175 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
03-30 14:11:41.971   175   175 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
03-30 14:11:41.971   175   175 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-30 14:11:41.971   175   175 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-30 14:11:41.971   175   175 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
03-30 14:11:41.971   175   175 E qdoverlay: src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
03-30 14:11:41.971   175   175 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=75
03-30 14:11:41.971   175   175 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=75
03-30 14:11:41.971   175   175 E qdoverlay: Ctrl commit failed set overlay
03-30 14:11:41.971   175   175 E qdhwcomposer: configure: commit fails
03-30 14:11:41.971   175   175 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-30 14:11:41.971   175   175 E qdoverlay: MdpCtrl close error in unset
,03-30 14:11:41.981  3894  3967 D Documents: Update found 7 roots in 103ms

```
