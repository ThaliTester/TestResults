#### Test 64613803f00187f_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
03-30 14:13:47.952   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 39756, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-30 14:13:47.978  3555  3629 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,--------- beginning of system
03-30 14:13:48.086   821  1414 I ActivityManager: Start proc 3633:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
03-30 14:13:48.088   821  1414 I ActivityManager: Killing 3019:com.google.android.partnersetup/u0a16 (adj 15): empty #17
03-30 14:13:48.246  1252  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-30 14:13:48.247  1252  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:13:48.247  1252  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:13:48.247  1252  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-30 14:13:48.252  1252  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-30 14:13:48.307  1252  2575 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-30 14:13:48.307  1252  2575 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:13:48.307  1252  2575 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:13:48.307  1252  2575 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-30 14:13:48.315  1252  2575 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-30 14:13:48.325  3555  3629 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-30 14:13:48.326  3555  3601 E BooksSync: Soft error
03-30 14:13:48.326  3555  3601 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-30 14:13:48.326  3555  3601 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-30 14:13:48.326  3555  3601 E BooksSync: Sync error
03-30 14:13:48.326  3555  3601 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-30 14:13:48.326  3555  3601 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-30 14:13:48.326  3555  3601 I BooksSync: Finished books sync
03-30 14:13:48.331   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39756, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-30 14:13:48.332   821  1101 I ActivityManager: Killing 3039:com.android.musicfx/u0a18 (adj 15): empty #17
03-30 14:13:48.335  3650  3650 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-30 14:13:48.338  3650  3650 D AndroidRuntime: CheckJNI is OFF
03-30 14:13:48.430  3650  3650 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-30 14:13:48.437   821  1379 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-30 14:13:48.443   821  1379 V WindowManager: addAppToken: AppWindowToken{6e9a89e token=Token{329e36d9 ActivityRecord{120d7d20 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-30 14:13:48.446  3650  3650 D AndroidRuntime: Shutting down VM
03-30 14:13:48.449  1512  1512 I HotwordDetector: Closing mic
03-30 14:13:48.450  1512  1764 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@24d4761f
03-30 14:13:48.479   821  1150 I ActivityManager: Start proc 3665:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-30 14:13:48.503   821   821 V ActivityManager: Display changed displayId=0
03-30 14:13:48.509   359  1772 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-30 14:13:48.510   359  1772 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-30 14:13:48.519   359  1030 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-30 14:13:48.523  1512  1765 I HotwordRecognitionRnr: Stopping hotword detection.
03-30 14:13:48.525  1512  1769 I HotwordRecognitionRnr: Hotword detection finished
03-30 14:13:48.557   821  1379 I ActivityManager: Killing 2463:android.process.acore/u0a5 (adj 15): empty #17
03-30 14:13:48.590  3665  3665 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-30 14:13:48.704   821  1271 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658295571
03-30 14:13:48.704   821  1271 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-30 14:13:48.765   821  1379 I ActivityManager: Killing 3089:com.google.android.apps.docs/u0a46 (adj 15): empty #18
03-30 14:13:49.011  3665  3665 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2575-2578)
03-30 14:13:49.011  3665  3665 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-30 14:13:49.057  3665  3665 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ab3bc24}
03-30 14:13:49.058  3665  3665 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-30 14:13:49.058  3665  3665 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-30 14:13:49.071  3665  3665 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-30 14:13:49.072  3665  3665 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-30 14:13:49.073  3665  3665 E SysUtils: ApplicationContext is null in ApplicationStatus
03-30 14:13:49.090  3665  3665 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-30 14:13:49.096  3665  3665 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-30 14:13:49.096  3665  3665 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-30 14:13:49.097  3665  3665 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-30 14:13:49.123  3132  3146 W art     : Suspending all threads took: 6.862ms
03-30 14:13:49.164   821  1322 I ActivityManager: Start proc 3697:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
03-30 14:13:49.165   821  1322 I ActivityManager: Killing 2833:com.google.android.gm/u0a78 (adj 15): empty #17
03-30 14:13:49.173   821   859 D BluetoothManagerService: Message: 20
03-30 14:13:49.173   821   859 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@579d038:true
03-30 14:13:49.461  3665  3665 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-30 14:13:49.472  3665  3665 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-30 14:13:49.488  3665  3665 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
03-30 14:13:49.494  3665  3665 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-30 14:13:49.494  3665  3665 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-30 14:13:49.549  3665  3732 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-30 14:13:49.553  3665  3665 D Atlas   : Validating map...
03-30 14:13:49.565   821  3580 V WindowManager: Adding window Window{23bad8b2 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 7 (after Window{1ee8888e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-30 14:13:49.567  3665  3707 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
03-30 14:13:49.609  3665  3732 I OpenGLRenderer: Initialized EGL, version 1.4
03-30 14:13:49.619  3665  3732 D OpenGLRenderer: Enabling debug mode 0
,03-30 14:13:49.672   821   860 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s225ms
,03-30 14:13:49.675  1235  1235 I Keyboard.Facilitator: onFinishInput()
,03-30 14:13:49.679  3665  3665 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3665
,03-30 14:13:49.692  3665  3665 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-30 14:13:49.761  3665  3665 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-30 14:13:49.878  3665  3733 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580590976
,03-30 14:13:49.881  3665  3733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-30 14:13:49.881  3665  3733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-30 14:13:49.881  3665  3733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-30 14:13:49.881  3665  3733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-30 14:13:49.881  3665  3733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-30 14:13:49.881  3665  3733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028269 added. We now have 1 listener(s)
,03-30 14:13:49.882   821  1418 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:13:49.884  3665  3733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-30 14:13:49.884  3665  3733 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:13:49.885  3665  3733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-30 14:13:49.885  3665  3733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-30 14:13:49.887  3665  3733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22d4781c added. We now have 1 listener(s)
03-30 14:13:49.887  3665  3733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-30 14:13:49.890   821  1011 D WifiService: New client listening to asynchronous messages
,03-30 14:13:49.893  3665  3733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-30 14:13:49.894  3665  3733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-30 14:13:49.894  3665  3733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-30 14:13:49.894  3665  3733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-30 14:13:49.894  3665  3733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-30 14:13:49.896  3665  3733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:13:49.897   821  1321 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:13:49.897  3665  3733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-30 14:13:49.902  3665  3733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:13:49.902  3665  3733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:13:49.902  3665  3733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:13:49.902  3665  3733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:13:49.902  3665  3733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:13:49.902  3665  3733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:13:49.902  3665  3733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:13:49.902  3665  3733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:13:49.902  3665  3733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-30 14:13:49.902  3665  3733 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-30 14:13:49.904  3665  3665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-30 14:13:49.904  3665  3733 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-30 14:13:49.906  3665  3665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-30 14:13:49.933  3665  3665 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-30 14:13:50.181   821  1418 I ActivityManager: Start proc 3745:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-30 14:13:50.199   821  1379 I ActivityManager: Killing 3060:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-30 14:13:50.210  3745  3745 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459340030210
,03-30 14:13:50.210  3745  3745 D         : TimeServiceNative: User Time to be set is 1459340030210
03-30 14:13:50.210  3745  3745 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
,03-30 14:13:50.210  3745  3745 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-30 14:13:50.210  3745  3745 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459340030210
03-30 14:13:50.211   374   880 D QC-time-services: Daemon: Connection accepted:time_genoff
03-30 14:13:50.211  3745  3745 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-30 14:13:50.211   374  3762 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459340030210
03-30 14:13:50.211   374  3762 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459340030210, operation = 0
03-30 14:13:50.211   374  3762 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/16/70 8:25:29
03-30 14:13:50.211   374  3762 D QC-time-services: Daemon:Value read from RTC seconds = 19643129000
03-30 14:13:50.211   374  3762 D QC-time-services: Daemon:new time 1459340030210 
03-30 14:13:50.211   374  3762 D QC-time-services: Daemon: delta 1439696901210 genoff 1439696901210 
03-30 14:13:50.211   374  3762 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901210 to memory
03-30 14:13:50.211   374  3762 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-30 14:13:50.211   374  3762 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-30 14:13:50.216   374  3762 D QC-time-services: Updating the TOD offset
03-30 14:13:50.216   374  3762 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901210 to memory
03-30 14:13:50.216   374  3762 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-30 14:13:50.216   374  3762 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-30 14:13:50.217   374  3762 E QC-time-services: Daemon:Update to modem bit set
03-30 14:13:50.217   374  3762 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
,03-30 14:13:50.217  3745  3745 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-30 14:13:50.217   374  3762 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143375230210
,03-30 14:13:50.286   374   880 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-30 14:13:50.292   374   878 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-30 14:13:50.425   821  3580 I ActivityManager: Start proc 3764:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-30 14:13:50.436   821  1411 I ActivityManager: Killing 3172:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-30 14:13:50.502  3665  3742 W jxcore-log: Initializing JXcore engine
03-30 14:13:50.502  3665  3742 W jxcore-log: JXcore engine is ready
,03-30 14:13:50.528  3742  3742 W Thread-390: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11671]" dev="sockfs" ino=11671 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-30 14:13:50.528  3742  3742 W Thread-390: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-30 14:13:50.528  3742  3742 W Thread-390: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9758]" dev="sockfs" ino=9758 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-30 14:13:50.528  3742  3742 W Thread-390: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21358]" dev="sockfs" ino=21358 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
,03-30 14:13:50.551  3665  3742 W jxcore-log: Starting JXcore engine
,03-30 14:13:50.634  3665  3742 W jxcore-log: Platform android
03-30 14:13:50.634  3665  3742 W jxcore-log: 
,03-30 14:13:50.635  3665  3742 W jxcore-log: Process ARCH arm
03-30 14:13:50.635  3665  3742 W jxcore-log: 
,03-30 14:13:50.699  3764  3764 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-30 14:13:50.699  3764  3764 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-30 14:13:50.699  3764  3764 I GAv4    :   adb logcat -s GAv4
,03-30 14:13:50.711  3764  3764 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-30 14:13:50.722  3764  3764 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-30 14:13:50.729  3764  3783 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-30 14:13:50.804   821  1418 I ActivityManager: Killing 2775:com.android.vending/u0a19 (adj 15): empty #17
,03-30 14:13:50.853  3665  3742 I jxcore-log: JXcore Cordova bridge is ready!
03-30 14:13:50.853  3665  3742 I jxcore-log: 
,03-30 14:13:50.853  3665  3742 W jxcore-log: JXcore engine is started
,03-30 14:13:50.862  3665  3733 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-30 14:13:50.863  3665  3665 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-30 14:13:51.043   821   840 I art     : Explicit concurrent mark sweep GC freed 16433(748KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.444ms total 64.601ms
,03-30 14:13:51.101  1774  1774 V Herrevad: NQAS connected
,03-30 14:13:51.121   821  1011 D WifiService: New client listening to asynchronous messages
,03-30 14:13:51.125  3200  3200 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-30 14:13:51.128  3200  3200 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 14:13:51.190   821  1414 I ActivityManager: Start proc 3794:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-30 14:13:51.204   371   371 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 13.407ms
,03-30 14:13:51.218  3794  3794 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-30 14:13:51.224   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 457us total 17.544ms
,03-30 14:13:51.244   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 330us total 18.881ms
,03-30 14:13:51.250  3794  3794 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@119ecb7(com.android.providers.calendar.CalendarProvider2@2ab3bc24)
,03-30 14:13:51.329  1252  2574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-30 14:13:51.329  1252  2574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:13:51.329  1252  2574 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:13:51.329  1252  2574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:13:51.332  1252  2574 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:51.339  3200  3791 E Babel   : UserRecoverableAuthException.
03-30 14:13:51.340  3200  3791 E Babel   : eei: BadAuthentication
03-30 14:13:51.340  3200  3791 E Babel   : 	at eeg.a(Unknown Source)
03-30 14:13:51.340  3200  3791 E Babel   : 	at eeg.a(Unknown Source)
03-30 14:13:51.340  3200  3791 E Babel   : 	at eeg.a(Unknown Source)
03-30 14:13:51.340  3200  3791 E Babel   : 	at g.a(Unknown Source)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cae.a(SourceFile:3089)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cae.a(SourceFile:1131)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cws.a(SourceFile:4333)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cws.a(SourceFile:1419)
03-30 14:13:51.340  3200  3791 E Babel   : 	at crl.a(SourceFile:492)
03-30 14:13:51.340  3200  3791 E Babel   : 	at crl.a(SourceFile:1468)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cqu.a(SourceFile:4416)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cas.b(SourceFile:106)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cap.d(SourceFile:335)
03-30 14:13:51.340  3200  3791 E Babel   : 	at caq.run(SourceFile:81)
03-30 14:13:51.340  3200  3791 E Babel   : Error getting auth token
03-30 14:13:51.340  3200  3791 E Babel   : dvm
03-30 14:13:51.340  3200  3791 E Babel   : 	at g.a(Unknown Source)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cae.a(SourceFile:3089)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cae.a(SourceFile:1131)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cws.a(SourceFile:4333)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cws.a(SourceFile:1419)
03-30 14:13:51.340  3200  3791 E Babel   : 	at crl.a(SourceFile:492)
03-30 14:13:51.340  3200  3791 E Babel   : 	at crl.a(SourceFile:1468)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cqu.a(SourceFile:4416)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cas.b(SourceFile:106)
03-30 14:13:51.340  3200  3791 E Babel   : 	at cap.d(SourceFile:335)
03-30 14:13:51.340  3200  3791 E Babel   : 	at caq.run(SourceFile:81)
,03-30 14:13:51.342  3200  3791 E Babel   : Account registration failed 1-Redacted-21
,03-30 14:13:51.343  3200  3791 E Babel   : cyp: null -- null
03-30 14:13:51.343  3200  3791 E Babel   : 	at cae.a(SourceFile:3121)
03-30 14:13:51.343  3200  3791 E Babel   : 	at cae.a(SourceFile:1131)
03-30 14:13:51.343  3200  3791 E Babel   : 	at cws.a(SourceFile:4333)
03-30 14:13:51.343  3200  3791 E Babel   : 	at cws.a(SourceFile:1419)
03-30 14:13:51.343  3200  3791 E Babel   : 	at crl.a(SourceFile:492)
03-30 14:13:51.343  3200  3791 E Babel   : 	at crl.a(SourceFile:1468)
03-30 14:13:51.343  3200  3791 E Babel   : 	at cqu.a(SourceFile:4416)
03-30 14:13:51.343  3200  3791 E Babel   : 	at cas.b(SourceFile:106)
03-30 14:13:51.343  3200  3791 E Babel   : 	at cap.d(SourceFile:335)
03-30 14:13:51.343  3200  3791 E Babel   : 	at caq.run(SourceFile:81)
,03-30 14:13:51.352  3200  3791 I art     : Note: end time exceeds epoch: 
,03-30 14:13:51.363  1252  2575 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-30 14:13:51.363  1252  2575 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:13:51.363  1252  2575 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:13:51.363  1252  2575 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:13:51.366  1252  2575 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:51.375  1252  2575 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-30 14:13:51.388  3200  3818 E Babel   : Unexpected exception while authenticating.
,03-30 14:13:51.389  3200  3818 E Babel   : eej: User intervention required. Notification has been pushed.
03-30 14:13:51.389  3200  3818 E Babel   : 	at eeg.b(Unknown Source)
03-30 14:13:51.389  3200  3818 E Babel   : 	at eeg.b(Unknown Source)
03-30 14:13:51.389  3200  3818 E Babel   : 	at g.a(Unknown Source)
03-30 14:13:51.389  3200  3818 E Babel   : 	at cae.b(SourceFile:1146)
03-30 14:13:51.389  3200  3818 E Babel   : 	at dcg.run(SourceFile:5617)
03-30 14:13:51.389  3200  3818 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:13:51.389  3200  3818 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:13:51.389  3200  3818 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-30 14:13:51.546  3794  3819 E SQLiteLog: (284) automatic index on view_events(_id)
,03-30 14:13:52.313  3794  3794 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-30 14:13:52.314  3794  3794 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-30 14:13:52.768  3555  3585 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-30 14:13:57.461   821  1418 I ActivityManager: Killing 2958:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-30 14:13:57.863   821  1101 I ActivityManager: Start proc 3828:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-30 14:13:58.003  1252  2574 I art     : Explicit concurrent mark sweep GC freed 20484(1214KB) AllocSpace objects, 5(362KB) LOS objects, 37% free, 26MB/42MB, paused 1.304ms total 45.230ms
,03-30 14:13:58.076  3828  3828 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-30 14:13:58.178  3828  3828 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-30 14:13:58.259   821  3580 I ActivityManager: Start proc 3865:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-30 14:13:58.285  3828  3828 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-30 14:13:58.287  3828  3828 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-30 14:13:58.302  3865  3865 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-30 14:13:58.302  3865  3865 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 14:13:58.320   821  1418 I ActivityManager: Killing 3409:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-30 14:13:58.328  3828  3843 D Finsky  : [389] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-30 14:13:58.332  3865  3865 I MultiDex: VM with version 2.1.0 has multidex support
03-30 14:13:58.332  3865  3865 I MultiDex: install
03-30 14:13:58.332  3865  3865 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-30 14:13:58.437  1252  1252 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:58.446  3828  3828 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-30 14:13:58.447  3828  3828 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-30 14:13:58.478  3865  3865 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-30 14:13:58.480  3828  3828 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-30 14:13:58.488  1252  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-30 14:13:58.489  1252  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:13:58.489  1252  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:13:58.489  1252  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:13:58.492  1252  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:58.512  3828  3828 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-30 14:13:58.521  3828  3843 D Finsky  : [389] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-30 14:13:58.546  3865  3865 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-30 14:13:58.549  1252  2112 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-30 14:13:58.553  1252  1252 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-30 14:13:58.557  1774  1774 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-30 14:13:58.595   821  1321 I ActivityManager: Start proc 3893:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-30 14:13:58.614  1774  3908 D LocationInitializer: Restart initialization of location
,03-30 14:13:58.626  3893  3893 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-30 14:13:58.626  3893  3893 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 14:13:58.664  3893  3893 I MultiDex: VM with version 2.1.0 has multidex support
03-30 14:13:58.664  3893  3893 I MultiDex: install
03-30 14:13:58.664  3893  3893 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-30 14:13:58.677  3893  3893 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-30 14:13:58.720  3893  3893 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-30 14:13:58.730  1252  1252 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
03-30 14:13:58.731  1252  2549 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-30 14:13:58.733  1774  1774 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-30 14:13:58.738  3893  3893 D WearableService: callingUid 10011, callindPid: 3893
,03-30 14:13:58.754  1844  2106 E MDM     : [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-30 14:13:58.758  1844  2106 E MDM     : [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-30 14:13:58.760  1774  3916 D LocationInitializer: Restart initialization of location
,03-30 14:13:58.860  3828  3828 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-30 14:13:59.191  3828  3828 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-30 14:13:59.233  1252  1252 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:59.267  1252  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-30 14:13:59.267  1252  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:13:59.268  1252  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:13:59.268  1252  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:13:59.271  1252  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:59.284  3828  3828 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-30 14:13:59.297  1252  1252 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:59.323  1252  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-30 14:13:59.323  1252  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:13:59.323  1252  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:13:59.323  1252  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:13:59.327  1252  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:59.355  1252  1252 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:59.450   821  1101 I art     : Explicit concurrent mark sweep GC freed 19719(1015KB) AllocSpace objects, 4(252KB) LOS objects, 32% free, 33MB/49MB, paused 1.769ms total 81.077ms
,03-30 14:13:59.482  1252  2573 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-30 14:13:59.482  1252  2573 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-30 14:13:59.482  1252  2573 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:13:59.482  1252  2573 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:13:59.486  1252  2573 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:59.494  3828  3828 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-30 14:13:59.673  1252  1252 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:59.743  1252  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-30 14:13:59.744  1252  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:13:59.744  1252  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:13:59.744  1252  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:13:59.755  1252  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:13:59.791  3828  3828 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-30 14:13:59.794  3828  3828 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-30 14:13:59.802  3828  3828 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-30 14:13:59.805  3828  3828 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 756 minutes (failures=5)
,03-30 14:13:59.831  1844  1900 D DeviceConnectionService: client connected with version: 7571000
,03-30 14:14:00.466  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:14:00.466  3665  3742 I jxcore-log: 
,03-30 14:14:00.469  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:14:00.469  3665  3742 I jxcore-log: 
,03-30 14:14:00.476  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:14:00.476  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:14:00.476  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:14:00.476  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:14:00.476  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:14:00.476  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
03-30 14:14:00.476  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:14:00.476  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:14:00.479  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:14:00.486  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:14:00.486  3665  3742 I jxcore-log: 
,03-30 14:14:00.492  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:14:00.492  3665  3742 I jxcore-log: 
,03-30 14:14:01.031  3665  3742 I jxcore-log: Unit Test app is loaded
03-30 14:14:01.031  3665  3742 I jxcore-log: 
,03-30 14:14:01.036  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:14:01.036  3665  3742 I jxcore-log: 
,03-30 14:14:01.044  3665  3742 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-30 14:14:01.046  3665  3742 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-30 14:14:01.046  3665  3742 I jxcore-log: 
,03-30 14:14:01.047  3665  3742 I jxcore-log: My device name is: motorola-Nexus 6,
03-30 14:14:01.047  3665  3742 I jxcore-log: 
,03-30 14:14:01.061  3665  3665 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74),
,03-30 14:14:03.770   821  1101 I ActivityManager: Killing 3359:com.google.android.youtube/u0a86 (adj 15): empty #17
,03-30 14:14:04.015  2152  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-30 14:14:04.033   821  1322 I ActivityManager: Killing 3499:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-30 14:14:04.733  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-30 14:14:04.733  3665  3742 I jxcore-log: 
,03-30 14:14:05.096  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-30 14:14:05.096  3665  3742 I jxcore-log: 
,03-30 14:14:05.109  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,03-30 14:14:05.109  3665  3742 I jxcore-log: 
,03-30 14:14:05.114  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-30 14:14:05.114  3665  3742 I jxcore-log: 
,03-30 14:14:05.151  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
03-30 14:14:05.151  3665  3742 I jxcore-log: 
,03-30 14:14:05.168  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-30 14:14:05.168  3665  3742 I jxcore-log: ,
,03-30 14:14:05.173  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-30 14:14:05.173  3665  3742 I jxcore-log: 
,03-30 14:14:07.097  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-30 14:14:07.097  3665  3742 I jxcore-log: 
,03-30 14:14:07.115  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-30 14:14:07.115  3665  3742 I jxcore-log: 
,03-30 14:14:07.124  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-30 14:14:07.124  3665  3742 I jxcore-log: 
,03-30 14:14:07.368  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-30 14:14:07.368  3665  3742 I jxcore-log: 
,03-30 14:14:07.438  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-30 14:14:07.438  3665  3742 I jxcore-log: 
,03-30 14:14:07.493  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-30 14:14:07.493  3665  3742 I jxcore-log: 
,03-30 14:14:07.500  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-30 14:14:07.500  3665  3742 I jxcore-log: 
,03-30 14:14:07.510  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-30 14:14:07.510  3665  3742 I jxcore-log: 
,03-30 14:14:07.515  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-30 14:14:07.515  3665  3742 I jxcore-log: 
,03-30 14:14:07.521  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-30 14:14:07.521  3665  3742 I jxcore-log: 
,03-30 14:14:07.537  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-30 14:14:07.537  3665  3742 I jxcore-log: 
,03-30 14:14:07.557  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-30 14:14:07.557  3665  3742 I jxcore-log: 
,03-30 14:14:07.639  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-30 14:14:07.639  3665  3742 I jxcore-log: 
,03-30 14:14:07.645  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-30 14:14:07.645  3665  3742 I jxcore-log: 
,03-30 14:14:07.671  3665  3742 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-30 14:14:07.671  3665  3742 I jxcore-log: ,
,03-30 14:14:08.878  3665  3742 I jxcore-log: TAP version 13
03-30 14:14:08.878  3665  3742 I jxcore-log: 
,03-30 14:14:08.880  3665  3742 I jxcore-log: # setup
03-30 14:14:08.880  3665  3742 I jxcore-log: 
,03-30 14:14:09.105  3665  3742 I jxcore-log: # 1. calling createNativeListener directly rejects
03-30 14:14:09.105  3665  3742 I jxcore-log: 
,03-30 14:14:09.260  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:09.260  3665  3742 I jxcore-log: 
,03-30 14:14:09.265  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 41226
03-30 14:14:09.265  3665  3742 I jxcore-log: 
,03-30 14:14:09.271  3665  3742 I jxcore-log: ok 1 Should throw
03-30 14:14:09.271  3665  3742 I jxcore-log: 
,03-30 14:14:09.273  3665  3742 I jxcore-log: # teardown
03-30 14:14:09.273  3665  3742 I jxcore-log: 
,03-30 14:14:09.420  3665  3742 I jxcore-log: # setup
03-30 14:14:09.420  3665  3742 I jxcore-log: 
,03-30 14:14:09.529  3665  3742 I jxcore-log: # 2. emits incomingConnectionState
03-30 14:14:09.529  3665  3742 I jxcore-log: 
,03-30 14:14:09.700  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:09.700  3665  3742 I jxcore-log: 
,03-30 14:14:09.704  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 40669
03-30 14:14:09.704  3665  3742 I jxcore-log: 
,03-30 14:14:09.713  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:09.713  3665  3742 I jxcore-log: 
,03-30 14:14:09.717  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:09.717  3665  3742 I jxcore-log: 
,03-30 14:14:09.726  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:09.726  3665  3742 I jxcore-log: 
,03-30 14:14:09.731  3665  3742 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-30 14:14:09.731  3665  3742 I jxcore-log: 
,03-30 14:14:09.746  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:09.746  3665  3742 I jxcore-log: 
03-30 14:14:09.747  3665  3742 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-30 14:14:09.747  3665  3742 I jxcore-log: 
,03-30 14:14:09.755  3665  3742 I jxcore-log: # teardown
03-30 14:14:09.755  3665  3742 I jxcore-log: 
,03-30 14:14:09.850  3665  3742 I jxcore-log: # setup
03-30 14:14:09.850  3665  3742 I jxcore-log: 
,03-30 14:14:10.032  3665  3742 I jxcore-log: # 3. emits routerPortConnectionFailed
03-30 14:14:10.032  3665  3742 I jxcore-log: 
,03-30 14:14:10.205  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:10.205  3665  3742 I jxcore-log: 
,03-30 14:14:10.208  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 58659
03-30 14:14:10.208  3665  3742 I jxcore-log: 
,03-30 14:14:10.214  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:10.214  3665  3742 I jxcore-log: 
03-30 14:14:10.215  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:10.215  3665  3742 I jxcore-log: 
,03-30 14:14:10.216  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:10.216  3665  3742 I jxcore-log: 
,03-30 14:14:10.242  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:10.242  3665  3742 I jxcore-log: 
03-30 14:14:10.244  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:10.244  3665  3742 I jxcore-log: 
03-30 14:14:10.248  3665  3742 I jxcore-log: DEBUG createNativeListener: 
03-30 14:14:10.248  3665  3742 I jxcore-log: 
03-30 14:14:10.249  3665  3742 I jxcore-log: ok 4 tried to connect to right port
03-30 14:14:10.249  3665  3742 I jxcore-log: 
03-30 14:14:10.250  3665  3742 I jxcore-log: ok 5 failed due to refused connection
03-30 14:14:10.250  3665  3742 I jxcore-log: 
03-30 14:14:10.250  3665  3742 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-30 14:14:10.250  3665  3742 I jxcore-log: 
03-30 14:14:10.254  3665  3742 I jxcore-log: # teardown
03-30 14:14:10.254  3665  3742 I jxcore-log: 
03-30 14:14:10.256  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:10.256  3665  3742 I jxcore-log: 
,03-30 14:14:10.419  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:10.419  3665  3742 I jxcore-log: 
,03-30 14:14:10.425  3665  3742 I jxcore-log: # setup
03-30 14:14:10.425  3665  3742 I jxcore-log: 
,03-30 14:14:10.426  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:10.426  3665  3742 I jxcore-log: 
,03-30 14:14:10.676  3665  3742 I jxcore-log: # 4. native server connections all up
03-30 14:14:10.676  3665  3742 I jxcore-log: 
,03-30 14:14:10.802  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:10.802  3665  3742 I jxcore-log: 
,03-30 14:14:10.812  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 37821
03-30 14:14:10.812  3665  3742 I jxcore-log: 
,03-30 14:14:10.820  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:10.820  3665  3742 I jxcore-log: 
,03-30 14:14:10.822  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:10.822  3665  3742 I jxcore-log: 
,03-30 14:14:10.823  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:10.823  3665  3742 I jxcore-log: 
,03-30 14:14:10.850  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:10.850  3665  3742 I jxcore-log: 
,03-30 14:14:10.855  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:10.855  3665  3742 I jxcore-log: 
,03-30 14:14:10.858  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:10.858  3665  3742 I jxcore-log: 
,03-30 14:14:10.860  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:10.860  3665  3742 I jxcore-log: 
,03-30 14:14:10.889  3665  3742 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-30 14:14:10.889  3665  3742 I jxcore-log: 
,03-30 14:14:10.889  3665  3742 I jxcore-log: ok 8 Send/recvd #1 should be same
03-30 14:14:10.889  3665  3742 I jxcore-log: 
,03-30 14:14:10.892  3665  3742 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-30 14:14:10.892  3665  3742 I jxcore-log: 
03-30 14:14:10.892  3665  3742 I jxcore-log: ok 10 Send/recvd #2 should be same
03-30 14:14:10.892  3665  3742 I jxcore-log: 
,03-30 14:14:10.895  3665  3742 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-30 14:14:10.895  3665  3742 I jxcore-log: 
,03-30 14:14:10.903  3665  3742 I jxcore-log: # teardown
03-30 14:14:10.903  3665  3742 I jxcore-log: 
,03-30 14:14:11.095  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:11.095  3665  3742 I jxcore-log: 
,03-30 14:14:11.098  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:11.098  3665  3742 I jxcore-log: 
,03-30 14:14:11.100  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:11.100  3665  3742 I jxcore-log: 
03-30 14:14:11.104  3665  3742 I jxcore-log: # setup
03-30 14:14:11.104  3665  3742 I jxcore-log: 
,03-30 14:14:11.105  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:11.105  3665  3742 I jxcore-log: 
,03-30 14:14:11.275  3665  3742 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-30 14:14:11.275  3665  3742 I jxcore-log: 
,03-30 14:14:11.356  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:11.356  3665  3742 I jxcore-log: 
,03-30 14:14:11.359  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 58467
03-30 14:14:11.359  3665  3742 I jxcore-log: 
,03-30 14:14:11.366  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:11.366  3665  3742 I jxcore-log: 
,03-30 14:14:11.367  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:11.367  3665  3742 I jxcore-log: 
,03-30 14:14:11.368  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:11.368  3665  3742 I jxcore-log: 
,03-30 14:14:11.381  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:11.381  3665  3742 I jxcore-log: ,
,03-30 14:14:11.384  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:11.384  3665  3742 I jxcore-log: 
,03-30 14:14:11.397  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:11.397  3665  3742 I jxcore-log: 
,03-30 14:14:11.410  3665  3742 I jxcore-log: ok 12 socket shouldn't close until after stream
03-30 14:14:11.410  3665  3742 I jxcore-log: 
,03-30 14:14:11.411  3665  3742 I jxcore-log: ok 13 incoming remains open
03-30 14:14:11.411  3665  3742 I jxcore-log: 
,03-30 14:14:11.418  3665  3742 I jxcore-log: # teardown
03-30 14:14:11.418  3665  3742 I jxcore-log: 
,03-30 14:14:11.557  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:11.557  3665  3742 I jxcore-log: 
,03-30 14:14:11.563  3665  3742 I jxcore-log: # setup
03-30 14:14:11.563  3665  3742 I jxcore-log: 
,03-30 14:14:11.564  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:11.564  3665  3742 I jxcore-log: 
,03-30 14:14:11.737  3665  3742 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-30 14:14:11.737  3665  3742 I jxcore-log: 
,03-30 14:14:11.874  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:11.874  3665  3742 I jxcore-log: 
,03-30 14:14:11.877  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 46336
03-30 14:14:11.877  3665  3742 I jxcore-log: 
,03-30 14:14:11.886  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:11.886  3665  3742 I jxcore-log: 
,03-30 14:14:11.889  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:11.889  3665  3742 I jxcore-log: 
,03-30 14:14:11.893  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
,03-30 14:14:11.893  3665  3742 I jxcore-log: 
,03-30 14:14:11.916  3665  3742 I jxcore-log: ok 14 we should not have gotten an error
03-30 14:14:11.916  3665  3742 I jxcore-log: 
,03-30 14:14:11.921  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:11.921  3665  3742 I jxcore-log: 
,03-30 14:14:11.926  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:11.926  3665  3742 I jxcore-log: 
,03-30 14:14:11.936  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:11.936  3665  3742 I jxcore-log: 
,03-30 14:14:11.939  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:11.939  3665  3742 I jxcore-log: 
,03-30 14:14:11.948  3665  3742 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-30 14:14:11.948  3665  3742 I jxcore-log: 
,03-30 14:14:11.948  3665  3742 I jxcore-log: ok 16 incoming is cleaned up
03-30 14:14:11.948  3665  3742 I jxcore-log: 
,03-30 14:14:11.955  3665  3742 I jxcore-log: # teardown
03-30 14:14:11.955  3665  3742 I jxcore-log: 
,03-30 14:14:12.076  3665  3742 I jxcore-log: # setup
03-30 14:14:12.076  3665  3742 I jxcore-log: 
,03-30 14:14:12.165  3665  3742 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-30 14:14:12.165  3665  3742 I jxcore-log: 
,03-30 14:14:12.346  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:12.346  3665  3742 I jxcore-log: 
,03-30 14:14:12.355  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 54679
03-30 14:14:12.355  3665  3742 I jxcore-log: 
,03-30 14:14:12.360  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:12.360  3665  3742 I jxcore-log: 
,03-30 14:14:12.361  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:12.361  3665  3742 I jxcore-log: 
,03-30 14:14:12.364  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:12.364  3665  3742 I jxcore-log: 
,03-30 14:14:12.376  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:12.376  3665  3742 I jxcore-log: 
,03-30 14:14:12.378  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:12.378  3665  3742 I jxcore-log: 
,03-30 14:14:12.392  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:12.392  3665  3742 I jxcore-log: 
,03-30 14:14:12.402  3665  3742 I jxcore-log: ok 17 stream was closed
03-30 14:14:12.402  3665  3742 I jxcore-log: 
,03-30 14:14:12.402  3665  3742 I jxcore-log: ok 18 incoming should survive
03-30 14:14:12.402  3665  3742 I jxcore-log: 
03-30 14:14:12.403  3665  3742 I jxcore-log: ok 19 mux should have no streams
03-30 14:14:12.403  3665  3742 I jxcore-log: 
,03-30 14:14:12.410  3665  3742 I jxcore-log: # teardown
03-30 14:14:12.410  3665  3742 I jxcore-log: 
,03-30 14:14:12.789  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close,
03-30 14:14:12.789  3665  3742 I jxcore-log: 
,03-30 14:14:12.809  3665  3742 I jxcore-log: # setup,
03-30 14:14:12.809  3665  3742 I jxcore-log: 
,03-30 14:14:12.812  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:12.812  3665  3742 I jxcore-log: 
,03-30 14:14:12.916  3665  3742 I jxcore-log: # 8. native server - closing the whole server cleans everything up,
03-30 14:14:12.916  3665  3742 I jxcore-log: 
,03-30 14:14:13.359  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server,
03-30 14:14:13.359  3665  3742 I jxcore-log: 
,03-30 14:14:13.370  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 42177,
03-30 14:14:13.370  3665  3742 I jxcore-log: 
,03-30 14:14:13.380  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-30 14:14:13.380  3665  3742 I jxcore-log: 
03-30 14:14:13.381  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.381  3665  3742 I jxcore-log: 
,03-30 14:14:13.383  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.383  3665  3742 I jxcore-log: 
,03-30 14:14:13.393  3665  3742 I jxcore-log: ok 20 we should not have gotten an error
03-30 14:14:13.393  3665  3742 I jxcore-log: 
,03-30 14:14:13.399  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:13.399  3665  3742 I jxcore-log: 
,03-30 14:14:13.402  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:13.402  3665  3742 I jxcore-log: 
,03-30 14:14:13.414  3665  3742 I jxcore-log: ok 21 Buffers are identical
03-30 14:14:13.414  3665  3742 I jxcore-log: 
,03-30 14:14:13.416  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:13.416  3665  3742 I jxcore-log: 
,03-30 14:14:13.420  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:13.420  3665  3742 I jxcore-log: 
,03-30 14:14:13.424  3665  3742 I jxcore-log: ok 22 native server is nulled out
03-30 14:14:13.424  3665  3742 I jxcore-log: 
,03-30 14:14:13.424  3665  3742 I jxcore-log: ok 23 native server should be closed,
03-30 14:14:13.424  3665  3742 I jxcore-log: 
03-30 14:14:13.424  3665  3742 I jxcore-log: ok 24 incoming has been removed
03-30 14:14:13.424  3665  3742 I jxcore-log: 
,03-30 14:14:13.425  3665  3742 I jxcore-log: ok 25 Incoming should be done
03-30 14:14:13.425  3665  3742 I jxcore-log: 
03-30 14:14:13.425  3665  3742 I jxcore-log: ok 26 The mux object should be closed
03-30 14:14:13.425  3665  3742 I jxcore-log: 
03-30 14:14:13.425  3665  3742 I jxcore-log: ok 27 The mux stream should be closed
03-30 14:14:13.425  3665  3742 I jxcore-log: 
,03-30 14:14:13.426  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:13.426  3665  3742 I jxcore-log: 
,03-30 14:14:13.442  3665  3742 I jxcore-log: # teardown
03-30 14:14:13.442  3665  3742 I jxcore-log: 
,03-30 14:14:13.535  3665  3742 I jxcore-log: # setup
03-30 14:14:13.535  3665  3742 I jxcore-log: 
,03-30 14:14:13.737  3665  3742 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-30 14:14:13.737  3665  3742 I jxcore-log: 
,03-30 14:14:13.940  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:13.940  3665  3742 I jxcore-log: 
,03-30 14:14:13.944  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 36639
03-30 14:14:13.944  3665  3742 I jxcore-log: 
,03-30 14:14:13.964  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.964  3665  3742 I jxcore-log: 
,03-30 14:14:13.965  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.965  3665  3742 I jxcore-log: 
,03-30 14:14:13.967  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.967  3665  3742 I jxcore-log: 
,03-30 14:14:13.970  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.970  3665  3742 I jxcore-log: 
,03-30 14:14:13.971  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.971  3665  3742 I jxcore-log: 
,03-30 14:14:13.972  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.972  3665  3742 I jxcore-log: 
,03-30 14:14:13.975  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.975  3665  3742 I jxcore-log: 
,03-30 14:14:13.976  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.976  3665  3742 I jxcore-log: 
,03-30 14:14:13.977  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.977  3665  3742 I jxcore-log: 
03-30 14:14:13.980  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.980  3665  3742 I jxcore-log: 
,03-30 14:14:13.981  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.981  3665  3742 I jxcore-log: 
,03-30 14:14:13.982  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.982  3665  3742 I jxcore-log: 
,03-30 14:14:13.985  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.985  3665  3742 I jxcore-log: 
03-30 14:14:13.986  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.986  3665  3742 I jxcore-log: 
,03-30 14:14:13.987  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.987  3665  3742 I jxcore-log: 
,03-30 14:14:13.989  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.989  3665  3742 I jxcore-log: 
03-30 14:14:13.989  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.989  3665  3742 I jxcore-log: 
03-30 14:14:13.990  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.990  3665  3742 I jxcore-log: 
,03-30 14:14:13.992  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.992  3665  3742 I jxcore-log: 
03-30 14:14:13.993  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.993  3665  3742 I jxcore-log: 
03-30 14:14:13.994  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.994  3665  3742 I jxcore-log: 
,03-30 14:14:13.996  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.996  3665  3742 I jxcore-log: 
03-30 14:14:13.997  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.997  3665  3742 I jxcore-log: 
03-30 14:14:13.998  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.998  3665  3742 I jxcore-log: 
,03-30 14:14:14.000  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:14.000  3665  3742 I jxcore-log: 
03-30 14:14:14.001  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:14.001  3665  3742 I jxcore-log: 
03-30 14:14:14.002  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:14.002  3665  3742 I jxcore-log: 
,03-30 14:14:14.004  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:14.004  3665  3742 I jxcore-log: 
03-30 14:14:14.004  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:14.004  3665  3742 I jxcore-log: 
03-30 14:14:14.005  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:14.005  3665  3742 I jxcore-log: 
,03-30 14:14:14.096  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.096  3665  3742 I jxcore-log: 
,03-30 14:14:14.099  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.099  3665  3742 I jxcore-log: 
,03-30 14:14:14.101  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.101  3665  3742 I jxcore-log: 
,03-30 14:14:14.104  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.104  3665  3742 I jxcore-log: 
,03-30 14:14:14.105  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.105  3665  3742 I jxcore-log: 
,03-30 14:14:14.106  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.106  3665  3742 I jxcore-log: 
,03-30 14:14:14.108  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.108  3665  3742 I jxcore-log: 
,03-30 14:14:14.110  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.110  3665  3742 I jxcore-log: 
,03-30 14:14:14.112  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.112  3665  3742 I jxcore-log: 
,03-30 14:14:14.114  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.114  3665  3742 I jxcore-log: 
,03-30 14:14:14.116  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.116  3665  3742 I jxcore-log: 
,03-30 14:14:14.117  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.117  3665  3742 I jxcore-log: 
,03-30 14:14:14.118  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.118  3665  3742 I jxcore-log: 
,03-30 14:14:14.120  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.120  3665  3742 I jxcore-log: 
,03-30 14:14:14.121  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.121  3665  3742 I jxcore-log: 
,03-30 14:14:14.123  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.123  3665  3742 I jxcore-log: 
,03-30 14:14:14.125  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.125  3665  3742 I jxcore-log: 
,03-30 14:14:14.126  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.126  3665  3742 I jxcore-log: 
,03-30 14:14:14.127  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.127  3665  3742 I jxcore-log: 
,03-30 14:14:14.129  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.129  3665  3742 I jxcore-log: 
,03-30 14:14:14.130  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.130  3665  3742 I jxcore-log: 
,03-30 14:14:14.134  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.134  3665  3742 I jxcore-log: 
,03-30 14:14:14.136  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.136  3665  3742 I jxcore-log: 
,03-30 14:14:14.138  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.138  3665  3742 I jxcore-log: 
,03-30 14:14:14.139  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.139  3665  3742 I jxcore-log: 
,03-30 14:14:14.141  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.141  3665  3742 I jxcore-log: 
,03-30 14:14:14.142  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.142  3665  3742 I jxcore-log: 
,03-30 14:14:14.143  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.143  3665  3742 I jxcore-log: 
,03-30 14:14:14.145  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.145  3665  3742 I jxcore-log: 
,03-30 14:14:14.146  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.146  3665  3742 I jxcore-log: 
,03-30 14:14:14.147  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.147  3665  3742 I jxcore-log: 
,03-30 14:14:14.148  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.148  3665  3742 I jxcore-log: 
,03-30 14:14:14.150  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.150  3665  3742 I jxcore-log: 
,03-30 14:14:14.152  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.152  3665  3742 I jxcore-log: 
,03-30 14:14:14.153  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.153  3665  3742 I jxcore-log: 
,03-30 14:14:14.154  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.154  3665  3742 I jxcore-log: 
,03-30 14:14:14.155  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.155  3665  3742 I jxcore-log: 
,03-30 14:14:14.157  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.157  3665  3742 I jxcore-log: 
,03-30 14:14:14.158  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.158  3665  3742 I jxcore-log: 
,03-30 14:14:14.159  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.159  3665  3742 I jxcore-log: 
,03-30 14:14:14.161  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.161  3665  3742 I jxcore-log: 
,03-30 14:14:14.162  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.162  3665  3742 I jxcore-log: 
,03-30 14:14:14.163  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.163  3665  3742 I jxcore-log: 
,03-30 14:14:14.165  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.165  3665  3742 I jxcore-log: 
,03-30 14:14:14.166  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.166  3665  3742 I jxcore-log: 
,03-30 14:14:14.167  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.167  3665  3742 I jxcore-log: 
,03-30 14:14:14.168  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.168  3665  3742 I jxcore-log: 
,03-30 14:14:14.170  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.170  3665  3742 I jxcore-log: 
,03-30 14:14:14.178  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.178  3665  3742 I jxcore-log: 
,03-30 14:14:14.179  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.179  3665  3742 I jxcore-log: 
,03-30 14:14:14.180  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.180  3665  3742 I jxcore-log: 
,03-30 14:14:14.182  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.182  3665  3742 I jxcore-log: 
,03-30 14:14:14.183  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.183  3665  3742 I jxcore-log: 
,03-30 14:14:14.184  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.184  3665  3742 I jxcore-log: 
,03-30 14:14:14.185  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.185  3665  3742 I jxcore-log: 
,03-30 14:14:14.187  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.187  3665  3742 I jxcore-log: 
,03-30 14:14:14.189  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.189  3665  3742 I jxcore-log: 
,03-30 14:14:14.191  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.191  3665  3742 I jxcore-log: 
,03-30 14:14:14.192  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.192  3665  3742 I jxcore-log: 
,03-30 14:14:14.194  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.194  3665  3742 I jxcore-log: 
,03-30 14:14:14.195  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.195  3665  3742 I jxcore-log: 
,03-30 14:14:14.197  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.197  3665  3742 I jxcore-log: 
,03-30 14:14:14.198  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.198  3665  3742 I jxcore-log: 
,03-30 14:14:14.199  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.199  3665  3742 I jxcore-log: 
,03-30 14:14:14.201  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.201  3665  3742 I jxcore-log: 
,03-30 14:14:14.202  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.202  3665  3742 I jxcore-log: 
,03-30 14:14:14.204  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.204  3665  3742 I jxcore-log: 
,03-30 14:14:14.205  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.205  3665  3742 I jxcore-log: 
,03-30 14:14:14.206  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.206  3665  3742 I jxcore-log: 
,03-30 14:14:14.208  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.208  3665  3742 I jxcore-log: 
,03-30 14:14:14.209  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.209  3665  3742 I jxcore-log: 
,03-30 14:14:14.210  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.210  3665  3742 I jxcore-log: 
,03-30 14:14:14.212  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.212  3665  3742 I jxcore-log: 
,03-30 14:14:14.216  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.216  3665  3742 I jxcore-log: 
,03-30 14:14:14.218  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.218  3665  3742 I jxcore-log: 
,03-30 14:14:14.219  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.219  3665  3742 I jxcore-log: 
,03-30 14:14:14.220  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.220  3665  3742 I jxcore-log: 
,03-30 14:14:14.222  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.222  3665  3742 I jxcore-log: 
,03-30 14:14:14.223  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.223  3665  3742 I jxcore-log: 
,03-30 14:14:14.224  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.224  3665  3742 I jxcore-log: 
,03-30 14:14:14.300  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.300  3665  3742 I jxcore-log: 
,03-30 14:14:14.301  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.301  3665  3742 I jxcore-log: 
03-30 14:14:14.302  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.302  3665  3742 I jxcore-log: 
,03-30 14:14:14.304  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.304  3665  3742 I jxcore-log: 
,03-30 14:14:14.306  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.306  3665  3742 I jxcore-log: 
,03-30 14:14:14.307  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.307  3665  3742 I jxcore-log: 
,03-30 14:14:14.308  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.308  3665  3742 I jxcore-log: 
03-30 14:14:14.309  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.309  3665  3742 I jxcore-log: 
,03-30 14:14:14.310  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.310  3665  3742 I jxcore-log: 
,03-30 14:14:14.311  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.311  3665  3742 I jxcore-log: 
03-30 14:14:14.313  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.313  3665  3742 I jxcore-log: 
03-30 14:14:14.314  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.314  3665  3742 I jxcore-log: 
,03-30 14:14:14.315  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.315  3665  3742 I jxcore-log: 
,03-30 14:14:14.316  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.316  3665  3742 I jxcore-log: 
,03-30 14:14:14.318  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.318  3665  3742 I jxcore-log: 
,03-30 14:14:14.319  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.319  3665  3742 I jxcore-log: 
03-30 14:14:14.320  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.320  3665  3742 I jxcore-log: 
,03-30 14:14:14.321  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.321  3665  3742 I jxcore-log: 
,03-30 14:14:14.321  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.321  3665  3742 I jxcore-log: 
03-30 14:14:14.322  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.322  3665  3742 I jxcore-log: 
,03-30 14:14:14.323  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.323  3665  3742 I jxcore-log: 
,03-30 14:14:14.324  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.324  3665  3742 I jxcore-log: 
,03-30 14:14:14.325  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.325  3665  3742 I jxcore-log: 
,03-30 14:14:14.326  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.326  3665  3742 I jxcore-log: 
03-30 14:14:14.327  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.327  3665  3742 I jxcore-log: 
,03-30 14:14:14.328  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.328  3665  3742 I jxcore-log: 
,03-30 14:14:14.329  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.329  3665  3742 I jxcore-log: 
,03-30 14:14:14.330  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.330  3665  3742 I jxcore-log: 
,03-30 14:14:14.330  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.330  3665  3742 I jxcore-log: 
03-30 14:14:14.331  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.331  3665  3742 I jxcore-log: 
,03-30 14:14:14.332  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.332  3665  3742 I jxcore-log: 
,03-30 14:14:14.333  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.333  3665  3742 I jxcore-log: 
03-30 14:14:14.334  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.334  3665  3742 I jxcore-log: 
,03-30 14:14:14.335  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.335  3665  3742 I jxcore-log: 
03-30 14:14:14.336  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.336  3665  3742 I jxcore-log: 
,03-30 14:14:14.337  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.337  3665  3742 I jxcore-log: 
03-30 14:14:14.338  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.338  3665  3742 I jxcore-log: 
03-30 14:14:14.338  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.338  3665  3742 I jxcore-log: 
,03-30 14:14:14.339  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.339  3665  3742 I jxcore-log: 
,03-30 14:14:14.340  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.340  3665  3742 I jxcore-log: 
03-30 14:14:14.341  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.341  3665  3742 I jxcore-log: 
,03-30 14:14:14.342  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.342  3665  3742 I jxcore-log: 
03-30 14:14:14.342  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.342  3665  3742 I jxcore-log: 
,03-30 14:14:14.343  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.343  3665  3742 I jxcore-log: 
,03-30 14:14:14.344  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.344  3665  3742 I jxcore-log: 
03-30 14:14:14.345  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.345  3665  3742 I jxcore-log: 
,03-30 14:14:14.346  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.346  3665  3742 I jxcore-log: 
03-30 14:14:14.347  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.347  3665  3742 I jxcore-log: 
,03-30 14:14:14.347  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.347  3665  3742 I jxcore-log: 
03-30 14:14:14.348  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.348  3665  3742 I jxcore-log: 
03-30 14:14:14.351  3665  3742 I jxcore-log: ok 28 native server is nulled out
03-30 14:14:14.351  3665  3742 I jxcore-log: 
03-30 14:14:14.352  3665  3742 I jxcore-log: ok 29 native server should be closed
03-30 14:14:14.352  3665  3742 I jxcore-log: 
03-30 14:14:14.352  3665  3742 I jxcore-log: ok 30 incoming has been removed
03-30 14:14:14.352  3665  3742 I jxcore-log: 
,03-30 14:14:14.356  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.356  3665  3742 I jxcore-log: 
,03-30 14:14:14.360  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.360  3665  3742 I jxcore-log: 
,03-30 14:14:14.362  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.362  3665  3742 I jxcore-log: 
,03-30 14:14:14.365  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.365  3665  3742 I jxcore-log: 
,03-30 14:14:14.368  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.368  3665  3742 I jxcore-log: 
,03-30 14:14:14.370  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.370  3665  3742 I jxcore-log: 
,03-30 14:14:14.372  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.372  3665  3742 I jxcore-log: 
,03-30 14:14:14.373  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.373  3665  3742 I jxcore-log: 
03-30 14:14:14.374  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.374  3665  3742 I jxcore-log: 
,03-30 14:14:14.375  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.375  3665  3742 I jxcore-log: 
,03-30 14:14:14.488  3665  3742 I jxcore-log: # teardown
03-30 14:14:14.488  3665  3742 I jxcore-log: 
,03-30 14:14:14.551  3665  3742 I jxcore-log: # setup
03-30 14:14:14.551  3665  3742 I jxcore-log: ,
,03-30 14:14:14.735  3665  3742 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-30 14:14:14.735  3665  3742 I jxcore-log: 
,03-30 14:14:14.855  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:14.855  3665  3742 I jxcore-log: 
,03-30 14:14:14.858  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 36237
03-30 14:14:14.858  3665  3742 I jxcore-log: 
,03-30 14:14:14.867  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:14.867  3665  3742 I jxcore-log: 
,03-30 14:14:14.870  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:14.870  3665  3742 I jxcore-log: 
,03-30 14:14:14.872  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:14.872  3665  3742 I jxcore-log: 
,03-30 14:14:14.880  3665  3742 I jxcore-log: ok 31 we should not have gotten an error
03-30 14:14:14.880  3665  3742 I jxcore-log: 
,03-30 14:14:14.884  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.884  3665  3742 I jxcore-log: 
,03-30 14:14:14.887  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.887  3665  3742 I jxcore-log: 
,03-30 14:14:14.895  3665  3742 I jxcore-log: ok 32 Buffers are identical
03-30 14:14:14.895  3665  3742 I jxcore-log: 
03-30 14:14:14.895  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.895  3665  3742 I jxcore-log: 
,03-30 14:14:14.897  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.897  3665  3742 I jxcore-log: 
,03-30 14:14:14.909  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.909  3665  3742 I jxcore-log: 
03-30 14:14:14.910  3665  3742 I jxcore-log: ok 33 server should be fine
03-30 14:14:14.910  3665  3742 I jxcore-log: 
,03-30 14:14:14.910  3665  3742 I jxcore-log: ok 34 server should be open
03-30 14:14:14.910  3665  3742 I jxcore-log: 
03-30 14:14:14.911  3665  3742 I jxcore-log: ok 35 incoming has been removed
03-30 14:14:14.911  3665  3742 I jxcore-log: 
03-30 14:14:14.911  3665  3742 I jxcore-log: ok 36 The mux object should be closed
03-30 14:14:14.911  3665  3742 I jxcore-log: 
,03-30 14:14:14.911  3665  3742 I jxcore-log: ok 37 The mux stream should be closed
03-30 14:14:14.911  3665  3742 I jxcore-log: 
,03-30 14:14:14.919  3665  3742 I jxcore-log: # teardown
03-30 14:14:14.919  3665  3742 I jxcore-log: 
,03-30 14:14:15.157  3665  3742 I jxcore-log: # setup
03-30 14:14:15.157  3665  3742 I jxcore-log: 
,03-30 14:14:15.296  3665  3742 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-30 14:14:15.296  3665  3742 I jxcore-log: 
,03-30 14:14:15.465  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:15.465  3665  3742 I jxcore-log: 
,03-30 14:14:15.475  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 45604
03-30 14:14:15.475  3665  3742 I jxcore-log: 
,03-30 14:14:15.481  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:15.481  3665  3742 I jxcore-log: 
,03-30 14:14:15.482  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:15.482  3665  3742 I jxcore-log: 
,03-30 14:14:15.484  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:15.484  3665  3742 I jxcore-log: 
,03-30 14:14:15.491  3665  3742 I jxcore-log: ok 38 we should not have gotten an error
03-30 14:14:15.491  3665  3742 I jxcore-log: 
,03-30 14:14:15.495  3665  3742 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:15.495  3665  3742 I jxcore-log: 
,03-30 14:14:15.498  3665  3742 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:15.498  3665  3742 I jxcore-log: 
,03-30 14:14:15.505  3665  3742 I jxcore-log: ok 39 Buffers are identical
03-30 14:14:15.505  3665  3742 I jxcore-log: 
,03-30 14:14:15.510  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-30 14:14:15.510  3665  3742 I jxcore-log: 
,03-30 14:14:15.511  3665  3742 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:15.511  3665  3742 I jxcore-log: ,
,03-30 14:14:15.514  3665  3742 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:15.514  3665  3742 I jxcore-log: 
,03-30 14:14:15.519  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:15.519  3665  3742 I jxcore-log: 
,03-30 14:14:15.520  3665  3742 I jxcore-log: ok 40 server should be fine
03-30 14:14:15.520  3665  3742 I jxcore-log: 
,03-30 14:14:15.520  3665  3742 I jxcore-log: ok 41 server should be open
03-30 14:14:15.520  3665  3742 I jxcore-log: 
,03-30 14:14:15.521  3665  3742 I jxcore-log: ok 42 incoming has been removed
03-30 14:14:15.521  3665  3742 I jxcore-log: 
03-30 14:14:15.521  3665  3742 I jxcore-log: ok 43 The mux object should be closed
03-30 14:14:15.521  3665  3742 I jxcore-log: 
,03-30 14:14:15.522  3665  3742 I jxcore-log: ok 44 The mux stream should be closed
03-30 14:14:15.522  3665  3742 I jxcore-log: 
,03-30 14:14:15.532  3665  3742 I jxcore-log: # teardown
03-30 14:14:15.532  3665  3742 I jxcore-log: 
,03-30 14:14:15.657  3665  3742 I jxcore-log: # setup
03-30 14:14:15.657  3665  3742 I jxcore-log: 
,03-30 14:14:15.752  3665  3742 I jxcore-log: # 12. closeAll can close even when connections open
03-30 14:14:15.752  3665  3742 I jxcore-log: 
,03-30 14:14:15.901  3665  3742 I jxcore-log: ok 45 not possible to connect to the server anymore
03-30 14:14:15.901  3665  3742 I jxcore-log: 
,03-30 14:14:15.907  3665  3742 I jxcore-log: # teardown
03-30 14:14:15.907  3665  3742 I jxcore-log: 
,03-30 14:14:16.072  3665  3742 I jxcore-log: # setup
03-30 14:14:16.072  3665  3742 I jxcore-log: 
,03-30 14:14:16.209  3665  3742 I jxcore-log: # 13. closeAll with promise
03-30 14:14:16.209  3665  3742 I jxcore-log: 
,03-30 14:14:16.342  3665  3742 I jxcore-log: ok 46 not possible to connect to the server anymore
03-30 14:14:16.342  3665  3742 I jxcore-log: 
,03-30 14:14:16.347  3665  3742 I jxcore-log: # teardown
03-30 14:14:16.347  3665  3742 I jxcore-log: 
,03-30 14:14:16.489  3665  3742 I jxcore-log: # setup
03-30 14:14:16.489  3665  3742 I jxcore-log: 
,03-30 14:14:16.677  3665  3742 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-30 14:14:16.677  3665  3742 I jxcore-log: 
,03-30 14:14:16.822  3665  3742 I jxcore-log: ok 47 Got the right error
03-30 14:14:16.822  3665  3742 I jxcore-log: 
,03-30 14:14:16.826  3665  3742 I jxcore-log: # teardown
03-30 14:14:16.826  3665  3742 I jxcore-log: 
,03-30 14:14:16.969  3665  3742 I jxcore-log: # setup
03-30 14:14:16.969  3665  3742 I jxcore-log: 
,03-30 14:14:17.149  3665  3742 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-30 14:14:17.149  3665  3742 I jxcore-log: 
,03-30 14:14:17.297  3665  3742 I jxcore-log: # teardown
03-30 14:14:17.297  3665  3742 I jxcore-log: 
,03-30 14:14:17.495  3665  3742 I jxcore-log: # setup
03-30 14:14:17.495  3665  3742 I jxcore-log: 
,03-30 14:14:17.624  3665  3742 I jxcore-log: # 16. multiplex can send data
03-30 14:14:17.624  3665  3742 I jxcore-log: 
,03-30 14:14:17.773  3665  3742 I jxcore-log: ok 48 String should be length:200
03-30 14:14:17.773  3665  3742 I jxcore-log: 
,03-30 14:14:17.782  3665  3742 I jxcore-log: # teardown
03-30 14:14:17.782  3665  3742 I jxcore-log: 
,03-30 14:14:17.925  3665  3742 I jxcore-log: # setup
03-30 14:14:17.925  3665  3742 I jxcore-log: 
,03-30 14:14:18.091  3665  3742 I jxcore-log: # 17. enqueue and run in order
03-30 14:14:18.091  3665  3742 I jxcore-log: 
,03-30 14:14:18.290  3665  3742 I jxcore-log: ok 49 firstPromise setTimeout,
03-30 14:14:18.290  3665  3742 I jxcore-log: 
,03-30 14:14:18.294  3665  3742 I jxcore-log: ok 50 firstPromise result
03-30 14:14:18.294  3665  3742 I jxcore-log: ,
03-30 14:14:18.295  3665  3742 I jxcore-log: ok 51 firstPromise testValue
03-30 14:14:18.295  3665  3742 I jxcore-log: 
,03-30 14:14:18.398  3665  3742 I jxcore-log: ok 52 secondPromise setTimeout
03-30 14:14:18.398  3665  3742 I jxcore-log: ,
,03-30 14:14:18.403  3665  3742 I jxcore-log: ok 53 secondPromise result
03-30 14:14:18.403  3665  3742 I jxcore-log: 
,03-30 14:14:18.404  3665  3742 I jxcore-log: ok 54 secondPromise testValue
03-30 14:14:18.404  3665  3742 I jxcore-log: 
,03-30 14:14:18.407  3665  3742 I jxcore-log: ok 55 thirdPromise in promise
03-30 14:14:18.407  3665  3742 I jxcore-log: 
,03-30 14:14:18.410  3665  3742 I jxcore-log: ok 56 thirdPromise result
03-30 14:14:18.410  3665  3742 I jxcore-log: 
,03-30 14:14:18.412  3665  3742 I jxcore-log: ok 57 thirdPromise testValue
03-30 14:14:18.412  3665  3742 I jxcore-log: 
,03-30 14:14:18.423  3665  3742 I jxcore-log: # teardown
03-30 14:14:18.423  3665  3742 I jxcore-log: 
,03-30 14:14:18.609  3665  3742 I jxcore-log: # setup
03-30 14:14:18.609  3665  3742 I jxcore-log: 
,03-30 14:14:19.127  3665  3742 I jxcore-log: # 18. enqueueAtTop and run backwards
03-30 14:14:19.127  3665  3742 I jxcore-log: 
,03-30 14:14:19.356  3665  3742 I jxcore-log: ok 58 thirdPromise - first to run
03-30 14:14:19.356  3665  3742 I jxcore-log: 
,03-30 14:14:19.358  3665  3742 I jxcore-log: ok 59 thirdPromise - in resolve
03-30 14:14:19.358  3665  3742 I jxcore-log: 
03-30 14:14:19.359  3665  3742 I jxcore-log: ok 60 secondPromise - second to run
03-30 14:14:19.359  3665  3742 I jxcore-log: 
03-30 14:14:19.360  3665  3742 I jxcore-log: ok 61 secondPromise - in catch
03-30 14:14:19.360  3665  3742 I jxcore-log: 
,03-30 14:14:19.361  3665  3742 I jxcore-log: ok 62 firstPromise - third to run
03-30 14:14:19.361  3665  3742 I jxcore-log: 
03-30 14:14:19.362  3665  3742 I jxcore-log: ok 63 firstPromise - in then
03-30 14:14:19.362  3665  3742 I jxcore-log: 
03-30 14:14:19.362  3665  3742 I jxcore-log: ok 64 testing promises
03-30 14:14:19.362  3665  3742 I jxcore-log: 
,03-30 14:14:19.365  3665  3742 I jxcore-log: # teardown
03-30 14:14:19.365  3665  3742 I jxcore-log: 
,03-30 14:14:19.618  3665  3742 I jxcore-log: # setup
03-30 14:14:19.618  3665  3742 I jxcore-log: 
,03-30 14:14:19.636  1252  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-30 14:14:19.637  1252  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:19.637  1252  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-30 14:14:19.637  1252  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:19.648  1252  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:19.681  3132  3939 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-30 14:14:19.681  3132  3939 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at jdm.a(PG:82)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at jcs.o(PG:406)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at jcn.a(PG:1379)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at jcs.i(PG:143)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at blb.a(PG:3937)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at czp.a(PG:18188)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at czp.a(PG:9081)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at czq.run(PG:1686)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:14:19.681  3132  3939 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at jdj.a(PG:4091)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at jdj.a(PG:1125)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at jdm.a(PG:77)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	... 12 more
03-30 14:14:19.681  3132  3939 E HttpOperation: Caused by: faj: BadAuthentication
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at fal.a(PG:38)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	at jdj.a(PG:4089)
03-30 14:14:19.681  3132  3939 E HttpOperation: 	... 14 more
,03-30 14:14:19.720  3665  3742 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-30 14:14:19.720  3665  3742 I jxcore-log: 
,03-30 14:14:19.752  1252  1269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-30 14:14:19.752  1252  1269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:19.752  1252  1269 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:19.752  1252  1269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:19.758  1252  1269 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:19.774  3132  3939 E HttpOperation: [getmobileexperiments] Unexpected exception
03-30 14:14:19.774  3132  3939 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at jdm.a(PG:82)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at jcs.o(PG:406)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at jcn.a(PG:1379)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at jcs.i(PG:143)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at hec.a(PG:42)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at hee.a(PG:102)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at czr.a(PG:65)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at kka.a(PG:108)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at czp.a(PG:19176)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at czp.a(PG:9081)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at czq.run(PG:1686)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:14:19.774  3132  3939 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at jdj.a(PG:4091)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at jdj.a(PG:1125)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at jdm.a(PG:77)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	... 15 more
03-30 14:14:19.774  3132  3939 E HttpOperation: Caused by: faj: BadAuthentication
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at fal.a(PG:38)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	at jdj.a(PG:4089)
03-30 14:14:19.774  3132  3939 E HttpOperation: 	... 17 more
,03-30 14:14:19.774  3132  3939 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-30 14:14:19.774  3132  3939 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at jdm.a(PG:82)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at jcs.o(PG:406)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at jcn.a(PG:1379)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at jcs.i(PG:143)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at hec.a(PG:42)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at hee.a(PG:102)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at czr.a(PG:65)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at kka.a(PG:108)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at czp.a(PG:19176)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at czp.a(PG:9081)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at czq.run(PG:1686)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at jdj.a(PG:4091)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at jdj.a(PG:1125)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at jdm.a(PG:77)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	... 15 more
03-30 14:14:19.774  3132  3939 E ExperimentLoader: Caused by: faj: BadAuthentication
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at fal.a(PG:38)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	at jdj.a(PG:4089)
03-30 14:14:19.774  3132  3939 E ExperimentLoader: 	... 17 more
,03-30 14:14:19.863  3665  3742 I jxcore-log: ok 65 fourth
03-30 14:14:19.863  3665  3742 I jxcore-log: 
,03-30 14:14:19.865  3665  3742 I jxcore-log: ok 66 fourth
03-30 14:14:19.865  3665  3742 I jxcore-log: 
,03-30 14:14:19.868  3665  3742 I jxcore-log: ok 67 second
03-30 14:14:19.868  3665  3742 I jxcore-log: 
,03-30 14:14:19.871  3665  3742 I jxcore-log: ok 68 secondPromise - in then,
03-30 14:14:19.871  3665  3742 I jxcore-log: 
,03-30 14:14:19.906   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 202887, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-30 14:14:19.975  3665  3742 I jxcore-log: ok 69 first,
03-30 14:14:19.975  3665  3742 I jxcore-log: 
,03-30 14:14:19.978  3665  3742 I jxcore-log: ok 70 firstPromise - in catch
03-30 14:14:19.978  3665  3742 I jxcore-log: 
03-30 14:14:19.978  3665  3742 I jxcore-log: ok 71 third,
03-30 14:14:19.978  3665  3742 I jxcore-log: 
03-30 14:14:19.978  3665  3742 I jxcore-log: ok 72 thirdPromise - in then
03-30 14:14:19.978  3665  3742 I jxcore-log: 
,03-30 14:14:19.979  3665  3742 I jxcore-log: ok 73 testingPromises,
03-30 14:14:19.979  3665  3742 I jxcore-log: 
03-30 14:14:19.982  3665  3742 I jxcore-log: # teardown
03-30 14:14:19.982  3665  3742 I jxcore-log: 
,03-30 14:14:20.167  3665  3742 I jxcore-log: # setup,
03-30 14:14:20.167  3665  3742 I jxcore-log: 
,03-30 14:14:20.315  3665  3742 I jxcore-log: # 20. queues handled independently
03-30 14:14:20.315  3665  3742 I jxcore-log: 
,03-30 14:14:20.490  3665  3742 I jxcore-log: ok 74 all short operations completed before the long resolves
03-30 14:14:20.490  3665  3742 I jxcore-log: ,
,03-30 14:14:20.495  3665  3742 I jxcore-log: # teardown
03-30 14:14:20.495  3665  3742 I jxcore-log: 
,03-30 14:14:20.679  3665  3742 I jxcore-log: # setup
03-30 14:14:20.679  3665  3742 I jxcore-log: 
,03-30 14:14:20.894  3665  3742 I jxcore-log: # 21. basic
03-30 14:14:20.894  3665  3742 I jxcore-log: 
,03-30 14:14:21.085  3665  3742 I jxcore-log: ok 75 sane
03-30 14:14:21.085  3665  3742 I jxcore-log: 
,03-30 14:14:21.091  3665  3742 I jxcore-log: # teardown
03-30 14:14:21.091  3665  3742 I jxcore-log: 
,03-30 14:14:21.238  3665  3742 I jxcore-log: # setup
03-30 14:14:21.238  3665  3742 I jxcore-log: 
,03-30 14:14:21.251  1252  3942 I VacuumService: Vacuum at: now=1459340061251 tag=VacuumService
,03-30 14:14:21.257  1252  3943 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-30 14:14:21.276  1252  3943 W Uploader: No account for auth token provided
,03-30 14:14:21.333   821  3580 I ActivityManager: Start proc 3944:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,03-30 14:14:21.404  3944  3963 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-30 14:14:21.404  3944  3963 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 14:14:21.411  1252  1720 I art     : Explicit concurrent mark sweep GC freed 33873(1917KB) AllocSpace objects, 9(992KB) LOS objects, 38% free, 25MB/41MB, paused 1.251ms total 35.937ms
,03-30 14:14:21.447  3944  3963 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-30 14:14:21.447  3665  3742 I jxcore-log: # 22. another
03-30 14:14:21.447  3665  3742 I jxcore-log: 
,03-30 14:14:21.484  3944  3963 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-30 14:14:21.501  1252  1252 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:21.522  1252  1724 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-30 14:14:21.523  1252  1724 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:21.523  1252  1724 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:21.523  1252  1724 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:21.526  1252  1724 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:21.537  3828  3828 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-30 14:14:21.537  3828  3828 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-30 14:14:21.538  3828  3828 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-30 14:14:21.579  3974  3974 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-962065375.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-962065375.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-30 14:14:21.598  3944  3944 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-30 14:14:21.603  3665  3742 I jxcore-log: ok 76 sane
03-30 14:14:21.603  3665  3742 I jxcore-log: 
03-30 14:14:21.606  3665  3742 I jxcore-log: # teardown
03-30 14:14:21.606  3665  3742 I jxcore-log: 
,03-30 14:14:21.612  3974  3974 I dex2oat : dex2oat took 33.406ms (threads: 4) arena alloc=90KB java alloc=12KB native alloc=845KB free=7MB
,03-30 14:14:21.727  3665  3742 I jxcore-log: # setup
03-30 14:14:21.727  3665  3742 I jxcore-log: 
,03-30 14:14:21.739  3944  3944 W InstanceID/Rpc: Found 10011
,03-30 14:14:21.808   821   840 I ActivityManager: Killing 3633:com.android.chrome/u0a40 (adj 15): empty #17
,03-30 14:14:21.815  1252  3943 W Uploader: No account for auth token provided
,03-30 14:14:21.833  3665  3742 I jxcore-log: # 23. can pass data in setup
03-30 14:14:21.833  3665  3742 I jxcore-log: 
,03-30 14:14:22.015  1252  3943 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-30 14:14:22.016  1252  3943 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:22.016  1252  3943 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:22.016  1252  3943 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:22.021  1252  3943 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:22.024  3665  3742 I jxcore-log: ok 77 test participant has uuid
03-30 14:14:22.024  3665  3742 I jxcore-log: 
03-30 14:14:22.025  3665  3742 I jxcore-log: ok 78 participant data matches
03-30 14:14:22.025  3665  3742 I jxcore-log: 
03-30 14:14:22.025  3665  3742 I jxcore-log: ok 79 test participant has uuid
03-30 14:14:22.025  3665  3742 I jxcore-log: 
03-30 14:14:22.026  3665  3742 I jxcore-log: ok 80 participant data matches
03-30 14:14:22.026  3665  3742 I jxcore-log: 
03-30 14:14:22.026  3665  3742 I jxcore-log: ok 81 test participant has uuid
03-30 14:14:22.026  3665  3742 I jxcore-log: 
03-30 14:14:22.026  3665  3742 I jxcore-log: ok 82 participant data matches
03-30 14:14:22.026  3665  3742 I jxcore-log: 
,03-30 14:14:22.035  3665  3742 I jxcore-log: not ok 83 test participant has uuid
03-30 14:14:22.035  3665  3742 I jxcore-log: 
03-30 14:14:22.035  3665  3742 I jxcore-log:   ---
03-30 14:14:22.035  3665  3742 I jxcore-log: 
03-30 14:14:22.035  3665  3742 I jxcore-log:     operator: ok
03-30 14:14:22.035  3665  3742 I jxcore-log: 
03-30 14:14:22.035  3665  3742 I jxcore-log:     expected: true
03-30 14:14:22.035  3665  3742 I jxcore-log: 
03-30 14:14:22.036  3665  3742 I jxcore-log:     actual:   undefined
03-30 14:14:22.036  3665  3742 I jxcore-log: 
,03-30 14:14:22.037  3665  3742 I jxcore-log:   ...
03-30 14:14:22.037  3665  3742 I jxcore-log: 
03-30 14:14:22.038  3665  3742 I jxcore-log: ok 84 participant data matches
03-30 14:14:22.038  3665  3742 I jxcore-log: 
,03-30 14:14:22.039  3665  3742 I jxcore-log: ok 85 own UUID is found from the participants list
03-30 14:14:22.039  3665  3742 I jxcore-log: 
03-30 14:14:22.042  3665  3742 I jxcore-log: # teardown
03-30 14:14:22.042  3665  3742 I jxcore-log: 
,03-30 14:14:22.063  1252  3943 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-30 14:14:22.063  1252  3943 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 14:14:22.063  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 14:14:22.063  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 14:14:22.063  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-30 14:14:22.063  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-30 14:14:22.063  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-30 14:14:22.063  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-30 14:14:22.063  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-30 14:14:22.063  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-30 14:14:22.063  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-30 14:14:22.063  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-30 14:14:22.063  1252  3943 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-30 14:14:22.166  1252  3943 W Uploader: No account for auth token provided
,03-30 14:14:22.271  1252  3943 W Uploader: No account for auth token provided
,03-30 14:14:22.406  3665  3742 I jxcore-log: # setup
03-30 14:14:22.406  3665  3742 I jxcore-log: 
,03-30 14:14:22.442  1252  3943 W Uploader: No account for auth token provided
,03-30 14:14:22.616  3665  3742 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-30 14:14:22.616  3665  3742 I jxcore-log: 
,03-30 14:14:22.636  1252  3943 W Uploader: No account for auth token provided
,03-30 14:14:22.768  1252  3943 W Uploader: No account for auth token provided
,03-30 14:14:22.773  3665  3742 I jxcore-log: ok 86 specific error should be returned
03-30 14:14:22.773  3665  3742 I jxcore-log: 
,03-30 14:14:22.778  3665  3742 I jxcore-log: # teardown
03-30 14:14:22.778  3665  3742 I jxcore-log: 
,03-30 14:14:22.906  1252  3943 W Uploader: No account for auth token provided
,03-30 14:14:22.955  3665  3742 I jxcore-log: ok 87 error should be null
03-30 14:14:22.955  3665  3742 I jxcore-log: 
,03-30 14:14:22.957  3665  3742 I jxcore-log: ok 88 error should be null
03-30 14:14:22.957  3665  3742 I jxcore-log: 
,03-30 14:14:22.962  3665  3742 I jxcore-log: # setup,
03-30 14:14:22.962  3665  3742 I jxcore-log: 
,03-30 14:14:23.040  1252  3943 W Uploader:  no longer exists, so no auth token.
,03-30 14:14:23.071  3665  3742 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-30 14:14:23.071  3665  3742 I jxcore-log: 
,03-30 14:14:23.161  1252  3943 W Uploader: No account for auth token provided
,03-30 14:14:23.256  3665  3742 I jxcore-log: ok 89 specific error should be returned
03-30 14:14:23.256  3665  3742 I jxcore-log: 
,03-30 14:14:23.258  3665  3742 I jxcore-log: # teardown
03-30 14:14:23.258  3665  3742 I jxcore-log: 
,03-30 14:14:23.330  1252  3943 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-30 14:14:23.330  1252  3943 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:23.330  1252  3943 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-30 14:14:23.331  1252  3943 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:23.340  1252  3943 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:23.405  3665  3742 I jxcore-log: ok 90 error should be null
03-30 14:14:23.405  3665  3742 I jxcore-log: 
,03-30 14:14:23.407  3665  3742 I jxcore-log: ok 91 error should be null
03-30 14:14:23.407  3665  3742 I jxcore-log: 
,03-30 14:14:23.410  3665  3742 I jxcore-log: # setup
03-30 14:14:23.410  3665  3742 I jxcore-log: 
,03-30 14:14:23.418  1252  3943 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-30 14:14:23.418  1252  3943 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 14:14:23.418  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 14:14:23.418  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 14:14:23.418  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-30 14:14:23.418  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-30 14:14:23.418  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-30 14:14:23.418  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-30 14:14:23.418  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-30 14:14:23.418  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-30 14:14:23.418  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-30 14:14:23.418  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-30 14:14:23.418  1252  3943 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-30 14:14:23.555  3665  3742 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-30 14:14:23.555  3665  3742 I jxcore-log: 
,03-30 14:14:23.592  1252  3943 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-30 14:14:23.593  1252  3943 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:23.593  1252  3943 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:23.593  1252  3943 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:23.597  1252  3943 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:23.635  1252  3943 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-30 14:14:23.635  1252  3943 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 14:14:23.635  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 14:14:23.635  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 14:14:23.635  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-30 14:14:23.635  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-30 14:14:23.635  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-30 14:14:23.635  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-30 14:14:23.635  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-30 14:14:23.635  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-30 14:14:23.635  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-30 14:14:23.635  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-30 14:14:23.635  1252  3943 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-30 14:14:23.758  1252  3943 W Uploader: No account for auth token provided
,03-30 14:14:23.854  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:23.854  3665  3742 I jxcore-log: 
03-30 14:14:23.856  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 46038
03-30 14:14:23.856  3665  3742 I jxcore-log: 
,03-30 14:14:23.859  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:23.860  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:23.860  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:23.865  3665  3742 I jxcore-log: ok 92 error should be null
03-30 14:14:23.865  3665  3742 I jxcore-log: 
,03-30 14:14:23.865  3665  3742 I jxcore-log: ok 93 error should be null
03-30 14:14:23.865  3665  3742 I jxcore-log: 
03-30 14:14:23.867  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:14:23.867  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 14:14:23.867  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:23.868  3665  3742 I jxcore-log: ok 94 error should be null
03-30 14:14:23.868  3665  3742 I jxcore-log: 
03-30 14:14:23.869  3665  3742 I jxcore-log: ok 95 error should be null
03-30 14:14:23.869  3665  3742 I jxcore-log: 
03-30 14:14:23.873  3665  3742 I jxcore-log: # teardown
03-30 14:14:23.873  3665  3742 I jxcore-log: 
,03-30 14:14:23.925  1252  3943 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-30 14:14:23.926  1252  3943 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
03-30 14:14:23.926  1252  3943 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:23.926  1252  3943 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:23.933  1252  3943 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:23.970  1252  3943 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-30 14:14:23.970  1252  3943 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 14:14:23.970  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 14:14:23.970  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 14:14:23.970  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550),
03-30 14:14:23.970  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-30 14:14:23.970  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-30 14:14:23.970  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-30 14:14:23.970  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-30 14:14:23.970  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-30 14:14:23.970  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125),
03-30 14:14:23.970  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-30 14:14:23.970  1252  3943 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-30 14:14:24.086  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:24.087  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-30 14:14:24.087  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:24.097  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:24.097  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:24.097  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:24.109  3665  3742 I jxcore-log: ok 96 error should be null
03-30 14:14:24.109  3665  3742 I jxcore-log: 
,03-30 14:14:24.110  3665  3742 I jxcore-log: ok 97 error should be null
03-30 14:14:24.110  3665  3742 I jxcore-log: 
,03-30 14:14:24.117  3665  3742 I jxcore-log: # setup
03-30 14:14:24.117  3665  3742 I jxcore-log: 
,03-30 14:14:24.151  1252  3943 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-30 14:14:24.151  1252  3943 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:24.151  1252  3943 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-30 14:14:24.152  1252  3943 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:24.160  1252  3943 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:24.191  3665  3742 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-30 14:14:24.191  3665  3742 I jxcore-log: 
,03-30 14:14:24.214  1252  3943 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.,
03-30 14:14:24.214  1252  3943 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 14:14:24.214  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 14:14:24.214  1252  3943 E Uploader: 	,at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 14:14:24.214  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-30 14:14:24.214  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
,03-30 14:14:24.214  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-30 14:14:24.214  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-30 14:14:24.214  1252  3943 E Uploader: ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-30 14:14:24.214  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-30 14:14:24.214  1252  3943 E Uploader: 	,at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-30 14:14:24.214  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-30 14:14:24.214  1252  3943 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135),
,03-30 14:14:24.330  1252  3943 W Uploader: No account for auth token provided
,03-30 14:14:24.366  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:24.366  3665  3742 I jxcore-log: 
,03-30 14:14:24.368  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 42933
03-30 14:14:24.368  3665  3742 I jxcore-log: 
,03-30 14:14:24.378  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-30 14:14:24.378  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:24.378  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:14:24.378  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-30 14:14:24.378  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:24.378  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:24.388  3665  3742 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:14:24.388   821  1101 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:24.402  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:24.415  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 14:14:24.416  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:14:24.416  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:24.417  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:24.432  2152  2169 D BtGatt.GattService: registerClient() - UUID=f19861a5-c69c-42c1-ba74-1f03d6b7d48b
,03-30 14:14:24.433  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=f19861a5-c69c-42c1-ba74-1f03d6b7d48b, clientIf=5
,03-30 14:14:24.435  3665  3682 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 14:14:24.437  2152  2216 D BtGatt.GattService: start scan with filters
,03-30 14:14:24.444  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:24.444  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 14:14:24.444  2152  2225 D BtGatt.ScanManager: handling starting scan
03-30 14:14:24.444  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:24.444  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
03-30 14:14:24.444  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:24.445  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:14:24.447  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:24.448  2152  2225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b2438d
,03-30 14:14:24.449   821  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:24.457  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-30 14:14:24.457  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:24.458  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:14:24.458  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:24.461  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-30 14:14:24.461  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:24.462  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:24.462  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:24.462  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:14:24.462  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:24.462  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:14:24.463  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:24.465  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:14:24.465  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:24.468  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:14:24.469  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:24.471  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:24.471  3665  3742 I jxcore-log: 
03-30 14:14:24.472  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:24.472  3665  3742 I jxcore-log: 
,03-30 14:14:24.474  3665  3742 I jxcore-log: ok 98 error should be null
03-30 14:14:24.474  3665  3742 I jxcore-log: 
,03-30 14:14:24.474  3665  3742 I jxcore-log: ok 99 error should be null
,03-30 14:14:24.474  3665  3742 I jxcore-log: 
,03-30 14:14:24.481  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-30 14:14:24.482  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:24.482  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-30 14:14:24.482  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:24.482  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:24.485  3665  3742 I jxcore-log: ok 100 error should be null
03-30 14:14:24.485  3665  3742 I jxcore-log: 
,03-30 14:14:24.485  3665  3742 I jxcore-log: ok 101 error should be null
03-30 14:14:24.485  3665  3742 I jxcore-log: 
,03-30 14:14:24.491  3665  3742 I jxcore-log: # teardown
03-30 14:14:24.491  3665  3742 I jxcore-log: 
,03-30 14:14:24.536  1252  3943 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-30 14:14:24.536  1252  3943 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:24.536  1252  3943 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:24.536  1252  3943 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:24.542  1252  3943 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-30 14:14:24.581  1252  3943 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-30 14:14:24.581  1252  3943 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 14:14:24.581  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 14:14:24.581  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 14:14:24.581  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-30 14:14:24.581  1252  3943 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-30 14:14:24.581  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-30 14:14:24.581  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-30 14:14:24.581  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-30 14:14:24.581  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-30 14:14:24.581  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-30 14:14:24.581  1252  3943 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-30 14:14:24.581  1252  3943 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-30 14:14:24.725  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:24.725  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:24.725  3665  3742 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-30 14:14:24.726  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:24.726  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-30 14:14:24.726  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:14:24.726  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:24.727  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:14:24.728  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:14:24.732  2152  2170 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:24.734  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 14:14:24.736  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-30 14:14:24.736  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 14:14:24.736  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:24.736  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:24.736  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:24.736  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 14:14:24.736  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:24.736  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 14:14:24.737  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:24.739  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:14:24.739  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:24.740  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:14:24.740  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:24.740  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:24.740  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:14:24.741  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:14:24.741  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:24.743  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-30 14:14:24.743  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:24.744  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-30 14:14:24.744  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:24.744  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:24.750  3665  3742 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 14:14:24.750  3665  3742 I jxcore-log: ,
,03-30 14:14:24.754  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:14:24.755   821  1414 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:24.761  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:24.761  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 14:14:24.762  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:24.769  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:24.769  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:24.769  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:24.769  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:24.773  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:14:24.773  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 14:14:24.773  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:24.777  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:24.777  3665  3742 I jxcore-log: ,
,03-30 14:14:24.779  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-30 14:14:24.779  3665  3742 I jxcore-log: 
,03-30 14:14:24.786  3665  3742 I jxcore-log: ok 102 error should be null
,03-30 14:14:24.786  3665  3742 I jxcore-log: 
03-30 14:14:24.786  3665  3742 I jxcore-log: ok 103 error should be null
03-30 14:14:24.786  3665  3742 I jxcore-log: 
,03-30 14:14:24.792  3665  3742 I jxcore-log: # setup
03-30 14:14:24.792  3665  3742 I jxcore-log: 
,03-30 14:14:24.842  3342  4032 V GoogleAuthProtoRequest: [342] a.<init>: mAccountName set to: thalitester@gmail.com
,03-30 14:14:24.897  1252  2575 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-30 14:14:24.899  1252  2575 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:24.899  1252  2575 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:24.899  1252  2575 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:24.910  1252  2575 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:24.981  3665  3742 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-30 14:14:24.981  3665  3742 I jxcore-log: 
,03-30 14:14:25.027   821   839 I art     : Explicit concurrent mark sweep GC freed 24625(1096KB) AllocSpace objects, 2(126KB) LOS objects, 31% free, 34MB/50MB, paused 1.406ms total 89.118ms
,03-30 14:14:25.036  3342  4032 W ExperimentUpdateService: [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-30 14:14:25.038  3342  4032 W ExperimentUpdateService: [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-30 14:14:25.038  3342  4032 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-30 14:14:25.038  3342  4032 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-30 14:14:25.038  3342  4032 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-30 14:14:25.038  3342  4032 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-30 14:14:25.038  3342  4032 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-30 14:14:25.038  3342  4032 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-30 14:14:25.038  3342  4032 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-30 14:14:25.038  3342  4032 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-30 14:14:25.038  3342  4032 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-30 14:14:25.038  3342  4032 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-30 14:14:25.131  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:25.131  3665  3742 I jxcore-log: 
,03-30 14:14:25.134  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 39551
03-30 14:14:25.134  3665  3742 I jxcore-log: 
,03-30 14:14:25.149  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 39551, start advertisements: true
03-30 14:14:25.149  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:25.149  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:25.149  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:25.154  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-30 14:14:25.154  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:25.154  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:25.154  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:25.167  2152  2216 D BtGatt.GattService: registerClient() - UUID=43867e6e-fff4-4d73-9e9d-6e8184b12176,
03-30 14:14:25.168  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=43867e6e-fff4-4d73-9e9d-6e8184b12176, clientIf=5
03-30 14:14:25.168  3665  3683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:14:25.169  2152  2170 D BtGatt.GattService: start scan with filters
,03-30 14:14:25.170  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:25.170  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:25.170  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-30 14:14:25.170  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:25.170  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:25.170  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:25.170  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:14:25.171  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:25.171  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:14:25.171  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-30 14:14:25.172  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:25.172  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:25.172  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:25.174  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-30 14:14:25.174  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:25.178  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-30 14:14:25.178  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:25.178  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-30 14:14:25.178  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 14:14:25.179  2152  2169 D BtGatt.GattService: registerClient() - UUID=ea55c51f-446d-473c-81c8-9e6498c90318
03-30 14:14:25.180  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=ea55c51f-446d-473c-81c8-9e6498c90318, clientIf=6
03-30 14:14:25.180  3665  3682 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 14:14:25.181  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
03-30 14:14:25.181  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:25.183  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:14:25.183  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:25.186  2152  2224 D BtGatt.AdvertiseManager: message : 0,
,03-30 14:14:25.191  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising,
,03-30 14:14:25.196  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-30 14:14:25.200  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-30 14:14:25.201  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:14:25.201  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:25.202   821  1322 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:25.204  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:25.204  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:25.204  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:14:25.204  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:25.205  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 14:14:25.206  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-30 14:14:25.206  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:14:25.206  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:14:25.207  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-30 14:14:25.207  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:25.207  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:25.207  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:25.207  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:14:25.207  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:25.207  3665  3665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:14:25.207  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:25.207  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:25.207  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:25.208  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:14:25.208  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:25.208  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:25.214   821  1101 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:25.216  3665  4033 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:25.219  3665  4033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:14:25.221  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:25.221  3665  3742 I jxcore-log: 
,03-30 14:14:25.225  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:25.225  3665  3742 I jxcore-log: 
,03-30 14:14:25.228  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:25.228  3665  3742 I jxcore-log: 
,03-30 14:14:25.233  3665  3742 I jxcore-log: ok 104 error should be null
03-30 14:14:25.233  3665  3742 I jxcore-log: 
,03-30 14:14:25.234  3665  3742 I jxcore-log: ok 105 error should be null
03-30 14:14:25.234  3665  3742 I jxcore-log: 
,03-30 14:14:25.248  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 39551, start advertisements: true
03-30 14:14:25.248  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:25.248  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:25.248  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:25.248  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:25.264  3665  3742 I jxcore-log: ok 106 error should be null
03-30 14:14:25.264  3665  3742 I jxcore-log: 
,03-30 14:14:25.265  3665  3742 I jxcore-log: ok 107 error should be null
03-30 14:14:25.265  3665  3742 I jxcore-log: 
,03-30 14:14:25.276  3665  3742 I jxcore-log: # teardown
03-30 14:14:25.276  3665  3742 I jxcore-log: 
,03-30 14:14:25.617  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:25.617  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 14:14:25.617  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:14:25.617  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:14:25.617  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:14:25.619  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-30 14:14:25.620  3665  4033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:14:25.620  3665  4033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:14:25.620  3665  4033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:14:25.620  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-30 14:14:25.621  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:25.621  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:25.621  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:14:25.621  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:25.621  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:14:25.621  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:14:25.622  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:14:25.624  2152  2170 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:25.627  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-30 14:14:25.630  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 14:14:25.631  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:25.632  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:25.633  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:25.633  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:25.633  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:25.633  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:14:25.633  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:14:25.633  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:25.633  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-30 14:14:25.634  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:14:25.634  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:25.635  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:14:25.637  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-30 14:14:25.638  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 14:14:25.639  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-30 14:14:25.639  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:25.639  2152  2214 D BtGatt.GattService: current time is 209206654553
03-30 14:14:25.639  2152  2214 D BtGatt.GattService: Batch record : [53, 49, 68, -62, 11, 79, 1, -128, -81, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -47, 5, 0, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -47, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 14:14:25.640  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:25.641  2152  2214 D BtGatt.GattService: ScanRecord : []
03-30 14:14:25.641  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 14:14:25.644  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 14:14:25.644  2152  2214 D BtGatt.GattService: Client app is not null!
03-30 14:14:25.646  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 14:14:25.647  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-30 14:14:25.647  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:25.647  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-30 14:14:25.647  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:14:25.647  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:14:25.647  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:25.647  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-30 14:14:25.647  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:14:25.648  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:14:25.648  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:25.648  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:25.649  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:25.649  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-30 14:14:25.654  3665  3742 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 14:14:25.654  3665  3742 I jxcore-log: 
,03-30 14:14:25.660  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-30 14:14:25.661   821  1322 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:25.671  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-30 14:14:25.673  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:25.673  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-30 14:14:25.678  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-30 14:14:25.679  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:14:25.679  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:25.679  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-30 14:14:25.679  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:25.679  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:25.684  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,03-30 14:14:25.684  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
,03-30 14:14:25.684  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-30 14:14:25.685  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:25.685  3665  3742 I jxcore-log: ,
,03-30 14:14:25.686  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:25.686  3665  3742 I jxcore-log: 
03-30 14:14:25.687  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-30 14:14:25.687  3665  3742 I jxcore-log: 
03-30 14:14:25.694  3665  3742 I jxcore-log: ok 108 error should be null
03-30 14:14:25.694  3665  3742 I jxcore-log: ,
03-30 14:14:25.695  3665  3742 I jxcore-log: ok 109 error should be null
03-30 14:14:25.695  3665  3742 I jxcore-log: ,
03-30 14:14:25.704  3665  3742 I jxcore-log: # setup
03-30 14:14:25.704  3665  3742 I jxcore-log: 
,03-30 14:14:25.830  3665  3742 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times,
03-30 14:14:25.830  3665  3742 I jxcore-log: 
,03-30 14:14:26.001  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server,
03-30 14:14:26.001  3665  3742 I jxcore-log: 
,03-30 14:14:26.003  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 35947,
03-30 14:14:26.003  3665  3742 I jxcore-log: 
,03-30 14:14:26.008  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-30 14:14:26.008  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:26.008  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:26.011  3665  3742 I jxcore-log: ok 110 error should be null
03-30 14:14:26.011  3665  3742 I jxcore-log: 
,03-30 14:14:26.012  3665  3742 I jxcore-log: ok 111 error should be null
03-30 14:14:26.012  3665  3742 I jxcore-log: 
03-30 14:14:26.014  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:26.014  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-30 14:14:26.014  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-30 14:14:26.018  3665  3742 I jxcore-log: ok 112 error should be null,
03-30 14:14:26.018  3665  3742 I jxcore-log: 
03-30 14:14:26.018  3665  3742 I jxcore-log: ok 113 error should be null
03-30 14:14:26.018  3665  3742 I jxcore-log: 
03-30 14:14:26.024  3665  3742 I jxcore-log: # teardown
03-30 14:14:26.024  3665  3742 I jxcore-log: ,
,03-30 14:14:26.115  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-30 14:14:26.115  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:26.115  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:26.117  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-30 14:14:26.117  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:26.117  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:26.121  3665  3742 I jxcore-log: ok 114 error should be null
03-30 14:14:26.121  3665  3742 I jxcore-log: 
03-30 14:14:26.122  3665  3742 I jxcore-log: ok 115 error should be null
03-30 14:14:26.122  3665  3742 I jxcore-log: 
,03-30 14:14:26.128  3665  3742 I jxcore-log: # setup
03-30 14:14:26.128  3665  3742 I jxcore-log: 
,03-30 14:14:26.219  3665  3742 I jxcore-log: # 30. #start should fail if called twice in a row
03-30 14:14:26.219  3665  3742 I jxcore-log: 
,03-30 14:14:26.343  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:26.343  3665  3742 I jxcore-log: 
,03-30 14:14:26.345  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 51814
03-30 14:14:26.345  3665  3742 I jxcore-log: 
,03-30 14:14:26.349  3665  3742 I jxcore-log: ok 116 first call should succeed,
,03-30 14:14:26.349  3665  3742 I jxcore-log: 
,03-30 14:14:26.349  3665  3742 I jxcore-log: ok 117 first call should succeed
03-30 14:14:26.349  3665  3742 I jxcore-log: 
,03-30 14:14:26.352  3665  3742 I jxcore-log: ok 118 specific error should be returned
03-30 14:14:26.352  3665  3742 I jxcore-log: 
,03-30 14:14:26.354  3665  3742 I jxcore-log: # teardown
03-30 14:14:26.354  3665  3742 I jxcore-log: 
,03-30 14:14:27.835  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:27.836  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:27.836  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:27.838  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:14:27.838  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:27.838  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:27.843  3665  3742 I jxcore-log: ok 119 error should be null
03-30 14:14:27.843  3665  3742 I jxcore-log: 
,03-30 14:14:27.844  3665  3742 I jxcore-log: ok 120 error should be null
03-30 14:14:27.844  3665  3742 I jxcore-log: 
03-30 14:14:27.848  3665  3742 I jxcore-log: # setup
03-30 14:14:27.848  3665  3742 I jxcore-log: 
,03-30 14:14:27.975  3665  3742 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-30 14:14:27.975  3665  3742 I jxcore-log: 
,03-30 14:14:28.568  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:28.568  3665  3742 I jxcore-log: 
,03-30 14:14:28.570  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 36423
03-30 14:14:28.570  3665  3742 I jxcore-log: 
,03-30 14:14:28.579  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 39551, start advertisements: false
,03-30 14:14:28.579  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:28.579  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 14:14:28.579  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:14:28.585  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-30 14:14:28.585  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:28.586  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
,03-30 14:14:28.592  2152  2216 D BtGatt.GattService: registerClient() - UUID=fe986ef9-9d0b-49e2-8580-4f0b8b01058c,
,03-30 14:14:28.593  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=fe986ef9-9d0b-49e2-8580-4f0b8b01058c, clientIf=5
03-30 14:14:28.594  3665  3682 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 14:14:28.594  2152  2169 D BtGatt.GattService: start scan with filters
,03-30 14:14:28.596  2152  2225 D BtGatt.ScanManager: handling starting scan,
03-30 14:14:28.596  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:28.596  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:28.597  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:28.597  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:28.597  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:28.597  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:14:28.597  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:28.598   821  1322 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:28.604  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-30 14:14:28.604  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:28.606  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-30 14:14:28.606  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:28.606  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-30 14:14:28.606  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:28.606  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 14:14:28.606  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:28.607  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK,
03-30 14:14:28.607  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:14:28.607  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:28.607  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:28.609  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 14:14:28.609  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:28.611  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:14:28.611  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:28.615  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:28.615  3665  3742 I jxcore-log: 
,03-30 14:14:28.616  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:28.616  3665  3742 I jxcore-log: 
,03-30 14:14:28.632  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 36423, start advertisements: true
03-30 14:14:28.632  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:28.632  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:28.632  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:28.636  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:14:28.636  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-30 14:14:28.637  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-30 14:14:28.637  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-30 14:14:28.637  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:14:28.637  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:28.637  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 14:14:28.637  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-30 14:14:28.642  2152  2216 D BtGatt.GattService: registerClient() - UUID=0db4cd22-9c26-45d7-b35e-6e5b0940deab,
,03-30 14:14:28.642  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=0db4cd22-9c26-45d7-b35e-6e5b0940deab, clientIf=6
03-30 14:14:28.642  3665  3683 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 14:14:28.644  2152  2224 D BtGatt.AdvertiseManager: message : 0,
,03-30 14:14:28.647  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:28.650  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:14:28.653  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-30 14:14:28.654  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:28.654  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:14:28.654  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:28.654  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-30 14:14:28.654  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:28.654  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:14:28.654  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:28.654   821   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:28.658  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:14:28.658  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-30 14:14:28.658  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:14:28.658  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:28.659  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:14:28.659  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 14:14:28.660  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:14:28.660  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:14:28.660  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:14:28.660  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:28.660  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:28.660  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:28.660  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:14:28.662   821  1418 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:14:28.663  3665  4034 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:28.668  3665  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:14:28.674  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:28.674  3665  3742 I jxcore-log: 
,03-30 14:14:28.682  3665  3742 I jxcore-log: ok 121 called only once
03-30 14:14:28.682  3665  3742 I jxcore-log: 
,03-30 14:14:28.683  3665  3742 I jxcore-log: ok 122 discovery state matches
03-30 14:14:28.683  3665  3742 I jxcore-log: 
03-30 14:14:28.683  3665  3742 I jxcore-log: ok 123 advertising state matches
03-30 14:14:28.683  3665  3742 I jxcore-log: 
,03-30 14:14:28.696  3665  3742 I jxcore-log: # teardown
03-30 14:14:28.696  3665  3742 I jxcore-log: 
,03-30 14:14:29.620  2152  2152 D BtGatt.ScanManager: awakened up at time 213187
03-30 14:14:29.622  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:14:29.631  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-30 14:14:29.631  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:29.631  2152  2214 D BtGatt.GattService: current time is 213198925073
03-30 14:14:29.632  2152  2214 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -19, 91, -12, -51, 106, 97, 1, -128, -81, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-30 14:14:29.632  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 14:14:29.633  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-30 14:14:29.641  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-30 14:14:29.642  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-30 14:14:29.643  3665  3665 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-30 14:14:29.644  3665  3665 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-30 14:14:29.652  3665  3742 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-30 14:14:29.652  3665  3742 I jxcore-log: 
,03-30 14:14:29.663  3665  3742 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-30 14:14:29.663  3665  3742 I jxcore-log: 
,03-30 14:14:29.667  3665  3742 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-30 14:14:29.667  3665  3742 I jxcore-log: 
,03-30 14:14:29.669  3665  3742 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-30 14:14:29.669  3665  3742 I jxcore-log: 
,03-30 14:14:29.924  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:29.925  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 14:14:29.925  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:14:29.925  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:14:29.925  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-30 14:14:29.925  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-30 14:14:29.925  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:29.925  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:29.925  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 14:14:29.925  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:29.925  3665  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:14:29.925  3665  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-30 14:14:29.925  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:14:29.925  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:14:29.925  3665  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-30 14:14:29.927  2152  2169 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:14:29.929  2152  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 14:14:29.931  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:29.931  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:29.931  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:29.931  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:14:29.931  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:14:29.931  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:29.931  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 14:14:29.934  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-30 14:14:29.935  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 14:14:29.936  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 14:14:29.936  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:29.937  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:29.940  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:14:29.940  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:29.940  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:14:29.941  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 14:14:29.941  2152  2214 D BtGatt.GattService: Client app is not null!
,03-30 14:14:29.943  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-30 14:14:29.944  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:29.945  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:14:29.945  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:14:29.945  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-30 14:14:29.945  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
03-30 14:14:29.945  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:29.945  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:29.945  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:14:29.946  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:14:29.946  3665  3742 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-30 14:14:29.947  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:29.947  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:29.947  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:29.947  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:29.950  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-30 14:14:29.950  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:29.951  2152  2214 D BtGatt.GattService: current time is 213518046166
,03-30 14:14:29.951  2152  2214 D BtGatt.GattService: Batch record : [-19, 91, -12, -51, 106, 97, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0],
03-30 14:14:29.951  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-30 14:14:29.952  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64],
,03-30 14:14:29.954  3665  3742 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-30 14:14:29.954  3665  3742 I jxcore-log: 
03-30 14:14:29.955  3665  3742 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 14:14:29.955  3665  3742 I jxcore-log: 
,03-30 14:14:29.961  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 14:14:29.962   821  1418 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:14:29.964  3665  3742 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 14:14:29.964  3665  3742 I jxcore-log: 
,03-30 14:14:29.972  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:29.973  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:29.973  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:29.977  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:14:29.977  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:14:29.977  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:29.977  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:29.977  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:29.978  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:29.978  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:29.978  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 14:14:29.981  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-30 14:14:29.981  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:29.981  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:29.982  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:29.982  3665  3742 I jxcore-log: 
,03-30 14:14:29.984  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:29.984  3665  3742 I jxcore-log: 
,03-30 14:14:29.985  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:29.985  3665  3742 I jxcore-log: 
,03-30 14:14:29.991  3665  3742 I jxcore-log: ok 124 error should be null
03-30 14:14:29.991  3665  3742 I jxcore-log: 
,03-30 14:14:29.991  3665  3742 I jxcore-log: ok 125 error should be null
03-30 14:14:29.991  3665  3742 I jxcore-log: 
,03-30 14:14:29.998  3665  3742 I jxcore-log: # setup
03-30 14:14:29.998  3665  3742 I jxcore-log: 
,03-30 14:14:30.302  3665  3742 I jxcore-log: # 32. does not send duplicate availability changes
03-30 14:14:30.302  3665  3742 I jxcore-log: 
,03-30 14:14:30.494  3665  3742 I jxcore-log: ok 126 should be called once
03-30 14:14:30.494  3665  3742 I jxcore-log: 
,03-30 14:14:30.495  3665  3742 I jxcore-log: ok 127 should not have been called more than once
03-30 14:14:30.495  3665  3742 I jxcore-log: 
,03-30 14:14:30.498  3665  3742 I jxcore-log: # teardown
,03-30 14:14:30.498  3665  3742 I jxcore-log: 
,03-30 14:14:30.601  3665  3742 I jxcore-log: ok 128 error should be null
,03-30 14:14:30.601  3665  3742 I jxcore-log: 
03-30 14:14:30.604  3665  3742 I jxcore-log: ok 129 error should be null
03-30 14:14:30.604  3665  3742 I jxcore-log: 
,03-30 14:14:30.606  3665  3742 I jxcore-log: # setup
03-30 14:14:30.606  3665  3742 I jxcore-log: 
,03-30 14:14:30.680  3665  3742 I jxcore-log: # 33. can get the network status
03-30 14:14:30.680  3665  3742 I jxcore-log: 
,03-30 14:14:30.798  3665  3742 I jxcore-log: ok 130 network status should have certain non-empty properties
03-30 14:14:30.798  3665  3742 I jxcore-log: 
,03-30 14:14:30.804  3665  3742 I jxcore-log: # teardown
03-30 14:14:30.804  3665  3742 I jxcore-log: 
,03-30 14:14:30.940  3665  3742 I jxcore-log: ok 131 error should be null,
03-30 14:14:30.940  3665  3742 I jxcore-log: 
,03-30 14:14:30.941  3665  3742 I jxcore-log: ok 132 error should be null
03-30 14:14:30.941  3665  3742 I jxcore-log: 
,03-30 14:14:30.952  3665  3742 I jxcore-log: # setup
03-30 14:14:30.952  3665  3742 I jxcore-log: 
,03-30 14:14:31.046  3665  3742 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-30 14:14:31.046  3665  3742 I jxcore-log: 
,03-30 14:14:31.172  3665  3742 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-30 14:14:31.172  3665  3742 I jxcore-log: 
,03-30 14:14:31.196  3665  3742 I jxcore-log: ok 133 host address should match
03-30 14:14:31.196  3665  3742 I jxcore-log: ,
03-30 14:14:31.197  3665  3742 I jxcore-log: ok 134 port should match
03-30 14:14:31.197  3665  3742 I jxcore-log: 
,03-30 14:14:33.179  3665  3742 I jxcore-log: ok 135 host address should be null
03-30 14:14:33.179  3665  3742 I jxcore-log: 
,03-30 14:14:33.181  3665  3742 I jxcore-log: ok 136 port should should be null
03-30 14:14:33.181  3665  3742 I jxcore-log: 
,03-30 14:14:33.205  3665  3742 I jxcore-log: # teardown
03-30 14:14:33.205  3665  3742 I jxcore-log: 
,03-30 14:14:33.253  2152  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-30 14:14:33.890  3665  3742 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 14:14:33.890  3665  3742 I jxcore-log: 
,03-30 14:14:33.895  3665  3742 I jxcore-log: ok 137 error should be null
03-30 14:14:33.895  3665  3742 I jxcore-log: 
,03-30 14:14:33.897  3665  3742 I jxcore-log: ok 138 error should be null
,03-30 14:14:33.897  3665  3742 I jxcore-log: 
03-30 14:14:33.902  3665  3742 I jxcore-log: # setup
03-30 14:14:33.902  3665  3742 I jxcore-log: 
,03-30 14:14:33.982  3665  3742 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-30 14:14:33.982  3665  3742 I jxcore-log: 
,03-30 14:14:34.116  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 36423, start advertisements: false,
03-30 14:14:34.117  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:34.117  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:14:34.117  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:14:34.125  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:14:34.126  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:34.126  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:34.135  2152  2169 D BtGatt.GattService: registerClient() - UUID=0462781f-8b52-4db8-b93d-f9227b736ee4
,03-30 14:14:34.136  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=0462781f-8b52-4db8-b93d-f9227b736ee4, clientIf=5,
03-30 14:14:34.137  3665  3682 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:14:34.138  2152  2170 D BtGatt.GattService: start scan with filters
,03-30 14:14:34.141  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-30 14:14:34.143  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 14:14:34.144  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:34.144  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-30 14:14:34.144  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-30 14:14:34.144  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:14:34.149  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:34.149  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:14:34.151   821  3150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:14:34.153  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-30 14:14:34.153  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:34.156  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:14:34.156  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:34.157  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan,
03-30 14:14:34.157  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 14:14:34.160  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:14:34.160  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:34.163  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-30 14:14:34.162  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:34.163  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:34.163  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-30 14:14:34.164  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:34.164  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-30 14:14:34.164  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:34.165  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:34.168  3665  3742 I jxcore-log: ok 139 Can call startListeningForAdvertisements without error
03-30 14:14:34.168  3665  3742 I jxcore-log: 
,03-30 14:14:34.169  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:34.169  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:34.169  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-30 14:14:34.169  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:14:34.171  2152  2170 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:14:34.173  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 14:14:34.173  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:34.174  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:34.174  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 14:14:34.174  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:34.174  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:34.174  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:34.174  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 14:14:34.174  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 14:14:34.174  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:34.175  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-30 14:14:34.176  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:34.176  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:34.177  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:14:34.177  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:34.177  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:14:34.179  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:14:34.179  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:34.179  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:34.179  3665  3742 I jxcore-log: 
03-30 14:14:34.181  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:34.181  3665  3742 I jxcore-log: 
,03-30 14:14:34.185  3665  3742 I jxcore-log: ok 140 Can call stopListeningForAdvertisements without error
03-30 14:14:34.185  3665  3742 I jxcore-log: 
,03-30 14:14:34.197  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:34.197  3665  3742 I jxcore-log: 
,03-30 14:14:34.200  3665  3742 I jxcore-log: # teardown
03-30 14:14:34.200  3665  3742 I jxcore-log: 
,03-30 14:14:34.402  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:34.403  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:34.404  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:34.408  3665  3742 I jxcore-log: ok 141 Should be able to call stopListeningForAdvertisments in teardown
03-30 14:14:34.408  3665  3742 I jxcore-log: 
,03-30 14:14:34.408  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:34.408  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:34.408  3665  3742 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-30 14:14:34.408  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 14:14:34.408  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-30 14:14:34.408  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:14:34.409  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-30 14:14:34.409  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:14:34.411  3665  3742 D BluetoothLeScanner: could not find callback wrapper
03-30 14:14:34.411  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:34.413  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:34.414  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:34.415  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:14:34.417  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-30 14:14:34.417  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:34.417  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-30 14:14:34.417  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:34.417  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:34.427  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:14:34.428   821  1418 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:34.440  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-30 14:14:34.441  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 14:14:34.442  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:34.448  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:34.448  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-30 14:14:34.449  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:34.452  3665  3742 I jxcore-log: ok 142 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:14:34.452  3665  3742 I jxcore-log: 
,03-30 14:14:34.466  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:34.466  3665  3742 I jxcore-log: 
,03-30 14:14:34.469  3665  3742 I jxcore-log: # setup
03-30 14:14:34.469  3665  3742 I jxcore-log: 
,03-30 14:14:34.650  3665  3742 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-30 14:14:34.650  3665  3742 I jxcore-log: 
,03-30 14:14:34.764  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 36423, start advertisements: false
03-30 14:14:34.764  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:34.764  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:14:34.764  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:14:34.767  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:34.767  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 14:14:34.767  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:34.770  2152  2170 D BtGatt.GattService: registerClient() - UUID=94bca0a6-220a-4415-9cc2-5a2f4cd971c5,
03-30 14:14:34.771  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=94bca0a6-220a-4415-9cc2-5a2f4cd971c5, clientIf=5
03-30 14:14:34.771  3665  3682 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:14:34.772  2152  2216 D BtGatt.GattService: start scan with filters
03-30 14:14:34.773  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-30 14:14:34.774  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:34.774  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:34.774  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:34.774  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:34.774  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:14:34.774  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:34.775   821  3150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:14:34.775  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:34.776  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:14:34.776  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:34.778  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:34.778  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:14:34.778  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:34.778  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:34.778  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-30 14:14:34.778  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:14:34.778  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:14:34.778  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:34.779  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:34.779  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:34.781  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:14:34.781  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:34.783  3665  3742 I jxcore-log: ok 143 Can call startListeningForAdvertisements without error
03-30 14:14:34.783  3665  3742 I jxcore-log: 
,03-30 14:14:34.784  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:14:34.784  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:34.790  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 36423, start advertisements: false
,03-30 14:14:34.791  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:34.791  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:14:34.791  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:34.791  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:34.796  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:34.796  3665  3742 I jxcore-log: 
,03-30 14:14:34.798  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:34.798  3665  3742 I jxcore-log: 
,03-30 14:14:34.802  3665  3742 I jxcore-log: ok 144 Can call startListeningForAdvertisements twice without error
03-30 14:14:34.802  3665  3742 I jxcore-log: 
,03-30 14:14:34.815  3665  3742 I jxcore-log: # teardown
03-30 14:14:34.815  3665  3742 I jxcore-log: 
,03-30 14:14:35.059  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:35.060  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:35.060  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 14:14:35.060  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:14:35.064  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:35.068  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 14:14:35.068  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:35.068  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 14:14:35.068  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:35.069  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:35.069  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:14:35.070  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:35.070  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 14:14:35.070  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 14:14:35.070  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:35.071  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:14:35.071  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:35.072  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:14:35.072  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:35.073  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:35.073  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:35.074  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:14:35.074  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:35.084  3665  3742 I jxcore-log: ok 145 Should be able to call stopListeningForAdvertisments in teardown,
03-30 14:14:35.084  3665  3742 I jxcore-log: 
03-30 14:14:35.086  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:35.086  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:35.086  3665  3742 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-30 14:14:35.086  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:35.086  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:35.086  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 14:14:35.086  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:35.087  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:14:35.088  3665  3742 D BluetoothLeScanner: could not find callback wrapper
03-30 14:14:35.088  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:35.091  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:35.091  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:35.091  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:14:35.091  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-30 14:14:35.091  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:35.091  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:35.092  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:35.092  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 14:14:35.094  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:35.094  3665  3742 I jxcore-log: 
,03-30 14:14:35.099  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 14:14:35.099   821  3150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:35.110  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:35.111  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:35.111  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:35.116  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:35.116  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:14:35.116  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:35.117  3665  3742 I jxcore-log: ok 146 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:14:35.117  3665  3742 I jxcore-log: 
,03-30 14:14:35.123  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:35.123  3665  3742 I jxcore-log: 
,03-30 14:14:35.124  3665  3742 I jxcore-log: # setup
03-30 14:14:35.124  3665  3742 I jxcore-log: 
,03-30 14:14:35.284  3665  3742 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
,03-30 14:14:35.284  3665  3742 I jxcore-log: 
,03-30 14:14:35.413  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-30 14:14:35.413  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:35.413  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:35.414  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:35.422  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:14:35.422  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:35.422  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:35.422  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:35.431  2152  2216 D BtGatt.GattService: registerClient() - UUID=25be5042-8136-4a8e-b861-94a0e6a1b133
,03-30 14:14:35.432  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=25be5042-8136-4a8e-b861-94a0e6a1b133, clientIf=5,
,03-30 14:14:35.433  3665  3682 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 14:14:35.434  2152  2169 D BtGatt.GattService: start scan with filters
03-30 14:14:35.437  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-30 14:14:35.437  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:35.438  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:35.438  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-30 14:14:35.443  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:35.443  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-30 14:14:35.445  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:35.446  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:35.446  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-30 14:14:35.447  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:14:35.447  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:35.449  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:14:35.449  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:35.450  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-30 14:14:35.450  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:35.450  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:14:35.451  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:35.451  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:35.451  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:14:35.454  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:14:35.454  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:35.457  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-30 14:14:35.457  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:35.464  2152  2170 D BtGatt.GattService: registerClient() - UUID=e79bd811-1d49-4b8d-8ad7-eba97e01fe18,
03-30 14:14:35.465  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=e79bd811-1d49-4b8d-8ad7-eba97e01fe18, clientIf=6
03-30 14:14:35.465  3665  3683 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:35.467  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:35.470  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:35.473  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:14:35.475  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-30 14:14:35.476  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:14:35.476  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:35.476   821  1418 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:14:35.479  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:35.479  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 14:14:35.479  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:14:35.479  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:35.480  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 14:14:35.480  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-30 14:14:35.480  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:14:35.480  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:14:35.480  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:35.480  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:35.480  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:35.480  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:35.480  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:35.480  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-30 14:14:35.481  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:35.481  3665  3665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:35.481  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:35.481  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:35.481  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:35.481  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:14:35.481  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:35.482  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:35.482  3665  3742 I jxcore-log: 
,03-30 14:14:35.484  3665  3742 I jxcore-log: ok 147 Can call startUpdateAdvertisingAndListening without error,
03-30 14:14:35.484  3665  3742 I jxcore-log: 
03-30 14:14:35.484   821  1414 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:14:35.485  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-30 14:14:35.485  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-30 14:14:35.485  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:14:35.485  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:14:35.485  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
,03-30 14:14:35.485  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-30 14:14:35.485  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:35.485  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:35.485  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:14:35.485  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-30 14:14:35.485  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:14:35.485  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:14:35.486  3665  4037 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:35.487  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:35.488  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 14:14:35.490  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 14:14:35.490  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:35.490  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:35.490  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-30 14:14:35.490  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:14:35.490  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:35.490  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-30 14:14:35.490  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-30 14:14:35.490  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:35.490  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-30 14:14:35.491  3665  4037 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-30 14:14:35.491  3665  4037 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:14:35.491  3665  4037 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-30 14:14:35.493  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:14:35.493  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:35.494  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:14:35.495  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-30 14:14:35.495  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 14:14:35.496  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-30 14:14:35.496  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:35.496  2152  2214 D BtGatt.GattService: current time is 219063644289
03-30 14:14:35.496  2152  2214 D BtGatt.GattService: Batch record : [6, -25, -4, -23, 2, 85, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-30 14:14:35.496  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:35.499  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 14:14:35.499  2152  2214 D BtGatt.GattService: Client app is not null!,
,03-30 14:14:35.503  2152  2170 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-30 14:14:35.504  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-30 14:14:35.504  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:35.504  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-30 14:14:35.504  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:14:35.504  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
03-30 14:14:35.504  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:35.504  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:35.504  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:14:35.505  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-30 14:14:35.505  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:35.505  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:35.505  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:35.505  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:35.508  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:35.508  3665  3742 I jxcore-log: 
03-30 14:14:35.508  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:35.508  3665  3742 I jxcore-log: 
03-30 14:14:35.511  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 14:14:35.512   821  1150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:35.517  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-30 14:14:35.517  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 14:14:35.517  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:35.520  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:35.520  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:14:35.520  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-30 14:14:35.520  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:14:35.520  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:35.520  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:35.520  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:35.521  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:35.521  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-30 14:14:35.522  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:35.522  3665  3742 I jxcore-log: 
,03-30 14:14:35.526  3665  3742 I jxcore-log: ok 148 Can call stopAdvertisingAndListening without error
03-30 14:14:35.526  3665  3742 I jxcore-log: 
,03-30 14:14:35.532  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:35.532  3665  3742 I jxcore-log: 
,03-30 14:14:35.534  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:35.534  3665  3742 I jxcore-log: 
,03-30 14:14:35.536  3665  3742 I jxcore-log: # teardown
03-30 14:14:35.536  3665  3742 I jxcore-log: 
,03-30 14:14:35.889  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:35.889  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:35.889  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:35.897  3665  3742 I jxcore-log: ok 149 Should be able to call stopListeningForAdvertisments in teardown
03-30 14:14:35.897  3665  3742 I jxcore-log: 
,03-30 14:14:35.899  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:35.900  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-30 14:14:35.900  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:35.905  3665  3742 I jxcore-log: ok 150 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:14:35.905  3665  3742 I jxcore-log: 
,03-30 14:14:35.916  3665  3742 I jxcore-log: # setup
03-30 14:14:35.916  3665  3742 I jxcore-log: 
,03-30 14:14:35.995  3665  3742 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-30 14:14:35.995  3665  3742 I jxcore-log: 
,03-30 14:14:36.117  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-30 14:14:36.117  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:36.117  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:36.117  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:36.122  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:14:36.123  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:36.123  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:36.123  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:36.127  2152  2170 D BtGatt.GattService: registerClient() - UUID=e4c2f3ae-23fa-4d7b-8216-bed75f0f28b2
,03-30 14:14:36.128  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=e4c2f3ae-23fa-4d7b-8216-bed75f0f28b2, clientIf=5
,03-30 14:14:36.128  3665  3683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
03-30 14:14:36.129  2152  2216 D BtGatt.GattService: start scan with filters
03-30 14:14:36.130  2152  2225 D BtGatt.ScanManager: handling starting scan
03-30 14:14:36.130  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 14:14:36.130  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:36.130  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:36.130  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:36.130  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:36.132  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-30 14:14:36.132  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:14:36.132  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:36.132  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:14:36.132  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:36.134  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-30 14:14:36.134  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:36.138  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:14:36.138  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-30 14:14:36.138  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:36.138  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:14:36.140  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 14:14:36.141  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:14:36.141  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:14:36.141  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:36.143  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:14:36.143  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:36.149  2152  2169 D BtGatt.GattService: registerClient() - UUID=303abfda-5d76-472c-8f55-34bde0845ed7,
03-30 14:14:36.150  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=303abfda-5d76-472c-8f55-34bde0845ed7, clientIf=6
03-30 14:14:36.150  3665  3682 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 14:14:36.151  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:36.154  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:36.158  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:14:36.161  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 14:14:36.162  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:14:36.162  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:36.163   821  1321 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:36.168  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:36.169  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-30 14:14:36.169  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:14:36.169  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:36.170  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-30 14:14:36.171  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:14:36.171  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:14:36.171  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:14:36.171  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:36.171  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:36.172  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:36.172  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:36.172  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:36.172  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:14:36.172  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:36.173  3665  3665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:14:36.173  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:36.173  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:36.173  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-30 14:14:36.173   821  1418 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:14:36.174  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:14:36.175  3665  4038 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-30 14:14:36.175  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:36.175  3665  3742 I jxcore-log: 
,03-30 14:14:36.175  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:36.180  3665  3742 I jxcore-log: ok 151 Can call startUpdateAdvertisingAndListening without error
03-30 14:14:36.180  3665  3742 I jxcore-log: 
,03-30 14:14:36.184  3665  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-30 14:14:36.185  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-30 14:14:36.185  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:36.185  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:36.185  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:36.185  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:36.186  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:36.186  3665  3742 I jxcore-log: 
03-30 14:14:36.186  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:36.186  3665  3742 I jxcore-log: 
,03-30 14:14:36.187  3665  3742 I jxcore-log: ok 152 Can call startUpdateAdvertisingAndListening twice without error
03-30 14:14:36.187  3665  3742 I jxcore-log: 
03-30 14:14:36.190  3665  3742 I jxcore-log: # teardown
03-30 14:14:36.190  3665  3742 I jxcore-log: 
,03-30 14:14:36.648  2152  2152 D BtGatt.ScanManager: awakened up at time 220215
,03-30 14:14:36.650  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:14:36.668  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-30 14:14:36.668  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:36.669  2152  2214 D BtGatt.GattService: current time is 220236124028
,03-30 14:14:36.669  2152  2214 D BtGatt.GattService: Batch record : [-40, 27, -3, -79, -5, 116, 1, -128, -82, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 14:14:36.669  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:36.669  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-30 14:14:36.671  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-30 14:14:36.672  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-30 14:14:36.672  3665  3665 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-30 14:14:36.673  3665  3665 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-30 14:14:36.677  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-30 14:14:36.677  3665  3742 I jxcore-log: 
,03-30 14:14:36.679  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
03-30 14:14:36.679  3665  3742 I jxcore-log: 
,03-30 14:14:36.828  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:14:36.829  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 14:14:36.829  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 14:14:36.829  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:14:36.833  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:36.836  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 14:14:36.837  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 14:14:36.837  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:36.837  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:36.839  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:36.839  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:36.840  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:14:36.840  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:36.841  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:14:36.844  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:36.845  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:14:36.845  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:14:36.845  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:36.845  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:36.846  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-30 14:14:36.846  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:36.847  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-30 14:14:36.847  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:36.847  2152  2214 D BtGatt.GattService: current time is 220414511424
03-30 14:14:36.847  2152  2214 D BtGatt.GattService: Batch record : [-40, 27, -3, -79, -5, 116, 1, -128, -65, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -62, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-30 14:14:36.848  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-30 14:14:36.848  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 14:14:36.852  3665  3742 I jxcore-log: ok 153 Should be able to call stopListeningForAdvertisments in teardown
03-30 14:14:36.852  3665  3742 I jxcore-log: 
03-30 14:14:36.853  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:36.854  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-30 14:14:36.854  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-30 14:14:36.854  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:14:36.854  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:14:36.854  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:14:36.854  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:36.854  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:36.854  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:14:36.854  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:36.855  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 14:14:36.855  3665  4038 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:14:36.855  3665  4038 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:14:36.856  3665  4038 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:14:36.856  3665  3742 D BluetoothLeScanner: could not find callback wrapper
03-30 14:14:36.857  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:36.857  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 14:14:36.861  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-30 14:14:36.862  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 14:14:36.866  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 14:14:36.866  2152  2214 D BtGatt.GattService: Client app is not null!
,03-30 14:14:36.868  2152  2170 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 14:14:36.869  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-30 14:14:36.869  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:36.869  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:14:36.870  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-30 14:14:36.870  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-30 14:14:36.870  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:36.871  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:36.871  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:14:36.872  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:14:36.872  3665  3742 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-30 14:14:36.873  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:36.873  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:36.873  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:36.873  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 14:14:36.883  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:36.883  3665  3742 I jxcore-log: 
,03-30 14:14:36.891  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:14:36.891   821  1322 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:36.898  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:36.898  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:36.898  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:36.901  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-30 14:14:36.901  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:14:36.901  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:36.901  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:36.901  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:36.901  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:36.902  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 14:14:36.904  3665  3742 I jxcore-log: ok 154 Should be able to call stopAdvertisingAndListening in teardown,
03-30 14:14:36.904  3665  3742 I jxcore-log: 
,03-30 14:14:36.918  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-30 14:14:36.918  3665  3742 I jxcore-log: 
,03-30 14:14:36.921  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-30 14:14:36.921  3665  3742 I jxcore-log: 
,03-30 14:14:36.924  3665  3742 I jxcore-log: # setup
03-30 14:14:36.924  3665  3742 I jxcore-log: 
,03-30 14:14:37.089  3665  3742 I jxcore-log: # 39. peerAvailabilityChange is called
03-30 14:14:37.089  3665  3742 I jxcore-log: 
,03-30 14:14:37.222  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-30 14:14:37.223  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:37.223  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:37.223  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:37.231  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-30 14:14:37.231  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:14:37.231  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:37.231  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:37.240  2152  2170 D BtGatt.GattService: registerClient() - UUID=acf298b0-2f9c-4540-b70c-a8ed365bbf4e
03-30 14:14:37.241  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=acf298b0-2f9c-4540-b70c-a8ed365bbf4e, clientIf=5,
03-30 14:14:37.241  3665  3683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:14:37.242  2152  2216 D BtGatt.GattService: start scan with filters
,03-30 14:14:37.245  2152  2225 D BtGatt.ScanManager: handling starting scan
03-30 14:14:37.245  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:37.245  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 14:14:37.246  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:37.246  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:37.246  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:14:37.246  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:37.247  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:37.247  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:14:37.247  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:14:37.247  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:37.248  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 14:14:37.248  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:37.250  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-30 14:14:37.250  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:37.253  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:14:37.253  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-30 14:14:37.253  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:37.254  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:14:37.257  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 14:14:37.258  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:37.260  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:14:37.260  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:37.264  2152  2170 D BtGatt.GattService: registerClient() - UUID=8d2c7e81-67be-4a58-90ee-9130415742bc
,03-30 14:14:37.265  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=8d2c7e81-67be-4a58-90ee-9130415742bc, clientIf=6
,03-30 14:14:37.265  3665  3682 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 14:14:37.268  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:37.275  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:37.279  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:14:37.283  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 14:14:37.284  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:14:37.284  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:37.285   821  3150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:37.292  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:37.293  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:37.293  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-30 14:14:37.293  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:37.294  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-30 14:14:37.295  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:14:37.295  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:14:37.295  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-30 14:14:37.295  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:37.295  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-30 14:14:37.296  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:37.296  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:37.296  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:37.296  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:14:37.296  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:37.296  3665  3665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:14:37.297  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:37.297  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:37.297  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:37.297  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-30 14:14:37.297  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:37.300   821  1414 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-30 14:14:37.302  3665  4039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-30 14:14:37.306  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:37.306  3665  3742 I jxcore-log: 
,03-30 14:14:37.308  3665  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-30 14:14:37.310  3665  3742 I jxcore-log: ok 155 Can call startUpdateAdvertisingAndListeningwithout error
03-30 14:14:37.310  3665  3742 I jxcore-log: 
,03-30 14:14:37.316  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-30 14:14:37.317  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:37.317  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-30 14:14:37.317  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:37.317  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:37.320  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:37.320  3665  3742 I jxcore-log: 
,03-30 14:14:37.336  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:37.336  3665  3742 I jxcore-log: 
,03-30 14:14:37.339  3665  3742 I jxcore-log: ok 156 Can call startListeningForAdvertisements without error
03-30 14:14:37.339  3665  3742 I jxcore-log: 
,03-30 14:14:37.764  2152  2152 D BtGatt.ScanManager: awakened up at time 221331
,03-30 14:14:37.767  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:14:37.778  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3,
,03-30 14:14:37.778  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:37.779  2152  2214 D BtGatt.GattService: current time is 221346026580
,03-30 14:14:37.779  2152  2214 D BtGatt.GattService: Batch record : [116, 40, 116, -111, 105, 89, 1, -128, -83, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 14:14:37.780  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:37.780  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-30 14:14:37.781  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 14:14:37.784  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-30 14:14:37.785  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 1
,03-30 14:14:37.786  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-30 14:14:37.786  3665  3665 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-30 14:14:37.787  3665  3665 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-30 14:14:37.792  3665  3742 I jxcore-log: ok 157 peers must be an array
03-30 14:14:37.792  3665  3742 I jxcore-log: 
,03-30 14:14:37.818  3665  3742 I jxcore-log: ok 158 peers must not be zero-length
03-30 14:14:37.818  3665  3742 I jxcore-log: 
,03-30 14:14:37.819  3665  3742 I jxcore-log: ok 159 peer must have peerIdentifier
03-30 14:14:37.819  3665  3742 I jxcore-log: 
,03-30 14:14:37.820  3665  3742 I jxcore-log: ok 160 peerIdentifier must be a string
03-30 14:14:37.820  3665  3742 I jxcore-log: 
,03-30 14:14:37.820  3665  3742 I jxcore-log: ok 161 peer must have peerAvailable
03-30 14:14:37.820  3665  3742 I jxcore-log: 
03-30 14:14:37.820  3665  3742 I jxcore-log: ok 162 peer must have pleaseConnect
03-30 14:14:37.820  3665  3742 I jxcore-log: 
,03-30 14:14:37.827  3665  3742 I jxcore-log: # teardown
03-30 14:14:37.827  3665  3742 I jxcore-log: 
,03-30 14:14:38.791  2152  2152 D BtGatt.ScanManager: awakened up at time 222358
,03-30 14:14:38.793  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:14:38.805  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-30 14:14:38.805  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:38.806  2152  2214 D BtGatt.GattService: current time is 222373091423
,03-30 14:14:38.806  2152  2214 D BtGatt.GattService: Batch record : [116, 40, 116, -111, 105, 89, 1, -128, -82, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 14:14:38.807  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-30 14:14:38.807  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 14:14:38.810  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-30 14:14:38.811  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-30 14:14:39.400  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:14:39.401  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 14:14:39.401  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 14:14:39.401  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:14:39.405  2152  2170 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:39.408  2152  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 14:14:39.409  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 14:14:39.409  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:39.409  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:39.409  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:39.409  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:39.410  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:39.410  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:14:39.410  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:14:39.410  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:39.411  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:39.411  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 14:14:39.411  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:39.414  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:14:39.414  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:39.414  3665  3742 I jxcore-log: ok 163 Should be able to call stopListeningForAdvertisments in teardown
03-30 14:14:39.414  3665  3742 I jxcore-log: 
03-30 14:14:39.414  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:14:39.416  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:39.417  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-30 14:14:39.417  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:14:39.417  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-30 14:14:39.417  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:14:39.418  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-30 14:14:39.418  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:39.418  2152  2214 D BtGatt.GattService: current time is 222985237881
03-30 14:14:39.418  2152  2214 D BtGatt.GattService: Batch record : [116, 40, 116, -111, 105, 89, 1, -128, -82, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 14:14:39.418  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:39.418  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-30 14:14:39.420  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-30 14:14:39.420  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:39.420  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:39.420  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:14:39.420  3665  4039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:14:39.420  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:39.420  3665  4039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:14:39.421  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:14:39.420  3665  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:14:39.422  3665  3742 D BluetoothLeScanner: could not find callback wrapper
03-30 14:14:39.422  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:39.422  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 14:14:39.424  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-30 14:14:39.425  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 14:14:39.428  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-30 14:14:39.428  2152  2214 D BtGatt.GattService: Client app is not null!
03-30 14:14:39.429  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:14:39.429  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-30 14:14:39.431  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:14:39.432  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-30 14:14:39.433  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-30 14:14:39.433  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-30 14:14:39.434  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:39.434  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-30 14:14:39.436  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:14:39.439  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-30 14:14:39.440  3665  3742 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-30 14:14:39.440  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:39.440  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:39.440  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:39.440  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:39.452  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:39.452  3665  3742 I jxcore-log: 
,03-30 14:14:39.453  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 14:14:39.454   821  1418 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:39.462  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:39.464  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:39.464  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:39.468  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:14:39.468  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:14:39.468  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:39.468  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:39.468  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:39.469  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:39.469  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-30 14:14:39.470  3665  3742 I jxcore-log: ok 164 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:14:39.470  3665  3742 I jxcore-log: 
,03-30 14:14:39.477  3665  3742 I jxcore-log: # setup
03-30 14:14:39.477  3665  3742 I jxcore-log: 
,03-30 14:14:39.479  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:39.479  3665  3742 I jxcore-log: 
,03-30 14:14:39.484  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:39.484  3665  3742 I jxcore-log: 
,03-30 14:14:39.557  3665  3742 I jxcore-log: # 40. Can connect to a remote peer
03-30 14:14:39.557  3665  3742 I jxcore-log: 
,03-30 14:14:42.380  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 49488, start advertisements: true
03-30 14:14:42.380  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:42.380  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:42.380  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:42.386  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-30 14:14:42.386  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:14:42.386  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:42.386  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:42.392  2152  2170 D BtGatt.GattService: registerClient() - UUID=11dda6ae-d328-4a6a-881c-9842ac377a37
03-30 14:14:42.392  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=11dda6ae-d328-4a6a-881c-9842ac377a37, clientIf=5
,03-30 14:14:42.393  3665  3682 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:14:42.393  2152  2216 D BtGatt.GattService: start scan with filters
,03-30 14:14:42.394  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 14:14:42.394  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:42.394  2152  2225 D BtGatt.ScanManager: handling starting scan
03-30 14:14:42.394  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:42.395  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:42.395  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:42.395  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:42.395  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:14:42.395  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:14:42.395  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:14:42.396  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:42.396  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:42.396  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:42.400  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:14:42.400  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:42.402  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:14:42.402  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:42.403  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
,03-30 14:14:42.403  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:14:42.405  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 14:14:42.406  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:42.407  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:14:42.407  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:42.408  2152  2169 D BtGatt.GattService: registerClient() - UUID=a6e6be6d-53aa-4b6d-9d4c-11ee065c5942
03-30 14:14:42.408  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=a6e6be6d-53aa-4b6d-9d4c-11ee065c5942, clientIf=6
,03-30 14:14:42.409  3665  3683 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:42.412  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:42.416  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:42.420  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:14:42.422  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 14:14:42.423  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:14:42.423  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:42.424   821  1101 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:42.431  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:42.431  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:42.431  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:14:42.431  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:42.433  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-30 14:14:42.434  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:14:42.434  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:14:42.434  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-30 14:14:42.434  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:42.435  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:42.435  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-30 14:14:42.435  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:42.436  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:42.436  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:14:42.436  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:42.437  3665  3665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:42.437   821  3580 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:14:42.437  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:42.437  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-30 14:14:42.437  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:42.438  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:42.438  3665  3742 I jxcore-log: 
03-30 14:14:42.438  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:14:42.438  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:42.439  3665  4041 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-30 14:14:42.441  3665  3742 I jxcore-log: ok 165 Can call startUpdateAdvertisingAndListening without error
03-30 14:14:42.441  3665  3742 I jxcore-log: 
,03-30 14:14:42.444  3665  4041 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-30 14:14:42.448  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 49488, start advertisements: false
03-30 14:14:42.448  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:42.448  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-30 14:14:42.449  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:42.449  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:42.452  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:42.452  3665  3742 I jxcore-log: 
,03-30 14:14:42.456  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:42.456  3665  3742 I jxcore-log: 
,03-30 14:14:42.459  3665  3742 I jxcore-log: ok 166 Can call startListeningForAdvertisements without error,
03-30 14:14:42.459  3665  3742 I jxcore-log: 
,03-30 14:14:43.416  2152  2152 D BtGatt.ScanManager: awakened up at time 226983,
03-30 14:14:43.419  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:14:43.429  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-30 14:14:43.429  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:43.429  2152  2214 D BtGatt.GattService: current time is 226996498297
03-30 14:14:43.429  2152  2214 D BtGatt.GattService: Batch record : [79, -94, -49, -106, 88, 74, 1, -128, -82, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-30 14:14:43.430  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:43.431  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 14:14:43.434  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-30 14:14:43.436  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-30 14:14:43.437  3665  3665 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-30 14:14:43.438  3665  3665 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-30 14:14:43.441  3665  3742 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-30 14:14:43.441  3665  3742 I jxcore-log: 
,03-30 14:14:43.455  3665  3742 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,03-30 14:14:43.455  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-30 14:14:43.462  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,03-30 14:14:43.464  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-30 14:14:43.464  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-30 14:14:43.466  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
,03-30 14:14:43.466  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-30 14:14:43.467  3665  3742 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-30 14:14:43.468  3665  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 397)
,03-30 14:14:43.469  3665  4042 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-30 14:14:43.471  3665  3742 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-30 14:14:43.471  3665  3742 I jxcore-log: 
03-30 14:14:43.474  2152  2170 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-30 14:14:45.745  2152  2226 W bt-btif : info:x10,
03-30 14:14:45.746  2152  2214 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-30 14:14:45.746  2152  2214 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-30 14:14:45.788  2152  2226 W bt-btif : info:x10
,03-30 14:14:45.788  2152  2214 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-30 14:14:45.789  2152  2214 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-30 14:14:45.928  2152  2226 E bt-btm  : tBTM_SEC_DEV:0xa2fa4eb4 rs_disc_pending=0
,03-30 14:14:45.928  2152  2226 W bt-btif : bta_dm_check_av:0
03-30 14:14:45.928  2152  2214 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:46.079  2152  2226 W bt-sdp  : process_service_search_attr_rsp
,03-30 14:14:46.148  2152  2226 E bt-btm  : tBTM_SEC_DEV:0xa2fa507c rs_disc_pending=0
,03-30 14:14:46.148  2152  2226 W bt-btif : bta_dm_check_av:0
03-30 14:14:46.148  2152  2214 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:46.426  2152  2226 W bt-rfcomm: PORT_StartCnf failed result:5
,03-30 14:14:46.427  2152  2319 W bt-btif : invalid rfc slot id: 10
03-30 14:14:46.427  2152  2214 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
03-30 14:14:46.428  3665  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 397)
,03-30 14:14:46.428  3665  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 397)
03-30 14:14:46.429  3665  4042 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 397)
03-30 14:14:46.430  3665  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Thread ID: 397
,03-30 14:14:46.431  3665  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdownBluetoothClientThread: Thread ID: 397
03-30 14:14:46.431  3665  3665 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> E0:DB:10:14:E2:C0]: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,03-30 14:14:46.432  3665  3665 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> E0:DB:10:14:E2:C0], error message: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
03-30 14:14:46.432  3665  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 397)
,03-30 14:14:46.433  3665  3665 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed
03-30 14:14:46.433  3665  3665 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
03-30 14:14:46.436  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
03-30 14:14:46.438  3665  4043 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 397
03-30 14:14:46.438  3665  4043 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 397)
03-30 14:14:46.438  3665  4043 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 397)
,03-30 14:14:46.445  3665  3742 I jxcore-log: INFO testThaliMobileNative: Connect returned an error: Connection to peer [<no peer name> E0:DB:10:14:E2:C0] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
03-30 14:14:46.445  3665  3742 I jxcore-log: 
,03-30 14:14:46.446  3665  3742 I jxcore-log: INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
03-30 14:14:46.446  3665  3742 I jxcore-log: 
,03-30 14:14:46.454  2152  2214 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-30 14:14:46.454  2152  2214 I BluetoothBondStateMachine: No record of the device:null
03-30 14:14:46.454  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 9 Address: E0:DB:10:14:E2:C0 newState: 0
03-30 14:14:46.454  2152  2215 E BluetoothBondStateMachine: In stable state, received invalid newState: 10
,03-30 14:14:46.500  2152  2226 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-30 14:14:46.500  2152  2226 E bt-btm  : Device not in IRK list
03-30 14:14:46.500  2152  2226 E bt-btif : Do not find the bg connection mask for the remote device
03-30 14:14:46.500  2152  2214 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-30 14:14:46.661  2152  2214 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-30 14:14:46.669  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-30 14:14:46.670  2152  2214 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-30 14:14:46.675  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11,
03-30 14:14:46.675  2152  2215 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-30 14:14:46.745   821   855 I ActivityManager: Start proc 4044:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-30 14:14:46.801  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-30 14:14:46.801  2152  2215 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-30 14:14:46.814  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-30 14:14:46.835  2152  2215 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-30 14:14:46.860   821   859 D BluetoothManagerService: Message: 20
03-30 14:14:46.860   821   859 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26f172d3:true
,03-30 14:14:46.863   821  1418 I ActivityManager: Killing 3555:com.google.android.apps.books/u0a34 (adj 15): empty #17
,03-30 14:14:47.147  2152  2226 W bt-btif : new conn_srvc id:26, app_id:255
03-30 14:14:47.147  2152  2226 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-30 14:14:47.147  2152  2226 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-30 14:14:47.148  3665  4041 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-30 14:14:47.150  3665  4041 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 399),
,03-30 14:14:47.150  3665  4041 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-30 14:14:47.152   821  3150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:47.155  3665  4064 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 399)
03-30 14:14:47.155  3665  4041 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:47.161  3665  4041 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:14:47.191  3665  4064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 399)
,03-30 14:14:47.195  3665  4064 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-30 14:14:47.196  3665  4064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 399)
,03-30 14:14:47.196  3665  4064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 399
03-30 14:14:47.196  3665  4064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 399)
03-30 14:14:47.196  3665  4064 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-30 14:14:47.197  3665  4064 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 399)
03-30 14:14:47.198  3665  3665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-30 14:14:47.199  3665  3665 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-30 14:14:47.199  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-30 14:14:47.201  3665  3665 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-30 14:14:47.202  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-30 14:14:47.203  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-30 14:14:47.203  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:47.203  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 14:14:47.203  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:14:47.203  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:14:47.203  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 14:14:47.207  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-30 14:14:47.208  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 14:14:47.213  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-30 14:14:47.213  2152  2214 D BtGatt.GattService: Client app is not null!
,03-30 14:14:47.215  2152  2170 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 14:14:47.217  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:47.217  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:47.217  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:47.217  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-30 14:14:47.218  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:14:47.219  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:14:47.219  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:47.219  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:47.219  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:14:47.228  2152  2216 D BtGatt.GattService: registerClient() - UUID=a441ce8d-22d0-4552-968f-af3a02961b79
,03-30 14:14:47.228  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=a441ce8d-22d0-4552-968f-af3a02961b79, clientIf=6
03-30 14:14:47.229  3665  3683 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:47.230  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:47.235  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:47.238  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-30 14:14:47.241  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 14:14:47.242  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:14:47.244  2152  2170 D BtGatt.GattService: stopScan() - queue size =1,
,03-30 14:14:47.247  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 14:14:47.247  2152  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 14:14:47.247  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.247  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:47.247  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:47.247  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:47.247  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:47.247  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:47.247  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:47.247  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:47.250  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:14:47.250  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:47.251  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:14:47.254  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-30 14:14:47.254  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:47.254  2152  2214 D BtGatt.GattService: current time is 230821978295
03-30 14:14:47.254  2152  2216 D BtGatt.GattService: registerClient() - UUID=7ad58187-20ce-4045-814e-e223260c4574
03-30 14:14:47.255  2152  2214 D BtGatt.GattService: Batch record : [79, -94, -49, -106, 88, 74, 1, -128, -82, 44, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -57, 44, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 14:14:47.255  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:47.255  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 14:14:47.255  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=7ad58187-20ce-4045-814e-e223260c4574, clientIf=5
03-30 14:14:47.256  3665  3683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:14:47.256  2152  2169 D BtGatt.GattService: start scan with filters
03-30 14:14:47.257  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 14:14:47.257  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-30 14:14:47.257  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-30 14:14:47.258  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:47.258  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:47.258  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 14:14:47.258  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 14:14:47.258  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:14:47.258  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:14:47.261  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-30 14:14:47.262  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 14:14:47.264  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-30 14:14:47.264  2152  2214 D BtGatt.GattService: Client app is not null!
03-30 14:14:47.266  2152  2225 D BtGatt.ScanManager: handling starting scan
03-30 14:14:47.267  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:14:47.268  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:14:47.268  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:47.269  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-30 14:14:47.269  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-30 14:14:47.269  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:14:47.269  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:47.269  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:14:47.269  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:14:47.270  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:47.270  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:47.270  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:47.270  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:14:47.270  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.271  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:47.271  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:14:47.273  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 14:14:47.273  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.274  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:14:47.274  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.275  2152  2216 D BtGatt.GattService: registerClient() - UUID=18676e60-5f5f-4e1e-b811-d12f6c262d76
03-30 14:14:47.275  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=18676e60-5f5f-4e1e-b811-d12f6c262d76, clientIf=6
03-30 14:14:47.276  3665  3683 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:47.277  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:47.281  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:47.284  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:14:47.286  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 14:14:47.287  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:14:47.289  2152  2169 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:47.290  2152  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 14:14:47.291  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-30 14:14:47.291  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:14:47.291  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-30 14:14:47.291  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:47.291  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:47.291  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:47.292  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 14:14:47.292  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.292  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:47.295  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:14:47.295  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.295  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:14:47.295  2152  2216 D BtGatt.GattService: registerClient() - UUID=118ef470-c6a9-4698-8a60-800ead37664a
03-30 14:14:47.295  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=118ef470-c6a9-4698-8a60-800ead37664a, clientIf=5
03-30 14:14:47.296  3665  3683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:14:47.296  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:14:47.296  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.296  2152  2169 D BtGatt.GattService: start scan with filters
03-30 14:14:47.300  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 14:14:47.300  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:47.300  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-30 14:14:47.300  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:47.300  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:47.300  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 14:14:47.300  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
,03-30 14:14:47.300  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:14:47.300  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:14:47.302  2152  2224 D BtGatt.AdvertiseManager: message : 1,
03-30 14:14:47.302  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 14:14:47.304  2152  2225 D BtGatt.ScanManager: handling starting scan
03-30 14:14:47.306  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-30 14:14:47.306  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.308  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 14:14:47.308  2152  2214 D BtGatt.GattService: Client app is not null!
,03-30 14:14:47.309  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:14:47.310  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:47.310  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-30 14:14:47.310  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:14:47.310  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:47.310  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:14:47.310  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:14:47.310  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:14:47.310  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:47.310  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:47.310  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:47.311  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:47.311  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:14:47.311  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:47.313  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:14:47.313  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:47.314  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-30 14:14:47.314  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.316  2152  2170 D BtGatt.GattService: registerClient() - UUID=63c234ef-ef66-4d65-b46b-0a650d356ffe
03-30 14:14:47.316  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=63c234ef-ef66-4d65-b46b-0a650d356ffe, clientIf=6
03-30 14:14:47.317  3665  3683 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:47.318  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:47.320  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising,
,03-30 14:14:47.322  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-30 14:14:47.325  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-30 14:14:47.325  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:14:47.326  2152  2170 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:14:47.327  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 14:14:47.328  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 14:14:47.328  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.328  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:47.328  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:47.328  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:47.328  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:47.328  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:47.328  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:47.328  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:47.330  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:14:47.330  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.330  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:14:47.330  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:14:47.331  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:47.332  2152  2170 D BtGatt.GattService: registerClient() - UUID=67a803be-2283-4b90-b6cd-69fd713e0db6
,03-30 14:14:47.332  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=67a803be-2283-4b90-b6cd-69fd713e0db6, clientIf=5,
03-30 14:14:47.333  3665  3683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:14:47.333  2152  2169 D BtGatt.GattService: start scan with filters
03-30 14:14:47.334  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:47.334  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 14:14:47.334  3665  3665 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-30 14:14:47.334  3665  3665 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-30 14:14:47.334  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:47.334  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:47.334  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:47.335  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-30 14:14:47.335  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:47.335  2152  2225 D BtGatt.ScanManager: handling starting scan
03-30 14:14:47.335  3665  4065 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 400)
03-30 14:14:47.336  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:14:47.337  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:47.338  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:14:47.338  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.338  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:47.338  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 14:14:47.339  3665  4065 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 49488
,03-30 14:14:47.339  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:14:47.339  3665  4065 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-30 14:14:47.339  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:47.340  3665  4065 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-30 14:14:47.340  3665  4065 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-30 14:14:47.341  3665  4067 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 401, name: Sender)
03-30 14:14:47.341  3665  4065 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 400)
03-30 14:14:47.341  3665  4065 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 400)
,03-30 14:14:47.342  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:14:47.342  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:47.343  3665  4068 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 402, name: Receiver)
,03-30 14:14:49.459  3665  3742 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
03-30 14:14:49.459  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> E0:DB:10:14:E2:C0]
,03-30 14:14:49.464  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
03-30 14:14:49.465  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
03-30 14:14:49.465  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-30 14:14:49.466  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null E0:DB:10:14:E2:C0
03-30 14:14:49.466  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address E0:DB:10:14:E2:C0
03-30 14:14:49.466  3665  3742 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,03-30 14:14:49.468  3665  4069 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 403)
,03-30 14:14:49.469  3665  4069 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
03-30 14:14:49.469  3665  4069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:49.475  2152  2170 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-30 14:14:49.564   821   854 I ActivityManager: Start proc 4070:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-30 14:14:49.644  3467  4087 V KeepSync: Connecting to GoogleApiClient
,03-30 14:14:49.667  2152  2226 E bt-btm  : tBTM_SEC_DEV:0xa2fa507c rs_disc_pending=1
03-30 14:14:49.667  2152  2226 W bt-btif : bta_dm_check_av:0
03-30 14:14:49.667  2152  2214 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:49.702  1235  1492 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-30 14:14:49.705  1235  1492 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-30 14:14:49.726  1252  1252 I ConfigService: onCreate
,03-30 14:14:49.736  1252  1269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-30 14:14:49.736  1252  1269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:49.736  1252  1269 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:49.736  1252  1269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:49.747  1252  1269 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:49.749  4070  4070 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-30 14:14:49.759  4070  4070 I BooksApp: Created application version: 3.6.8 (30608)
,03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: Handling authorization failure
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-30 14:14:49.764  1774  4089 E ClientConnectionOperation: 	... 7 more
,03-30 14:14:49.765  3467  4087 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-30 14:14:49.767  3467  4087 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-30 14:14:49.772  3467  4087 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-30 14:14:49.773  3467  4087 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-30 14:14:49.829  1252  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-30 14:14:49.829  1252  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:49.829  1252  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:49.829  1252  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:49.832  1252  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:49.845  4070  4098 I BooksSync: Starting books sync for 61035162, extras: ade
,03-30 14:14:49.871  3467  4087 E KeepSync: IOException
03-30 14:14:49.871  3467  4087 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-30 14:14:49.871  3467  4087 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-30 14:14:49.871  3467  4087 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140),
03-30 14:14:49.871  3467  4087 E KeepSync: 	... 10 more
03-30 14:14:49.871  3467  4087 W KeepSync: Sync result 2
,03-30 14:14:49.880   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 204234, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-30 14:14:49.967  4070  4105 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-30 14:14:50.083  1252  1270 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-30 14:14:50.084  1252  1270 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:50.084  1252  1270 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:50.084  1252  1270 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:50.091  1252  1270 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-30 14:14:50.191  1252  1720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-30 14:14:50.191  1252  1720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 14:14:50.192  1252  1720 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:50.192  1252  1720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:50.200  1252  1720 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:50.231  4070  4105 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-30 14:14:50.236  4070  4098 E BooksSync: Soft error
03-30 14:14:50.236  4070  4098 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-30 14:14:50.236  4070  4098 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-30 14:14:50.237  4070  4098 E BooksSync: Sync error
03-30 14:14:50.237  4070  4098 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-30 14:14:50.237  4070  4098 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-30 14:14:50.237  4070  4098 I BooksSync: Finished books sync
,03-30 14:14:50.250   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 203486, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-30 14:14:50.311   821  1379 I ActivityManager: Killing 3745:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-30 14:14:51.081  2152  2226 W bt-btif : info:x10,
,03-30 14:14:51.081  2152  2214 D         : remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
03-30 14:14:51.082  2152  2214 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-30 14:14:51.265  2152  2226 E bt-btm  : tBTM_SEC_DEV:0xa2fa4eb4 rs_disc_pending=1
,03-30 14:14:51.265  2152  2226 W bt-btif : bta_dm_check_av:0
03-30 14:14:51.265  2152  2214 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:51.433  2152  2226 W bt-sdp  : process_service_search_attr_rsp
,03-30 14:14:51.649  2152  2214 D btif_config: btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,03-30 14:14:51.657  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,03-30 14:14:51.658  2152  2214 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-30 14:14:51.662  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,03-30 14:14:51.662  2152  2215 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-30 14:14:51.710  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
03-30 14:14:51.710  2152  2215 D BluetoothAdapterProperties: Failed to remove device: E0:DB:10:14:E2:C0
,03-30 14:14:51.713  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,03-30 14:14:51.726  2152  2215 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-30 14:14:52.181  2152  2226 E bt-btm  : tBTM_SEC_DEV:0xa2fa4eb4 rs_disc_pending=0
03-30 14:14:52.181  2152  2226 W bt-btif : bta_dm_check_av:0
03-30 14:14:52.182  2152  2214 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:52.187  2152  2226 W bt-btif : new conn_srvc id:26, app_id:1
03-30 14:14:52.188  2152  2226 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-30 14:14:52.188  2152  2226 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-30 14:14:52.188  3665  4069 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 403)
03-30 14:14:52.188  3665  4069 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 403)
03-30 14:14:52.189  3665  4069 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 404)
03-30 14:14:52.189  3665  4069 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 404)
,03-30 14:14:52.189  3665  4069 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 403)
,03-30 14:14:52.192  3665  4108 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 404)
,03-30 14:14:52.346  2152  2152 D BtGatt.ScanManager: awakened up at time 235913
,03-30 14:14:52.348  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:14:52.355  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-30 14:14:52.355  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:52.356  2152  2214 D BtGatt.GattService: current time is 235923120949
03-30 14:14:52.356  2152  2214 D BtGatt.GattService: Batch record : [104, 110, -90, 23, 41, 79, 1, -128, -96, 83, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -68, 77, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 14:14:52.357  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:52.358  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-30 14:14:52.361  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-30 14:14:52.363  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-30 14:14:52.449  2152  2226 E bt-btm  : tBTM_SEC_DEV:0xa2fa4eb4 rs_disc_pending=1
,03-30 14:14:52.449  2152  2226 W bt-btif : bta_dm_check_av:0
03-30 14:14:52.449  2152  2214 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:52.578  3665  4108 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 404)
,03-30 14:14:52.581  3665  4108 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> E0:DB:10:14:E2:C0]
,03-30 14:14:52.582  3665  4108 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 403)
03-30 14:14:52.582  3665  4108 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> E0:DB:10:14:E2:C0] (thread ID: 403)
,03-30 14:14:52.584  3665  4108 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 404)
03-30 14:14:52.584  3665  3665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> E0:DB:10:14:E2:C0]
03-30 14:14:52.585  3665  3665 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> E0:DB:10:14:E2:C0]
,03-30 14:14:52.585  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-30 14:14:52.591  3665  3665 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> E0:DB:10:14:E2:C0], created successfully
,03-30 14:14:52.591  3665  3665 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,03-30 14:14:52.592  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
03-30 14:14:52.592  3665  3665 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-30 14:14:52.594  3665  4109 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 405)
03-30 14:14:52.597  3665  4109 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 36916
03-30 14:14:52.597  3665  4109 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-30 14:14:52.597  3665  4109 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 36916 (peer ID: E0:DB:10:14:E2:C0)
,03-30 14:14:52.599  3665  4109 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "E0:DB:10:14:E2:C0" removed,
,03-30 14:14:52.605  3665  3742 I jxcore-log: INFO testThaliMobileNative: ,
03-30 14:14:52.605  3665  3742 I jxcore-log: 
,03-30 14:14:52.609  3665  3742 I jxcore-log: ok 167 Must have listeningPort
,03-30 14:14:52.609  3665  3742 I jxcore-log: 
,03-30 14:14:52.610  3665  3742 I jxcore-log: ok 168 listeningPort must be a number
03-30 14:14:52.610  3665  3742 I jxcore-log: 
,03-30 14:14:52.611  3665  3742 I jxcore-log: ok 169 Connection must have clientPort
,03-30 14:14:52.611  3665  3742 I jxcore-log: 
,03-30 14:14:52.613  3665  3742 I jxcore-log: ok 170 clientPort must be a number
03-30 14:14:52.613  3665  3742 I jxcore-log: 
,03-30 14:14:52.614  3665  3742 I jxcore-log: ok 171 Connection must have serverPort
03-30 14:14:52.614  3665  3742 I jxcore-log: 
03-30 14:14:52.614  3665  3742 I jxcore-log: ok 172 serverPort must be a number
03-30 14:14:52.614  3665  3742 I jxcore-log: ,
03-30 14:14:52.615  3665  3742 I jxcore-log: ok 173 forward connection must have clientPort == 0
03-30 14:14:52.615  3665  3742 I jxcore-log: 
,03-30 14:14:52.615  3665  3742 I jxcore-log: ok 174 forward connection must have serverPort == 0
03-30 14:14:52.615  3665  3742 I jxcore-log: 
03-30 14:14:52.620  3665  3742 I jxcore-log: # teardown
,03-30 14:14:52.620  3665  3742 I jxcore-log: 
,03-30 14:14:52.681  3665  4067 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 401, thread name: Sender)
,03-30 14:14:52.681  3665  4067 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-30 14:14:52.682  3665  4067 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-30 14:14:52.682  3665  4067 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 400
,03-30 14:14:52.682  3665  4067 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 400)
03-30 14:14:52.683  3665  4068 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 402, thread name: Receiver): bt socket closed, read return: -1
03-30 14:14:52.683  3665  4068 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 402, name: Receiver)
,03-30 14:14:52.685  3665  4067 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-30 14:14:52.685  3665  4067 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-30 14:14:52.685  3665  4067 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 402
,03-30 14:14:52.685  3665  4067 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-30 14:14:52.685  3665  4067 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 401
03-30 14:14:52.685  3665  4067 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 400)
,03-30 14:14:52.687  3665  4067 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 400)
03-30 14:14:52.687  3665  4067 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-30 14:14:52.688  3665  4067 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 401, name: Sender)
,03-30 14:14:52.692  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:14:52.692  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 14:14:52.692  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 14:14:52.692  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:14:52.696  2152  2216 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:52.698  2152  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 14:14:52.701  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 14:14:52.701  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:52.701  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:52.702  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:52.702  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:52.702  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:52.702  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:14:52.702  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:14:52.702  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:52.703  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-30 14:14:52.704  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-30 14:14:52.704  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:52.704  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 14:14:52.704  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:52.705  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:14:52.706  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:14:52.706  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:52.713  3665  3742 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-30 14:14:52.713  3665  3742 I jxcore-log: 
,03-30 14:14:52.714  3665  3742 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-30 14:14:52.714  3665  3742 I jxcore-log: 
03-30 14:14:52.715  3665  3742 I jxcore-log: ok 175 Should be able to call stopListeningForAdvertisments in teardown
03-30 14:14:52.715  3665  3742 I jxcore-log: 
03-30 14:14:52.716  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:52.716  3665  3742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> E0:DB:10:14:E2:C0]
03-30 14:14:52.716  3665  3742 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 405)
03-30 14:14:52.716  3665  3742 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 405)
03-30 14:14:52.716  3665  3742 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-30 14:14:52.716  3665  3742 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 405)
03-30 14:14:52.716  3665  3742 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 405)
03-30 14:14:52.718  3665  4109 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 405)
,03-30 14:14:52.719  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-30 14:14:52.719  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:14:52.719  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:14:52.719  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:14:52.719  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:14:52.719  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:52.719  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:52.719  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:14:52.719  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:52.719  3665  4041 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:14:52.720  3665  4041 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:14:52.720  3665  4041 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:14:52.721  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 14:14:52.722  3665  3742 D BluetoothLeScanner: could not find callback wrapper
03-30 14:14:52.722  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:52.722  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-30 14:14:52.724  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-30 14:14:52.725  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 14:14:52.727  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 14:14:52.727  2152  2214 D BtGatt.GattService: Client app is not null!,
03-30 14:14:52.728  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-30 14:14:52.728  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:52.728  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:52.728  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:14:52.728  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:14:52.728  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:14:52.728  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:52.728  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:52.728  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:14:52.729  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:14:52.729  3665  3742 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-30 14:14:52.729  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:52.729  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:52.729  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:52.729  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 14:14:52.731  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:52.731  3665  3742 I jxcore-log: 
,03-30 14:14:52.735  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:14:52.735   821  1414 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:52.740  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:14:52.741  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-30 14:14:52.741  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-30 14:14:52.741  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:14:52.741  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:52.744  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:52.744  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:52.744  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:52.744  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:52.744  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-30 14:14:52.746  3665  3742 I jxcore-log: ok 176 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:14:52.746  3665  3742 I jxcore-log: 
03-30 14:14:52.751  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:52.751  3665  3742 I jxcore-log: 
03-30 14:14:52.752  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:52.752  3665  3742 I jxcore-log: 
,03-30 14:14:52.754  3665  3742 I jxcore-log: # setup
03-30 14:14:52.754  3665  3742 I jxcore-log: 
,03-30 14:14:53.233  2152  2226 E bt-btm  : tBTM_SEC_DEV:0xa2fa4eb4 rs_disc_pending=0
03-30 14:14:53.234  2152  2226 W bt-btif : bta_dm_check_av:0
,03-30 14:14:53.234  2152  2214 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:53.252  2152  2226 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,03-30 14:14:53.333  2152  2226 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,03-30 14:14:53.333  2152  2226 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-30 14:14:53.954  3665  3742 I jxcore-log: # 41. Can shift large amounts of data
03-30 14:14:53.954  3665  3742 I jxcore-log: ,
,03-30 14:14:54.120  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 34653, start advertisements: true,
03-30 14:14:54.121  3665  3742 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2,
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 14:14:54.121  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:54.121  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:54.123  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:54.123  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:54.128  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-30 14:14:54.128  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:54.128  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:54.128  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:54.135  2152  2169 D BtGatt.GattService: registerClient() - UUID=e020222c-0700-49c5-8914-ee246f037d0d,
03-30 14:14:54.136  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=e020222c-0700-49c5-8914-ee246f037d0d, clientIf=5
03-30 14:14:54.136  3665  3683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 14:14:54.137  2152  2216 D BtGatt.GattService: start scan with filters
,03-30 14:14:54.139  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-30 14:14:54.140  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 14:14:54.140  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 14:14:54.140  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:54.140  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
03-30 14:14:54.140  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-30 14:14:54.141  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:14:54.141  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-30 14:14:54.141  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:14:54.141  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:14:54.142  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:54.142  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 14:14:54.142  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:54.143  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:14:54.143  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:54.145  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:14:54.145  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:54.145  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:54.146  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:14:54.148  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:14:54.148  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:14:54.149  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:14:54.150  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:54.150  2152  2170 D BtGatt.GattService: registerClient() - UUID=fbd9c7e0-1b9a-4f7d-b0ee-56c8f28cc218
03-30 14:14:54.150  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=fbd9c7e0-1b9a-4f7d-b0ee-56c8f28cc218, clientIf=6
03-30 14:14:54.151  3665  3682 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 14:14:54.153  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:54.156  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
03-30 14:14:54.159  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:14:54.162  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 14:14:54.163  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:14:54.163  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:54.163   821  1101 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:14:54.165  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-30 14:14:54.165  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:54.165  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:14:54.165  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:54.167  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-30 14:14:54.167  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:14:54.167  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:14:54.167  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-30 14:14:54.167  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:54.168  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:54.168  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:54.168  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:54.168  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:14:54.168  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING],
03-30 14:14:54.168  3665  3665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:54.168  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:54.168  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:54.168  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:54.168  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:14:54.168  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:54.168  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:54.170  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:54.170  3665  3742 I jxcore-log: 
03-30 14:14:54.170   821  3150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:14:54.172  3665  4110 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:54.173  3665  3742 I jxcore-log: ok 177 Can call startUpdateAdvertisingAndListening without error
03-30 14:14:54.173  3665  3742 I jxcore-log: 
,03-30 14:14:54.185  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 34653, start advertisements: false
,03-30 14:14:54.185  3665  4110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-30 14:14:54.185  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:54.186  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-30 14:14:54.186  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:54.186  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:54.188  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:54.188  3665  3742 I jxcore-log: 
,03-30 14:14:54.190  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:54.190  3665  3742 I jxcore-log: 
,03-30 14:14:54.193  3665  3742 I jxcore-log: ok 178 Can call startListeningForAdvertisements without error
03-30 14:14:54.193  3665  3742 I jxcore-log: 
,03-30 14:14:54.748  2152  2212 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-30 14:14:54.765  4070  4094 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-30 14:14:54.808  1252  1252 I ConfigService: onDestroy
,03-30 14:14:57.131  2152  2226 E bt-btm  : tBTM_SEC_DEV:0xa2fa507c rs_disc_pending=0
03-30 14:14:57.131  2152  2226 W bt-btif : bta_dm_check_av:0
03-30 14:14:57.132  2152  2214 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:58.501  2152  2226 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
,03-30 14:14:58.508  2152  2152 D BluetoothMapService: onReceive
,03-30 14:14:58.533   821   859 D BluetoothManagerService: Message: 20
,03-30 14:14:58.534   821   859 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22a2ba01:true
,03-30 14:14:58.550  1512  1512 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524],
,03-30 14:14:58.555  1512  1512 I BluetoothClassifier: Bluetooth Device Name: Note4-1
,03-30 14:14:58.564  2152  2226 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-30 14:14:58.567  2152  2152 D BluetoothMapService: onReceive
,03-30 14:14:58.602  1512  1512 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-30 14:14:58.606  1512  1512 I BluetoothClassifier: Bluetooth Device Name: G4-1,
,03-30 14:14:59.154  2152  2152 D BtGatt.ScanManager: awakened up at time 242721
,03-30 14:14:59.156  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:14:59.161  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-30 14:14:59.161  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:14:59.161  2152  2214 D BtGatt.GattService: current time is 242728887978
03-30 14:14:59.162  2152  2214 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -57, 53, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 22, 64, -99, -35, 23, 89, 1, -128, -81, 53, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-30 14:14:59.163  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 14:14:59.164  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:59.166  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-30 14:14:59.167  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-30 14:14:59.167  3665  3665 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-30 14:14:59.168  3665  3665 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-30 14:14:59.182  3665  3742 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-30 14:14:59.183  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-30 14:14:59.185  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
03-30 14:14:59.185  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-30 14:14:59.185  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-30 14:14:59.186  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
03-30 14:14:59.186  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-30 14:14:59.186  3665  3742 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-30 14:14:59.188  3665  4114 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 407)
03-30 14:14:59.188  3665  4114 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:59.201  2152  2169 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-30 14:14:59.844  3828  3844 D Finsky  : [390] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-30 14:14:59.865  1252  1252 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:14:59.962  1252  1270 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-30 14:14:59.963  1252  1270 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-30 14:14:59.963  1252  1270 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 14:14:59.963  1252  1270 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 14:14:59.976  1252  1270 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 14:15:00.076  1252  1270 I art     : Explicit concurrent mark sweep GC freed 60566(3MB) AllocSpace objects, 2(75KB) LOS objects, 36% free, 28MB/44MB, paused 2.105ms total 65.345ms
,03-30 14:15:00.094  3828  3844 D Finsky  : [390] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-30 14:15:00.384  2152  2226 W bt-btif : info:x10
03-30 14:15:00.384  2152  2214 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 2205
,03-30 14:15:00.417  1512  1512 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-30 14:15:00.424  1512  1512 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-30 14:15:00.485  2152  2226 W bt-sdp  : process_service_search_attr_rsp
,03-30 14:15:00.696  2152  2214 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-30 14:15:00.702  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-30 14:15:00.702  2152  2214 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-30 14:15:00.705  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-30 14:15:00.706  2152  2215 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-30 14:15:00.804  2152  2214 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-30 14:15:00.804  2152  2215 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-30 14:15:00.813  2152  2215 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-30 14:15:00.831  2152  2215 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-30 14:15:00.882  2152  2226 W bt-btif : new conn_srvc id:26, app_id:1
,03-30 14:15:00.882  2152  2226 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-30 14:15:00.883  2152  2226 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-30 14:15:00.883  3665  4114 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 407)
03-30 14:15:00.883  3665  4114 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 407)
,03-30 14:15:00.884  3665  4114 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 408)
03-30 14:15:00.884  3665  4114 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 408)
03-30 14:15:00.885  3665  4114 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 407)
,03-30 14:15:00.891  3665  4120 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 408)
,03-30 14:15:00.900  3665  4120 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 408)
,03-30 14:15:00.903  3665  4120 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-30 14:15:00.904  3665  4120 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 407)
03-30 14:15:00.904  3665  4120 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 407)
03-30 14:15:00.904  3665  4120 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 408)
,03-30 14:15:00.904  3665  3665 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-30 14:15:00.905  3665  3665 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-30 14:15:00.905  3665  3665 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-30 14:15:00.905  3665  3665 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-30 14:15:00.906  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-30 14:15:00.906  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:15:00.906  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:15:00.906  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 14:15:00.906  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:15:00.906  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:15:00.906  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:15:00.913  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-30 14:15:00.915  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 14:15:00.923  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-30 14:15:00.923  2152  2214 D BtGatt.GattService: Client app is not null!
,03-30 14:15:00.925  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-30 14:15:00.927  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-30 14:15:00.927  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
,03-30 14:15:00.927  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:15:00.927  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:15:00.928  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-30 14:15:00.929  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:15:00.929  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-30 14:15:00.930  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 14:15:00.930  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:15:00.938  2152  2216 D BtGatt.GattService: registerClient() - UUID=022fd9b4-ef23-4d78-ba12-e3711b9aa838
03-30 14:15:00.938  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=022fd9b4-ef23-4d78-ba12-e3711b9aa838, clientIf=6
03-30 14:15:00.939  3665  3682 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 14:15:00.940  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-30 14:15:00.945  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:15:00.947  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:15:00.950  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 14:15:00.951  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:15:00.952  2152  2169 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:15:00.954  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 14:15:00.954  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 14:15:00.954  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:00.954  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:15:00.955  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:15:00.955  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:00.955  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:00.955  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:15:00.955  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:15:00.955  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:15:00.957  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:15:00.957  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:00.957  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:15:00.959  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-30 14:15:00.959  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:00.961  2152  2169 D BtGatt.GattService: registerClient() - UUID=dbe16d58-0f1c-4dd7-913b-e3000a9a35b1
03-30 14:15:00.961  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=dbe16d58-0f1c-4dd7-913b-e3000a9a35b1, clientIf=5
03-30 14:15:00.961  3665  3682 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:15:00.962  2152  4119 D BtGatt.GattService: start scan with filters
,03-30 14:15:00.963  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 14:15:00.963  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 14:15:00.964  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-30 14:15:00.964  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:15:00.964  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:15:00.964  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 14:15:00.964  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 14:15:00.964  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:15:00.964  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:15:00.966  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-30 14:15:00.966  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 14:15:00.968  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 14:15:00.969  2152  2214 D BtGatt.GattService: Client app is not null!
03-30 14:15:00.969  2152  4119 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:15:00.970  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-30 14:15:00.970  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:15:00.970  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-30 14:15:00.970  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:15:00.970  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:15:00.971  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:15:00.971  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:15:00.971  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:00.971  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:00.971  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:15:00.974  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-30 14:15:00.974  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:00.975  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:15:00.975  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:00.976  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:15:00.976  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:15:00.977  2152  2216 D BtGatt.GattService: registerClient() - UUID=8bb62738-516c-4cdc-a914-e73638454004
03-30 14:15:00.977  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=8bb62738-516c-4cdc-a914-e73638454004, clientIf=6
,03-30 14:15:00.978  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:15:00.978  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:00.978  3665  3682 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 14:15:00.979  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:15:00.979  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:00.979  2152  2224 D BtGatt.AdvertiseManager: message : 0
03-30 14:15:00.982  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:15:00.984  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:15:00.987  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-30 14:15:00.987  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:15:00.988  2152  4119 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:15:00.989  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 14:15:00.989  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:15:00.989  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:00.989  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:00.989  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:15:00.989  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:15:00.990  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:15:00.990  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 14:15:00.990  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:00.991  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:15:00.993  2152  2216 D BtGatt.GattService: registerClient() - UUID=62443889-e2c3-497c-bb35-6e23c3e4891f
,03-30 14:15:00.993  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=62443889-e2c3-497c-bb35-6e23c3e4891f, clientIf=5
03-30 14:15:00.993  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:15:00.993  3665  3682 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:15:00.994  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:00.994  2152  2169 D BtGatt.GattService: start scan with filters
03-30 14:15:00.994  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:15:00.995  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:15:00.995  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:15:00.995  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:15:00.995  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:00.995  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-30 14:15:00.995  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:15:00.995  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:15:00.995  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 14:15:00.995  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 14:15:00.995  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:15:00.995  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:15:00.997  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-30 14:15:00.997  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 14:15:01.001  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-30 14:15:01.001  2152  2214 D BtGatt.GattService: Client app is not null!
03-30 14:15:01.002  2152  2216 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:15:01.003  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:15:01.003  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-30 14:15:01.003  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:15:01.003  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:15:01.003  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:15:01.003  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:15:01.003  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:01.003  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:01.003  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:15:01.009  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-30 14:15:01.012  2152  2169 D BtGatt.GattService: registerClient() - UUID=8d32bbcf-1d1a-43a6-a410-b2244dce15d7
,03-30 14:15:01.012  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=8d32bbcf-1d1a-43a6-a410-b2244dce15d7, clientIf=6
,03-30 14:15:01.012  3665  3682 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
,03-30 14:15:01.013  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-30 14:15:01.013  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-30 14:15:01.014  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:15:01.015  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:01.015  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:15:01.015  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:15:01.015  2152  2224 D BtGatt.AdvertiseManager: message : 0
03-30 14:15:01.017  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 14:15:01.017  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:01.018  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:15:01.018  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:01.024  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:15:01.026  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:15:01.028  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 14:15:01.029  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:15:01.030  2152  2170 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:15:01.031  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 14:15:01.032  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:15:01.032  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:01.032  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:01.032  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 14:15:01.032  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:15:01.032  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:01.032  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:15:01.032  3665  3665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:15:01.032  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:15:01.035  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-30 14:15:01.035  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:01.035  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:15:01.036  2152  2169 D BtGatt.GattService: registerClient() - UUID=9f6bcd4c-199c-4d4f-8977-986ada8ed3b9
03-30 14:15:01.036  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:15:01.036  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:01.037  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=9f6bcd4c-199c-4d4f-8977-986ada8ed3b9, clientIf=5
,03-30 14:15:01.041  3665  3682 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 14:15:01.041  2152  2216 D BtGatt.GattService: start scan with filters
,03-30 14:15:01.042  2152  2225 D BtGatt.ScanManager: handling starting scan
03-30 14:15:01.043  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:15:01.043  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 14:15:01.043  3665  3665 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-30 14:15:01.043  3665  3665 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-30 14:15:01.043  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:15:01.043  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:15:01.043  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-30 14:15:01.043  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:15:01.043  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:15:01.044  3665  4121 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 409)
03-30 14:15:01.045  3665  4121 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55915
03-30 14:15:01.045  3665  4121 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-30 14:15:01.045  3665  4121 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 55915 (peer ID: F8:95:C7:87:3C:51)
03-30 14:15:01.045  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-30 14:15:01.045  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:01.045  3665  4121 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-30 14:15:01.046  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:15:01.046  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:01.046  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan,
03-30 14:15:01.046  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:15:01.047  3665  3742 I jxcore-log: INFO testThaliMobileNative: 
03-30 14:15:01.047  3665  3742 I jxcore-log: 
,03-30 14:15:01.047  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 14:15:01.047  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:01.048  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:15:01.048  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:01.049  3665  3742 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-30 14:15:01.049  3665  3742 I jxcore-log: 
,03-30 14:15:01.053  3665  4121 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 55915
,03-30 14:15:01.053  3665  4121 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-30 14:15:01.053  3665  4121 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-30 14:15:01.054  3665  4121 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-30 14:15:01.054  3665  4122 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 410, name: Sender)
,03-30 14:15:01.055  3665  3742 I jxcore-log: INFO testThaliMobileNative: forwardSend,
03-30 14:15:01.055  3665  3742 I jxcore-log: 
03-30 14:15:01.055  3665  4121 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 409)
03-30 14:15:01.055  3665  4121 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 409)
,03-30 14:15:01.057  3665  4123 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 411, name: Receiver)
,03-30 14:15:01.252  3665  3742 I jxcore-log: INFO testThaliMobileNative: forwardData,
03-30 14:15:01.252  3665  3742 I jxcore-log: 
,03-30 14:15:01.258  3665  3742 I jxcore-log: INFO testThaliMobileNative: forwardData,
03-30 14:15:01.258  3665  3742 I jxcore-log: 
,03-30 14:15:01.320  3665  3742 I jxcore-log: INFO testThaliMobileNative: forwardData,
03-30 14:15:01.320  3665  3742 I jxcore-log: 
,03-30 14:15:01.394  3665  3742 I jxcore-log: INFO testThaliMobileNative: forwardData,
03-30 14:15:01.394  3665  3742 I jxcore-log: 
,03-30 14:15:01.461  3665  3742 I jxcore-log: INFO testThaliMobileNative: forwardData
03-30 14:15:01.461  3665  3742 I jxcore-log: 
,03-30 14:15:01.465  3665  3742 I jxcore-log: ok 179 received should match sent forward
03-30 14:15:01.465  3665  3742 I jxcore-log: 
,03-30 14:15:01.480  3665  3742 I jxcore-log: # teardown
03-30 14:15:01.480  3665  3742 I jxcore-log: 
,03-30 14:15:01.819  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:01.820  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 14:15:01.820  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 14:15:01.820  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:15:01.824  2152  2169 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:15:01.827  2152  4119 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-30 14:15:01.828  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:15:01.828  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 14:15:01.828  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:15:01.828  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:01.828  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:15:01.829  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:15:01.829  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-30 14:15:01.829  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:15:01.829  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:01.829  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-30 14:15:01.830  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 14:15:01.830  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-30 14:15:01.833  3665  3742 I jxcore-log: ok 180 Should be able to call stopListeningForAdvertisments in teardown
03-30 14:15:01.833  3665  3742 I jxcore-log: ,
,03-30 14:15:01.834  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-30 14:15:01.834  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-30 14:15:01.835  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-30 14:15:01.835  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:01.835  3665  3742 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-30 14:15:01.835  3665  3742 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 409)
,03-30 14:15:01.835  3665  3742 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 409)
03-30 14:15:01.835  3665  3742 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-30 14:15:01.835  3665  3742 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-30 14:15:01.835  3665  3742 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 411
,03-30 14:15:01.835  3665  3742 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-30 14:15:01.835  3665  3742 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 410
,03-30 14:15:01.835  3665  3742 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 409)
03-30 14:15:01.835  3665  3742 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 409)
03-30 14:15:01.836  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-30 14:15:01.836  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:15:01.836  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-30 14:15:01.836  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:15:01.836  3665  4123 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 411, thread name: Receiver): bt socket closed, read return: -1
,03-30 14:15:01.836  3665  4123 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 411, name: Receiver)
03-30 14:15:01.837  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:15:01.837  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-30 14:15:01.837  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:15:01.837  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 14:15:01.837  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:15:01.838  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 14:15:01.838  3665  4122 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 410, thread name: Sender): Socket closed
03-30 14:15:01.838  3665  4122 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 410, name: Sender)
,03-30 14:15:01.839  3665  3742 D BluetoothLeScanner: could not find callback wrapper
03-30 14:15:01.839  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:15:01.839  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 14:15:01.840  3665  4110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-30 14:15:01.840  3665  4110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:15:01.840  3665  4110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-30 14:15:01.844  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-30 14:15:01.844  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:01.844  2152  2214 D BtGatt.GattService: current time is 245411947560
03-30 14:15:01.845  2152  2214 D BtGatt.GattService: Batch record : [1, 26, -111, 112, 55, 105, 1, -128, -94, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -75, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-30 14:15:01.845  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:15:01.846  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 14:15:01.848  2152  2224 D BtGatt.AdvertiseManager: message : 1,
03-30 14:15:01.848  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 14:15:01.852  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-30 14:15:01.852  2152  2214 D BtGatt.GattService: Client app is not null!
03-30 14:15:01.853  2152  4119 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:15:01.853  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-30 14:15:01.853  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:01.853  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:15:01.854  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-30 14:15:01.854  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:15:01.854  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:01.854  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:15:01.854  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:15:01.855  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:15:01.855  3665  3742 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-30 14:15:01.855  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:01.855  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:15:01.856  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:01.856  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 14:15:01.857  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:15:01.857  3665  3742 I jxcore-log: 
03-30 14:15:01.863  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:15:01.863   821   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:15:01.869  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:15:01.871  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:01.871  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:15:01.880  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:15:01.880  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:15:01.880  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:01.880  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:15:01.880  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:01.880  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:01.881  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
,03-30 14:15:01.883  3665  3742 I jxcore-log: ok 181 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:15:01.883  3665  3742 I jxcore-log: 
,03-30 14:15:01.887  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-30 14:15:01.887  3665  3742 I jxcore-log: 
,03-30 14:15:01.888  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:01.888  3665  3742 I jxcore-log: 
,03-30 14:15:01.889  3665  3742 I jxcore-log: # setup
03-30 14:15:01.889  3665  3742 I jxcore-log: 
,03-30 14:15:01.897  2152  2226 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,03-30 14:15:04.705  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:04.705  3665  3742 I jxcore-log: 
,03-30 14:15:04.707  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-30 14:15:04.707  3665  3742 I jxcore-log: 
,03-30 14:15:04.716  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-30 14:15:04.716  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:04.716  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:04.716  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:04.716  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:04.716  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:04.716  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:04.716  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:04.721  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:04.724  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-30 14:15:04.724  3665  3742 I jxcore-log: 
,03-30 14:15:04.728  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-30 14:15:04.728  3665  3742 I jxcore-log: 
,03-30 14:15:04.734  3665  3742 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
,03-30 14:15:04.734  3665  3742 I jxcore-log: 
,03-30 14:15:04.736  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-30 14:15:04.736  3665  3742 I jxcore-log: 
,03-30 14:15:04.890  3665  3742 I jxcore-log: ok 182 specific error should be returned
03-30 14:15:04.890  3665  3742 I jxcore-log: 
,03-30 14:15:04.895  3665  3742 I jxcore-log: # teardown
03-30 14:15:04.895  3665  3742 I jxcore-log: 
,03-30 14:15:05.889  2152  2226 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-30 14:15:05.895  2152  2152 D BluetoothMapService: onReceive
,03-30 14:15:05.924  1512  1512 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-30 14:15:05.931  1512  1512 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-30 14:15:06.133  3665  3742 I jxcore-log: ok 183 must be stopped,
03-30 14:15:06.133  3665  3742 I jxcore-log: 
,03-30 14:15:06.141  3665  3742 I jxcore-log: # setup
03-30 14:15:06.141  3665  3742 I jxcore-log: 
,03-30 14:15:06.276  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:06.276  3665  3742 I jxcore-log: 
,03-30 14:15:06.281  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:06.281  3665  3742 I jxcore-log: 
,03-30 14:15:06.291  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-30 14:15:06.291  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:06.291  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:06.291  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:06.291  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:06.291  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:06.291  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:06.291  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:06.295  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:06.296  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:06.296  3665  3742 I jxcore-log: 
,03-30 14:15:06.298  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:06.298  3665  3742 I jxcore-log: 
,03-30 14:15:06.301  3665  3742 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called,
03-30 14:15:06.301  3665  3742 I jxcore-log: 
,03-30 14:15:06.303  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:06.303  3665  3742 I jxcore-log: 
,03-30 14:15:06.396  2152  2212 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-30 14:15:07.055  3665  3742 I jxcore-log: ok 184 specific error should be returned
03-30 14:15:07.055  3665  3742 I jxcore-log: ,
,03-30 14:15:07.057  3665  3742 I jxcore-log: # teardown
03-30 14:15:07.057  3665  3742 I jxcore-log: 
,03-30 14:15:08.184  3665  3742 I jxcore-log: ok 185 must be stopped
03-30 14:15:08.184  3665  3742 I jxcore-log: 
,03-30 14:15:08.186  3665  3742 I jxcore-log: # setup
03-30 14:15:08.186  3665  3742 I jxcore-log: 
,03-30 14:15:08.293  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:08.293  3665  3742 I jxcore-log: 
,03-30 14:15:08.298  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:08.298  3665  3742 I jxcore-log: 
,03-30 14:15:08.308  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:08.308  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:08.308  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:08.308  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:08.308  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:08.308  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:08.308  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:08.308  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:08.312  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:08.314  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:08.314  3665  3742 I jxcore-log: 
,03-30 14:15:08.315  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:08.315  3665  3742 I jxcore-log: 
,03-30 14:15:08.318  3665  3742 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-30 14:15:08.318  3665  3742 I jxcore-log: 
,03-30 14:15:08.319  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:08.319  3665  3742 I jxcore-log: 
,03-30 14:15:08.911  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:08.911  3665  3742 I jxcore-log: 
,03-30 14:15:08.914  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 33392
03-30 14:15:08.914  3665  3742 I jxcore-log: 
,03-30 14:15:08.916  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:08.916  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:08.916  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:08.920  3665  3742 I jxcore-log: ok 186 no errors
03-30 14:15:08.920  3665  3742 I jxcore-log: 
03-30 14:15:08.921  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:15:08.921  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 14:15:08.921  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:15:08.922  3665  3742 I jxcore-log: ok 187 still no errors
03-30 14:15:08.922  3665  3742 I jxcore-log: 
,03-30 14:15:08.928  3665  3742 I jxcore-log: # teardown
03-30 14:15:08.928  3665  3742 I jxcore-log: 
,03-30 14:15:09.067  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:09.068  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:15:09.068  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:15:09.071  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:15:09.071  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 14:15:09.072  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:09.084  3665  3742 I jxcore-log: ok 188 must be stopped
03-30 14:15:09.084  3665  3742 I jxcore-log: 
,03-30 14:15:09.090  3665  3742 I jxcore-log: # setup
03-30 14:15:09.090  3665  3742 I jxcore-log: 
,03-30 14:15:09.615  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:09.615  3665  3742 I jxcore-log: 
,03-30 14:15:09.621  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:09.621  3665  3742 I jxcore-log: 
,03-30 14:15:09.632  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-30 14:15:09.632  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:09.632  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:09.632  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:09.632  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:09.632  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:09.632  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:09.632  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:09.636  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:09.638  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:09.638  3665  3742 I jxcore-log: 
,03-30 14:15:09.640  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:09.640  3665  3742 I jxcore-log: 
,03-30 14:15:09.644  3665  3742 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-30 14:15:09.644  3665  3742 I jxcore-log: 
,03-30 14:15:09.645  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:09.645  3665  3742 I jxcore-log: 
,03-30 14:15:09.775  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:09.775  3665  3742 I jxcore-log: 
,03-30 14:15:09.777  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 38404
03-30 14:15:09.777  3665  3742 I jxcore-log: 
,03-30 14:15:09.784  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 34653, start advertisements: false
03-30 14:15:09.784  3665  3742 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-30 14:15:09.784  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-30 14:15:09.786  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-30 14:15:09.786  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:15:09.786  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 14:15:09.786  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 14:15:09.786  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:15:09.786  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 14:15:09.786  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:15:09.786  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500,
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:09.787  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:15:09.787  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:15:09.787  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-30 14:15:09.793  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
,03-30 14:15:09.794  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:15:09.794  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:15:09.802  2152  4119 D BtGatt.GattService: registerClient() - UUID=5c1f0b3f-25fd-47d3-beed-c1b325a0298d
03-30 14:15:09.802  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=5c1f0b3f-25fd-47d3-beed-c1b325a0298d, clientIf=5
03-30 14:15:09.803  3665  3683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:15:09.805  2152  2216 D BtGatt.GattService: start scan with filters
03-30 14:15:09.806  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:15:09.806  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 14:15:09.806  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-30 14:15:09.807  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:15:09.807  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:15:09.807  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:09.812  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:15:09.812  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:15:09.813   821  1322 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:15:09.815  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:15:09.816  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:09.817  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:15:09.817  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:09.817  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:15:09.817  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:15:09.819  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:15:09.819  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:09.821  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:15:09.821  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:09.824  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:15:09.824  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:15:09.824  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:15:09.824  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:15:09.824  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:15:09.825  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:15:09.827  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:09.827  3665  3742 I jxcore-log: 
03-30 14:15:09.827  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:09.827  3665  3742 I jxcore-log: 
03-30 14:15:09.828  3665  3742 I jxcore-log: ok 189 no errors
03-30 14:15:09.828  3665  3742 I jxcore-log: 
,03-30 14:15:09.832  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 34653, start advertisements: false
03-30 14:15:09.832  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:15:09.832  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:15:09.832  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:15:09.832  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:15:09.835  3665  3742 I jxcore-log: ok 190 still no errors
,03-30 14:15:09.835  3665  3742 I jxcore-log: 
,03-30 14:15:09.841  3665  3742 I jxcore-log: # teardown
,03-30 14:15:09.841  3665  3742 I jxcore-log: 
,03-30 14:15:10.430  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:10.430  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:10.431  3665  3742 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-30 14:15:10.431  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:15:10.431  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:15:10.431  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:15:10.431  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:15:10.431  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:15:10.431  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:15:10.436  2152  2169 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:15:10.439  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 14:15:10.439  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:10.440  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:15:10.441  2152  4119 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 14:15:10.443  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:15:10.443  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:10.443  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:15:10.443  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 14:15:10.444  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 14:15:10.444  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:10.445  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:15:10.445  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:10.446  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:15:10.447  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:15:10.447  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-30 14:15:10.447  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:15:10.447  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:15:10.447  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:10.449  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:15:10.449  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:15:10.450  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:15:10.450  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:10.450  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:15:10.459  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:15:10.460   821  3580 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:15:10.469  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:15:10.470  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:10.470  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:15:10.474  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:15:10.475  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:15:10.475  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:10.475  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:15:10.477  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:15:10.478  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:10.478  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:10.480  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:10.480  3665  3742 I jxcore-log: 
,03-30 14:15:10.482  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:10.482  3665  3742 I jxcore-log: 
,03-30 14:15:10.491  3665  3742 I jxcore-log: ok 191 must be stopped
03-30 14:15:10.491  3665  3742 I jxcore-log: 
,03-30 14:15:10.504  3665  3742 I jxcore-log: # setup
03-30 14:15:10.504  3665  3742 I jxcore-log: 
,03-30 14:15:10.603  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:10.603  3665  3742 I jxcore-log: 
,03-30 14:15:10.608  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:10.608  3665  3742 I jxcore-log: 
,03-30 14:15:10.620  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:10.620  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:10.620  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:10.620  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:10.620  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:10.620  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:10.620  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:10.620  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:10.624  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:10.625  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:10.625  3665  3742 I jxcore-log: 
,03-30 14:15:10.627  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:10.627  3665  3742 I jxcore-log: 
,03-30 14:15:10.630  3665  3742 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-30 14:15:10.630  3665  3742 I jxcore-log: 
,03-30 14:15:10.631  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:10.631  3665  3742 I jxcore-log: 
,03-30 14:15:10.763  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:10.763  3665  3742 I jxcore-log: 
,03-30 14:15:10.765  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 52105
03-30 14:15:10.765  3665  3742 I jxcore-log: 
,03-30 14:15:10.771  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 52105, start advertisements: true
,03-30 14:15:10.771  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:15:10.771  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:15:10.772  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:15:10.778  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-30 14:15:10.778  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:15:10.778  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:15:10.778  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:15:10.786  2152  2170 D BtGatt.GattService: registerClient() - UUID=6d91a798-4361-48c9-a423-3ba0c1ebb8d2
,03-30 14:15:10.786  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=6d91a798-4361-48c9-a423-3ba0c1ebb8d2, clientIf=5
03-30 14:15:10.786  3665  3683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:15:10.787  2152  2216 D BtGatt.GattService: start scan with filters
03-30 14:15:10.788  2152  2225 D BtGatt.ScanManager: handling starting scan
,03-30 14:15:10.790  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:15:10.790  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 14:15:10.790  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:15:10.790  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:15:10.791  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:10.792  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:15:10.792  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:10.792  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:10.792  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:15:10.792  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:15:10.794  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:15:10.794  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:10.794  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:15:10.794  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:15:10.794  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:15:10.796  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:10.796  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 14:15:10.796  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:15:10.798  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:15:10.798  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:10.799  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:15:10.799  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:10.803  2152  2216 D BtGatt.GattService: registerClient() - UUID=4d3cdb3c-0ee0-4b5a-9b31-b67ba326b7e9
03-30 14:15:10.803  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=4d3cdb3c-0ee0-4b5a-9b31-b67ba326b7e9, clientIf=6
,03-30 14:15:10.804  3665  3682 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 14:15:10.805  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-30 14:15:10.809  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:15:10.812  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:15:10.815  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 14:15:10.816  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:15:10.816  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:15:10.817   821  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:15:10.820  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:15:10.820  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:15:10.820  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:15:10.820  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:15:10.821  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 14:15:10.821  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:15:10.821  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-30 14:15:10.821  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:15:10.822  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:15:10.822  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-30 14:15:10.822  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:15:10.822  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:15:10.822  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-30 14:15:10.822  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:15:10.822  3665  3665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:15:10.822  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:15:10.822  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:15:10.822  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:10.823  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:15:10.823  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:15:10.823  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:15:10.825  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:10.825  3665  3742 I jxcore-log: 
03-30 14:15:10.827  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:10.827  3665  3742 I jxcore-log: 
,03-30 14:15:10.827  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:15:10.827  3665  3742 I jxcore-log: 
03-30 14:15:10.829  3665  3742 I jxcore-log: ok 192 no errors
03-30 14:15:10.829  3665  3742 I jxcore-log: 
03-30 14:15:10.831   821  3150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:15:10.834  3665  4126 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:15:10.837  3665  4126 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:15:10.837  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 52105, start advertisements: true
,03-30 14:15:10.837  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:15:10.838  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:15:10.838  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:15:10.838  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:15:10.844  3665  3742 I jxcore-log: ok 193 still no errors
03-30 14:15:10.844  3665  3742 I jxcore-log: 
,03-30 14:15:10.856  3665  3742 I jxcore-log: # teardown
03-30 14:15:10.856  3665  3742 I jxcore-log: 
,03-30 14:15:11.483  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
,03-30 14:15:11.483  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 14:15:11.483  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections,
03-30 14:15:11.483  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:15:11.484  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:15:11.484  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:15:11.484  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:15:11.484  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-30 14:15:11.484  3665  4126 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:15:11.484  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:15:11.484  3665  4126 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-30 14:15:11.485  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:15:11.485  3665  4126 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:15:11.485  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 14:15:11.485  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:15:11.494  2152  4119 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:15:11.496  2152  2170 D BtGatt.GattService: unregisterClient() - clientIf=5,
,03-30 14:15:11.497  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-30 14:15:11.497  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-30 14:15:11.497  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-30 14:15:11.498  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:11.498  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:15:11.498  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:15:11.498  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:15:11.498  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-30 14:15:11.498  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:11.498  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-30 14:15:11.501  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:15:11.501  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:11.502  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:15:11.502  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-30 14:15:11.503  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 14:15:11.505  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-30 14:15:11.505  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:11.505  2152  2214 D BtGatt.GattService: current time is 255072434640
03-30 14:15:11.505  2152  2214 D BtGatt.GattService: Batch record : [57, 110, -41, 40, 16, 119, 1, -128, -82, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0],
,03-30 14:15:11.506  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:15:11.506  2152  2214 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 14:15:11.509  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-30 14:15:11.509  2152  2214 D BtGatt.GattService: Client app is not null!
,03-30 14:15:11.511  2152  4119 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 14:15:11.512  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:15:11.512  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:11.512  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:15:11.512  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:15:11.512  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:15:11.512  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:11.512  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:15:11.512  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:15:11.514  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-30 14:15:11.514  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:15:11.514  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:15:11.514  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:11.514  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:15:11.524  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:15:11.525   821  1150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:15:11.530  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:15:11.531  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 14:15:11.531  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:15:11.532  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-30 14:15:11.532  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:15:11.535  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-30 14:15:11.535  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:15:11.535  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:11.536  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:15:11.536  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:11.536  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 14:15:11.537  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:15:11.537  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 14:15:11.537  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:11.538  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-30 14:15:11.538  3665  3742 I jxcore-log: 
03-30 14:15:11.539  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:11.539  3665  3742 I jxcore-log: ,
03-30 14:15:11.539  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:11.539  3665  3742 I jxcore-log: 
,03-30 14:15:11.543  3665  3742 I jxcore-log: ok 194 must be stopped,
03-30 14:15:11.543  3665  3742 I jxcore-log: 
03-30 14:15:11.549  3665  3742 I jxcore-log: # setup,
03-30 14:15:11.549  3665  3742 I jxcore-log: 
,03-30 14:15:12.174  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-30 14:15:12.174  3665  3742 I jxcore-log: 
,03-30 14:15:12.175  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:12.175  3665  3742 I jxcore-log: 
,03-30 14:15:12.183  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:12.183  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:12.183  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:12.183  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:12.183  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:12.183  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:12.183  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:12.183  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:12.187  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:12.188  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:12.188  3665  3742 I jxcore-log: 
,03-30 14:15:12.190  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:12.190  3665  3742 I jxcore-log: 
,03-30 14:15:12.193  3665  3742 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-30 14:15:12.193  3665  3742 I jxcore-log: 
,03-30 14:15:12.199  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:12.199  3665  3742 I jxcore-log: 
,03-30 14:15:12.344  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:12.344  3665  3742 I jxcore-log: 
,03-30 14:15:12.346  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 39624
03-30 14:15:12.346  3665  3742 I jxcore-log: 
,03-30 14:15:12.348  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:12.348  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:12.348  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:12.351  3665  3742 I jxcore-log: ok 195 no errors
03-30 14:15:12.351  3665  3742 I jxcore-log: 
,03-30 14:15:12.352  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:15:12.352  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:12.352  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:12.353  3665  3742 I jxcore-log: ok 196 still no errors
03-30 14:15:12.353  3665  3742 I jxcore-log: 
,03-30 14:15:12.359  3665  3742 I jxcore-log: # teardown
03-30 14:15:12.359  3665  3742 I jxcore-log: 
,03-30 14:15:12.890  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:15:12.890  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:15:12.890  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:12.894  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:12.894  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:12.894  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:12.898  3665  3742 I jxcore-log: ok 197 must be stopped
03-30 14:15:12.898  3665  3742 I jxcore-log: 
,03-30 14:15:12.903  3665  3742 I jxcore-log: # setup
03-30 14:15:12.903  3665  3742 I jxcore-log: 
,03-30 14:15:13.001  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:13.001  3665  3742 I jxcore-log: 
,03-30 14:15:13.006  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:13.006  3665  3742 I jxcore-log: 
,03-30 14:15:13.020  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:13.020  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:13.020  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
03-30 14:15:13.020  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:13.020  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:13.020  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:13.020  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:13.020  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:13.027  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:13.032  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:13.032  3665  3742 I jxcore-log: 
,03-30 14:15:13.038  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:13.038  3665  3742 I jxcore-log: 
,03-30 14:15:13.048  3665  3742 I jxcore-log: # 48. can get the network status before starting
03-30 14:15:13.048  3665  3742 I jxcore-log: 
,03-30 14:15:13.054  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:13.054  3665  3742 I jxcore-log: 
,03-30 14:15:13.214  3665  3742 I jxcore-log: ok 198 network status should have certain non-empty properties
03-30 14:15:13.214  3665  3742 I jxcore-log: 
,03-30 14:15:13.217  3665  3742 I jxcore-log: # teardown
03-30 14:15:13.217  3665  3742 I jxcore-log: 
,03-30 14:15:13.318  3665  3742 I jxcore-log: ok 199 must be stopped
03-30 14:15:13.318  3665  3742 I jxcore-log: 
,03-30 14:15:13.326  3665  3742 I jxcore-log: # setup
03-30 14:15:13.326  3665  3742 I jxcore-log: 
,03-30 14:15:13.477  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:13.477  3665  3742 I jxcore-log: 
,03-30 14:15:13.481  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:13.481  3665  3742 I jxcore-log: 
,03-30 14:15:13.495  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:13.495  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:13.495  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:13.495  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
03-30 14:15:13.495  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:13.495  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:13.495  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:13.495  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:13.502  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:13.506  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:13.506  3665  3742 I jxcore-log: 
,03-30 14:15:13.510  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:13.510  3665  3742 I jxcore-log: 
,03-30 14:15:13.519  3665  3742 I jxcore-log: # 49. error returned with bad router
03-30 14:15:13.519  3665  3742 I jxcore-log: 
,03-30 14:15:13.524  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:13.524  3665  3742 I jxcore-log: 
,03-30 14:15:13.627  3665  3742 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string,
03-30 14:15:13.627  3665  3742 I jxcore-log: 
03-30 14:15:13.629  3665  3742 I jxcore-log: ok 200 specific error expected
03-30 14:15:13.629  3665  3742 I jxcore-log: 
,03-30 14:15:13.632  3665  3742 I jxcore-log: # teardown,
03-30 14:15:13.632  3665  3742 I jxcore-log: 
,03-30 14:15:13.760  3665  3742 I jxcore-log: ok 201 must be stopped
03-30 14:15:13.760  3665  3742 I jxcore-log: 
,03-30 14:15:13.767  3665  3742 I jxcore-log: # setup
,03-30 14:15:13.767  3665  3742 I jxcore-log: 
,03-30 14:15:13.921  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:13.921  3665  3742 I jxcore-log: 
,03-30 14:15:13.924  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:13.924  3665  3742 I jxcore-log: 
,03-30 14:15:13.931  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-30 14:15:13.931  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:13.931  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:13.931  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:13.931  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:13.931  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:13.931  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:13.931  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:13.935  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:13.937  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:13.937  3665  3742 I jxcore-log: ,
,03-30 14:15:13.939  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:13.939  3665  3742 I jxcore-log: ,
03-30 14:15:13.942  3665  3742 I jxcore-log: # 50. all services are stopped when we call stop
03-30 14:15:13.942  3665  3742 I jxcore-log: 
,03-30 14:15:13.943  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:13.943  3665  3742 I jxcore-log: 
,03-30 14:15:14.132  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:14.132  3665  3742 I jxcore-log: 
,03-30 14:15:14.135  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 52960
03-30 14:15:14.135  3665  3742 I jxcore-log: 
,03-30 14:15:14.141  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 52105, start advertisements: false
,03-30 14:15:14.141  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:15:14.141  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:15:14.141  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:15:14.146  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:15:14.147  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:15:14.147  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:15:14.152  2152  2170 D BtGatt.GattService: registerClient() - UUID=56e429b5-8097-4b56-a75d-fee932e32bcd
,03-30 14:15:14.153  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=56e429b5-8097-4b56-a75d-fee932e32bcd, clientIf=5
,03-30 14:15:14.154  3665  3683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:15:14.155  2152  4119 D BtGatt.GattService: start scan with filters
03-30 14:15:14.157  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 14:15:14.157  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:15:14.157  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:15:14.157  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:15:14.157  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:14.157  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:15:14.157  2152  2225 D BtGatt.ScanManager: handling starting scan
03-30 14:15:14.157  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:14.158   821   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:15:14.167  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:15:14.167  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:14.169  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:15:14.169  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:14.169  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:15:14.170  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 14:15:14.172  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:15:14.172  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:15:14.172  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:15:14.172  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:15:14.172  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:14.173  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:15:14.174  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:15:14.174  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:14.177  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:15:14.177  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:14.179  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:14.179  3665  3742 I jxcore-log: 
,03-30 14:15:14.181  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:14.181  3665  3742 I jxcore-log: 
,03-30 14:15:14.191  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 52960, start advertisements: true
03-30 14:15:14.191  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:15:14.191  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:15:14.191  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:15:14.198  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-30 14:15:14.198  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-30 14:15:14.198  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-30 14:15:14.198  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:15:14.199  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:15:14.199  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:14.199  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:14.199  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:15:14.207  2152  4119 D BtGatt.GattService: registerClient() - UUID=70a587d5-09cd-4e75-87b9-32b8cdb00178
03-30 14:15:14.208  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=70a587d5-09cd-4e75-87b9-32b8cdb00178, clientIf=6
,03-30 14:15:14.209  3665  3682 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 14:15:14.211  2152  2224 D BtGatt.AdvertiseManager: message : 0
,03-30 14:15:14.217  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:15:14.222  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:15:14.227  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 14:15:14.228  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:15:14.228  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:15:14.228  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:15:14.229  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:15:14.229  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:15:14.229   821  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:15:14.229  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-30 14:15:14.229  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-30 14:15:14.235  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:15:14.235  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 14:15:14.235  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:15:14.235  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:14.235  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:15:14.237  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 14:15:14.237  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:15:14.238  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:15:14.238  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:15:14.238  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:15:14.239  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:15:14.239  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:14.239   821  1321 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:15:14.240  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:15:14.242  3665  4127 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:15:14.245  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:15:14.245  3665  3742 I jxcore-log: 
,03-30 14:15:14.247  3665  4127 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:15:14.260  3665  3742 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:15:14.260  3665  3742 I jxcore-log: 
,03-30 14:15:14.266  3665  3742 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:15:14.266  3665  3742 I jxcore-log: 
,03-30 14:15:14.270  3665  3742 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:15:14.270  3665  3742 I jxcore-log: 
,03-30 14:15:14.276  3665  3742 I jxcore-log: ok 202 connection to servers manager should succeed after starting
03-30 14:15:14.276  3665  3742 I jxcore-log: 
,03-30 14:15:14.313  3665  3742 I jxcore-log: ok 203 connection to router server should succeed after starting
,03-30 14:15:14.313  3665  3742 I jxcore-log: 
03-30 14:15:14.315  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-30 14:15:14.315  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 14:15:14.315  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-30 14:15:14.315  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:15:14.315  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:15:14.315  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:15:14.315  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 14:15:14.315  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:15:14.315  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:15:14.316  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:15:14.316  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:15:14.316  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:15:14.319  3665  4127 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:15:14.319  3665  4127 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:15:14.319  3665  4127 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:15:14.321  2152  2170 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:15:14.323  2152  4119 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 14:15:14.324  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:15:14.324  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:14.324  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:15:14.324  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:15:14.324  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:15:14.324  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:14.324  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 14:15:14.324  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 14:15:14.324  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:14.324  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:15:14.327  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:15:14.327  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:14.327  2152  2224 D BtGatt.AdvertiseManager: message : 1
03-30 14:15:14.328  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 14:15:14.329  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 14:15:14.329  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:15:14.329  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:14.332  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 14:15:14.332  2152  2214 D BtGatt.GattService: Client app is not null!
,03-30 14:15:14.335  2152  2170 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 14:15:14.337  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:15:14.337  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:15:14.337  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-30 14:15:14.337  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
,03-30 14:15:14.337  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
,03-30 14:15:14.337  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:15:14.337  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-30 14:15:14.337  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:15:14.338  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:15:14.338  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:14.338  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:15:14.338  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:14.338  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 14:15:14.343  3665  3742 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:15:14.343  3665  3742 I jxcore-log: 
03-30 14:15:14.346  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 14:15:14.346   821   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:15:14.355  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 14:15:14.356  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:14.356  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:15:14.361  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:15:14.361  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:15:14.361  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:14.361  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:15:14.361  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:14.362  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:14.362  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:15:14.362  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-30 14:15:14.362  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:15:14.363  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 14:15:14.363  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:15:14.364  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:15:14.364  3665  3742 I jxcore-log: 
03-30 14:15:14.365  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:14.365  3665  3742 I jxcore-log: ,
03-30 14:15:14.366  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:14.366  3665  3742 I jxcore-log: 
,03-30 14:15:14.371  3665  3742 I jxcore-log: ok 204 is stopped after calling stop
,03-30 14:15:14.371  3665  3742 I jxcore-log: 
,03-30 14:15:14.376  3665  3742 I jxcore-log: ok 205 connection to servers manager should fail after stopping
,03-30 14:15:14.376  3665  3742 I jxcore-log: 
,03-30 14:15:14.380  3665  3742 I jxcore-log: ok 206 connection to router server should fail after stopping
,03-30 14:15:14.380  3665  3742 I jxcore-log: 
,03-30 14:15:14.385  3665  3742 I jxcore-log: # teardown
,03-30 14:15:14.385  3665  3742 I jxcore-log: 
,03-30 14:15:14.623  3665  3742 I jxcore-log: ok 207 must be stopped
03-30 14:15:14.623  3665  3742 I jxcore-log: 
,03-30 14:15:14.631  3665  3742 I jxcore-log: # setup
03-30 14:15:14.631  3665  3742 I jxcore-log: 
,03-30 14:15:15.167  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:15.167  3665  3742 I jxcore-log: 
,03-30 14:15:15.176  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:15.176  3665  3742 I jxcore-log: 
,03-30 14:15:15.187  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:15.187  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:15.187  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:15.187  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:15.187  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:15.187  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:15.187  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:15.187  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:15.190  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:15.193  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:15.193  3665  3742 I jxcore-log: 
,03-30 14:15:15.196  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:15.196  3665  3742 I jxcore-log: 
,03-30 14:15:15.201  3665  3742 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-30 14:15:15.201  3665  3742 I jxcore-log: 
,03-30 14:15:15.205  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:15.205  3665  3742 I jxcore-log: 
,03-30 14:15:15.369  3665  3742 I jxcore-log: ok 208 called with right arguments
03-30 14:15:15.369  3665  3742 I jxcore-log: 
,03-30 14:15:15.371  3665  3742 I jxcore-log: # teardown
03-30 14:15:15.371  3665  3742 I jxcore-log: 
,03-30 14:15:15.494  3665  3742 I jxcore-log: ok 209 must be stopped
03-30 14:15:15.494  3665  3742 I jxcore-log: 
03-30 14:15:15.496  3665  3742 I jxcore-log: # setup
03-30 14:15:15.496  3665  3742 I jxcore-log: 
,03-30 14:15:15.644  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:15.644  3665  3742 I jxcore-log: 
03-30 14:15:15.648  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:15.648  3665  3742 I jxcore-log: 
,03-30 14:15:15.662  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-30 14:15:15.662  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:15.662  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:15.662  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:15.662  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:15.662  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:15.662  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:15.662  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:15.667  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:15.668  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:15.668  3665  3742 I jxcore-log: 
,03-30 14:15:15.670  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:15.670  3665  3742 I jxcore-log: 
,03-30 14:15:15.673  3665  3742 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-30 14:15:15.673  3665  3742 I jxcore-log: 
,03-30 14:15:15.675  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:15.675  3665  3742 I jxcore-log: 
,03-30 14:15:15.855  3665  3742 I jxcore-log: ok 210 called with right arguments
03-30 14:15:15.855  3665  3742 I jxcore-log: 
,03-30 14:15:15.858  3665  3742 I jxcore-log: # teardown
03-30 14:15:15.858  3665  3742 I jxcore-log: 
,03-30 14:15:15.964  3665  3742 I jxcore-log: ok 211 must be stopped
03-30 14:15:15.964  3665  3742 I jxcore-log: 
,03-30 14:15:15.972  3665  3742 I jxcore-log: # setup
03-30 14:15:15.972  3665  3742 I jxcore-log: 
,03-30 14:15:16.109  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:16.109  3665  3742 I jxcore-log: 
,03-30 14:15:16.114  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:16.114  3665  3742 I jxcore-log: 
,03-30 14:15:16.122  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:16.122  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:16.122  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:16.122  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:16.122  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:16.122  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:16.122  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:16.122  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:16.126  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:16.128  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:16.128  3665  3742 I jxcore-log: 
,03-30 14:15:16.129  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:16.129  3665  3742 I jxcore-log: 
,03-30 14:15:16.132  3665  3742 I jxcore-log: # 53. make sure we actually call kill connections properly
03-30 14:15:16.132  3665  3742 I jxcore-log: 
,03-30 14:15:16.134  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:16.134  3665  3742 I jxcore-log: 
,03-30 14:15:16.276  3665  3742 I jxcore-log: ok 212 specific error expected
03-30 14:15:16.276  3665  3742 I jxcore-log: 
,03-30 14:15:16.278  3665  3742 I jxcore-log: # teardown
03-30 14:15:16.278  3665  3742 I jxcore-log: 
,03-30 14:15:16.452  3665  3742 I jxcore-log: ok 213 must be stopped
03-30 14:15:16.452  3665  3742 I jxcore-log: 
,03-30 14:15:16.456  3665  3742 I jxcore-log: # setup
03-30 14:15:16.456  3665  3742 I jxcore-log: 
,03-30 14:15:16.575  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:16.575  3665  3742 I jxcore-log: 
,03-30 14:15:16.576  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:16.576  3665  3742 I jxcore-log: 
,03-30 14:15:16.585  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-30 14:15:16.585  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:16.585  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:16.585  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:16.585  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:16.585  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:16.585  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:16.585  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:16.589  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-30 14:15:16.595  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-30 14:15:16.595  3665  3742 I jxcore-log: 
,03-30 14:15:16.601  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-30 14:15:16.601  3665  3742 I jxcore-log: 
,03-30 14:15:16.610  3665  3742 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received,
03-30 14:15:16.610  3665  3742 I jxcore-log: 
,03-30 14:15:16.616  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-30 14:15:16.616  3665  3742 I jxcore-log: 
,03-30 14:15:16.714  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server,
03-30 14:15:16.714  3665  3742 I jxcore-log: 
03-30 14:15:16.716  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 43312,
03-30 14:15:16.716  3665  3742 I jxcore-log: 
,03-30 14:15:16.724  3665  3742 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":33191,"error":{}}
03-30 14:15:16.724  3665  3742 I jxcore-log: 
,03-30 14:15:16.725  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:15:16.725  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:16.725  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:16.727  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:15:16.728  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:16.728  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:16.740  3665  3742 I jxcore-log: ok 214 failure reason is as expected
,03-30 14:15:16.740  3665  3742 I jxcore-log: 
03-30 14:15:16.741  3665  3742 I jxcore-log: ok 215 error description is as expected
03-30 14:15:16.741  3665  3742 I jxcore-log: 
03-30 14:15:16.741  3665  3742 I jxcore-log: ok 216 must be stopped
03-30 14:15:16.741  3665  3742 I jxcore-log: ,
,03-30 14:15:16.749  3665  3742 I jxcore-log: # teardown
,03-30 14:15:16.749  3665  3742 I jxcore-log: 
,03-30 14:15:16.895  3665  3742 I jxcore-log: ok 217 must be stopped
03-30 14:15:16.895  3665  3742 I jxcore-log: 
03-30 14:15:16.900  3665  3742 I jxcore-log: # setup
03-30 14:15:16.900  3665  3742 I jxcore-log: 
,03-30 14:15:17.038  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:17.038  3665  3742 I jxcore-log: 
,03-30 14:15:17.044  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:17.044  3665  3742 I jxcore-log: 
,03-30 14:15:17.051  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:17.051  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:17.051  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:17.051  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:17.051  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:17.051  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:17.051  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:17.051  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:17.055  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:17.057  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:17.057  3665  3742 I jxcore-log: 
03-30 14:15:17.058  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:17.058  3665  3742 I jxcore-log: 
,03-30 14:15:17.061  3665  3742 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-30 14:15:17.061  3665  3742 I jxcore-log: 
,03-30 14:15:17.063  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:17.063  3665  3742 I jxcore-log: 
,03-30 14:15:17.250  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:17.250  3665  3742 I jxcore-log: 
,03-30 14:15:17.252  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 60133
03-30 14:15:17.252  3665  3742 I jxcore-log: 
,03-30 14:15:17.256  3665  3742 I jxcore-log: ok 218 peerIdentifier matches
03-30 14:15:17.256  3665  3742 I jxcore-log: 
,03-30 14:15:17.256  3665  3742 I jxcore-log: ok 219 error description matches
03-30 14:15:17.256  3665  3742 I jxcore-log: 
,03-30 14:15:17.260  3665  3742 I jxcore-log: # teardown
03-30 14:15:17.260  3665  3742 I jxcore-log: 
,03-30 14:15:17.404  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:17.404  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:17.404  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:17.405  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:17.405  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:17.405  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:15:17.409  3665  3742 I jxcore-log: ok 220 must be stopped
03-30 14:15:17.409  3665  3742 I jxcore-log: 
,03-30 14:15:17.417  3665  3742 I jxcore-log: # setup
03-30 14:15:17.417  3665  3742 I jxcore-log: 
,03-30 14:15:17.555  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:17.555  3665  3742 I jxcore-log: 
,03-30 14:15:17.559  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:17.559  3665  3742 I jxcore-log: 
,03-30 14:15:17.573  3665  3742 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:17.573  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:17.573  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,03-30 14:15:17.573  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:17.573  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:17.573  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:17.573  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:17.573  3665  3742 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-30 14:15:17.578  3665  3742 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:17.581  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:17.581  3665  3742 I jxcore-log: 
,03-30 14:15:17.585  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:17.585  3665  3742 I jxcore-log: 
,03-30 14:15:17.606  3665  3742 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate,
03-30 14:15:17.606  3665  3742 I jxcore-log: 
03-30 14:15:17.608  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-30 14:15:17.608  3665  3742 I jxcore-log: 
,03-30 14:15:17.731  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:17.731  3665  3742 I jxcore-log: 
,03-30 14:15:17.733  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 56194
03-30 14:15:17.733  3665  3742 I jxcore-log: 
,03-30 14:15:17.739  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 52960, start advertisements: false
,03-30 14:15:17.739  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:15:17.740  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:15:17.740  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:15:17.744  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:15:17.744  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
03-30 14:15:17.744  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:15:17.748  2152  2170 D BtGatt.GattService: registerClient() - UUID=a43039e2-c51f-4fab-91a3-53fe34102a6b
,03-30 14:15:17.749  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=a43039e2-c51f-4fab-91a3-53fe34102a6b, clientIf=5
03-30 14:15:17.750  3665  3682 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 14:15:17.750  2152  2169 D BtGatt.GattService: start scan with filters
03-30 14:15:17.751  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:15:17.751  2152  2225 D BtGatt.ScanManager: handling starting scan
03-30 14:15:17.751  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 14:15:17.751  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:15:17.751  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:15:17.751  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:17.751  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:15:17.752  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-30 14:15:17.752   821  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:15:17.754  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:15:17.754  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:15:17.754  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:15:17.754  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:15:17.755  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:15:17.755  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:15:17.757  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-30 14:15:17.757  3665  3742 I jxcore-log: 
,03-30 14:15:17.768  3665  3742 I jxcore-log: ok 221 discoveryActive matches
03-30 14:15:17.768  3665  3742 I jxcore-log: 
,03-30 14:15:17.769  3665  3742 I jxcore-log: ok 222 advertisingActive matches
03-30 14:15:17.769  3665  3742 I jxcore-log: 
03-30 14:15:17.773  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:17.773  3665  3742 I jxcore-log: 
,03-30 14:15:17.778  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:17.778  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:17.778  3665  3742 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-30 14:15:17.778  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:15:17.778  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:15:17.778  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:15:17.778  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-30 14:15:17.780  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:15:17.780  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:15:17.782  2152  2170 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:15:17.784  2152  2169 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 14:15:17.828   821  1101 I art     : Explicit concurrent mark sweep GC freed 29545(1410KB) AllocSpace objects, 8(693KB) LOS objects, 32% free, 33MB/49MB, paused 1.362ms total 70.423ms
03-30 14:15:17.830  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:15:17.831  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:17.831  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:15:17.831  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:15:17.831  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:17.831  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 14:15:17.832  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 14:15:17.832  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:15:17.834  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:15:17.834  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:17.834  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:15:17.834  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 14:15:17.834  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:15:17.835  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:15:17.835  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:15:17.836  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:15:17.836  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:17.836  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:15:17.836  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:17.837  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 14:15:17.838  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:15:17.838  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:17.840  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:15:17.840  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:17.845  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 14:15:17.845  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:17.845  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:15:17.847  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:15:17.847   821  1418 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:15:17.849  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:15:17.849  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:17.849  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:15:17.850  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:15:17.850  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:17.867  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:15:17.868  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:17.868  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:15:17.870  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:17.870  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:17.870  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:17.870  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:17.871  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:15:17.871  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:17.871  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:15:17.872  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:17.872  3665  3742 I jxcore-log: 
,03-30 14:15:17.873  3665  3742 I jxcore-log: ok 223 discoveryActive matches
03-30 14:15:17.873  3665  3742 I jxcore-log: 
,03-30 14:15:17.874  3665  3742 I jxcore-log: ok 224 advertisingActive matches
03-30 14:15:17.874  3665  3742 I jxcore-log: 
,03-30 14:15:17.876  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:17.876  3665  3742 I jxcore-log: 
,03-30 14:15:17.886  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:17.886  3665  3742 I jxcore-log: 
,03-30 14:15:17.888  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 55800
03-30 14:15:17.888  3665  3742 I jxcore-log: 
,03-30 14:15:17.892  3665  3742 I io.jxcore.node.ConnectionHelper: start: Port number: 55800, start advertisements: true
,03-30 14:15:17.892  3665  3742 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:15:17.892  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:15:17.892  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:15:17.894  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:15:17.894  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:15:17.894  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:15:17.894  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:15:17.896  2152  4119 D BtGatt.GattService: registerClient() - UUID=56bb6c57-7087-41fc-8b64-bd600be689b2
,03-30 14:15:17.897  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=56bb6c57-7087-41fc-8b64-bd600be689b2, clientIf=5
03-30 14:15:17.897  3665  3683 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 14:15:17.897  2152  2170 D BtGatt.GattService: start scan with filters
,03-30 14:15:17.898  2152  2225 D BtGatt.ScanManager: handling starting scan,
03-30 14:15:17.898  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:15:17.898  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:15:17.898  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-30 14:15:17.898  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-30 14:15:17.899  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:17.900  2152  2214 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 14:15:17.900  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:17.900  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:17.900  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:15:17.900  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 14:15:17.900  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 14:15:17.900  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:17.900  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:17.900  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:15:17.901  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 14:15:17.901  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:17.901  2152  2225 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:15:17.901  2152  2225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 14:15:17.903  2152  2214 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 14:15:17.903  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:17.903  2152  2170 D BtGatt.GattService: registerClient() - UUID=d7f0c671-22a5-4eb0-90ee-5d5e80c2caaf
03-30 14:15:17.903  2152  2214 D BtGatt.GattService: onClientRegistered() - UUID=d7f0c671-22a5-4eb0-90ee-5d5e80c2caaf, clientIf=6
,03-30 14:15:17.903  3665  3682 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 14:15:17.904  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 14:15:17.904  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 14:15:17.904  2152  2224 D BtGatt.AdvertiseManager: message : 0
03-30 14:15:17.906  2152  2224 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:15:17.908  2152  2214 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 14:15:17.910  2152  2214 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 14:15:17.911  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:15:17.911  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:15:17.911   821   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:15:17.913  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:15:17.913  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:15:17.913  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-30 14:15:17.913  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:15:17.914  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 14:15:17.914  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-30 14:15:17.914  3665  3742 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:15:17.914  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-30 14:15:17.914  3665  3742 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:15:17.914  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-30 14:15:17.914  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:15:17.914  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:15:17.914  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-30 14:15:17.914  3665  3665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:15:17.914  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:15:17.914  3665  3665 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:15:17.914  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:15:17.914  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:15:17.914  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:15:17.914  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:15:17.914  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:15:17.915   821  1150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 14:15:17.916  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:17.916  3665  3742 I jxcore-log: 
,03-30 14:15:17.917  3665  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-30 14:15:17.918  3665  4128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-30 14:15:17.920  3665  3742 I jxcore-log: not ok 225 discoveryActive matches
03-30 14:15:17.920  3665  3742 I jxcore-log: 
,03-30 14:15:17.920  3665  3742 I jxcore-log:   ---
03-30 14:15:17.920  3665  3742 I jxcore-log: 
03-30 14:15:17.920  3665  3742 I jxcore-log:     operator: equal
03-30 14:15:17.920  3665  3742 I jxcore-log: 
03-30 14:15:17.920  3665  3742 I jxcore-log:     expected: false
03-30 14:15:17.920  3665  3742 I jxcore-log: 
,03-30 14:15:17.920  3665  3742 I jxcore-log:     actual:   true
03-30 14:15:17.920  3665  3742 I jxcore-log: 
03-30 14:15:17.920  3665  3742 I jxcore-log:   ...
03-30 14:15:17.920  3665  3742 I jxcore-log: 
,03-30 14:15:17.923  3665  3742 I jxcore-log: not ok 226 advertisingActive matches
03-30 14:15:17.923  3665  3742 I jxcore-log: 
,03-30 14:15:17.923  3665  3742 I jxcore-log:   ---
03-30 14:15:17.923  3665  3742 I jxcore-log: 
,03-30 14:15:17.923  3665  3742 I jxcore-log:     operator: equal
03-30 14:15:17.923  3665  3742 I jxcore-log: 
03-30 14:15:17.923  3665  3742 I jxcore-log:     expected: true
03-30 14:15:17.923  3665  3742 I jxcore-log: 
03-30 14:15:17.923  3665  3742 I jxcore-log:     actual:   false
03-30 14:15:17.923  3665  3742 I jxcore-log: 
03-30 14:15:17.923  3665  3742 I jxcore-log:   ...
03-30 14:15:17.923  3665  3742 I jxcore-log: 
03-30 14:15:17.925  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:17.925  3665  3742 I jxcore-log: 
,03-30 14:15:17.925  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:15:17.925  3665  3742 I jxcore-log: 
03-30 14:15:17.928  3665  3742 I jxcore-log: not ok 227 discoveryActive matches
03-30 14:15:17.928  3665  3742 I jxcore-log: 
03-30 14:15:17.928  3665  3742 I jxcore-log:   ---
03-30 14:15:17.928  3665  3742 I jxcore-log: 
03-30 14:15:17.928  3665  3742 I jxcore-log:     operator: equal
03-30 14:15:17.928  3665  3742 I jxcore-log: 
03-30 14:15:17.928  3665  3742 I jxcore-log:     expected: false
03-30 14:15:17.928  3665  3742 I jxcore-log: 
03-30 14:15:17.928  3665  3742 I jxcore-log:     actual:   true
03-30 14:15:17.928  3665  3742 I jxcore-log: 
03-30 14:15:17.928  3665  3742 I jxcore-log:   ...
03-30 14:15:17.928  3665  3742 I jxcore-log: 
03-30 14:15:17.930  3665  3742 I jxcore-log: not ok 228 advertisingActive matches
03-30 14:15:17.930  3665  3742 I jxcore-log: 
,03-30 14:15:17.930  3665  3742 I jxcore-log:   ---
03-30 14:15:17.930  3665  3742 I jxcore-log: 
03-30 14:15:17.930  3665  3742 I jxcore-log:     operator: equal
03-30 14:15:17.930  3665  3742 I jxcore-log: 
03-30 14:15:17.930  3665  3742 I jxcore-log:     expected: false
03-30 14:15:17.930  3665  3742 I jxcore-log: 
03-30 14:15:17.930  3665  3742 I jxcore-log:     actual:   true
03-30 14:15:17.930  3665  3742 I jxcore-log: 
03-30 14:15:17.930  3665  3742 I jxcore-log:   ...
03-30 14:15:17.930  3665  3742 I jxcore-log: 
03-30 14:15:17.932  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:15:17.932  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 14:15:17.932  3665  3742 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:15:17.932  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:15:17.932  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:15:17.932  3665  3742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:15:17.932  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:15:17.932  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:15:17.932  3665  4128 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:15:17.932  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:15:17.932  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:15:17.932  3665  4128 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-30 14:15:17.932  3665  4128 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:15:17.932  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:15:17.932  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:15:17.934  2152  4119 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:15:17.934  2152  2170 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 14:15:17.934  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:15:17.935  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:17.935  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:15:17.935  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:15:17.935  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:15:17.935  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:17.935  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 14:15:17.936  2152  2214 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 14:15:17.936  2152  2224 D BtGatt.AdvertiseManager: message : 1
,03-30 14:15:17.936  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:17.936  2152  2225 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:15:17.937  2152  2224 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 14:15:17.938  2152  2214 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 14:15:17.938  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:17.939  2152  2225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 14:15:17.940  2152  2214 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 14:15:17.940  2152  2214 D BtGatt.GattService: Client app is not null!
,03-30 14:15:17.940  2152  4119 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 14:15:17.941  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-30 14:15:17.941  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:17.941  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:15:17.941  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:15:17.941  3665  3742 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-30 14:15:17.941  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:17.941  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:15:17.941  3665  3742 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:15:17.942  2152  2214 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 14:15:17.942  2152  2214 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 14:15:17.942  3665  3742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:15:17.942  3665  3742 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:17.942  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:15:17.942  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:15:17.942  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 14:15:17.946  3665  3665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 14:15:17.946   821  1150 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 14:15:17.949  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:15:17.950  3665  3665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:17.950  3665  3665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:15:17.952  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:15:17.952  3665  3665 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:15:17.952  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:17.952  3665  3665 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:17.952  3665  3665 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:17.952  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:15:17.952  3665  3665 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:17.953  3665  3665 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-30 14:15:17.953  3665  3742 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:15:17.953  3665  3742 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:17.953  3665  3742 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:17.954  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:15:17.954  3665  3742 I jxcore-log: 
,03-30 14:15:17.955  3665  3742 I jxcore-log: ok 229 discoveryActive matches
03-30 14:15:17.955  3665  3742 I jxcore-log: 
,03-30 14:15:17.960  3665  3742 I jxcore-log: not ok 230 advertisingActive matches,
03-30 14:15:17.960  3665  3742 I jxcore-log: 
03-30 14:15:17.961  3665  3742 I jxcore-log:   ---
03-30 14:15:17.961  3665  3742 I jxcore-log: 
,03-30 14:15:17.961  3665  3742 I jxcore-log:     operator: equal
03-30 14:15:17.961  3665  3742 I jxcore-log: 
03-30 14:15:17.961  3665  3742 I jxcore-log:     expected: false
03-30 14:15:17.961  3665  3742 I jxcore-log: 
03-30 14:15:17.961  3665  3742 I jxcore-log:     actual:   true
03-30 14:15:17.961  3665  3742 I jxcore-log: 
03-30 14:15:17.961  3665  3742 I jxcore-log:   ...
03-30 14:15:17.961  3665  3742 I jxcore-log: 
,03-30 14:15:17.963  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:17.963  3665  3742 I jxcore-log: 
03-30 14:15:17.964  3665  3742 I jxcore-log: ok 231 discoveryActive matches
03-30 14:15:17.964  3665  3742 I jxcore-log: 
,03-30 14:15:17.964  3665  3742 I jxcore-log: ok 232 advertisingActive matches
03-30 14:15:17.964  3665  3742 I jxcore-log: ,
03-30 14:15:17.966  3665  3742 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:17.966  3665  3742 I jxcore-log: 
,03-30 14:15:17.977  3665  3742 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:17.977  3665  3742 I jxcore-log: 
,03-30 14:15:17.979  3665  3742 I jxcore-log: DEBUG createNativeListener: listening 35878
03-30 14:15:17.979  3665  3742 I jxcore-log: 
,03-30 14:15:17.986  3665  3742 I jxcore-log: Uncaught Promise Rejection: {}
03-30 14:15:17.986  3665  3742 I jxcore-log: 
,03-30 14:15:17.990  3665  3742 E jxcore-log: Trace: [Error: Call Stop!]
03-30 14:15:17.990  3665  3742 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-30 14:15:17.990  3665  3742 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-30 14:15:17.990  3665  3742 E jxcore-log:     at emit@events.js:98:1
,03-30 14:15:17.990  3665  3742 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-30 14:15:17.990  3665  3742 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-30 14:15:17.990  3665  3742 E jxcore-log:     at $0a@node.js:917:1
03-30 14:15:17.990  3665  3742 E jxcore-log: 
03-30 14:15:17.991  3665  3742 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-30 14:15:17.991  3665  3742 I jxcore-log: 
,03-30 14:15:17.993  3665  3742 I jxcore-log: # teardown
03-30 14:15:17.993  3665  3742 I jxcore-log: 
,03-30 14:15:18.278  4129  4129 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-30 14:15:18.281  4129  4129 D AndroidRuntime: CheckJNI is OFF
,03-30 14:15:18.407  4129  4129 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-30 14:15:18.419   821   855 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
03-30 14:15:18.420   821   855 I ActivityManager: Killing 3665:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-30 14:15:18.477   821   865 W PackageSettings: Skipping PackageSetting{214e32e0 com.example.hello/10273} due to missing metadata
,03-30 14:15:18.559   821  1000 W InputDispatcher: channel '23bad8b2 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
03-30 14:15:18.559   821  1000 E InputDispatcher: channel '23bad8b2 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,03-30 14:15:18.560   821  1414 I WindowState: WIN DEATH: Window{23bad8b2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-30 14:15:18.561   821  1414 W InputDispatcher: Attempted to unregister already unregistered input channel '23bad8b2 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,03-30 14:15:18.561   821  1011 D WifiService: Client connection lost with reason: 4
,03-30 14:15:18.632   821   855 W ActivityManager: Force removing ActivityRecord{120d7d20 u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-30 14:15:18.654   821   865 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-30 14:15:18.662   821  1322 W ActivityManager: Spurious death for ProcessRecord{18f1f88c 3665:com.test.thalitest/u0a95}, curProc for 3665: null
,03-30 14:15:18.663   821  1046 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-30 14:15:18.675  1235  1235 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-30 14:15:18.676   821  1001 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-30 14:15:18.683  3002  3002 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-30 14:15:18.686  1235  4143 I Keyboard.Facilitator.DecoderInitializer: run()
,03-30 14:15:18.704  1235  4143 I Decoder : createOrResetDecoder
,03-30 14:15:18.716  1066  1066 I art     : Explicit concurrent mark sweep GC freed 50656(2MB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 5.235ms total 51.896ms
,03-30 14:15:18.743   821  1101 I ActivityManager: Start proc 4145:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-30 14:15:18.747  1252  1252 I ConfigService: onCreate
,03-30 14:15:18.767  1512  1512 I art     : Explicit concurrent mark sweep GC freed 10085(486KB) AllocSpace objects, 2(32KB) LOS objects, 36% free, 27MB/43MB, paused 1.060ms total 110.397ms
,03-30 14:15:18.768  1235  4143 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-30 14:15:18.783   821   840 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3665 uid 10095
03-30 14:15:18.784  1235  1235 I Keyboard.Facilitator: onFinishInput()
,03-30 14:15:18.790  1235  4143 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-30 14:15:18.791   821   821 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-30 14:15:18.791   821   821 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-30 14:15:18.792  1235  4143 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-30 14:15:18.792  1235  4143 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-30 14:15:18.797  1235  4143 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,03-30 14:15:18.797  1235  4143 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-30 14:15:18.798  1235  4143 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,03-30 14:15:18.798  1235  4143 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-30 14:15:18.799  1235  4143 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-30 14:15:18.799  1235  4143 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-30 14:15:18.799  1235  4143 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-30 14:15:18.799  1235  4143 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-30 14:15:18.799  1235  4143 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-30 14:15:18.799  1235  4143 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-30 14:15:18.817  1512  1512 W LocationOracleImpl: Best location was null
,03-30 14:15:18.834  1512  4169 I HotwordRecognitionRnr: Starting hotword detection.
,03-30 14:15:18.836  1512  4170 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@3abde2bd
,03-30 14:15:18.837  1372  1372 I art     : Explicit concurrent mark sweep GC freed 4963(362KB) AllocSpace objects, 11(1298KB) LOS objects, 31% free, 35MB/51MB, paused 774us total 24.832ms
,03-30 14:15:18.840   359  4173 I AudioFlinger: AudioFlinger's thread 0xb4064000 ready to run
,03-30 14:15:18.844   359  1030 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-30 14:15:18.844  1512  4170 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@3abde2bd
,03-30 14:15:18.854   359  4173 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-30 14:15:18.854   359  4173 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-30 14:15:18.854   359  4173 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-30 14:15:18.854   359  4173 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-30 14:15:18.862   359  4173 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-30 14:15:18.867   821   865 I art     : Explicit concurrent mark sweep GC freed 18658(1745KB) AllocSpace objects, 5(268KB) LOS objects, 32% free, 33MB/49MB, paused 3.059ms total 200.673ms
,03-30 14:15:18.867  4145  4178 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-30 14:15:18.892   821  3150 I ActivityManager: Start proc 4179:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-30 14:15:18.903  4129  4129 I art     : System.exit called, status: 0
03-30 14:15:18.903  4129  4129 I AndroidRuntime: VM exiting with result code 0.
,03-30 14:15:18.920  4145  4166 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-30 14:15:18.936  1512  1512 I HotwordWorker: onReady
,03-30 14:15:18.956   821   865 I ActivityManager: Start proc 4201:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-30 14:15:18.963  1372  1372 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-30 14:15:18.964  1372  1372 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-30 14:15:18.996   821  3150 I ActivityManager: Start proc 4222:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-30 14:15:19.023   821  1418 I ActivityManager: Killing 3697:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,03-30 14:15:19.029   821   839 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@119e9af8}
,03-30 14:15:19.032   821  1010 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-30 14:15:19.033  4222  4222 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-30 14:15:19.041  4145  4166 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
,--------- beginning of crash
03-30 14:15:19.042  4145  4166 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-30 14:15:19.042  4145  4166 E AndroidRuntime: Process: android.process.acore, PID: 4145
03-30 14:15:19.042  4145  4166 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-30 14:15:19.042  4145  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-30 14:15:19.042  4145  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-30 14:15:19.042  4145  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-30 14:15:19.042  4145  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-30 14:15:19.042  4145  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-30 14:15:19.042  4145  4166 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-30 14:15:19.042  4145  4166 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-30 14:15:19.042  4145  4166 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-30 14:15:19.042  4145  4166 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.042  4145  4166 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-30 14:15:19.042  4145  4166 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-30 14:15:19.075   821  1271 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658295571
03-30 14:15:19.075   821  1271 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-30 14:15:19.145   821  4241 E DropBoxManagerService: Can't write: system_app_crash
03-30 14:15:19.145   821  4241 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
03-30 14:15:19.145   821  4241 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 14:15:19.145   821  4241 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 14:15:19.145   821  4241 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-30 14:15:19.145   821  4241 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-30 14:15:19.145   821  4241 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-30 14:15:19.145   821  4241 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-30 14:15:19.145   821  4241 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 14:15:19.145   821  4241 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-30 14:15:19.145   821  4241 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 14:15:19.145   821  4241 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 14:15:19.145   821  4241 E DropBoxManagerService: 	... 5 more
,03-30 14:15:19.149  1252  1252 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
03-30 14:15:19.150  1252  1252 D AndroidRuntime: Shutting down VM
03-30 14:15:19.150  1252  1252 E AndroidRuntime: FATAL EXCEPTION: main
03-30 14:15:19.150  1252  1252 E AndroidRuntime: Process: com.google.process.gapps, PID: 1252
03-30 14:15:19.150  1252  1252 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-30 14:15:19.150  1252  1252 E AndroidRuntime: 	... 9 more
,03-30 14:15:19.156  4222  4243 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-30 14:15:19.156  4222  4243 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-30 14:15:19.157  4222  4243 E AndroidRuntime: Process: com.android.keychain, PID: 4222
03-30 14:15:19.157  4222  4243 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-30 14:15:19.157  4222  4243 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-30 14:15:19.158   821  4244 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-30 14:15:19.159   821   855 D Atlas   : Validating map...
03-30 14:15:19.166   821  4245 E DropBoxManagerService: Can't write: system_app_crash
03-30 14:15:19.166   821  4245 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
03-30 14:15:19.166   821  4245 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 14:15:19.166   821  4245 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 14:15:19.166   821  4245 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-30 14:15:19.166   821  4245 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-30 14:15:19.166   821  4245 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-30 14:15:19.166   821  4245 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-30 14:15:19.166   821  4245 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 14:15:19.166   821  4245 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-30 14:15:19.166   821  4245 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 14:15:19.166   821  4245 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 14:15:19.166   821  4245 E DropBoxManagerService: 	... 5 more
03-30 14:15:19.168   821  4246 E DropBoxManagerService: Can't write: system_app_crash
03-30 14:15:19.168   821  4246 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
03-30 14:15:19.168   821  4246 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 14:15:19.168   821  4246 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 14:15:19.168   821  4246 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-30 14:15:19.168   821  4246 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-30 14:15:19.168   821  4246 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-30 14:15:19.168   821  4246 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-30 14:15:19.168   821  4246 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 14:15:19.168   821  4246 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-30 14:15:19.168   821  4246 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 14:15:19.168   821  4246 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 14:15:19.168   821  4246 E DropBoxManagerService: 	... 5 more
,03-30 14:15:19.203   821  4244 I OpenGLRenderer: Initialized EGL, version 1.4
03-30 14:15:19.214   821  4244 D OpenGLRenderer: Enabling debug mode 0
,03-30 14:15:19.421  1512  1512 I HotwordDetector: Closing mic
03-30 14:15:19.421  1512  1764 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@3abde2bd
,03-30 14:15:19.470  1512  4252 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-30 14:15:19.474   821   839 I ActivityManager: Killing 3794:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-30 14:15:19.484   359  4173 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,03-30 14:15:19.485   359  4173 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
,03-30 14:15:19.488   359  1030 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-30 14:15:19.510  1512  4169 I HotwordRecognitionRnr: Hotword detection finished
03-30 14:15:19.510  1512  1765 I HotwordRecognitionRnr: Stopping hotword detection.
,03-30 14:15:19.579   821   839 I ActivityManager: Killing 3200:com.google.android.talk/u0a61 (adj 15): empty #18
,03-30 14:15:19.844  1235  4143 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-30 14:15:19.844  1235  4143 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-30 14:15:19.868  1235  4143 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-30 14:15:19.868  1235  4143 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-30 14:15:19.891  1235  4143 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp,
03-30 14:15:19.891  1235  4143 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-30 14:15:19.892  1235  4143 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-30 14:15:19.892  1235  4143 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-30 14:15:20.722   821  1321 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@119e9af8}
,03-30 14:15:23.834  1512  4258 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-30 14:15:24.329   821  1271 E QMI_FW  : xport_send: Sendto failed for port 4608
03-30 14:15:24.329   821  1271 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-30 14:15:24.329   821  1271 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1658295571
03-30 14:15:24.329   821  1271 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-30 14:15:24.335   259   316 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0,
,03-30 14:15:24.341   872   872 E kickstart: ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,03-30 14:15:24.341   872   872 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error
03-30 14:15:24.341   872   872 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
03-30 14:15:24.342   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_unlock

```
