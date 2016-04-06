#### Test 6539483973f7970_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
04-06 03:10:16.947  1556  2420 I CheckinService: Done disabling old GoogleServicesFramework version
,04-06 03:10:17.482  3578  3578 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-06 03:10:17.485  3578  3578 D AndroidRuntime: CheckJNI is OFF
04-06 03:10:17.591  3578  3578 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
04-06 03:10:17.595   763  1129 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-06 03:10:17.601   763  1129 V WindowManager: addAppToken: AppWindowToken{f9d62a2 token=Token{22c466d ActivityRecord{375a7e84 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
04-06 03:10:17.606   763   836 V WindowManager: Adding window Window{1544d625 u0 Starting com.test.thalitest} at 2 of 7 (after Window{162a0d9f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-06 03:10:17.611  3578  3578 D AndroidRuntime: Shutting down VM
04-06 03:10:17.612  1423  1439 W SearchService: Abort, client detached.
04-06 03:10:17.644   763  1279 I ActivityManager: Start proc 3599:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
04-06 03:10:17.686  1423  1591 I DeviceStateChecker: DeviceStateChecker cancelled
04-06 03:10:17.691  1423  1423 I MicroDetector: Keeping mic open: false
04-06 03:10:17.691  1423  1423 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@10d6370e
04-06 03:10:17.693  1423  1584 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
04-06 03:10:17.748   188  1597 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-06 03:10:17.748   188  1597 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-06 03:10:17.753  1423  1594 I MicroRecognitionRunner: Detection finished
04-06 03:10:17.753  1423  1590 I MicroRecognitionRunner: Stopping hotword detection.
04-06 03:10:17.755  3599  3599 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
04-06 03:10:17.777  3599  3599 I cr_LibraryLoader: Time to load native libraries: 9 ms (timestamps 9661-9670)
04-06 03:10:17.777  3599  3599 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-06 03:10:17.790  3599  3599 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {228889ef}
04-06 03:10:17.790  3599  3599 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-06 03:10:17.790  3599  3599 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
04-06 03:10:17.808   763   779 I ActivityManager: Killing 3099:com.android.providers.calendar/u0a1 (adj 15): empty #17
,04-06 03:10:17.887  3599  3599 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,04-06 03:10:17.910  3599  3599 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-06 03:10:17.973   763   835 D BluetoothManagerService: Message: 20
,04-06 03:10:17.973   763   835 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@231fd79b:true
,04-06 03:10:17.976  3599  3599 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
04-06 03:10:17.976  3599  3599 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,04-06 03:10:18.016  3599  3599 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-06 03:10:18.016  3599  3599 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,04-06 03:10:18.029  3599  3599 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,04-06 03:10:18.036  3599  3599 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-06 03:10:18.037  3599  3599 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,04-06 03:10:18.046  3599  3599 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,04-06 03:10:18.085  3599  3660 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-06 03:10:18.094  3599  3599 D Atlas   : Validating map...
04-06 03:10:18.103   763  1330 V WindowManager: Adding window Window{2c46df26 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1544d625 u0 Starting com.test.thalitest})
04-06 03:10:18.112   763   869 D WifiService: New client listening to asynchronous messages
,04-06 03:10:18.127   763   778 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-06 03:10:18.128   763   870 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-06 03:10:18.128   763   870 D ConnectivityService: apparently satisfied.  currentScore=60
,04-06 03:10:18.128  3599  3663 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-06 03:10:18.166  3599  3660 I OpenGLRenderer: Initialized EGL, version 1.4
,04-06 03:10:18.171  3599  3660 D OpenGLRenderer: Enabling debug mode 0
,04-06 03:10:18.234   763   836 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +622ms
,04-06 03:10:18.238  1108  1108 I Keyboard.Facilitator: onFinishInput()
,04-06 03:10:18.266  3599  3666 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,04-06 03:10:18.313  3599  3599 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3599
,04-06 03:10:18.507  3599  3599 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-06 03:10:18.609  3599  3673 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362819968
,04-06 03:10:18.617  3599  3673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-06 03:10:18.617  3599  3673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-06 03:10:18.617  3599  3673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-06 03:10:18.617  3599  3673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-06 03:10:18.617  3599  3673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-06 03:10:18.617  3599  3673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@393b26bf added. We now have 1 listener(s)
,04-06 03:10:18.619   763  1129 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-06 03:10:18.621  3599  3673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,04-06 03:10:18.625  3599  3673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,04-06 03:10:18.626  3599  3673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,04-06 03:10:18.626  3599  3673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,04-06 03:10:18.631  3599  3673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@398dd0ea added. We now have 1 listener(s)
04-06 03:10:18.632  3599  3673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-06 03:10:18.635  3599  3673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,04-06 03:10:18.637  3599  3673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
04-06 03:10:18.637  3599  3673 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,04-06 03:10:18.641  3599  3673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,04-06 03:10:18.642   763  1279 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-06 03:10:18.642  3599  3673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,04-06 03:10:18.648  3599  3673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-06 03:10:18.648  3599  3673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-06 03:10:18.648  3599  3673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-06 03:10:18.648  3599  3673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-06 03:10:18.648  3599  3673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-06 03:10:18.648  3599  3673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-06 03:10:18.648  3599  3673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-06 03:10:18.648  3599  3673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-06 03:10:18.648  3599  3673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-06 03:10:18.648  3599  3673 D io.jxcore.node.ConnectivityMonitor: start: OK
,04-06 03:10:18.650  3599  3599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-06 03:10:18.652  3599  3599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
04-06 03:10:18.652  3599  3673 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-06 03:10:18.681  3599  3599 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-06 03:10:18.760   763   843 W PackageSettings: Skipping PackageSetting{22e614f2 com.example.hello/10116} due to missing metadata
,04-06 03:10:19.238  3599  3674 W jxcore-log: Initializing JXcore engine
04-06 03:10:19.239  3599  3674 W jxcore-log: JXcore engine is ready
,04-06 03:10:19.272  3674  3674 W Thread-362: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9444]" dev="sockfs" ino=9444 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,04-06 03:10:19.272  3674  3674 W Thread-362: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
04-06 03:10:19.272  3674  3674 W Thread-362: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8145]" dev="sockfs" ino=8145 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,04-06 03:10:19.272  3674  3674 W Thread-362: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[19694]" dev="sockfs" ino=19694 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,04-06 03:10:19.287  3599  3674 W jxcore-log: Starting JXcore engine
,04-06 03:10:19.368  3599  3674 W jxcore-log: Platform android
04-06 03:10:19.368  3599  3674 W jxcore-log: 
04-06 03:10:19.368  3599  3674 W jxcore-log: Process ARCH arm
04-06 03:10:19.368  3599  3674 W jxcore-log: 
,04-06 03:10:19.637  3599  3674 I jxcore-log: JXcore Cordova bridge is ready!
04-06 03:10:19.637  3599  3674 I jxcore-log: 
,04-06 03:10:19.638  3599  3674 W jxcore-log: JXcore engine is started
,04-06 03:10:19.646  3599  3673 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-06 03:10:19.648  3599  3599 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-06 03:10:22.302  3263  3287 W Babel   : aye TOOK TOO LONG! (15034ms > 10000ms)
,04-06 03:10:22.303  3263  3285 W Babel   : aye TOOK TOO LONG! (15041ms > 10000ms)
,04-06 03:10:22.307   763   852 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-06 03:10:22.311   763   778 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-06 03:10:22.314  3263  3263 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
04-06 03:10:22.314  3263  3263 W Babel   : BAM#gBA: invalid account id: -1
04-06 03:10:22.314  3263  3263 W Babel   : BAM#gBA: invalid account id: -1
04-06 03:10:22.314  3263  3263 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,04-06 03:10:22.316   763  1304 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-06 03:10:22.319   763   779 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-06 03:10:22.341  3263  3295 W Babel   : aye TOOK TOO LONG! (15037ms > 10000ms)
,04-06 03:10:22.469  1516  1620 I Finsky  : [120] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
04-06 03:10:22.470  1516  1516 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-06 03:10:25.463  1516  1516 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(151): Beginning daily hygiene
,04-06 03:10:25.471  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:10:25.479  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:10:25.481  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:10:25.727  1516  1604 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-06 03:10:25.727  1516  1604 I qtaguid : Untagging socket 37 failed errno=-22
04-06 03:10:25.727  1516  1604 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-06 03:10:25.731  1516  1604 I Finsky  : [108] com.google.android.finsky.e.d.a(3949): Process stable target turned on mid-process: 12602748
,04-06 03:10:25.735  1516  1604 I Finsky  : [108] com.google.android.finsky.e.a.b(88): Application close deferrer set because of stale process stable experiments
,04-06 03:10:25.748  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:10:25.848  1516  1603 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-06 03:10:25.848  1516  1603 I qtaguid : Untagging socket 37 failed errno=-22
04-06 03:10:25.848  1516  1603 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-06 03:10:25.850  1516  1516 I Finsky  : [1] com.google.android.finsky.m.e.a(156): Skipping DFE self-update. Local Version [80631600] >= Server Version [-1]
,04-06 03:10:25.854  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:10:26.183  1516  1604 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-06 03:10:26.183  1516  1604 I qtaguid : Untagging socket 37 failed errno=-22
04-06 03:10:26.183  1516  1604 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-06 03:10:26.611  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:10:26.762   763  1304 I ActivityManager: Start proc 3718:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,04-06 03:10:26.798  3718  3718 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,04-06 03:10:26.824  3718  3718 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@12ab76ce(com.android.providers.calendar.CalendarProvider2@228889ef)
,04-06 03:10:26.830   763  1304 I ActivityManager: Killing 3150:com.android.musicfx/u0a13 (adj 15): empty #17
,04-06 03:10:26.910   763   852 I ActivityManager: Killing 3231:com.quickoffice.android/u0a65 (adj 15): empty #17
,04-06 03:10:26.978  1516  1603 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-06 03:10:26.978  1516  1603 I qtaguid : Untagging socket 37 failed errno=-22
04-06 03:10:26.978  1516  1603 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-06 03:10:27.016   763   852 I ActivityManager: Killing 3182:com.google.android.apps.docs/u0a35 (adj 15): empty #18
,04-06 03:10:27.151  1516  1516 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler.b(99): Scheduling auto-update check using JobScheduler.
,04-06 03:10:27.159  1516  1516 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(9405): Logging device features
,04-06 03:10:27.173  1627  1627 D WearableService: callingUid 10007, callindPid: 1627
,04-06 03:10:27.181  1627  1713 D DeviceConnectionService: client connected with version: 8298000
,04-06 03:10:27.199  1516  1516 E Finsky  : [1] com.google.android.finsky.wear.bf.a(728): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
04-06 03:10:27.199  1516  1516 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6337): Dropping command=hygiene due to Gms not connected
,04-06 03:10:28.148  3718  3718 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
04-06 03:10:28.148  3718  3718 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,04-06 03:10:28.947  3599  3674 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-06 03:10:28.947  3599  3674 I jxcore-log: 
04-06 03:10:28.950  3599  3674 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-06 03:10:28.950  3599  3674 I jxcore-log: 
,04-06 03:10:28.953  3599  3674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-06 03:10:28.953  3599  3674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-06 03:10:28.953  3599  3674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-06 03:10:28.953  3599  3674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-06 03:10:28.953  3599  3674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-06 03:10:28.953  3599  3674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-06 03:10:28.953  3599  3674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-06 03:10:28.953  3599  3674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-06 03:10:28.955  3599  3674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,04-06 03:10:28.956  3599  3674 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-06 03:10:28.956  3599  3674 I jxcore-log: 
04-06 03:10:28.958  3599  3674 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-06 03:10:28.958  3599  3674 I jxcore-log: 
,04-06 03:10:29.438  3599  3674 I jxcore-log: Unit Test app is loaded
04-06 03:10:29.438  3599  3674 I jxcore-log: 
,04-06 03:10:29.444  3599  3599 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-06 03:10:29.445  3599  3674 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-06 03:10:29.445  3599  3674 I jxcore-log: 
,04-06 03:10:29.451  3599  3674 I jxcore-log: My device name is: LGE-Nexus 5
04-06 03:10:29.451  3599  3674 I jxcore-log: 
,04-06 03:10:29.496   763   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-58
04-06 03:10:29.496   763   868 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-06 03:10:31.848  3718  3777 E SQLiteLog: (284) automatic index on view_events(_id)
,04-06 03:10:31.882  1516  3778 I Finsky  : [133] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-06 03:10:31.887  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:10:31.894  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:10:31.896  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:10:33.142  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-06 03:10:33.142  3599  3674 I jxcore-log: 
,04-06 03:10:33.485  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-06 03:10:33.485  3599  3674 I jxcore-log: 
,04-06 03:10:33.509  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-06 03:10:33.509  3599  3674 I jxcore-log: 
,04-06 03:10:33.513  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-06 03:10:33.513  3599  3674 I jxcore-log: 
,04-06 03:10:33.528  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-06 03:10:33.528  3599  3674 I jxcore-log: 
,04-06 03:10:33.531  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-06 03:10:33.531  3599  3674 I jxcore-log: 
,04-06 03:10:35.404  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-06 03:10:35.404  3599  3674 I jxcore-log: 
,04-06 03:10:35.415  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-06 03:10:35.415  3599  3674 I jxcore-log: 
,04-06 03:10:35.424  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-06 03:10:35.424  3599  3674 I jxcore-log: 
,04-06 03:10:35.580  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-06 03:10:35.580  3599  3674 I jxcore-log: 
,04-06 03:10:36.482  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-06 03:10:36.482  3599  3674 I jxcore-log: 
,04-06 03:10:36.539  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-06 03:10:36.539  3599  3674 I jxcore-log: 
,04-06 03:10:36.545  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
04-06 03:10:36.545  3599  3674 I jxcore-log: 
,04-06 03:10:36.679  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-06 03:10:36.679  3599  3674 I jxcore-log: 
,04-06 03:10:36.699  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-06 03:10:36.699  3599  3674 I jxcore-log: 
,04-06 03:10:36.703  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-06 03:10:36.703  3599  3674 I jxcore-log: 
,04-06 03:10:36.708  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-06 03:10:36.708  3599  3674 I jxcore-log: 
,04-06 03:10:36.723  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-06 03:10:36.723  3599  3674 I jxcore-log: 
,04-06 03:10:36.742  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-06 03:10:36.742  3599  3674 I jxcore-log: 
,04-06 03:10:36.825  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-06 03:10:36.825  3599  3674 I jxcore-log: 
,04-06 03:10:36.830  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-06 03:10:36.830  3599  3674 I jxcore-log: 
,04-06 03:10:36.854  3599  3674 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-06 03:10:36.854  3599  3674 I jxcore-log: 
,04-06 03:10:36.874  3599  3674 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
04-06 03:10:36.875  3599  3674 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
04-06 03:10:36.875  3599  3674 I jxcore-log: 
,04-06 03:10:41.649  1516  1620 I Finsky  : [120] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-06 03:10:41.650  1516  1516 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-06 03:10:49.500   763   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-60
,04-06 03:11:05.748   763  1131 I art     : Explicit concurrent mark sweep GC freed 40176(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 1.496ms total 51.750ms
,04-06 03:11:05.774  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:11:05.777  1627  3828 I VacuumService: Vacuum at: now=1459905065777 tag=VacuumService
,04-06 03:11:06.973  1627  3841 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 6754 seconds from now (1459905066973)
,04-06 03:11:07.053  1627  3833 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,04-06 03:11:07.056  1627  3833 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-06 03:11:07.915  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:11:07.916  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:11:09.501   763   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-60
04-06 03:11:09.501   763   868 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-06 03:11:18.281  1108  1373 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-06 03:11:18.282  1108  1373 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-06 03:11:18.501  2063  2127 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-06 03:11:29.505   763   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-61
04-06 03:11:29.505   763   868 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-06 03:11:48.828   763   838 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,04-06 03:11:48.833   763   838 I PowerManagerService: Sleeping (uid 1000)...
,04-06 03:11:48.881   763   838 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-06 03:11:48.893   188   188 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-06 03:11:48.902   763   868 E WifiStateMachine: cancelDelayedScan -> 11
,04-06 03:11:48.906   763   868 E native  : do suspend false
,04-06 03:11:48.916   175  1454 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (173 us)
,04-06 03:11:49.120  1108  1108 I Keyboard.Facilitator: onFinishInput()
04-06 03:11:49.120   188   876 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,04-06 03:11:49.132   763   868 E WifiStateMachine: cancelDelayedScan -> 13
,04-06 03:11:49.134   763   868 E native  : do suspend true
,04-06 03:11:49.404   763   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-60
04-06 03:11:49.404   763   868 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,04-06 03:11:49.472   763   836 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
04-06 03:11:49.472   175   175 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
04-06 03:11:49.472   175   175 D qdhwcomposer: hwc_blank: Blanking display: 0
,04-06 03:11:49.475   763   763 V ActivityManager: Display changed displayId=0
,04-06 03:11:49.506   763   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-60
,04-06 03:11:49.506   763   868 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,04-06 03:11:49.595   176   176 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
,04-06 03:11:49.596   176   176 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,04-06 03:11:49.596   176   176 I rmt_storage: wakelock acquired: 1, error no: 2
04-06 03:11:49.596   176   575 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236803456)
,04-06 03:11:49.709   176   575 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,04-06 03:11:49.709   176   575 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
04-06 03:11:49.709   176   575 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236803456) wakelock released: 1, error no: 0
04-06 03:11:49.709   176   575 I rmt_storage: 
,04-06 03:11:49.711   176   176 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,04-06 03:11:49.776   175   175 D qdhwcomposer: hwc_blank: Done blanking display: 0
,04-06 03:11:49.778   763   886 D SurfaceControl: Excessive delay in setPowerMode(): 305ms
04-06 03:11:49.778  1766  1768 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,04-06 03:11:49.790  3599  3599 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
04-06 03:11:49.790  3599  3599 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,04-06 03:11:49.809  3599  3599 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@173d25c4 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@28c7bf7c, 16908290=android.view.AbsSavedState$1@28c7bf7c}, android:focusedViewId=100}]}]
04-06 03:11:49.809  3599  3599 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
04-06 03:11:49.809  3599  3599 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
04-06 03:11:49.810  3599  3599 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,04-06 03:12:04.225  1627  2021 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,04-06 03:12:27.205  1516  1516 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler$CheckPreconditionsAndAutoUpdateJobService.onStartJob(142): JobScheduler invoked, loading libraries.
,04-06 03:12:27.349  1516  1516 I Finsky  : [1] com.google.android.finsky.receivers.h.a(443): Request install of com.google.android.music v=2612 pri=3 for auto_update
,04-06 03:12:27.395  1516  1516 I Finsky  : [1] com.google.android.finsky.installer.v.b(149): Created session 649553479 for com.google.android.music
,04-06 03:12:27.408  1516  1516 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1184): Installer kick - starting com.google.android.music
,04-06 03:12:27.421  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:12:27.426  1516  1516 I Finsky  : [1] com.google.android.finsky.receivers.h.a(443): Request install of com.google.android.apps.docs v=61011635 pri=3 for auto_update
,04-06 03:12:27.430  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:12:27.432  1627  1627 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-06 03:12:27.449  1516  1516 I Finsky  : [1] com.google.android.finsky.installer.v.b(149): Created session 1757077855 for com.google.android.apps.docs
,04-06 03:12:27.455  1516  1516 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler$CheckPreconditionsAndAutoUpdateJobService.a(186): auto-updates finished successfully.
,04-06 03:12:27.742  1516  1604 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-06 03:12:27.742  1516  1604 I qtaguid : Untagging socket 37 failed errno=-22
04-06 03:12:27.742  1516  1604 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-06 03:12:28.014  1516  1516 I Finsky  : [1] com.google.android.finsky.receivers.ag.onPostExecute(2999): Downloading patch for com.google.android.music (com.google.android.music)
,04-06 03:12:28.015  1516  1516 I Finsky  : [1] com.google.android.finsky.download.e.a(242): Duplicate state set for 'com.google.android.music' (0). Already in that state
04-06 03:12:28.015  1516  1516 I Finsky  : [1] com.google.android.finsky.download.x.e(143): Download com.google.android.music added to DownloadQueue
,04-06 03:12:28.017  1516  1516 I Finsky  : [1] com.google.android.finsky.download.e.a(244): com.google.android.music from 0 to 1.
,04-06 03:12:28.020   189   189 I installd: free_cache(8544289) avail 11069652992
,04-06 03:12:28.022  1516  1516 I Finsky  : [1] com.google.android.finsky.download.ai.run(5557): Download com.google.android.music starting
,04-06 03:12:28.057  1516  1606 I Finsky  : [110] com.google.android.finsky.download.ae.a(1570): Enqueued com.google.android.music as content://downloads/my_downloads/802
,04-06 03:12:28.059  1516  1516 I Finsky  : [1] com.google.android.finsky.download.e.a(244): com.google.android.music from 1 to 2.
,04-06 03:12:28.059  1516  1516 I Finsky  : [1] com.google.android.finsky.download.x.a(635): com.google.android.music: onStart
,04-06 03:12:28.088  1516  1516 I Finsky  : [1] com.google.android.finsky.download.x.b(404): com.google.android.music: onProgress 0/-1 Status: 192.
,04-06 03:12:28.095   929  3898 D DownloadManager: [802] Starting
,04-06 03:12:28.105   929  3898 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,04-06 03:12:37.285  3599  3674 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-06 03:12:37.285  3599  3674 I jxcore-log: 
,04-06 03:12:37.615  3918  3918 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-06 03:12:37.620  3918  3918 D AndroidRuntime: CheckJNI is OFF
,04-06 03:12:37.725  3918  3918 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-06 03:12:37.732   763   831 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
04-06 03:12:37.732   763   831 I ActivityManager: Killing 3599:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,04-06 03:12:37.771   763   843 W PackageSettings: Skipping PackageSetting{22e614f2 com.example.hello/10116} due to missing metadata
,04-06 03:12:37.783   763  1304 I WindowState: WIN DEATH: Window{2c46df26 u0 com.test.thalitest/com.test.thalitest.MainActivity}
04-06 03:12:37.783   763   852 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@36110356)
,04-06 03:12:37.783   763   869 D WifiService: Client connection lost with reason: 4
04-06 03:12:37.784   763   870 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-06 03:12:37.784   763   870 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-06 03:12:37.941   763   831 I ActivityManager:   Force finishing activity 3 ActivityRecord{375a7e84 u0 com.test.thalitest/.MainActivity t19}
,04-06 03:12:37.943   763  1129 W ActivityManager: Spurious death for ProcessRecord{1ec6cfd7 3599:com.test.thalitest/u0a49}, curProc for 3599: null
,04-06 03:12:37.946   763   843 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,04-06 03:12:38.018   909   909 I art     : Explicit concurrent mark sweep GC freed 15247(678KB) AllocSpace objects, 0(0B) LOS objects, 27% free, 41MB/57MB, paused 735us total 33.769ms
,04-06 03:12:38.026  1305  1305 I art     : Explicit concurrent mark sweep GC freed 1931(115KB) AllocSpace objects, 4(369KB) LOS objects, 38% free, 25MB/41MB, paused 757us total 47.016ms
04-06 03:12:38.026   763   888 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
04-06 03:12:38.026   763   888 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,04-06 03:12:38.048  1423  1423 I art     : Explicit concurrent mark sweep GC freed 3235(245KB) AllocSpace objects, 7(154KB) LOS objects, 25% free, 22MB/30MB, paused 1.206ms total 96.916ms
,04-06 03:12:38.049  1556  1556 I art     : Explicit concurrent mark sweep GC freed 7499(386KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 23MB/31MB, paused 498us total 94.347ms
,04-06 03:12:38.050   763   860 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-06 03:12:38.053  1108  1108 I Keyboard.Facilitator: resetDictionaries() : en_US
,04-06 03:12:38.054  1627  1716 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,04-06 03:12:38.055  1108  3957 I Keyboard.Facilitator.DecoderInitializer: run()
,04-06 03:12:38.058  1108  3957 I Decoder : createOrResetDecoder
,04-06 03:12:38.069  1381  3958 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,04-06 03:12:38.099   763   763 I art     : Explicit concurrent mark sweep GC freed 52685(3MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 29MB/44MB, paused 2.191ms total 102.626ms
,04-06 03:12:38.101   763   843 I art     : WaitForGcToComplete blocked for 73.466ms for cause Explicit
,04-06 03:12:38.116   763  1304 I ActivityManager: Start proc 3959:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,04-06 03:12:38.135  1108  3957 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,04-06 03:12:38.177   763  1304 I ActivityManager: Start proc 3979:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,04-06 03:12:38.182   763   778 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3599 uid 10049
,04-06 03:12:38.183   763  1131 I ActivityManager: Killing 3331:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
,04-06 03:12:38.184  1108  1108 I Keyboard.Facilitator: onFinishInput()
,04-06 03:12:38.189   763   763 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-06 03:12:38.189   763   763 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,04-06 03:12:38.193  1108  3957 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
04-06 03:12:38.195  1108  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
04-06 03:12:38.195  1108  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,04-06 03:12:38.196  1108  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,04-06 03:12:38.196  1108  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,04-06 03:12:38.197  1108  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
04-06 03:12:38.197  1108  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
04-06 03:12:38.197  1108  3957 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-06 03:12:38.197  1108  3957 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-06 03:12:38.197  1108  3957 I Keyboard.Facilitator.Delight2FileSweeper: run()
04-06 03:12:38.198  1108  3957 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-06 03:12:38.198  1108  3957 I StatsUtilsManager: startPeriodStatsRecorder() : Success
04-06 03:12:38.198  1108  3957 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,04-06 03:12:38.209  1305  1305 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-06 03:12:38.232   763   843 I art     : Explicit concurrent mark sweep GC freed 13150(1281KB) AllocSpace objects, 2(1312KB) LOS objects, 33% free, 28MB/42MB, paused 1.613ms total 129.802ms
,04-06 03:12:38.253  3979  3979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-06 03:12:38.258  1516  1516 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(268): Wear auto uninstall disabled for package com.test.thalitest
,04-06 03:12:38.268  1556  3999 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-06 03:12:38.268  1556  3999 D AccountUtils: Clearing selected account for com.test.thalitest
,04-06 03:12:38.278  1627  1627 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-06 03:12:38.278  1627  1627 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-06 03:12:38.281  1556  3999 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,04-06 03:12:38.294  1305  1460 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-06 03:12:38.309   763  1105 I ActivityManager: Start proc 4005:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,04-06 03:12:38.338  3918  3918 I art     : System.exit called, status: 0
04-06 03:12:38.338  3918  3918 I AndroidRuntime: VM exiting with result code 0.
,04-06 03:12:38.398   763   843 I ActivityManager: Start proc 4024:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,04-06 03:12:38.406  1556  4021 W BaseAppContext: Using Auth Proxy for data requests.
,04-06 03:12:38.408  1556  4021 W BaseAppContext: Using Auth Proxy for data requests.
,04-06 03:12:38.421   763   778 I ActivityManager: Killing 2871:com.google.android.gms.unstable/u0a7 (adj 15): empty #17
,04-06 03:12:38.510  1556  4045 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/databases/DocList.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,04-06 03:12:38.523  1556  3999 I GMPM-SVC: App measurement is starting up, version: 8703
04-06 03:12:38.523  1556  3999 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,04-06 03:12:38.536  4005  4049 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
04-06 03:12:38.536  4005  4049 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
04-06 03:12:38.536  4005  4049 I GAv4    :   adb logcat -s GAv4
,04-06 03:12:38.543  1556  3999 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,04-06 03:12:38.553  4005  4049 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,04-06 03:12:38.560  1556  4050 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2307)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:418)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.a(:com.google.android.gms:357)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.s(:com.google.android.gms:1591)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.p(:com.google.android.gms:1605)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.c(:com.google.android.gms:306)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ar.run(:com.google.android.gms:195)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-06 03:12:38.560  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ap.run(:com.google.android.gms:294)
04-06 03:12:38.560  1556  4050 E GMPM-SVC: Opening the database failed, dropping and recreating it
,04-06 03:12:38.561  4005  4049 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:418)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.a(:com.google.android.gms:357)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.s(:com.google.android.gms:1591)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.p(:com.google.android.gms:1605)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.c(:com.google.android.gms:306)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ar.run(:com.google.android.gms:195)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-06 03:12:38.562  1556  4050 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ap.run(:com.google.android.gms:294)
04-06 03:12:38.562  4005  4057 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-06 03:12:38.562  1556  4050 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an, error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
04-06 03:12:38.562  4005  4057 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-06 03:12:38.562  1556  4050 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
04-06 03:12:38.562  1556  4050 E GMPM-SVC: Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
04-06 03:12:38.563  1556  4050 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2303)
04-06 03:12:38.563  1556  4050 E GMPM-SVC: Error querying app: com.test.thalitest, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2303)
04-06 03:12:38.564  4005  4058 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
04-06 03:12:38.565  4005  4057 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-06 03:12:38.565  1556  4050 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2303)
04-06 03:12:38.566  1556  4050 E GMPM-SVC: Task exception on worker thread: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2303)
04-06 03:12:38.567  1556  2041 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
04-06 03:12:38.568  1556  2041 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
04-06 03:12:38.568  1556  2041 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
04-06 03:12:38.568  1556  2041 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
04-06 03:12:38.568  1556  2041 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
04-06 03:12:38.568  1556  2041 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
04-06 03:12:38.568  1556  2041 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
04-06 03:12:38.568  1556  2041 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at hey$a.getWritableDatabase(Unknown Source)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at hey.l(Unknown Source)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at hey.a(Unknown Source)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at hey.j(Unknown Source)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at hfd.run(Unknown Source)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
04-06 03:12:38.569  4005  4058 E SQLiteDatabase: 	at iom$c.run(Unknown Source)
04-06 03:12:38.570  4005  4058 E GAv4    : Opening the database failed, dropping the table and recreating it
04-06 03:12:38.570  4005  4057 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at hey$a.getWritableDatabase(Unknown Source)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at hey.l(Unknown Source)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at hey.a(Unknown Source)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at hey.j(Unknown Source)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at hfd.run(Unknown Source)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
04-06 03:12:38.571  4005  4058 E SQLiteDatabase: 	at iom$c.run(Unknown Source)
04-06 03:12:38.571  4005  4058 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-06 03:12:38.572  4005  4058 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-06 03:12:38.572  4005  4057 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-06 03:12:38.572  4005  4058 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-06 03:12:38.572  4005  4057 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-06 03:12:38.572  4005  4057 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
04-06 03:12:38.573  1556  4059 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
04-06 03:12:38.576  1556  4059 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
04-06 03:12:38.576  1556  4059 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
04-06 03:12:38.576  1556  4059 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
04-06 03:12:38.576   763  1105 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-06 03:12:38.576  1556  4059 I GCore-Chimera-Crash: ==
04-06 03:12:38.576  1556  4059 I GCore-Chimera-Crash: GCore-Chimera-Crash
04-06 03:12:38.576   763   870 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-06 03:12:38.576   763   870 D ConnectivityService: apparently satisfied.  currentScore=60
04-06 03:12:38.577  1556  4060 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
--------- beginning of crash
04-06 03:12:38.578  1556  4059 E AndroidRuntime: FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
04-06 03:12:38.578  1556  4059 E AndroidRuntime: Process: com.google.android.gms, PID: 1556
04-06 03:12:38.578  1556  4059 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at com.google.android.gms.people.c.e.a(:com.google.android.gms:110)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at com.google.android.gms.people.sync.a.b.d(:com.google.android.gms:3165)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at com.google.android.gms.people.service.bg.b.a(:com.google.android.gms:245)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(:com.google.android.gms:77)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
04-06 03:12:38.578  1556  4059 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-06 03:12:38.580  1556  1650 I Icing   : doRemovePackageData com.test.thalitest
04-06 03:12:38.581  1556  4059 I Process : Sending signal. PID: 1556 SIG: 9
04-06 03:12:38.586   763  4061 E DropBoxManagerService: Can't write: system_app_crash
04-06 03:12:38.586   763  4061 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
04-06 03:12:38.586   763  4061 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-06 03:12:38.586   763  4061 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-06 03:12:38.586   763  4061 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-06 03:12:38.586   763  4061 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-06 03:12:38.586   763  4061 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-06 03:12:38.586   763  4061 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-06 03:12:38.586   763  4061 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-06 03:12:38.586   763  4061 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-06 03:12:38.586   763  4061 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-06 03:12:38.586   763  4061 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-06 03:12:38.586   763  4061 E DropBoxManagerService: 	... 5 more
04-06 03:12:38.598   763  1131 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@febbf4e)
,04-06 03:12:38.599   763   870 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-06 03:12:38.600   763   870 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-06 03:12:38.600   763   869 D WifiService: Client connection lost with reason: 4

```
