#### Test 757892686fd65a6_thali04_LGE-Nexus 5 Logs


```
--------- beginning of main
,07-01 08:59:04.638  1701  1884 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
07-01 08:59:05.333  3165  3165 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-01 08:59:05.337  3165  3165 D AndroidRuntime: CheckJNI is OFF
07-01 08:59:05.380  3165  3165 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-01 08:59:05.422  3165  3165 I Radio-JNI: register_android_hardware_Radio DONE
07-01 08:59:05.441  3165  3165 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-01 08:59:05.444   786  1230 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-01 08:59:05.463   786  1230 I ActivityManager: Start proc 3181:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-01 08:59:05.466  3165  3165 D AndroidRuntime: Shutting down VM
07-01 08:59:05.565   786   797 D ConnectivityService: listenForNetwork for Listen from uid/pid:10008/1625 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 08:59:05.588  3181  3181 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-01 08:59:05.607  1625  3205 W DriveInitializer: Background init thread started
07-01 08:59:05.618  3181  3181 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2285-2288)
07-01 08:59:05.618  3181  3181 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:59:05.638  3181  3181 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e938374}
07-01 08:59:05.638  3181  3181 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:59:05.638  3181  3181 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 08:59:05.644  3181  3181 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 08:59:05.645  3181  3181 E SysUtils: ApplicationContext is null in ApplicationStatus
07-01 08:59:05.650  3181  3210 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-01 08:59:05.655  3181  3181 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-01 08:59:05.659  3181  3181 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 08:59:05.659  3181  3181 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 08:59:05.659  3181  3181 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-01 08:59:05.675  1625  3205 W DriveInitializer: Background init thread ended
,07-01 08:59:05.699   786   806 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ccc75f8:true
,07-01 08:59:05.788  3181  3181 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-01 08:59:05.799  3181  3181 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-01 08:59:05.841  3181  3241 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-01 08:59:05.862  3181  3225 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-01 08:59:05.890  3181  3241 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 08:59:05.920  1233  1233 I Keyboard.Facilitator: onFinishInput()
,07-01 08:59:05.945   786   807 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +400ms (total +490ms)
,07-01 08:59:06.036  3181  3181 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3181
,07-01 08:59:06.121  3181  3181 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 08:59:06.253  3181  3245 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1655256784
,07-01 08:59:06.257  3181  3245 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 08:59:06.257  3181  3245 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 08:59:06.257  3181  3245 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 08:59:06.257  3181  3245 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 08:59:06.257  3181  3245 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-01 08:59:06.257  3181  3245 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ecf11b added. We now have 1 listener(s)
,07-01 08:59:06.260  3181  3245 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
,07-01 08:59:06.262  3181  3245 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-01 08:59:06.262  3181  3245 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-01 08:59:06.263  3181  3245 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-01 08:59:06.265  3181  3245 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc973f6 added. We now have 1 listener(s)
07-01 08:59:06.266  3181  3245 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 08:59:06.268   786   893 D WifiService: New client listening to asynchronous messages
,07-01 08:59:06.268  3181  3245 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-01 08:59:06.268  3181  3245 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-01 08:59:06.269  3181  3245 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-01 08:59:06.269  3181  3245 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-01 08:59:06.269  3181  3245 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-01 08:59:06.269  3181  3245 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-01 08:59:06.272  3181  3245 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-01 08:59:06.272  3181  3245 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
,07-01 08:59:06.274  3181  3245 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-01 08:59:06.274  3181  3245 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 08:59:06.274  3181  3245 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 08:59:06.274  3181  3245 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-01 08:59:06.274  3181  3245 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 08:59:06.274  3181  3245 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 08:59:06.274  3181  3245 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 08:59:06.274  3181  3245 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 08:59:06.274  3181  3245 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 08:59:06.274  3181  3245 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-01 08:59:06.274  3181  3245 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-01 08:59:06.274  3181  3245 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 08:59:06.298  3181  3181 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 08:59:06.964  3181  3258 W jxcore-log: Initializing JXcore engine
,07-01 08:59:06.964  3181  3258 W jxcore-log: JXcore engine is ready
,07-01 08:59:06.994  3258  3258 W Thread-254: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[7715]" dev="sockfs" ino=7715 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-01 08:59:06.994  3258  3258 W Thread-254: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-01 08:59:06.994  3258  3258 W Thread-254: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18763]" dev="sockfs" ino=18763 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-01 08:59:07.011  3181  3258 W jxcore-log: Starting JXcore engine
,07-01 08:59:07.086  3181  3258 W jxcore-log: Platform android
07-01 08:59:07.086  3181  3258 W jxcore-log: 
,07-01 08:59:07.087  3181  3258 W jxcore-log: Process ARCH arm
07-01 08:59:07.087  3181  3258 W jxcore-log: 
,07-01 08:59:07.275  3181  3258 I jxcore-log: JXcore Cordova bridge is ready!
07-01 08:59:07.275  3181  3258 I jxcore-log: 
07-01 08:59:07.275  3181  3258 W jxcore-log: JXcore engine is started
,07-01 08:59:07.280  3181  3245 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 08:59:07.282   786  1230 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
,07-01 08:59:07.293   786  1230 I ActivityManager: Start proc 3259:com.android.packageinstaller/u0a63 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,07-01 08:59:07.326  3259  3259 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,07-01 08:59:07.424  3259  3271 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-01 08:59:07.473  3259  3271 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-01 08:59:07.475  3259  3271 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 08:59:07.506  1233  1233 I Keyboard.Facilitator: onFinishInput()
,07-01 08:59:07.563   786   807 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +249ms (total +278ms)
,07-01 08:59:35.792  1701  1701 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=943d8a83-5d3f-4ca4-b613-5469a123af10
,07-01 08:59:35.793  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-01 08:59:35.794  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 08:59:35.871  1701  1792 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-01 08:59:35.873  1625  3285 D UdcContextInitService: registered all accounts: true
,07-01 08:59:35.876  1701  1768 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-01 08:59:35.927  1701  1768 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10008, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
07-01 08:59:35.927  1701  1701 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,07-01 08:59:36.000  1625  1854 I Icing   : Performing maintenance.
,07-01 08:59:36.004  1625  3300 E IcingInternalCorpora: Unknown Contacts update mode: MAYBE
,07-01 08:59:36.049  1625  3301 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-01 08:59:36.055  1701  1761 E Auth    : [GoogleAccountDataServiceImpl] getToken() -> NETWORK_ERROR. Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/webhistory
,07-01 08:59:36.057  1625  1854 W Icing   : Failed to get auth token for account:<redacted>, error:NetworkError
,07-01 08:59:36.075  1701  1760 E Auth    : [GoogleAccountDataServiceImpl] getToken() -> NETWORK_ERROR. Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/webhistory
,07-01 08:59:36.076  1625  1854 W Icing   : Failed to get auth token for account:<redacted>, error:NetworkError
,07-01 08:59:36.077  1701  3303 I VacuumService: Vacuum at: now=1467356376077 tag=VacuumService
,07-01 08:59:36.159  1625  1854 I Icing   : updateResources: need to parse pru{com.google.android.gms}
,07-01 08:59:36.267  1625  1854 I Icing   : Performing maintenance usage 1704427 budget 5501069557 free 99.969% index free 99.982% purge? false target 3850748689
,07-01 08:59:36.274  1625  1854 I Icing   : Starting compaction min disk 99.969% min index 99.982%
,07-01 08:59:36.425  1625  1854 I Icing   : Usage reports aged/total 0/6
,07-01 08:59:36.634  1625  1854 I Icing   : Done compaction min disk 99.969% min index 99.982% num docs 66 old 73 trimmed 0 err 0
,07-01 08:59:36.641  1625  1788 I Icing   : Query from com.google.android.gms package restrict com.google.android.gms start 0 num 100
,07-01 09:00:05.559  1625  3310 I EventLogChimeraService: Aggregate from 1467354602024 (log), 1467354602024 (data)
,07-01 09:00:05.718  1625  3312 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,07-01 09:00:05.733  1625  3312 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,07-01 09:00:07.509  1233  1344 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-01 09:00:07.509  1233  1344 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-01 09:00:36.093  1701  1768 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-01 09:00:36.093  1701  1768 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-01 09:00:36.094  1701  1768 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
07-01 09:00:36.094  1701  1768 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
07-01 09:00:36.094  1701  1768 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,07-01 09:00:36.117  1701  1768 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,07-01 09:00:43.761   786   884 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-01 09:00:43.761   786   786 V KeyguardServiceDelegate: onStartedWakingUp()
07-01 09:00:43.763   786   813 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-01 09:00:43.772  3181  3181 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-01 09:00:43.773  3181  3181 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-01 09:00:43.776   786   813 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@e9fb24a)
07-01 09:00:43.778   786  2321 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-01 09:00:43.781   786   892 D WifiConfigStore: Retrieve network priorities after PNO.
07-01 09:00:43.781   786   892 E WifiStateMachine:  Fail to set up pno, want false now false
,07-01 09:00:43.784   202   829 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-01 09:00:43.794  1701  1701 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-01 09:00:43.805  1273  1356 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
,07-01 09:00:43.805  1273  1356 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
07-01 09:00:43.805  1273  1356 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
07-01 09:00:43.805  1273  1352 D BrcmNfcJni: RoutingManager::commitRouting
07-01 09:00:43.805  1273  1356 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
,07-01 09:00:43.822  1273  1352 D NfcService: Discovery configuration equal, not updating.
,07-01 09:00:43.859  1948  1952 E ANDR-PERF-LOCK: Failed to reset optimization for resource: 4 level: 0
,07-01 09:00:43.860   786   807 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-01 09:00:43.860   194   194 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6b24000
07-01 09:00:43.860   194   194 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-01 09:00:44.030   786   813 I DisplayPowerController: Unblocked screen on after 267 ms
,07-01 09:00:44.031   786   813 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-01 09:00:44.093   194   194 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-01 09:00:44.094   786   909 D SurfaceControl: Excessive delay in setPowerMode(): 234ms
,07-01 09:01:13.755   786   813 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-01 09:01:13.756   786   813 I PowerManagerService: Sleeping (uid 1000)...
,07-01 09:01:13.883  1233  1233 I Keyboard.Facilitator: onFinishInput()
,07-01 09:01:13.889  3181  3181 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-01 09:01:13.889  3181  3181 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-01 09:01:13.920   786   795 I art     : Background partial concurrent mark sweep GC freed 18963(1433KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 24MB/36MB, paused 754us total 103.732ms
,07-01 09:01:14.339   786   813 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-01 09:01:14.386   786   807 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-01 09:01:14.390   194   194 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
07-01 09:01:14.390   194   194 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-01 09:01:14.660   194   194 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-01 09:01:14.661   786   909 D SurfaceControl: Excessive delay in setPowerMode(): 275ms
,07-01 09:01:14.661  1948  1952 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
07-01 09:01:14.667   786   892 D WifiConfigStore: Retrieve network priorities after PNO.
07-01 09:01:14.667   786   892 E WifiStateMachine:  Fail to set up pno, want false now false
07-01 09:01:14.669   202   202 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-01 09:01:38.720   786   884 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-01 09:01:38.721   786   786 V KeyguardServiceDelegate: onStartedWakingUp()
,07-01 09:01:38.723   786   813 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-01 09:01:38.729  1233  1233 I Keyboard.Facilitator: onFinishInput()
07-01 09:01:38.731   786   813 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@e9fb24a)
07-01 09:01:38.732  3181  3181 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-01 09:01:38.732  3181  3181 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-01 09:01:38.741   786  1541 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-01 09:01:38.744   786   892 D WifiConfigStore: Retrieve network priorities after PNO.
07-01 09:01:38.744   786   892 E WifiStateMachine:  Fail to set up pno, want false now false
07-01 09:01:38.746   202   900 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-01 09:01:38.761  1701  1701 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-01 09:01:38.772  1273  1356 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
,07-01 09:01:38.772  1273  1356 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
07-01 09:01:38.772  1273  1356 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
07-01 09:01:38.772  1273  2849 D BrcmNfcJni: RoutingManager::commitRouting
07-01 09:01:38.772  1273  1356 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
,07-01 09:01:38.782  1273  2849 D NfcService: Discovery configuration equal, not updating.
,07-01 09:01:38.821  1948  1952 E ANDR-PERF-LOCK: Failed to reset optimization for resource: 4 level: 0
,07-01 09:01:38.822   786   807 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-01 09:01:38.822   194   194 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6b24000
07-01 09:01:38.822   194   194 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-01 09:01:38.991   786   813 I DisplayPowerController: Unblocked screen on after 268 ms
,07-01 09:01:38.991   786   813 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-01 09:01:39.053   194   194 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-01 09:01:39.053   786   909 D SurfaceControl: Excessive delay in setPowerMode(): 231ms
,07-01 09:02:04.455  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:02:04.479  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:02:04.482  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:02:08.717   786   813 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-01 09:02:08.718   786   813 I PowerManagerService: Sleeping (uid 1000)...
,07-01 09:02:08.833  1233  1233 I Keyboard.Facilitator: onFinishInput()
,07-01 09:02:08.847  3181  3181 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-01 09:02:08.847  3181  3181 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-01 09:02:09.281   786   813 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-01 09:02:09.305   786   807 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-01 09:02:09.309   194   194 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
07-01 09:02:09.309   194   194 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-01 09:02:09.588   194   194 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-01 09:02:09.588   786   909 D SurfaceControl: Excessive delay in setPowerMode(): 283ms
07-01 09:02:09.589  1948  1952 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-01 09:02:09.594   786   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-01 09:02:09.594   786   892 E WifiStateMachine:  Fail to set up pno, want false now false
07-01 09:02:09.596   202   829 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-01 09:03:08.835  1233  1344 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-01 09:03:08.835  1233  1344 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-01 09:03:38.765  1701  1884 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-01 09:04:31.371   786   884 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-01 09:04:31.372   786   786 V KeyguardServiceDelegate: onStartedWakingUp()
,07-01 09:04:31.374   786   813 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-01 09:04:31.382  3181  3181 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-01 09:04:31.382  3181  3181 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-01 09:04:31.383   786   813 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@e9fb24a)
07-01 09:04:31.389  1233  1233 I Keyboard.Facilitator: onFinishInput()
,07-01 09:04:31.389   786   892 D WifiConfigStore: Retrieve network priorities after PNO.
07-01 09:04:31.389   786   892 E WifiStateMachine:  Fail to set up pno, want false now false
,07-01 09:04:31.391   202   202 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-01 09:04:31.393   786   967 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-01 09:04:31.405  1701  1701 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-01 09:04:31.418  1273  1356 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
,07-01 09:04:31.419  1273  1356 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
07-01 09:04:31.419  1273  1356 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
07-01 09:04:31.420  1273  1689 D BrcmNfcJni: RoutingManager::commitRouting
,07-01 09:04:31.420  1273  1356 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
,07-01 09:04:31.426  1273  1689 D NfcService: Discovery configuration equal, not updating.
,07-01 09:04:31.465  1948  1952 E ANDR-PERF-LOCK: Failed to reset optimization for resource: 4 level: 0
,07-01 09:04:31.465   786   807 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-01 09:04:31.465   194   194 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6b24000
07-01 09:04:31.466   194   194 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-01 09:04:31.635   786   813 I DisplayPowerController: Unblocked screen on after 261 ms
,07-01 09:04:31.636   786   813 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-01 09:04:31.703   194   194 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-01 09:04:31.703   786   909 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
,07-01 09:05:01.365   786   813 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-01 09:05:01.367   786   813 I PowerManagerService: Sleeping (uid 1000)...
07-01 09:05:01.506  1233  1233 I Keyboard.Facilitator: onFinishInput()
,07-01 09:05:01.522  3181  3181 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-01 09:05:01.522  3181  3181 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-01 09:05:01.944   786   813 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-01 09:05:01.994   786   807 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-01 09:05:01.999   194   194 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,07-01 09:05:01.999   194   194 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-01 09:05:02.270   194   194 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-01 09:05:02.271   786   909 D SurfaceControl: Excessive delay in setPowerMode(): 276ms
,07-01 09:05:02.271  1948  1952 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
07-01 09:05:02.277   786   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-01 09:05:02.277   786   892 E WifiStateMachine:  Fail to set up pno, want false now false
,07-01 09:05:02.279   202   900 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-01 09:06:01.509  1233  1344 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-01 09:06:01.509  1233  1344 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-01 09:06:31.409  1701  1884 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-01 09:07:04.574  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:04.596  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:04.596  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:46.493  2518  2518 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(17227): Beginning daily hygiene, foreground = false
,07-01 09:07:46.543  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:46.546  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-01 09:07:46.546  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:46.590  2518  2518 W Finsky  : [1] com.google.android.finsky.services.n.a(313): Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-01 09:07:46.599  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:46.618  2518  2518 W Finsky  : [1] com.google.android.finsky.services.q.a(413): Self-update check failed with error: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-01 09:07:46.627  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:46.653  2518  2518 W Finsky  : [1] com.google.android.finsky.j.ac.a(562): Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-01 09:07:46.760  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:46.787  2518  2518 W Finsky  : [1] com.google.android.finsky.autoupdate.t.a(243): Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-01 09:07:46.789  2518  2518 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(590): Logging device features
,07-01 09:07:46.793  2518  2518 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(57): Cancelling accelerated self-Update check
,07-01 09:07:46.798  2518  2518 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(783): Scheduling new run in 27 minutes (failures=2)
,07-01 09:07:46.809  1701  1701 D WearableService: callingUid 10008, callindPid: 1701
,07-01 09:07:46.878  2518  2518 I Finsky  : [1] com.google.android.vending.verifier.VerifyInstalledPackagesReceiver.onReceive(2100): Skipping verification because network inactive
,07-01 09:07:46.880  1701  1761 D DeviceConnectionService: client connected with version: 8486000
,07-01 09:07:46.891  2518  2518 E Finsky  : [1] com.google.android.finsky.wear.bk.a(752): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-01 09:07:46.891  2518  2518 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6355): Dropping command=hygiene due to Gms not connected
,07-01 09:07:46.901  2518  3548 I Finsky  : [233] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-01 09:07:46.901  2518  2554 I PlayCommon: [215] com.google.android.play.a.w.a(27551): Starting to flush logs
,07-01 09:07:46.923  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:07:46.970  2518  2554 I PlayCommon: [215] com.google.android.play.a.w.a(27562): Log flushed by 0 successful uploads
,07-01 09:08:01.715  2518  2557 I Finsky  : [218] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-01 09:08:01.784  2518  2557 I Finsky  : [218] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-01 09:08:01.785  2518  2518 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-01 09:12:04.678  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:12:04.697  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-01 09:12:04.697  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:16:49.211   786   801 I UsageStatsService: User[0] Flushing usage stats to disk
,07-01 09:17:04.795  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:17:04.815  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:17:04.815  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:19:04.837  1701  1884 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-01 09:22:04.913  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-01 09:22:04.925  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-01 09:22:04.926  1701  1701 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,TIME-OUT KILL (timeout was 1400000ms)
```
