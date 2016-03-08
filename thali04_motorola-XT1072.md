#### Test 617033519c823d7_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  880): send {302502c, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
V/AlarmManager(  880): done {302502c, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [19ms]
--------- beginning of main
E/SQLiteLog( 4921): (284) automatic index on view_events(_id)
D/AndroidRuntime( 5004): 
D/AndroidRuntime( 5004): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5004): CheckJNI is OFF
D/AndroidRuntime( 5004): Calling main entry com.android.commands.am.Am
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (165 us)
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5004): Shutting down VM
I/ActivityManager(  880): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5023 uid=10560 gids={50560, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/SFPerfTracer(  279):      triggers: (rate: 11:352) (compose: 0:1) (post: 0:1) (render: 0:2) (0:1011 frames) (1:1078)
D/SFPerfTracer(  279):        layers: (3:12) (FocusedStackFrame (0xb7cc1c10): 1:14)* (DimLayer (0xb7ccc688): 0:3)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7ccea78): 0:52)- (StatusBar (0xb7cd1fb0): 0:153) (NavigationBar (0xb7c600b0): 0:20) (com.android.systemui.ImageWallpaper (0xb7c66ae8): 0:8)* (Starting com.motorola.ccc.ota (0xb7ca11e0): 0:35)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7cb0c08): 0:24) (Starting com.example.hello (0xb7ca11e0): 1:2)* 
,I/WebViewFactory( 5023): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5023): Time to load native libraries: 3 ms (timestamps 4472-4475)
,I/LibraryLoader( 5023): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5023): Binding Chromium to main looper Looper (main, tid 1) {86d3153}
,I/LibraryLoader( 5023): Expected native library version number "",actual native library version number ""
I/chromium( 5023): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5023): Initializing chromium process, singleProcess=true
,W/art     ( 5023): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5023): ApplicationContext is null in ApplicationStatus
,W/chromium( 5023): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5023): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5023): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5023): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5023): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5023): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5023): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5023): Local Branch: 
I/Adreno-EGL( 5023): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5023): Local Patches: NONE
I/Adreno-EGL( 5023): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11bdf606:true
,D/BluetoothAdapter( 5023): 476793669: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5023): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5023): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5023): CordovaWebView is running on device made by: motorola
,W/art     ( 5023): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5023): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5023): Render dirty regions requested: true
,D/Atlas   ( 5023): Validating map...
,W/chromium( 5023): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5023): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5023): Enabling debug mode 0
,I/Keyboard.Facilitator( 1403): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.example.hello/.MainActivity,cp,ca,960
,I/ActivityManager(  880): Displayed com.example.hello/.MainActivity: +960ms
,E/Adreno-ES20( 5023): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5023): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5023): Cannot call determinedVisibility() - never saw a connection for the pid: 5023
,I/chromium( 5023): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5023): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5023): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 5023): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5023): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5023): JniHelper::setJavaVM(0xb83ea310), pthread_self() = -1200239152
,W/jxcore-log( 5023): Initializing JXcore engine
W/jxcore-log( 5023): JXcore engine is ready
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (44:313 vsyncs) (46:1172)
,W/Thread-588( 5074): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10560 path="socket:[7379]" dev="sockfs" ino=7379 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-588( 5074): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10560 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-588( 5074): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10560 path="socket:[9431]" dev="sockfs" ino=9431 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-588( 5074): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10560 path="socket:[22038]" dev="sockfs" ino=22038 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5023): Starting JXcore engine
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:36000 mC
,W/jxcore-log( 5023): Platform android
W/jxcore-log( 5023): 
W/jxcore-log( 5023): Process ARCH arm
W/jxcore-log( 5023): 
,I/ActivityManager(  880): Killing 4831:com.android.vending/u0a32 (adj 15): empty #7
,I/jxcore-log( 5023): JXcore Cordova bridge is ready!
I/jxcore-log( 5023): 
,W/jxcore-log( 5023): JXcore engine is started
,E/jxcore  ( 5023): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 5023): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/ActivityManager(  880): Killing 4895:com.google.android.gms:car/u0a16 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_4831/cgroup.procs: No such file or directory
,I/SFPerfTracer(  279):      triggers: (rate: 11:354) (compose: 0:1) (post: 0:1) (render: 0:2) (16:1109 frames) (17:1191)
D/SFPerfTracer(  279):        layers: (3:11) (FocusedStackFrame (0xb7cc1c10): 0:18)* (DimLayer (0xb7ccc688): 0:6)* (StatusBar (0xb7cd1fb0): 0:153) (NavigationBar (0xb7c600b0): 0:20) (com.android.systemui.ImageWallpaper (0xb7c66ae8): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7cb0c08): 0:52)- (Starting com.example.hello (0xb7ca11e0): 0:40)- (com.example.hello/com.example.hello.MainActivity (0xb7ccea78): 17:56) 
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_4895/cgroup.procs: No such file or directory
,D/TaskPersister(  880): removeObsoleteFile: deleting file=8_task_thumbnail.png
,V/AlarmManager(  880): send {1d1214cb, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {1d1214cb, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [3ms]
,V/AlarmManager(  880): send {30ae4a8, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  880): done {30ae4a8, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,I/ActivityManager(  880): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5096 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  880): send {1f3ebbc1, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  880): done {1f3ebbc1, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [45ms]
,D/Finsky  ( 5096): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5096): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5096): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5096): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Ads     ( 5096): Skipping gmscore version check
,D/Finsky  ( 5096): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5096): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5096): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5096): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 5096): [590] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5096): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  880): Killing 4971:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_4971/cgroup.procs: No such file or directory
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=320, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310761, SEQNUM=4319, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-18028, POWER_SUPPLY_CHARGE_COUNTER=-255, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/Finsky  ( 5096): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  880): send {595bedd, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  880): done {595bedd, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [11ms]
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5096): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5165 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5096): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/ResourcesManager( 5165): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5165): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5165): VM with version 2.1.0 has multidex support
I/MultiDex( 5165): install
I/MultiDex( 5165): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5165): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5165): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5165): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@256572b4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5165): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 5165): Reading stored module config
,D/WearableService( 1711): callingUid 10016, callindPid: 1711
,E/MDM     ( 1711): [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1711): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1939): Restart initialization of location
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 5165): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1711): No location to return for getLastLocation()
W/FusedLocationProvider( 1711): location=null
,D/CAR.SERVICE( 5165): Connecting to CarCallService...
,D/NativeLibraryUtils( 5165): Install completed successfully. count=14 extracted=0
,I/art     (  880): Explicit concurrent mark sweep GC freed 15380(712KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.237ms total 116.104ms
,I/art     ( 5165): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5165): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 5165): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5165): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5165): Creating a new PhoneAdapter instance
,W/ActivityManager(  880): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5165): setListener: com.google.android.gms.car.dn@2cdde913
W/ActivityManager(  880): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5165): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 5165): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5165): Package validated; name: com.android.vending
,V/Finsky  ( 5096): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5096): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5096): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  880): send {25f881ac, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 5096): [1] DailyHygiene.reschedule: Scheduling new run in 293 minutes (failures=4)
,V/AlarmManager(  880): done {25f881ac, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [51ms]
,D/DeviceConnectionService( 1711): client connected with version: 8296000
,D/Finsky  ( 5096): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 5096): [600] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5096): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5096): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:35000 mC
,I/ActivityManager(  880): Killing 2971:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10049/pid_2971/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 5165): mConnectedToCar = false, abort
,E/ActivityThread( 5165): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1f8ee19b that was originally bound here
E/ActivityThread( 5165): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1f8ee19b that was originally bound here
E/ActivityThread( 5165): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5165): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5165): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5165): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5165): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5165): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5165): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5165): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5165): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5165): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5165): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5165): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5165): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5165): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5165): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5165): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5165): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5165): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5165): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5165): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5165): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5165): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5165): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5165): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3db40c02 that was originally bound here
E/ActivityThread( 5165): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3db40c02 that was originally bound here
E/ActivityThread( 5165): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5165): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5165): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5165): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5165): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5165): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5165): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5165): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5165): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5165): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5165): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5165): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5165): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5165): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5165): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5165): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5165): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5165): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5165): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5165): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5165): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5165): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  880): Unbind failed: could not find connection for android.os.BinderProxy@228a572d
,V/AlarmManager(  880): send {d5418a7, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): done {d5418a7, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 2505): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2505): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2505): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2505): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2505):  Nonce Reponse 
I/MMApiWebService( 2505): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2505): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2505): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2505): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2505): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2505): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 4325(180KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 747us total 33.189ms
,D/MMApiWebService( 2505): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2505): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2505): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2505): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  880): send {3bd1d6b0, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  880): done {3bd1d6b0, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [4ms]
,D/Finsky  ( 5096): [590] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5096): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=309, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311394, SEQNUM=4331, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-17427, POWER_SUPPLY_CHARGE_COUNTER=-352, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=306, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311952, SEQNUM=4337, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-17427, POWER_SUPPLY_CHARGE_COUNTER=-378, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/AlarmManager(  880): send {23e23929, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  880): done {23e23929, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 2505): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2505): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2505): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2505): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2505):  Nonce Reponse 
I/MMApiWebService( 2505): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2505): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2505): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2505): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2505): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2505): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2505): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2505): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2505): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2505): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator.LanguageModelFlusher( 1403): run()
,I/Keyboard.Facilitator( 1403): flushDynamicLanguageModels()
,I/ConfigService( 1711): onCreate
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ConfigService( 1711): onDestroy
,I/PowerManagerService(  880): Nap time (uid 1000)...
I/PowerManagerService(  880): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  880): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  880): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  880): Build Date: 10/28/14 Tue
I/Adreno-EGL(  880): Local Branch: 
I/Adreno-EGL(  880): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  880): Local Patches: NONE
I/Adreno-EGL(  880): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  880): activate, handle: 1598182242, enabled: 0, index 2
D/        (  880): BstSensorExt: id=1598182242, en=0
,D/        (  880): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 224
,D/        (  880): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  880): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  880): Display changed displayId=0
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb7b92550
,D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/rmt_storage(  289): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7c56820
I/rmt_storage(  289): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  289): wakelock acquired: 1, error no: 42
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1211800264)
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1211800264) wakelock released: 1, error no: 0
I/rmt_storage(  289): 
,I/rmt_storage(  289): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7c56820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
I/SFPerfTracer(  279):       trigger: frame rate (-33.529%)	(39.883 fps)	(25.074 ms) 	(4 drops)	(14 frames)
I/SFPerfTracer(  279):      triggers: (rate: 12:361) (compose: 0:1) (post: 0:1) (render: 0:2) (14:1154 frames) (15:1249)
D/SFPerfTracer(  279):        layers: (6:11) (FocusedStackFrame (0xb7cc1c10): 0:19)* (DimLayer (0xb7c204b8): 0:15) (DimLayer (0xb7ccc688): 0:6)* (StatusBar (0xb7cd1fb0): 0:158) (NavigationBar (0xb7c600b0): 0:20) (com.android.systemui.ImageWallpaper (0xb7c66ae8): 0:8)* (com.example.hello/com.example.hello.MainActivity (0xb7ccea78): 0:56) (com.example.hello/com.example.hello.MainActivity (0xb7ca11e0): 0:35) (ColorFade (0xb7cb0c08): 15:17) 
,D/SurfaceControl(  880): Excessive delay in setPowerMode(): 346ms
,I/PowerManagerService(  880): Sleeping (uid 1000)...
,I/WindowManager(  880): AOD feature not enabled!
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  296): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  296): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  296): platform_set_parameters: exit with code(0)
E/msm8974_platform(  296): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  296): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  296): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2d8789c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb83ea310, mCls = 0x1752
I/WifiNative-HAL(  880): Could not start hal
D/WifiStateMachine(  880): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  880): setSuspendOptimizations: 4 false
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 4
,D/        (  880): activate, handle: 1598182229, enabled: 0, index 0
E/        (  880): <BST> disable accel, orig state: 1
I/        (  880): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  296): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  296): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  296): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  296): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  296): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2d8789c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb83ea310, mCls = 0x101736
I/WifiNative-HAL(  880): Could not start hal
D/WifiStateMachine(  880): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: false
E/WifiStateMachine(  880): setSuspendOptimizations: 4 true
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  880): send {2d641c47, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  880): done {2d641c47, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312653, SEQNUM=4346, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12419, POWER_SUPPLY_CHARGE_COUNTER=-639, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  880): send {30ae4a8, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  880): send {d5418a7, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {23e23929, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  880): done {30ae4a8, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [6ms]
,V/AlarmManager(  880): done {23e23929, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [22ms]
,V/AlarmManager(  880): done {d5418a7, *alarm*:android.intent.action.TIME_TICK} [44ms]
,V/AlarmManager(  880): send {3a27dc74, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  880): done {3a27dc74, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,E/global frequency( 2505): no tags to log
,D/Checkin ( 2505): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2505): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/art     ( 2505): Explicit concurrent mark sweep GC freed 19509(1158KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 10MB/18MB, paused 1.119ms total 64.936ms
,D/BSUtils ( 2505): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 52880(2MB) AllocSpace objects, 32(1026KB) LOS objects, 39% free, 7MB/12MB, paused 1.030ms total 49.300ms
,I/BSUtils ( 2505): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2505): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  880): Explicit concurrent mark sweep GC freed 17387(958KB) AllocSpace objects, 4(301KB) LOS objects, 33% free, 20MB/30MB, paused 1.473ms total 109.329ms
,D/BSUtils ( 2505): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2505): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2505): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2505): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 4086(170KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 817us total 40.280ms
,I/BSUtils ( 2505): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2505): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2505): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2505): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2505): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2505): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2505): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2505): BcsDSCheckin.events found events 2000
,D/Checkin ( 2505): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2505): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2505): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2505): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2505): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2505): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2505): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2505): unknown error code mapping for: 0
I/global frequency( 2505): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2505): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2505): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2505): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 2505): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2505): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2505): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2505): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2505):  Nonce Reponse 
I/MMApiWebService( 2505): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2505): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2505): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2505): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2505): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2505): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2505): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2505): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2505): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2505): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2505): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  880): send {23e23929, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  880): done {23e23929, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,V/AlarmManager(  880): send {1ebe99, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  880): done {1ebe99, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [3ms]
,I/VacuumService( 1711): Vacuum at: now=1457426749180 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1711): disconnect managed GoogleApiClient
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311646, SEQNUM=4353, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12419, POWER_SUPPLY_CHARGE_COUNTER=-834, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {d5418a7, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {30ae4a8, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  880): done {30ae4a8, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [8ms]
,V/AlarmManager(  880): done {d5418a7, *alarm*:android.intent.action.TIME_TICK} [44ms]
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 5314): 
D/AndroidRuntime( 5314): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5314): CheckJNI is OFF
D/AndroidRuntime( 5314): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.example.hello appid=10560 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 5023:com.example.hello/u0a560 (adj 0): stop com.example.hello
I/WindowState(  880): WIN DEATH: Window{15725caf u0 com.example.hello/com.example.hello.MainActivity}
I/WindowState(  880): WIN DEATH: Window{11f5ecb6 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  880): Skipping PackageSetting{2ccb79b2 com.test.thalitest/10558} due to missing metadata
I/ActivityManager(  880):   Force finishing activity ActivityRecord{7e1708a u0 com.example.hello/.MainActivity t9}
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager(  880): Spurious death for ProcessRecord{2df24d3f 5023:com.example.hello/u0a560}, curProc for 5023: null
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  880): Force stopping com.example.hello appid=10560 user=0: pkg removed
I/art     ( 2912): Explicit concurrent mark sweep GC freed 3288(700KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 7MB/12MB, paused 673us total 36.258ms
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1711): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1403): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1403): run()
I/Decoder ( 1403): createOrResetDecoder
I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5343 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1555): Explicit concurrent mark sweep GC freed 7315(531KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 496us total 83.767ms
I/art     ( 1939): Explicit concurrent mark sweep GC freed 680(30KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/19MB, paused 876us total 122.803ms
D/OtaApp  ( 2505): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2505): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2505): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2505): [info] > Exceed max defer attempts for optional update, suppresing later btn
I/ConfigService( 1711): onCreate
D/Checkin ( 2505): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2505): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2505): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2505): publish the event [tag = MOT_OTA event name = LOG]
I/art     (  880): Explicit concurrent mark sweep GC freed 13261(873KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.645ms total 144.749ms
I/art     (  880): WaitForGcToComplete blocked for 94.229ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1403): run()
W/InputMethodManagerService(  880): Got RemoteException sending setActive(false) notification to pid 5023 uid 10560
I/Keyboard.Facilitator( 1403): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1403): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1403): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1403): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1403): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1403): run()
I/StatsUtilsManager( 1403): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1403): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 5343): Cleaning up data for package: com.example.hello
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5367 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5343): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  880): Killing 4601:com.android.defcontainer/u0a10 (adj 15): empty #7
I/art     (  880): Explicit concurrent mark sweep GC freed 4850(257KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 3.331ms total 195.167ms
D/AndroidRuntime( 5314): Shutting down VM
D/TaskPersister(  880): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  880): removeObsoleteFile: deleting file=8_task.xml
W/libprocessgroup(  880): failed to open /acct/uid_10010/pid_4601/cgroup.procs: No such file or directory
I/Launcher( 1555): Deferring update until onResume
W/asset   ( 5367): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5367): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5367): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5367): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5388 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  880): Killing 4921:com.android.providers.calendar/u0a5 (adj 15): empty #7
W/ContextImpl( 5388): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_4921/cgroup.procs: No such file or directory
D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1939): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1939): Removing dialog suppression flag for package com.example.hello
E/NetworkScheduler.SchedulerReceiver( 1711): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1711): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1939): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5414 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
E/SQLiteLog( 1939): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/FileUtils( 1939): Failed to chmod(/data/data/com.google.android.gms/databases/phenotype.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/ClearPendingStateOp( 1939): Runtime exception while performing operation
E/ClearPendingStateOp( 1939): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1939): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 1939): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1939): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1939): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1939): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1939): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1939): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1939): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1939): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1939): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1939): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1939): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1939): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1939): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1939): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 1939): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1939): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1939): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1939): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1939): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1939): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1939): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1939): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1939): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1939): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1939): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 1939): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/DropBoxManagerService(  880): Can't write: system_app_wtf
E/DropBoxManagerService(  880): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  880): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  880): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  880): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  880): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  880): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  880): 	... 5 more
E/SQLiteLog( 1939): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Icing   ( 1939): doRemovePackageData com.example.hello
--------- beginning of crash
E/AndroidRuntime( 1939): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1939): Process: com.google.android.gms, PID: 1939
E/AndroidRuntime( 1939): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1939): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1939): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1939): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1939): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1939): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1939): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1939): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1939): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1939): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1939): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1939): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1939): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1939): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  880): Can't write: system_app_crash
E/DropBoxManagerService(  880): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  880): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  880): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  880): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  880): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  880): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  880): 	... 5 more
W/FileUtils( 1939): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SharedPreferencesImpl( 1939): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
I/Process ( 1939): Sending signal. PID: 1939 SIG: 9
D/ConnectivityService(  880): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@80aa871)
D/ConnectivityService(  880): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  880): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
I/ActivityManager(  880): Process com.google.android.gms (pid 1939) has died
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 1000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20999ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 20999ms

```
