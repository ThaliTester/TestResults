#### Test 648099369ce4518_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-31 18:04:05.763  1564  2563 I CheckinService: Done disabling old GoogleServicesFramework version
,03-31 18:04:06.052  3457  3457 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 18:04:06.054  3457  3457 D AndroidRuntime: CheckJNI is OFF
03-31 18:04:06.150  3457  3457 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-31 18:04:06.153   765  1199 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 18:04:06.160   765  1199 V WindowManager: addAppToken: AppWindowToken{19cfbee7 token=Token{169b04a6 ActivityRecord{24dade01 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-31 18:04:06.165   765   835 V WindowManager: Adding window Window{3d74027e u0 Starting com.test.thalitest} at 2 of 7 (after Window{1f83b9c6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 18:04:06.168  3457  3457 D AndroidRuntime: Shutting down VM
03-31 18:04:06.179  1394  1409 W SearchService: Abort, client detached.
03-31 18:04:06.211   765  1036 I ActivityManager: Start proc 3478:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-31 18:04:06.261  1394  1561 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
03-31 18:04:06.267  1394  1584 I DeviceStateChecker: DeviceStateChecker cancelled
03-31 18:04:06.272  1394  1394 I MicroDetector: Keeping mic open: false
03-31 18:04:06.272  1394  1394 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@35e06158
03-31 18:04:06.310  3478  3478 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
03-31 18:04:06.316   188  1591 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 18:04:06.317   188  1591 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 18:04:06.324  3478  3478 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 9933-9935)
03-31 18:04:06.324  3478  3478 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 18:04:06.333  3478  3478 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3932ad30}
03-31 18:04:06.333  3478  3478 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 18:04:06.333  3478  3478 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 18:04:06.344  3478  3478 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
03-31 18:04:06.359  1394  1588 I MicroRecognitionRunner: Detection finished
03-31 18:04:06.360  3478  3478 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
03-31 18:04:06.360  1394  1583 I MicroRecognitionRunner: Stopping hotword detection.
,03-31 18:04:06.420   765   834 D BluetoothManagerService: Message: 20
03-31 18:04:06.420   765   834 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d0b45c:true
,03-31 18:04:06.428  3478  3478 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-31 18:04:06.429  3478  3478 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-31 18:04:06.466  3478  3478 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-31 18:04:06.466  3478  3478 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-31 18:04:06.479  3478  3478 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-31 18:04:06.485  3478  3478 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 18:04:06.486  3478  3478 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-31 18:04:06.495  3478  3478 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-31 18:04:06.516  3478  3537 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 18:04:06.521  3478  3478 D Atlas   : Validating map...
,03-31 18:04:06.526   765  1348 V WindowManager: Adding window Window{394136db u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3d74027e u0 Starting com.test.thalitest})
,03-31 18:04:06.533   765   858 D WifiService: New client listening to asynchronous messages
,03-31 18:04:06.541   765  1010 D ConnectivityService: listenForNetwork for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 18:04:06.542   765   859 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 18:04:06.542   765   859 D ConnectivityService: apparently satisfied.  currentScore=60
,03-31 18:04:06.543  3478  3539 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 18:04:06.546   765  1203 I ActivityManager: Killing 1998:com.google.android.apps.fitness/u0a82 (adj 15): empty #17
,03-31 18:04:06.732   175   175 D SurfaceFlinger: shader cache generated - 24 shaders in 160.096100 ms
,03-31 18:04:06.774  3478  3537 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 18:04:06.777  3478  3537 D OpenGLRenderer: Enabling debug mode 0
,03-31 18:04:06.829   765   835 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +642ms
,03-31 18:04:06.830  1103  1103 I Keyboard.Facilitator: onFinishInput()
,03-31 18:04:06.837  3478  3550 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-31 18:04:06.873  3478  3478 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3478
,03-31 18:04:06.972  3478  3478 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 18:04:07.146  3478  3556 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1262934784
,03-31 18:04:07.148  3478  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 18:04:07.148  3478  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 18:04:07.148  3478  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 18:04:07.148  3478  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 18:04:07.148  3478  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-31 18:04:07.148  3478  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f1ff0c0 added. We now have 1 listener(s)
03-31 18:04:07.148   765  1277 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:04:07.152  3478  3556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
03-31 18:04:07.153  3478  3556 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-31 18:04:07.154  3478  3556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 18:04:07.154  3478  3556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 18:04:07.162  3478  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b265f9f added. We now have 1 listener(s)
03-31 18:04:07.162  3478  3556 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 18:04:07.167  3478  3556 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-31 18:04:07.170  3478  3556 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-31 18:04:07.170  3478  3556 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-31 18:04:07.173  3478  3556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 18:04:07.173   765   781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 18:04:07.174  3478  3556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-31 18:04:07.178  3478  3556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:04:07.178  3478  3556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:04:07.178  3478  3556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 18:04:07.178  3478  3556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:04:07.178  3478  3556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:04:07.178  3478  3556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:04:07.178  3478  3556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:04:07.178  3478  3556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 18:04:07.179  3478  3556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 18:04:07.179  3478  3556 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 18:04:07.180  3478  3556 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 18:04:07.180  3478  3478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-31 18:04:07.182  3478  3478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 18:04:07.211  3478  3478 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 18:04:08.003  3478  3564 W jxcore-log: Initializing JXcore engine
03-31 18:04:08.003  3478  3564 W jxcore-log: JXcore engine is ready
,03-31 18:04:08.048  3564  3564 W Thread-353: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[6933]" dev="sockfs" ino=6933 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-31 18:04:08.048  3564  3564 W Thread-353: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-31 18:04:08.048  3564  3564 W Thread-353: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8596]" dev="sockfs" ino=8596 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-31 18:04:08.048  3564  3564 W Thread-353: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[15243]" dev="sockfs" ino=15243 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-31 18:04:08.078  3478  3564 W jxcore-log: Starting JXcore engine
,03-31 18:04:08.171  3478  3564 W jxcore-log: Platform android
03-31 18:04:08.171  3478  3564 W jxcore-log: 
03-31 18:04:08.171  3478  3564 W jxcore-log: Process ARCH arm
03-31 18:04:08.171  3478  3564 W jxcore-log: 
,03-31 18:04:08.446  3478  3564 I jxcore-log: JXcore Cordova bridge is ready!
03-31 18:04:08.446  3478  3564 I jxcore-log: 
,03-31 18:04:08.446  3478  3564 W jxcore-log: JXcore engine is started
,03-31 18:04:08.451  3478  3556 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 18:04:08.453  3478  3478 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 18:04:09.285  3252  3278 W Babel   : aye TOOK TOO LONG! (15007ms > 10000ms)
,03-31 18:04:09.286  3252  3276 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-31 18:04:09.289   765  1010 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 18:04:09.293   765  1277 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 18:04:09.296  3252  3252 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-31 18:04:09.296  3252  3252 W Babel   : BAM#gBA: invalid account id: -1
03-31 18:04:09.296  3252  3252 W Babel   : BAM#gBA: invalid account id: -1
,03-31 18:04:09.297  3252  3252 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-31 18:04:09.299   765   782 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 18:04:09.301   765  3360 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 18:04:09.389  3252  3286 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-31 18:04:09.430  1647  1725 I Finsky  : [136] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-31 18:04:09.431  1647  1647 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 18:04:11.424  1564  1576 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-31 18:04:15.547   765  1203 I ActivityManager: Killing 3071:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-31 18:04:15.650   765  1203 I ActivityManager: Killing 2988:com.android.settings/1000 (adj 15): empty #18
,03-31 18:04:15.663   765   858 D WifiService: Client connection lost with reason: 4
,03-31 18:04:17.146   765   857 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-46
03-31 18:04:17.146   765   857 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 18:04:17.320  1647  1647 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-31 18:04:17.429   765  1203 I art     : Explicit concurrent mark sweep GC freed 32418(1580KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.558ms total 79.125ms
,03-31 18:04:17.431  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:04:17.437  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:04:17.438  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:04:17.960  3478  3564 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 18:04:17.960  3478  3564 I jxcore-log: 
03-31 18:04:17.963  3478  3564 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 18:04:17.963  3478  3564 I jxcore-log: 
,03-31 18:04:17.966  3478  3564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 18:04:17.966  3478  3564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 18:04:17.966  3478  3564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 18:04:17.966  3478  3564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 18:04:17.966  3478  3564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 18:04:17.966  3478  3564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 18:04:17.966  3478  3564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 18:04:17.966  3478  3564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 18:04:17.968  3478  3564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-31 18:04:17.969  3478  3564 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 18:04:17.969  3478  3564 I jxcore-log: 
03-31 18:04:17.971  3478  3564 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 18:04:17.971  3478  3564 I jxcore-log: 
,03-31 18:04:18.107  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:04:18.217  1647  1691 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-31 18:04:18.217  1647  1691 I qtaguid : Untagging socket 37 failed errno=-22
03-31 18:04:18.217  1647  1691 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-31 18:04:18.221  1647  1647 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-31 18:04:18.266  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:04:18.317   765  1199 I ActivityManager: Start proc 3636:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-31 18:04:18.333   200   200 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 3.699ms total 15.176ms
,03-31 18:04:18.360   200   200 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 194us total 19.057ms
,03-31 18:04:18.387   200   200 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 875us total 19.528ms
,03-31 18:04:18.389  3636  3636 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 18:04:18.389  3636  3636 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 18:04:18.412  3636  3636 I MultiDex: VM with version 2.1.0 has multidex support
03-31 18:04:18.412  3636  3636 I MultiDex: install
03-31 18:04:18.412  3636  3636 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 18:04:18.425  3636  3636 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-31 18:04:18.456  3636  3636 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 18:04:18.465  3636  3636 D ChimeraCfgMgr: Reading stored module config
,03-31 18:04:18.471  1531  1531 D WearableService: callingUid 10007, callindPid: 1531
,03-31 18:04:18.475  1531  2066 E MDM     : [174] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-31 18:04:18.480  1531  1531 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 18:04:18.480  1564  3670 D LocationInitializer: Restart initialization of location
,03-31 18:04:18.491  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:04:18.503  3478  3564 I jxcore-log: Unit Test app is loaded
03-31 18:04:18.503  3478  3564 I jxcore-log: 
,03-31 18:04:18.508  1531  1614 W GCoreFlp: No location to return for getLastLocation()
03-31 18:04:18.508  1531  3671 W FusedLocationProvider: location=null
03-31 18:04:18.509  3478  3564 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 18:04:18.509  3478  3564 I jxcore-log: 
,03-31 18:04:18.511  3478  3478 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 18:04:18.515  3478  3564 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,03-31 18:04:18.517  3478  3564 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-31 18:04:18.517  3478  3564 I jxcore-log: 
,03-31 18:04:18.523  3478  3478 I chromium: [INFO:CONSOLE(86)] "logCallback Device did not have required hardware capabilities!", source: file:///android_asset/www/js/thali_main.js (86)
,03-31 18:04:18.525  3478  3564 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-31 18:04:18.525  3478  3564 I jxcore-log:   bluetooth: 'on',
03-31 18:04:18.525  3478  3564 I jxcore-log:   wifi: 'on',
03-31 18:04:18.525  3478  3564 I jxcore-log:   cellular: 'doNotCare',
03-31 18:04:18.525  3478  3564 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-31 18:04:18.525  3478  3564 I jxcore-log: 
03-31 18:04:18.525  3478  3564 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-31 18:04:18.525  3478  3564 I jxcore-log: 
,03-31 18:04:18.574  3636  3669 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-31 18:04:18.585  3636  3636 D CAR.SERVICE: Connecting to CarCallService...
,03-31 18:04:18.590  1647  1692 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-31 18:04:18.590  1647  1692 I qtaguid : Untagging socket 37 failed errno=-22
03-31 18:04:18.590  1647  1692 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-31 18:04:18.594  3636  3636 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 18:04:18.594  3636  3636 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 18:04:18.599  3636  3636 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-31 18:04:18.606  3636  3636 D CAR.TEL.Service: Creating a new CarCallService.
03-31 18:04:18.607  3636  3636 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-31 18:04:18.608   765  1277 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-31 18:04:18.609  3636  3636 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@1fc88b69
,03-31 18:04:18.609   765   781 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-31 18:04:18.609  3636  3636 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-31 18:04:18.609  3636  3636 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-31 18:04:18.676  3636  3660 D CAR.SERVICE: Package validated; name: com.android.vending
,03-31 18:04:18.743  3679  3679 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 18:04:18.745  3679  3679 D AndroidRuntime: CheckJNI is OFF
,03-31 18:04:18.831  3679  3679 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 18:04:18.839   765   830 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-31 18:04:18.839   765   830 I ActivityManager: Killing 3478:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-31 18:04:18.872   765  1348 I WindowState: WIN DEATH: Window{394136db u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-31 18:04:18.872   765  1199 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@f3a1205)
03-31 18:04:18.873   765   859 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 18:04:18.873   765   859 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 18:04:18.873   765   858 D WifiService: Client connection lost with reason: 4
,03-31 18:04:18.887   765   841 W PackageSettings: Skipping PackageSetting{24240b08 com.example.hello/10116} due to missing metadata
,03-31 18:04:19.049   765   830 W ActivityManager: Force removing ActivityRecord{24dade01 u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-31 18:04:19.054   765   781 W ActivityManager: Spurious death for ProcessRecord{2215625a 3478:com.test.thalitest/u0a49}, curProc for 3478: null
,03-31 18:04:19.056   765   841 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-31 18:04:19.095  1394  1394 I art     : Explicit concurrent mark sweep GC freed 4969(362KB) AllocSpace objects, 7(154KB) LOS objects, 24% free, 21MB/29MB, paused 461us total 36.092ms
,03-31 18:04:19.096  1564  1564 I art     : Explicit concurrent mark sweep GC freed 4181(179KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 23MB/38MB, paused 930us total 37.657ms
03-31 18:04:19.101  1531  1631 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-31 18:04:19.102   765   883 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-31 18:04:19.103  1103  1103 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-31 18:04:19.105  1103  3700 I Keyboard.Facilitator.DecoderInitializer: run()
,03-31 18:04:19.107   905   905 I art     : Explicit concurrent mark sweep GC freed 39538(1636KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 1.084ms total 29.392ms
,03-31 18:04:19.114  1103  3700 I Decoder : createOrResetDecoder
,03-31 18:04:19.124   765   849 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 18:04:19.127  1360  3701 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-31 18:04:19.174   765  1010 I ActivityManager: Start proc 3709:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-31 18:04:19.176  1103  3700 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-31 18:04:19.201  1103  3700 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-31 18:04:19.202  1103  3700 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 18:04:19.202  1103  3700 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-31 18:04:19.204  1103  3700 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-31 18:04:19.204  1103  3700 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-31 18:04:19.205  1103  3700 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 18:04:19.205  1103  3700 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-31 18:04:19.210  1103  3700 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 18:04:19.210  1103  3700 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 18:04:19.210  1103  3700 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-31 18:04:19.210   765  3360 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3478 uid 10049
,03-31 18:04:19.216  3709  3709 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
03-31 18:04:19.216  1103  1103 I Keyboard.Facilitator: onFinishInput()
03-31 18:04:19.216   765   765 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 18:04:19.216  1103  3700 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 18:04:19.216   765   765 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-31 18:04:19.216  1103  3700 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 18:04:19.222  1103  3700 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-31 18:04:19.238  1564  3730 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-31 18:04:19.238  1564  3730 D AccountUtils: Clearing selected account for com.test.thalitest
,03-31 18:04:19.253  1564  3730 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
03-31 18:04:19.253  1531  1531 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-31 18:04:19.253  1531  1531 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-31 18:04:19.261  1280  1280 I art     : Explicit concurrent mark sweep GC freed 3001(165KB) AllocSpace objects, 6(531KB) LOS objects, 38% free, 25MB/41MB, paused 1.210ms total 30.234ms
,03-31 18:04:19.288  1394  1394 W LocationOracle: Best location was null
,03-31 18:04:19.288  1394  1394 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-31 18:04:19.306  1394  3741 I MicroRecognitionRunner: Starting detection.
03-31 18:04:19.307  1394  3742 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@1ea87eb8
,03-31 18:04:19.312   188  3744 I AudioFlinger: AudioFlinger's thread 0xb447d000 ready to run
,03-31 18:04:19.316  1564  3735 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 18:04:19.325  1564  3730 I GMPM-SVC: App measurement is starting up, version: 8703
03-31 18:04:19.326  1564  3730 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-31 18:04:19.327  1564  3735 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 18:04:19.330  1394  3742 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@1ea87eb8
,03-31 18:04:19.340   188  3744 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-31 18:04:19.340   188  3744 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-31 18:04:19.340   188  3744 D         : Failed to fetch the lookup information of the device 0000003E 
03-31 18:04:19.340   188  3744 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-31 18:04:19.340   188  3744 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-31 18:04:19.347   188  3744 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-31 18:04:19.347  1531  1614 W GCoreFlp: No location to return for getLastLocation()
,03-31 18:04:19.355  1394  3746 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-31 18:04:19.355  1531  1614 W GCoreFlp: No location to return for getLastLocation()
,03-31 18:04:19.363  1531  1614 W GCoreFlp: No location to return for getLastLocation()
,03-31 18:04:19.388   765   841 I art     : Explicit concurrent mark sweep GC freed 31691(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.811ms total 198.402ms
,03-31 18:04:19.394   765   765 I ActivityManager: Start proc 3750:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,03-31 18:04:19.410  1531  1614 W GCoreFlp: No location to return for getLastLocation()
,03-31 18:04:19.415  1564  1615 I Icing   : doRemovePackageData com.test.thalitest
,03-31 18:04:19.422  1564  3730 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-31 18:04:19.433  1394  1394 I MicroDetectionWorker: onReady
,03-31 18:04:19.445  1531  1614 W GCoreFlp: No location to return for getLastLocation()
,03-31 18:04:19.455   765  1036 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 18:04:19.455   765   859 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 18:04:19.455   765   859 D ConnectivityService: apparently satisfied.  currentScore=60
,03-31 18:04:19.456  1564  3777 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 18:04:19.462  1531  1614 W GCoreFlp: No location to return for getLastLocation()
,03-31 18:04:19.475  1564  3776 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-31 18:04:19.475  1564  3776 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-31 18:04:19.476  1564  3776 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-31 18:04:19.476  1564  3776 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
03-31 18:04:19.476  1280  1453 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-31 18:04:19.480  1564  3776 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-31 18:04:19.480  1564  3776 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-31 18:04:19.481  1564  3776 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-31 18:04:19.485  1564  3776 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-31 18:04:19.485  1564  3776 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-31 18:04:19.488  1564  3776 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
03-31 18:04:19.488  1564  3776 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,03-31 18:04:19.489  1564  3776 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-31 18:04:19.489  1564  3776 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-31 18:04:19.501  1394  3746 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 146 ms] updated apps [took 146 ms] 
,03-31 18:04:19.548  3679  3679 I art     : System.exit called, status: 0
03-31 18:04:19.548  3679  3679 I AndroidRuntime: VM exiting with result code 0.
,03-31 18:04:19.577   765  1348 I ActivityManager: Start proc 3783:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-31 18:04:19.599   765   841 I ActivityManager: Start proc 3801:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-31 18:04:19.612  1531  1531 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 18:04:19.621   765  1203 I ActivityManager: Killing 3225:com.android.providers.calendar/u0a1 (adj 15): empty #17
,03-31 18:04:19.667  3783  3783 D ExternalStorage: After updating volumes, found 1 active roots
,03-31 18:04:19.678  1394  1394 E LocationReceiver: Received bad location: null
,03-31 18:04:19.683  1564  3734 W DriveInitializer: Awaiting to be initialized
,03-31 18:04:19.684   765   781 I ActivityManager: Killing 3317:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
03-31 18:04:19.684  1564  3824 W DriveInitializer: Background init thread started
,03-31 18:04:19.729  1564  3824 E DocListDatabase: Failed to delete from ContentFileDeletionLock163 table
03-31 18:04:19.729  1564  3824 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-31 18:04:19.729  1564  3824 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 18:04:19.729  1564  3824 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 18:04:19.729  1564  3824 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 18:04:19.729  1564  3824 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 18:04:19.729  1564  3824 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 18:04:19.729  1564  3824 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-31 18:04:19.729  1564  3824 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-31 18:04:19.729  1564  3824 E DocListDatabase: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-31 18:04:19.729  1564  3824 W DriveInitializer: Background init thread ended
03-31 18:04:19.730  1564  3734 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-31 18:04:19.730  1564  3734 E DriveAsyncService: disk I/O error (code 3850)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(:com.google.android.gms:486)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(:com.google.android.gms:461)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(:com.google.android.gms:1519)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(:com.google.android.gms:16)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-31 18:04:19.730  1564  3734 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-31 18:04:19.733  1280  1498 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-31 18:04:19.733  1280  1498 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-31 18:04:19.734  1564  3824 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-31 18:04:19.734  1564  3824 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-31 18:04:19.734  1564  3824 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-31 18:04:19.734  1564  3824 I GCore-Chimera-Crash: ==
03-31 18:04:19.734  1564  3824 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
03-31 18:04:19.734  1564  3824 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-31 18:04:19.734  1564  3824 E AndroidRuntime: Process: com.google.android.gms, PID: 1564
03-31 18:04:19.734  1564  3824 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-31 18:04:19.734  1564  3824 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 18:04:19.734  1564  3824 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 18:04:19.734  1564  3824 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 18:04:19.734  1564  3824 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 18:04:19.734  1564  3824 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 18:04:19.734  1564  3824 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-31 18:04:19.734  1564  3824 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-31 18:04:19.734  1564  3824 E AndroidRuntime: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: Can't write: system_app_crash
03-31 18:04:19.739   765  3825 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 18:04:19.739   765  3825 E DropBoxManagerService: 	... 5 more
03-31 18:04:19.743   765   830 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 18:04:19.743   765   830 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-31 18:04:19.758   765  3826 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-31 18:04:19.758   765   830 D Atlas   : Validating map...
,03-31 18:04:19.784   765  3826 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
03-31 18:04:19.785   765  3826 I OpenGLRenderer: Initialized EGL, version 1.4
03-31 18:04:19.788   765  3826 D OpenGLRenderer: Enabling debug mode 0
03-31 18:04:19.799  3750  3779 D Documents: Update found 7 roots in 277ms
,03-31 18:04:19.981  1647  1691 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
,03-31 18:04:19.981  1647  1691 I qtaguid : Untagging socket 37 failed errno=-22
03-31 18:04:19.981  1647  1691 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22

```
