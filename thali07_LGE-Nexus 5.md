#### Test 648991491c812df_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
04-01 09:11:01.811   740   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,04-01 09:11:02.119  3284  3284 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-01 09:11:02.122  3284  3284 D AndroidRuntime: CheckJNI is OFF
04-01 09:11:02.226  3284  3284 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
04-01 09:11:02.230   740  3202 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-01 09:11:02.235   740  3202 V WindowManager: addAppToken: AppWindowToken{2ac8ee86 token=Token{388c361 ActivityRecord{bdfc6c8 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
04-01 09:11:02.240  3284  3284 D AndroidRuntime: Shutting down VM
04-01 09:11:02.242  1403  1420 W SearchService: Abort, client detached.
04-01 09:11:02.246   740   834 V WindowManager: Adding window Window{3dad7d99 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2acb84f9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-01 09:11:02.286   740   755 I ActivityManager: Start proc 3305:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
04-01 09:11:02.299  1403  1580 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
04-01 09:11:02.314  1403  1588 I DeviceStateChecker: DeviceStateChecker cancelled
04-01 09:11:02.316  1403  1403 I MicroDetector: Keeping mic open: false
04-01 09:11:02.317  1403  1403 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@1f93d51f
04-01 09:11:02.371   189  1594 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-01 09:11:02.371   189  1594 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-01 09:11:02.378  1403  1589 I MicroRecognitionRunner: Detection finished
04-01 09:11:02.379  1403  1587 I MicroRecognitionRunner: Stopping hotword detection.
04-01 09:11:02.409  3305  3305 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
04-01 09:11:02.423  3305  3305 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 9493-9495)
04-01 09:11:02.423  3305  3305 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-01 09:11:02.432  3305  3305 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {163184e7}
04-01 09:11:02.433  3305  3305 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-01 09:11:02.433  3305  3305 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
04-01 09:11:02.435   740  1186 I ActivityManager: Killing 1906:com.android.defcontainer/u0a4 (adj 15): empty #17
,04-01 09:11:02.459  3305  3305 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
04-01 09:11:02.474  3305  3305 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
04-01 09:11:02.521   740   833 D BluetoothManagerService: Message: 20
04-01 09:11:02.521   740   833 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11951b2f:true
04-01 09:11:02.531  3305  3305 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
04-01 09:11:02.531  3305  3305 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
04-01 09:11:02.583  3305  3305 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-01 09:11:02.583  3305  3305 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-01 09:11:02.595  3305  3305 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
04-01 09:11:02.601  3305  3305 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
04-01 09:11:02.601  3305  3305 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
04-01 09:11:02.610  3305  3305 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
04-01 09:11:02.631  3305  3356 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
04-01 09:11:02.635  3305  3305 D Atlas   : Validating map...
04-01 09:11:02.639   740   755 V WindowManager: Adding window Window{3e8387ca u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3dad7d99 u0 Starting com.test.thalitest})
04-01 09:11:02.646   740   860 D WifiService: New client listening to asynchronous messages
04-01 09:11:02.655   740  1246 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-01 09:11:02.655   740   861 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-01 09:11:02.655   740   861 D ConnectivityService: apparently satisfied.  currentScore=60
04-01 09:11:02.657  3305  3358 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
04-01 09:11:02.805   177   177 D SurfaceFlinger: shader cache generated - 24 shaders in 132.635681 ms
04-01 09:11:02.827  3305  3356 I OpenGLRenderer: Initialized EGL, version 1.4
04-01 09:11:02.830  3305  3356 D OpenGLRenderer: Enabling debug mode 0
04-01 09:11:02.904  1097  1097 I Keyboard.Facilitator: onFinishInput()
04-01 09:11:02.908   740   834 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +666ms
04-01 09:11:02.924  3305  3366 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
04-01 09:11:02.953  3305  3305 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3305
04-01 09:11:03.091  3305  3305 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
04-01 09:11:03.201  3305  3379 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362699136
04-01 09:11:03.204  3305  3379 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-01 09:11:03.204  3305  3379 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-01 09:11:03.204  3305  3379 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-01 09:11:03.204  3305  3379 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-01 09:11:03.204  3305  3379 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-01 09:11:03.204  3305  3379 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98cabb7 added. We now have 1 listener(s)
04-01 09:11:03.206   740   927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
04-01 09:11:03.209  3305  3379 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
04-01 09:11:03.210  3305  3379 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
04-01 09:11:03.211  3305  3379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
04-01 09:11:03.211  3305  3379 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-01 09:11:03.215  3305  3379 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@deef442 added. We now have 1 listener(s)
04-01 09:11:03.215  3305  3379 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
04-01 09:11:03.223  3305  3379 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
04-01 09:11:03.228  3305  3379 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
04-01 09:11:03.229  3305  3379 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
04-01 09:11:03.233  3305  3379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
04-01 09:11:03.234   740  1186 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
04-01 09:11:03.234  3305  3379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
04-01 09:11:03.242  3305  3379 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 09:11:03.242  3305  3379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 09:11:03.242  3305  3379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-01 09:11:03.242  3305  3379 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 09:11:03.242  3305  3379 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 09:11:03.242  3305  3379 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 09:11:03.242  3305  3379 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 09:11:03.242  3305  3379 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-01 09:11:03.242  3305  3379 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-01 09:11:03.242  3305  3379 D io.jxcore.node.ConnectivityMonitor: start: OK
04-01 09:11:03.243  3305  3379 I io.jxcore.node.LifeCycleMonitor: start: OK
04-01 09:11:03.247  3305  3305 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
04-01 09:11:03.249  3305  3305 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 09:11:03.286  3305  3305 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-01 09:11:03.368  1642  1696 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-01 09:11:03.369  1642  1642 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-01 09:11:03.876  3305  3382 W jxcore-log: Initializing JXcore engine
04-01 09:11:03.876  3305  3382 W jxcore-log: JXcore engine is ready
,04-01 09:11:03.914  3382  3382 W Thread-327: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[7854]" dev="sockfs" ino=7854 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,04-01 09:11:03.914  3382  3382 W Thread-327: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
04-01 09:11:03.914  3382  3382 W Thread-327: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[7909]" dev="sockfs" ino=7909 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-01 09:11:03.914  3382  3382 W Thread-327: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[17626]" dev="sockfs" ino=17626 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,04-01 09:11:03.933  3305  3382 W jxcore-log: Starting JXcore engine
,04-01 09:11:04.016  3305  3382 W jxcore-log: Platform android
04-01 09:11:04.016  3305  3382 W jxcore-log: 
04-01 09:11:04.016  3305  3382 W jxcore-log: Process ARCH arm
04-01 09:11:04.016  3305  3382 W jxcore-log: 
,04-01 09:11:04.217  3305  3382 I jxcore-log: JXcore Cordova bridge is ready!
04-01 09:11:04.217  3305  3382 I jxcore-log: 
,04-01 09:11:04.217  3305  3382 W jxcore-log: JXcore engine is started
,04-01 09:11:04.221  3305  3379 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-01 09:11:04.222  3305  3305 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-01 09:11:07.488  1558  1570 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,04-01 09:11:09.526   740   927 I ActivityManager: Killing 2063:com.android.providers.calendar/u0a1 (adj 15): empty #17
,04-01 09:11:09.648   740   927 I ActivityManager: Killing 2310:com.google.android.calendar/u0a28 (adj 15): empty #18
,04-01 09:11:10.638  1642  1642 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,04-01 09:11:10.655  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:11:10.664  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:11:10.666  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:11:11.274  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:11:11.525  1642  1684 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
04-01 09:11:11.525  1642  1684 I qtaguid : Untagging socket 38 failed errno=-22
04-01 09:11:11.525  1642  1684 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,04-01 09:11:11.529  1642  1642 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,04-01 09:11:11.575  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:11:11.623   740  3202 I ActivityManager: Start proc 3415:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,04-01 09:11:11.662  3415  3415 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-01 09:11:11.663  3415  3415 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-01 09:11:11.692  3415  3415 I MultiDex: VM with version 2.1.0 has multidex support
04-01 09:11:11.692  3415  3415 I MultiDex: install
04-01 09:11:11.692  3415  3415 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-01 09:11:11.707  3415  3415 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,04-01 09:11:11.741  3415  3415 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-01 09:11:11.754  3415  3415 D ChimeraCfgMgr: Reading stored module config
,04-01 09:11:11.756  1513  1513 D WearableService: callingUid 10007, callindPid: 1513
,04-01 09:11:11.762  1513  1888 E MDM     : [166] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
04-01 09:11:11.764  1513  1513 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-01 09:11:11.765  1558  3450 D LocationInitializer: Restart initialization of location
,04-01 09:11:11.777  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:11:11.791  1513  1618 W GCoreFlp: No location to return for getLastLocation()
,04-01 09:11:11.791  1513  3451 W FusedLocationProvider: location=null
,04-01 09:11:11.868  3415  3448 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,04-01 09:11:11.870  3415  3415 D CAR.SERVICE: Connecting to CarCallService...
,04-01 09:11:11.881  3415  3415 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-01 09:11:11.881  3415  3415 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-01 09:11:11.888  3415  3415 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,04-01 09:11:11.894  3415  3415 D CAR.TEL.Service: Creating a new CarCallService.
,04-01 09:11:11.896  3415  3415 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,04-01 09:11:11.898   740  1186 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,04-01 09:11:11.898  3415  3415 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@b188954
04-01 09:11:11.898   740  1185 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,04-01 09:11:11.899  3415  3415 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
04-01 09:11:11.899  3415  3415 D CAR.TEL.Service: Starting CarCallService with initial phone null
,04-01 09:11:11.936  1642  1683 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
,04-01 09:11:11.936  1642  1683 I qtaguid : Untagging socket 38 failed errno=-22
04-01 09:11:11.936  1642  1683 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,04-01 09:11:11.953  3415  3430 D CAR.SERVICE: Package validated; name: com.android.vending
,04-01 09:11:12.517  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:11:12.569   740   740 I art     : Explicit concurrent mark sweep GC freed 31414(1508KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.282ms total 51.685ms
,04-01 09:11:13.043  1642  1684 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
04-01 09:11:13.043  1642  1684 I qtaguid : Untagging socket 38 failed errno=-22
04-01 09:11:13.043  1642  1684 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,04-01 09:11:13.124  1642  1642 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,04-01 09:11:13.151  1513  1530 D DeviceConnectionService: client connected with version: 8298000
,04-01 09:11:13.179  1642  1642 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
04-01 09:11:13.179  1642  1642 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,04-01 09:11:13.383  3305  3382 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-01 09:11:13.383  3305  3382 I jxcore-log: 
04-01 09:11:13.385  3305  3382 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-01 09:11:13.385  3305  3382 I jxcore-log: 
,04-01 09:11:13.387  3305  3382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 09:11:13.387  3305  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 09:11:13.387  3305  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-01 09:11:13.387  3305  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 09:11:13.387  3305  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 09:11:13.387  3305  3382 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 09:11:13.387  3305  3382 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 09:11:13.387  3305  3382 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-01 09:11:13.390  3305  3382 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
04-01 09:11:13.391  3305  3382 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-01 09:11:13.391  3305  3382 I jxcore-log: 
04-01 09:11:13.393  3305  3382 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-01 09:11:13.393  3305  3382 I jxcore-log: 
,04-01 09:11:13.892  3305  3382 I jxcore-log: Unit Test app is loaded
04-01 09:11:13.892  3305  3382 I jxcore-log: 
04-01 09:11:13.895  3305  3382 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-01 09:11:13.895  3305  3382 I jxcore-log: 
,04-01 09:11:13.899  3305  3305 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-01 09:11:13.899  3305  3382 I jxcore-log: My device name is: LGE-Nexus 5
04-01 09:11:13.899  3305  3382 I jxcore-log: 
,04-01 09:11:14.552   740   829 I ActivityManager: Start proc 3490:com.android.providers.calendar/u0a1 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,04-01 09:11:14.583  3490  3490 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,04-01 09:11:14.604  3490  3490 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@3ff022a6(com.android.providers.calendar.CalendarProvider2@163184e7)
,04-01 09:11:14.616  3490  3508 E SQLiteLog: (284) automatic index on view_events(_id)
,04-01 09:11:14.636  1642  3509 I Finsky  : [145] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-01 09:11:14.643  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:11:15.660  3490  3490 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
04-01 09:11:15.660  3490  3490 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,04-01 09:11:15.680   740   829 I ActivityManager: Start proc 3530:com.google.android.calendar/u0a28 for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,04-01 09:11:15.727  3530  3530 E SQLiteLog: (283) recovered 44 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,04-01 09:11:15.821  3530  3530 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,04-01 09:11:16.799   740   755 I ActivityManager: Killing 3023:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,04-01 09:11:17.009  3415  3415 D CAR.SERVICE: mConnectedToCar = false, abort
,04-01 09:11:17.012   740   756 I ActivityManager: Killing 3043:com.android.musicfx/u0a13 (adj 15): empty #17
,04-01 09:11:17.023  3415  3415 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@13451ebc that was originally bound here
04-01 09:11:17.023  3415  3415 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@13451ebc that was originally bound here
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-01 09:11:17.023  3415  3415 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-01 09:11:17.140  3415  3415 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@38e9f0a7 that was originally bound here
04-01 09:11:17.140  3415  3415 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@38e9f0a7 that was originally bound here
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-01 09:11:17.140  3415  3415 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-01 09:11:17.142   740  1190 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@1b7e433e
,04-01 09:11:17.724  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-01 09:11:17.724  3305  3382 I jxcore-log: 
,04-01 09:11:18.074  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-01 09:11:18.074  3305  3382 I jxcore-log: 
,04-01 09:11:18.084  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-01 09:11:18.084  3305  3382 I jxcore-log: 
,04-01 09:11:18.088  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-01 09:11:18.088  3305  3382 I jxcore-log: 
,04-01 09:11:18.103  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-01 09:11:18.103  3305  3382 I jxcore-log: 
04-01 09:11:18.106  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-01 09:11:18.106  3305  3382 I jxcore-log: 
,04-01 09:11:20.045  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-01 09:11:20.045  3305  3382 I jxcore-log: 
,04-01 09:11:20.066  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-01 09:11:20.066  3305  3382 I jxcore-log: 
,04-01 09:11:20.073  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-01 09:11:20.073  3305  3382 I jxcore-log: 
,04-01 09:11:20.319  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-01 09:11:20.319  3305  3382 I jxcore-log: 
,04-01 09:11:20.390  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-01 09:11:20.390  3305  3382 I jxcore-log: 
,04-01 09:11:20.443  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-01 09:11:20.443  3305  3382 I jxcore-log: 
,04-01 09:11:20.449  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-01 09:11:20.449  3305  3382 I jxcore-log: 
,04-01 09:11:20.458  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-01 09:11:20.458  3305  3382 I jxcore-log: 
04-01 09:11:20.462  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-01 09:11:20.462  3305  3382 I jxcore-log: 
04-01 09:11:20.466  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-01 09:11:20.466  3305  3382 I jxcore-log: 
,04-01 09:11:20.481  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-01 09:11:20.481  3305  3382 I jxcore-log: 
,04-01 09:11:20.500  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-01 09:11:20.500  3305  3382 I jxcore-log: 
,04-01 09:11:20.583  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-01 09:11:20.583  3305  3382 I jxcore-log: 
,04-01 09:11:20.587  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-01 09:11:20.587  3305  3382 I jxcore-log: 
,04-01 09:11:20.611  3305  3382 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-01 09:11:20.611  3305  3382 I jxcore-log: 
,04-01 09:11:20.617  3305  3382 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,04-01 09:11:20.619  3305  3382 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
04-01 09:11:20.619  3305  3382 I jxcore-log: 
,04-01 09:11:20.823  3530  3556 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,04-01 09:11:20.900   740  3202 I ActivityManager: Killing 3080:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,04-01 09:11:21.815   740   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
04-01 09:11:21.816   740   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 09:11:28.504  1642  1696 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-01 09:11:28.505  1642  1642 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-01 09:11:41.819   740   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,04-01 09:12:01.823   740   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
04-01 09:12:01.823   740   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 09:12:02.088   740  1149 D AlarmManagerService: Setting time of day to sec=1459494722
04-01 09:12:02.394   740  1149 W AlarmManagerService: Unable to set rtc to 1459494722: Invalid argument
,04-01 09:12:02.427   740   829 I ActivityManager: Start proc 3596:com.qualcomm.timeservice/u0a68 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,04-01 09:12:02.471  3596  3596 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459494722471
04-01 09:12:02.471  3596  3596 D         : TimeServiceNative: User Time to be set is 1459494722471
,04-01 09:12:02.471  3596  3596 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
04-01 09:12:02.471  3596  3596 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
04-01 09:12:02.471  3596  3596 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459494722471
04-01 09:12:02.471   203   605 D QC-time-services: Daemon: Connection accepted:time_genoff
04-01 09:12:02.471  3596  3596 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
04-01 09:12:02.471   203  3613 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459494722471
04-01 09:12:02.471   203  3613 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459494722471, operation = 0
04-01 09:12:02.472   203  3613 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/23/71 1:16:32
04-01 09:12:02.472   203  3613 D QC-time-services: Daemon:Value read from RTC seconds = 43809392000
04-01 09:12:02.472   203  3613 D QC-time-services: Daemon:new time 1459494722471 
,04-01 09:12:02.472   203  3613 D QC-time-services: Daemon: delta 1415685330471 genoff 1415685330471 
04-01 09:12:02.472   203  3613 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1415685330471 to memory
04-01 09:12:02.472   203  3613 D QC-time-services: Daemon:Opening File: /data/system/time/ats_2
04-01 09:12:02.472   203  3613 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,04-01 09:12:02.479   203  3613 D QC-time-services: Updating the TOD offset
04-01 09:12:02.479   203  3613 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1415685330471 to memory
04-01 09:12:02.479   203  3613 D QC-time-services: Daemon:Opening File: /data/system/time/ats_1
04-01 09:12:02.479   203  3613 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,04-01 09:12:02.483   203  3613 D QC-time-services: Daemon:Update to modem bit set
04-01 09:12:02.483  3596  3596 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
04-01 09:12:02.483   203  3613 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
04-01 09:12:02.483   203  3613 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143529922471
,04-01 09:12:02.488   203   603 D QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,04-01 09:12:02.489   203   605 D QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,04-01 09:12:02.509  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:12:02.516  1513  3615 I VacuumService: Vacuum at: now=1459494722516 tag=VacuumService
,04-01 09:12:02.734   740  1106 I ActivityManager: Start proc 3617:com.google.android.deskclock/u0a33 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,04-01 09:12:02.741   740  3258 I ActivityManager: Killing 3120:com.google.android.keep/u0a52 (adj 15): empty #17
,04-01 09:12:02.832  3617  3617 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
04-01 09:12:02.832  3617  3617 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
04-01 09:12:02.832  3617  3617 I GAv4    :   adb logcat -s GAv4
,04-01 09:12:02.853  3617  3617 I AlarmClock: AlarmInitReceiver android.intent.action.TIME_SET
,04-01 09:12:02.898   740  1246 I ActivityManager: Start proc 3641:com.google.android.keep/u0a52 for broadcast com.google.android.keep/.notification.AlertReceiver
,04-01 09:12:02.899   740  1246 I ActivityManager: Killing 3175:com.quickoffice.android/u0a65 (adj 15): empty #17
,04-01 09:12:02.914   200   200 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 272us total 16.017ms
,04-01 09:12:02.928   200   200 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 359us total 11.957ms
,04-01 09:12:02.938   200   200 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 196us total 9.325ms
,04-01 09:12:03.101  3641  3671 E SQLiteLog: (284) automatic index on blob_node(tree_entity_id)
,04-01 09:12:03.108  3641  3671 E SQLiteLog: (284) automatic index on blob_node(tree_entity_id)
,04-01 09:12:03.233  1097  1261 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-01 09:12:03.233  1097  1261 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-01 09:12:03.242  1513  1513 I ConfigService: onCreate
,04-01 09:12:03.409  1941  2028 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 09:12:03.677   740  1242 I ActivityManager: Killing 2531:com.google.android.gm/u0a41 (adj 15): empty #17
,04-01 09:12:08.146   740  3258 I art     : Explicit concurrent mark sweep GC freed 37405(1786KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.561ms total 94.750ms
,04-01 09:12:08.149  3641  3667 I GAV3    : Thread[GAThread,5,main]: No campaign data found.
,04-01 09:12:08.297  1513  1513 I ConfigService: onDestroy
,04-01 09:12:22.135   740   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
04-01 09:12:22.135   740   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 09:12:37.044   740   836 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
04-01 09:12:37.049   740   836 I PowerManagerService: Sleeping (uid 1000)...
,04-01 09:12:37.097   740   836 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-01 09:12:37.110   189   189 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-01 09:12:37.121   177   843 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (113 us)
,04-01 09:12:37.134   740   859 E WifiStateMachine: cancelDelayedScan -> 11
,04-01 09:12:37.138   740   859 E native  : do suspend false
,04-01 09:12:37.328   189  1130 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,04-01 09:12:37.330  1097  1097 I Keyboard.Facilitator: onFinishInput()
,04-01 09:12:37.338   740   859 E WifiStateMachine: cancelDelayedScan -> 13
,04-01 09:12:37.339   740   859 E native  : do suspend true
,04-01 09:12:37.639   740   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
04-01 09:12:37.639   740   859 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,04-01 09:12:37.725   740   834 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,04-01 09:12:37.729   740   740 V ActivityManager: Display changed displayId=0
,04-01 09:12:37.759   177   177 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
04-01 09:12:37.759   177   177 D qdhwcomposer: hwc_blank: Blanking display: 0
,04-01 09:12:37.860   178   178 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
04-01 09:12:37.860   178   178 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
04-01 09:12:37.860   178   178 I rmt_storage: wakelock acquired: 1, error no: 2
,04-01 09:12:37.860   178   577 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236802816)
,04-01 09:12:37.932   178   577 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
04-01 09:12:37.932   178   577 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
04-01 09:12:37.932   178   577 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236802816) wakelock released: 1, error no: 0
04-01 09:12:37.932   178   577 I rmt_storage: 
,04-01 09:12:37.934   178   178 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,04-01 09:12:38.024   177   177 D qdhwcomposer: hwc_blank: Done blanking display: 0
04-01 09:12:38.024   740   883 D SurfaceControl: Excessive delay in setPowerMode(): 266ms
04-01 09:12:38.025  1924  1926 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,04-01 09:12:38.040  3305  3305 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
04-01 09:12:38.040  3305  3305 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,04-01 09:12:38.066  3305  3305 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@14c1425c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@28b864e, 16908290=android.view.AbsSavedState$1@28b864e}, android:focusedViewId=100}]}]
04-01 09:12:38.066  3305  3305 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
04-01 09:12:38.066  3305  3305 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
04-01 09:12:38.066  3305  3305 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,04-01 09:12:42.139   740   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
04-01 09:12:42.140   740   859 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,04-01 09:12:43.034  1513  1851 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,04-01 09:12:47.869  1513  3723 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 8417 seconds from now (1459494767869)
,04-01 09:12:47.943  1513  3720 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,04-01 09:12:47.948  1513  3720 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-01 09:12:48.701  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:12:48.702  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 09:12:48.859  1513  1524 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32daa23b)
,04-01 09:12:48.859  1513  1524 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@39273d58)
04-01 09:12:48.860  1513  1524 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@14761eb1)
,04-01 09:12:48.860  1513  1524 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@218b2f96)
04-01 09:12:48.860  1513  1524 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@14c72717)
,04-01 09:13:29.222  3305  3382 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-01 09:13:29.222  3305  3382 I jxcore-log: 
,04-01 09:13:29.625  3744  3744 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-01 09:13:29.629  3744  3744 D AndroidRuntime: CheckJNI is OFF
,04-01 09:13:29.726  3744  3744 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-01 09:13:29.731   740   829 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
04-01 09:13:29.731   740   829 I ActivityManager: Killing 3305:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,04-01 09:13:29.771   740   840 W PackageSettings: Skipping PackageSetting{180052ec com.example.hello/10116} due to missing metadata
,04-01 09:13:29.783   740   860 D WifiService: Client connection lost with reason: 4
,04-01 09:13:29.785   740  3202 I WindowState: WIN DEATH: Window{3e8387ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
04-01 09:13:29.785   740   756 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3251f214)
04-01 09:13:29.785   740   861 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-01 09:13:29.785   740   861 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-01 09:13:29.843   740   829 I ActivityManager:   Force finishing activity 3 ActivityRecord{bdfc6c8 u0 com.test.thalitest/.MainActivity t19}
,04-01 09:13:29.849   740  1106 W ActivityManager: Spurious death for ProcessRecord{341e5abd 3305:com.test.thalitest/u0a49}, curProc for 3305: null
,04-01 09:13:29.850   740   840 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,04-01 09:13:29.889  1239  1239 I art     : Explicit concurrent mark sweep GC freed 1695(106KB) AllocSpace objects, 5(450KB) LOS objects, 38% free, 25MB/41MB, paused 745us total 20.984ms
,04-01 09:13:29.914   907   907 I art     : Explicit concurrent mark sweep GC freed 9547(420KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 793us total 22.933ms
,04-01 09:13:29.920  1558  1558 I art     : Explicit concurrent mark sweep GC freed 3804(316KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 23MB/30MB, paused 539us total 61.490ms
,04-01 09:13:29.922  1403  1403 I art     : Explicit concurrent mark sweep GC freed 2981(236KB) AllocSpace objects, 7(154KB) LOS objects, 25% free, 22MB/30MB, paused 615us total 57.490ms
,04-01 09:13:29.930  1513  1630 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,04-01 09:13:29.931   740   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-01 09:13:29.931  1097  1097 I Keyboard.Facilitator: resetDictionaries() : en_US
04-01 09:13:29.932  1097  3769 I Keyboard.Facilitator.DecoderInitializer: run()
,04-01 09:13:29.935   740   885 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
04-01 09:13:29.935   740   885 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,04-01 09:13:29.946  1097  3769 I Decoder : createOrResetDecoder
,04-01 09:13:29.975  2981  3777 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,04-01 09:13:29.990   740   740 I art     : Explicit concurrent mark sweep GC freed 32978(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 29MB/44MB, paused 1.796ms total 86.620ms
,04-01 09:13:29.992   740   840 I art     : WaitForGcToComplete blocked for 51.796ms for cause Explicit
,04-01 09:13:30.004   740   927 I ActivityManager: Start proc 3778:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,04-01 09:13:30.007  1513  1513 I ConfigService: onCreate
,04-01 09:13:30.046  1097  3769 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,04-01 09:13:30.067  1097  3769 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,04-01 09:13:30.069  1097  3769 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
04-01 09:13:30.069  1097  3769 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,04-01 09:13:30.070   740   740 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-01 09:13:30.070   740   740 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
04-01 09:13:30.070  1097  3769 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
04-01 09:13:30.070  1097  3769 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
04-01 09:13:30.071  1097  3769 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
04-01 09:13:30.071  1097  3769 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,04-01 09:13:30.072  1097  3769 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-01 09:13:30.072  1097  3769 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-01 09:13:30.072  1097  3769 I Keyboard.Facilitator.Delight2FileSweeper: run()
04-01 09:13:30.073  1097  3769 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-01 09:13:30.073  1097  3769 I StatsUtilsManager: startPeriodStatsRecorder() : Success
04-01 09:13:30.073  1097  3769 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
04-01 09:13:30.078   740  1106 I ActivityManager: Start proc 3802:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
04-01 09:13:30.084   740  1246 I ActivityManager: Killing 2882:com.google.android.apps.photos/u0a83 (adj 15): empty #17
04-01 09:13:30.085   740   840 I art     : Explicit concurrent mark sweep GC freed 7355(639KB) AllocSpace objects, 2(1312KB) LOS objects, 33% free, 28MB/42MB, paused 2.023ms total 89.231ms
04-01 09:13:30.106   740   756 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3305 uid 10049
04-01 09:13:30.106  1097  1097 I Keyboard.Facilitator: onFinishInput()
,04-01 09:13:30.126  1239  1239 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-01 09:13:30.154  3744  3744 I art     : System.exit called, status: 0
04-01 09:13:30.154  3744  3744 I AndroidRuntime: VM exiting with result code 0.
,04-01 09:13:30.183  3802  3802 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-01 09:13:30.206   740   840 I ActivityManager: Start proc 3821:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,04-01 09:13:30.233  1558  3843 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-01 09:13:30.233  1558  3843 D AccountUtils: Clearing selected account for com.test.thalitest
,04-01 09:13:30.236   740   756 I ActivityManager: Killing 2772:com.google.android.setupwizard/u0a16 (adj 15): empty #17
,04-01 09:13:30.256  1513  1513 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-01 09:13:30.256  1513  1513 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-01 09:13:30.275   740  1186 I ActivityManager: Start proc 3847:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,04-01 09:13:30.280  1558  3843 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,04-01 09:13:30.303  1239  1439 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-01 09:13:30.321  1558  3861 W BaseAppContext: Using Auth Proxy for data requests.
,04-01 09:13:30.327  1558  3861 W BaseAppContext: Using Auth Proxy for data requests.
,04-01 09:13:30.341  1558  3861 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-01 09:13:30.341  1558  3861 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: Runtime exception while performing operation
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-01 09:13:30.341  1558  3861 E ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-01 09:13:30.341  1558  3861 F ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
04-01 09:13:30.347  1558  3843 I GMPM-SVC: App measurement is starting up, version: 8703
04-01 09:13:30.347  1558  3843 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
04-01 09:13:30.351   740  3868 E DropBoxManagerService: Can't write: system_app_wtf
04-01 09:13:30.351   740  3868 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
04-01 09:13:30.351   740  3868 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-01 09:13:30.351   740  3868 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-01 09:13:30.351   740  3868 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-01 09:13:30.351   740  3868 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-01 09:13:30.351   740  3868 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-01 09:13:30.351   740  3868 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-01 09:13:30.351   740  3868 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-01 09:13:30.351   740  3868 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-01 09:13:30.351   740  3868 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-01 09:13:30.351   740  3868 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-01 09:13:30.351   740  3868 E DropBoxManagerService: 	... 5 more
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(:com.google.android.gms:223)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.b(:com.google.android.gms:601)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(:com.google.android.gms:595)
04-01 09:13:30.371  1558  3870 E SQLiteDatabase: 	at com.google.android.gms.drive.database.o.run(:com.google.android.gms:616)
04-01 09:13:30.375  1558  3871 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,04-01 09:13:30.377  1558  1617 I Icing   : doRemovePackageData com.test.thalitest
04-01 09:13:30.388  1558  3870 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
04-01 09:13:30.388  1558  3870 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
04-01 09:13:30.388  1558  3870 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
04-01 09:13:30.388  1558  3870 I GCore-Chimera-Crash: ==
04-01 09:13:30.388  1558  3870 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
04-01 09:13:30.389  1558  3870 E AndroidRuntime: FATAL EXCEPTION: Open database in background
04-01 09:13:30.389  1558  3870 E AndroidRuntime: Process: com.google.android.gms, PID: 1558
04-01 09:13:30.389  1558  3870 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at com.google.android.gms.drive.database.c.getWritableDatabase(:com.google.android.gms:223)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.b(:com.google.android.gms:601)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.a(:com.google.android.gms:595)
04-01 09:13:30.389  1558  3870 E AndroidRuntime: 	at com.google.android.gms.drive.database.o.run(:com.google.android.gms:616)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2307)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:418)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.a(:com.google.android.gms:357)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.s(:com.google.android.gms:1591)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.p(:com.google.android.gms:1605)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.c(:com.google.android.gms:306)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ar.run(:com.google.android.gms:195)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 09:13:30.390  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ap.run(:com.google.android.gms:294)
04-01 09:13:30.391  1558  3869 E GMPM-SVC: Opening the database failed, dropping and recreating it
04-01 09:13:30.391  1558  3843 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-01 09:13:30.393   740  3875 E DropBoxManagerService: Can't write: system_app_crash
04-01 09:13:30.393   740  3875 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
04-01 09:13:30.393   740  3875 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-01 09:13:30.393   740  3875 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-01 09:13:30.393   740  3875 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-01 09:13:30.393   740  3875 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-01 09:13:30.393   740  3875 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-01 09:13:30.393   740  3875 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-01 09:13:30.393   740  3875 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-01 09:13:30.393   740  3875 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-01 09:13:30.393   740  3875 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-01 09:13:30.393   740  3875 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-01 09:13:30.393   740  3875 E DropBoxManagerService: 	... 5 more
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:418)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.a(:com.google.android.gms:357)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.s(:com.google.android.gms:1591)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.p(:com.google.android.gms:1605)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.c(:com.google.android.gms:306)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ar.run(:com.google.android.gms:195)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
04-01 09:13:30.394  1558  3869 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ap.run(:com.google.android.gms:294)
04-01 09:13:30.394  1558  3869 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
04-01 09:13:30.394  1558  3869 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
04-01 09:13:30.394  1558  3869 E GMPM-SVC: Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
04-01 09:13:30.395   740   829 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{26d7e6a0 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{2def36d2 1558 com.google.android.gms/10007/u0 remote:ced0d5d}: process crashing
04-01 09:13:30.395  1558  3870 I Process : Sending signal. PID: 1558 SIG: 9

```
