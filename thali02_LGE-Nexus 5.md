#### Test 613623661dfc74c_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/CAR.SERVICE( 3117): mConnectedToCar = false, abort
,--------- beginning of system
E/ActivityThread( 3117): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2534b462 that was originally bound here
E/ActivityThread( 3117): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2534b462 that was originally bound here
E/ActivityThread( 3117): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3117): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3117): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3117): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3117): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3117): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3117): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3117): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3117): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3117): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3117): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3117): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3117): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3117): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3117): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3117): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3117): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3117): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3117): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3117): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3117): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3117): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3117): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3117): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3d7aaee5 that was originally bound here
E/ActivityThread( 3117): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3d7aaee5 that was originally bound here
E/ActivityThread( 3117): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3117): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3117): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3117): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3117): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3117): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3117): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3117): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3117): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3117): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3117): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3117): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3117): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3117): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3117): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3117): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3117): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3117): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3117): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3117): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3117): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3117): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@1d68f9de
D/AndroidRuntime( 3178): 
D/AndroidRuntime( 3178): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3178): CheckJNI is OFF
D/AndroidRuntime( 3178): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3211 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3178): Shutting down VM
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 191us total 7.875ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.396ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 175us total 7.471ms
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3211): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3211): Time to load native libraries: 2 ms (timestamps 5894-5896)
I/LibraryLoader( 3211): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3211): Binding Chromium to main looper Looper (main, tid 1) {1ae236fa}
I/LibraryLoader( 3211): Expected native library version number "",actual native library version number ""
I/chromium( 3211): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3211): Initializing chromium process, singleProcess=true
W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3211): ApplicationContext is null in ApplicationStatus
,W/chromium( 3211): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3211): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3211): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3211): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30d83842:true
,W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3211): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3211): CordovaWebView is running on device made by: LGE
,W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3211): Render dirty regions requested: true
D/Atlas   ( 3211): Validating map...
W/chromium( 3211): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3211): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3211): Enabling debug mode 0
,I/Keyboard.Facilitator( 1076): onFinishInput()
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +393ms (total +1m4s256ms)
,W/IInputConnectionWrapper( 3211): showStatusIcon on inactive InputConnection
,W/BindingManager( 3211): Cannot call determinedVisibility() - never saw a connection for the pid: 3211
,D/JsMessageQueue( 3211): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3211): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258380416
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29340181 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e0f414 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3211): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  761): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3211): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 3211): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:84)
W/System.err( 3211): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3211): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
,W/System.err( 3211): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3211): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3211): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3211): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3211): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3211): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3211): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3211): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3211): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 3211): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c9c3ab2 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20136a03 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3211): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 3211): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 3211): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:84)
W/System.err( 3211): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 3211): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 3211): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 3211): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 3211): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 3211): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 3211): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 3211): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 3211): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 3211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3211): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3211): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/chromium( 3211): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 3211): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,D/Finsky  ( 2727): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2727): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/ActivityThread( 1609): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  761): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 74110, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  761): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 165546, reason: UserStart
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1675): Vacuum at: now=1456920205808 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1076): run()
I/Keyboard.Facilitator( 1076): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1675): disconnect managed GoogleApiClient
,I/ActivityManager(  761): Killing 2643:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2643/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3299 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/EventLogService( 1609): Aggregate from 1456919017942 (log), 1456919017942 (data)
,I/GAv4    ( 3299): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3299):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3299):   adb logcat -s GAv4
,W/GAv4    ( 3299): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3299): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3299): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  761): Killing 2804:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2804/cgroup.procs: No such file or directory
,I/PhenotypeConfigurator( 1675): Scheduling Phenotype for one-off execution 10151 seconds from now (1456921037988)
,I/PhenotypeFlagCommitter( 1675): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1675): Using platform SSLCertificateSocketFactory
,W/bt-smp  ( 2193): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2193): Plain text(LSB ~ MSB) = 4c 18 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2193): Encrypted text(LSB ~ MSB) = 55 dd 54 bf 79 1c 57 ba a2 da 9b 36 86 0f ac d4 
,W/bt-btm  ( 2193): Stopping oneshot timer
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3362): 
D/AndroidRuntime( 3362): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3362): CheckJNI is OFF
D/AndroidRuntime( 3362): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3211:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  761): WIN DEATH: Window{147335f2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
W/PackageSettings(  761): Skipping PackageSetting{17cb3769 com.example.hello/10278} due to missing metadata
I/ActivityManager(  761):   Force finishing activity ActivityRecord{218837bf u0 com.test.thalitest/.MainActivity t218}
W/ActivityManager(  761): Spurious death for ProcessRecord{34afe395 3211:com.test.thalitest/u0a270}, curProc for 3211: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1280): Explicit concurrent mark sweep GC freed 7370(554KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 513us total 20.991ms
I/art     ( 1609): Explicit concurrent mark sweep GC freed 4437(295KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 22MB/30MB, paused 446us total 33.988ms
I/art     ( 1400): Explicit concurrent mark sweep GC freed 6201(484KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 290us total 19.829ms
I/Keyboard.Facilitator( 1076): resetDictionaries() : en_US
W/GeofencerStateMachine( 1675): Ignoring removeGeofence because network location is disabled.
I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1076): run()
I/art     (  761): Explicit concurrent mark sweep GC freed 34065(1839KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 3.824ms total 68.179ms
I/Decoder ( 1076): createOrResetDecoder
D/VoicemailCleanupService( 1362): Cleaning up data for package: com.test.thalitest
I/UpdateIcingCorporaServi( 1400): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1280): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1ae236fa new=com.google.android.velvet.VelvetApplication@1ae236fa
I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  946): Initialized EGL, version 1.4
I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3404 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/OpenGLRenderer(  946): Enabling debug mode 0
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  761): removeObsoleteFile: deleting file=218_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1076): run()
I/art     (  761): Explicit concurrent mark sweep GC freed 5177(293KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.070ms total 109.667ms
W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@25bab5c8 (uid=10034 pid=946)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1076): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1076): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1076): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1076): run()
I/StatsUtilsManager( 1076): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1076): shouldRecordStats() = Too Soon
W/ContextImpl( 3404): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1609): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1609): Clearing selected account for com.test.thalitest
I/UpdateIcingCorporaServi( 1400): UpdateCorporaTask done [took 148 ms] updated apps [took 148 ms] 
D/ChimeraCfgMgr( 1609): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1609): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1609): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1609): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1675): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1675): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 3211 uid 10270
I/Keyboard.Facilitator( 1076): onFinishInput()
D/AndroidRuntime( 3362): Shutting down VM
I/art     ( 1675): Explicit concurrent mark sweep GC freed 129597(7MB) AllocSpace objects, 33(551KB) LOS objects, 39% free, 24MB/40MB, paused 928us total 70.373ms
E/DataBuffer( 1675): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29785ef)
I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3433 uid=10039 gids={50039, 9997} abi=armeabi-v7a
E/DataBuffer( 1675): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b2d08fc)
E/DataBuffer( 1675): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29d1cb85)
E/DataBuffer( 1675): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@28345dda)
I/LocationSettingsChecker( 1609): Removing dialog suppression flag for package com.test.thalitest
E/DataBuffer( 1675): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@380920b)
E/DataBuffer( 1675): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29bfb8e8)
W/BaseAppContext( 1609): Using Auth Proxy for data requests.
W/BaseAppContext( 1609): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 1609): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1609): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1609): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1609): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/DataBuffer( 1675): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e42e63d)
E/DataBuffer( 1675): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@24d0ce32)
E/DataBuffer( 1675): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@38673783)
E/DataBuffer( 1675): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@292ebd00)
E/DataBuffer( 1675): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@347ca939)
D/gH_CompatibleDatabase( 1609): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1609): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1609): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/GMPM-SVC( 1609): App measurement is starting up, version: 8489
I/GMPM-SVC( 1609): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
D/gH_CompatibleDatabase( 1609): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1609): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1609): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1609): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1609): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1609): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3456 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  761): Killing 2785:com.android.settings/1000 (adj 15): empty #17
D/WifiService(  761): Client connection lost with reason: 4
W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2785/cgroup.procs: No such file or directory
I/Icing   ( 1609): doRemovePackageData com.test.thalitest
I/ActivityManager(  761): Killing 1745:com.android.defcontainer/u0a5 (adj 15): empty #17
D/ExternalStorage( 3456): After updating volumes, found 1 active roots
W/libprocessgroup(  761): failed to open /acct/uid_10005/pid_1745/cgroup.procs: No such file or directory
W/ResourcesManager( 2929): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2929): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Documents( 3433): Update found 7 roots in 235ms
D/Documents( 3433): Update found 7 roots in 149ms
I/Launcher( 1280): Deferring update until onResume
E/SQLiteLog( 1280): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
W/ResourcesManager( 1280): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1280): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1280): Deferring update until onResume

```
