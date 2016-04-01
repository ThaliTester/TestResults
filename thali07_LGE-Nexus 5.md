#### Test 6480993629f6128_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
04-01 23:47:17.430  1549  1619 I Finsky  : [125] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
04-01 23:47:17.431  1549  1549 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
04-01 23:47:17.648  1568  2391 I CheckinService: Done disabling old GoogleServicesFramework version
,04-01 23:47:18.167  3473  3473 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-01 23:47:18.170  3473  3473 D AndroidRuntime: CheckJNI is OFF
04-01 23:47:18.271  3473  3473 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
04-01 23:47:18.275   742  1202 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-01 23:47:18.285   742  1202 V WindowManager: addAppToken: AppWindowToken{29e79549 token=Token{1aa08f50 ActivityRecord{122ea113 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
04-01 23:47:18.291  3473  3473 D AndroidRuntime: Shutting down VM
04-01 23:47:18.293  1357  1697 W SearchService: Abort, client detached.
04-01 23:47:18.294   742   836 V WindowManager: Adding window Window{b6f868 u0 Starting com.test.thalitest} at 2 of 7 (after Window{20af944b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-01 23:47:18.312   742   757 I ActivityManager: Start proc 3494:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
04-01 23:47:18.351  1357  1590 I DeviceStateChecker: DeviceStateChecker cancelled
04-01 23:47:18.351  1357  1357 I MicroDetector: Keeping mic open: false
04-01 23:47:18.351  1357  1357 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@ae5cf5e
04-01 23:47:18.408   190  1598 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-01 23:47:18.408   190  1598 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-01 23:47:18.414  1357  1595 I MicroRecognitionRunner: Detection finished
04-01 23:47:18.415  1357  1589 I MicroRecognitionRunner: Stopping hotword detection.
04-01 23:47:18.432  3494  3494 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
04-01 23:47:18.449  3494  3494 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 7204-7205)
04-01 23:47:18.449  3494  3494 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-01 23:47:18.463  3494  3494 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {38e387f1}
04-01 23:47:18.463  3494  3494 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-01 23:47:18.464  3494  3494 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
04-01 23:47:18.466   742  1175 I ActivityManager: Killing 1856:com.android.defcontainer/u0a4 (adj 15): empty #17
04-01 23:47:18.500  3494  3494 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,04-01 23:47:18.521  3494  3494 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-01 23:47:18.571   742   835 D BluetoothManagerService: Message: 20
04-01 23:47:18.571   742   835 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31b987d6:true
,04-01 23:47:18.577  3494  3494 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
04-01 23:47:18.577  3494  3494 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,04-01 23:47:18.612  3494  3494 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-01 23:47:18.613  3494  3494 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,04-01 23:47:18.625  3494  3494 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,04-01 23:47:18.630  3494  3494 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-01 23:47:18.631  3494  3494 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,04-01 23:47:18.640  3494  3494 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,04-01 23:47:18.667  3494  3546 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-01 23:47:18.671  3494  3494 D Atlas   : Validating map...
,04-01 23:47:18.743   742   869 I art     : Explicit concurrent mark sweep GC freed 25915(1497KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.457ms total 66.170ms
,04-01 23:47:18.835   183   183 D SurfaceFlinger: shader cache generated - 24 shaders in 135.650665 ms
,04-01 23:47:18.899   742   869 V WindowManager: Adding window Window{c9289d u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{b6f868 u0 Starting com.test.thalitest})
,04-01 23:47:18.906   742   860 D WifiService: New client listening to asynchronous messages
,04-01 23:47:18.918   742  1207 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-01 23:47:18.919   742   861 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-01 23:47:18.919   742   861 D ConnectivityService: apparently satisfied.  currentScore=60
,04-01 23:47:18.920  3494  3553 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-01 23:47:18.953  3494  3546 I OpenGLRenderer: Initialized EGL, version 1.4
,04-01 23:47:18.956  3494  3546 D OpenGLRenderer: Enabling debug mode 0
,04-01 23:47:19.020   742   836 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +726ms
,04-01 23:47:19.027  1099  1099 I Keyboard.Facilitator: onFinishInput()
,04-01 23:47:19.034  3494  3556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,04-01 23:47:19.068  3494  3494 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3494
,04-01 23:47:19.276  3494  3494 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-01 23:47:19.381  3494  3568 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1262869248
,04-01 23:47:19.384  3494  3568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-01 23:47:19.384  3494  3568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-01 23:47:19.384  3494  3568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-01 23:47:19.384  3494  3568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-01 23:47:19.384  3494  3568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-01 23:47:19.385  3494  3568 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@318a1241 added. We now have 1 listener(s)
04-01 23:47:19.385   742  1207 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-01 23:47:19.388  3494  3568 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,04-01 23:47:19.394  3494  3568 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
04-01 23:47:19.394  3494  3568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
04-01 23:47:19.394  3494  3568 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-01 23:47:19.396  3494  3568 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cc7cbd4 added. We now have 1 listener(s)
04-01 23:47:19.396  3494  3568 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-01 23:47:19.398  3494  3568 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,04-01 23:47:19.399  3494  3568 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
04-01 23:47:19.400  3494  3568 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,04-01 23:47:19.402  3494  3568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,04-01 23:47:19.402   742  3290 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
04-01 23:47:19.403  3494  3568 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,04-01 23:47:19.408  3494  3568 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 23:47:19.408  3494  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 23:47:19.408  3494  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-01 23:47:19.408  3494  3568 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 23:47:19.408  3494  3568 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 23:47:19.408  3494  3568 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 23:47:19.408  3494  3568 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 23:47:19.408  3494  3568 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-01 23:47:19.408  3494  3568 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-01 23:47:19.408  3494  3568 D io.jxcore.node.ConnectivityMonitor: start: OK
,04-01 23:47:19.409  3494  3494 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 23:47:19.410  3494  3568 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-01 23:47:19.411  3494  3494 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 23:47:19.441  3494  3494 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-01 23:47:20.040  3494  3571 W jxcore-log: Initializing JXcore engine
04-01 23:47:20.040  3494  3571 W jxcore-log: JXcore engine is ready
,04-01 23:47:20.069  3571  3571 W Thread-353: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9322]" dev="sockfs" ino=9322 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-01 23:47:20.069  3571  3571 W Thread-353: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,04-01 23:47:20.069  3571  3571 W Thread-353: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8364]" dev="sockfs" ino=8364 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-01 23:47:20.069  3571  3571 W Thread-353: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[18804]" dev="sockfs" ino=18804 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,04-01 23:47:20.086  3494  3571 W jxcore-log: Starting JXcore engine
,04-01 23:47:20.161  3494  3571 W jxcore-log: Platform android
04-01 23:47:20.161  3494  3571 W jxcore-log: 
04-01 23:47:20.161  3494  3571 W jxcore-log: Process ARCH arm
04-01 23:47:20.161  3494  3571 W jxcore-log: 
,04-01 23:47:20.330   742   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
,04-01 23:47:20.401  3494  3571 I jxcore-log: JXcore Cordova bridge is ready!
04-01 23:47:20.401  3494  3571 I jxcore-log: 
,04-01 23:47:20.402  3494  3571 W jxcore-log: JXcore engine is started
,04-01 23:47:20.409  3494  3568 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-01 23:47:20.410  3494  3494 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-01 23:47:22.468  3353  3393 W Babel   : aye TOOK TOO LONG! (15037ms > 10000ms)
,04-01 23:47:22.469  3353  3391 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,04-01 23:47:22.472   742  1172 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-01 23:47:22.476   742  1252 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-01 23:47:22.479  3353  3353 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
04-01 23:47:22.479  3353  3353 W Babel   : BAM#gBA: invalid account id: -1
04-01 23:47:22.479  3353  3353 W Babel   : BAM#gBA: invalid account id: -1
04-01 23:47:22.479  3353  3353 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,04-01 23:47:22.482   742  1141 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-01 23:47:22.484   742  1137 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-01 23:47:22.500  3353  3402 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,04-01 23:47:22.626  1624  1624 I art     : Explicit concurrent mark sweep GC freed 25954(1477KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 22MB/37MB, paused 982us total 33.771ms
,04-01 23:47:26.710  1549  1549 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(151): Beginning daily hygiene
,04-01 23:47:26.739  1624  1624 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 23:47:26.745  1624  1624 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 23:47:26.747  1624  1624 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 23:47:27.342  1624  1624 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 23:47:27.432  1549  1607 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-01 23:47:27.432  1549  1607 I qtaguid : Untagging socket 37 failed errno=-22
04-01 23:47:27.432  1549  1607 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-01 23:47:27.434  1549  1549 I Finsky  : [1] com.google.android.finsky.m.e.a(156): Skipping DFE self-update. Local Version [80631600] >= Server Version [-1]
,04-01 23:47:27.475  1624  1624 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 23:47:27.508   742  1175 I ActivityManager: Start proc 3620:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,04-01 23:47:27.544   201   201 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 274us total 22.388ms
,04-01 23:47:27.557   742  1202 I ActivityManager: Killing 3069:com.android.providers.calendar/u0a1 (adj 15): empty #17
,04-01 23:47:27.565   201   201 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 204us total 19.167ms
,04-01 23:47:27.568  3620  3620 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-01 23:47:27.568  3620  3620 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-01 23:47:27.575   201   201 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 197us total 9.467ms
,04-01 23:47:27.596  3620  3620 I MultiDex: VM with version 2.1.0 has multidex support
04-01 23:47:27.596  3620  3620 I MultiDex: install
04-01 23:47:27.596  3620  3620 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-01 23:47:27.966  3620  3620 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,04-01 23:47:28.006  3620  3620 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-01 23:47:28.024  1624  1624 D WearableService: callingUid 10007, callindPid: 1624
,04-01 23:47:28.027  1624  2859 E MDM     : [215] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,04-01 23:47:28.033  3620  3620 D ChimeraCfgMgr: Reading stored module config
,04-01 23:47:28.037  1624  1624 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-01 23:47:28.044  1624  1624 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 23:47:28.051  1568  3656 D LocationInitializer: Restart initialization of location
,04-01 23:47:28.095  1624  1669 W GCoreFlp: No location to return for getLastLocation()
,04-01 23:47:28.096  1624  3660 W FusedLocationProvider: location=null
,04-01 23:47:28.156  3620  3657 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,04-01 23:47:28.184  3620  3620 D CAR.SERVICE: Connecting to CarCallService...
,04-01 23:47:28.196  3620  3620 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
04-01 23:47:28.196  3620  3620 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-01 23:47:28.202  3620  3620 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,04-01 23:47:28.207  1549  1606 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-01 23:47:28.207  1549  1606 I qtaguid : Untagging socket 37 failed errno=-22
04-01 23:47:28.207  1549  1606 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
04-01 23:47:28.208  3620  3620 D CAR.TEL.Service: Creating a new CarCallService.
04-01 23:47:28.209  3620  3620 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,04-01 23:47:28.216   742  1207 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,04-01 23:47:28.217  3620  3620 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@1556f296
,04-01 23:47:28.217   742   758 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
04-01 23:47:28.217  3620  3620 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
,04-01 23:47:28.217  3620  3620 D CAR.TEL.Service: Starting CarCallService with initial phone null
,04-01 23:47:28.290  3620  3641 D CAR.SERVICE: Package validated; name: com.android.vending
,04-01 23:47:28.814  1624  1624 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 23:47:29.252  1549  1607 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-01 23:47:29.252  1549  1607 I qtaguid : Untagging socket 37 failed errno=-22
04-01 23:47:29.252  1549  1607 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-01 23:47:29.352  1549  1549 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(9405): Logging device features
,04-01 23:47:29.388  1624  1676 D DeviceConnectionService: client connected with version: 8298000
,04-01 23:47:29.393  1549  1549 E Finsky  : [1] com.google.android.finsky.wear.bf.a(728): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
04-01 23:47:29.393  1549  1549 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6337): Dropping command=hygiene due to Gms not connected
,04-01 23:47:29.553  3494  3571 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-01 23:47:29.553  3494  3571 I jxcore-log: 
04-01 23:47:29.555  3494  3571 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-01 23:47:29.555  3494  3571 I jxcore-log: 
,04-01 23:47:29.558  3494  3571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 23:47:29.558  3494  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 23:47:29.558  3494  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-01 23:47:29.558  3494  3571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 23:47:29.558  3494  3571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 23:47:29.558  3494  3571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 23:47:29.558  3494  3571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 23:47:29.558  3494  3571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-01 23:47:29.560  3494  3571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
04-01 23:47:29.561  3494  3571 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-01 23:47:29.561  3494  3571 I jxcore-log: 
04-01 23:47:29.562  3494  3571 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-01 23:47:29.562  3494  3571 I jxcore-log: 
,04-01 23:47:30.052  3494  3571 I jxcore-log: Unit Test app is loaded
04-01 23:47:30.052  3494  3571 I jxcore-log: 
,04-01 23:47:30.057  3494  3571 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-01 23:47:30.057  3494  3571 I jxcore-log: 
04-01 23:47:30.058  3494  3494 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-01 23:47:30.061  3494  3571 I jxcore-log: My device name is: LGE-Nexus 5
04-01 23:47:30.061  3494  3571 I jxcore-log: 
,04-01 23:47:32.544   742   831 I ActivityManager: Start proc 3704:com.android.providers.calendar/u0a1 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,04-01 23:47:32.568  3704  3704 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,04-01 23:47:32.589  3704  3704 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@172f8398(com.android.providers.calendar.CalendarProvider2@38e387f1)
,04-01 23:47:32.614  3704  3722 E SQLiteLog: (284) automatic index on view_events(_id)
,04-01 23:47:32.634  1549  3732 I Finsky  : [134] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-01 23:47:32.640  1624  1624 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 23:47:33.347  3620  3620 D CAR.SERVICE: mConnectedToCar = false, abort
,04-01 23:47:33.350   742   758 I ActivityManager: Killing 3095:com.google.android.apps.magazines/u0a56 (adj 15): empty #17
,04-01 23:47:33.357  3620  3620 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@f70c16c that was originally bound here
04-01 23:47:33.357  3620  3620 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@f70c16c that was originally bound here
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-01 23:47:33.357  3620  3620 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-01 23:47:33.372   742  1252 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@be2912e)
,04-01 23:47:33.373   742   861 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-01 23:47:33.373   742   861 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-01 23:47:33.659  3620  3620 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3adb0db1 that was originally bound here
04-01 23:47:33.659  3620  3620 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3adb0db1 that was originally bound here
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-01 23:47:33.659  3620  3620 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-01 23:47:33.660   742   757 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@f4804cf
,04-01 23:47:33.663  3704  3704 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
04-01 23:47:33.663  3704  3704 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,04-01 23:47:33.808  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-01 23:47:33.808  3494  3571 I jxcore-log: 
,04-01 23:47:34.150  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-01 23:47:34.150  3494  3571 I jxcore-log: 
,04-01 23:47:34.161  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-01 23:47:34.161  3494  3571 I jxcore-log: 
,04-01 23:47:34.164  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-01 23:47:34.164  3494  3571 I jxcore-log: 
,04-01 23:47:34.179  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-01 23:47:34.179  3494  3571 I jxcore-log: 
,04-01 23:47:34.183  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-01 23:47:34.183  3494  3571 I jxcore-log: 
,04-01 23:47:36.101  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-01 23:47:36.101  3494  3571 I jxcore-log: 
,04-01 23:47:36.122  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-01 23:47:36.122  3494  3571 I jxcore-log: 
,04-01 23:47:36.130  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-01 23:47:36.130  3494  3571 I jxcore-log: 
,04-01 23:47:36.279  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-01 23:47:36.279  3494  3571 I jxcore-log: 
,04-01 23:47:36.360  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-01 23:47:36.360  3494  3571 I jxcore-log: 
,04-01 23:47:36.415  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-01 23:47:36.415  3494  3571 I jxcore-log: 
,04-01 23:47:36.420  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
04-01 23:47:36.420  3494  3571 I jxcore-log: 
,04-01 23:47:36.552  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-01 23:47:36.552  3494  3571 I jxcore-log: 
,04-01 23:47:36.572  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-01 23:47:36.572  3494  3571 I jxcore-log: 
,04-01 23:47:36.577  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-01 23:47:36.577  3494  3571 I jxcore-log: 
04-01 23:47:36.582  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-01 23:47:36.582  3494  3571 I jxcore-log: 
,04-01 23:47:36.597  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-01 23:47:36.597  3494  3571 I jxcore-log: 
,04-01 23:47:36.615  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-01 23:47:36.615  3494  3571 I jxcore-log: 
,04-01 23:47:36.696  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-01 23:47:36.696  3494  3571 I jxcore-log: 
,04-01 23:47:36.701  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-01 23:47:36.701  3494  3571 I jxcore-log: 
,04-01 23:47:36.724  3494  3571 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-01 23:47:36.724  3494  3571 I jxcore-log: 
,04-01 23:47:36.734  3494  3571 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
04-01 23:47:36.736  3494  3571 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
04-01 23:47:36.736  3494  3571 I jxcore-log: 
,04-01 23:47:38.837   742   757 I ActivityManager: Killing 2545:com.google.android.gm/u0a41 (adj 15): empty #17
,04-01 23:47:40.333   742   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
04-01 23:47:40.334   742   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 23:47:46.571  1549  1619 I Finsky  : [125] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-01 23:47:46.571  1549  1549 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-01 23:48:00.334   742   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
,04-01 23:48:19.040  1099  1313 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-01 23:48:19.041  1099  1313 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-01 23:48:19.089  1624  1624 I ConfigService: onCreate
,04-01 23:48:20.338   742   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
04-01 23:48:20.339   742   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 23:48:20.595   742  1126 D AlarmManagerService: Setting time of day to sec=1459547300
04-01 23:48:20.851   742  1126 W AlarmManagerService: Unable to set rtc to 1459547300: Invalid argument
,04-01 23:48:20.886   742  1137 I art     : Explicit concurrent mark sweep GC freed 43014(1999KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.624ms total 66.612ms
,04-01 23:48:20.910   742   831 I ActivityManager: Start proc 3794:com.qualcomm.timeservice/u0a68 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,04-01 23:48:21.000  3794  3794 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459547301000
,04-01 23:48:21.000  3794  3794 D         : TimeServiceNative: User Time to be set is 1459547301000
04-01 23:48:21.000  3794  3794 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
04-01 23:48:21.000  3794  3794 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
04-01 23:48:21.000  3794  3794 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459547301000
04-01 23:48:21.000   205   604 D QC-time-services: Daemon: Connection accepted:time_genoff
,04-01 23:48:21.001  3794  3794 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
04-01 23:48:21.001   205  3813 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459547301000
04-01 23:48:21.001   205  3813 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459547301000, operation = 0
04-01 23:48:21.001   205  3813 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/23/71 15:52:50
04-01 23:48:21.001   205  3813 D QC-time-services: Daemon:Value read from RTC seconds = 43861970000
04-01 23:48:21.001   205  3813 D QC-time-services: Daemon:new time 1459547301000 
04-01 23:48:21.001   205  3813 D QC-time-services: Daemon: delta 1415685331000 genoff 1415685331000 
04-01 23:48:21.001   205  3813 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1415685331000 to memory
04-01 23:48:21.001   205  3813 D QC-time-services: Daemon:Opening File: /data/system/time/ats_2
04-01 23:48:21.001   205  3813 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,04-01 23:48:21.006   205  3813 D QC-time-services: Updating the TOD offset
04-01 23:48:21.006   205  3813 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1415685331000 to memory
04-01 23:48:21.006   205  3813 D QC-time-services: Daemon:Opening File: /data/system/time/ats_1
04-01 23:48:21.006   205  3813 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,04-01 23:48:21.009   205  3813 D QC-time-services: Daemon:Update to modem bit set
04-01 23:48:21.009  3794  3794 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,04-01 23:48:21.012   205  3813 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
04-01 23:48:21.012   205  3813 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143582501000
,04-01 23:48:21.014   742  1202 I ActivityManager: Killing 2900:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,04-01 23:48:21.018   205   604 D QC-time-services: Daemon: Time-services: Waiting to acceptconnection
04-01 23:48:21.018   205   602 D QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,04-01 23:48:21.077  1624  1624 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 23:48:21.084  1624  3817 I VacuumService: Vacuum at: now=1459547301084 tag=VacuumService
,04-01 23:48:21.322   742  1250 I ActivityManager: Start proc 3819:com.google.android.deskclock/u0a33 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,04-01 23:48:21.391  3819  3819 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
04-01 23:48:21.391  3819  3819 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
04-01 23:48:21.391  3819  3819 I GAv4    :   adb logcat -s GAv4
,04-01 23:48:21.406  3819  3819 I AlarmClock: AlarmInitReceiver android.intent.action.TIME_SET
,04-01 23:48:21.445  3300  3840 E SQLiteLog: (284) automatic index on blob_node(tree_entity_id)
,04-01 23:48:21.448  3300  3840 E SQLiteLog: (284) automatic index on blob_node(tree_entity_id)
,04-01 23:48:21.460   742   869 I ActivityManager: Killing 3244:com.google.android.configupdater/u0a2 (adj 15): empty #17
,04-01 23:48:24.436  1624  1624 I ConfigService: onDestroy
,04-01 23:48:40.598   742   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
04-01 23:48:40.598   742   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 23:48:55.564   742   838 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
04-01 23:48:55.568   742   838 I PowerManagerService: Sleeping (uid 1000)...
,04-01 23:48:55.623   190   876 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-01 23:48:55.628   742   838 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-01 23:48:55.639   183   843 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (105 us)
,04-01 23:48:55.650   742   859 E WifiStateMachine: cancelDelayedScan -> 11
,04-01 23:48:55.654   742   859 E native  : do suspend false
,04-01 23:48:55.849  1099  1099 I Keyboard.Facilitator: onFinishInput()
04-01 23:48:55.849   190   190 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,04-01 23:48:55.859   742   859 E WifiStateMachine: cancelDelayedScan -> 13
,04-01 23:48:55.862   742   859 E native  : do suspend true
,04-01 23:48:56.154   742   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
04-01 23:48:56.154   742   859 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,04-01 23:48:56.212   742   836 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
04-01 23:48:56.214   742   742 V ActivityManager: Display changed displayId=0
,04-01 23:48:56.219   183   183 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
04-01 23:48:56.219   183   183 D qdhwcomposer: hwc_blank: Blanking display: 0
,04-01 23:48:56.337   184   184 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
04-01 23:48:56.337   184   184 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
04-01 23:48:56.337   184   184 I rmt_storage: wakelock acquired: 1, error no: 2
04-01 23:48:56.338   184   562 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236802816)
,04-01 23:48:56.431   184   562 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
04-01 23:48:56.431   184   562 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,04-01 23:48:56.432   184   562 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236802816) wakelock released: 1, error no: 0
04-01 23:48:56.432   184   562 I rmt_storage: 
,04-01 23:48:56.433   184   184 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,04-01 23:48:56.509   183   183 D qdhwcomposer: hwc_blank: Done blanking display: 0
04-01 23:48:56.509   742   885 D SurfaceControl: Excessive delay in setPowerMode(): 291ms
,04-01 23:48:56.510  1928  1932 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,04-01 23:48:56.518  3494  3494 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
04-01 23:48:56.518  3494  3494 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,04-01 23:48:56.545  3494  3494 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5d0645e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@625438a, 16908290=android.view.AbsSavedState$1@625438a}, android:focusedViewId=100}]}]
04-01 23:48:56.545  3494  3494 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
04-01 23:48:56.545  3494  3494 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
04-01 23:48:56.545  3494  3494 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,04-01 23:49:00.603   742   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
04-01 23:49:00.603   742   859 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
04-01 23:49:00.606  1624  1904 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,04-01 23:49:03.632  1624  3894 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 14243 seconds from now (1459547343632)
,04-01 23:49:03.713  1624  3885 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,04-01 23:49:03.716  1624  3885 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-01 23:49:04.531  1624  3885 I art     : WaitForGcToComplete blocked for 34.494ms for cause Explicit
,04-01 23:49:04.559  1624  1636 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@374ba44b)
04-01 23:49:04.559  1624  1636 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3445fe28)
04-01 23:49:04.560  1624  1636 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@102d9741)
04-01 23:49:04.560  1624  1636 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4c564e6)
04-01 23:49:04.560  1624  1636 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1cae3a27)
,04-01 23:49:04.603  1624  3885 I art     : Explicit concurrent mark sweep GC freed 13838(617KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 27MB/43MB, paused 1.264ms total 72.746ms
,04-01 23:49:05.150  1624  1624 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 23:49:05.151  1624  1624 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 23:49:55.850  1099  1313 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-01 23:49:55.850  1099  1313 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-01 23:49:55.899  1624  1624 I ConfigService: onCreate
,04-01 23:49:59.334  3494  3571 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-01 23:49:59.334  3494  3571 I jxcore-log: 
,04-01 23:49:59.727  3923  3923 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-01 23:49:59.730  3923  3923 D AndroidRuntime: CheckJNI is OFF
,04-01 23:49:59.827  3923  3923 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-01 23:49:59.832   742   831 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
,04-01 23:49:59.832   742   831 I ActivityManager: Killing 3494:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,04-01 23:49:59.873   742   842 W PackageSettings: Skipping PackageSetting{1e1b019c com.example.hello/10116} due to missing metadata
,04-01 23:49:59.895   742  1207 I WindowState: WIN DEATH: Window{c9289d u0 com.test.thalitest/com.test.thalitest.MainActivity}
04-01 23:49:59.895   742  1252 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@19f6baec)
04-01 23:49:59.895   742   860 D WifiService: Client connection lost with reason: 4
,04-01 23:49:59.896   742   861 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-01 23:49:59.896   742   861 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-01 23:50:00.042   742   831 I ActivityManager:   Force finishing activity 3 ActivityRecord{122ea113 u0 com.test.thalitest/.MainActivity t19}
,04-01 23:50:00.047   742   758 W ActivityManager: Spurious death for ProcessRecord{3989aeb5 3494:com.test.thalitest/u0a49}, curProc for 3494: null
,04-01 23:50:00.047   742   842 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,04-01 23:50:00.049   742   842 I ActivityManager:   Force finishing activity 3 ActivityRecord{122ea113 u0 com.test.thalitest/.MainActivity t19 f}
04-01 23:50:00.049   742   842 W ActivityManager: Duplicate finish request for ActivityRecord{122ea113 u0 com.test.thalitest/.MainActivity t19 f}
,04-01 23:50:00.077   908   908 I art     : Explicit concurrent mark sweep GC freed 10118(445KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 814us total 22.880ms
,04-01 23:50:00.104  1203  1203 I art     : Explicit concurrent mark sweep GC freed 1694(106KB) AllocSpace objects, 5(450KB) LOS objects, 38% free, 25MB/41MB, paused 2.330ms total 49.945ms
,04-01 23:50:00.138   742   742 I art     : Explicit concurrent mark sweep GC freed 36596(1997KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 29MB/43MB, paused 1.142ms total 59.689ms
,04-01 23:50:00.153   742   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-01 23:50:00.154  1099  1099 I Keyboard.Facilitator: resetDictionaries() : en_US
,04-01 23:50:00.159  1624  1678 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,04-01 23:50:00.161  1099  3952 I Keyboard.Facilitator.DecoderInitializer: run()
,04-01 23:50:00.163  1099  3952 I Decoder : createOrResetDecoder
,04-01 23:50:00.166   742   887 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
04-01 23:50:00.166   742   887 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,04-01 23:50:00.170  1568  1568 I art     : Explicit concurrent mark sweep GC freed 3369(194KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 23MB/31MB, paused 491us total 120.111ms
,04-01 23:50:00.190  3419  3954 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,04-01 23:50:00.195  1357  1357 I art     : Explicit concurrent mark sweep GC freed 3343(256KB) AllocSpace objects, 7(154KB) LOS objects, 25% free, 22MB/30MB, paused 11.308ms total 140.631ms
,04-01 23:50:00.206   742  1252 I ActivityManager: Start proc 3959:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,04-01 23:50:00.235  1099  3952 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,04-01 23:50:00.240   742   742 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-01 23:50:00.240   742   742 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,04-01 23:50:00.260  1099  3952 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,04-01 23:50:00.262  1099  3952 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
04-01 23:50:00.262  1099  3952 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,04-01 23:50:00.264  1099  3952 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
04-01 23:50:00.264  1099  3952 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,04-01 23:50:00.265  1099  3952 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
04-01 23:50:00.265  1099  3952 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
04-01 23:50:00.266  1099  3952 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-01 23:50:00.266  1099  3952 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-01 23:50:00.266  1099  3952 I Keyboard.Facilitator.Delight2FileSweeper: run()
04-01 23:50:00.266  1099  3952 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-01 23:50:00.266  1099  3952 I StatsUtilsManager: startPeriodStatsRecorder() : Success
04-01 23:50:00.266  1099  3952 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,04-01 23:50:00.281   742  1252 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3494 uid 10049
,04-01 23:50:00.282  1099  1099 I Keyboard.Facilitator: onFinishInput()
,04-01 23:50:00.283   742   869 I ActivityManager: Start proc 3980:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,04-01 23:50:00.302   742  1207 I ActivityManager: Killing 3276:com.google.android.apps.gcs/u0a37 (adj 15): empty #17
,04-01 23:50:00.307  1203  1203 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-01 23:50:00.308  3980  3980 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-01 23:50:00.340   742   842 I art     : Explicit concurrent mark sweep GC freed 15493(1427KB) AllocSpace objects, 1(1296KB) LOS objects, 33% free, 28MB/42MB, paused 1.859ms total 122.341ms
,04-01 23:50:00.391  3923  3923 I art     : System.exit called, status: 0
04-01 23:50:00.391  3923  3923 I AndroidRuntime: VM exiting with result code 0.
,04-01 23:50:00.435   742   842 I ActivityManager: Start proc 4000:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,04-01 23:50:00.439   742   869 I ActivityManager: Killing 3168:com.google.android.apps.photos/u0a83 (adj 15): empty #17
,04-01 23:50:00.440  1549  1549 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(268): Wear auto uninstall disabled for package com.test.thalitest
,04-01 23:50:00.459  1203  1408 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-01 23:50:00.491  1568  4020 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-01 23:50:00.491  1568  4020 D AccountUtils: Clearing selected account for com.test.thalitest
,04-01 23:50:00.498   742  1137 I ActivityManager: Killing 2831:com.google.android.setupwizard/u0a16 (adj 15): empty #17
,04-01 23:50:00.532  1568  4020 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,04-01 23:50:00.534  1624  1624 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,04-01 23:50:00.534  1624  1624 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-01 23:50:00.565   742  1202 I ActivityManager: Start proc 4026:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,04-01 23:50:00.572  1568  4020 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 23:50:00.572  1568  4020 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: Could not unregister android package com.test.thalitest
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer:, 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 23:50:00.572  1568  4020 E PhenotypeInitializer: 	at java.lang.Thread.run(Thread.java:818)

```
