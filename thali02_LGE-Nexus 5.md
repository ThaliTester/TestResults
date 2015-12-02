#### Test 52383621d5a0cb8_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3210): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3210):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3210):   adb logcat -s GAv4
W/GAv4    ( 3210): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3210): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3210): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3210): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
E/SQLiteLog( 3210): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,--------- beginning of system
W/ResourcesManager( 3210): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3210): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2703): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  760): Killing 2108:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3210): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 3210): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3210): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2108/cgroup.procs: No such file or directory
V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3268): 
D/AndroidRuntime( 3268): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3268): CheckJNI is OFF
D/AndroidRuntime( 3268): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3291 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3268): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/Icing   ( 1667): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/WebViewFactory( 3291): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/Icing   ( 1667): Loaded CLD2 Version V2.0 - 20141016
I/LibraryLoader( 3291): Time to load native libraries: 5 ms (timestamps 7991-7996)
I/LibraryLoader( 3291): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3291): Binding Chromium to main looper Looper (main, tid 1) {3d4d3435}
I/LibraryLoader( 3291): Expected native library version number "",actual native library version number ""
I/chromium( 3291): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3291): Initializing chromium process, singleProcess=true
W/art     ( 3291): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3291): ApplicationContext is null in ApplicationStatus
W/chromium( 3291): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3291): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3291): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3291): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Icing   ( 1667): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21bd04d7:true
W/art     ( 3291): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3291): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3291): CordovaWebView is running on device made by: LGE
W/art     ( 3291): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3291): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3291): Render dirty regions requested: true
D/Atlas   ( 3291): Validating map...
W/chromium( 3291): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3291): Initialized EGL, version 1.4
D/OpenGLRenderer( 3291): Enabling debug mode 0
W/BindingManager( 3291): Cannot call determinedVisibility() - never saw a connection for the pid: 3291
W/IInputConnectionWrapper( 3291): showStatusIcon on inactive InputConnection
I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +421ms (total +56s45ms)
D/JsMessageQueue( 3291): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3291): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
D/JX-Cordova( 3291): jxcore cordova android initializing
I/ActivityManager(  760): Killing 2661:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2661/cgroup.procs: No such file or directory
,W/jxcore-log( 3291): Initializing JXcore engine
W/jxcore-log( 3291): JXcore engine is ready
,W/jxcore-log( 3291): Starting JXcore engine
,W/.test.thalitest( 3291): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9364]" dev="sockfs" ino=9364 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3291): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3291): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8076]" dev="sockfs" ino=8076 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3291): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19930]" dev="sockfs" ino=19930 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3291): Platform android
W/jxcore-log( 3291): 
W/jxcore-log( 3291): Process ARCH arm
W/jxcore-log( 3291): 
,I/jxcore-log( 3291): JXcore Cordova bridge is ready!
I/jxcore-log( 3291): 
,W/jxcore-log( 3291): JXcore engine is started
,I/Choreographer( 3291): Skipped 112 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3291): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3291): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 3291): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}],
,I/chromium( 3291): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  760): Killing 2606:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2606/cgroup.procs: No such file or directory
,W/PluginManager( 3291): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 28ms. Plugin should use CordovaInterface.getThreadPool().
,V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1397): Vacuum at: now=1449056467845 tag=VacuumService
,D/Finsky  ( 2703): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2703): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/UdcCache:FPQuery( 1667): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1397): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1397): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1397): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1397): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1397): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1397):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1397): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1397): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1397): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1397): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1397): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1397): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1397): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/GCM     ( 1397): GCM message com.google.android.gms 0:1449056471064251%136ddda6f9fd7ecd
,I/GCM     ( 1667): Message from 745476177629 null
,I/GCoreUlr( 1518): GCM message received Intent { act=com.google.android.c2dm.intent.RECEIVE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.location.reporting.service.GcmBroadcastReceiver (has extras) }
,I/GCoreUlr( 1518): Received GCM notification for account#2# timestamp:1449056471057
I/GCoreUlr( 1518): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_INSISTENT_SYNC cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{account=Account {name=thalitester@gmail.com, type=com.google}, label=GcmBroadcastReceiver}]
,I/GCoreUlr( 1518): DispatchingService.onCreate()
,I/art     (  760): Explicit concurrent mark sweep GC freed 22149(1018KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.648ms total 62.668ms
,W/BaseAppContext( 1518): Using Auth Proxy for data requests.
,I/GCoreUlr( 1518): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/art     ( 1518): Explicit concurrent mark sweep GC freed 25043(1483KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 19MB/32MB, paused 1.157ms total 24.796ms
,E/DataBuffer( 1518): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@289148fa)
,I/GCoreUlr( 1518): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1518): Unbound from all location providers
,I/GCoreUlr( 1518): DispatchingService.onDestroy()
I/GCoreUlr( 1518): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1518): Stopping handler for UlrDispSvcSlow
,I/GCoreUlr( 1518): Unbound from all location providers
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3427
W/ProcessCpuTracker(  760): Skipping unknown process pid 3430
W/ProcessCpuTracker(  760): Skipping unknown process pid 3442
W/ProcessCpuTracker(  760): Skipping unknown process pid 3443
,I/ClearcutLoggerApiImpl( 1518): disconnect managed GoogleApiClient
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3451 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3451): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3451):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3451):   adb logcat -s GAv4
,W/GAv4    ( 3451): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3451): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3451): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2796:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2796/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2766:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  760): Client connection lost with reason: 4
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2766/cgroup.procs: No such file or directory
,W/bt-smp  ( 2137): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2137): Plain text(LSB ~ MSB) = e7 e6 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2137): Encrypted text(LSB ~ MSB) = 81 9c 1c a8 71 a7 47 dc 43 3d ff 35 b9 0d 5a fe 
,W/bt-btm  ( 2137): Stopping oneshot timer
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,I/ActivityManager(  760): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3491 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3491): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3491): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3491): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 3491): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3491): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3491): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3542): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads234061279.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads234061279.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3542): dex2oat took 43.739ms (threads: 4)
,W/InstanceID/Rpc( 3491): Found 10008
,I/ActivityManager(  760): Killing 2634:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2634/cgroup.procs: No such file or directory
,I/ProcessStatsService(  760): Prepared write state in 6ms
,I/ProcessStatsService(  760): Prepared write state in 3ms
,W/bt-smp  ( 2137): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2137): Plain text(LSB ~ MSB) = f0 f7 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2137): Encrypted text(LSB ~ MSB) = 37 d4 95 9f 25 b7 c6 7b 35 35 72 37 11 59 1a 7e 
W/bt-btm  ( 2137): Stopping oneshot timer
,I/EventLogService( 1667): Aggregate from 1449055800075 (log), 1449055800075 (data)
,I/ProcessStatsService(  760): Pruning old procstats: /data/system/procstats/state-2015-12-01-12-15-47.bin
,I/art     ( 1397): Explicit concurrent mark sweep GC freed 69593(3MB) AllocSpace objects, 19(327KB) LOS objects, 39% free, 21MB/35MB, paused 677us total 35.413ms
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager(  760): Killing 1382:android.process.acore/u0a4 (adj 13): empty for 1814s
I/ActivityManager(  760): Killing 3071:com.google.android.gms:car/u0a8 (adj 13): empty for 1821s
I/ActivityManager(  760): Killing 2067:com.android.providers.calendar/u0a2 (adj 13): empty for 1822s
I/ActivityManager(  760): Killing 1915:com.google.android.talk/u0a54 (adj 13): empty for 1846s
I/ActivityManager(  760): Killing 2818:com.google.android.music:main/u0a60 (adj 15): empty for 1847s
I/ActivityManager(  760): Killing 2043:com.google.android.calendar/u0a31 (adj 15): empty for 1852s
W/libprocessgroup(  760): failed to open /acct/uid_10008/pid_3071/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10002/pid_2067/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10054/pid_1915/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10060/pid_2818/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10031/pid_2043/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10004/pid_1382/cgroup.procs: No such file or directory
V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3640): 
D/AndroidRuntime( 3640): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3640): CheckJNI is OFF
D/AndroidRuntime( 3640): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 3291:com.test.thalitest/u0a270 (adj 11): stop com.test.thalitest
W/PackageSettings(  760): Skipping PackageSetting{3bbabe7d com.example.hello/10277} due to missing metadata
W/ActivityManager(  760): Spurious death for ProcessRecord{3a6f237b 3291:com.test.thalitest/u0a270}, curProc for 3291: null
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1283): Explicit concurrent mark sweep GC freed 33110(1438KB) AllocSpace objects, 15(1417KB) LOS objects, 37% free, 26MB/42MB, paused 504us total 24.268ms
I/Keyboard.Facilitator( 1099): resetDictionaries() : en_US
W/GeofencerStateMachine( 1518): Ignoring removeGeofence because network location is disabled.
I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
I/art     (  760): Explicit concurrent mark sweep GC freed 19966(1301KB) AllocSpace objects, 11(252KB) LOS objects, 33% free, 27MB/41MB, paused 1.175ms total 57.024ms
I/art     (  760): WaitForGcToComplete blocked for 19.167ms for cause Explicit
I/art     ( 1415): Explicit concurrent mark sweep GC freed 11468(873KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 300us total 92.368ms
I/ActivityManager(  760): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3665 uid=10004 gids={50004, 9997} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1099): run()
I/Decoder ( 1099): createOrResetDecoder
I/ConfigService( 1397): onCreate
D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.MainLanguageModelLoader( 1099): run()
D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
I/art     (  760): Explicit concurrent mark sweep GC freed 5702(306KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.491ms total 124.639ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1099): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1099): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1099): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1099): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1099): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1099): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1099): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1099): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1099): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1099): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1099): run()
I/StatsUtilsManager( 1099): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1099): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 3665): Cleaning up data for package: com.test.thalitest
I/UpdateIcingCorporaServi( 1415): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1283): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@35c590ca new=com.google.android.velvet.VelvetApplication@35c590ca
I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3700 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ContactLocale( 3665): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Launcher( 1283): Deferring update until onResume
D/AndroidRuntime( 3640): Shutting down VM
W/ResourcesManager( 1283): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1283): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1283): Deferring update until onResume
W/ContextImpl( 3700): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/UpdateIcingCorporaServi( 1415): UpdateCorporaTask done [took 419 ms] updated apps [took 419 ms] 
D/PackageBroadcastService( 1667): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1667): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1667): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1667): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1667): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1667): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1397): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1397): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1667): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1667): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1667): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1667): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1667): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1667): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1667): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1667): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1667): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1667): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1667): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1667): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1667): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1667): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3750 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/ActivityManager(  760): Killing 1480:com.google.android.partnersetup/u0a13 (adj 15): empty for 1816s
W/libprocessgroup(  760): failed to open /acct/uid_10013/pid_1480/cgroup.procs: No such file or directory
W/BaseAppContext( 1667): Using Auth Proxy for data requests.
W/BaseAppContext( 1667): Using Auth Proxy for data requests.
I/GMPM-SVC( 1667): App measurement is starting up
I/PeopleContactsSync( 1667): CP2 sync disabled
I/Icing   ( 1667): doRemovePackageData com.test.thalitest
E/SQLiteLog( 1667): (3850) statement aborts at 22: [DELETE FROM events WHERE app_id=?] disk I/O error
E/GMPM-SVC( 1667): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.d.d(SourceFile:911)
E/SharedPreferencesImpl( 1667): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SQLiteDatabase( 3750): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 3750): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3750): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 3750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3750): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 3750): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 3750): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/SQLiteDatabase( 3750): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 3750): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 3750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/SQLiteDatabase( 3750): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 3750): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/SQLiteDatabase( 3750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3750): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3750): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/SQLiteDatabase( 3750): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3750): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3750): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/SQLiteDatabase( 3750): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
D/AndroidRuntime( 3750): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 3750): FATAL EXCEPTION: main
E/AndroidRuntime( 3750): Process: com.android.documentsui, PID: 3750
E/AndroidRuntime( 3750): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/AndroidRuntime( 3750): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 3750): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/AndroidRuntime( 3750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3750): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3750): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 3750): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 3750): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 3750): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 3750): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/AndroidRuntime( 3750): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3750): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 3750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 3750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3750): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3750): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 3750): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 3750): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/AndroidRuntime( 3750): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 3750): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 3750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/AndroidRuntime( 3750): 	... 9 more
I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3779 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  760): Killing 3045:com.android.defcontainer/u0a5 (adj 15): empty for 1813s

```
