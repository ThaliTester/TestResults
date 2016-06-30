#### Test 7578926851a8f91_thali04_LGE-Nexus 5 Logs


```
--------- beginning of main
06-30 12:52:04.083  2514  2552 I Finsky  : [226] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,06-30 12:52:04.175  2514  2552 I Finsky  : [226] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
06-30 12:52:04.175  2514  2514 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
06-30 12:52:04.689  3195  3195 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 12:52:04.693  3195  3195 D AndroidRuntime: CheckJNI is OFF
06-30 12:52:04.728  3195  3195 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 12:52:04.764  3195  3195 I Radio-JNI: register_android_hardware_Radio DONE
06-30 12:52:04.783  3195  3195 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 12:52:04.785   787   798 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 12:52:04.821   787   798 I ActivityManager: Start proc 3212:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-30 12:52:04.825  3195  3195 D AndroidRuntime: Shutting down VM
06-30 12:52:04.891  3212  3212 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
06-30 12:52:04.920  3212  3212 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2507-2509)
06-30 12:52:04.920  3212  3212 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:52:04.934  3212  3212 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d7f9}
06-30 12:52:04.934  3212  3212 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:52:04.934  3212  3212 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 12:52:04.940  3212  3212 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 12:52:04.941  3212  3212 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 12:52:04.946  3212  3227 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
06-30 12:52:04.951  3212  3212 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-30 12:52:04.955  3212  3212 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 12:52:04.955  3212  3212 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 12:52:04.955  3212  3212 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
06-30 12:52:05.001   787   805 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@97b9f95:true
,06-30 12:52:05.118  3212  3212 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 12:52:05.129  3212  3212 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
06-30 12:52:05.172  3212  3249 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
06-30 12:52:05.192  3212  3236 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
06-30 12:52:05.218  3212  3249 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 12:52:05.242  1220  1220 I Keyboard.Facilitator: onFinishInput()
06-30 12:52:05.259   787   806 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +414ms (total +455ms)
06-30 12:52:05.333  3212  3212 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3212
06-30 12:52:05.415  3212  3212 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 12:52:05.542  3212  3252 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1644508880
06-30 12:52:05.546  3212  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:52:05.546  3212  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:52:05.546  3212  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:52:05.546  3212  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:52:05.546  3212  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 12:52:05.546  3212  3252 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a4c844 added. We now have 1 listener(s)
06-30 12:52:05.548  3212  3252 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
06-30 12:52:05.549  3212  3252 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
06-30 12:52:05.549  3212  3252 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 12:52:05.550  3212  3252 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 12:52:05.554  3212  3252 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcbaff3 added. We now have 1 listener(s)
06-30 12:52:05.554  3212  3252 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 12:52:05.557   787   892 D WifiService: New client listening to asynchronous messages
06-30 12:52:05.558  3212  3252 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:52:05.559  3212  3252 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 12:52:05.560  3212  3252 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 12:52:05.560  3212  3252 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 12:52:05.560  3212  3252 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 12:52:05.560  3212  3252 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 12:52:05.562  3212  3252 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 12:52:05.563  3212  3252 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
06-30 12:52:05.564  3212  3252 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:52:05.564  3212  3252 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:52:05.564  3212  3252 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:52:05.564  3212  3252 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 12:52:05.564  3212  3252 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 12:52:05.564  3212  3252 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 12:52:05.564  3212  3252 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:52:05.564  3212  3252 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:52:05.564  3212  3252 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 12:52:05.564  3212  3252 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 12:52:05.564  3212  3252 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 12:52:05.564  3212  3252 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 12:52:05.584  3212  3212 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
06-30 12:52:06.302  3212  3259 W jxcore-log: Initializing JXcore engine
06-30 12:52:06.302  3212  3259 W jxcore-log: JXcore engine is ready
06-30 12:52:06.334  3259  3259 W Thread-261: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[7966]" dev="sockfs" ino=7966 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 12:52:06.334  3259  3259 W Thread-261: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 12:52:06.334  3259  3259 W Thread-261: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18084]" dev="sockfs" ino=18084 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 12:52:06.358  3212  3259 W jxcore-log: Starting JXcore engine
06-30 12:52:06.448  3212  3259 W jxcore-log: Platform android
06-30 12:52:06.448  3212  3259 W jxcore-log: 
06-30 12:52:06.448  3212  3259 W jxcore-log: Process ARCH arm
06-30 12:52:06.448  3212  3259 W jxcore-log: 
06-30 12:52:06.663  3212  3259 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:52:06.663  3212  3259 I jxcore-log: 
06-30 12:52:06.663  3212  3259 W jxcore-log: JXcore engine is started
06-30 12:52:06.665  3212  3252 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 12:52:06.667   787  1322 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
06-30 12:52:06.684   787  1322 I ActivityManager: Start proc 3262:com.android.packageinstaller/u0a63 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
06-30 12:52:06.686  3212  3252 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
06-30 12:52:06.723  3262  3262 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
06-30 12:52:06.808  3262  3274 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 12:52:06.850  3262  3274 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,06-30 12:52:06.851  3262  3274 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 12:52:06.872  1220  1220 I Keyboard.Facilitator: onFinishInput()
,06-30 12:52:06.910   787   806 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +200ms (total +238ms)
,06-30 12:52:33.997  1733  1876 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 12:52:35.025   787  1081 D ConnectivityService: listenForNetwork for Listen from uid/pid:10008/1613 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 12:52:35.065  1613  3302 W DriveInitializer: Background init thread started
,06-30 12:52:35.128  1613  3302 W DriveInitializer: Background init thread ended
,06-30 12:53:05.303  1733  1733 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=58211201-15e4-4f12-8e22-d05dbc16a0b0
06-30 12:53:05.307  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 12:53:05.307  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:53:05.412  1733  1797 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 12:53:05.414  1613  3319 D UdcContextInitService: registered all accounts: true
,06-30 12:53:05.418  1733  1781 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 12:53:05.475  1733  1781 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10008, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
06-30 12:53:05.475  1733  1733 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 12:53:05.559  1733  3331 I VacuumService: Vacuum at: now=1467283985559 tag=VacuumService
,06-30 12:53:06.912  1220  1346 I Keyboard.Facilitator.LanguageModelFlusher: run()
,06-30 12:53:06.913  1220  1346 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-30 12:54:05.660  1733  1781 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 12:54:05.661  1733  1781 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 12:54:05.661  1733  1781 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-30 12:54:05.662  1733  1781 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 12:54:05.686  1733  1781 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 12:54:05.686  1733  1781 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 12:55:33.815  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:33.835  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:33.836  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:33.915  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:33.936  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:33.937  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:34.018  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:34.038  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:34.038  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:18.173   787   800 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 13:10:34.140  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:34.156  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:34.156  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:15:34.236  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:15:34.256  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:15:34.256  1733  1733 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,TIME-OUT KILL (timeout was 1400000ms)
```
