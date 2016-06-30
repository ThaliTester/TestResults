#### Test 72145431fdae11f_thali04_LGE-Nexus 5 Logs


```
--------- beginning of main
06-30 10:35:49.053  2446  2481 I Finsky  : [218] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
06-30 10:35:49.116  2446  2481 I Finsky  : [218] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
06-30 10:35:49.117  2446  2446 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,06-30 10:35:51.028  3112  3112 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 10:35:51.032  3112  3112 D AndroidRuntime: CheckJNI is OFF
06-30 10:35:51.065  3112  3112 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 10:35:51.100  3112  3112 I Radio-JNI: register_android_hardware_Radio DONE
06-30 10:35:51.118  3112  3112 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 10:35:51.121   788  1314 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 10:35:51.145   788  1314 I ActivityManager: Start proc 3128:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-30 10:35:51.149  3112  3112 D AndroidRuntime: Shutting down VM
06-30 10:35:51.227  3128  3128 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
06-30 10:35:51.270  3128  3128 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1897-1899)
06-30 10:35:51.270  3128  3128 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:51.287  3128  3128 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6ad6c92}
06-30 10:35:51.287  3128  3128 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:51.287  3128  3128 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 10:35:51.293  3128  3128 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 10:35:51.294  3128  3128 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 10:35:51.299  3128  3143 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
06-30 10:35:51.304  3128  3128 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-30 10:35:51.307  3128  3128 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:35:51.307  3128  3128 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:35:51.308  3128  3128 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
06-30 10:35:51.343   788   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5a160e1:true
,06-30 10:35:51.422  3128  3128 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 10:35:51.432  3128  3128 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,06-30 10:35:51.480  3128  3165 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:35:51.502  3128  3152 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-30 10:35:51.538  3128  3165 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:35:51.579   788   809 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +401ms (total +447ms)
,06-30 10:35:51.582  1227  1227 I Keyboard.Facilitator: onFinishInput()
,06-30 10:35:51.669  3128  3128 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3128
,06-30 10:35:51.759  3128  3128 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:35:51.875  3128  3168 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1640429264
,06-30 10:35:51.879  3128  3168 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:35:51.879  3128  3168 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:35:51.879  3128  3168 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:35:51.879  3128  3168 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:35:51.879  3128  3168 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,06-30 10:35:51.879  3128  3168 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa40211 added. We now have 1 listener(s)
,06-30 10:35:51.881  3128  3168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
,06-30 10:35:51.882  3128  3168 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
06-30 10:35:51.882  3128  3168 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-30 10:35:51.882  3128  3168 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-30 10:35:51.885  3128  3168 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9cb19e4 added. We now have 1 listener(s)
06-30 10:35:51.885  3128  3168 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 10:35:51.887   788   893 D WifiService: New client listening to asynchronous messages
,06-30 10:35:51.887  3128  3168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:51.887  3128  3168 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 10:35:51.888  3128  3168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 10:35:51.888  3128  3168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:35:51.888  3128  3168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,06-30 10:35:51.888  3128  3168 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 10:35:51.889  3128  3168 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 10:35:51.889  3128  3168 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
,06-30 10:35:51.890  3128  3168 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:35:51.890  3128  3168 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:35:51.890  3128  3168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:51.890  3128  3168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:51.890  3128  3168 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:51.890  3128  3168 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:51.890  3128  3168 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:51.890  3128  3168 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:51.890  3128  3168 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:51.890  3128  3168 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:35:51.890  3128  3168 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:35:51.891  3128  3168 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 10:35:51.940  3128  3128 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:35:52.629  3128  3175 W jxcore-log: Initializing JXcore engine
,06-30 10:35:52.629  3128  3175 W jxcore-log: JXcore engine is ready
,06-30 10:35:52.654  3175  3175 W Thread-257: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[8667]" dev="sockfs" ino=8667 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,06-30 10:35:52.654  3175  3175 W Thread-257: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 10:35:52.654  3175  3175 W Thread-257: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20229]" dev="sockfs" ino=20229 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,06-30 10:35:52.678  3128  3175 W jxcore-log: Starting JXcore engine
,06-30 10:35:52.758  3128  3175 W jxcore-log: Platform android
06-30 10:35:52.758  3128  3175 W jxcore-log: 
,06-30 10:35:52.758  3128  3175 W jxcore-log: Process ARCH arm
06-30 10:35:52.758  3128  3175 W jxcore-log: 
,06-30 10:35:52.948  3128  3175 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:35:52.948  3128  3175 I jxcore-log: 
,06-30 10:35:52.948  3128  3175 W jxcore-log: JXcore engine is started
,06-30 10:35:52.954  3128  3168 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 10:35:52.956   788  2549 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
,06-30 10:35:52.969   788  2549 I ActivityManager: Start proc 3176:com.android.packageinstaller/u0a63 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 10:35:52.972  3128  3168 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 10:35:53.005  3176  3176 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 10:35:53.089  3176  3188 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:35:53.136  3176  3188 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,06-30 10:35:53.138  3176  3188 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:35:53.166  1227  1227 I Keyboard.Facilitator: onFinishInput()
,06-30 10:35:53.219   788   809 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +226ms (total +260ms)
,06-30 10:36:30.787  1694  1873 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 10:36:31.933   788   974 D ConnectivityService: listenForNetwork for Listen from uid/pid:10008/1600 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 10:36:31.969  1600  3211 W DriveInitializer: Background init thread started
,06-30 10:36:32.022  1600  3211 W DriveInitializer: Background init thread ended
,06-30 10:36:53.169  1227  1349 I Keyboard.Facilitator.LanguageModelFlusher: run()
,06-30 10:36:53.169  1227  1349 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-30 10:37:02.104  1694  1694 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=7f043ae6-39f1-4250-901c-4c2ca4d4ea32
,06-30 10:37:02.105  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:37:02.106  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:37:02.196  1600  3244 D UdcContextInitService: registered all accounts: true
06-30 10:37:02.197  1694  1787 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 10:37:02.203  1694  1760 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 10:37:02.282  1694  1760 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10008, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-30 10:37:02.318  1694  1694 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 10:37:02.321  1694  3256 I VacuumService: Vacuum at: now=1467275822321 tag=VacuumService
,06-30 10:38:02.428  1694  1760 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-30 10:38:02.429  1694  1760 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-30 10:38:02.429  1694  1760 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 10:38:02.430  1694  1760 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 10:38:02.489  1694  1760 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
06-30 10:38:02.489  1694  1760 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 10:39:30.610  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:39:30.628  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:39:30.628  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:44:30.709  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:44:30.726  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:44:30.726  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:49:30.807  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:49:30.819  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:49:30.820  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:54:15.453   788   800 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 10:54:30.916  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:54:30.935  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:54:30.938  1694  1694 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,TIME-OUT KILL (timeout was 1400000ms)
```
