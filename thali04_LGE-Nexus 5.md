#### Test 757892682551a10_thali04_LGE-Nexus 5 Logs


```
--------- beginning of main
06-30 13:52:29.620  1235  1350 I Keyboard.Facilitator.LanguageModelFlusher: run()
06-30 13:52:29.620  1235  1350 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-30 13:52:30.985  3191  3191 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 13:52:30.989  3191  3191 D AndroidRuntime: CheckJNI is OFF
06-30 13:52:31.024  3191  3191 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 13:52:31.061  3191  3191 I Radio-JNI: register_android_hardware_Radio DONE
06-30 13:52:31.080  3191  3191 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 13:52:31.082   790   959 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 13:52:31.109   790   959 I ActivityManager: Start proc 3207:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-30 13:52:31.112  3191  3191 D AndroidRuntime: Shutting down VM
06-30 13:52:31.202  3207  3207 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
06-30 13:52:31.246  3207  3207 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8894-8896)
06-30 13:52:31.246  3207  3207 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:31.263  3207  3207 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b0db30f}
06-30 13:52:31.263  3207  3207 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:31.263  3207  3207 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:52:31.269  3207  3207 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 13:52:31.270  3207  3207 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 13:52:31.276  3207  3222 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
06-30 13:52:31.279  3207  3207 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-30 13:52:31.283  3207  3207 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:31.283  3207  3207 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:31.284  3207  3207 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
06-30 13:52:31.331   790   810 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a6c1cb8:true
,06-30 13:52:31.394  3207  3207 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 13:52:31.405  3207  3207 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,06-30 13:52:31.455  3207  3244 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 13:52:31.475  3207  3231 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-30 13:52:31.509  3207  3244 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 13:52:31.538  1235  1235 I Keyboard.Facilitator: onFinishInput()
,06-30 13:52:31.552   790   811 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +405ms (total +455ms)
,06-30 13:52:31.636  3207  3207 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3207
,06-30 13:52:31.717  3207  3207 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 13:52:31.825  3207  3247 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1671431888
,06-30 13:52:31.830  3207  3247 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:52:31.830  3207  3247 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:52:31.830  3207  3247 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:52:31.830  3207  3247 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:52:31.830  3207  3247 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,06-30 13:52:31.830  3207  3247 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3705892 added. We now have 1 listener(s)
,06-30 13:52:31.833  3207  3247 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
06-30 13:52:31.835  3207  3247 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
06-30 13:52:31.836  3207  3247 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:52:31.836  3207  3247 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 13:52:31.839  3207  3247 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c7ff19 added. We now have 1 listener(s)
06-30 13:52:31.839  3207  3247 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:52:31.842   790   895 D WifiService: New client listening to asynchronous messages
,06-30 13:52:31.842  3207  3247 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 13:52:31.842  3207  3247 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 13:52:31.844  3207  3247 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 13:52:31.844  3207  3247 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,06-30 13:52:31.844  3207  3247 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 13:52:31.844  3207  3247 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 13:52:31.846  3207  3247 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 13:52:31.846  3207  3247 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
,06-30 13:52:31.847  3207  3247 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 13:52:31.847  3207  3247 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:52:31.847  3207  3247 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:52:31.847  3207  3247 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 13:52:31.847  3207  3247 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:52:31.847  3207  3247 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:52:31.847  3207  3247 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:52:31.847  3207  3247 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:52:31.847  3207  3247 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 13:52:31.847  3207  3247 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 13:52:31.847  3207  3247 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:52:31.848  3207  3247 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 13:52:31.885  3207  3207 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 13:52:32.547  3207  3254 W jxcore-log: Initializing JXcore engine
,06-30 13:52:32.547  3207  3254 W jxcore-log: JXcore engine is ready
,06-30 13:52:32.574  3254  3254 W Thread-261: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9623]" dev="sockfs" ino=9623 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,06-30 13:52:32.574  3254  3254 W Thread-261: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 13:52:32.584  3254  3254 W Thread-261: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20629]" dev="sockfs" ino=20629 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,06-30 13:52:32.600  3207  3254 W jxcore-log: Starting JXcore engine
,06-30 13:52:32.703  3207  3254 W jxcore-log: Platform android
06-30 13:52:32.703  3207  3254 W jxcore-log: 
06-30 13:52:32.703  3207  3254 W jxcore-log: Process ARCH arm
06-30 13:52:32.703  3207  3254 W jxcore-log: 
,06-30 13:52:32.905  3207  3254 I jxcore-log: JXcore Cordova bridge is ready!
06-30 13:52:32.905  3207  3254 I jxcore-log: 
,06-30 13:52:32.906  3207  3254 W jxcore-log: JXcore engine is started
,06-30 13:52:32.909  3207  3247 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 13:52:32.911   790  1157 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
,06-30 13:52:32.926   790  1157 I ActivityManager: Start proc 3256:com.android.packageinstaller/u0a63 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
06-30 13:52:32.928  3207  3247 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 13:52:32.962  3256  3256 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 13:52:33.050  3256  3268 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 13:52:33.088  3256  3268 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,06-30 13:52:33.090  3256  3268 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 13:52:33.109  1235  1235 I Keyboard.Facilitator: onFinishInput()
,06-30 13:52:33.146   790   811 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +200ms (total +231ms)
,06-30 13:53:03.753  1729  1876 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 13:53:04.763   790  1279 D ConnectivityService: listenForNetwork for Listen from uid/pid:10008/1611 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:53:04.793  1611  3284 W DriveInitializer: Background init thread started
,06-30 13:53:04.844  1611  3284 W DriveInitializer: Background init thread ended
,06-30 13:53:33.111  1235  1350 I Keyboard.Facilitator.LanguageModelFlusher: run()
,06-30 13:53:33.111  1235  1350 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-30 13:53:35.009  1729  1729 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=eb8e39c6-ee4b-448b-a231-c3e06c7102b5
,06-30 13:53:35.010  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 13:53:35.011  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:53:35.093  1729  1795 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 13:53:35.094  1611  3297 D UdcContextInitService: registered all accounts: true
,06-30 13:53:35.102  1729  1779 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 13:53:35.168  1729  1779 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10008, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-30 13:53:35.228  1729  1729 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 13:53:35.233  1729  3309 I VacuumService: Vacuum at: now=1467287615233 tag=VacuumService
,06-30 13:54:35.354  1729  1779 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 13:54:35.355  1729  1779 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 13:54:35.355  1729  1779 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 13:54:35.355  1729  1779 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 13:54:35.379  1729  1779 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
06-30 13:54:35.379  1729  1779 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 13:56:03.595  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:56:03.616  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 13:56:03.616  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:01:03.697  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:01:03.715  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:01:03.715  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:06:03.794  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:06:03.816  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:06:03.817  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:10:48.383   790   805 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 14:11:03.915  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:11:03.935  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 14:11:03.935  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,TIME-OUT KILL (timeout was 1400000ms),06-30 14:16:04.016  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 14:16:04.035  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 14:16:04.035  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 14:16:09.174  3374  3374 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 14:16:09.178  3374  3374 D AndroidRuntime: CheckJNI is OFF
06-30 14:16:09.212  3374  3374 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 14:16:09.246  3374  3374 I Radio-JNI: register_android_hardware_Radio DONE
06-30 14:16:09.266  3374  3374 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 14:16:09.271   790   806 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
06-30 14:16:09.271   790   806 I ActivityManager: Killing 3207:com.test.thalitest/u0a0 (adj 1): stop com.test.thalitest
06-30 14:16:09.302   790  1347 D GraphicsStats: Buffer count: 3
06-30 14:16:09.302   790  1347 I WindowState: WIN DEATH: Window{c7c23e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 14:16:09.303   790   895 D WifiService: Client connection lost with reason: 4
06-30 14:16:09.413   790   817 W PackageSettings: Skipping PackageSetting{b321601 com.example.hello/10278} due to missing metadata
06-30 14:16:09.441   790   806 W PackageManager: Package com.test.thalitest is missing; assuming frozen
06-30 14:16:09.442   790   817 I art     : Starting a blocking GC Explicit
06-30 14:16:09.443   790   806 E ActivityManager: Failure starting process com.test.thalitest
06-30 14:16:09.443   790   806 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:1324)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:3305)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
06-30 14:16:09.443   790   806 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:16:09.443   790   806 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
06-30 14:16:09.443   790   806 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 14:16:09.443   790   806 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
06-30 14:16:09.443   790   806 I ActivityManager:   Force finishing activity ActivityRecord{e8d745d u0 com.test.thalitest/.MainActivity t243}
06-30 14:16:09.444   790   806 I ActivityManager:   Force finishing activity ActivityRecord{8954fdf u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t243}
06-30 14:16:09.448   790   806 I ActivityManager: Killing 2169:com.google.android.calendar/u0a31 (adj 15): empty #17
06-30 14:16:09.486   790   817 I art     : Explicit concurrent mark sweep GC freed 25810(1809KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 24MB/36MB, paused 796us total 42.800ms
06-30 14:16:09.505   790  1278 W ActivityManager: Spurious death for ProcessRecord{5fa7376 0:com.test.thalitest/u0a0}, curProc for 3207: null
06-30 14:16:09.514   790   817 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
06-30 14:16:09.516  3374  3374 I art     : System.exit called, status: 0
06-30 14:16:09.516  3374  3374 I AndroidRuntime: VM exiting with result code 0.
06-30 14:16:09.525   790   817 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
06-30 14:16:09.572   790   806 I ActivityManager: Exiting empty application process com.test.thalitest (null)
06-30 14:16:09.579   790   886 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 14:16:09.580  1729  1795 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 14:16:09.609  1235  1235 I Keyboard.Facilitator: resetDictionaries() : en_US
06-30 14:16:09.611  1235  3405 I Keyboard.Facilitator.DecoderInitializer: run()
06-30 14:16:09.614  1235  3405 I Decoder : createOrResetDecoder
06-30 14:16:09.620  1306  1306 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
06-30 14:16:09.624  2232  3410 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
06-30 14:16:09.641  2232  2249 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj2F5744965) - 
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigChimeraService.a(SourceFile:413)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at keo.run(SourceFile:1072)
06-30 14:16:09.642  1729  3412 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigChimeraService.a(SourceFile:413)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at keo.run(SourceFile:1072)
06-30 14:16:09.643  1729  3412 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
06-30 14:16:09.645  1729  3412 W SQLiteOpenHelper: Opened config.db in read-only mode
06-30 14:16:09.661  2232  3410 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
06-30 14:16:09.662  1378  3415 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
06-30 14:16:09.662  2232  3410 I Process : Sending signal. PID: 2232 SIG: 9
06-30 14:16:09.677   790   790 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 14:16:09.694  1378  3415 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-30 14:16:09.695   790  1552 I ActivityManager: Start proc 3420:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
06-30 14:16:09.706  1235  3405 I Keyboard.Facilitator.MainLanguageModelLoader: run()

```
