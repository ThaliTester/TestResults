#### Test 64809936d936b9e_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
04-03 21:07:11.777  1567  2380 I CheckinService: Done disabling old GoogleServicesFramework version
,04-03 21:07:12.918  3450  3450 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-03 21:07:12.920  3450  3450 D AndroidRuntime: CheckJNI is OFF
04-03 21:07:13.049  3450  3450 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
04-03 21:07:13.052   740   949 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-03 21:07:13.063   740   949 V WindowManager: addAppToken: AppWindowToken{3bd89c81 token=Token{37d0d068 ActivityRecord{3c51578b u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
04-03 21:07:13.071   740   835 V WindowManager: Adding window Window{265b4480 u0 Starting com.test.thalitest} at 2 of 7 (after Window{cc1cc4b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-03 21:07:13.075  3450  3450 D AndroidRuntime: Shutting down VM
04-03 21:07:13.077  1376  1398 W SearchService: Abort, client detached.
04-03 21:07:13.128   740   957 I ActivityManager: Start proc 3471:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
04-03 21:07:13.148  1376  1589 I DeviceStateChecker: DeviceStateChecker cancelled
04-03 21:07:13.152  1376  1376 I MicroDetector: Keeping mic open: false
04-03 21:07:13.152  1376  1376 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@8dd9b6a
04-03 21:07:13.205   188  1598 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-03 21:07:13.205   188  1598 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-03 21:07:13.214  1376  1595 I MicroRecognitionRunner: Detection finished
04-03 21:07:13.215  1376  1588 I MicroRecognitionRunner: Stopping hotword detection.
04-03 21:07:13.225  3471  3471 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
04-03 21:07:13.236  3471  3471 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 7820-7823)
04-03 21:07:13.236  3471  3471 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-03 21:07:13.253  3471  3471 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10474f3}
04-03 21:07:13.253  3471  3471 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-03 21:07:13.253  3471  3471 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
04-03 21:07:13.265   740   755 I ActivityManager: Killing 3037:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
04-03 21:07:13.284  3471  3471 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,04-03 21:07:13.305  3471  3471 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-03 21:07:13.378   740   834 D BluetoothManagerService: Message: 20
04-03 21:07:13.378   740   834 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@399453ae:true
,04-03 21:07:13.381  3471  3471 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,04-03 21:07:13.381  3471  3471 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,04-03 21:07:13.419  3471  3471 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-03 21:07:13.419  3471  3471 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,04-03 21:07:13.431  3471  3471 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,04-03 21:07:13.436  3471  3471 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
04-03 21:07:13.437  3471  3471 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,04-03 21:07:13.446  3471  3471 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,04-03 21:07:13.468  3471  3528 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-03 21:07:13.473  3471  3471 D Atlas   : Validating map...
,04-03 21:07:13.478   740  1164 V WindowManager: Adding window Window{3c914655 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{265b4480 u0 Starting com.test.thalitest})
,04-03 21:07:13.485   740   868 D WifiService: New client listening to asynchronous messages
,04-03 21:07:13.497   740   755 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-03 21:07:13.498   740   869 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-03 21:07:13.498   740   869 D ConnectivityService: apparently satisfied.  currentScore=60
,04-03 21:07:13.499  3471  3530 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-03 21:07:13.580   740  1211 I art     : Explicit concurrent mark sweep GC freed 22164(1062KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.976ms total 64.988ms
,04-03 21:07:13.596  3471  3528 I OpenGLRenderer: Initialized EGL, version 1.4
,04-03 21:07:13.599  3471  3528 D OpenGLRenderer: Enabling debug mode 0
,04-03 21:07:13.667  1081  1081 I Keyboard.Facilitator: onFinishInput()
,04-03 21:07:13.674  3471  3538 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,04-03 21:07:13.677   740   835 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +588ms
,04-03 21:07:13.701  3471  3471 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3471
,04-03 21:07:13.859  3471  3471 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-03 21:07:13.937  3471  3544 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362632576
,04-03 21:07:13.948  3471  3544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-03 21:07:13.948  3471  3544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-03 21:07:13.948  3471  3544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-03 21:07:13.948  3471  3544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-03 21:07:13.948  3471  3544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,04-03 21:07:13.951  3471  3544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17fc2cc3 added. We now have 1 listener(s)
,04-03 21:07:13.953   740  1244 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-03 21:07:13.955  3471  3544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,04-03 21:07:13.956  3471  3544 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
04-03 21:07:13.957  3471  3544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
04-03 21:07:13.957  3471  3544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,04-03 21:07:13.960  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-03 21:07:13.960  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-03 21:07:13.960  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-03 21:07:13.960  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
04-03 21:07:13.960  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-03 21:07:13.960  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-03 21:07:13.960  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-03 21:07:13.960  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-03 21:07:13.960  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-03 21:07:13.960  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-03 21:07:13.960  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,04-03 21:07:13.961  3471  3544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@286601be added. We now have 1 listener(s)
,04-03 21:07:13.962  3471  3544 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-03 21:07:13.964  3471  3544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,04-03 21:07:13.966  3471  3544 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
04-03 21:07:13.966  3471  3544 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
04-03 21:07:13.973  3471  3544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
04-03 21:07:13.973   740  1240 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
04-03 21:07:13.974  3471  3544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,04-03 21:07:13.978  3471  3544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-03 21:07:13.978  3471  3544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-03 21:07:13.978  3471  3544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-03 21:07:13.978  3471  3544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-03 21:07:13.978  3471  3544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-03 21:07:13.978  3471  3544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-03 21:07:13.978  3471  3544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-03 21:07:13.978  3471  3544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-03 21:07:13.978  3471  3544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,04-03 21:07:13.978  3471  3544 D io.jxcore.node.ConnectivityMonitor: start: OK
04-03 21:07:13.978  3471  3544 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-03 21:07:13.992  3471  3471 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-03 21:07:13.995  3471  3471 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-03 21:07:14.004  3471  3471 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-03 21:07:14.273   740   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,04-03 21:07:14.642  3471  3545 W jxcore-log: Initializing JXcore engine
04-03 21:07:14.642  3471  3545 W jxcore-log: JXcore engine is ready
,04-03 21:07:14.680  3545  3545 W Thread-347: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[6883]" dev="sockfs" ino=6883 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,04-03 21:07:14.680  3545  3545 W Thread-347: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
04-03 21:07:14.680  3545  3545 W Thread-347: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[9728]" dev="sockfs" ino=9728 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-03 21:07:14.680  3545  3545 W Thread-347: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[19798]" dev="sockfs" ino=19798 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,04-03 21:07:14.694  3471  3545 W jxcore-log: Starting JXcore engine
,04-03 21:07:14.776  3471  3545 W jxcore-log: Platform android
04-03 21:07:14.776  3471  3545 W jxcore-log: 
04-03 21:07:14.776  3471  3545 W jxcore-log: Process ARCH arm
04-03 21:07:14.776  3471  3545 W jxcore-log: 
,04-03 21:07:15.049  3471  3545 I jxcore-log: JXcore Cordova bridge is ready!
04-03 21:07:15.049  3471  3545 I jxcore-log: 
04-03 21:07:15.049  3471  3545 W jxcore-log: JXcore engine is started
,04-03 21:07:15.053  3471  3544 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-03 21:07:15.055  3471  3471 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-03 21:07:16.790  3330  3359 W Babel   : aye TOOK TOO LONG! (15031ms > 10000ms)
,04-03 21:07:16.791  3330  3357 W Babel   : aye TOOK TOO LONG! (15035ms > 10000ms)
,04-03 21:07:16.794   740   755 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-03 21:07:16.797   740  1162 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-03 21:07:16.800  3330  3330 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
04-03 21:07:16.800  3330  3330 W Babel   : BAM#gBA: invalid account id: -1
04-03 21:07:16.800  3330  3330 W Babel   : BAM#gBA: invalid account id: -1
04-03 21:07:16.800  3330  3330 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,04-03 21:07:16.802   740   949 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-03 21:07:16.804   740  1166 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-03 21:07:16.897  1545  1621 I Finsky  : [126] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-03 21:07:16.898  1545  1545 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-03 21:07:16.918  3330  3378 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,04-03 21:07:18.339  1567  1578 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,04-03 21:07:20.882  1545  1545 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(151): Beginning daily hygiene
,04-03 21:07:20.904  1625  1625 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-03 21:07:20.909  1625  1625 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-03 21:07:20.910  1625  1625 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-03 21:07:21.654   740  1215 I ActivityManager: Start proc 3577:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,04-03 21:07:21.680  3577  3577 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,04-03 21:07:21.704  3577  3577 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@282fdb62(com.android.providers.calendar.CalendarProvider2@10474f3)
,04-03 21:07:21.710   740   949 I ActivityManager: Killing 3065:com.google.android.deskclock/u0a33 (adj 15): empty #17
,04-03 21:07:21.847  1625  1625 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-03 21:07:21.856   740   957 I ActivityManager: Killing 3115:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,04-03 21:07:21.973  1545  1607 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-03 21:07:21.973  1545  1607 I qtaguid : Untagging socket 37 failed errno=-22
04-03 21:07:21.973  1545  1607 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-03 21:07:21.976  1545  1545 I Finsky  : [1] com.google.android.finsky.m.e.a(156): Skipping DFE self-update. Local Version [80631600] >= Server Version [-1]
,04-03 21:07:22.003   740   957 I ActivityManager: Killing 2328:com.google.android.calendar/u0a28 (adj 15): empty #18
,04-03 21:07:22.229  1625  1625 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-03 21:07:22.258   740  1245 I ActivityManager: Start proc 3606:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,04-03 21:07:22.274   199   199 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 203us total 12.104ms
,04-03 21:07:22.289   199   199 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 213us total 13.512ms
,04-03 21:07:22.311   199   199 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 205us total 20.374ms
,04-03 21:07:22.322  3606  3606 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-03 21:07:22.322  3606  3606 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-03 21:07:22.356  3606  3606 I MultiDex: VM with version 2.1.0 has multidex support
04-03 21:07:22.357  3606  3606 I MultiDex: install
04-03 21:07:22.357  3606  3606 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-03 21:07:22.375  3606  3606 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,04-03 21:07:22.434  3606  3606 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-03 21:07:22.452  1625  1625 D WearableService: callingUid 10007, callindPid: 1625
04-03 21:07:22.452  3606  3606 D ChimeraCfgMgr: Reading stored module config
,04-03 21:07:22.457  1625  1951 E MDM     : [192] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,04-03 21:07:22.474  1625  1625 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-03 21:07:22.474  1567  3638 D LocationInitializer: Restart initialization of location
,04-03 21:07:22.482  1625  1625 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-03 21:07:22.501  1625  1671 W GCoreFlp: No location to return for getLastLocation()
04-03 21:07:22.501  1625  3639 W FusedLocationProvider: location=null
,04-03 21:07:22.556  3606  3637 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,04-03 21:07:22.557  3606  3606 D CAR.SERVICE: Connecting to CarCallService...
,04-03 21:07:22.566  3606  3606 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
04-03 21:07:22.566  3606  3606 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-03 21:07:22.572  3606  3606 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,04-03 21:07:22.575  3606  3606 D CAR.TEL.Service: Creating a new CarCallService.
04-03 21:07:22.576  3606  3606 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,04-03 21:07:22.578   740  1162 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
04-03 21:07:22.578  3606  3606 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@3704e270
,04-03 21:07:22.578   740   756 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
04-03 21:07:22.579  3606  3606 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
04-03 21:07:22.579  3606  3606 D CAR.TEL.Service: Starting CarCallService with initial phone null
,04-03 21:07:22.639  3606  3621 D CAR.SERVICE: Package validated; name: com.android.vending
,04-03 21:07:22.716  1545  1606 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-03 21:07:22.716  1545  1606 I qtaguid : Untagging socket 37 failed errno=-22
,04-03 21:07:22.716  1545  1606 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-03 21:07:23.223  3577  3577 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
04-03 21:07:23.223  3577  3577 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,04-03 21:07:23.243   740   830 I ActivityManager: Start proc 3657:com.google.android.calendar/u0a28 for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,04-03 21:07:23.260  1625  1625 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-03 21:07:23.347  3657  3657 E SQLiteLog: (283) recovered 44 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,04-03 21:07:23.464  3657  3657 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,04-03 21:07:23.926  1545  1607 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-03 21:07:23.926  1545  1607 I qtaguid : Untagging socket 37 failed errno=-22
04-03 21:07:23.926  1545  1607 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-03 21:07:24.010  1545  1545 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(9405): Logging device features
,04-03 21:07:24.039  1545  1545 I Finsky  : [1] com.google.android.vending.verifier.VerifyInstalledPackagesReceiver.onReceive(41): Verify installed apps requested
,04-03 21:07:24.045  1625  1697 D DeviceConnectionService: client connected with version: 8298000
,04-03 21:07:24.048  1545  1545 I Finsky  : [1] com.google.android.vending.verifier.m.onPreExecute(567): Verifying installed apps
,04-03 21:07:24.071  1545  1545 E Finsky  : [1] com.google.android.finsky.wear.bf.a(728): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
04-03 21:07:24.072  1545  1545 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6337): Dropping command=hygiene due to Gms not connected
,04-03 21:07:24.097  1545  3707 I Finsky  : [136] com.google.android.vending.verifier.m.a(679): Adding com.quickoffice.android for verification
,04-03 21:07:24.450  3471  3545 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-03 21:07:24.450  3471  3545 I jxcore-log: 
,04-03 21:07:24.452  3471  3545 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-03 21:07:24.452  3471  3545 I jxcore-log: 
,04-03 21:07:24.455  3471  3545 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-03 21:07:24.455  3471  3545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-03 21:07:24.455  3471  3545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-03 21:07:24.455  3471  3545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-03 21:07:24.455  3471  3545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-03 21:07:24.455  3471  3545 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-03 21:07:24.455  3471  3545 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-03 21:07:24.455  3471  3545 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-03 21:07:24.457  3471  3545 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,04-03 21:07:24.458  3471  3545 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-03 21:07:24.458  3471  3545 I jxcore-log: 
,04-03 21:07:24.460  3471  3545 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-03 21:07:24.460  3471  3545 I jxcore-log: 
,04-03 21:07:24.677  1545  1606 I qtaguid : Failed write_ctrl(u 48) res=-1 errno=22
04-03 21:07:24.677  1545  1606 I qtaguid : Untagging socket 48 failed errno=-22
04-03 21:07:24.677  1545  1606 W NetworkManagementSocketTagger: untagSocket(48) failed with errno -22
,04-03 21:07:24.952  3471  3545 I jxcore-log: Unit Test app is loaded
04-03 21:07:24.952  3471  3545 I jxcore-log: 
,04-03 21:07:24.957  3471  3545 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-03 21:07:24.957  3471  3545 I jxcore-log: 
,04-03 21:07:24.961  3471  3471 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
04-03 21:07:24.962  3471  3545 I jxcore-log: My device name is: LGE-Nexus 5
04-03 21:07:24.962  3471  3545 I jxcore-log: 
,04-03 21:07:24.963  3471  3545 I jxcore-log: WARN testUtils: myNameCallback not set!
04-03 21:07:24.963  3471  3545 I jxcore-log: 
,04-03 21:07:26.721  3577  3717 E SQLiteLog: (284) automatic index on view_events(_id)
,04-03 21:07:26.748  1545  3718 I Finsky  : [137] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-03 21:07:26.755  1625  1625 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-03 21:07:27.696  3606  3606 D CAR.SERVICE: mConnectedToCar = false, abort
,04-03 21:07:27.700  3606  3606 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@11366058 that was originally bound here
04-03 21:07:27.700  3606  3606 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@11366058 that was originally bound here
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-03 21:07:27.700  3606  3606 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-03 21:07:27.708  3606  3606 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3031ccb3 that was originally bound here
04-03 21:07:27.708  3606  3606 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3031ccb3 that was originally bound here
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-03 21:07:27.708  3606  3606 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-03 21:07:27.709   740   755 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@75b76c7
,04-03 21:07:28.440  3657  3684 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,04-03 21:07:28.600   740  1240 I ActivityManager: Killing 3152:com.android.musicfx/u0a13 (adj 15): empty #17
,04-03 21:07:28.703  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-03 21:07:28.703  3471  3545 I jxcore-log: 
,04-03 21:07:29.043  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-03 21:07:29.043  3471  3545 I jxcore-log: 
,04-03 21:07:29.053  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-03 21:07:29.053  3471  3545 I jxcore-log: 
,04-03 21:07:29.057  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-03 21:07:29.057  3471  3545 I jxcore-log: 
,04-03 21:07:29.072  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-03 21:07:29.072  3471  3545 I jxcore-log: 
,04-03 21:07:29.075  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-03 21:07:29.075  3471  3545 I jxcore-log: 
,04-03 21:07:29.169   740   756 I ActivityManager: Killing 3089:com.google.android.keep/u0a52 (adj 15): empty #17
,04-03 21:07:31.011  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-03 21:07:31.011  3471  3545 I jxcore-log: 
,04-03 21:07:31.031  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-03 21:07:31.031  3471  3545 I jxcore-log: 
,04-03 21:07:31.039  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-03 21:07:31.039  3471  3545 I jxcore-log: 
,04-03 21:07:31.189  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-03 21:07:31.189  3471  3545 I jxcore-log: 
,04-03 21:07:31.270  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-03 21:07:31.270  3471  3545 I jxcore-log: 
,04-03 21:07:31.322  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-03 21:07:31.322  3471  3545 I jxcore-log: 
,04-03 21:07:31.328  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
04-03 21:07:31.328  3471  3545 I jxcore-log: 
,04-03 21:07:31.459  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-03 21:07:31.459  3471  3545 I jxcore-log: 
,04-03 21:07:31.479  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-03 21:07:31.479  3471  3545 I jxcore-log: 
,04-03 21:07:31.483  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-03 21:07:31.483  3471  3545 I jxcore-log: 
,04-03 21:07:31.488  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-03 21:07:31.488  3471  3545 I jxcore-log: 
,04-03 21:07:31.503  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-03 21:07:31.503  3471  3545 I jxcore-log: 
,04-03 21:07:31.522  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-03 21:07:31.522  3471  3545 I jxcore-log: 
,04-03 21:07:31.603  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-03 21:07:31.603  3471  3545 I jxcore-log: 
04-03 21:07:31.608  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-03 21:07:31.608  3471  3545 I jxcore-log: 
,04-03 21:07:31.631  3471  3545 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-03 21:07:31.631  3471  3545 I jxcore-log: 
,04-03 21:07:31.640  3471  3545 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,04-03 21:07:31.641  3471  3545 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
04-03 21:07:31.641  3471  3545 I jxcore-log: 
,04-03 21:07:34.277   740   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
04-03 21:07:34.278   740   867 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-03 21:07:40.482  1545  1621 I Finsky  : [126] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-03 21:07:40.482  1545  1545 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-03 21:07:54.281   740   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
,04-03 21:07:56.298  1625  1625 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-03 21:07:56.301  1625  3760 I VacuumService: Vacuum at: now=1459710476301 tag=VacuumService
,04-03 21:07:56.721   740  1162 I art     : Explicit concurrent mark sweep GC freed 40078(1844KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.399ms total 96.276ms
,04-03 21:07:57.373  1625  3771 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 7072 seconds from now (1459710477373)
,04-03 21:07:57.445  1625  3769 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,04-03 21:07:57.448  1625  3769 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-03 21:07:58.153  1625  3769 I art     : Explicit concurrent mark sweep GC freed 143753(8MB) AllocSpace objects, 41(656KB) LOS objects, 38% free, 25MB/41MB, paused 1.341ms total 70.918ms
,04-03 21:07:58.754  1625  1625 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-03 21:07:58.755  1625  1625 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-03 21:08:13.668  1081  1242 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-03 21:08:13.668  1081  1242 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-03 21:08:13.721  1625  1625 I ConfigService: onCreate
,04-03 21:08:14.282   740   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,04-03 21:08:14.282   740   867 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-03 21:08:18.792  1625  1625 I ConfigService: onDestroy
,04-03 21:08:34.289   740   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
04-03 21:08:34.289   740   867 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-03 21:08:48.131   740   837 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
04-03 21:08:48.136   740   837 I PowerManagerService: Sleeping (uid 1000)...
,04-03 21:08:48.211   740   837 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-03 21:08:48.229   188   188 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-03 21:08:48.241   740   867 E WifiStateMachine: cancelDelayedScan -> 11
,04-03 21:08:48.243   175   317 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (110 us)
,04-03 21:08:48.254   740   867 E native  : do suspend false
,04-03 21:08:48.378  1987  2053 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-03 21:08:48.407  1081  1081 I Keyboard.Facilitator: onFinishInput()
,04-03 21:08:48.408   188   875 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,04-03 21:08:48.417   740   867 E WifiStateMachine: cancelDelayedScan -> 13
,04-03 21:08:48.421   740   867 E native  : do suspend true
,04-03 21:08:48.743   740   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
,04-03 21:08:48.744   740   867 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,04-03 21:08:48.788   175   175 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
04-03 21:08:48.788   175   175 D qdhwcomposer: hwc_blank: Blanking display: 0
04-03 21:08:48.788   740   835 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,04-03 21:08:48.789   740   740 V ActivityManager: Display changed displayId=0
,04-03 21:08:48.909   176   176 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
04-03 21:08:48.909   176   176 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
04-03 21:08:48.909   176   176 I rmt_storage: wakelock acquired: 1, error no: 2
04-03 21:08:48.909   176   576 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236802816)
,04-03 21:08:49.004   176   576 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
04-03 21:08:49.004   176   576 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
04-03 21:08:49.004   176   576 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236802816) wakelock released: 1, error no: 0
04-03 21:08:49.004   176   576 I rmt_storage: 
,04-03 21:08:49.007   176   176 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,04-03 21:08:49.063   175   175 D qdhwcomposer: hwc_blank: Done blanking display: 0
04-03 21:08:49.063   740   884 D SurfaceControl: Excessive delay in setPowerMode(): 275ms
04-03 21:08:49.063  1881  1882 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,04-03 21:08:49.079  3471  3471 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
04-03 21:08:49.079  3471  3471 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,04-03 21:08:49.111  3471  3471 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7c085f8 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@68ba656, 16908290=android.view.AbsSavedState$1@68ba656}, android:focusedViewId=100}]}]
04-03 21:08:49.111  3471  3471 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
04-03 21:08:49.111  3471  3471 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
04-03 21:08:49.111  3471  3471 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,04-03 21:08:54.293   740   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
04-03 21:08:54.294   740   867 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,04-03 21:09:46.465  3471  3545 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-03 21:09:46.465  3471  3545 I jxcore-log: 
,04-03 21:09:46.854  3850  3850 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-03 21:09:46.857  3850  3850 D AndroidRuntime: CheckJNI is OFF
,04-03 21:09:46.953  3850  3850 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-03 21:09:46.959   740   830 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
04-03 21:09:46.959   740   830 I ActivityManager: Killing 3471:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,04-03 21:09:46.998   740   841 W PackageSettings: Skipping PackageSetting{330d4946 com.example.hello/10116} due to missing metadata
,04-03 21:09:47.013   740   949 I WindowState: WIN DEATH: Window{3c914655 u0 com.test.thalitest/com.test.thalitest.MainActivity}
04-03 21:09:47.013   740   868 D WifiService: Client connection lost with reason: 4
04-03 21:09:47.013   740  1211 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@353754fd)
04-03 21:09:47.014   740   869 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-03 21:09:47.014   740   869 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-03 21:09:47.169   740   830 I ActivityManager:   Force finishing activity 3 ActivityRecord{3c51578b u0 com.test.thalitest/.MainActivity t19}
,04-03 21:09:47.173   740  1240 W ActivityManager: Spurious death for ProcessRecord{3d2275f2 3471:com.test.thalitest/u0a49}, curProc for 3471: null
04-03 21:09:47.174   740   841 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,04-03 21:09:47.218  1194  1194 I art     : Explicit concurrent mark sweep GC freed 1765(109KB) AllocSpace objects, 5(450KB) LOS objects, 38% free, 25MB/41MB, paused 915us total 29.611ms
,04-03 21:09:47.239   908   908 I art     : Explicit concurrent mark sweep GC freed 9359(413KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 1.002ms total 45.025ms
,04-03 21:09:47.258  1567  1567 I art     : Explicit concurrent mark sweep GC freed 2539(151KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 23MB/30MB, paused 9.820ms total 80.075ms
,04-03 21:09:47.260  1376  1376 I art     : Explicit concurrent mark sweep GC freed 2947(241KB) AllocSpace objects, 7(154KB) LOS objects, 24% free, 22MB/30MB, paused 473us total 68.045ms
,04-03 21:09:47.269   740   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-03 21:09:47.270  1625  1679 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,04-03 21:09:47.277   740   886 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
04-03 21:09:47.277   740   886 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,04-03 21:09:47.302  1081  1081 I Keyboard.Facilitator: resetDictionaries() : en_US
,04-03 21:09:47.304  1081  3879 I Keyboard.Facilitator.DecoderInitializer: run()
,04-03 21:09:47.306  1081  3879 I Decoder : createOrResetDecoder
,04-03 21:09:47.311  3008  3883 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,04-03 21:09:47.316   740   740 I art     : Explicit concurrent mark sweep GC freed 36565(2035KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 29MB/43MB, paused 1.419ms total 76.765ms
,04-03 21:09:47.318   740  1215 I ActivityManager: Start proc 3884:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,04-03 21:09:47.341  1625  1625 I ConfigService: onCreate
,04-03 21:09:47.399   740   957 I ActivityManager: Start proc 3907:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,04-03 21:09:47.402   740   740 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-03 21:09:47.402   740   740 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,04-03 21:09:47.417   740  1245 I ActivityManager: Killing 3197:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,04-03 21:09:47.420   740   756 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3471 uid 10049
04-03 21:09:47.422  1081  1081 I Keyboard.Facilitator: onFinishInput()
,04-03 21:09:47.423  1081  3879 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,04-03 21:09:47.436   740   841 I art     : Explicit concurrent mark sweep GC freed 12827(1234KB) AllocSpace objects, 2(1312KB) LOS objects, 33% free, 28MB/42MB, paused 2.737ms total 112.942ms
,04-03 21:09:47.439  1194  1194 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-03 21:09:47.448  1081  3879 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
04-03 21:09:47.450  1081  3879 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
04-03 21:09:47.450  1081  3879 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,04-03 21:09:47.451  1081  3879 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,04-03 21:09:47.451  1081  3879 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
04-03 21:09:47.452  1081  3879 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
04-03 21:09:47.452  1081  3879 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
04-03 21:09:47.452  1081  3879 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-03 21:09:47.452  1081  3879 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-03 21:09:47.452  1081  3879 I Keyboard.Facilitator.Delight2FileSweeper: run()
04-03 21:09:47.453  1081  3879 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-03 21:09:47.453  1081  3879 I StatsUtilsManager: startPeriodStatsRecorder() : Success
04-03 21:09:47.453  1081  3879 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,04-03 21:09:47.483  3907  3907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-03 21:09:47.488  1545  1545 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(268): Wear auto uninstall disabled for package com.test.thalitest
,04-03 21:09:47.501  1567  3928 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-03 21:09:47.501  1567  3928 D AccountUtils: Clearing selected account for com.test.thalitest
,04-03 21:09:47.507  1625  1625 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-03 21:09:47.507  1625  1625 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-03 21:09:47.516  3850  3850 I art     : System.exit called, status: 0
04-03 21:09:47.516  3850  3850 I AndroidRuntime: VM exiting with result code 0.
,04-03 21:09:47.536   740  1164 I ActivityManager: Start proc 3933:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,04-03 21:09:47.539  1567  3928 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,04-03 21:09:47.540  1194  1422 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-03 21:09:47.570   740   841 I ActivityManager: Start proc 3953:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,04-03 21:09:47.612  1567  3970 W BaseAppContext: Using Auth Proxy for data requests.
,04-03 21:09:47.614   740  1166 I ActivityManager: Killing 3252:com.quickoffice.android/u0a65 (adj 15): empty #17
,04-03 21:09:47.656  1567  3970 W BaseAppContext: Using Auth Proxy for data requests.
,04-03 21:09:47.662  1567  3970 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-03 21:09:47.662  1567  3970 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: Runtime exception while performing operation
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-03 21:09:47.664  1567  3970 E ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-03 21:09:47.664  1567  3970 F ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
04-03 21:09:47.682  1567  3928 I GMPM-SVC: App measurement is starting up, version: 8703
04-03 21:09:47.682  1567  3928 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
04-03 21:09:47.684   740  3975 E DropBoxManagerService: Can't write: system_app_wtf
04-03 21:09:47.684   740  3975 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
04-03 21:09:47.684   740  3975 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-03 21:09:47.684   740  3975 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-03 21:09:47.684   740  3975 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-03 21:09:47.684   740  3975 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-03 21:09:47.684   740  3975 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-03 21:09:47.684   740  3975 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-03 21:09:47.684   740  3975 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-03 21:09:47.684   740  3975 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-03 21:09:47.684   740  3975 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-03 21:09:47.684   740  3975 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-03 21:09:47.684   740  3975 E DropBoxManagerService: 	... 5 more
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(:com.google.android.gms:223)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(:com.google.android.gms:601)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(:com.google.android.gms:595)
04-03 21:09:47.690  1567  3974 E SQLiteDatabase: 	at com.google.android.gms.drive.database.o.run(:com.google.android.gms:616)
04-03 21:09:47.692   740  1164 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-03 21:09:47.692   740   869 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-03 21:09:47.692   740   869 D ConnectivityService: apparently satisfied.  currentScore=60
04-03 21:09:47.692  1567  3976 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-03 21:09:47.701  1567  3974 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
04-03 21:09:47.701  1567  3974 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
04-03 21:09:47.701  1567  3974 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
04-03 21:09:47.701  1567  3974 I GCore-Chimera-Crash: ==
04-03 21:09:47.701  1567  3974 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
04-03 21:09:47.701  1567  3974 E AndroidRuntime: FATAL EXCEPTION: Open database in background
04-03 21:09:47.701  1567  3974 E AndroidRuntime: Process: com.google.android.gms, PID: 1567
04-03 21:09:47.701  1567  3974 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at com.google.android.gms.drive.database.c.getWritableDatabase(:com.google.android.gms:223)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.b(:com.google.android.gms:601)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.a(:com.google.android.gms:595)
04-03 21:09:47.701  1567  3974 E AndroidRuntime: 	at com.google.android.gms.drive.database.o.run(:com.google.android.gms:616)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: Can't write: system_app_crash
04-03 21:09:47.704   740  3979 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-03 21:09:47.704   740  3979 E DropBoxManagerService: 	... 5 more
04-03 21:09:47.704  1567  1652 I Icing   : doRemovePackageData com.test.thalitest
04-03 21:09:47.708  1567  3978 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
04-03 21:09:47.709  1567  3978 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
04-03 21:09:47.709  1567  3978 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
04-03 21:09:47.709  1567  3978 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
04-03 21:09:47.709  1567  3978 I GCore-Chimera-Crash: ==
04-03 21:09:47.709  1567  3978 I GCore-Chimera-Crash: GCore-Chimera-Crash
04-03 21:09:47.709  1567  3978 I Process : Sending signal. PID: 1567 SIG: 9
04-03 21:09:47.727   740  1215 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@85a3f3f)
04-03 21:09:47.727   740   869 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-03 21:09:47.727   740   869 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-03 21:09:47.727   740   868 D WifiService: Client connection lost with reason: 4

```
