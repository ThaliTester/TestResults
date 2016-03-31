#### Test 645312549bcf247_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
,03-31 01:47:59.328  1563  2571 I CheckinService: Done disabling old GoogleServicesFramework version
03-31 01:47:59.580  3602  3602 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 01:47:59.598  3602  3602 D AndroidRuntime: CheckJNI is OFF
--------- beginning of system
03-31 01:47:59.616   768   843 W PackageSettings: Skipping PackageSetting{2804d155 com.example.hello/10116} due to missing metadata
03-31 01:47:59.703  3602  3602 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-31 01:47:59.707   768  1247 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 01:47:59.712   768  1247 V WindowManager: addAppToken: AppWindowToken{2edb8f02 token=Token{39cfe84d ActivityRecord{1b61fbe4 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-31 01:47:59.717   768   837 V WindowManager: Adding window Window{29bed405 u0 Starting com.test.thalitest} at 2 of 7 (after Window{8f2c029 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 01:47:59.719  3602  3602 D AndroidRuntime: Shutting down VM
03-31 01:47:59.726  1433  1452 W SearchService: Abort, client detached.
03-31 01:47:59.751   768   858 I ActivityManager: Start proc 3623:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-31 01:47:59.778  1433  1433 I MicroDetector: Keeping mic open: false
03-31 01:47:59.778  1433  1433 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@284ca42e
03-31 01:47:59.778  1433  1595 I DeviceStateChecker: DeviceStateChecker cancelled
03-31 01:47:59.787  1433  1587 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
03-31 01:47:59.808   201   201 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 392us total 47.636ms
03-31 01:47:59.832   190  1601 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 01:47:59.832   201   201 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 403us total 23.359ms
03-31 01:47:59.832   190  1601 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 01:47:59.843  1433  1598 I MicroRecognitionRunner: Detection finished
03-31 01:47:59.845   201   201 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 198us total 10.863ms
03-31 01:47:59.845  1433  1594 I MicroRecognitionRunner: Stopping hotword detection.
03-31 01:47:59.894  3623  3623 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
03-31 01:47:59.903  3623  3623 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 1211-1212)
03-31 01:47:59.903  3623  3623 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 01:47:59.904   768  1252 I ActivityManager: Killing 2176:com.android.providers.calendar/u0a1 (adj 15): empty #17
03-31 01:47:59.912  3623  3623 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {55025dd}
03-31 01:47:59.912  3623  3623 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 01:47:59.912  3623  3623 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 01:47:59.943  3623  3623 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,03-31 01:47:59.959  3623  3623 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-31 01:48:00.008   768   836 D BluetoothManagerService: Message: 20
,03-31 01:48:00.008   768   836 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2dcbb07b:true
,03-31 01:48:00.018  3623  3623 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-31 01:48:00.018  3623  3623 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-31 01:48:00.054  3623  3623 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-31 01:48:00.055  3623  3623 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-31 01:48:00.066  3623  3623 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-31 01:48:00.072  3623  3623 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 01:48:00.073  3623  3623 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-31 01:48:00.082  3623  3623 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-31 01:48:00.102  3623  3682 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 01:48:00.107  3623  3623 D Atlas   : Validating map...
,03-31 01:48:00.163   768  1133 I art     : Explicit concurrent mark sweep GC freed 28909(1631KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 1.336ms total 51.007ms
,03-31 01:48:00.164   768  1133 V WindowManager: Adding window Window{11fe0d86 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{29bed405 u0 Starting com.test.thalitest})
,03-31 01:48:00.177   768   869 D WifiService: New client listening to asynchronous messages
,03-31 01:48:00.188   768   783 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 01:48:00.188   768   870 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 01:48:00.188   768   870 D ConnectivityService: apparently satisfied.  currentScore=60
,03-31 01:48:00.189  3623  3685 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 01:48:00.220  3623  3682 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 01:48:00.223  3623  3682 D OpenGLRenderer: Enabling debug mode 0
,03-31 01:48:00.266   768   837 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +539ms
,03-31 01:48:00.270  1111  1111 I Keyboard.Facilitator: onFinishInput()
,03-31 01:48:00.290  3623  3688 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-31 01:48:00.326  3623  3623 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3623
,03-31 01:48:00.481  3623  3623 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 01:48:00.583  3623  3697 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1265505280
,03-31 01:48:00.590  3623  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 01:48:00.590  3623  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 01:48:00.590  3623  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 01:48:00.590  3623  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 01:48:00.590  3623  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-31 01:48:00.590  3623  3697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@315ef444 added. We now have 1 listener(s)
03-31 01:48:00.592   768  1247 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 01:48:00.624  3623  3697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,03-31 01:48:00.629  3623  3697 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-31 01:48:00.630  3623  3697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 01:48:00.631  3623  3697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-31 01:48:00.639  3623  3697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a7910b0 added. We now have 1 listener(s)
03-31 01:48:00.640  3623  3697 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 01:48:00.643  3623  3697 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-31 01:48:00.651  3623  3697 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,03-31 01:48:00.651  3623  3697 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-31 01:48:00.655  3623  3697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 01:48:00.655   768  1135 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 01:48:00.657  3623  3697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-31 01:48:00.664  3623  3697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 01:48:00.664  3623  3697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 01:48:00.664  3623  3697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 01:48:00.664  3623  3697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 01:48:00.664  3623  3697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 01:48:00.664  3623  3697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 01:48:00.664  3623  3697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 01:48:00.664  3623  3697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 01:48:00.664  3623  3697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 01:48:00.664  3623  3697 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 01:48:00.666  3623  3697 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 01:48:00.667  3623  3623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 01:48:00.668  3623  3623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 01:48:00.690  3623  3623 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 01:48:01.387  3623  3698 W jxcore-log: Initializing JXcore engine
03-31 01:48:01.387  3623  3698 W jxcore-log: JXcore engine is ready
,03-31 01:48:01.417  3698  3698 W Thread-358: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[6693]" dev="sockfs" ino=6693 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-31 01:48:01.417  3698  3698 W Thread-358: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,03-31 01:48:01.427  3698  3698 W Thread-358: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[7438]" dev="sockfs" ino=7438 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-31 01:48:01.427  3698  3698 W Thread-358: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[18736]" dev="sockfs" ino=18736 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-31 01:48:01.445  3623  3698 W jxcore-log: Starting JXcore engine
,03-31 01:48:01.582  3623  3698 W jxcore-log: Platform android
03-31 01:48:01.582  3623  3698 W jxcore-log: 
03-31 01:48:01.582  3623  3698 W jxcore-log: Process ARCH arm
03-31 01:48:01.582  3623  3698 W jxcore-log: 
,03-31 01:48:01.807  3623  3698 I jxcore-log: JXcore Cordova bridge is ready!
03-31 01:48:01.807  3623  3698 I jxcore-log: 
03-31 01:48:01.807  3623  3698 W jxcore-log: JXcore engine is started
,03-31 01:48:01.810  3623  3697 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 01:48:01.811  3623  3623 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 01:48:03.145  3281  3310 W Babel   : aye TOOK TOO LONG! (15027ms > 10000ms)
,03-31 01:48:03.146  3281  3308 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-31 01:48:03.150   768   858 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 01:48:03.155   768  1135 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 01:48:03.157  3281  3281 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-31 01:48:03.158  3281  3281 W Babel   : BAM#gBA: invalid account id: -1
03-31 01:48:03.158  3281  3281 W Babel   : BAM#gBA: invalid account id: -1
03-31 01:48:03.158  3281  3281 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-31 01:48:03.160   768  1247 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 01:48:03.162   768  1244 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 01:48:03.231  3281  3318 W Babel   : aye TOOK TOO LONG! (15039ms > 10000ms)
,03-31 01:48:03.274  1659  1777 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-31 01:48:03.275  1659  1659 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 01:48:09.055   768  1135 I ActivityManager: Start proc 3746:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,03-31 01:48:09.096  3746  3746 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-31 01:48:09.122  3746  3746 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@3a8d75b4(com.android.providers.calendar.CalendarProvider2@55025dd)
,03-31 01:48:09.132   768  1133 I ActivityManager: Killing 3159:com.android.musicfx/u0a13 (adj 15): empty #17
,03-31 01:48:09.215   768   783 I ActivityManager: Killing 2515:com.google.android.calendar/u0a28 (adj 15): empty #17
,03-31 01:48:09.897   768   868 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 01:48:09.897   768   868 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 01:48:10.234  3746  3746 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-31 01:48:10.235  3746  3746 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-31 01:48:10.252   768   832 I ActivityManager: Start proc 3784:com.google.android.calendar/u0a28 for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,03-31 01:48:10.254   768  1133 I ActivityManager: Killing 3192:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,03-31 01:48:10.477  3784  3784 E SQLiteLog: (283) recovered 44 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,03-31 01:48:10.610  3784  3784 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,03-31 01:48:11.056  3623  3698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 01:48:11.056  3623  3698 I jxcore-log: 
,03-31 01:48:11.058  3623  3698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 01:48:11.058  3623  3698 I jxcore-log: 
,03-31 01:48:11.061  3623  3698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 01:48:11.061  3623  3698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 01:48:11.061  3623  3698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 01:48:11.061  3623  3698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 01:48:11.061  3623  3698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 01:48:11.061  3623  3698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 01:48:11.061  3623  3698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 01:48:11.061  3623  3698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 01:48:11.063  3623  3698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-31 01:48:11.064  3623  3698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 01:48:11.064  3623  3698 I jxcore-log: 
03-31 01:48:11.065  3623  3698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 01:48:11.065  3623  3698 I jxcore-log: 
,03-31 01:48:11.367  1659  1659 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-31 01:48:11.387  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 01:48:11.395  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 01:48:11.398  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 01:48:11.566  3623  3698 I jxcore-log: Unit Test app is loaded
03-31 01:48:11.566  3623  3698 I jxcore-log: 
,03-31 01:48:11.573  3623  3623 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 01:48:11.575  3623  3698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 01:48:11.575  3623  3698 I jxcore-log: 
,03-31 01:48:11.583  3623  3698 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,03-31 01:48:11.586  3623  3698 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-31 01:48:11.586  3623  3698 I jxcore-log: 
,03-31 01:48:11.593  3623  3623 I chromium: [INFO:CONSOLE(86)] "logCallback Device did not have required hardware capabilities!", source: file:///android_asset/www/js/thali_main.js (86)
,03-31 01:48:11.598  3623  3698 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-31 01:48:11.598  3623  3698 I jxcore-log:   bluetooth: 'on',
03-31 01:48:11.598  3623  3698 I jxcore-log:   wifi: 'on',
03-31 01:48:11.598  3623  3698 I jxcore-log:   cellular: 'doNotCare',
03-31 01:48:11.598  3623  3698 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-31 01:48:11.598  3623  3698 I jxcore-log: 
03-31 01:48:11.598  3623  3698 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-31 01:48:11.598  3623  3698 I jxcore-log: 
,03-31 01:48:11.841  3821  3821 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-31 01:48:11.844  3821  3821 D AndroidRuntime: CheckJNI is OFF
,03-31 01:48:11.953  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 01:48:11.959  3821  3821 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 01:48:11.964   768   832 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
,03-31 01:48:11.965   768   832 I ActivityManager: Killing 3623:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-31 01:48:11.999   768   869 D WifiService: Client connection lost with reason: 4
,03-31 01:48:11.999   768   783 I WindowState: WIN DEATH: Window{11fe0d86 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-31 01:48:11.999   768   784 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@32d652a5)
03-31 01:48:12.000   768   870 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 01:48:12.000   768   870 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 01:48:12.006   768   843 W PackageSettings: Skipping PackageSetting{2804d155 com.example.hello/10116} due to missing metadata
,03-31 01:48:12.048  1659  1747 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-31 01:48:12.048  1659  1747 I qtaguid : Untagging socket 38 failed errno=-22
03-31 01:48:12.048  1659  1747 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-31 01:48:12.051  1659  1659 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-31 01:48:12.071   768   832 W ActivityManager: Force removing ActivityRecord{1b61fbe4 u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-31 01:48:12.077   768  1135 W ActivityManager: Spurious death for ProcessRecord{30da67a 3623:com.test.thalitest/u0a49}, curProc for 3623: null
,03-31 01:48:12.078   768   843 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-31 01:48:12.090  1525  1632 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-31 01:48:12.096   768   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 01:48:12.100  1111  1111 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-31 01:48:12.118   909   909 I art     : Explicit concurrent mark sweep GC freed 7490(347KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 1.231ms total 33.093ms
,03-31 01:48:12.120   768   888 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-31 01:48:12.163   768   783 I ActivityManager: Start proc 3847:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-31 01:48:12.170  1111  3835 I Keyboard.Facilitator.DecoderInitializer: run()
,03-31 01:48:12.173  1111  3835 I Decoder : createOrResetDecoder
,03-31 01:48:12.182  1369  3837 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-31 01:48:12.206   768   768 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 01:48:12.206   768   768 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-31 01:48:12.219  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 01:48:12.219  1433  1433 I art     : Explicit concurrent mark sweep GC freed 5232(371KB) AllocSpace objects, 7(154KB) LOS objects, 40% free, 21MB/36MB, paused 964us total 137.299ms
,03-31 01:48:12.233  1563  1563 I art     : Explicit concurrent mark sweep GC freed 1250(49KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 23MB/30MB, paused 547us total 152.361ms
,03-31 01:48:12.246   768  1247 I ActivityManager: Start proc 3872:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-31 01:48:12.268   768   784 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3623 uid 10049
03-31 01:48:12.269  1111  1111 I Keyboard.Facilitator: onFinishInput()
,03-31 01:48:12.276   768  1133 I ActivityManager: Start proc 3892:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-31 01:48:12.316  1248  1248 I art     : Explicit concurrent mark sweep GC freed 2835(160KB) AllocSpace objects, 4(369KB) LOS objects, 38% free, 25MB/41MB, paused 811us total 23.145ms
,03-31 01:48:12.324  3872  3872 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 01:48:12.325  3872  3872 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 01:48:12.342  1433  1433 W LocationOracle: Best location was null
03-31 01:48:12.342  1433  1433 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-31 01:48:12.346  3892  3892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-31 01:48:12.360   768   843 I art     : Explicit concurrent mark sweep GC freed 35160(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 1.380ms total 157.449ms
,03-31 01:48:12.365  1563  3913 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-31 01:48:12.365  1563  3913 D AccountUtils: Clearing selected account for com.test.thalitest
,03-31 01:48:12.366   768   768 I art     : WaitForGcToComplete blocked for 158.217ms for cause Explicit
,03-31 01:48:12.366  1433  3914 I MicroRecognitionRunner: Starting detection.
,03-31 01:48:12.367  1433  3915 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@20aac1f9
,03-31 01:48:12.371   190  3918 I AudioFlinger: AudioFlinger's thread 0xb4403000 ready to run
,03-31 01:48:12.376  1433  3915 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@20aac1f9
,03-31 01:48:12.386   190  3918 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-31 01:48:12.386   190  3918 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-31 01:48:12.386   190  3918 D         : Failed to fetch the lookup information of the device 0000003E 
03-31 01:48:12.386   190  3918 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-31 01:48:12.386   190  3918 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-31 01:48:12.392   190  3918 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-31 01:48:12.408  3872  3872 I MultiDex: VM with version 2.1.0 has multidex support
03-31 01:48:12.408  1525  1612 W GCoreFlp: No location to return for getLastLocation()
,03-31 01:48:12.409  3872  3872 I MultiDex: install
03-31 01:48:12.409  3872  3872 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 01:48:12.413  1563  3913 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
03-31 01:48:12.414  1525  1612 W GCoreFlp: No location to return for getLastLocation()
,03-31 01:48:12.423  1525  1612 W GCoreFlp: No location to return for getLastLocation()
,03-31 01:48:12.428  1525  1525 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-31 01:48:12.429  1525  1525 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-31 01:48:12.442   768   768 I art     : Explicit concurrent mark sweep GC freed 6326(329KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.790ms total 74.995ms
,03-31 01:48:12.458   768   858 I ActivityManager: Start proc 3925:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-31 01:48:12.473  1525  1612 W GCoreFlp: No location to return for getLastLocation()
,03-31 01:48:12.478  1433  1433 I MicroDetectionWorker: onReady
,03-31 01:48:12.484  1563  3923 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 01:48:12.492  1563  3923 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 01:48:12.505  3872  3872 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-31 01:48:12.508  1563  3913 I GMPM-SVC: App measurement is starting up, version: 8703
03-31 01:48:12.508  1563  3913 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-31 01:48:12.522  1248  1424 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-31 01:48:12.535  1525  1612 W GCoreFlp: No location to return for getLastLocation()
,03-31 01:48:12.536  3821  3821 I art     : System.exit called, status: 0
03-31 01:48:12.536  3821  3821 I AndroidRuntime: VM exiting with result code 0.
,03-31 01:48:12.565  1525  1612 W GCoreFlp: No location to return for getLastLocation()
,03-31 01:48:12.568  1563  3913 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-31 01:48:12.594  3872  3872 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 01:48:12.611   768   843 I ActivityManager: Start proc 3959:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-31 01:48:12.623  1563  1633 I Icing   : doRemovePackageData com.test.thalitest
,03-31 01:48:12.633   768  1189 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 01:48:12.634   768   870 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 01:48:12.634   768   870 D ConnectivityService: apparently satisfied.  currentScore=60
03-31 01:48:12.634  1563  3977 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 01:48:12.653  3872  3872 D ChimeraCfgMgr: Reading stored module config
,03-31 01:48:12.662  1563  3955 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-31 01:48:12.662  1563  3955 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-31 01:48:12.662  1563  3955 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-31 01:48:12.663  1563  3955 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-31 01:48:12.668  1111  3835 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-31 01:48:12.671  1563  3955 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-31 01:48:12.671  1563  3955 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,03-31 01:48:12.672  1563  3955 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-31 01:48:12.680  1563  3955 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-31 01:48:12.680  1563  3955 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-31 01:48:12.682  1563  3955 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
03-31 01:48:12.683  1563  3955 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
03-31 01:48:12.683  1563  3955 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-31 01:48:12.684  1563  3955 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-31 01:48:12.702  1111  3835 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-31 01:48:12.705  1111  3835 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 01:48:12.705  1111  3835 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-31 01:48:12.707  1111  3835 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-31 01:48:12.707  1111  3835 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-31 01:48:12.708  1111  3835 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 01:48:12.708  1111  3835 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-31 01:48:12.709  1111  3835 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 01:48:12.709  1111  3835 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 01:48:12.709  1111  3835 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-31 01:48:12.709  1111  3835 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 01:48:12.709  1111  3835 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 01:48:12.709  1111  3835 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-31 01:48:12.714  1563  3922 W DriveInitializer: Awaiting to be initialized
03-31 01:48:12.714  1563  3982 W DriveInitializer: Background init thread started
,03-31 01:48:12.744  1563  3982 E DocListDatabase: Failed to delete from ContentFileDeletionLock163 table
03-31 01:48:12.744  1563  3982 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-31 01:48:12.744  1563  3982 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 01:48:12.744  1563  3982 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 01:48:12.744  1563  3982 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 01:48:12.744  1563  3982 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 01:48:12.744  1563  3982 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 01:48:12.744  1563  3982 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-31 01:48:12.744  1563  3982 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-31 01:48:12.744  1563  3982 E DocListDatabase: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-31 01:48:12.744  1563  3982 W DriveInitializer: Background init thread ended
03-31 01:48:12.745  1563  3922 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-31 01:48:12.745  1563  3922 E DriveAsyncService: disk I/O error (code 3850)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(:com.google.android.gms:486)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(:com.google.android.gms:461)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(:com.google.android.gms:1519)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(:com.google.android.gms:16)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-31 01:48:12.745  1563  3922 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-31 01:48:12.748  1563  3982 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-31 01:48:12.748  1563  3982 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-31 01:48:12.748  1563  3982 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-31 01:48:12.748  1563  3982 I GCore-Chimera-Crash: ==
03-31 01:48:12.748  1563  3982 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
03-31 01:48:12.748  1563  3982 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-31 01:48:12.748  1563  3982 E AndroidRuntime: Process: com.google.android.gms, PID: 1563
03-31 01:48:12.748  1563  3982 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-31 01:48:12.748  1563  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 01:48:12.748  1563  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 01:48:12.748  1563  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 01:48:12.748  1563  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 01:48:12.748  1563  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 01:48:12.748  1563  3982 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-31 01:48:12.748  1563  3982 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-31 01:48:12.748  1563  3982 E AndroidRuntime: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
,03-31 01:48:12.755   768  3984 E DropBoxManagerService: Can't write: system_app_crash
03-31 01:48:12.755   768  3984 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-31 01:48:12.755   768  3984 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 01:48:12.755   768  3984 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 01:48:12.755   768  3984 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 01:48:12.755   768  3984 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 01:48:12.755   768  3984 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 01:48:12.755   768  3984 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 01:48:12.755   768  3984 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 01:48:12.755   768  3984 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 01:48:12.755   768  3984 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 01:48:12.755   768  3984 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 01:48:12.755   768  3984 E DropBoxManagerService: 	... 5 more
,03-31 01:48:12.764   768   832 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 01:48:12.764   768   832 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 01:48:12.780   768  3985 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 01:48:12.781   768   832 D Atlas   : Validating map...
,03-31 01:48:12.781  3872  3978 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-31 01:48:12.791  3872  3872 D CAR.SERVICE: Connecting to CarCallService...
,03-31 01:48:12.794  1248  1496 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-31 01:48:12.794  1248  1496 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-31 01:48:12.807  3872  3872 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 01:48:12.807  3872  3872 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 01:48:12.816   768  3985 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
03-31 01:48:12.816   768  3985 I OpenGLRenderer: Initialized EGL, version 1.4
03-31 01:48:12.816  3872  3872 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-31 01:48:12.820   768  3985 D OpenGLRenderer: Enabling debug mode 0
03-31 01:48:12.820   768  1252 I ActivityManager: Killing 3250:com.quickoffice.android/u0a65 (adj 15): empty #17
,03-31 01:48:12.826  1659  1748 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-31 01:48:12.826  1659  1748 I qtaguid : Untagging socket 38 failed errno=-22
03-31 01:48:12.827  1659  1748 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-31 01:48:12.843  3925  3992 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
03-31 01:48:12.843  3925  3992 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 01:48:12.843  3925  3992 I GAv4    :   adb logcat -s GAv4
,03-31 01:48:12.846   178   178 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-31 01:48:12.846   178   178 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-31 01:48:12.846   178   178 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-31 01:48:12.846   178   178 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-31 01:48:12.846   178   178 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 01:48:12.846   178   178 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 01:48:12.846   178   178 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-31 01:48:12.846   178   178 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-31 01:48:12.846   178   178 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 01:48:12.846   178   178 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 01:48:12.846   178   178 E qdoverlay: Ctrl commit failed set overlay
03-31 01:48:12.846   178   178 E qdhwcomposer: configureLowRes: commit failed for low res panel
03-31 01:48:12.846   178   178 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-31 01:48:12.846   178   178 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-31 01:48:12.846   178   178 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
03-31 01:48:12.846   178   178 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
03-31 01:48:12.846   178   178 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 01:48:12.846   178   178 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-31 01:48:12.846   178   178 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
03-31 01:48:12.846   178   178 E qdoverlay: src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
03-31 01:48:12.846   178   178 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=75
03-31 01:48:12.846   178   178 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=75
03-31 01:48:12.846   178   178 E qdoverlay: Ctrl commit failed set overlay
03-31 01:48:12.846   178   178 E qdhwcomposer: configure: commit fails
03-31 01:48:12.846   178   178 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-31 01:48:12.846   178   178 E qdoverlay: MdpCtrl close error in unset
,03-31 01:48:12.865  3872  3872 D CAR.TEL.Service: Creating a new CarCallService.
,03-31 01:48:12.866  3872  3872 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-31 01:48:12.867   768  1189 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-31 01:48:12.867  3872  3872 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@2c9bf412
03-31 01:48:12.867   768  1244 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-31 01:48:12.868  3872  3872 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-31 01:48:12.868  3872  3872 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-31 01:48:12.892  3925  3992 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-31 01:48:12.899  3925  3992 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-31 01:48:12.899  3925  4000 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-31 01:48:12.899  3925  4000 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 01:48:12.906  3925  4001 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-31 01:48:12.907  3925  4000 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-31 01:48:12.921  3872  3888 D CAR.SERVICE: Package validated; name: com.android.vending
,03-31 01:48:13.025   768  3974 I ActivityManager: Killing 3375:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
,03-31 01:48:13.055  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 01:48:13.058  3925  3996 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
,03-31 01:48:13.069  1433  4015 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-31 01:48:13.087   768   783 I ActivityManager: Start proc 4017:com.quickoffice.android/u0a65 for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver

```
