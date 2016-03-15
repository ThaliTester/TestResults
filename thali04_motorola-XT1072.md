#### Test 6275440391a6bae_thali04_motorola-XT1072 Logs


```
--------- beginning of system
03-15 20:35:41.751   885  3197 W libprocessgroup: failed to open /acct/uid_10060/pid_4709/cgroup.procs: No such file or directory
,03-15 20:35:41.836   885  1512 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4875 uid=10054 gids={50054, 9997, 3003} abi=armeabi-v7a
--------- beginning of main
03-15 20:35:41.956  4875  4875 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
03-15 20:35:41.966  4875  4875 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
03-15 20:35:41.977  4875  4875 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
03-15 20:35:41.993  4875  4875 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
03-15 20:35:42.032  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-15 20:35:42.040   885  1301 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=4906 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
03-15 20:35:42.064   885  1486 I ActivityManager: Killing 4684:com.google.android.gm/u0a63 (adj 15): empty #7
03-15 20:35:42.123   885  1222 W libprocessgroup: failed to open /acct/uid_10063/pid_4684/cgroup.procs: No such file or directory
03-15 20:35:42.168   885  1558 I ActivityManager: Killing 4756:com.android.providers.calendar/u0a5 (adj 15): empty #7
03-15 20:35:42.225  4892  4892 D AndroidRuntime: 
03-15 20:35:42.225  4892  4892 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-15 20:35:42.228  4892  4892 D AndroidRuntime: CheckJNI is OFF
03-15 20:35:42.263   885  1486 W libprocessgroup: failed to open /acct/uid_10005/pid_4756/cgroup.procs: No such file or directory
03-15 20:35:42.434  4892  4892 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-15 20:35:42.447   885  3197 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-15 20:35:42.480   281  3814 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (315 us)
03-15 20:35:42.500  1484  3885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-15 20:35:42.504  4892  4892 D AndroidRuntime: Shutting down VM
03-15 20:35:42.550   885   900 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4959 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-15 20:35:42.553   885  1528 I ActivityManager: Killing 4603:com.motorola.context/u0a8 (adj 15): empty #7
03-15 20:35:42.659   885  1557 W libprocessgroup: failed to open /acct/uid_10008/pid_4603/cgroup.procs: No such file or directory
03-15 20:35:42.665  1484  3885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-15 20:35:42.702  4906  4988 I GservicesUpdateTask: Updating Gservices keys
,03-15 20:35:42.717  1962  4989 D GmsModuleFndr: Beginning GMS chimera module scan
,03-15 20:35:42.718  1962  4989 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
,03-15 20:35:42.720  1962  4989 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
,03-15 20:35:42.739  1962  1962 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,03-15 20:35:42.745  1962  4989 D ChimeraCfgMgr: Beginning module configuration check
,03-15 20:35:42.750  1962  4990 I CheckinService: Checking schedule, now: 1458070542750 next: 1458671673803
03-15 20:35:42.750  1962  4990 I CheckinService: active receiver: disabled
,03-15 20:35:42.753  1962  1962 D SystemUpdateService: onCreate
,03-15 20:35:42.757  1962  1962 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-15 20:35:42.770  1962  4989 D ChimeraCfgMgr: Module APKs unchanged, check complete
,03-15 20:35:42.786  1962  4992 I SystemUpdateService: cancelUpdate (empty URL)
,03-15 20:35:42.786  1962  4992 I SystemUpdateService: active receiver: disabled
,03-15 20:35:42.865  3854  3944 I art     : Explicit concurrent mark sweep GC freed 4276(178KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 968us total 31.233ms
,03-15 20:35:43.080  4959  4959 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-15 20:35:43.106  4959  4959 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9942-9944)
,03-15 20:35:43.106  4959  4959 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 20:35:43.118  1962  1962 I art     : Explicit concurrent mark sweep GC freed 6634(468KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 12MB/21MB, paused 1.431ms total 81.158ms
,03-15 20:35:43.133  1962  1974 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-15 20:35:43.141  4959  4959 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2038ccfe}
,03-15 20:35:43.142  4959  4959 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 20:35:43.148  4959  4959 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 20:35:43.167  4959  4959 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-15 20:35:43.168  4959  4959 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:35:43.170  4959  4959 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-15 20:35:43.174  3854  4327 I art     : Explicit concurrent mark sweep GC freed 2672(103KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.172ms total 34.802ms
,03-15 20:35:43.204  4959  4959 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-15 20:35:43.214  4959  4959 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-15 20:35:43.214  4959  4959 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-15 20:35:43.215  4959  4959 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 20:35:43.215  4959  4959 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 20:35:43.215  4959  4959 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 20:35:43.215  4959  4959 I Adreno-EGL: Local Branch: 
03-15 20:35:43.215  4959  4959 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 20:35:43.215  4959  4959 I Adreno-EGL: Local Patches: NONE
03-15 20:35:43.215  4959  4959 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 20:35:43.270  1962  1962 D SystemUpdateService: onDestroy
,03-15 20:35:43.304  1962  1962 W DynamiteLoaderImpl: Failed to load module version: module com.google.android.gms.flags not found
,03-15 20:35:43.304  1962  1962 I DynamiteModule: Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
03-15 20:35:43.305  1962  1962 I DynamiteModule: Selected local version of com.google.android.gms.flags
,03-15 20:35:43.310   885  1111 D BluetoothManagerService: Message: 20
03-15 20:35:43.310   885  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8b5e81d:true
,03-15 20:35:43.387  1962  1962 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,03-15 20:35:43.448   885  1644 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5023 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:43.455  1962  1962 I OcrUtils: Updating ocr activity enabled=false
,03-15 20:35:43.483  5023  5023 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-15 20:35:43.505  4959  4959 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:35:43.516  4959  4959 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-15 20:35:43.533  5023  5023 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@26121303(com.android.providers.calendar.CalendarProvider2@2ecf3280)
,03-15 20:35:43.536  4959  4959 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-15 20:35:43.557  4959  4959 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-15 20:35:43.557  4959  4959 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:35:43.591   885  1301 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,03-15 20:35:43.598  1962  1962 D OcrModelManager: Updating downloaded model state (gservices changed)
,03-15 20:35:43.640  4959  5056 D OpenGLRenderer: Render dirty regions requested: true
,03-15 20:35:43.658  4959  4959 D Atlas   : Validating map...
,03-15 20:35:43.665  4959  5012 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-15 20:35:43.712  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 20:35:43.712  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:35:43.715  4959  5056 I OpenGLRenderer: Initialized EGL, version 1.4
,03-15 20:35:43.719  3854  3869 I art     : Explicit concurrent mark sweep GC freed 2721(107KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 732us total 34.887ms
,03-15 20:35:43.723  4959  5056 D OpenGLRenderer: Enabling debug mode 0
,03-15 20:35:43.790  1423  1423 I Keyboard.Facilitator: onFinishInput()
,03-15 20:35:43.793   885  1112 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1286
03-15 20:35:43.793   885  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s286ms
,03-15 20:35:43.818  1715  2369 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,03-15 20:35:43.948  4959  5064 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-15 20:35:43.949  4959  5064 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-15 20:35:43.988  4959  4959 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4959
,03-15 20:35:43.993   281   281 I SFPerfTracer:      triggers: (rate: 15:428) (compose: 0:1) (post: 0:1) (render: 0:2) (8:914 frames) (9:1003)
03-15 20:35:43.993   281   281 D SFPerfTracer:        layers: (4:13) (FocusedStackFrame (0xb7557738): 0:15)* (DimLayer (0xb74eb528): 0:6)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7543568): 0:39)- (StatusBar (0xb7548938): 0:120) (NavigationBar (0xb755f540): 0:33) (com.android.systemui.ImageWallpaper (0xb7561930): 0:6)* (Starting com.motorola.ccc.ota (0xb7538008): 0:28)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb75871c0): 0:52)- (Starting com.test.thalitest (0xb7538008): 9:39) (com.test.thalitest/com.test.thalitest.MainActivity (0xb7543f48): 0:5) 
,03-15 20:35:44.067   885  1557 I art     : Explicit concurrent mark sweep GC freed 15604(776KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 3.145ms total 147.576ms
,03-15 20:35:44.214  4959  4959 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-15 20:35:44.334  1715  1715 I art     : Explicit concurrent mark sweep GC freed 14622(777KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 13MB/22MB, paused 1.108ms total 83.747ms
,03-15 20:35:44.388  1715  1715 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,03-15 20:35:44.392  1715  1715 I GCoreUlr: DispatchingService.onCreate()
,03-15 20:35:44.516   885  1599 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5073 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-15 20:35:44.558   281   723 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (43:232 vsyncs) (45:1036)
,03-15 20:35:44.568  5023  5023 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-15 20:35:44.569  5023  5023 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-15 20:35:44.585  4959  5056 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-15 20:35:44.585  4959  5056 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-15 20:35:44.594   885  1222 I ActivityManager: Killing 4790:com.google.android.talk/u0a70 (adj 15): empty #7
,03-15 20:35:44.625  5073  5073 D PhoneMonitor: Register our PhoneStateListener
03-15 20:35:44.626  1715  2029 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-15 20:35:44.796   885  1528 W libprocessgroup: failed to open /acct/uid_10070/pid_4790/cgroup.procs: No such file or directory
,03-15 20:35:44.817  1715  5084 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,03-15 20:35:44.823  4959  5060 D jxcore_app_log: JniHelper::setJavaVM(0xb7d9f310), pthread_self() = -1206879712
,03-15 20:35:44.838  1715  5062 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
03-15 20:35:44.838  4959  5060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-15 20:35:44.838  4959  5060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-15 20:35:44.838  4959  5060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-15 20:35:44.838  4959  5060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-15 20:35:44.838  4959  5060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-15 20:35:44.838  4959  5060 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ec2866a added. We now have 1 listener(s)
03-15 20:35:44.839   885  1599 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-15 20:35:44.843  4959  5060 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
,03-15 20:35:44.846  4959  5060 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,03-15 20:35:44.847  4959  5060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-15 20:35:44.847  4959  5060 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-15 20:35:44.847  4959  5060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-15 20:35:44.855  4959  5060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-15 20:35:44.855  4959  5060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-15 20:35:44.855  4959  5060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-15 20:35:44.855  4959  5060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-15 20:35:44.855  4959  5060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-15 20:35:44.855  4959  5060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-15 20:35:44.855  4959  5060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-15 20:35:44.855  4959  5060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-15 20:35:44.855  4959  5060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-15 20:35:44.855  4959  5060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-15 20:35:44.855  4959  5060 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30508d1 added. We now have 1 listener(s)
03-15 20:35:44.855  4959  5060 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-15 20:35:44.857  5073  5073 V SetupWizard: Connected to Gservices successfully
,03-15 20:35:44.869   885  1240 D WifiService: New client listening to asynchronous messages
,03-15 20:35:44.872  4959  5060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-15 20:35:44.877  4959  5060 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-15 20:35:44.877  4959  5060 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-15 20:35:44.882  4959  5060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-15 20:35:44.883   885  3197 I ActivityManager: Killing 4875:com.google.android.configupdater/u0a54 (adj 15): empty #7
,03-15 20:35:45.002   885   901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-15 20:35:45.005   885  1558 W libprocessgroup: failed to open /acct/uid_10054/pid_4875/cgroup.procs: No such file or directory
,03-15 20:35:45.009  4959  5060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-15 20:35:45.017  4959  5060 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-15 20:35:45.017  4959  5060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-15 20:35:45.017  4959  5060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-15 20:35:45.017  4959  5060 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-15 20:35:45.017  4959  5060 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-15 20:35:45.017  4959  5060 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-15 20:35:45.017  4959  5060 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-15 20:35:45.017  4959  5060 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-15 20:35:45.017  4959  5060 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-15 20:35:45.017  4959  5060 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-15 20:35:45.020  4959  4959 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 20:35:45.023  4959  4959 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 20:35:45.103   885  1222 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5097 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-15 20:35:45.122  4959  4959 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-15 20:35:45.133  1715  2415 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-15 20:35:45.186  3854  3870 I art     : Explicit concurrent mark sweep GC freed 2641(105KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.456ms total 42.164ms
,03-15 20:35:45.202  5097  5097 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 20:35:45.225  1715  5062 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10016, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,03-15 20:35:45.228  1715  1715 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,03-15 20:35:45.308  1715  5084 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-15 20:35:45.317  1715  5084 I GCoreUlr: Unbound from all location providers
03-15 20:35:45.317  1715  5084 I GCoreUlr: Place inference reporting - stopped
,03-15 20:35:45.335  1715  1715 I GCoreUlr: DispatchingService.onDestroy()
,03-15 20:35:45.335  1715  1715 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-15 20:35:45.339  1715  1715 I GCoreUlr: Unbound from all location providers
03-15 20:35:45.339  1715  1715 I GCoreUlr: Place inference reporting - stopped
,03-15 20:35:45.421  5097  5120 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-15 20:35:45.421  5097  5120 I Babel_SMS: MmsConfig.loadMmsSettings
,03-15 20:35:45.424  5097  5120 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-15 20:35:45.424  5097  5120 I Babel_SMS: MmsConfig.loadFromDatabase
,03-15 20:35:45.445  5097  5120 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-15 20:35:45.445  5097  5120 I Babel_SMS: MmsConfig.loadFromResources
,03-15 20:35:45.447  5097  5120 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-15 20:35:45.448  5097  5120 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-15 20:35:45.521  5097  5097 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-15 20:35:45.525  5097  5097 I Babel_Crash: startup - clean
,03-15 20:35:45.552  5097  5123 I Babel   : deleted: false for 0
,03-15 20:35:45.647  5097  5112 W art     : Suspending all threads took: 11.536ms
,03-15 20:35:45.699   885  1644 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5125 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-15 20:35:45.721   309   309 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 22.259ms
,03-15 20:35:45.741   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 18.959ms
,03-15 20:35:45.761   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 19.809ms
,03-15 20:35:45.818  5097  5097 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 20:35:45.827  5097  5097 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-15 20:35:45.832  5097  5097 W VideoCapabilities: Unsupported mime video/mpeg2
,03-15 20:35:45.861  5097  5097 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-15 20:35:45.877  5097  5097 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-15 20:35:45.879  5097  5097 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 20:35:45.884  5097  5097 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 20:35:45.894  5097  5097 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 20:35:45.961   885  1222 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5146 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
03-15 20:35:45.962   885  1222 I ActivityManager: Killing 4841:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-15 20:35:46.094  5125  5143 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-15 20:35:46.099   885  1557 W libprocessgroup: failed to open /acct/uid_10019/pid_4841/cgroup.procs: No such file or directory
,03-15 20:35:46.105   885  1256 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-15 20:35:46.109  5097  5097 I vclib   : onServiceConnected
03-15 20:35:46.110  5097  5097 W Babel   : Attempted to change video mute state without an active call.
,03-15 20:35:46.141  5146  5146 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-15 20:35:46.141  5146  5146 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,03-15 20:35:46.141  5146  5146 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 20:35:46.141  5146  5146 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-15 20:35:46.149  5097  5097 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 20:35:46.149  5097  5097 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 20:35:46.206  5097  5097 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 20:35:46.279  5097  5112 W art     : Suspending all threads took: 13.626ms
,03-15 20:35:46.298  4906  5166 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-15 20:35:46.307  1576  1576 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a98df7b new=com.google.android.velvet.VelvetApplication@a98df7b
,03-15 20:35:46.316  5097  5097 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-15 20:35:46.316  5097  5097 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 20:35:46.344  1962  5172 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-15 20:35:46.349  1962  5172 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-15 20:35:46.367   885   901 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5173 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:46.414  1962  5172 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-15 20:35:46.453  1962  2031 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-15 20:35:46.510  5173  5173 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 20:35:46.597  4906  5166 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 296 ms] updated apps [took 296 ms] 
,03-15 20:35:46.601   885  1512 I ActivityManager: Killing 5023:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-15 20:35:46.681   885   901 W libprocessgroup: failed to open /acct/uid_10005/pid_5023/cgroup.procs: No such file or directory
,03-15 20:35:46.726  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 20:35:46.727  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:35:46.904  4959  5096 W jxcore-log: Initializing JXcore engine
03-15 20:35:46.904  4959  5096 W jxcore-log: JXcore engine is ready
,03-15 20:35:46.964  5096  5096 W Thread-555: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[6527]" dev="sockfs" ino=6527 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-15 20:35:46.964  5096  5096 W Thread-555: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-15 20:35:46.964  5096  5096 W Thread-555: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[6684]" dev="sockfs" ino=6684 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-15 20:35:46.964  5096  5096 W Thread-555: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[22997]" dev="sockfs" ino=22997 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-15 20:35:46.994  4959  5096 W jxcore-log: Starting JXcore engine
,03-15 20:35:47.089   885  1222 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5202 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:47.157  4959  5096 W jxcore-log: Platform android
03-15 20:35:47.157  4959  5096 W jxcore-log: 
03-15 20:35:47.157  4959  5096 W jxcore-log: Process ARCH arm
03-15 20:35:47.157  4959  5096 W jxcore-log: 
,03-15 20:35:47.166   885   900 I ActivityManager: Killing 4818:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-15 20:35:47.241   885  1222 W libprocessgroup: failed to open /acct/uid_10088/pid_4818/cgroup.procs: No such file or directory
,03-15 20:35:47.421  5202  5202 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-15 20:35:47.568  5202  5202 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-15 20:35:47.588  5202  5202 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 20:35:47.589  5202  5202 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 20:35:47.638  5202  5202 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-15 20:35:47.638  5202  5202 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-15 20:35:47.643  5202  5244 D Ads     : Skipping gmscore version check
,03-15 20:35:47.654   885  1558 I ActivityManager: Killing 5073:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-15 20:35:47.740  1962  2031 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-15 20:35:47.793  4959  5096 I jxcore-log: JXcore Cordova bridge is ready!
03-15 20:35:47.793  4959  5096 I jxcore-log: 
03-15 20:35:47.794  4959  5096 W jxcore-log: JXcore engine is started
,03-15 20:35:47.796   885  3197 W libprocessgroup: failed to open /acct/uid_10035/pid_5073/cgroup.procs: No such file or directory
,03-15 20:35:47.803  4959  5060 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-15 20:35:47.820  4959  5096 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-15 20:35:47.820  4959  5096 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-15 20:35:47.831  4959  4959 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-15 20:35:47.834   885  1507 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5249 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:47.866  1962  2031 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,03-15 20:35:47.879   885  1301 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5266 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:47.883  1962  2031 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-15 20:35:47.907  1484  3885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-15 20:35:47.908  4959  5060 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 77ms. Plugin should use CordovaInterface.getThreadPool().
,03-15 20:35:47.925  1484  3885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-15 20:35:47.938  5202  5202 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-15 20:35:47.944  2580  2580 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-15 20:35:47.945  5266  5266 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-15 20:35:47.947  2580  2580 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-15 20:35:47.948  2580  2580 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-15 20:35:47.950  2580  2580 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-15 20:35:47.952  2580  2580 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-15 20:35:47.985  5202  5202 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-15 20:35:47.998  5266  5266 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@26121303(com.android.providers.calendar.CalendarProvider2@2ecf3280)
,03-15 20:35:48.043  5249  5291 I Gmail   : getAccountsCursor
03-15 20:35:48.043  5249  5292 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-15 20:35:48.085   885  1486 I art     : Explicit concurrent mark sweep GC freed 17698(893KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 1.809ms total 130.187ms
,03-15 20:35:48.086  2580  2580 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-15 20:35:48.087  2580  2580 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-15 20:35:48.088  2580  2580 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-15 20:35:48.118   885  1507 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5294 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:48.162  1423  1423 I Keyboard.Facilitator: onFinishInput()
,03-15 20:35:48.166  4959  4959 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-15 20:35:48.193   885  1112 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,9017,
03-15 20:35:48.193   885  1112 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,5685 (total)
,03-15 20:35:48.209   885  1599 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-15 20:35:48.221  5294  5294 I Exchange: EasService.onCreate
,03-15 20:35:48.222  5249  5315 I Gmail   : Observing account changes for notifications
,03-15 20:35:48.232  5294  5317 I Exchange: RestartPingTask
,03-15 20:35:48.246  5249  5249 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-15 20:35:48.252  5294  5294 I Exchange: RestartPingsTask did not start any pings.
03-15 20:35:48.252  5294  5294 I Exchange: PSS stopIfIdle
03-15 20:35:48.252  5294  5294 I Exchange: PSS has no active accounts; stopping service.
,03-15 20:35:48.317  5249  5322 I Gmail   : getAccountsCursor
,03-15 20:35:48.321  5294  5294 I Exchange: onDestroy
03-15 20:35:48.322   885  1301 I ActivityManager: Killing 5146:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-15 20:35:48.353   885  1486 W libprocessgroup: failed to open /acct/uid_10027/pid_5146/cgroup.procs: No such file or directory
,03-15 20:35:48.476  2580  2580 D 3CDM.DeviceAdminSetupReceiver: received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,03-15 20:35:48.478  2580  2580 D 3CDM.DeviceAdminSetupReceiver: time to show notification
,03-15 20:35:48.497   885   901 I ActivityManager: Killing 4906:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-15 20:35:48.532  5249  5331 E SQLiteLog: (283) recovered 32 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-15 20:35:48.545   885   900 W libprocessgroup: failed to open /acct/uid_10039/pid_4906/cgroup.procs: No such file or directory
,03-15 20:35:48.551  1293  1849 W ResourcesManager: Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,03-15 20:35:48.563   885  1226 V AlarmManager: send {3803a772, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,03-15 20:35:48.606   885  1644 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5334 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-15 20:35:48.680  1293  1293 E ActivatableNotificationView:  oops Width=0 ActualHeight=128
03-15 20:35:48.680  5249  5332 I Gmail   : notifyAccountChanged
,03-15 20:35:48.687  5249  5291 I Gmail   : getAccountsCursor
,03-15 20:35:48.688  5249  5332 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 20:35:48.700  5249  5332 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 20:35:48.712  5249  5332 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 20:35:48.714  5249  5332 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 20:35:48.741   885  1557 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5356 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:48.754   885  1222 I ActivityManager: Killing 5173:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-15 20:35:48.787   885  1512 W libprocessgroup: failed to open /acct/uid_10090/pid_5173/cgroup.procs: No such file or directory
,03-15 20:35:48.788  1715  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:35:48.789  1715  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:35:48.824  5356  5356 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,03-15 20:35:48.824  5356  5356 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,03-15 20:35:48.828  5356  5356 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 20:35:48.828  5356  5356 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-15 20:35:48.922   885  1507 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5377 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-15 20:35:48.933  5249  5292 I Gmail   : getAccountsCursor
,03-15 20:35:48.935   885   901 I ActivityManager: Killing 5202:com.android.vending/u0a32 (adj 15): empty #7
,03-15 20:35:48.944   281   281 I SFPerfTracer:      triggers: (rate: 15:429) (compose: 0:1) (post: 0:1) (render: 0:2) (17:1006 frames) (18:1107)
03-15 20:35:48.944   281   281 D SFPerfTracer:        layers: (4:11) (FocusedStackFrame (0xb7557738): 0:17)* (DimLayer (0xb74eb528): 0:7) (StatusBar (0xb7548938): 13:152) (NavigationBar (0xb755f540): 0:46) (com.android.systemui.ImageWallpaper (0xb7561930): 0:6)* (Starting com.test.thalitest (0xb7538008): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7543f48): 1:86)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7538008): 18:29) 
,03-15 20:35:48.976   885  1093 I ActivityManager: Killing 3854:com.google.process.gapps/u0a16 (adj 15): empty #7
,03-15 20:35:49.007   885   900 W libprocessgroup: failed to open /acct/uid_10016/pid_3854/cgroup.procs: No such file or directory
,03-15 20:35:49.013   885  1222 W libprocessgroup: failed to open /acct/uid_10032/pid_5202/cgroup.procs: No such file or directory
,03-15 20:35:49.027  5266  5266 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-15 20:35:49.027  5266  5266 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-15 20:35:49.030   885  1482 I ActivityManager: Killing 5294:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-15 20:35:49.081   885  1644 W libprocessgroup: failed to open /acct/uid_10060/pid_5294/cgroup.procs: No such file or directory
,03-15 20:35:49.095  4959  4959 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@e7c6e37 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 20:35:49.095  4959  4959 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@e7c6e37 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-15 20:35:49.095  4959  4959 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 20:35:49.098  4959  4959 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@347a9f36 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 20:35:49.098  4959  4959 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@347a9f36 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-15 20:35:49.098  4959  4959 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 20:35:49.123  1962  5172 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-15 20:35:49.144  1962  5172 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-15 20:35:49.236  1962  1962 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,03-15 20:35:49.357   885   901 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5401 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-15 20:35:49.426  5377  5394 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-15 20:35:49.449  1962  1962 D AsyncTaskServiceImpl: Submit a task: k
,03-15 20:35:49.456  5401  5401 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,03-15 20:35:49.475  1962  5426 D k       : Processing package: com.test.thalitest
,03-15 20:35:49.495  1962  5426 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
03-15 20:35:49.495  1962  5426 D k       : Found info for package com.test.thalitest in db.
,03-15 20:35:49.548   305   385 I ThermalEngine: Sensor:xo_therm_pu2:38000 mC
,03-15 20:35:49.548   885  1558 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5430 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-15 20:35:49.569   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 20.119ms
,03-15 20:35:49.589   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 18.875ms
,03-15 20:35:49.611   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 21.391ms
,03-15 20:35:49.628  5401  5401 I GoogleHttpClient: GMS http client unavailable, use old client
,03-15 20:35:49.651  5401  5401 I GoogleHttpClient: GMS http client unavailable, use old client
,03-15 20:35:49.675   885  1599 I ActivityManager: Killing 5249:com.google.android.gm/u0a63 (adj 15): empty #7
,03-15 20:35:49.731   885  1222 W libprocessgroup: failed to open /acct/uid_10063/pid_5249/cgroup.procs: No such file or directory
,03-15 20:35:49.738  1962  5425 W BaseAppContext: Using Auth Proxy for data requests.
03-15 20:35:49.738  1962  5425 W BaseAppContext: Using Auth Proxy for data requests.
,03-15 20:35:49.739   885  1486 I ActivityManager: Killing 3085:com.google.android.calendar/u0a49 (adj 15): empty #7
,03-15 20:35:49.784   885  1512 W libprocessgroup: failed to open /acct/uid_10049/pid_3085/cgroup.procs: No such file or directory
03-15 20:35:49.784  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 20:35:49.785  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:35:49.789  1962  5425 W BaseAppContext: Using Auth Proxy for data requests.
,03-15 20:35:49.800  1962  5425 W BaseAppContext: Using Auth Proxy for data requests.
,03-15 20:35:49.818  1962  5425 W BaseAppContext: Using Auth Proxy for data requests.
,03-15 20:35:50.047  5377  5394 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 619 ms] updated apps [took 619 ms] 
,03-15 20:35:50.050   885  1512 I ActivityManager: Killing 5266:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-15 20:35:50.151   885  1528 W libprocessgroup: failed to open /acct/uid_10005/pid_5266/cgroup.procs: No such file or directory
,03-15 20:35:50.190  1962  5422 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,03-15 20:35:50.303  1962  5425 I art     : Explicit concurrent mark sweep GC freed 46944(3MB) AllocSpace objects, 11(176KB) LOS objects, 24% free, 14MB/19MB, paused 1.369ms total 127.682ms
,03-15 20:35:50.320   885  1301 I art     : Explicit concurrent mark sweep GC freed 12023(581KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.801ms total 131.210ms
,03-15 20:35:50.422  5430  5430 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-15 20:35:50.422  5430  5430 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-15 20:35:50.422  5430  5430 I GAv4    :   adb logcat -s GAv4
,03-15 20:35:50.435  5430  5430 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-15 20:35:50.455  5430  5430 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-15 20:35:50.461  5430  5468 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-15 20:35:50.477  5430  5430 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-15 20:35:50.650   280   397 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
03-15 20:35:50.650   280   397 W Vold    : Returning OperationFailed - no handler for errno 0
03-15 20:35:50.650  5430  5474 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,03-15 20:35:50.663  1962  5425 W art     : Verification of boolean com.google.android.gms.games.broker.VideoAgent.handleMessage(android.os.Message) took 151.450ms
,03-15 20:35:50.664  1962  2031 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-15 20:35:50.683  5430  5475 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 20:35:50.684  5430  5475 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 20:35:50.701   885  1507 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5478 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:50.703   885  1507 I ActivityManager: Killing 5125:android.process.acore/u0a7 (adj 15): empty #7
,03-15 20:35:50.733  1962  2031 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-15 20:35:50.802   885  1644 W libprocessgroup: failed to open /acct/uid_10007/pid_5125/cgroup.procs: No such file or directory
,03-15 20:35:50.825  5478  5478 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 20:35:50.856  5430  5475 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 20:35:50.925  5430  5475 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 20:35:50.925  5430  5475 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 20:35:50.947   885  1226 V AlarmManager: send {3ee9d479, *alarm*:com.android.server.WifiManager.action.START_SCAN}
03-15 20:35:50.947   885  1226 V AlarmManager: send {21168394, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,03-15 20:35:51.051  1962  2031 I Icing   : Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,03-15 20:35:51.071   885  1558 I ActivityManager: Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5504 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-15 20:35:51.171   885  1599 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5526 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:51.200  5504  5525 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-15 20:35:51.212   885   900 I ActivityManager: Killing 5334:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-15 20:35:51.292   885   901 W libprocessgroup: failed to open /acct/uid_10019/pid_5334/cgroup.procs: No such file or directory
,03-15 20:35:51.312  1962  2031 I Icing   : Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,03-15 20:35:51.314   885  1644 I ActivityManager: Killing 5356:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-15 20:35:51.372   885  1557 W libprocessgroup: failed to open /acct/uid_10027/pid_5356/cgroup.procs: No such file or directory
,03-15 20:35:51.437  5526  5526 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-15 20:35:51.462   885  1226 V AlarmManager: send {a6af0df, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,03-15 20:35:51.463   885   885 V AlarmManager: done {a6af0df, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [3ms]
,03-15 20:35:51.556  5526  5526 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-15 20:35:51.570  5526  5526 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 20:35:51.571  5526  5526 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 20:35:51.625  5526  5572 D Ads     : Skipping gmscore version check
,03-15 20:35:51.653   885  1644 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5573 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-15 20:35:51.662  5526  5526 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-15 20:35:51.681  5526  5526 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-15 20:35:51.681  5526  5526 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-15 20:35:51.686   885  1557 I ActivityManager: Killing 5097:com.google.android.talk/u0a70 (adj 15): empty #7
,03-15 20:35:51.688  1715  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:35:51.689  1715  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:35:51.694  5573  5573 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-15 20:35:51.742   885  1482 W libprocessgroup: failed to open /acct/uid_10070/pid_5097/cgroup.procs: No such file or directory
,03-15 20:35:51.747  5526  5526 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-15 20:35:51.758  5526  5526 D Finsky  : [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,03-15 20:35:51.785   885   900 I ActivityManager: Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=5601 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:51.795   885  1644 I ActivityManager: Killing 4959:com.test.thalitest/u0a109 (adj 15): empty #7
,03-15 20:35:51.818  5526  5526 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-15 20:35:51.835   885  1240 D WifiService: Client connection lost with reason: 4
,03-15 20:35:51.877   885  1144 W PackageSettings: Skipping PackageSetting{2d86e91 com.example.hello/10568} due to missing metadata
,03-15 20:35:52.008   885  1486 W libprocessgroup: failed to open /acct/uid_10109/pid_4959/cgroup.procs: No such file or directory
,03-15 20:35:52.019   885  1256 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
,03-15 20:35:52.120  5601  5601 E SQLiteLog: (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,03-15 20:35:52.183   885  1482 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5627 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:52.224  5627  5627 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-15 20:35:52.257  5601  5601 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,03-15 20:35:52.267  5627  5627 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@26121303(com.android.providers.calendar.CalendarProvider2@2ecf3280)
,03-15 20:35:52.304   885  1557 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5649 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-15 20:35:52.398  5649  5649 D PhoneMonitor: Register our PhoneStateListener
,03-15 20:35:52.408   885  1507 I ActivityManager: Killing 5377:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-15 20:35:52.432   885   900 W libprocessgroup: failed to open /acct/uid_10039/pid_5377/cgroup.procs: No such file or directory
,03-15 20:35:52.449  1962  5667 I CheckinService: Checking schedule, now: 1458070552448 next: 1458070566803
03-15 20:35:52.449  1962  5667 I CheckinService: active receiver: disabled
,03-15 20:35:52.450  1715  3300 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-15 20:35:52.567   885  1222 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5669 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:52.666  5669  5688 I Gmail   : getAccountsCursor
03-15 20:35:52.667  5669  5689 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-15 20:35:52.738   885  1644 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5694 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:52.747  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:35:52.747  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:35:52.819  5669  5669 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-15 20:35:52.827  5694  5694 I Exchange: EasService.onCreate
,03-15 20:35:52.832   885  1482 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-15 20:35:52.841  5694  5717 I Exchange: RestartPingTask
,03-15 20:35:52.853  5526  5554 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-15 20:35:52.853  5526  5554 I qtaguid : Untagging socket 37 failed errno=-22
03-15 20:35:52.853  5526  5554 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-15 20:35:52.855  5669  5716 I Gmail   : Observing account changes for notifications
,03-15 20:35:52.858  5526  5526 D Finsky  : [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,03-15 20:35:52.866  5694  5694 I Exchange: RestartPingsTask did not start any pings.
03-15 20:35:52.866  5694  5694 I Exchange: PSS stopIfIdle
03-15 20:35:52.866  5694  5694 I Exchange: PSS has no active accounts; stopping service.
,03-15 20:35:52.908  5669  5721 I Gmail   : getAccountsCursor
,03-15 20:35:53.028   885  1486 I art     : Explicit concurrent mark sweep GC freed 15214(999KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 1.380ms total 121.585ms
,03-15 20:35:53.042  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:35:53.077   885  1222 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5731 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-15 20:35:53.126  5694  5694 I Exchange: onDestroy
,03-15 20:35:53.127   885  3197 I ActivityManager: Killing 5430:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,03-15 20:35:53.160   885  1482 W libprocessgroup: failed to open /acct/uid_10057/pid_5430/cgroup.procs: No such file or directory
,03-15 20:35:53.185   885  1222 I ActivityManager: Killing 5478:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-15 20:35:53.189  5731  5731 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 20:35:53.190  5731  5731 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 20:35:53.195  5669  5753 E SQLiteLog: (283) recovered 33 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-15 20:35:53.233  5731  5731 I MultiDex: VM with version 2.1.0 has multidex support
03-15 20:35:53.233  5731  5731 I MultiDex: install
03-15 20:35:53.233  5731  5731 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-15 20:35:53.256  5669  5755 I Gmail   : notifyAccountChanged
,03-15 20:35:53.257  5669  5688 I Gmail   : getAccountsCursor
,03-15 20:35:53.259  5669  5755 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 20:35:53.263  5669  5755 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 20:35:53.269  5669  5755 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 20:35:53.270  5669  5755 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 20:35:53.273   885  1486 W libprocessgroup: failed to open /acct/uid_10090/pid_5478/cgroup.procs: No such file or directory
,03-15 20:35:53.274   885   885 V AlarmManager: done {3803a772, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [4727ms]
,03-15 20:35:53.280  5627  5763 E SQLiteLog: (284) automatic index on view_events(_id)
,03-15 20:35:53.295   885   885 V AlarmManager: done {3ee9d479, *alarm*:com.android.server.WifiManager.action.START_SCAN} [2348ms]
,03-15 20:35:53.296   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.31 rxSuccessRate=8.63 targetRoamBSSID=any RSSI=-48
03-15 20:35:53.296   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=27583 interval=30000 maxinterval=300000
03-15 20:35:53.296   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
,03-15 20:35:53.297   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
,03-15 20:35:53.297   885  1237 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-15 20:35:53.298  1412  1412 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-15 20:35:53.298   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-15 20:35:53.298   293  1649 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-15 20:35:53.299   885  1237 E WifiStateMachine: [1,458,070,553,299 ms] noteScanstart no scan source
,03-15 20:35:53.302   885   885 V AlarmManager: done {21168394, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [2356ms]
,03-15 20:35:53.307  5731  5731 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 20:35:53.332  1715  3936 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-15 20:35:53.352   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-15 20:35:53.352   293  1649 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-15 20:35:53.352   490   509 D TCMD    : NL - Read 56 bytes from update socket.
03-15 20:35:53.352   490   509 D TCMD    : NL - message type is RTM_NEWLINK
03-15 20:35:53.352   490   509 D TCMD    : Listening for incoming client connection request
,03-15 20:35:53.354   885  1237 E WifiStateMachine: [1,458,070,553,354 ms] noteScanEnd no scan source
,03-15 20:35:53.361   885  1237 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@27cf02d2 sup_state=COMPLETED debouncing=false
,03-15 20:35:53.367  5627  5627 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-15 20:35:53.368  5627  5627 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-15 20:35:53.388  5731  5731 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-15 20:35:53.388  5731  5731 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16c978c2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 20:35:53.389  5731  5731 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 20:35:53.408  5731  5731 D ChimeraCfgMgr: Reading stored module config
,03-15 20:35:53.412  1715  1715 D WearableService: callingUid 10016, callindPid: 1715
,03-15 20:35:53.419  1715  4783 E MDM     : [212] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-15 20:35:53.420  1715  1715 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 20:35:53.421  1962  5775 D LocationInitializer: Restart initialization of location
,03-15 20:35:53.432  1715  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:35:53.458  1715  1988 W GCoreFlp: No location to return for getLastLocation()
03-15 20:35:53.459  1715  5776 W FusedLocationProvider: location=null
,03-15 20:35:53.463  5526  5553 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-15 20:35:53.463  5526  5553 I qtaguid : Untagging socket 37 failed errno=-22
03-15 20:35:53.464  5526  5553 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-15 20:35:53.471  5669  5724 I Gmail   : getAccountsCursor
,03-15 20:35:53.601  5731  5774 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-15 20:35:53.605  5731  5731 D CAR.SERVICE: Connecting to CarCallService...
,03-15 20:35:53.628  5731  5731 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-15 20:35:53.629  5731  5731 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-15 20:35:53.674  5731  5731 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-15 20:35:53.675   885   901 I ActivityManager: Killing 5504:android.process.acore/u0a7 (adj 15): empty #7
,03-15 20:35:53.801   885  1482 W libprocessgroup: failed to open /acct/uid_10007/pid_5504/cgroup.procs: No such file or directory
,03-15 20:35:53.814  5731  5731 D CAR.TEL.Service: Creating a new CarCallService.
03-15 20:35:53.816  5731  5731 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
03-15 20:35:53.817   885  1222 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-15 20:35:53.817  5731  5731 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@1982a7be
03-15 20:35:53.818   885   901 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-15 20:35:53.818  5731  5731 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-15 20:35:53.818  5731  5731 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-15 20:35:53.892  5731  5750 D CAR.SERVICE: Package validated; name: com.android.vending
,03-15 20:35:53.918  5526  5526 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,03-15 20:35:54.594  5526  5554 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-15 20:35:54.594  5526  5554 I qtaguid : Untagging socket 37 failed errno=-22
03-15 20:35:54.594  5526  5554 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-15 20:35:54.660   885  1222 W ActivityManager: getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,03-15 20:35:54.704  5526  5526 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 20:35:54.704  5526  5526 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 20:35:54.860  5526  5526 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 20:35:54.884  5526  5526 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,03-15 20:35:54.896   885  1226 V AlarmManager: send {1c4d6cb9, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,03-15 20:35:54.922   885   885 V AlarmManager: done {1c4d6cb9, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [26ms]
,03-15 20:35:54.927  1715  1733 D DeviceConnectionService: client connected with version: 8296000
,03-15 20:35:54.934  5526  5803 D Finsky  : [649] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-15 20:35:54.955  5526  5526 D Finsky  : [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-15 20:35:54.955  5526  5526 D Finsky  : [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,03-15 20:35:55.422   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=337, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311759, SEQNUM=4367, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-161, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 20:35:55.460  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:35:55.485   885  1507 I ActivityManager: Killing 5649:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-15 20:35:55.501   885  1507 I ActivityManager: Killing 5694:com.google.android.gm.exchange/u0a60 (adj 15): empty #8
,03-15 20:35:55.535   885  3197 W libprocessgroup: failed to open /acct/uid_10035/pid_5649/cgroup.procs: No such file or directory
,03-15 20:35:55.537   885   901 W libprocessgroup: failed to open /acct/uid_10060/pid_5694/cgroup.procs: No such file or directory
,03-15 20:35:55.761  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:35:55.762  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:35:56.802   885  1226 V AlarmManager: send {1782f9f1, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-15 20:35:56.807   885   885 V AlarmManager: done {1782f9f1, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,03-15 20:35:57.045  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:35:57.164  5601  5626 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,03-15 20:35:57.179  5601  5626 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-15 20:35:57.843  5669  5713 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-15 20:35:58.050  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:35:58.777  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:35:58.777  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:35:58.933  5731  5731 D CAR.SERVICE: mConnectedToCar = false, abort
,03-15 20:35:58.950  5731  5731 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2b8741e6 that was originally bound here
03-15 20:35:58.950  5731  5731 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2b8741e6 that was originally bound here
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-15 20:35:58.950  5731  5731 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,03-15 20:35:58.956  5731  5731 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@194d3e79 that was originally bound here
03-15 20:35:58.956  5731  5731 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@194d3e79 that was originally bound here
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-15 20:35:58.956  5731  5731 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,03-15 20:35:58.958   885  1301 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@11911ef3
,03-15 20:35:59.052  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:35:59.552   305   385 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-15 20:36:00.000   885  1226 V AlarmManager: send {24d726cd, *alarm*:android.intent.action.TIME_TICK}
,03-15 20:36:00.030   885   885 V AlarmManager: done {24d726cd, *alarm*:android.intent.action.TIME_TICK} [29ms]
,03-15 20:36:01.791  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:01.791  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:02.025   281   723 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:319 vsyncs) (1:1137)
,03-15 20:36:04.806  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:04.807  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:07.239   885  1093 I ActivityManager: Waited long enough for: ServiceRecord{20785348 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,03-15 20:36:07.823  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:07.824  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:08.056  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:09.057  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:09.060   885  1226 V AlarmManager: send {152a67b0, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,03-15 20:36:09.074   885  1226 V AlarmManager: send {2007dae, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,03-15 20:36:09.076   885  1226 V AlarmManager: send {3ee9d479, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-15 20:36:09.077   885   885 V AlarmManager: done {2007dae, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [18ms]
,03-15 20:36:09.094   885   885 V AlarmManager: done {152a67b0, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [35ms]
03-15 20:36:09.094   885   885 V AlarmManager: done {3ee9d479, *alarm*:com.android.server.WifiManager.action.START_SCAN} [35ms]
,03-15 20:36:09.096   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.26 rxSuccessRate=3.33 targetRoamBSSID=any RSSI=-48
03-15 20:36:09.096   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=43383 interval=30000 maxinterval=300000
03-15 20:36:09.096   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=43383 interval=30000 maxinterval=300000
03-15 20:36:09.096   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=true
03-15 20:36:09.097   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN bump interval =45000
03-15 20:36:09.097  1412  1412 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-15 20:36:09.098   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-15 20:36:09.098   293  1649 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-15 20:36:09.100   885  1237 E WifiStateMachine: [1,458,070,569,100 ms] noteScanstart no scan source
,03-15 20:36:09.133  1962  5828 I CheckinService: Checking schedule, now: 1458070569133 next: 1458070566803
03-15 20:36:09.133  1962  5828 I CheckinService: active receiver: enabled
,03-15 20:36:09.146  1962  5828 I CheckinService: Preparing to send checkin request
03-15 20:36:09.146  1962  5828 I EventLogService: Accumulating logs since 1458070526934
,03-15 20:36:09.196  1962  5828 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,03-15 20:36:09.197  1962  5828 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-15 20:36:09.266  1715  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:36:09.268  1715  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:36:09.294  5526  5569 D Finsky  : [640] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
03-15 20:36:09.295  5526  5526 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,03-15 20:36:09.346   885  1222 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5838 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-15 20:36:09.368   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.702ms
,03-15 20:36:09.387  5838  5838 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-15 20:36:09.387  5838  5838 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-15 20:36:09.387   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.356ms
,03-15 20:36:09.408   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.212ms
,03-15 20:36:09.425  5838  5838 I MultiDex: VM with version 2.1.0 has multidex support
03-15 20:36:09.426  5838  5838 I MultiDex: install
03-15 20:36:09.426  5838  5838 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-15 20:36:09.443  5838  5838 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 20:36:09.498  5838  5838 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 20:36:09.498  5838  5838 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16c978c2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 20:36:09.498  5838  5838 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 20:36:09.524  1715  1715 D WearableService: callingUid 10016, callindPid: 1715
,03-15 20:36:09.527  1962  5860 D LocationInitializer: Restart initialization of location
,03-15 20:36:09.529  1715  1715 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 20:36:09.532  1715  2369 E MDM     : [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-15 20:36:09.541  1715  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:36:09.557   305   385 I ThermalEngine: Sensor:xo_therm_pu2:35000 mC
,03-15 20:36:09.558  1715  1988 W GCoreFlp: No location to return for getLastLocation()
,03-15 20:36:09.559  1715  5861 W FusedLocationProvider: location=null
,03-15 20:36:09.564   490   509 D TCMD    : NL - Read 56 bytes from update socket.
03-15 20:36:09.564   490   509 D TCMD    : NL - message type is RTM_NEWLINK
03-15 20:36:09.564   490   509 D TCMD    : Listening for incoming client connection request
03-15 20:36:09.564   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
03-15 20:36:09.564   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 4
03-15 20:36:09.564   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
03-15 20:36:09.564   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 3
,03-15 20:36:09.564   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:09.564   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-15 20:36:09.564   293  1649 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS ,
03-15 20:36:09.565   885  1237 E WifiStateMachine: [1,458,070,569,565 ms] noteScanEnd no scan source
,03-15 20:36:09.568   885  1237 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@27cf02d2 sup_state=COMPLETED debouncing=false
,03-15 20:36:09.579  5838  5838 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-15 20:36:09.579  5838  5838 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-15 20:36:09.652  5838  5859 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-15 20:36:09.784   295   295 D WVCdm   : Instantiating CDM.
,03-15 20:36:09.789   295  1400 I WVCdm   : CdmEngine::OpenSession
03-15 20:36:09.789   295  1400 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,03-15 20:36:09.805   295  1400 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,03-15 20:36:09.841   295  1400 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
03-15 20:36:09.842   295  1400 D DrmWidevineDash: Service_Initialize: starts!
03-15 20:36:09.842   295  1400 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,03-15 20:36:09.842   295  1400 D QSEECOMAPI: : App is not loaded in QSEE
03-15 20:36:09.842   295  1400 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-15 20:36:09.842   295  1400 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-15 20:36:09.842   295  1400 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-15 20:36:09.842   295  1400 D QSEECOMAPI: : App is not loaded in QSEE
03-15 20:36:09.842   295  1400 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-15 20:36:09.842   295  1400 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-15 20:36:09.842   295  1400 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-15 20:36:09.842   295  1400 D QSEECOMAPI: : App is not loaded in QSEE
,03-15 20:36:09.871   295  1400 D QSEECOMAPI: : Loaded image: APP id = 3
,03-15 20:36:09.873   295  1400 D DrmWidevineDash: Service_Initialize: ends! returns 0
03-15 20:36:09.873   295  1400 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500d000
03-15 20:36:09.873   295  1400 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500d000
,03-15 20:36:09.881   295  1400 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
03-15 20:36:09.881   295  1400 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,03-15 20:36:09.881   295  1400 D DrmWidevineDash: hlos api version =  9
03-15 20:36:09.881   295  1400 D DrmWidevineDash: tz api version =  8
03-15 20:36:09.881   295  1400 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-15 20:36:09.881   295  1400 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,03-15 20:36:09.889   295  1400 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,03-15 20:36:09.889   295  1400 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-15 20:36:09.889   295  1400 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb13fe960
03-15 20:36:09.889   295  1400 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-15 20:36:09.889   295  1400 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-15 20:36:09.889   295  1400 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb8fb0db0, dataLength=8
,03-15 20:36:09.890   295  1400 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,03-15 20:36:09.892   295  1400 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb9029828, wrapped_rsa_key_length=1280
,03-15 20:36:09.895   295  1400 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,03-15 20:36:09.895   295  1400 I WVCdm   : CdmEngine::QueryKeyControlInfo
03-15 20:36:09.895   295   984 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-15 20:36:09.895   295   984 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-15 20:36:09.895   295   984 I WVCdm   : CdmEngine::GenerateKeyRequest
03-15 20:36:09.896   295   984 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb90f5a88, idLength=0xb54e8730
,03-15 20:36:09.906   295   984 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-15 20:36:09.906   295   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-15 20:36:09.906   295   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-15 20:36:09.906   295   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
03-15 20:36:09.906   295   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-15 20:36:09.906   295   984 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
03-15 20:36:09.906   295   984 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
03-15 20:36:09.906   295   984 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-15 20:36:09.907   295   984 D DrmWidevineDash: hlos api version =  9
03-15 20:36:09.907   295   984 D DrmWidevineDash: tz api version =  8
03-15 20:36:09.907   295   984 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-15 20:36:09.907   295   984 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
03-15 20:36:09.907   295   984 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-15 20:36:09.907   295   984 D WVCdm   : PrepareKeyRequest: nonce=1677736264
03-15 20:36:09.907   295   984 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb9017f50
03-15 20:36:09.907   295   984 D DrmWidevineDash: message_length=1591, signature=0xb9030de8, signature_length=3041822484
,03-15 20:36:10.101   295   984 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,03-15 20:36:10.102   295   983 I WVCdm   : CdmEngine::CloseSession
03-15 20:36:10.102   295   983 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-15 20:36:10.102   295   983 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-15 20:36:10.102   295   983 I WVCdm   : L3 Terminate.
03-15 20:36:10.102   295   983 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,03-15 20:36:10.103   295   983 D DrmWidevineDash: Service_Uninitialize: starts!
03-15 20:36:10.103   295   983 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-15 20:36:10.103   295   983 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,03-15 20:36:10.103   295   983 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-15 20:36:10.103   295   983 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-15 20:36:10.207   295  1400 I WVCdm   : CdmEngine::OpenSession
03-15 20:36:10.207   295  1400 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
03-15 20:36:10.209   295  1400 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,03-15 20:36:10.234   295  1400 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,03-15 20:36:10.234   295  1400 D DrmWidevineDash: Service_Initialize: starts!
03-15 20:36:10.234   295  1400 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-15 20:36:10.234   295  1400 D QSEECOMAPI: : App is not loaded in QSEE
03-15 20:36:10.235   295  1400 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-15 20:36:10.235   295  1400 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-15 20:36:10.235   295  1400 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-15 20:36:10.235   295  1400 D QSEECOMAPI: : App is not loaded in QSEE
03-15 20:36:10.235   295  1400 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-15 20:36:10.235   295  1400 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-15 20:36:10.235   295  1400 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-15 20:36:10.235   295  1400 D QSEECOMAPI: : App is not loaded in QSEE
,03-15 20:36:10.265   295  1400 D QSEECOMAPI: : Loaded image: APP id = 3
,03-15 20:36:10.265   295  1400 D DrmWidevineDash: Service_Initialize: ends! returns 0
03-15 20:36:10.265   295  1400 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500d000
03-15 20:36:10.265   295  1400 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500d000
,03-15 20:36:10.270   295  1400 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,03-15 20:36:10.270   295  1400 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-15 20:36:10.271   295  1400 D DrmWidevineDash: hlos api version =  9
,03-15 20:36:10.272   295  1400 D DrmWidevineDash: tz api version =  8
,03-15 20:36:10.272   295  1400 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-15 20:36:10.272   295  1400 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,03-15 20:36:10.279   295  1400 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,03-15 20:36:10.279   295  1400 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-15 20:36:10.279   295  1400 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb13fe960
03-15 20:36:10.279   295  1400 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-15 20:36:10.279   295  1400 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-15 20:36:10.279   295  1400 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb902c878, dataLength=8
03-15 20:36:10.279   295  1400 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,03-15 20:36:10.280   295  1400 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb90ed660, wrapped_rsa_key_length=1280
,03-15 20:36:10.283   295  1400 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,03-15 20:36:10.283   295  1400 I WVCdm   : CdmEngine::QueryKeyControlInfo
,03-15 20:36:10.285   295   295 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-15 20:36:10.285   295   295 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-15 20:36:10.285   295   295 I WVCdm   : CdmEngine::GenerateKeyRequest
,03-15 20:36:10.285   295   295 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb90f5aa8, idLength=0xbe8472b0
,03-15 20:36:10.292   295   295 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-15 20:36:10.292   295   295 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-15 20:36:10.292   295   295 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-15 20:36:10.292   295   295 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
03-15 20:36:10.293   295   295 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-15 20:36:10.293   295   295 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
03-15 20:36:10.293   295   295 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
03-15 20:36:10.293   295   295 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-15 20:36:10.293   295   295 D DrmWidevineDash: hlos api version =  9
03-15 20:36:10.293   295   295 D DrmWidevineDash: tz api version =  8
03-15 20:36:10.293   295   295 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-15 20:36:10.293   295   295 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
03-15 20:36:10.293   295   295 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-15 20:36:10.293   295   295 D WVCdm   : PrepareKeyRequest: nonce=2017755880
03-15 20:36:10.293   295   295 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb90186b0
03-15 20:36:10.293   295   295 D DrmWidevineDash: message_length=1622, signature=0xb9018498, signature_length=3196351124
,03-15 20:36:10.481   295   295 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,03-15 20:36:10.482   295  1400 I WVCdm   : CdmEngine::CloseSession
03-15 20:36:10.482   295  1400 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,03-15 20:36:10.483   295  1400 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-15 20:36:10.483   295  1400 I WVCdm   : L3 Terminate.
03-15 20:36:10.483   295  1400 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,03-15 20:36:10.484   295  1400 D DrmWidevineDash: Service_Uninitialize: starts!
03-15 20:36:10.484   295  1400 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-15 20:36:10.484   295  1400 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,03-15 20:36:10.485   295  1400 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,03-15 20:36:10.486   295  1400 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-15 20:36:10.664  5873  5873 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-15 20:36:10.764  5873  5873 I dex2oat : dex2oat took 100.190ms (threads: 4)
,03-15 20:36:10.780  5838  5853 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 20:36:10.780  5838  5853 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 20:36:10.780  5838  5853 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 20:36:10.780  5838  5853 I Adreno-EGL: Local Branch: 
03-15 20:36:10.780  5838  5853 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 20:36:10.780  5838  5853 I Adreno-EGL: Local Patches: NONE
03-15 20:36:10.780  5838  5853 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 20:36:10.835  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:10.835  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:10.885  5838  5853 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 20:36:10.885  5838  5853 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 20:36:10.885  5838  5853 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 20:36:10.885  5838  5853 I Adreno-EGL: Local Branch: 
03-15 20:36:10.885  5838  5853 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 20:36:10.885  5838  5853 I Adreno-EGL: Local Patches: NONE
03-15 20:36:10.885  5838  5853 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 20:36:10.942  5838  5853 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 20:36:10.942  5838  5853 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 20:36:10.942  5838  5853 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 20:36:10.942  5838  5853 I Adreno-EGL: Local Branch: 
03-15 20:36:10.942  5838  5853 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 20:36:10.942  5838  5853 I Adreno-EGL: Local Patches: NONE
03-15 20:36:10.942  5838  5853 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 20:36:10.996  5838  5853 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 20:36:10.996  5838  5853 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 20:36:10.996  5838  5853 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 20:36:10.996  5838  5853 I Adreno-EGL: Local Branch: 
03-15 20:36:10.996  5838  5853 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 20:36:10.996  5838  5853 I Adreno-EGL: Local Patches: NONE
03-15 20:36:10.996  5838  5853 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 20:36:11.403  1962  5828 I CheckinRequestBuilder: Classify the device as Phone.
,03-15 20:36:11.589  1962  5828 I CheckinTask: Sending checkin request (9877 bytes)
,03-15 20:36:12.058  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:12.131  1962  5828 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,03-15 20:36:12.133  1962  5828 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-15 20:36:12.271   885  1301 I art     : Explicit concurrent mark sweep GC freed 29868(1401KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 1.856ms total 124.843ms
,03-15 20:36:12.369  1962  5828 I CheckinRequestBuilder: Classify the device as Phone.
,03-15 20:36:12.402  1962  5828 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,03-15 20:36:12.409  1962  5828 I CheckinService: Checking schedule, now: 1458070572409 next: 1458671709403
03-15 20:36:12.409  1962  5828 I CheckinService: active receiver: disabled
,03-15 20:36:12.418   885  1557 I ActivityManager: Killing 5669:com.google.android.gm/u0a63 (adj 15): empty #7
,03-15 20:36:12.429  1962  1962 D CheckinService: Recording last checkin time for package unspecified as 1458070572428
,03-15 20:36:12.450   885   900 W libprocessgroup: failed to open /acct/uid_10063/pid_5669/cgroup.procs: No such file or directory
,03-15 20:36:12.500   885   901 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5892 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-15 20:36:12.541  5892  5892 D PhoneMonitor: Register our PhoneStateListener
,03-15 20:36:12.555  5892  5892 V SetupWizard: Connected to Gservices successfully
,03-15 20:36:12.558   885  1528 I ActivityManager: Killing 5573:com.motorola.context/u0a8 (adj 15): empty #7
,03-15 20:36:12.575   885  1301 W libprocessgroup: failed to open /acct/uid_10008/pid_5573/cgroup.procs: No such file or directory
,03-15 20:36:12.605  1715  2415 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-15 20:36:13.853  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:13.853  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:14.003  1484  1484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-15 20:36:14.059  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:14.555   885  1507 I ActivityManager: Killing 5601:com.google.android.calendar/u0a49 (adj 13): empty #7
,03-15 20:36:14.611   885  1507 I ActivityManager: Killing 5627:com.android.providers.calendar/u0a5 (adj 15): empty #8
,03-15 20:36:14.692   885   901 W libprocessgroup: failed to open /acct/uid_10049/pid_5601/cgroup.procs: No such file or directory
,03-15 20:36:14.698   885  1512 W libprocessgroup: failed to open /acct/uid_10005/pid_5627/cgroup.procs: No such file or directory
,03-15 20:36:15.371   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=318, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311968, SEQNUM=4382, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-218, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 20:36:15.412  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:36:16.868  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:16.868  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:19.215   885  1228 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-15 20:36:19.290   885  1093 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5932 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-15 20:36:19.389   885   885 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-15 20:36:19.389   885   885 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 20:36:19.395   885   885 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 20:36:19.401   885   885 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 20:36:19.401   885   885 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@15affe83
,03-15 20:36:19.435  1576  1576 I Launcher: Deferring update until onResume
,03-15 20:36:19.491  1715  2089 I art     : Explicit concurrent mark sweep GC freed 30644(1926KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 13MB/23MB, paused 1.076ms total 78.506ms
,03-15 20:36:19.492  1715  1715 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-15 20:36:19.561   305   385 I ThermalEngine: Sensor:xo_therm_pu2:35000 mC
,03-15 20:36:19.695   885  1557 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5971 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-15 20:36:19.738   885  3197 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5988 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-15 20:36:19.739   885  3197 I ActivityManager: Killing 5731:com.google.android.gms:car/u0a16 (adj 15): empty #7
,03-15 20:36:19.773   885  1558 I ActivityManager: Killing 5526:com.android.vending/u0a32 (adj 15): empty #7
,03-15 20:36:19.802   885   901 W libprocessgroup: failed to open /acct/uid_10016/pid_5731/cgroup.procs: No such file or directory
,03-15 20:36:19.807   885  1486 W libprocessgroup: failed to open /acct/uid_10032/pid_5526/cgroup.procs: No such file or directory
,03-15 20:36:19.820  5988  5988 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 20:36:19.874  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 20:36:19.875  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:19.986  5988  6018 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-15 20:36:19.986  5988  6018 I Babel_SMS: MmsConfig.loadMmsSettings
03-15 20:36:19.986  5988  6018 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-15 20:36:19.986  5988  6018 I Babel_SMS: MmsConfig.loadFromDatabase
,03-15 20:36:20.008  5988  6018 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-15 20:36:20.008  5988  6018 I Babel_SMS: MmsConfig.loadFromResources
03-15 20:36:20.009  5988  6018 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-15 20:36:20.010  5988  6018 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-15 20:36:20.062  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:20.081  5988  5988 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-15 20:36:20.085  5988  5988 I Babel_Crash: startup - clean
,03-15 20:36:20.100  5988  6025 I Babel   : deleted: false for 0
,03-15 20:36:20.195   885  1486 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6027 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-15 20:36:20.322  5988  5988 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-15 20:36:20.329  5988  5988 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-15 20:36:20.333  5988  5988 W VideoCapabilities: Unsupported mime video/mpeg2
,03-15 20:36:20.355  5988  5988 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-15 20:36:20.362  5988  5988 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-15 20:36:20.363  5988  5988 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-15 20:36:20.366  5988  5988 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 20:36:20.383  5988  5988 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 20:36:20.457   885  1507 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6053 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
03-15 20:36:20.458   885  1507 I ActivityManager: Killing 5892:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-15 20:36:20.462  6027  6046 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-15 20:36:20.541   885  1482 W libprocessgroup: failed to open /acct/uid_10035/pid_5892/cgroup.procs: No such file or directory
,03-15 20:36:20.548  5988  5988 I vclib   : onServiceConnected
,03-15 20:36:20.549  5988  5988 W Babel   : Attempted to change video mute state without an active call.
,03-15 20:36:20.555  6053  6053 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,03-15 20:36:20.555  6053  6053 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,03-15 20:36:20.556  6053  6053 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 20:36:20.556  6053  6053 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-15 20:36:20.568  5988  5988 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-15 20:36:20.568  5988  5988 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 20:36:20.606  5988  5988 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 20:36:20.609  1576  1576 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a98df7b new=com.google.android.velvet.VelvetApplication@a98df7b
,03-15 20:36:20.610  5932  6074 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-15 20:36:20.622  1962  6078 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-15 20:36:20.622  1962  6078 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-15 20:36:20.657   885  1301 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6080 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-15 20:36:20.674  5988  5988 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 20:36:20.674  5988  5988 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 20:36:20.687  1962  6078 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-15 20:36:20.713  1962  2031 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-15 20:36:20.735  6080  6080 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 20:36:20.740  5932  6074 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 128 ms] updated apps [took 128 ms] 
,03-15 20:36:20.970   885  1486 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6109 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:36:21.021   885  1507 I ActivityManager: Killing 5838:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-15 20:36:21.062  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:21.071   885  1486 W libprocessgroup: failed to open /acct/uid_10016/pid_5838/cgroup.procs: No such file or directory
,03-15 20:36:21.138  6109  6109 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-15 20:36:21.140   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:36:21.140   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:36:21.140   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:36:21.140   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:36:21.140   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,03-15 20:36:21.140   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:36:21.140   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 20:36:21.140   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:36:21.140   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:36:21.140   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:36:21.140   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:36:21.140   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:36:21.140   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:36:21.140   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:36:21.216   885  1528 I art     : Explicit concurrent mark sweep GC freed 21444(1155KB) AllocSpace objects, 2(121KB) LOS objects, 33% free, 21MB/32MB, paused 2.082ms total 124.153ms
,03-15 20:36:21.248  6109  6109 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-15 20:36:21.263  6109  6109 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 20:36:21.265  6109  6109 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 20:36:21.302  6109  6109 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-15 20:36:21.302  6109  6109 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
03-15 20:36:21.303  6109  6152 D Ads     : Skipping gmscore version check
,03-15 20:36:21.306  6109  6109 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-15 20:36:21.322  6109  6109 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-15 20:36:21.325   885  1644 I ActivityManager: Killing 5971:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-15 20:36:21.412   885  1482 W libprocessgroup: failed to open /acct/uid_10019/pid_5971/cgroup.procs: No such file or directory
,03-15 20:36:21.810  1962  2031 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-15 20:36:21.862  1962  2031 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-15 20:36:22.891  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:22.892  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:25.729   885  1644 I ActivityManager: Killing 5988:com.google.android.talk/u0a70 (adj 15): empty #7
,03-15 20:36:25.792   885  1482 W libprocessgroup: failed to open /acct/uid_10070/pid_5988/cgroup.procs: No such file or directory
,03-15 20:36:25.907  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:25.908  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:26.813   885  1226 V AlarmManager: send {1782f9f1, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-15 20:36:26.817   885   885 V AlarmManager: done {1782f9f1, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,03-15 20:36:26.838  1962  6160 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,03-15 20:36:26.846   885  1092 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 195335, reason: UserStart
,03-15 20:36:27.696   885  1222 I ActivityManager: Killing 6053:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-15 20:36:27.726   885  1558 W libprocessgroup: failed to open /acct/uid_10027/pid_6053/cgroup.procs: No such file or directory
,03-15 20:36:28.118   885  1226 V AlarmManager: send {3b7f5abb, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,03-15 20:36:28.125   885  1226 V AlarmManager: send {3ee9d479, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-15 20:36:28.127   885   885 V AlarmManager: done {3b7f5abb, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [10ms]
,03-15 20:36:28.132   885   885 V AlarmManager: done {3ee9d479, *alarm*:com.android.server.WifiManager.action.START_SCAN} [15ms]
,03-15 20:36:28.131   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.00 rxSuccessRate=0.65 targetRoamBSSID=any RSSI=-48
03-15 20:36:28.135   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=19039 interval=45000 maxinterval=300000
03-15 20:36:28.135   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-15 20:36:28.135   885  1237 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-15 20:36:28.136  1412  1412 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-15 20:36:28.137   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-15 20:36:28.137   293  1649 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-15 20:36:28.140   885  1237 E WifiStateMachine: [1,458,070,588,140 ms] noteScanstart no scan source
,03-15 20:36:28.202   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
03-15 20:36:28.202   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 9
03-15 20:36:28.202   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-15 20:36:28.202   293  1649 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-15 20:36:28.203   490   509 D TCMD    : NL - Read 56 bytes from update socket.
03-15 20:36:28.203   490   509 D TCMD    : NL - message type is RTM_NEWLINK
03-15 20:36:28.203   490   509 D TCMD    : Listening for incoming client connection request
,03-15 20:36:28.207   885  1237 E WifiStateMachine: [1,458,070,588,207 ms] noteScanEnd no scan source
,03-15 20:36:28.210   885  1237 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@27cf02d2 sup_state=COMPLETED debouncing=false
,03-15 20:36:28.349  1715  6167 I VacuumService: Vacuum at: now=1458070588349 tag=VacuumService
,03-15 20:36:28.759  1715  6172 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 13261 seconds from now (1458070588759)
,03-15 20:36:28.863  1715  6170 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-15 20:36:28.870  1715  6170 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-15 20:36:28.918  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 20:36:28.919  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:29.070  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:29.566   305   385 I ThermalEngine: Sensor:xo_therm_pu2:34000 mC
,03-15 20:36:30.070  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:30.777  1715  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:36:30.779  1715  1715 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:36:31.929  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 20:36:31.929  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:34.074  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:34.945  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:34.945  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:35.371   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=311, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312116, SEQNUM=4400, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-272, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 20:36:35.451  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:36:37.961  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:37.962  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:39.571   305   385 I ThermalEngine: Sensor:xo_therm_pu2:34000 mC
,03-15 20:36:40.935   885  1246 E BackupManagerService: Timeout restoring application @pm@
,03-15 20:36:40.940   885  1246 W BackupManagerService: Tried to clear data for @pm@ but not found
,03-15 20:36:40.945  1715  1733 W GmsBackupTransport: Restore processing aborted, no more packages
,03-15 20:36:40.948   885  1246 E BackupManagerService: Failure getting next package name
,03-15 20:36:40.949   885  1246 E BackupManagerService: Duplicate finish
,03-15 20:36:40.974  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:40.975  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:43.764   885  1226 V AlarmManager: send {3ee9d479, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-15 20:36:43.767   885   885 V AlarmManager: done {3ee9d479, *alarm*:com.android.server.WifiManager.action.START_SCAN} [3ms]
,03-15 20:36:43.770   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.28 rxSuccessRate=2.33 targetRoamBSSID=any RSSI=-48
03-15 20:36:43.771   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=34674 interval=45000 maxinterval=300000
03-15 20:36:43.771   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-15 20:36:43.771   885  1237 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
,03-15 20:36:43.774  1412  1412 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-15 20:36:43.774   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-15 20:36:43.774   293  1649 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-15 20:36:43.777   885  1237 E WifiStateMachine: [1,458,070,603,777 ms] noteScanstart no scan source
,03-15 20:36:43.843   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 20 
03-15 20:36:43.843   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 20 
03-15 20:36:43.843   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:43.843   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:43.843   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 20:36:43.843   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-15 20:36:43.843   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:43.843   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 20:36:43.843   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
03-15 20:36:43.843   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 6
03-15 20:36:43.843   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
03-15 20:36:43.843   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 7
03-15 20:36:43.843   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
03-15 20:36:43.843   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 8
03-15 20:36:43.843   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-15 20:36:43.843   293  1649 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-15 20:36:43.843   490   509 D TCMD    : NL - Read 56 bytes from update socket.
03-15 20:36:43.843   490   509 D TCMD    : NL - message type is RTM_NEWLINK
03-15 20:36:43.843   490   509 D TCMD    : Listening for incoming client connection request
,03-15 20:36:43.849   885  1237 E WifiStateMachine: [1,458,070,603,849 ms] noteScanEnd no scan source
,03-15 20:36:43.851   885  1237 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@27cf02d2 sup_state=COMPLETED debouncing=false
,03-15 20:36:43.987  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:43.987  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:47.002  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:47.003  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:48.169  1423  1613 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-15 20:36:48.175  1423  1613 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-15 20:36:48.222  1715  1715 I ConfigService: onCreate
,03-15 20:36:49.575   305   385 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-15 20:36:50.017  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:50.017  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:53.031  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:53.031  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-15 20:36:53.032  1293  1293 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
03-15 20:36:53.032  1293  1293 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,03-15 20:36:53.284  1715  1715 I ConfigService: onDestroy
,03-15 20:36:56.045  1293  1293 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 20:36:56.046  1293  1293 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 20:36:56.402   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=301, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311372, SEQNUM=4402, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-313, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 20:36:56.488  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:36:56.545  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:36:56.833   885  1226 V AlarmManager: send {1782f9f1, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-15 20:36:56.837   885   885 V AlarmManager: done {1782f9f1, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,03-15 20:36:57.445   885  1122 I PowerManagerService: Nap time (uid 1000)...
,03-15 20:36:57.447   885  1122 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-15 20:36:57.477   885  1122 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 20:36:57.477   885  1122 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 20:36:57.477   885  1122 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 20:36:57.477   885  1122 I Adreno-EGL: Local Branch: 
03-15 20:36:57.477   885  1122 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 20:36:57.477   885  1122 I Adreno-EGL: Local Patches: NONE
03-15 20:36:57.477   885  1122 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 20:36:57.963   885  1122 D         : activate, handle: 1598182242, enabled: 0, index 2
,03-15 20:36:57.966   885  1122 D         : BstSensorExt: id=1598182242, en=0
03-15 20:36:57.966   885  1122 D         : enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,03-15 20:36:57.971   885  1122 D         : activate, handle: 2, enabled: 0, index 5
,03-15 20:36:57.976   885  1112 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-15 20:36:57.979   885   885 V ActivityManager: Display changed displayId=0
,03-15 20:36:58.007   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb744c550
,03-15 20:36:58.009   281   281 D qdhwcomposer: hwc_blank: Blanking display: 0
,03-15 20:36:58.117   290   290 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7d59820
03-15 20:36:58.118   290   290 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
03-15 20:36:58.118   290   290 I rmt_storage: wakelock acquired: 1, error no: 42
,03-15 20:36:58.120   290   811 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1210738552)
,03-15 20:36:58.224   290   811 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
03-15 20:36:58.224   290   811 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,03-15 20:36:58.226   290   811 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1210738552) wakelock released: 1, error no: 0
03-15 20:36:58.226   290   811 I rmt_storage: 
,03-15 20:36:58.229   290   290 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7d59820
,03-15 20:36:58.327   281   687 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-15 20:36:58.328   281   281 I qdhwcomposer: enable_dcabc: Done setting OFF mode
03-15 20:36:58.328   281   281 D qdhwcomposer: hwc_blank: Done blanking display: 0
,03-15 20:36:58.330   885  1255 D SurfaceControl: Excessive delay in setPowerMode(): 352ms
,03-15 20:36:58.337   885  1122 I PowerManagerService: Sleeping (uid 1000)...
,03-15 20:36:58.338   281   281 I SFPerfTracer:       trigger: frame rate (-27.857%)	(43.286 fps)	(23.102 ms) 	(3 drops)	(16 frames)
03-15 20:36:58.339   281   281 I SFPerfTracer:      triggers: (rate: 16:433) (compose: 0:1) (post: 0:2) (render: 0:3) (16:1048 frames) (17:1164)
03-15 20:36:58.339   281   281 D SFPerfTracer:        layers: (4:10) (FocusedStackFrame (0xb7557738): 0:17)* (DimLayer (0xb74eb528): 0:8)* (StatusBar (0xb7548938): 0:184) (NavigationBar (0xb755f540): 0:46) (com.android.systemui.ImageWallpaper (0xb7561930): 0:6)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7538008): 0:31) (ColorFade (0xb7543568): 17:19) 
,03-15 20:36:58.341   885   885 I WindowManager: AOD feature not enabled!
,03-15 20:36:58.356  1484  3885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-15 20:36:58.405   885  1237 D WifiStateMachine: backgroundScan enabled=false startBackgroundScanIfNeeded:false
03-15 20:36:58.405   885  1237 E WifiStateMachine: handleScreenStateChanged Exit: true
,03-15 20:36:58.409   295   984 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-15 20:36:58.411   295   984 V msm8974_platform: platform_set_parameters: enter: screen_state=on
03-15 20:36:58.411   295   984 V msm8974_platform: platform_set_parameters: exit with code(0)
,03-15 20:36:58.412   295   984 E msm8974_platform: platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
03-15 20:36:58.412   295   984 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
,03-15 20:36:58.414   295   984 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,03-15 20:36:58.431   885  1237 E WifiStateMachine: setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-15 20:36:58.431   885  1237 E native  : do suspend false
,03-15 20:36:58.519   885   885 D         : activate, handle: 1598182229, enabled: 0, index 0
03-15 20:36:58.519   885   885 E         : <BST> disable accel, orig state: 1
03-15 20:36:58.519   885   885 I         : <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,03-15 20:36:58.522  1423  1423 I Keyboard.Facilitator: onFinishInput()
03-15 20:36:58.522   295   295 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-15 20:36:58.522   295   295 V msm8974_platform: platform_set_parameters: enter: screen_state=off
03-15 20:36:58.522   295   295 V msm8974_platform: platform_set_parameters: exit with code(0)
03-15 20:36:58.522   295   295 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
03-15 20:36:58.522   295   295 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,03-15 20:36:58.528   885  1237 D WifiStateMachine: backgroundScan enabled=true startBackgroundScanIfNeeded:false
03-15 20:36:58.528   885  1237 E WifiStateMachine: handleScreenStateChanged Exit: false
,03-15 20:36:58.534   885  1237 E WifiStateMachine: setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-15 20:36:58.535   885  1237 E WifiStateMachine: setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-15 20:36:58.535   885  1237 E native  : do suspend true
,03-15 20:36:59.580   305   385 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-15 20:37:00.152   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:37:00.152   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:00.152   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:00.152   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:00.152   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:00.152   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:00.152   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 20:37:00.152   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:37:00.152   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:00.152   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:00.152   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:00.152   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:00.152   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:00.153   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:37:00.560  1484  1484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-15 20:37:00.680  1484  1484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-15 20:37:03.362   885  1226 V AlarmManager: send {24d726cd, *alarm*:android.intent.action.TIME_TICK}
,03-15 20:37:03.365   885  1226 V AlarmManager: send {27cf1638, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
03-15 20:37:03.366   885  1226 V AlarmManager: send {3341b611, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,03-15 20:37:03.384   885   885 V AlarmManager: done {27cf1638, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [23ms]
,03-15 20:37:03.399   885   885 V AlarmManager: done {3341b611, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [37ms]
,03-15 20:37:03.408   885   885 V AlarmManager: done {24d726cd, *alarm*:android.intent.action.TIME_TICK} [47ms]
,03-15 20:37:03.413  1962  6238 I EventLogService: Aggregate from 1458070569173 (log), 1458068821370 (data)
,03-15 20:37:08.531   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312203, SEQNUM=4414, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10917, POWER_SUPPLY_CHARGE_COUNTER=-345, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 20:37:08.601  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:37:08.652  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:37:09.584   305   385 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-15 20:37:14.156   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:37:14.156   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:14.156   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:14.156   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:14.156   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:14.157   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:14.157   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 20:37:14.157   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:37:14.157   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:14.157   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:14.157   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:14.157   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:14.157   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:14.157   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:37:19.589   305   385 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-15 20:37:28.548   885  1226 V AlarmManager: send {1b38c102, *walarm*:com.google.android.intent.action.SEND_IDLE}
,03-15 20:37:28.555   885   885 V AlarmManager: done {1b38c102, *walarm*:com.google.android.intent.action.SEND_IDLE} [7ms]
,03-15 20:37:29.594   305   385 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-15 20:37:30.161   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:37:30.161   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:30.161   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:30.161   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:30.161   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:30.161   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:30.161   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 20:37:30.161   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:37:30.161   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:30.161   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:30.162   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:30.162   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:30.162   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:30.162   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 20:37:30.162   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:37:30.162   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:30.162   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:30.162   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:30.162   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:30.162   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:30.162   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 20:37:30.162   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:37:30.162   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:30.162   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:30.162   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:30.162   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:30.162   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:30.162   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:37:32.954  2580  3959 E global frequency: no tags to log
,03-15 20:37:32.957  2580  3959 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-15 20:37:32.975  2580  2580 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 20:37:32.979  1559  2088 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-15 20:37:33.080  1484  1500 I art     : Explicit concurrent mark sweep GC freed 56259(3MB) AllocSpace objects, 36(1233KB) LOS objects, 39% free, 7MB/12MB, paused 966us total 44.674ms
,03-15 20:37:33.100  2580  2580 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 20:37:33.112  2580  2580 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-15 20:37:33.121  2580  2580 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 20:37:33.122  1559  1574 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-15 20:37:33.211  2580  2580 I art     : Explicit concurrent mark sweep GC freed 29625(1734KB) AllocSpace objects, 6(119KB) LOS objects, 40% free, 11MB/19MB, paused 1.257ms total 71.548ms
,03-15 20:37:33.360   885  1222 I art     : Explicit concurrent mark sweep GC freed 43960(2MB) AllocSpace objects, 2(215KB) LOS objects, 33% free, 21MB/32MB, paused 1.444ms total 122.963ms
,03-15 20:37:33.382  2580  2580 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 20:37:33.392  2580  2580 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-15 20:37:33.399  2580  2580 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 20:37:33.401  1559  2088 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-15 20:37:33.467  1484  4609 I art     : Explicit concurrent mark sweep GC freed 3976(168KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 536us total 26.783ms
,03-15 20:37:33.484  2580  2580 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 20:37:33.494  2580  2580 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-15 20:37:33.498  2580  3959 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-15 20:37:33.499  2580  3959 I global frequency: BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,03-15 20:37:33.500  2580  3959 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-15 20:37:33.500  2580  3959 E global frequency: BcsDSCheckin.logProperties: BL State from property is null or empty
,03-15 20:37:33.501  2580  3959 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-15 20:37:33.502  2580  3959 D Checkin : publish the event [tag = DEV_ATTRIBS event name = SW]
,03-15 20:37:33.504  2580  3959 D Checkin : publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,03-15 20:37:33.515  2580  3959 I global frequency: BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,03-15 20:37:33.516  2580  3959 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-15 20:37:39.598   305   385 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-15 20:37:40.165   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
,03-15 20:37:40.165   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:40.165   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:40.165   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:40.165   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:40.165   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:40.165   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 20:37:40.165   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:37:40.165   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:40.166   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:40.166   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:40.166   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:40.166   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:40.166   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:37:40.852  1715  2417 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-15 20:37:43.535   885  1226 V AlarmManager: send {2ef5eb4e, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,03-15 20:37:43.539   885   885 V AlarmManager: done {2ef5eb4e, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [4ms]
,03-15 20:37:49.603   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:37:56.359   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:37:56.359   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:56.359   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:56.359   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:56.359   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:56.359   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:56.359   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 20:37:56.362   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311728, SEQNUM=4418, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9815, POWER_SUPPLY_CHARGE_COUNTER=-456, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 20:37:56.408  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:37:56.450   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:37:56.450   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:37:56.450   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:37:56.450   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:37:56.450   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:37:56.450   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:37:56.450   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:37:56.504  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:37:58.523  1423  1613 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-15 20:37:58.523  1423  1613 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-15 20:37:58.540  1715  1715 I ConfigService: onCreate
,03-15 20:37:59.608   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:38:03.593  1715  1715 I ConfigService: onDestroy
,03-15 20:38:09.612   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:38:19.617   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:38:29.621   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:38:39.626   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:38:49.630   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:38:59.635   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:39:09.640   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:39:16.479   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311927, SEQNUM=4420, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-643, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-15 20:39:16.480   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:39:16.480   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:39:16.480   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:39:16.480   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:39:16.481   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:39:16.481   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:39:16.481   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:39:16.525  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:39:16.569   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:39:16.569   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:39:16.569   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:39:16.569   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:39:16.569   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:39:16.569   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:39:16.570   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:39:16.626  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:39:19.644   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:39:29.649   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:39:39.653   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:39:49.658   305   385 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 20:39:51.460   293  1649 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
,03-15 20:39:51.460   293  1649 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
,03-15 20:39:59.663   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:40:09.667   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:40:19.672   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:40:29.676   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:40:39.681   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:40:49.686   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:40:59.690   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:41:00.001   885  1226 V AlarmManager: send {24d726cd, *alarm*:android.intent.action.TIME_TICK}
,03-15 20:41:00.035   885   885 V AlarmManager: done {24d726cd, *alarm*:android.intent.action.TIME_TICK} [35ms]
,03-15 20:41:09.695   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:41:19.699   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:41:29.704   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:41:39.708   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:41:49.713   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:41:59.718   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:42:09.722   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:42:19.727   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:42:29.731   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:42:39.736   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:42:49.741   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:42:59.745   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:43:06.806   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=272, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311534, SEQNUM=4424, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=504, POWER_SUPPLY_CHARGE_COUNTER=-790, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-15 20:43:06.808   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:43:06.808   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:43:06.808   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:43:06.808   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:43:06.808   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:43:06.808   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:43:06.808   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:43:06.865  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:43:09.750   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:43:19.754   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:43:29.759   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:43:39.764   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:43:49.768   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:43:59.773   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:44:07.086   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=271, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311810, SEQNUM=4425, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-802, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-15 20:44:07.088   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:44:07.088   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:44:07.088   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:44:07.088   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:44:07.088   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:44:07.088   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:44:07.088   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:44:07.136  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:44:09.777   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:44:19.782   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:44:29.787   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:44:39.791   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:44:49.796   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:44:59.800   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:45:01.000   885  1226 V AlarmManager: send {24d726cd, *alarm*:android.intent.action.TIME_TICK}
03-15 20:45:01.003   885  1226 V AlarmManager: send {3c496e5a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,03-15 20:45:01.043   885  1093 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6257 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,03-15 20:45:01.092   885   885 V AlarmManager: done {24d726cd, *alarm*:android.intent.action.TIME_TICK} [92ms]
,03-15 20:45:01.216  6257  6257 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-15 20:45:01.216  6257  6257 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-15 20:45:01.216  6257  6257 I GAv4    :   adb logcat -s GAv4
,03-15 20:45:01.233  6257  6257 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-15 20:45:01.255  6257  6257 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-15 20:45:01.260  6257  6285 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-15 20:45:01.267   885   885 V AlarmManager: done {3c496e5a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [268ms]
03-15 20:45:01.268   885  1301 I ActivityManager: Killing 5932:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-15 20:45:01.283   885  1599 W libprocessgroup: failed to open /acct/uid_10039/pid_5932/cgroup.procs: No such file or directory
,03-15 20:45:09.805   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:45:19.810   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:45:29.814   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:45:39.819   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:45:49.823   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:45:59.828   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:46:09.833   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:46:19.837   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:46:29.842   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:46:39.846   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:46:49.851   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:46:59.855   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:47:09.860   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:47:19.865   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:47:27.926   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=269, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311780, SEQNUM=4430, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-26, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-15 20:47:27.928   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:47:27.928   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:47:27.928   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:47:27.928   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:47:27.928   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:47:27.928   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:47:27.928   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:47:27.973  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:47:29.869   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:47:39.874   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:47:49.879   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:47:53.317   885  1226 V AlarmManager: send {24d726cd, *alarm*:android.intent.action.TIME_TICK}
,03-15 20:47:53.320   885  1226 V AlarmManager: send {21168394, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,03-15 20:47:53.334   885   885 V AlarmManager: done {21168394, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [17ms]
,03-15 20:47:53.362   885   885 V AlarmManager: done {24d726cd, *alarm*:android.intent.action.TIME_TICK} [46ms]
,03-15 20:47:59.883   305   385 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 20:48:09.888   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:48:17.319   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312092, SEQNUM=4431, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-27, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-15 20:48:17.321   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:48:17.321   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:48:17.321   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:48:17.321   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:48:17.321   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:48:17.321   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:48:17.322   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:48:17.366  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:48:17.408   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:48:17.408   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:48:17.408   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:48:17.408   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:48:17.408   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:48:17.408   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:48:17.408   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:48:17.459  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:48:19.892   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:48:29.897   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:48:39.902   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:48:49.906   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:48:59.911   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:49:08.366   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312368, SEQNUM=4437, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-30, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-15 20:49:08.368   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:49:08.368   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:49:08.368   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:49:08.368   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:49:08.368   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:49:08.368   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:49:08.368   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:49:08.415  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:49:09.915   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:49:19.920   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:49:29.924   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:49:39.929   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:49:49.934   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:49:59.938   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:50:09.943   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:50:19.947   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:50:29.952   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:50:39.957   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:50:49.961   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:50:59.966   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:51:09.970   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:51:19.975   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:51:29.979   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:51:39.984   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:51:49.989   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:51:59.993   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:52:09.998   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:52:20.003   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:52:30.007   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:52:40.012   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:52:50.017   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:53:00.021   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:53:10.026   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:53:20.030   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:53:30.035   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:53:40.039   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:53:50.044   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:54:00.049   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:54:10.053   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:54:20.058   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:54:30.062   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:54:40.067   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:54:49.358   885  1092 I UsageStatsService: User[0] Flushing usage stats to disk
,03-15 20:54:50.072   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:55:00.076   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:55:08.002   885  1226 V AlarmManager: send {24d726cd, *alarm*:android.intent.action.TIME_TICK}
03-15 20:55:08.004   885  1226 V AlarmManager: send {1782f9f1, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-15 20:55:08.011   885   885 V AlarmManager: done {1782f9f1, *walarm*:android.content.syncmanager.SYNC_ALARM} [9ms]
,03-15 20:55:08.041   885   885 V AlarmManager: done {24d726cd, *alarm*:android.intent.action.TIME_TICK} [40ms]
,03-15 20:55:10.081   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:55:20.085   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:55:30.090   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:55:40.094   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:55:50.099   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:56:00.104   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:56:10.108   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:56:20.113   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:56:30.121   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:56:30.172   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311158, SEQNUM=4440, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-15 20:56:30.174   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:56:30.174   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:56:30.174   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:56:30.174   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:56:30.174   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:56:30.174   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:56:30.174   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:56:30.215  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:56:40.126   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:56:50.130   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:57:00.135   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:57:10.139   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:57:20.144   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:57:30.149   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:57:40.153   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:57:50.158   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:58:00.162   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:58:10.167   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:58:20.171   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:58:20.646   885  1221 D BatteryService: uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312325, SEQNUM=4441, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-15 20:58:20.648   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 20:58:20.648   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 20:58:20.648   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-15 20:58:20.648   293   517 I MDMCTBK : checkDefaultInst, pid match
03-15 20:58:20.648   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 20:58:20.648   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 20:58:20.648   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 20:58:20.695  2456  2567 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:58:30.176   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:58:40.181   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:58:50.185   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:59:00.190   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 20:59:10.194   305   385 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),03-15 20:59:13.161  6320  6320 D AndroidRuntime: 
03-15 20:59:13.161  6320  6320 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-15 20:59:13.165  6320  6320 D AndroidRuntime: CheckJNI is OFF
03-15 20:59:13.334  6320  6320 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-15 20:59:13.345   885  1093 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
03-15 20:59:13.397   885  1144 W PackageSettings: Skipping PackageSetting{2d86e91 com.example.hello/10568} due to missing metadata
03-15 20:59:13.421   885  1144 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
03-15 20:59:13.440  1715  2029 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-15 20:59:13.454   885  1228 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-15 20:59:13.455  1423  1423 I Keyboard.Facilitator: resetDictionaries() : en_US
03-15 20:59:13.511   885  1482 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6341 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
03-15 20:59:13.531  3011  3011 I art     : Explicit concurrent mark sweep GC freed 11465(2MB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 7MB/12MB, paused 7.377ms total 90.939ms
03-15 20:59:13.532  6027  6339 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
03-15 20:59:13.543  1423  6340 I Keyboard.Facilitator.DecoderInitializer: run()
03-15 20:59:13.583  6341  6341 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-15 20:59:13.584  6341  6341 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-15 20:59:13.584  6341  6341 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 20:59:13.584  6341  6341 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
03-15 20:59:13.606  1423  6340 I Decoder : createOrResetDecoder
03-15 20:59:13.606  1576  1576 I art     : Explicit concurrent mark sweep GC freed 2549(135KB) AllocSpace objects, 3(128KB) LOS objects, 24% free, 13MB/17MB, paused 554us total 175.853ms
03-15 20:59:13.631  1962  1962 I art     : Explicit concurrent mark sweep GC freed 22005(1324KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 14MB/19MB, paused 1.364ms total 182.560ms
03-15 20:59:13.633   885   885 I art     : Explicit concurrent mark sweep GC freed 22553(1788KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 21MB/32MB, paused 5.562ms total 204.936ms
03-15 20:59:13.634   885  1144 I art     : WaitForGcToComplete blocked for 205.642ms for cause Explicit
03-15 20:59:13.680  1715  1715 I ConfigService: onCreate
03-15 20:59:13.722   885  1486 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6373 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
03-15 20:59:13.744   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.534ms
03-15 20:59:13.760   885   885 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-15 20:59:13.761   885   885 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-15 20:59:13.765   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 353us total 20.245ms
03-15 20:59:13.767   885  1256 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-15 20:59:13.767   885  1256 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
03-15 20:59:13.767   885  1486 I ActivityManager: Killing 6080:com.google.android.apps.plus/u0a90 (adj 15): empty #7
03-15 20:59:13.787   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 21.983ms
03-15 20:59:13.801  1423  6340 I Keyboard.Facilitator.MainLanguageModelLoader: run()
03-15 20:59:13.833  1423  6340 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-15 20:59:13.836  1423  6340 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-15 20:59:13.836  1423  6340 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-15 20:59:13.844  1423  6340 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-15 20:59:13.845  1423  6340 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-15 20:59:13.847  1423  6340 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-15 20:59:13.847  1423  6340 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-15 20:59:13.849  1423  6340 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-15 20:59:13.849   885  1144 I art     : Explicit concurrent mark sweep GC freed 5748(301KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 2.001ms total 207.390ms
03-15 20:59:13.853  1423  6340 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-15 20:59:13.853  1423  6340 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-15 20:59:13.853  1423  6340 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-15 20:59:13.853  1423  6340 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-15 20:59:13.853  1423  6340 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
03-15 20:59:13.872   885   901 W libprocessgroup: failed to open /acct/uid_10090/pid_6080/cgroup.procs: No such file or directory
03-15 20:59:13.940  6320  6320 D AndroidRuntime: Shutting down VM
03-15 20:59:13.946  1576  1576 I Launcher: Deferring update until onResume
03-15 20:59:13.958  6373  6373 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
03-15 20:59:13.985   885  1144 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6392 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
03-15 20:59:14.039   885   901 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6410 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
03-15 20:59:14.053   885   900 I ActivityManager: Killing 6109:com.android.vending/u0a32 (adj 15): empty #7
03-15 20:59:14.142   885   901 W libprocessgroup: failed to open /acct/uid_10032/pid_6109/cgroup.procs: No such file or directory
03-15 20:59:14.152   885  1558 I ActivityManager: Killing 5401:com.google.process.gapps/u0a16 (adj 15): empty #7
03-15 20:59:14.202   885  1528 W libprocessgroup: failed to open /acct/uid_10016/pid_5401/cgroup.procs: No such file or directory
03-15 20:59:14.225  1576  1576 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a98df7b new=com.google.android.velvet.VelvetApplication@a98df7b
03-15 20:59:14.236  1962  6434 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-15 20:59:14.236  1962  6434 D AccountUtils: Clearing selected account for com.test.thalitest
03-15 20:59:14.324  1715  1715 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-15 20:59:14.324  1715  1715 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
03-15 20:59:14.327  1962  6434 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
03-15 20:59:14.358   885   900 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6441 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
03-15 20:59:14.407   885  1486 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6460 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
03-15 20:59:14.419  1962  6434 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/databases/phenotype.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-15 20:59:14.479  6460  6460 I GservicesProvider: Gservices pushing to system: true; secure/global: true
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1353)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-15 20:59:14.490  6460  6460 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
03-15 20:59:14.490  6460  6460 D AndroidRuntime: Shutting down VM
--------- beginning of crash
03-15 20:59:14.491  6460  6460 E AndroidRuntime: FATAL EXCEPTION: main
03-15 20:59:14.491  6460  6460 E AndroidRuntime: Process: com.google.process.gapps, PID: 6460
03-15 20:59:14.491  6460  6460 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5054)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1353)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
03-15 20:59:14.491  6460  6460 E AndroidRuntime: 	... 11 more
03-15 20:59:14.507   885  6481 E DropBoxManagerService: Can't write: system_app_crash
03-15 20:59:14.507   885  6481 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
03-15 20:59:14.507   885  6481 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-15 20:59:14.507   885  6481 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-15 20:59:14.507   885  6481 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-15 20:59:14.507   885  6481 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-15 20:59:14.507   885  6481 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-15 20:59:14.507   885  6481 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
03-15 20:59:14.507   885  6481 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-15 20:59:14.507   885  6481 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-15 20:59:14.507   885  6481 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-15 20:59:14.507   885  6481 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-15 20:59:14.507   885  6481 E DropBoxManagerService: 	... 5 more
03-15 20:59:14.508   281   687 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
03-15 20:59:14.522  2176  2188 E MP-Decision: Error(-22) changing core 3 status to online

```
