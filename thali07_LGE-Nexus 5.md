#### Test 646138036c5f71d_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-31 15:13:49.891  1563  2475 I CheckinService: Done disabling old GoogleServicesFramework version
,03-31 15:13:50.222  3304  3304 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 15:13:50.227  3304  3304 D AndroidRuntime: CheckJNI is OFF
03-31 15:13:50.322  3304  3304 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-31 15:13:50.325   763  1423 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 15:13:50.331   763  1423 V WindowManager: addAppToken: AppWindowToken{f9d14ce token=Token{2467f5c9 ActivityRecord{45c21d0 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-31 15:13:50.338   763   837 V WindowManager: Adding window Window{3239501 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2c54d81 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 15:13:50.342  3304  3304 D AndroidRuntime: Shutting down VM
03-31 15:13:50.348  1398  1422 W SearchService: Abort, client detached.
03-31 15:13:50.389   763   938 I ActivityManager: Start proc 3325:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-31 15:13:50.399  1398  1592 I DeviceStateChecker: DeviceStateChecker cancelled
03-31 15:13:50.401  1398  1398 I MicroDetector: Keeping mic open: false
03-31 15:13:50.401  1398  1398 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@24e78b3e
03-31 15:13:50.452   190  1599 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 15:13:50.452   190  1599 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 15:13:50.459  1398  1596 I MicroRecognitionRunner: Detection finished
03-31 15:13:50.461  1398  1591 I MicroRecognitionRunner: Stopping hotword detection.
03-31 15:13:50.501  3325  3325 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
03-31 15:13:50.511  3325  3325 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 8117-8118)
03-31 15:13:50.511  3325  3325 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 15:13:50.519   763  1224 I ActivityManager: Killing 2089:com.android.providers.calendar/u0a1 (adj 15): empty #17
03-31 15:13:50.520  3325  3325 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3db09c24}
03-31 15:13:50.520  3325  3325 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 15:13:50.520  3325  3325 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 15:13:50.544  3325  3325 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,03-31 15:13:50.558  3325  3325 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-31 15:13:50.598   763   836 D BluetoothManagerService: Message: 20
03-31 15:13:50.598   763   836 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33afed7:true
,03-31 15:13:50.605  3325  3325 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-31 15:13:50.605  3325  3325 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-31 15:13:50.640  3325  3325 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-31 15:13:50.640  3325  3325 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-31 15:13:50.656  3325  3325 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-31 15:13:50.662  3325  3325 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 15:13:50.663  3325  3325 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-31 15:13:50.672  3325  3325 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-31 15:13:50.694  3325  3383 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 15:13:50.699  3325  3325 D Atlas   : Validating map...
,03-31 15:13:50.704   763   938 V WindowManager: Adding window Window{3989df92 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3239501 u0 Starting com.test.thalitest})
,03-31 15:13:50.713   763   868 D WifiService: New client listening to asynchronous messages
03-31 15:13:50.722   763  1223 D ConnectivityService: listenForNetwork for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 15:13:50.723   763   869 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 15:13:50.723   763   869 D ConnectivityService: apparently satisfied.  currentScore=60
03-31 15:13:50.723  3325  3385 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 15:13:50.743  3325  3383 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 15:13:50.749  3325  3383 D OpenGLRenderer: Enabling debug mode 0
,03-31 15:13:50.787  1102  1102 I Keyboard.Facilitator: onFinishInput()
,03-31 15:13:50.806   763   837 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +445ms
,03-31 15:13:50.825  3325  3392 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-31 15:13:50.860  3325  3325 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3325
,03-31 15:13:50.883   763   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,03-31 15:13:51.039  3325  3325 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 15:13:51.131  3325  3398 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362698112
,03-31 15:13:51.132   763  1154 D AlarmManagerService: Setting time of day to sec=1459430031
03-31 15:13:51.149   763  1154 W AlarmManagerService: Unable to set rtc to 1459430031: Invalid argument
,03-31 15:13:51.153  3325  3398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 15:13:51.153  3325  3398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 15:13:51.153  3325  3398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 15:13:51.153  3325  3398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 15:13:51.153  3325  3398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 15:13:51.153  3325  3398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87d2f87 added. We now have 1 listener(s)
,03-31 15:13:51.168  1661  1722 I Finsky  : [136] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-31 15:13:51.169  1661  1661 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 15:13:51.190   763   831 I ActivityManager: Start proc 3399:com.qualcomm.timeservice/u0a68 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
03-31 15:13:51.191   763  1226 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 15:13:51.193  3325  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
03-31 15:13:51.194  3325  3398 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-31 15:13:51.195  3325  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 15:13:51.195  3325  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 15:13:51.197  3325  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b58e652 added. We now have 1 listener(s)
03-31 15:13:51.198  3325  3398 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 15:13:51.206  3325  3398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-31 15:13:51.207  3325  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-31 15:13:51.207  3325  3398 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-31 15:13:51.209  3325  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 15:13:51.210   763  1224 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 15:13:51.210  3325  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-31 15:13:51.213  3325  3398 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 15:13:51.213  3325  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 15:13:51.213  3325  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 15:13:51.213  3325  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 15:13:51.213  3325  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 15:13:51.213  3325  3398 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 15:13:51.213  3325  3398 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 15:13:51.213  3325  3398 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 15:13:51.213  3325  3398 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-31 15:13:51.213  3325  3398 D io.jxcore.node.ConnectivityMonitor: start: OK
03-31 15:13:51.214  3325  3398 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 15:13:51.217  3325  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 15:13:51.219  3325  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 15:13:51.252  3399  3399 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459430031252
03-31 15:13:51.252  3399  3399 D         : TimeServiceNative: User Time to be set is 1459430031252
03-31 15:13:51.252  3399  3399 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-31 15:13:51.252  3399  3399 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-31 15:13:51.252  3399  3399 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459430031252
03-31 15:13:51.252   204   606 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-31 15:13:51.254   204  3423 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459430031252
03-31 15:13:51.254   204  3423 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459430031252, operation = 0
03-31 15:13:51.254   204  3423 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/22/71 7:18:21
,03-31 15:13:51.254   204  3423 D QC-time-services: Daemon:Value read from RTC seconds = 43744701000
03-31 15:13:51.254   204  3423 D QC-time-services: Daemon:new time 1459430031252 
03-31 15:13:51.254   204  3423 D QC-time-services: Daemon: delta 1415685330252 genoff 1415685330252 
03-31 15:13:51.254   204  3423 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1415685330252 to memory
03-31 15:13:51.254   204  3423 D QC-time-services: Daemon:Opening File: /data/system/time/ats_2
03-31 15:13:51.254   204  3423 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-31 15:13:51.255  3399  3399 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-31 15:13:51.261   204  3423 D QC-time-services: Updating the TOD offset
03-31 15:13:51.261   204  3423 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1415685330252 to memory
03-31 15:13:51.261   204  3423 D QC-time-services: Daemon:Opening File: /data/system/time/ats_1
03-31 15:13:51.261   204  3423 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-31 15:13:51.261  3325  3325 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 15:13:51.267   204  3423 D QC-time-services: Daemon:Update to modem bit set
03-31 15:13:51.267   204  3423 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-31 15:13:51.267   204  3423 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143465231252
03-31 15:13:51.268  3399  3399 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-31 15:13:51.271   204   606 D QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-31 15:13:51.272   204   604 D QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-31 15:13:51.273   763  1226 I ActivityManager: Killing 2983:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-31 15:13:51.477   763   779 I ActivityManager: Start proc 3427:com.google.android.deskclock/u0a33 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-31 15:13:51.526  3427  3427 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
03-31 15:13:51.526  3427  3427 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 15:13:51.526  3427  3427 I GAv4    :   adb logcat -s GAv4
,03-31 15:13:51.539  3427  3427 I AlarmClock: AlarmInitReceiver android.intent.action.TIME_SET
,03-31 15:13:51.583  3171  3448 E SQLiteLog: (284) automatic index on blob_node(tree_entity_id)
03-31 15:13:51.585  3171  3448 E SQLiteLog: (284) automatic index on blob_node(tree_entity_id)
,03-31 15:13:51.597   763  1224 I ActivityManager: Killing 3003:com.android.musicfx/u0a13 (adj 15): empty #17
,03-31 15:13:51.851  3325  3416 W jxcore-log: Initializing JXcore engine
03-31 15:13:51.851  3325  3416 W jxcore-log: JXcore engine is ready
,03-31 15:13:51.869  3416  3416 W Thread-322: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9487]" dev="sockfs" ino=9487 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-31 15:13:51.869  3416  3416 W Thread-322: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-31 15:13:51.869  3416  3416 W Thread-322: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8430]" dev="sockfs" ino=8430 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-31 15:13:51.879  3416  3416 W Thread-322: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[18598]" dev="sockfs" ino=18598 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-31 15:13:51.896  3325  3416 W jxcore-log: Starting JXcore engine
,03-31 15:13:51.971  3325  3416 W jxcore-log: Platform android
03-31 15:13:51.971  3325  3416 W jxcore-log: 
03-31 15:13:51.971  3325  3416 W jxcore-log: Process ARCH arm
03-31 15:13:51.971  3325  3416 W jxcore-log: 
,03-31 15:13:52.163  3325  3416 I jxcore-log: JXcore Cordova bridge is ready!
03-31 15:13:52.163  3325  3416 I jxcore-log: 
03-31 15:13:52.163  3325  3416 W jxcore-log: JXcore engine is started
,03-31 15:13:52.170  3325  3398 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 15:13:52.171  3325  3325 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 15:13:59.693   763  1224 I ActivityManager: Start proc 3472:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,03-31 15:13:59.724  3472  3472 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-31 15:13:59.751  3472  3472 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@7e4cb7(com.android.providers.calendar.CalendarProvider2@3db09c24)
,03-31 15:13:59.761   763  1423 I ActivityManager: Killing 1942:com.android.defcontainer/u0a4 (adj 15): empty #17
,03-31 15:14:00.068   763  1423 I ActivityManager: Killing 3031:com.google.android.apps.docs/u0a35 (adj 15): empty #18
,03-31 15:14:00.661  1661  1661 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-31 15:14:00.670  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:00.675  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:00.676  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:00.788  3472  3472 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-31 15:14:00.789  3472  3472 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-31 15:14:01.257  3325  3416 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 15:14:01.257  3325  3416 I jxcore-log: 
,03-31 15:14:01.259  3325  3416 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 15:14:01.259  3325  3416 I jxcore-log: 
,03-31 15:14:01.263  3325  3416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 15:14:01.263  3325  3416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 15:14:01.263  3325  3416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 15:14:01.263  3325  3416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 15:14:01.263  3325  3416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 15:14:01.263  3325  3416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 15:14:01.263  3325  3416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 15:14:01.263  3325  3416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 15:14:01.264  3325  3416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 15:14:01.266  3325  3416 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 15:14:01.266  3325  3416 I jxcore-log: 
03-31 15:14:01.268  3325  3416 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 15:14:01.268  3325  3416 I jxcore-log: 
,03-31 15:14:01.563  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:01.693  1661  1706 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-31 15:14:01.693  1661  1706 I qtaguid : Untagging socket 37 failed errno=-22
03-31 15:14:01.693  1661  1706 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-31 15:14:01.696  1661  1661 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-31 15:14:01.740  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:01.764  3325  3416 I jxcore-log: Unit Test app is loaded
03-31 15:14:01.764  3325  3416 I jxcore-log: 
,03-31 15:14:01.770  3325  3416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 15:14:01.770  3325  3416 I jxcore-log: 
,03-31 15:14:01.770  3325  3325 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 15:14:01.773  3325  3416 I jxcore-log: My device name is: LGE-Nexus 5
03-31 15:14:01.773  3325  3416 I jxcore-log: 
,03-31 15:14:01.779   763   779 I ActivityManager: Start proc 3519:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-31 15:14:01.835  3519  3519 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 15:14:01.835  3519  3519 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 15:14:01.860  3519  3519 I MultiDex: VM with version 2.1.0 has multidex support
03-31 15:14:01.860  3519  3519 I MultiDex: install
03-31 15:14:01.860  3519  3519 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 15:14:01.876  3519  3519 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-31 15:14:01.910  3519  3519 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 15:14:01.923  1514  1514 D WearableService: callingUid 10007, callindPid: 1514
,03-31 15:14:01.926  1514  1977 E MDM     : [176] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-31 15:14:01.938  3519  3519 D ChimeraCfgMgr: Reading stored module config
,03-31 15:14:01.959  1563  3538 D LocationInitializer: Restart initialization of location
,03-31 15:14:01.964  1514  1514 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 15:14:01.979  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:02.007  1514  1631 W GCoreFlp: No location to return for getLastLocation()
03-31 15:14:02.007  1514  3540 W FusedLocationProvider: location=null
,03-31 15:14:02.070  3519  3539 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-31 15:14:02.076  3519  3519 D CAR.SERVICE: Connecting to CarCallService...
,03-31 15:14:02.095  3519  3519 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 15:14:02.095  3519  3519 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 15:14:02.104  3519  3519 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-31 15:14:02.110  3519  3519 D CAR.TEL.Service: Creating a new CarCallService.
,03-31 15:14:02.112  3519  3519 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-31 15:14:02.115   763  1113 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-31 15:14:02.116  3519  3519 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@3ae8254d
,03-31 15:14:02.116   763  1112 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-31 15:14:02.116  3519  3519 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-31 15:14:02.116  3519  3519 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-31 15:14:02.135  1661  1705 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-31 15:14:02.135  1661  1705 I qtaguid : Untagging socket 37 failed errno=-22
,03-31 15:14:02.135  1661  1705 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-31 15:14:02.178  3519  3534 D CAR.SERVICE: Package validated; name: com.android.vending
,03-31 15:14:02.693   763  1224 I art     : Explicit concurrent mark sweep GC freed 25061(1196KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.097ms total 50.314ms
,03-31 15:14:02.696  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:04.788  3472  3591 E SQLiteLog: (284) automatic index on view_events(_id)
,03-31 15:14:05.580  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 15:14:05.580  3325  3416 I jxcore-log: 
,03-31 15:14:05.925  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 15:14:05.925  3325  3416 I jxcore-log: 
,03-31 15:14:05.936  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 15:14:05.936  3325  3416 I jxcore-log: 
,03-31 15:14:05.940  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 15:14:05.940  3325  3416 I jxcore-log: 
,03-31 15:14:05.977  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 15:14:05.977  3325  3416 I jxcore-log: 
,03-31 15:14:05.992  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 15:14:05.992  3325  3416 I jxcore-log: 
03-31 15:14:05.995  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 15:14:05.995  3325  3416 I jxcore-log: 
,03-31 15:14:06.999   763   938 I ActivityManager: Killing 3119:com.quickoffice.android/u0a65 (adj 15): empty #17
,03-31 15:14:07.231  3519  3519 D CAR.SERVICE: mConnectedToCar = false, abort
,03-31 15:14:07.234   763  1113 I ActivityManager: Killing 2945:com.google.android.apps.photos/u0a83 (adj 15): empty #17
,03-31 15:14:07.247  3519  3519 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1f107895 that was originally bound here
03-31 15:14:07.247  3519  3519 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1f107895 that was originally bound here
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-31 15:14:07.247  3519  3519 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,03-31 15:14:07.336  3519  3519 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1ef10ce4 that was originally bound here
03-31 15:14:07.336  3519  3519 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1ef10ce4 that was originally bound here
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-31 15:14:07.336  3519  3519 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,03-31 15:14:07.337   763   778 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@1934e7ae
,03-31 15:14:07.360  1661  1706 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-31 15:14:07.360  1661  1706 I qtaguid : Untagging socket 37 failed errno=-22
03-31 15:14:07.360  1661  1706 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
03-31 15:14:07.361  1661  1706 D Volley  : [124] c.a: HTTP response for request=<[ ] https://android.clients.google.com/fdfe/bulkDetails?au=1 0xe8d195d1 NORMAL 5> [lifetime=4719], [size=88910], [rc=200], [retryCount=0]
,03-31 15:14:07.451  1661  1674 I art     : WaitForGcToComplete blocked for 62.142ms for cause HomogeneousSpaceCompact
,03-31 15:14:07.549  1661  1661 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,03-31 15:14:07.577  1514  1514 D WearableService: callingUid 10007, callindPid: 1514
,03-31 15:14:07.579  1514  1532 D DeviceConnectionService: client connected with version: 8298000
,03-31 15:14:07.593  1661  1661 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-31 15:14:07.593  1661  1661 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,03-31 15:14:07.941  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 15:14:07.941  3325  3416 I jxcore-log: 
,03-31 15:14:07.957  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 15:14:07.957  3325  3416 I jxcore-log: 
,03-31 15:14:07.965  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 15:14:07.965  3325  3416 I jxcore-log: 
,03-31 15:14:08.209  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 15:14:08.209  3325  3416 I jxcore-log: 
,03-31 15:14:08.279  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 15:14:08.279  3325  3416 I jxcore-log: 
,03-31 15:14:08.332  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 15:14:08.332  3325  3416 I jxcore-log: 
,03-31 15:14:08.338  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 15:14:08.338  3325  3416 I jxcore-log: 
,03-31 15:14:08.346  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 15:14:08.346  3325  3416 I jxcore-log: 
,03-31 15:14:08.350  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 15:14:08.350  3325  3416 I jxcore-log: 
03-31 15:14:08.355  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 15:14:08.355  3325  3416 I jxcore-log: 
,03-31 15:14:08.370  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 15:14:08.370  3325  3416 I jxcore-log: 
,03-31 15:14:08.388  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 15:14:08.388  3325  3416 I jxcore-log: 
,03-31 15:14:08.472  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 15:14:08.472  3325  3416 I jxcore-log: 
,03-31 15:14:08.476  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 15:14:08.476  3325  3416 I jxcore-log: 
,03-31 15:14:08.500  3325  3416 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 15:14:08.500  3325  3416 I jxcore-log: 
,03-31 15:14:08.507  3325  3416 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,03-31 15:14:08.508  3325  3416 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-31 15:14:08.508  3325  3416 I jxcore-log: 
,03-31 15:14:10.902   763   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 15:14:10.903   763   867 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 15:14:12.614  1661  3606 I Finsky  : [146] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-31 15:14:12.618  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:12.623  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:12.624  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:17.676  1661  1722 I Finsky  : [136] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
03-31 15:14:17.676  1661  1661 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 15:14:30.906   763   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,03-31 15:14:33.563  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:33.570  1514  3660 I VacuumService: Vacuum at: now=1459430073570 tag=VacuumService
,03-31 15:14:34.788  1514  3669 I art     : Explicit concurrent mark sweep GC freed 109652(6MB) AllocSpace objects, 35(560KB) LOS objects, 39% free, 24MB/40MB, paused 1.094ms total 79.715ms
,03-31 15:14:34.829  1514  3677 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 7275 seconds from now (1459430074829)
,03-31 15:14:34.914  1514  3669 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-31 15:14:34.917  1514  3669 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 15:14:35.643  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:35.645  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:50.804  1102  1367 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-31 15:14:50.804  1102  1367 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 15:14:50.856  1514  1514 I ConfigService: onCreate
,03-31 15:14:50.906   763   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 15:14:50.906   763   867 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 15:14:55.904  1514  1514 I ConfigService: onDestroy
,03-31 15:15:10.910   763   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 15:15:10.911   763   867 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 15:15:25.175   763   839 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-31 15:15:25.189   763   839 I PowerManagerService: Sleeping (uid 1000)...
,03-31 15:15:25.240   190   866 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-31 15:15:25.244   763   839 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-31 15:15:25.250   763   867 E WifiStateMachine: cancelDelayedScan -> 11
,03-31 15:15:25.255   183  1583 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (347 us)
,03-31 15:15:25.261   763   867 E native  : do suspend false
,03-31 15:15:25.397  1984  2052 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 15:15:25.426  1102  1102 I Keyboard.Facilitator: onFinishInput()
,03-31 15:15:25.427   190   190 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,03-31 15:15:25.440   763   867 E WifiStateMachine: cancelDelayedScan -> 13
,03-31 15:15:25.441   763   867 E native  : do suspend true
,03-31 15:15:25.759   763   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,03-31 15:15:25.762   763   867 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,03-31 15:15:25.820   763   837 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-31 15:15:25.822   763   763 V ActivityManager: Display changed displayId=0
03-31 15:15:25.824   183   183 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-31 15:15:25.824   183   183 D qdhwcomposer: hwc_blank: Blanking display: 0
,03-31 15:15:25.934   184   184 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
03-31 15:15:25.934   184   184 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
03-31 15:15:25.934   184   184 I rmt_storage: wakelock acquired: 1, error no: 2
03-31 15:15:25.934   184   571 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236803456)
,03-31 15:15:26.005   184   571 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,03-31 15:15:26.005   184   571 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
03-31 15:15:26.006   184   571 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236803456) wakelock released: 1, error no: 0
03-31 15:15:26.006   184   571 I rmt_storage: 
,03-31 15:15:26.008   184   184 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,03-31 15:15:26.108   183   183 D qdhwcomposer: hwc_blank: Done blanking display: 0
03-31 15:15:26.109   763   884 D SurfaceControl: Excessive delay in setPowerMode(): 288ms
03-31 15:15:26.109  1885  1886 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,03-31 15:15:26.124  3325  3325 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
03-31 15:15:26.124  3325  3325 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-31 15:15:26.168  3325  3325 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1236fbb5 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2c2e7409, 16908290=android.view.AbsSavedState$1@2c2e7409}, android:focusedViewId=100}]}]
03-31 15:15:26.168  3325  3325 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
03-31 15:15:26.168  3325  3325 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
03-31 15:15:26.168  3325  3325 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,03-31 15:15:30.914   763   867 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 15:15:30.914   763   867 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,03-31 15:15:32.108  1514  1875 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-31 15:16:25.427  1102  1367 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-31 15:16:25.427  1102  1367 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 15:16:25.476  1514  1514 I ConfigService: onCreate
,03-31 15:16:30.524  1514  1514 I ConfigService: onDestroy
,03-31 15:28:19.637  1398  3740 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,03-31 15:28:19.711  1398  3740 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
03-31 15:28:19.711  1398  3740 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,03-31 15:28:19.717  1398  3740 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
03-31 15:28:19.717  1398  3740 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,03-31 15:28:19.774  1398  3740 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
03-31 15:28:19.774  1398  3740 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,03-31 15:28:19.815  1563  1627 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,03-31 15:28:19.878  1398  3740 I ContextCompilationHandl: Recognition context unchanged for APP_NAMES en-US
,03-31 15:28:19.878  1398  3740 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,03-31 15:28:19.904  1563  1653 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,03-31 15:28:19.946  1563  2482 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,03-31 15:28:19.971  1563  1653 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,03-31 15:28:20.004  1563  2482 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,03-31 15:28:20.026  1398  3740 E ContextCompilationHandl: No recognition context built for MUSIC_NAMES en-US
,03-31 15:28:27.231  1984  2066 W bt-btm  : Stopping oneshot timer
,03-31 15:33:15.950   763   830 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),03-31 15:37:21.345  3749  3749 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 15:37:21.347  3749  3749 D AndroidRuntime: CheckJNI is OFF
03-31 15:37:21.433  3749  3749 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-31 15:37:21.440   763   831 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-31 15:37:21.440   763   831 I ActivityManager: Killing 3325:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
03-31 15:37:21.476   763  1223 I WindowState: WIN DEATH: Window{3989df92 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-31 15:37:21.477   763   868 D WifiService: Client connection lost with reason: 4
03-31 15:37:21.477   763  1424 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@359e57a5)
03-31 15:37:21.477   763   869 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 15:37:21.478   763   869 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 15:37:21.500   763   843 W PackageSettings: Skipping PackageSetting{ed6b87c com.example.hello/10116} due to missing metadata
03-31 15:37:21.550   763   831 I ActivityManager:   Force finishing activity 3 ActivityRecord{45c21d0 u0 com.test.thalitest/.MainActivity t19}
03-31 15:37:21.555   763   779 W ActivityManager: Spurious death for ProcessRecord{1bdc77a 3325:com.test.thalitest/u0a49}, curProc for 3325: null
03-31 15:37:21.556   763   843 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
03-31 15:37:21.557   763   843 I ActivityManager:   Force finishing activity 3 ActivityRecord{45c21d0 u0 com.test.thalitest/.MainActivity t19 f}
03-31 15:37:21.557   763   843 W ActivityManager: Duplicate finish request for ActivityRecord{45c21d0 u0 com.test.thalitest/.MainActivity t19 f}
03-31 15:37:21.590   907   907 I art     : Explicit concurrent mark sweep GC freed 9884(435KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 3.380ms total 24.990ms
03-31 15:37:21.611  1227  1227 I art     : Explicit concurrent mark sweep GC freed 1718(107KB) AllocSpace objects, 6(531KB) LOS objects, 38% free, 25MB/41MB, paused 1.721ms total 49.333ms
03-31 15:37:21.653   763   886 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
03-31 15:37:21.653   763   886 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
03-31 15:37:21.656  1102  1102 I Keyboard.Facilitator: resetDictionaries() : en_US
03-31 15:37:21.656  1514  1637 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-31 15:37:21.660   763   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-31 15:37:21.662  1398  1398 I art     : Explicit concurrent mark sweep GC freed 24083(2MB) AllocSpace objects, 9(2MB) LOS objects, 25% free, 22MB/29MB, paused 832us total 100.975ms
03-31 15:37:21.671  1102  3783 I Keyboard.Facilitator.DecoderInitializer: run()
03-31 15:37:21.678  1563  1563 I art     : Explicit concurrent mark sweep GC freed 11287(650KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 23MB/30MB, paused 433us total 94.212ms
03-31 15:37:21.681   763   763 I art     : Explicit concurrent mark sweep GC freed 352055(7MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 29MB/44MB, paused 1.570ms total 97.935ms
03-31 15:37:21.684   763   843 I art     : WaitForGcToComplete blocked for 13.263ms for cause Explicit
03-31 15:37:21.686  1102  3783 I Decoder : createOrResetDecoder
03-31 15:37:21.693  1342  3784 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
03-31 15:37:21.709  1563  1574 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-31 15:37:21.712   763   938 I ActivityManager: Start proc 3786:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
03-31 15:37:21.751  1514  1514 I ConfigService: onCreate
03-31 15:37:21.766   763   763 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 15:37:21.766   763   763 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-31 15:37:21.787  1102  3783 I Keyboard.Facilitator.MainLanguageModelLoader: run()
03-31 15:37:21.806   763  1424 I ActivityManager: Start proc 3806:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
03-31 15:37:21.808   763   938 I ActivityManager: Killing 2591:com.google.android.gm/u0a41 (adj 15): empty #17
03-31 15:37:21.817  1102  3783 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-31 15:37:21.820  1102  3783 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 15:37:21.820  1102  3783 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-31 15:37:21.822  1102  3783 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-31 15:37:21.822  1102  3783 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-31 15:37:21.823   763  1224 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3325 uid 10049
03-31 15:37:21.824  1102  1102 I Keyboard.Facilitator: onFinishInput()
03-31 15:37:21.824  1102  3783 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 15:37:21.824  1102  3783 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-31 15:37:21.825  1102  3783 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 15:37:21.825  1102  3783 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 15:37:21.825  1102  3783 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-31 15:37:21.825  1102  3783 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 15:37:21.825  1102  3783 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 15:37:21.825  1102  3783 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
03-31 15:37:21.838   763   843 I art     : Explicit concurrent mark sweep GC freed 12817(1231KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 29MB/44MB, paused 1.154ms total 153.695ms
03-31 15:37:21.849  1227  1227 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-31 15:37:21.869  3806  3806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
03-31 15:37:21.881  1563  3827 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-31 15:37:21.881  1563  3827 D AccountUtils: Clearing selected account for com.test.thalitest
03-31 15:37:21.885  1514  1514 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-31 15:37:21.885  1514  1514 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
03-31 15:37:21.903  3749  3749 I art     : System.exit called, status: 0
03-31 15:37:21.903  3749  3749 I AndroidRuntime: VM exiting with result code 0.
03-31 15:37:21.905   763  1226 I ActivityManager: Start proc 3831:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
03-31 15:37:21.908  1563  3827 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
03-31 15:37:21.916   201   201 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 273us total 11.065ms
03-31 15:37:21.926   201   201 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 196us total 8.923ms
03-31 15:37:21.936   201   201 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 196us total 9.339ms
03-31 15:37:21.958   763   843 I ActivityManager: Start proc 3850:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
03-31 15:37:21.995  1563  3869 W BaseAppContext: Using Auth Proxy for data requests.
03-31 15:37:21.997  1563  3869 W BaseAppContext: Using Auth Proxy for data requests.
03-31 15:37:22.001   763   779 I ActivityManager: Killing 2764:com.google.android.music:main/u0a58 (adj 15): empty #17
03-31 15:37:22.045  1563  3827 I GMPM-SVC: App measurement is starting up, version: 8703
03-31 15:37:22.045  1563  3827 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(:com.google.android.gms:223)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(:com.google.android.gms:601)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(:com.google.android.gms:595)
03-31 15:37:22.061  1563  3873 E SQLiteDatabase: 	at com.google.android.gms.drive.database.o.run(:com.google.android.gms:616)
03-31 15:37:22.069  1563  3827 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-31 15:37:22.071  1563  3873 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-31 15:37:22.071  1563  1619 I Icing   : doRemovePackageData com.test.thalitest
03-31 15:37:22.071  1563  3873 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-31 15:37:22.071  1563  3873 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-31 15:37:22.071  1563  3873 I GCore-Chimera-Crash: ==
03-31 15:37:22.071  1563  3873 I GCore-Chimera-Crash: GCore-Chimera-Crash
03-31 15:37:22.071  1563  3875 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
03-31 15:37:22.076  1563  3873 E AndroidRuntime: FATAL EXCEPTION: Open database in background
03-31 15:37:22.076  1563  3873 E AndroidRuntime: Process: com.google.android.gms, PID: 1563
03-31 15:37:22.076  1563  3873 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at com.google.android.gms.drive.database.c.getWritableDatabase(:com.google.android.gms:223)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.b(:com.google.android.gms:601)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.a(:com.google.android.gms:595)
03-31 15:37:22.076  1563  3873 E AndroidRuntime: 	at com.google.android.gms.drive.database.o.run(:com.google.android.gms:616)
03-31 15:37:22.080  1563  3873 I Process : Sending signal. PID: 1563 SIG: 9
03-31 15:37:22.085   763  3879 E DropBoxManagerService: Can't write: system_app_crash
03-31 15:37:22.085   763  3879 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
03-31 15:37:22.085   763  3879 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 15:37:22.085   763  3879 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 15:37:22.085   763  3879 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 15:37:22.085   763  3879 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 15:37:22.085   763  3879 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 15:37:22.085   763  3879 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 15:37:22.085   763  3879 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 15:37:22.085   763  3879 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 15:37:22.085   763  3879 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 15:37:22.085   763  3879 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 15:37:22.085   763  3879 E DropBoxManagerService: 	... 5 more
03-31 15:37:22.096   763   868 D WifiService: Client connection lost with reason: 4

```
