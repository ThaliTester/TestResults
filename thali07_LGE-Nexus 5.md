#### Test 681021307227906_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
04-28 21:25:07.285  3005  3005 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=2 stopped=true)
--------- beginning of system
04-28 21:25:07.300   763  1180 I ActivityManager: Killing 2848:com.android.musicfx/u0a13 (adj 15): empty #17
,04-28 21:25:07.788  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
04-28 21:25:07.863  3361  3361 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-28 21:25:07.866  3361  3361 D AndroidRuntime: CheckJNI is OFF
04-28 21:25:07.940  2884  2910 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-28 21:25:07.940  2884  2910 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
04-28 21:25:07.956  2884  2910 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
04-28 21:25:07.960  3361  3361 D AndroidRuntime: Calling main entry com.android.commands.am.Am
04-28 21:25:07.967   763  1189 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-28 21:25:07.972   763  1189 V WindowManager: addAppToken: AppWindowToken{10539ec4 token=Token{23d735d7 ActivityRecord{392b4156 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
04-28 21:25:07.974  3361  3361 D AndroidRuntime: Shutting down VM
04-28 21:25:07.976   763   836 V WindowManager: Adding window Window{375d08cf u0 Starting com.test.thalitest} at 2 of 7 (after Window{1138b665 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-28 21:25:07.980  1443  1474 W SearchService: Abort, client detached.
04-28 21:25:08.010  2884  2910 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
04-28 21:25:08.012   763   971 I ActivityManager: Start proc 3383:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
04-28 21:25:08.039  1443  1586 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
04-28 21:25:08.050  1443  1443 I MicroDetector: Keeping mic open: false
04-28 21:25:08.050  1443  1443 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ah@122ae83c
04-28 21:25:08.052  1443  1588 I DeviceStateChecker: DeviceStateChecker cancelled
04-28 21:25:08.095  3383  3383 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
04-28 21:25:08.104  3383  3383 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 5492-5493)
04-28 21:25:08.104  3383  3383 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-28 21:25:08.108   189  1594 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-28 21:25:08.108   189  1594 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-28 21:25:08.113  1443  1591 I MicroRecognitionRunner: Detection finished
04-28 21:25:08.114  1443  1587 I MicroRecognitionRunner: Stopping hotword detection.
04-28 21:25:08.117  3383  3383 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3e6d19cc}
04-28 21:25:08.117  3383  3383 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-28 21:25:08.117  3383  3383 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
04-28 21:25:08.133  3383  3383 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
04-28 21:25:08.147  3383  3383 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-28 21:25:08.200   763   835 D BluetoothManagerService: Message: 20
04-28 21:25:08.200   763   835 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@221a45d5:true
,04-28 21:25:08.206  3383  3383 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,04-28 21:25:08.206  3383  3383 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,04-28 21:25:08.248  3383  3383 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-28 21:25:08.249  3383  3383 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,04-28 21:25:08.261  3383  3383 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,04-28 21:25:08.268  3383  3383 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-28 21:25:08.269  3383  3383 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,04-28 21:25:08.278  3383  3383 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,04-28 21:25:08.299  3383  3440 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
04-28 21:25:08.304  3383  3383 D Atlas   : Validating map...
04-28 21:25:08.309   763  1031 V WindowManager: Adding window Window{1b342aa8 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{375d08cf u0 Starting com.test.thalitest})
,04-28 21:25:08.316   763   860 D WifiService: New client listening to asynchronous messages
,04-28 21:25:08.327   763  1236 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-28 21:25:08.327   763   861 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-28 21:25:08.327   763   861 D ConnectivityService: apparently satisfied.  currentScore=60
04-28 21:25:08.328  3383  3442 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-28 21:25:08.332   763   831 I ActivityManager: Waited long enough for: ServiceRecord{8b04b5 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,04-28 21:25:08.354  3383  3440 I OpenGLRenderer: Initialized EGL, version 1.4
,04-28 21:25:08.359  3383  3440 D OpenGLRenderer: Enabling debug mode 0
,04-28 21:25:08.543   177   177 D SurfaceFlinger: shader cache generated - 24 shaders in 170.182449 ms
,04-28 21:25:08.573   763   836 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +593ms
,04-28 21:25:08.578  1092  1092 I Keyboard.Facilitator: onFinishInput()
,04-28 21:25:08.581  3383  3452 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,04-28 21:25:08.613  3383  3383 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3383
,04-28 21:25:08.702  3383  3383 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-28 21:25:08.861  3383  3458 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1569236608
,04-28 21:25:08.868  3383  3458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-28 21:25:08.868  3383  3458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-28 21:25:08.868  3383  3458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-28 21:25:08.868  3383  3458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-28 21:25:08.868  3383  3458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,04-28 21:25:08.869  3383  3458 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cb9a0cf added. We now have 1 listener(s)
04-28 21:25:08.870   763  1236 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-28 21:25:08.873  3383  3458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,04-28 21:25:08.876  3383  3458 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,04-28 21:25:08.877  3383  3458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
04-28 21:25:08.877  3383  3458 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-28 21:25:08.880  3383  3458 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6dde3a added. We now have 1 listener(s)
04-28 21:25:08.881  3383  3458 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-28 21:25:08.885  3383  3458 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,04-28 21:25:08.887  3383  3458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
04-28 21:25:08.887  3383  3458 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,04-28 21:25:08.889  3383  3458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
04-28 21:25:08.890   763  1031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-28 21:25:08.891  3383  3458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,04-28 21:25:08.895  3383  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-28 21:25:08.895  3383  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-28 21:25:08.895  3383  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-28 21:25:08.895  3383  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-28 21:25:08.895  3383  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-28 21:25:08.895  3383  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-28 21:25:08.895  3383  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-28 21:25:08.895  3383  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-28 21:25:08.895  3383  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-28 21:25:08.895  3383  3458 D io.jxcore.node.ConnectivityMonitor: start: OK
,04-28 21:25:08.897  3383  3458 I io.jxcore.node.LifeCycleMonitor: start: OK
04-28 21:25:08.897  3383  3383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-28 21:25:08.899  3383  3383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-28 21:25:08.923  3383  3383 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-28 21:25:09.575  3383  3459 W jxcore-log: Initializing JXcore engine
,04-28 21:25:09.575  3383  3459 W jxcore-log: JXcore engine is ready
,04-28 21:25:09.625  3459  3459 W Thread-342: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[6749]" dev="sockfs" ino=6749 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,04-28 21:25:09.625  3459  3459 W Thread-342: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
04-28 21:25:09.625  3459  3459 W Thread-342: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[7820]" dev="sockfs" ino=7820 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-28 21:25:09.625  3459  3459 W Thread-342: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[17671]" dev="sockfs" ino=17671 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,04-28 21:25:09.651  3383  3459 W jxcore-log: Starting JXcore engine
,04-28 21:25:09.756  3383  3459 W jxcore-log: Platform android
04-28 21:25:09.756  3383  3459 W jxcore-log: 
04-28 21:25:09.756  3383  3459 W jxcore-log: Process ARCH arm
04-28 21:25:09.756  3383  3459 W jxcore-log: 
,04-28 21:25:09.788   763   831 I ActivityManager: Waited long enough for: ServiceRecord{ebf56f8 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,04-28 21:25:09.950  3383  3459 I jxcore-log: JXcore Cordova bridge is ready!
04-28 21:25:09.950  3383  3459 I jxcore-log: 
04-28 21:25:09.951  3383  3459 W jxcore-log: JXcore engine is started
,04-28 21:25:09.953  3383  3458 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-28 21:25:09.955  3383  3383 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-28 21:25:10.228  1736  1788 I Finsky  : [144] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,04-28 21:25:10.309  1736  1788 I Finsky  : [144] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,04-28 21:25:10.310  1736  1736 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,04-28 21:25:12.122  1538  2496 I CheckinService: Done disabling old GoogleServicesFramework version
,04-28 21:25:12.151  3005  3030 W Babel   : aye TOOK TOO LONG! (15029ms > 10000ms)
,04-28 21:25:12.152  3005  3028 W Babel   : aye TOOK TOO LONG! (15032ms > 10000ms)
,04-28 21:25:12.156   763   968 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-28 21:25:12.160   763  1234 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-28 21:25:12.163  3005  3005 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
04-28 21:25:12.163  3005  3005 W Babel   : BAM#gBA: invalid account id: -1
04-28 21:25:12.163  3005  3005 W Babel   : BAM#gBA: invalid account id: -1
04-28 21:25:12.163  3005  3005 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,04-28 21:25:12.165   763  1031 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-28 21:25:12.167   763   779 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-28 21:25:12.272  3005  3038 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,04-28 21:25:13.014   763   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-48
,04-28 21:25:19.645  3383  3459 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-28 21:25:19.645  3383  3459 I jxcore-log: 
04-28 21:25:19.647  3383  3459 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-28 21:25:19.647  3383  3459 I jxcore-log: 
,04-28 21:25:19.651  3383  3459 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-28 21:25:19.651  3383  3459 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-28 21:25:19.651  3383  3459 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-28 21:25:19.651  3383  3459 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-28 21:25:19.651  3383  3459 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-28 21:25:19.651  3383  3459 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-28 21:25:19.651  3383  3459 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-28 21:25:19.651  3383  3459 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-28 21:25:19.653  3383  3459 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,04-28 21:25:19.655  3383  3459 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-28 21:25:19.655  3383  3459 I jxcore-log: 
04-28 21:25:19.657  3383  3459 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-28 21:25:19.657  3383  3459 I jxcore-log: 
,04-28 21:25:20.049  3383  3459 I jxcore-log: Unit Test app is loaded
04-28 21:25:20.049  3383  3459 I jxcore-log: 
,04-28 21:25:20.054  3383  3459 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-28 21:25:20.054  3383  3459 I jxcore-log: 
,04-28 21:25:20.057  3383  3459 I jxcore-log: My device name is: LGE-Nexus 5
04-28 21:25:20.057  3383  3459 I jxcore-log: 
,04-28 21:25:20.058  3383  3459 I jxcore-log: WARN testUtils: myNameCallback not set!
04-28 21:25:20.058  3383  3459 I jxcore-log: 
,04-28 21:25:20.060  3383  3383 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-28 21:25:22.282  1736  1736 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,04-28 21:25:22.304  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:25:22.309  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:25:22.311  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:25:22.980  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:25:23.085  1736  1736 I Finsky  : [1] com.google.android.finsky.m.e.a(152): Skipping DFE self-update. Local Version [80641200] >= Server Version [-1]
,04-28 21:25:23.135  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:25:23.162   763  1258 I ActivityManager: Start proc 3535:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,04-28 21:25:23.197  3535  3535 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-28 21:25:23.197  3535  3535 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-28 21:25:23.225  3535  3535 I MultiDex: VM with version 2.1.0 has multidex support
04-28 21:25:23.225  3535  3535 I MultiDex: install
04-28 21:25:23.225  3535  3535 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-28 21:25:23.244  3535  3535 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,04-28 21:25:23.301  3535  3535 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-28 21:25:23.310  3535  3535 D ChimeraCfgMgr: Reading stored module config
,04-28 21:25:23.314  1630  1630 D WearableService: callingUid 10007, callindPid: 1630
,04-28 21:25:23.317  1630  1933 E MDM     : [195] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,04-28 21:25:23.324  1630  1630 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-28 21:25:23.324  1538  3566 D LocationInitializer: Restart initialization of location
,04-28 21:25:23.335  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:25:23.345  1630  1691 W GCoreFlp: No location to return for getLastLocation()
04-28 21:25:23.346  1630  3567 W FusedLocationProvider: location=null
,04-28 21:25:23.408  3535  3565 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,04-28 21:25:23.411  3535  3535 D CAR.SERVICE: Connecting to CarCallService...
,04-28 21:25:23.422  3535  3535 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
04-28 21:25:23.423  3535  3535 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-28 21:25:23.428  3535  3535 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,04-28 21:25:23.429   763  1183 I ActivityManager: Killing 2884:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,04-28 21:25:23.558  3535  3535 D CAR.TEL.Service: Creating a new CarCallService.
,04-28 21:25:23.559  3535  3535 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,04-28 21:25:23.562   763  1189 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,04-28 21:25:23.562  3535  3535 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@13ca9dd5
04-28 21:25:23.562   763  1183 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,04-28 21:25:23.563  3535  3535 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
04-28 21:25:23.563  3535  3535 D CAR.TEL.Service: Starting CarCallService with initial phone null
,04-28 21:25:23.630  3535  3550 D CAR.SERVICE: Package validated; name: com.android.vending
,04-28 21:25:23.916  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-28 21:25:23.916  3383  3459 I jxcore-log: 
,04-28 21:25:24.097  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:25:24.270  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-28 21:25:24.270  3383  3459 I jxcore-log: 
,04-28 21:25:24.302  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-28 21:25:24.302  3383  3459 I jxcore-log: 
04-28 21:25:24.306  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-28 21:25:24.306  3383  3459 I jxcore-log: 
,04-28 21:25:24.322  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-28 21:25:24.322  3383  3459 I jxcore-log: 
04-28 21:25:24.325  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-28 21:25:24.325  3383  3459 I jxcore-log: 
,04-28 21:25:24.481  1736  1736 I Finsky  : [1] com.google.android.finsky.api.model.t.b(6629): Change varies-by-account for com.google.android.apps.genie.geniewidget to false
,04-28 21:25:24.483  1736  1736 I Finsky  : [1] com.google.android.finsky.api.model.t.b(8654): Change auto-acquire tags for com.google.android.apps.genie.geniewidget from d_AAAAAAADF8w= to 
,04-28 21:25:24.530  1736  1736 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler.b(99): Scheduling auto-update check using JobScheduler.
,04-28 21:25:24.538  1736  1736 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10401): Logging device features
,04-28 21:25:24.579  1630  1646 D DeviceConnectionService: client connected with version: 8486000
,04-28 21:25:24.582  1736  1736 E Finsky  : [1] com.google.android.finsky.wear.bh.a(742): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
04-28 21:25:24.582  1736  1736 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6349): Dropping command=hygiene due to Gms not connected
,04-28 21:25:26.276  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-28 21:25:26.276  3383  3459 I jxcore-log: 
,04-28 21:25:26.287  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-28 21:25:26.287  3383  3459 I jxcore-log: 
,04-28 21:25:26.296  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-28 21:25:26.296  3383  3459 I jxcore-log: 
,04-28 21:25:26.446  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-28 21:25:26.446  3383  3459 I jxcore-log: 
,04-28 21:25:26.527  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-28 21:25:26.527  3383  3459 I jxcore-log: 
,04-28 21:25:26.580  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-28 21:25:26.580  3383  3459 I jxcore-log: 
,04-28 21:25:26.587  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
04-28 21:25:26.587  3383  3459 I jxcore-log: 
,04-28 21:25:26.720  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-28 21:25:26.720  3383  3459 I jxcore-log: 
,04-28 21:25:26.740  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-28 21:25:26.740  3383  3459 I jxcore-log: 
,04-28 21:25:26.744  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-28 21:25:26.744  3383  3459 I jxcore-log: 
04-28 21:25:26.749  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-28 21:25:26.749  3383  3459 I jxcore-log: 
,04-28 21:25:26.765  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-28 21:25:26.765  3383  3459 I jxcore-log: 
,04-28 21:25:26.783  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-28 21:25:26.783  3383  3459 I jxcore-log: 
,04-28 21:25:26.866  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-28 21:25:26.866  3383  3459 I jxcore-log: 
,04-28 21:25:26.870  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-28 21:25:26.870  3383  3459 I jxcore-log: 
,04-28 21:25:26.895  3383  3459 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-28 21:25:26.895  3383  3459 I jxcore-log: 
,04-28 21:25:26.905  3383  3459 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
04-28 21:25:26.905  3383  3459 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
04-28 21:25:26.905  3383  3459 I jxcore-log: 
,04-28 21:25:27.366   763   831 W ProcessCpuTracker: Skipping unknown process pid 3597
,04-28 21:25:28.344   763   971 I ActivityManager: Killing 1670:com.android.defcontainer/u0a4 (adj 15): empty #17
,04-28 21:25:28.406  1736  3601 I Finsky  : [158] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(162): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-28 21:25:28.407  1736  1785 I PlayCommon: [142] com.google.android.play.a.v.a(25540): Starting to flush logs
,04-28 21:25:28.471  1630  1714 I art     : Explicit concurrent mark sweep GC freed 51841(3MB) AllocSpace objects, 50(800KB) LOS objects, 39% free, 22MB/37MB, paused 1.552ms total 60.317ms
,04-28 21:25:28.474  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:25:28.531   763  1031 I art     : Explicit concurrent mark sweep GC freed 27549(1305KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.300ms total 56.382ms
,04-28 21:25:28.683  3535  3535 D CAR.SERVICE: mConnectedToCar = false, abort
,04-28 21:25:28.683   763  1236 I ActivityManager: Killing 2928:com.quickoffice.android/u0a65 (adj 15): empty #17
,04-28 21:25:28.689  3535  3535 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@38985c63 that was originally bound here
04-28 21:25:28.689  3535  3535 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@38985c63 that was originally bound here
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-28 21:25:28.689  3535  3535 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-28 21:25:28.716  3535  3535 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1f37728c that was originally bound here
04-28 21:25:28.716  3535  3535 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1f37728c that was originally bound here
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-28 21:25:28.716  3535  3535 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-28 21:25:28.716   763  1180 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@6fdb186
,04-28 21:25:29.003  1736  1785 I PlayCommon: [142] com.google.android.play.a.v.a(25551): Log flushed by 1 successful uploads
,04-28 21:25:33.018   763   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-48
04-28 21:25:33.018   763   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-28 21:25:33.397  1538  1552 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,04-28 21:25:39.087  1736  1788 I Finsky  : [144] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,04-28 21:25:39.182  1736  1788 I Finsky  : [144] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,04-28 21:25:39.183  1736  1736 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,04-28 21:25:53.024   763   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-51
,04-28 21:25:57.012  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:25:57.015  1630  3656 I VacuumService: Vacuum at: now=1461871557015 tag=VacuumService
,04-28 21:25:58.020  1630  3664 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,04-28 21:25:58.023  1630  3664 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-28 21:25:59.413  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:25:59.414  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:26:08.579  1092  1491 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-28 21:26:08.579  1092  1491 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-28 21:26:08.633  1630  1630 I ConfigService: onCreate
,04-28 21:26:13.028   763   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
04-28 21:26:13.029   763   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-28 21:26:13.741  1630  1630 I ConfigService: onDestroy
,04-28 21:26:33.033   763   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-51
04-28 21:26:33.034   763   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-28 21:26:48.772   763   838 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
04-28 21:26:48.777   763   838 I PowerManagerService: Sleeping (uid 1000)...
,04-28 21:26:48.842   763   838 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-28 21:26:48.845   189   874 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-28 21:26:48.855   177   341 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (268 us)
,04-28 21:26:48.866   763   859 E WifiStateMachine: cancelDelayedScan -> 11
,04-28 21:26:48.871   763   859 E native  : do suspend false
,04-28 21:26:49.036  1092  1092 I Keyboard.Facilitator: onFinishInput()
04-28 21:26:49.036   189  1190 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,04-28 21:26:49.045   763   859 E WifiStateMachine: cancelDelayedScan -> 13
,04-28 21:26:49.047   763   859 E native  : do suspend true
,04-28 21:26:49.371   763   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-51
04-28 21:26:49.372   763   859 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,04-28 21:26:49.448   763   836 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,04-28 21:26:49.450   763   763 V ActivityManager: Display changed displayId=0
,04-28 21:26:49.459   177   177 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
04-28 21:26:49.460   177   177 D qdhwcomposer: hwc_blank: Blanking display: 0
,04-28 21:26:49.583   178   178 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
04-28 21:26:49.584   178   178 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
04-28 21:26:49.584   178   178 I rmt_storage: wakelock acquired: 1, error no: 2
,04-28 21:26:49.584   178   578 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236802816)
,04-28 21:26:49.689   178   578 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
04-28 21:26:49.689   178   578 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
04-28 21:26:49.689   178   578 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236802816) wakelock released: 1, error no: 0
04-28 21:26:49.689   178   578 I rmt_storage: 
,04-28 21:26:49.691   178   178 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,04-28 21:26:49.731   177   177 D qdhwcomposer: hwc_blank: Done blanking display: 0
04-28 21:26:49.731   763   883 D SurfaceControl: Excessive delay in setPowerMode(): 284ms
04-28 21:26:49.732  1939  1941 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,04-28 21:26:49.747  3383  3383 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
04-28 21:26:49.747  3383  3383 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,04-28 21:26:49.765  3383  3383 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@19dba73d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@53265b2, 16908290=android.view.AbsSavedState$1@53265b2}, android:focusedViewId=100}]}]
04-28 21:26:49.765  3383  3383 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
04-28 21:26:49.765  3383  3383 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
04-28 21:26:49.765  3383  3383 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,04-28 21:26:53.034   763   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-51
04-28 21:26:53.034   763   859 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,04-28 21:26:53.668  1630  1733 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,04-28 21:27:24.580  1736  1736 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler$CheckPreconditionsAndAutoUpdateJobService.onStartJob(142): JobScheduler invoked, loading libraries.
,04-28 21:27:24.723  1736  1736 I Finsky  : [1] com.google.android.finsky.receivers.j.a(436): Request install of com.google.android.apps.genie.geniewidget v=26701187 pri=3 for auto_update
,04-28 21:27:24.733  1736  1736 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1182): Installer kick - starting com.google.android.apps.genie.geniewidget
,04-28 21:27:24.744  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:27:24.748  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:27:24.749  1630  1630 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-28 21:27:24.772  1736  1736 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler$CheckPreconditionsAndAutoUpdateJobService.a(186): auto-updates finished successfully.
,04-28 21:27:24.797  1736  1777 I Finsky  : [134] com.google.android.finsky.installer.y.b(204): Created session 1310947995 for com.google.android.apps.genie.geniewidget
,04-28 21:27:25.028  1736  1777 I Finsky  : [134] com.google.android.finsky.installer.ah.run(127): Session for com.google.android.apps.genie.geniewidget already exists, skipping creation
,04-28 21:27:25.032  1736  1736 I Finsky  : [1] com.google.android.finsky.receivers.ah.onPostExecute(2830): Downloading gzip for com.google.android.apps.genie.geniewidget (com.google.android.apps.genie.geniewidget)
,04-28 21:27:25.033  1736  1736 I Finsky  : [1] com.google.android.finsky.download.e.a(242): Duplicate state set for 'com.google.android.apps.genie.geniewidget' (0). Already in that state
04-28 21:27:25.033  1736  1736 I Finsky  : [1] com.google.android.finsky.download.x.e(143): Download com.google.android.apps.genie.geniewidget added to DownloadQueue
,04-28 21:27:25.035  1736  1736 I Finsky  : [1] com.google.android.finsky.download.e.a(244): com.google.android.apps.genie.geniewidget from 0 to 1.
,04-28 21:27:25.037   190   190 I installd: free_cache(3356918) avail 11047628800
,04-28 21:27:25.040  1736  1736 I Finsky  : [1] com.google.android.finsky.download.ai.run(5557): Download com.google.android.apps.genie.geniewidget starting
,04-28 21:27:25.066  1736  1778 I Finsky  : [135] com.google.android.finsky.download.ae.a(1570): Enqueued com.google.android.apps.genie.geniewidget as content://downloads/my_downloads/857
04-28 21:27:25.067  1736  1736 I Finsky  : [1] com.google.android.finsky.download.e.a(244): com.google.android.apps.genie.geniewidget from 1 to 2.
04-28 21:27:25.067  1736  1736 I Finsky  : [1] com.google.android.finsky.download.x.a(635): com.google.android.apps.genie.geniewidget: onStart
,04-28 21:27:25.082  1736  1736 I Finsky  : [1] com.google.android.finsky.download.x.b(404): com.google.android.apps.genie.geniewidget: onProgress 0/-1 Status: 190.
,04-28 21:27:25.102   928  3739 D DownloadManager: [857] Starting
,04-28 21:27:25.110   928  3739 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,04-28 21:27:25.132  1736  1736 I Finsky  : [1] com.google.android.finsky.download.x.b(404): com.google.android.apps.genie.geniewidget: onProgress 0/-1 Status: 192.
,04-28 21:27:32.630   928  3739 D DownloadManager: [857] Finished with status SUCCESS
,04-28 21:27:32.703  1736  1736 I Finsky  : [1] com.google.android.finsky.download.DownloadBroadcastReceiver.a(45): Intent received at DownloadBroadcastReceiver
,04-28 21:27:32.705  1736  1736 I Finsky  : [1] com.google.android.finsky.download.x.b(404): com.google.android.apps.genie.geniewidget: onProgress 3356918/3356918 Status: 200.
,04-28 21:27:32.741  1736  1736 I Finsky  : [1] com.google.android.finsky.download.e.a(244): com.google.android.apps.genie.geniewidget from 2 to 3.
04-28 21:27:32.741  1736  1736 I Finsky  : [1] com.google.android.finsky.download.x.b(603): com.google.android.apps.genie.geniewidget: onComplete
04-28 21:27:32.742  1736  1736 I Finsky  : [1] com.google.android.finsky.download.x.i(344): Download com.google.android.apps.genie.geniewidget removed from DownloadQueue
,04-28 21:27:32.743   190   190 I installd: free_cache(0) avail 11044278272
,04-28 21:27:32.754  1736  1736 I Finsky  : [1] com.google.android.finsky.receivers.x.c(37916): Prepare to copy com.google.android.apps.genie.geniewidget (com.google.android.apps.genie.geniewidget) from content://downloads/my_downloads/857 (expect 4978691 bytes, isGzipped: true)
,04-28 21:27:32.843   763   971 I art     : Explicit concurrent mark sweep GC freed 58504(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 29MB/44MB, paused 1.451ms total 61.108ms
,04-28 21:27:32.856  1538  1538 V Herrevad: NQAS connected
,04-28 21:27:32.861   190   190 I installd: free_cache(4978691) avail 11044278272
,04-28 21:27:32.893  1630  1630 I ConfigService: onCreate
,04-28 21:27:33.074  1630  1642 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3f35b7eb)
,04-28 21:27:33.076  1630  1642 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32ab1948)
,04-28 21:27:33.077  1630  1642 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a3de3e1)
,04-28 21:27:33.078  1630  1642 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18cec506)
,04-28 21:27:33.078  1630  1642 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@38b5e7c7)
,04-28 21:27:33.079  1630  1642 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1cfc81f4)
,04-28 21:27:33.113  1736  1793 I Finsky  : [147] com.google.android.finsky.receivers.aa.a(2970): com.google.android.apps.genie.geniewidget (com.google.android.apps.genie.geniewidget) (4978691 bytes) copied successfully in 251 ms
,04-28 21:27:33.246  1736  1736 I Finsky  : [1] com.google.android.finsky.receivers.aa.onPostExecute(4051): Successfully copied APK to update com.google.android.apps.genie.geniewidget (com.google.android.apps.genie.geniewidget)
04-28 21:27:33.247  1736  1736 I Finsky  : [1] com.google.android.finsky.receivers.x.c(41092): Begin install of com.google.android.apps.genie.geniewidget
,04-28 21:27:33.748   763   842 I ActivityManager: Start proc 3770:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,04-28 21:27:33.819  1736  1736 I Finsky  : [1] com.google.android.vending.verifier.PackageVerificationReceiver.onReceive(2101): Skipping verification because own installation
,04-28 21:27:33.820   763   842 D PackageManager: /data/app/vmdl1310947995.tmp already staged; skipping copy
,04-28 21:27:33.824  1736  1736 I Finsky  : [1] com.google.android.vending.verifier.PackageVerificationReceiver.onReceive(40): Verification requested, id = 0
,04-28 21:27:34.276   763   842 D PackageManager: Renaming /data/app/vmdl1310947995.tmp to /data/app/com.google.android.apps.genie.geniewidget-1
,04-28 21:27:34.278   763   831 I ActivityManager: Force stopping com.google.android.apps.genie.geniewidget appid=10040 user=-1: replace sys pkg
,04-28 21:27:34.283   763   842 W PackageManager: Trying to update system app code path from /data/app/com.google.android.apps.genie.geniewidget-2 to /data/app/com.google.android.apps.genie.geniewidget-1
,04-28 21:27:34.304   763   842 I PackageManager: Running dexopt on: /data/app/com.google.android.apps.genie.geniewidget-1/base.apk pkg=com.google.android.apps.genie.geniewidget isa=arm vmSafeMode=false
,04-28 21:27:34.336  3788  3788 I dex2oat : /system/bin/dex2oat --zip-fd=6 --zip-location=/data/app/com.google.android.apps.genie.geniewidget-1/base.apk --oat-fd=7 --oat-location=/data/dalvik-cache/arm/data@app@com.google.android.apps.genie.geniewidget-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m --swap-fd=8
,04-28 21:27:34.488  3788  3788 I dex2oat : Decided to run without swap.
,04-28 21:27:37.967  1630  1630 I ConfigService: onDestroy
,04-28 21:27:38.006  3788  3788 I dex2oat : dex2oat took 3.669s (threads: 4) arena alloc=566KB java alloc=6MB native alloc=9MB free=6MB
,04-28 21:27:38.012   763   842 W PackageManager: Code path for pkg : com.google.android.apps.genie.geniewidget changing from /data/app/com.google.android.apps.genie.geniewidget-2 to /data/app/com.google.android.apps.genie.geniewidget-1
04-28 21:27:38.012   763   831 I ActivityManager: Force stopping com.google.android.apps.genie.geniewidget appid=10040 user=-1: update pkg
04-28 21:27:38.013   763   842 W PackageManager: Resource path for pkg : com.google.android.apps.genie.geniewidget changing from /data/app/com.google.android.apps.genie.geniewidget-2 to /data/app/com.google.android.apps.genie.geniewidget-1
,04-28 21:27:38.041   763   842 W PackageSettings: Skipping PackageSetting{22385131 com.example.hello/10116} due to missing metadata
,04-28 21:27:38.110   763   842 W PackageSettings: Skipping PackageSetting{22385131 com.example.hello/10116} due to missing metadata
04-28 21:27:38.135   763   842 I ActivityManager: Force stopping com.google.android.apps.genie.geniewidget appid=10040 user=0: pkg removed
,04-28 21:27:38.163   763   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-28 21:27:38.166   763  1189 I ActivityManager: Killing 3040:com.google.android.apps.magazines/u0a56 (adj 15): empty #17
,04-28 21:27:38.182  1215  1215 I art     : Explicit concurrent mark sweep GC freed 1911(116KB) AllocSpace objects, 6(531KB) LOS objects, 23% free, 25MB/33MB, paused 542us total 42.332ms
,04-28 21:27:38.191   763   778 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@281817e2)
04-28 21:27:38.191   763   861 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-28 21:27:38.191   763   861 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-28 21:27:38.229   763   763 I art     : Explicit concurrent mark sweep GC freed 228986(9MB) AllocSpace objects, 41(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.973ms total 86.994ms
,04-28 21:27:38.229   763   763 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-28 21:27:38.229   763   763 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.apps.genie.geniewidget flg=0x4000010 (has extras) }
,04-28 21:27:38.402   763  1189 I ActivityManager: Start proc 3850:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,04-28 21:27:38.415   200   200 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 203us total 12.832ms
,04-28 21:27:38.426   200   200 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 198us total 10.118ms
,04-28 21:27:38.435   763   842 W Settings: Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,04-28 21:27:38.442   200   200 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 4.866ms total 15.504ms
,04-28 21:27:38.450   763   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-28 21:27:38.453   763   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-28 21:27:38.483   763  1189 I ActivityManager: Start proc 3872:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,04-28 21:27:38.495   763  1031 I ActivityManager: Killing 3185:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
,04-28 21:27:38.508   763   763 W ResourcesManager: Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,04-28 21:27:38.541   763   763 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.google.android.apps.genie.geniewidget flg=0x4000010 (has extras) }
04-28 21:27:38.542   763   763 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,04-28 21:27:38.572   763   842 I art     : Explicit concurrent mark sweep GC freed 17017(706KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 29MB/44MB, paused 8.582ms total 133.289ms
,04-28 21:27:38.574  3872  3872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-28 21:27:38.602  1736  1736 I Finsky  : [1] com.google.android.finsky.receivers.aj.a(2112): Successful install of com.google.android.apps.genie.geniewidget
,04-28 21:27:38.603  1538  3893 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.apps.genie.geniewidget
,04-28 21:27:38.606  1630  1630 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-28 21:27:38.606  1630  1630 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-28 21:27:38.628  1538  3893 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.apps.genie.geniewidget
,04-28 21:27:38.651  1538  3897 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,04-28 21:27:38.651  1538  3897 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,04-28 21:27:38.653  1538  3897 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.google.android.apps.genie.geniewidget.
,04-28 21:27:38.653  1538  3897 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,04-28 21:27:38.663  1538  3897 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
04-28 21:27:38.664  1538  3897 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
04-28 21:27:38.664  1538  3897 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,04-28 21:27:38.667   763  1189 I ActivityManager: Start proc 3898:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,04-28 21:27:38.669  1736  1736 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(271): Wear auto install disabled for package com.google.android.apps.genie.geniewidget
,04-28 21:27:38.674  1538  3897 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
04-28 21:27:38.674  1538  3897 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,04-28 21:27:38.677  1538  3897 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,04-28 21:27:38.677  1538  3897 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,04-28 21:27:38.677  1538  3897 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
04-28 21:27:38.678  1538  3897 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,04-28 21:27:38.729  1215  1433 W ResourceType: No package identifier when getting value for resource number 0x00000000
04-28 21:27:38.729  1215  1433 W PackageManager: Failure retrieving resources for com.google.android.apps.genie.geniewidget: Resource ID #0x0
,04-28 21:27:38.843  1215  1433 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-28 21:27:38.868  3898  3917 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
04-28 21:27:38.868  3898  3917 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
04-28 21:27:38.868  3898  3917 I GAv4    :   adb logcat -s GAv4
,04-28 21:27:38.878  3898  3917 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,04-28 21:27:38.887  3898  3917 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,04-28 21:27:38.891  3898  3922 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,04-28 21:27:39.183   763   778 I ActivityManager: Killing 3206:com.google.android.deskclock/u0a33 (adj 15): empty #17
,04-28 21:27:39.301   763  1031 I ActivityManager: Start proc 3938:com.quickoffice.android/u0a65 for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver
,04-28 21:27:39.363  3938  3938 W Quickoffice: Cleanup of storage: done
,04-28 21:27:39.365  3938  3957 D com.google.android.apps.docs.quickoffice.X: Loading recent documents list
,04-28 21:27:39.369  3938  3958 D Quickoffice: The number of lines present in  /proc/mount 21
,04-28 21:27:39.370  3938  3958 D Quickoffice: Parsing the storagedefinition.xml.
,04-28 21:27:39.383  3938  3958 D Quickoffice: # of Storagedefinitions - 35
04-28 21:27:39.383  3938  3958 D Quickoffice: The # of storage definitions available - 35
04-28 21:27:39.383  3938  3958 D Quickoffice: Processing mountline rootfs / rootfs ro,seclabel,relatime 0 0
,04-28 21:27:39.383  3938  3958 D Quickoffice: Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
,04-28 21:27:39.383  3938  3958 D Quickoffice: Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
04-28 21:27:39.383  3938  3958 D Quickoffice: Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
04-28 21:27:39.384  3938  3958 D Quickoffice: Processing mountline proc /proc proc rw,relatime 0 0
04-28 21:27:39.384  3938  3958 D Quickoffice: Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
,04-28 21:27:39.384  3938  3958 D Quickoffice: Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
04-28 21:27:39.384  3938  3958 D Quickoffice: Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
04-28 21:27:39.385  3938  3958 D Quickoffice: Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
,04-28 21:27:39.385  3938  3958 D Quickoffice: Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
04-28 21:27:39.385  3938  3958 D Quickoffice: Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
,04-28 21:27:39.386  3938  3958 D Quickoffice: Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
04-28 21:27:39.386  3938  3958 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,relatime,data=ordered 0 0
,04-28 21:27:39.386  3938  3958 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
04-28 21:27:39.387  3938  3958 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
,04-28 21:27:39.387  3938  3958 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
,04-28 21:27:39.388  3938  3958 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,context=u:object_r:firmware_file:s0,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
04-28 21:27:39.388  3938  3958 D Quickoffice: Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,noexec,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,04-28 21:27:39.388  3938  3958 D Quickoffice: Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
,04-28 21:27:39.389  3938  3958 D Quickoffice: Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,noexec,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
04-28 21:27:39.389  3938  3958 D Quickoffice: Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,noexec,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,04-28 21:27:39.390  3938  3958 D Quickoffice: Build properties are not configured for this storage definition.
,04-28 21:27:39.390  3938  3958 D Quickoffice: Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,noexec,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
,04-28 21:27:39.393  3938  3958 D Quickoffice: The # of mounts identified -  1
,04-28 21:27:39.398   763   779 I ActivityManager: Killing 2692:com.google.android.keep/u0a52 (adj 15): empty #17
,04-28 21:27:39.399  3938  3960 D com.google.android.apps.docs.quickoffice.X: Checking validity of 0 items
,04-28 21:27:39.425  3938  3959 W Quickoffice: Could not load clipboard.
,04-28 21:27:39.442   763   778 W ActivityManager: No permission grants found for com.quickoffice.android
,04-28 21:27:39.443  3938  3960 D ContentResolverUtil: There are 0 persisted uri permissions.
04-28 21:27:39.443  3938  3960 D com.google.android.apps.docs.quickoffice.X: 0 items were valid
,04-28 21:27:39.450  3938  3961 W Quickoffice: Could not store clipboard.
,04-28 21:27:39.473   763  1236 I ActivityManager: Start proc 3962:com.google.android.partnersetup/u0a11 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
,04-28 21:27:39.555  1538  3893 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.apps.genie.geniewidget
,04-28 21:27:39.562  1538  3893 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.apps.genie.geniewidget
,04-28 21:27:39.579   763  1189 I ActivityManager: Killing 2285:com.google.android.gm/u0a41 (adj 15): empty #17
,04-28 21:27:39.606  1538  1538 D AsyncTaskServiceImpl: Submit a task: k
,04-28 21:27:39.620  1538  3996 D k       : Processing package: com.google.android.apps.genie.geniewidget
,04-28 21:27:39.626  1538  3996 D b       : Look up (com.google.android.apps.genie.geniewidget:26701187) returned no result
,04-28 21:27:39.627  1538  3996 D k       : Starting Hash for package com.google.android.apps.genie.geniewidget:2.6.7 (120857206)
,04-28 21:27:39.631  1630  2526 D GCM     : GcmService start Intent { act=com.google.android.gms.gcm.PACKAGE_REPLACED cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gms.gcm.PACKAGE_REPLACED
,04-28 21:27:39.653  1215  1215 E ReflectionReceiver: Unrecognized event: android.intent.action.PACKAGE_ADDED
,04-28 21:27:39.654  1443  4001 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.apps.genie.geniewidget, CONTACTS=MAYBE
,04-28 21:27:39.692   763  1183 I ActivityManager: Start proc 4003:com.google.android.apps.magazines/u0a56 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver
,04-28 21:27:39.720  1538  3996 D k       : Package com.google.android.apps.genie.geniewidget's hash: fd07b3719caa72c848a2b800bc6a4dff14a94890c71779f425b73f438e63f72c
,04-28 21:27:39.723  1538  3996 D b       : Look up (com.google.android.apps.genie.geniewidget:26701187) returned no result
,04-28 21:27:39.727  1443  4001 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 71 ms] updated apps [took 71 ms] 
,04-28 21:27:39.738  1538  3996 D k       : Saved the app info in cache for package:com.google.android.apps.genie.geniewidget.
,04-28 21:27:39.921  4003  4003 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
,04-28 21:27:39.933  4003  4003 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 7321-7322)
04-28 21:27:39.933  4003  4003 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,04-28 21:27:39.938  4003  4003 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {38985c63}
,04-28 21:27:39.938  4003  4003 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-28 21:27:39.939  4003  4003 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,04-28 21:27:39.953  4003  4003 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,04-28 21:27:39.967  4003  4003 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-28 21:27:40.013  4003  4063 W cr_media: Requires BLUETOOTH permission
,04-28 21:27:40.027  4003  4003 I NSApplication: Starting up...
,04-28 21:27:40.034   763   779 I ActivityManager: Killing 3129:com.google.android.apps.photos/u0a83 (adj 15): empty #17
,04-28 21:27:40.140  1538  3893 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.apps.genie.geniewidget
,04-28 21:27:40.185   763  1234 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-28 21:27:40.186   763   861 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-28 21:27:40.186   763   861 D ConnectivityService: apparently satisfied.  currentScore=60
,04-28 21:27:40.188  4003  4080 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-28 21:27:40.193  1538  1538 D AsyncTaskServiceImpl: Submit a task: k
,04-28 21:27:40.202  1538  3996 D k       : Processing package: com.google.android.apps.genie.geniewidget
,04-28 21:27:40.215  1538  3996 D GassUtils: Found app info for package com.google.android.apps.genie.geniewidget:26701187. Hash: fd07b3719caa72c848a2b800bc6a4dff14a94890c71779f425b73f438e63f72c
04-28 21:27:40.215  1538  3996 D k       : Found info for package com.google.android.apps.genie.geniewidget in db.
,04-28 21:27:40.233  1630  1630 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-28 21:27:40.233  1630  1630 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-28 21:27:40.251   763  1189 I ActivityManager: Start proc 4087:com.google.android.apps.cloudprint/u0a32 for broadcast com.google.android.apps.cloudprint/.printdialog.receivers.UpgradeBroadcastReceiver
,04-28 21:27:40.399   763  1189 I ActivityManager: Killing 2962:com.google.android.setupwizard/u0a16 (adj 15): empty #17
,04-28 21:27:40.707  1538  1619 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,04-28 21:27:40.766  1538  1619 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,04-28 21:27:40.767  1538  1619 I Icing   : Indexing CC99D49BDF7A31CC93C41E542898B6DE53E184A6 from com.google.android.googlequicksearchbox
,04-28 21:27:40.799  1538  1619 I Icing   : Indexing done CC99D49BDF7A31CC93C41E542898B6DE53E184A6
,04-28 21:27:41.287  1538  1619 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,04-28 21:27:41.299  1538  1619 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,04-28 21:27:42.734  3383  3459 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-28 21:27:42.734  3383  3459 I jxcore-log: 
,04-28 21:27:43.045  4140  4140 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-28 21:27:43.048  4140  4140 D AndroidRuntime: CheckJNI is OFF
,04-28 21:27:43.154  4140  4140 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-28 21:27:43.162   763   831 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
04-28 21:27:43.162   763   831 I ActivityManager: Killing 3383:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,04-28 21:27:43.213   763   842 W PackageSettings: Skipping PackageSetting{22385131 com.example.hello/10116} due to missing metadata
,04-28 21:27:43.215   763  1180 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@27294dd4)
04-28 21:27:43.215   763   860 D WifiService: Client connection lost with reason: 4
04-28 21:27:43.216   763   861 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-28 21:27:43.216   763   861 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-28 21:27:43.216   763  1234 I WindowState: WIN DEATH: Window{1b342aa8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,04-28 21:27:43.371   763   831 I ActivityManager:   Force finishing activity 3 ActivityRecord{392b4156 u0 com.test.thalitest/.MainActivity t19}
,04-28 21:27:43.374   763  1180 W ActivityManager: Spurious death for ProcessRecord{844eb7d 3383:com.test.thalitest/u0a49}, curProc for 3383: null
04-28 21:27:43.374   763   842 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,04-28 21:27:43.375   763   842 I ActivityManager:   Force finishing activity 3 ActivityRecord{392b4156 u0 com.test.thalitest/.MainActivity t19 f}
04-28 21:27:43.375   763   842 W ActivityManager: Duplicate finish request for ActivityRecord{392b4156 u0 com.test.thalitest/.MainActivity t19 f}
,04-28 21:27:43.393  1630  1699 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,04-28 21:27:43.394   763   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-28 21:27:43.396   763   885 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
04-28 21:27:43.396   763   885 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,04-28 21:27:43.417   763   763 W ResourcesManager: Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,04-28 21:27:43.421   763   763 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-28 21:27:43.421   763   763 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,04-28 21:27:43.431  1092  1092 I Keyboard.Facilitator: resetDictionaries() : en_US
,04-28 21:27:43.438  1368  4161 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,04-28 21:27:43.448   906   906 I art     : Explicit concurrent mark sweep GC freed 49080(2MB) AllocSpace objects, 0(0B) LOS objects, 27% free, 41MB/57MB, paused 953us total 57.502ms
,04-28 21:27:43.449  3872  3872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-28 21:27:43.465  1092  4175 I Keyboard.Facilitator.DecoderInitializer: run()
,04-28 21:27:43.473  1092  4175 I Decoder : createOrResetDecoder
,04-28 21:27:43.491  1630  1630 I ConfigService: onCreate
,04-28 21:27:43.499  1443  1443 I art     : Explicit concurrent mark sweep GC freed 8539(612KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 22MB/30MB, paused 516us total 118.829ms
,04-28 21:27:43.515  1538  1538 I art     : Explicit concurrent mark sweep GC freed 27673(1683KB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 23MB/31MB, paused 657us total 137.206ms
,04-28 21:27:43.516  1538  3893 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-28 21:27:43.516  1538  3893 D AccountUtils: Clearing selected account for com.test.thalitest
,04-28 21:27:43.528  1092  4175 I Keyboard.Facilitator.MainLanguageModelLoader: run()
04-28 21:27:43.528  1538  1552 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@28e6b366)
,04-28 21:27:43.538  1538  3893 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,04-28 21:27:43.547  1630  1630 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-28 21:27:43.547  1630  1630 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-28 21:27:43.551  1736  1736 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(274): Wear auto uninstall disabled for package com.test.thalitest
,04-28 21:27:43.569  1215  1433 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-28 21:27:43.572  1092  4175 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,04-28 21:27:43.575  1092  4175 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
04-28 21:27:43.575  1092  4175 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,04-28 21:27:43.579  1092  4175 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
04-28 21:27:43.579  1092  4175 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
04-28 21:27:43.581  1092  4175 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
04-28 21:27:43.581  1092  4175 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,04-28 21:27:43.583  1092  4175 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-28 21:27:43.583  1092  4175 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-28 21:27:43.583  1092  4175 I Keyboard.Facilitator.Delight2FileSweeper: run()
,04-28 21:27:43.583  1092  4175 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-28 21:27:43.583  1092  4175 I StatsUtilsManager: startPeriodStatsRecorder() : Success
04-28 21:27:43.583  1092  4175 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,04-28 21:27:43.586  1443  4185 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,04-28 21:27:43.622   763   763 I ActivityManager: Start proc 4187:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,04-28 21:27:43.623   763   842 I art     : Explicit concurrent mark sweep GC freed 37576(3MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 29MB/44MB, paused 1.863ms total 168.644ms
,04-28 21:27:43.631  1538  4183 W BaseAppContext: Using Auth Proxy for data requests.
,04-28 21:27:43.634  1538  4183 W BaseAppContext: Using Auth Proxy for data requests.
,04-28 21:27:43.674  4140  4140 I art     : System.exit called, status: 0
04-28 21:27:43.674  4140  4140 I AndroidRuntime: VM exiting with result code 0.
,04-28 21:27:43.681  1538  3893 I GMPM-SVC: App measurement is starting up, version: 8703
,04-28 21:27:43.681  1538  3893 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,04-28 21:27:43.688  1538  3893 I GMPM-SVC: AppMeasurement disabled with google_app_measurement_enable=0
,04-28 21:27:43.707  1443  4185 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 120 ms] updated apps [took 120 ms] 
,04-28 21:27:43.710  1538  3893 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,04-28 21:27:43.711  1538  1619 I Icing   : doRemovePackageData com.test.thalitest
,04-28 21:27:43.721   763   778 D ConnectivityService: listenForNetwork for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-28 21:27:43.721   763   861 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-28 21:27:43.721   763   861 D ConnectivityService: apparently satisfied.  currentScore=60
,04-28 21:27:43.723  1538  4218 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-28 21:27:43.730   763  1180 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3383 uid 10049
,04-28 21:27:43.738  1092  1092 I Keyboard.Facilitator: onFinishInput()
,04-28 21:27:43.739  1538  4219 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
04-28 21:27:43.739  1538  4219 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
04-28 21:27:43.740  1538  4219 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
04-28 21:27:43.740  1538  4219 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,04-28 21:27:43.744  1538  4219 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
04-28 21:27:43.744  1538  4219 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,04-28 21:27:43.744  1538  4219 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,04-28 21:27:43.757  1215  1215 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-28 21:27:43.804   763  1189 I ActivityManager: Start proc 4223:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,04-28 21:27:43.810  1538  4219 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
04-28 21:27:43.811  1538  4219 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,04-28 21:27:43.812  1538  4219 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,04-28 21:27:43.813  1538  4219 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
04-28 21:27:43.813  1538  4219 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,04-28 21:27:43.814  1538  4219 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,04-28 21:27:43.826   763  1180 I ActivityManager: Killing 2588:com.google.android.calendar/u0a28 (adj 15): empty #17
,04-28 21:27:43.839  4223  4223 D ExternalStorage: After updating volumes, found 1 active roots
,04-28 21:27:43.907  1538  4211 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:1775)
,04-28 21:27:43.909  1538  1919 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,04-28 21:27:43.914   763  1031 I ActivityManager: Killing 3005:com.google.android.talk/u0a51 (adj 15): empty #17
,04-28 21:27:43.957   928  2096 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10049)] disk I/O error
,--------- beginning of crash
04-28 21:27:43.959   928  2096 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
04-28 21:27:43.959   928  2096 E AndroidRuntime: Process: android.process.media, PID: 928
04-28 21:27:43.959   928  2096 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1175)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
04-28 21:27:43.959   928  2096 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,04-28 21:27:43.967   928  2096 I Process : Sending signal. PID: 928 SIG: 9
,04-28 21:27:43.968   763  4247 E DropBoxManagerService: Can't write: system_app_crash
04-28 21:27:43.968   763  4247 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
04-28 21:27:43.968   763  4247 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-28 21:27:43.968   763  4247 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-28 21:27:43.968   763  4247 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-28 21:27:43.968   763  4247 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-28 21:27:43.968   763  4247 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-28 21:27:43.968   763  4247 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-28 21:27:43.968   763  4247 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-28 21:27:43.968   763  4247 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-28 21:27:43.968   763  4247 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-28 21:27:43.968   763  4247 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-28 21:27:43.968   763  4247 E DropBoxManagerService: 	... 5 more
,04-28 21:27:43.971   174   174 E lowmemorykiller: Error writing /proc/928/oom_score_adj; errno=22
,04-28 21:27:43.991   763  1031 I ActivityManager: Process android.process.media (pid 928) has died
,04-28 21:27:43.991   763  1031 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 1000ms

```
