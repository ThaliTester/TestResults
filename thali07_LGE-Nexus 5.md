#### Test 639808779d5bfaa_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
,03-29 11:05:11.745  1549  2529 I CheckinService: Done disabling old GoogleServicesFramework version
03-29 11:05:12.031  3428  3428 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-29 11:05:12.034  3428  3428 D AndroidRuntime: CheckJNI is OFF
03-29 11:05:12.143  3428  3428 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-29 11:05:12.146   765   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-29 11:05:12.153   765   940 V WindowManager: addAppToken: AppWindowToken{69491f2 token=Token{2af060fd ActivityRecord{232b2954 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-29 11:05:12.158   765   838 V WindowManager: Adding window Window{7ffb2b5 u0 Starting com.test.thalitest} at 2 of 7 (after Window{1ea774b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-29 11:05:12.162  3428  3428 D AndroidRuntime: Shutting down VM
03-29 11:05:12.164  1383  1399 W SearchService: Abort, client detached.
03-29 11:05:12.200   765  1251 I ActivityManager: Start proc 3449:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-29 11:05:12.244  1383  1383 I MicroDetector: Keeping mic open: false
03-29 11:05:12.244  1383  1596 I DeviceStateChecker: DeviceStateChecker cancelled
03-29 11:05:12.249  1383  1383 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@37cea9ab
03-29 11:05:12.303   191  1601 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-29 11:05:12.303   191  1601 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-29 11:05:12.309  1383  1597 I MicroRecognitionRunner: Detection finished
03-29 11:05:12.310  1383  1595 I MicroRecognitionRunner: Stopping hotword detection.
03-29 11:05:12.328  3449  3449 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
03-29 11:05:12.341  3449  3449 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 480-482)
03-29 11:05:12.341  3449  3449 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-29 11:05:12.353  3449  3449 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d5ebf7f}
03-29 11:05:12.353  3449  3449 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-29 11:05:12.354  3449  3449 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
03-29 11:05:12.362  3449  3449 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,03-29 11:05:12.383  3449  3449 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
03-29 11:05:12.388   765   780 I ActivityManager: Killing 2984:com.android.settings/1000 (adj 15): empty #17
,03-29 11:05:12.397   765   869 D WifiService: Client connection lost with reason: 4
,03-29 11:05:12.424   765   837 D BluetoothManagerService: Message: 20
03-29 11:05:12.424   765   837 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32915ba2:true
,03-29 11:05:12.446  3449  3449 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-29 11:05:12.446  3449  3449 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-29 11:05:12.487  3449  3449 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-29 11:05:12.487  3449  3449 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-29 11:05:12.500  3449  3449 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-29 11:05:12.501  3449  3449 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 11:05:12.505   765   780 I art     : Explicit concurrent mark sweep GC freed 24296(1189KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.289ms total 61.763ms
,03-29 11:05:12.510  3449  3449 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
03-29 11:05:12.511  3449  3449 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
03-29 11:05:12.511  3449  3449 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,03-29 11:05:12.513  3449  3449 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-29 11:05:12.519  3449  3449 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,03-29 11:05:12.524  3449  3449 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-29 11:05:12.529  3449  3449 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 11:05:12.529  3449  3449 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 11:05:12.546  3449  3507 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-29 11:05:12.551  3449  3449 D Atlas   : Validating map...
,03-29 11:05:12.556   765  1149 V WindowManager: Adding window Window{298dbc9b u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{7ffb2b5 u0 Starting com.test.thalitest})
,03-29 11:05:12.562   765   869 D WifiService: New client listening to asynchronous messages
,03-29 11:05:12.571   765  1256 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-29 11:05:12.571   765   870 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-29 11:05:12.571   765   870 D ConnectivityService: apparently satisfied.  currentScore=60
03-29 11:05:12.572  3449  3511 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-29 11:05:12.591  3449  3507 I OpenGLRenderer: Initialized EGL, version 1.4
03-29 11:05:12.594  3449  3507 D OpenGLRenderer: Enabling debug mode 0
,03-29 11:05:12.626  3449  3449 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-29 11:05:12.646  3449  3514 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-29 11:05:12.739   177   177 D SurfaceFlinger: shader cache generated - 24 shaders in 149.409164 ms
,03-29 11:05:12.760  1098  1098 I Keyboard.Facilitator: onFinishInput()
,03-29 11:05:12.832  3449  3449 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-29 11:05:12.833  3449  3449 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3449
,03-29 11:05:12.853   765   838 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +688ms
,03-29 11:05:13.012  3449  3449 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-29 11:05:13.178  3449  3525 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362819328
,03-29 11:05:13.182  3449  3525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-29 11:05:13.182  3449  3525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-29 11:05:13.182  3449  3525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-29 11:05:13.182  3449  3525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-29 11:05:13.182  3449  3525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-29 11:05:13.182  3449  3525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@200bd2ae added. We now have 1 listener(s)
,03-29 11:05:13.182   765  1148 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 11:05:13.185  3449  3525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,03-29 11:05:13.187  3449  3525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-29 11:05:13.187  3449  3525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-29 11:05:13.188  3449  3525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-29 11:05:13.191  3449  3525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0de4e5 added. We now have 1 listener(s)
03-29 11:05:13.191  3449  3525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-29 11:05:13.194  3449  3525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-29 11:05:13.196  3449  3525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-29 11:05:13.196  3449  3525 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-29 11:05:13.199  3449  3525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-29 11:05:13.199   765   781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 11:05:13.200  3449  3525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-29 11:05:13.208  3449  3525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 11:05:13.208  3449  3525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 11:05:13.208  3449  3525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-29 11:05:13.208  3449  3525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 11:05:13.208  3449  3525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 11:05:13.208  3449  3525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 11:05:13.208  3449  3525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 11:05:13.208  3449  3525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-29 11:05:13.208  3449  3525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-29 11:05:13.208  3449  3525 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-29 11:05:13.211  3449  3449 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-29 11:05:13.212  3449  3449 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-29 11:05:13.213  3449  3525 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-29 11:05:13.239  3449  3449 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-29 11:05:13.870  3449  3463 I art     : Background sticky concurrent mark sweep GC freed 73730(5MB) AllocSpace objects, 16(1520KB) LOS objects, 17% free, 22MB/26MB, paused 2.327ms total 110.780ms
,03-29 11:05:13.907  3449  3526 W jxcore-log: Initializing JXcore engine
03-29 11:05:13.907  3449  3526 W jxcore-log: JXcore engine is ready
,03-29 11:05:13.952  3526  3526 W Thread-347: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9409]" dev="sockfs" ino=9409 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-29 11:05:13.952  3526  3526 W Thread-347: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-29 11:05:13.952  3526  3526 W Thread-347: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8115]" dev="sockfs" ino=8115 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-29 11:05:13.952  3526  3526 W Thread-347: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[17607]" dev="sockfs" ino=17607 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-29 11:05:13.968  3449  3526 W jxcore-log: Starting JXcore engine
,03-29 11:05:14.050  3449  3526 W jxcore-log: Platform android
03-29 11:05:14.050  3449  3526 W jxcore-log: 
03-29 11:05:14.050  3449  3526 W jxcore-log: Process ARCH arm
03-29 11:05:14.050  3449  3526 W jxcore-log: 
,03-29 11:05:14.241  3449  3526 I jxcore-log: JXcore Cordova bridge is ready!
03-29 11:05:14.241  3449  3526 I jxcore-log: 
,03-29 11:05:14.242  3449  3526 W jxcore-log: JXcore engine is started
,03-29 11:05:14.250  3449  3525 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-29 11:05:14.251  3449  3449 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-29 11:05:15.532  3232  3260 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-29 11:05:15.533  3232  3258 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-29 11:05:15.536   765   781 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-29 11:05:15.541   765   780 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-29 11:05:15.544  3232  3232 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-29 11:05:15.544  3232  3232 W Babel   : BAM#gBA: invalid account id: -1
03-29 11:05:15.544  3232  3232 W Babel   : BAM#gBA: invalid account id: -1
03-29 11:05:15.544  3232  3232 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-29 11:05:15.546   765  1148 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-29 11:05:15.549   765  1189 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-29 11:05:15.563  3232  3268 W Babel   : aye TOOK TOO LONG! (15037ms > 10000ms)
,03-29 11:05:15.717  1674  1735 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
03-29 11:05:15.717  1674  1674 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-29 11:05:17.405  1549  1560 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-29 11:05:23.147   765   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-51
03-29 11:05:23.147   765   868 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
,03-29 11:05:23.268  3449  3526 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 11:05:23.268  3449  3526 I jxcore-log: 
,03-29 11:05:23.270  3449  3526 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 11:05:23.270  3449  3526 I jxcore-log: 
,03-29 11:05:23.273  3449  3526 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 11:05:23.273  3449  3526 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 11:05:23.273  3449  3526 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-29 11:05:23.273  3449  3526 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 11:05:23.273  3449  3526 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 11:05:23.273  3449  3526 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 11:05:23.273  3449  3526 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 11:05:23.273  3449  3526 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 11:05:23.275  3449  3526 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 11:05:23.276  3449  3526 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 11:05:23.276  3449  3526 I jxcore-log: 
03-29 11:05:23.278  3449  3526 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 11:05:23.278  3449  3526 I jxcore-log: 
,03-29 11:05:23.769  3449  3526 I jxcore-log: Unit Test app is loaded
03-29 11:05:23.769  3449  3526 I jxcore-log: 
,03-29 11:05:23.772  3449  3526 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 11:05:23.772  3449  3526 I jxcore-log: 
,03-29 11:05:23.778  3449  3526 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
03-29 11:05:23.780  3449  3449 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-29 11:05:23.780  3449  3526 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-29 11:05:23.780  3449  3526 I jxcore-log: 
03-29 11:05:23.783  3449  3526 I jxcore-log: logCallback not set !!!!
03-29 11:05:23.783  3449  3526 I jxcore-log: 
03-29 11:05:23.785  3449  3526 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-29 11:05:23.785  3449  3526 I jxcore-log:   bluetooth: 'on',
03-29 11:05:23.785  3449  3526 I jxcore-log:   wifi: 'on',
03-29 11:05:23.785  3449  3526 I jxcore-log:   cellular: 'doNotCare',
03-29 11:05:23.785  3449  3526 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-29 11:05:23.785  3449  3526 I jxcore-log: 
03-29 11:05:23.786  3449  3526 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-29 11:05:23.786  3449  3526 I jxcore-log: 
,03-29 11:05:23.944  1674  1674 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-29 11:05:23.960  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:05:23.964  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-29 11:05:23.965  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:05:24.040  3606  3606 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-29 11:05:24.043  3606  3606 D AndroidRuntime: CheckJNI is OFF
,03-29 11:05:24.131  3606  3606 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-29 11:05:24.136   765   833 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
,03-29 11:05:24.137   765   833 I ActivityManager: Killing 3449:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-29 11:05:24.167   765  1149 I WindowState: WIN DEATH: Window{298dbc9b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-29 11:05:24.168   765   780 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@165c7a62)
03-29 11:05:24.168   765   869 D WifiService: Client connection lost with reason: 4
03-29 11:05:24.169   765   870 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-29 11:05:24.170   765   870 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-29 11:05:24.200   765   844 W PackageSettings: Skipping PackageSetting{2de8e436 com.example.hello/10116} due to missing metadata
,03-29 11:05:24.347   765   833 W ActivityManager: Force removing ActivityRecord{232b2954 u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-29 11:05:24.352   765  1256 W ActivityManager: Spurious death for ProcessRecord{3c7627f3 3449:com.test.thalitest/u0a49}, curProc for 3449: null
,03-29 11:05:24.353   765   844 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-29 11:05:24.413   909   909 I art     : Explicit concurrent mark sweep GC freed 39486(1633KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 58MB/74MB, paused 1.046ms total 31.789ms
,03-29 11:05:24.430  1549  1549 I art     : Explicit concurrent mark sweep GC freed 3218(129KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 23MB/30MB, paused 420us total 68.946ms,
,03-29 11:05:24.449   765   887 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-29 11:05:24.453   765   852 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-29 11:05:24.454  1507  1630 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-29 11:05:24.455  1098  1098 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-29 11:05:24.474  1098  3628 I Keyboard.Facilitator.DecoderInitializer: run()
,03-29 11:05:24.494  1383  1383 I art     : Explicit concurrent mark sweep GC freed 2863(265KB) AllocSpace objects, 7(154KB) LOS objects, 25% free, 22MB/30MB, paused 594us total 124.175ms
,03-29 11:05:24.496   765   765 I art     : Explicit concurrent mark sweep GC freed 22816(1371KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 9.952ms total 121.161ms
,03-29 11:05:24.497   765   844 I art     : WaitForGcToComplete blocked for 32.621ms for cause Explicit
,03-29 11:05:24.502  1312  3635 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-29 11:05:24.511  1098  3628 I Decoder : createOrResetDecoder
,03-29 11:05:24.515  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:05:24.543  1098  3628 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-29 11:05:24.558   765  1256 I ActivityManager: Start proc 3640:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-29 11:05:24.565  1098  3628 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-29 11:05:24.568  1098  3628 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-29 11:05:24.568  1098  3628 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-29 11:05:24.570  1098  3628 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-29 11:05:24.570  1098  3628 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-29 11:05:24.571  1098  3628 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-29 11:05:24.571  1098  3628 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-29 11:05:24.573  1098  3628 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-29 11:05:24.573  1098  3628 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,03-29 11:05:24.573  1098  3628 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-29 11:05:24.573  1098  3628 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-29 11:05:24.573  1098  3628 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-29 11:05:24.573  1098  3628 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-29 11:05:24.587   765   765 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-29 11:05:24.587   765   765 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-29 11:05:24.597  3640  3640 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-29 11:05:24.601   765  1148 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3449 uid 10049
,03-29 11:05:24.604  1098  1098 I Keyboard.Facilitator: onFinishInput()
,03-29 11:05:24.613  1549  3661 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-29 11:05:24.613  1549  3661 D AccountUtils: Clearing selected account for com.test.thalitest
,03-29 11:05:24.628  1507  1507 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-29 11:05:24.628  1507  1507 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-29 11:05:24.631  1383  1383 W LocationOracle: Best location was null
03-29 11:05:24.631  1383  1383 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-29 11:05:24.644  1252  1252 I art     : Explicit concurrent mark sweep GC freed 2818(162KB) AllocSpace objects, 7(612KB) LOS objects, 38% free, 25MB/41MB, paused 1.279ms total 27.435ms
,03-29 11:05:24.647  1383  3665 I MicroRecognitionRunner: Starting detection.
,03-29 11:05:24.648  1383  3667 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@25a887c5
,03-29 11:05:24.655   191  3669 I AudioFlinger: AudioFlinger's thread 0xb4424000 ready to run
,03-29 11:05:24.661  1383  3667 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@25a887c5
,03-29 11:05:24.670   191  3669 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-29 11:05:24.670   191  3669 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-29 11:05:24.671   191  3669 D         : Failed to fetch the lookup information of the device 0000003E 
03-29 11:05:24.671   191  3669 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-29 11:05:24.671   191  3669 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
03-29 11:05:24.671  1549  3661 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-29 11:05:24.677   191  3669 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-29 11:05:24.700  1507  1604 W GCoreFlp: No location to return for getLastLocation()
,03-29 11:05:24.704  1507  1604 W GCoreFlp: No location to return for getLastLocation()
,03-29 11:05:24.708  1507  1604 W GCoreFlp: No location to return for getLastLocation()
,03-29 11:05:24.710  1383  3674 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-29 11:05:24.721  1549  3671 W BaseAppContext: Using Auth Proxy for data requests.
,03-29 11:05:24.739  1507  1604 W GCoreFlp: No location to return for getLastLocation()
,03-29 11:05:24.744   765   844 I art     : Explicit concurrent mark sweep GC freed 16684(1435KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 2.631ms total 245.037ms
,03-29 11:05:24.752   765   765 I ActivityManager: Start proc 3678:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,03-29 11:05:24.764  1383  1383 I MicroDetectionWorker: onReady
,03-29 11:05:24.769  1549  3661 I GMPM-SVC: App measurement is starting up, version: 8703
03-29 11:05:24.769  1549  3661 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-29 11:05:24.771  1549  3671 W BaseAppContext: Using Auth Proxy for data requests.
03-29 11:05:24.771   202   202 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 943us total 17.243ms
,03-29 11:05:24.773  1507  1604 W GCoreFlp: No location to return for getLastLocation()
,03-29 11:05:24.787   202   202 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 203us total 13.676ms
,03-29 11:05:24.791  1507  1604 W GCoreFlp: No location to return for getLastLocation()
,03-29 11:05:24.799   202   202 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 195us total 11.310ms
,03-29 11:05:24.813  1383  3674 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 103 ms] updated apps [took 103 ms] 
03-29 11:05:24.813  1549  1629 I Icing   : doRemovePackageData com.test.thalitest
,03-29 11:05:24.814  1549  3661 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-29 11:05:24.829   765  1256 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-29 11:05:24.830   765   870 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-29 11:05:24.830   765   870 D ConnectivityService: apparently satisfied.  currentScore=60
,03-29 11:05:24.830  1549  3704 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-29 11:05:24.833  1549  3694 E SQLiteLog: (539) recovered 3 pages from /data/data/com.google.android.gms/databases/DocList.db-journal
,03-29 11:05:24.845  1549  3703 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-29 11:05:24.845  1549  3703 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,03-29 11:05:24.846  1549  3703 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-29 11:05:24.846  1549  3703 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-29 11:05:24.848  1674  1721 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-29 11:05:24.848  1674  1721 I qtaguid : Untagging socket 37 failed errno=-22
03-29 11:05:24.848  1674  1721 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-29 11:05:24.857  1252  1486 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-29 11:05:24.861  1549  3703 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-29 11:05:24.861  1549  3703 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,03-29 11:05:24.861  1549  3703 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-29 11:05:24.868  1674  1674 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-29 11:05:24.879  1549  3703 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-29 11:05:24.879  1549  3703 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-29 11:05:24.881  1549  3703 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,03-29 11:05:24.883  1549  3703 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,03-29 11:05:24.883  1549  3703 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-29 11:05:24.884  1549  3703 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-29 11:05:24.925  3606  3606 I art     : System.exit called, status: 0
03-29 11:05:24.925  3606  3606 I AndroidRuntime: VM exiting with result code 0.
,03-29 11:05:24.936   765  1189 I ActivityManager: Start proc 3709:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-29 11:05:24.939  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 11:05:24.968   765   844 I ActivityManager: Start proc 3727:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-29 11:05:25.001   765  1149 I ActivityManager: Start proc 3745:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-29 11:05:25.018   765   780 I ActivityManager: Killing 2603:com.google.android.keep/u0a52 (adj 15): empty #17
,03-29 11:05:25.032  3709  3709 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-29 11:05:25.032  3709  3709 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 11:05:25.057  3709  3709 I MultiDex: VM with version 2.1.0 has multidex support
03-29 11:05:25.057  3709  3709 I MultiDex: install
,03-29 11:05:25.057  3709  3709 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-29 11:05:25.069  1549  3670 W DriveInitializer: Awaiting to be initialized
,03-29 11:05:25.070  1549  3768 W DriveInitializer: Background init thread started
,03-29 11:05:25.075   765   780 I ActivityManager: Killing 2759:com.android.providers.calendar/u0a1 (adj 15): empty #17
,03-29 11:05:25.090  3745  3745 D ExternalStorage: After updating volumes, found 1 active roots
,03-29 11:05:25.096  1549  3768 E DocListDatabase: Failed to delete from ContentFileDeletionLock163 table
03-29 11:05:25.096  1549  3768 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-29 11:05:25.096  1549  3768 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-29 11:05:25.096  1549  3768 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-29 11:05:25.096  1549  3768 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-29 11:05:25.096  1549  3768 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-29 11:05:25.096  1549  3768 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-29 11:05:25.096  1549  3768 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-29 11:05:25.096  1549  3768 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-29 11:05:25.096  1549  3768 E DocListDatabase: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
,03-29 11:05:25.096  1549  3768 W DriveInitializer: Background init thread ended
03-29 11:05:25.096  1549  3670 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-29 11:05:25.097  1549  3670 E DriveAsyncService: disk I/O error (code 3850)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(:com.google.android.gms:486)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(:com.google.android.gms:461)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(:com.google.android.gms:1519)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(:com.google.android.gms:16)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-29 11:05:25.097  1549  3670 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-29 11:05:25.107   928  2173 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10049)] disk I/O error
--------- beginning of crash
03-29 11:05:25.108   928  2173 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
03-29 11:05:25.108   928  2173 E AndroidRuntime: Process: android.process.media, PID: 928
03-29 11:05:25.108   928  2173 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1175)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-29 11:05:25.108   928  2173 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: Can't write: system_app_crash
03-29 11:05:25.120   765  3772 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 11:05:25.120   765  3772 E DropBoxManagerService: 	... 5 more
03-29 11:05:25.130  1252  1575 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-29 11:05:25.130  1252  1575 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-29 11:05:25.136   765  3774 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-29 11:05:25.137   765   833 D Atlas   : Validating map...
03-29 11:05:25.144  1549  3768 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-29 11:05:25.144  1549  3768 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-29 11:05:25.144  1549  3768 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-29 11:05:25.144  1549  3768 I GCore-Chimera-Crash: ==
03-29 11:05:25.144  1549  3768 I GCore-Chimera-Crash: GCore-Chimera-Crash
03-29 11:05:25.144  1549  3768 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-29 11:05:25.144  1549  3768 E AndroidRuntime: Process: com.google.android.gms, PID: 1549
03-29 11:05:25.144  1549  3768 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-29 11:05:25.144  1549  3768 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-29 11:05:25.144  1549  3768 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-29 11:05:25.144  1549  3768 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-29 11:05:25.144  1549  3768 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-29 11:05:25.144  1549  3768 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-29 11:05:25.144  1549  3768 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-29 11:05:25.144  1549  3768 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-29 11:05:25.144  1549  3768 E AndroidRuntime: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: Can't write: system_app_crash
03-29 11:05:25.147   765  3775 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-29 11:05:25.147   765  3775 E DropBoxManagerService: 	... 5 more
03-29 11:05:25.156  3709  3709 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
03-29 11:05:25.167  1383  1383 E LocationReceiver: Received bad location: null
,03-29 11:05:25.178   765  3774 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-29 11:05:25.178   765  3774 I OpenGLRenderer: Initialized EGL, version 1.4
03-29 11:05:25.182   765  3774 D OpenGLRenderer: Enabling debug mode 0
,03-29 11:05:25.192   177   177 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-29 11:05:25.192   177   177 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-29 11:05:25.193   177   177 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-29 11:05:25.193   177   177 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-29 11:05:25.193   177   177 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-29 11:05:25.193   177   177 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-29 11:05:25.193   177   177 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-29 11:05:25.193   177   177 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-29 11:05:25.193   177   177 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-29 11:05:25.193   177   177 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-29 11:05:25.193   177   177 E qdoverlay: Ctrl commit failed set overlay
03-29 11:05:25.193   177   177 E qdhwcomposer: configureLowRes: commit failed for low res panel
03-29 11:05:25.193   177   177 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-29 11:05:25.193   177   177 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-29 11:05:25.193   177   177 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
03-29 11:05:25.193   177   177 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
03-29 11:05:25.193   177   177 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-29 11:05:25.193   177   177 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-29 11:05:25.193   177   177 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
03-29 11:05:25.193   177   177 E qdoverlay: src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
03-29 11:05:25.193   177   177 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=75
03-29 11:05:25.193   177   177 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=75
03-29 11:05:25.193   177   177 E qdoverlay: Ctrl commit failed set overlay
03-29 11:05:25.193   177   177 E qdhwcomposer: configure: commit fails
03-29 11:05:25.193   177   177 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-29 11:05:25.193   177   177 E qdoverlay: MdpCtrl close error in unset
,03-29 11:05:25.195   765   833 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-29 11:05:25.195   765   833 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 11:05:25.205  3709  3709 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-29 11:05:25.214  3709  3709 D ChimeraCfgMgr: Reading stored module config
,03-29 11:05:25.271   765  1251 I ActivityManager: Start proc 3781:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,03-29 11:05:25.398  1674  1720 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-29 11:05:25.398  1674  1720 I qtaguid : Untagging socket 37 failed errno=-22
03-29 11:05:25.398  1674  1720 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-29 11:05:25.468   177   177 E qdoverlay: GenericPipe failed to close ctrl
03-29 11:05:25.468   177   177 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,03-29 11:05:25.468   177   177 E qdoverlay: MdpCtrl close error in unset
03-29 11:05:25.469   177   177 E qdoverlay: GenericPipe failed to close ctrl
03-29 11:05:25.469   177   177 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-29 11:05:25.469   177   177 E qdoverlay: MdpCtrl close error in unset
03-29 11:05:25.469   177   177 E qdoverlay: GenericPipe failed to close ctrl
03-29 11:05:25.469   177   177 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-29 11:05:25.469   177   177 E qdoverlay: MdpCtrl close error in unset
03-29 11:05:25.469   177   177 E qdoverlay: GenericPipe failed to close ctrl
,03-29 11:05:25.473   177   177 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-29 11:05:25.473   177   177 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=13 dpy=0 numHwLayers=5
03-29 11:05:25.473   177   177 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-29 11:05:25.473   177   177 E qdhwcomposer: hwc_set_primary: display commit fail!

```
