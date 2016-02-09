#### Test 5841644866d9c0e_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/system
D/ConnectivityService(  758): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
--------- beginning of /dev/log/main
D/CaptivePortalTracker(  758): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/CaptivePortalTracker(  758): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  758): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/ActivityThread(  758): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/CaptivePortalTracker(  758): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  758): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  758): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/CaptivePortalTracker(  758): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  758): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AndroidRuntime( 2450): 
D/AndroidRuntime( 2450): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2450): CheckJNI is OFF
D/dalvikvm( 2450): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2450): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2450): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2450): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2450): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2450): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2450): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 2450): Shutting down VM
D/dalvikvm( 2450): GC_CONCURRENT freed 96K, 15% free 586K/684K, paused 0ms+0ms, total 3ms
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2450
,I/ActivityManager(  758): Waited long enough for: ServiceRecord{42dc3f38 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  758): Waited long enough for: ServiceRecord{42ce2f28 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  758): Killing 1826:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/CheckinService( 1327): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  758): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=2474 uid=10014 gids={50014, 3003, 1028, 1015}
,D/InitAlarmsService( 1766): Clearing and rescheduling alarms.
,D/Finsky  ( 2474): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/ActivityManager(  758): Killing 1098:com.android.printspooler/u0a64 (adj 15): empty #17
,D/dalvikvm( 2474): GC_CONCURRENT freed 232K, 2% free 16891K/17152K, paused 1ms+1ms, total 14ms
,D/Finsky  ( 2474): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 2474): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2474): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 2474): GC_CONCURRENT freed 267K, 2% free 17100K/17376K, paused 2ms+2ms, total 19ms
,D/Finsky  ( 2474): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2474): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 2474): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2474): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1120): GC_CONCURRENT freed 416K, 4% free 17939K/18636K, paused 1ms+1ms, total 16ms
,D/dalvikvm( 2474): GC_CONCURRENT freed 222K, 2% free 17298K/17552K, paused 3ms+1ms, total 12ms
,D/dalvikvm( 2474): GC_CONCURRENT freed 387K, 3% free 17297K/17716K, paused 2ms+1ms, total 11ms
,D/dalvikvm( 2474): GC_CONCURRENT freed 212K, 2% free 17487K/17728K, paused 2ms+1ms, total 11ms
,D/dalvikvm( 2474): GC_CONCURRENT freed 150K, 2% free 17821K/18016K, paused 1ms+2ms, total 14ms
,D/dalvikvm( 2474): GC_CONCURRENT freed 236K, 2% free 18061K/18356K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 2474): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 2474): GC_FOR_ALLOC freed 92K, 2% free 18157K/18484K, paused 13ms, total 13ms
,D/dalvikvm( 2474): GC_FOR_ALLOC freed 183K, 3% free 18219K/18612K, paused 11ms, total 11ms
,D/dalvikvm( 2474): GC_FOR_ALLOC freed 241K, 3% free 18344K/18740K, paused 10ms, total 11ms
,D/dalvikvm( 2474): GC_CONCURRENT freed 246K, 2% free 18540K/18868K, paused 2ms+0ms, total 13ms
,D/dalvikvm( 2474): GC_CONCURRENT freed 157K, 1% free 18900K/19088K, paused 2ms+1ms, total 15ms
,D/dalvikvm( 2474): GC_CONCURRENT freed 459K, 3% free 19125K/19616K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 2474): GC_CONCURRENT freed 241K, 2% free 19633K/19904K, paused 2ms+1ms, total 18ms
,D/Finsky  ( 2474): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,V/GLSActivity( 1120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2474): GC_CONCURRENT freed 1060K, 6% free 19465K/20580K, paused 1ms+1ms, total 18ms,
,I/qtaguid ( 2474): Failed write_ctrl(u 52) res=-1 errno=22
,I/qtaguid ( 2474): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2474): untagSocket(52) failed with errno -22
,D/dalvikvm( 2474): GC_CONCURRENT freed 443K, 4% free 19859K/20580K, paused 2ms+1ms, total 28ms
,D/Finsky  ( 2474): [1] DailyHygiene.flushEventLogs: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  758): Killing 1017:com.google.android.keep/u0a52 (adj 15): empty #17
,D/dalvikvm(  758): GC_CONCURRENT freed 1487K, 6% free 24256K/25780K, paused 4ms+6ms, total 109ms
,D/dalvikvm( 2131): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2131): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2131): VFY: replacing opcode 0x62 at 0x000a
,D/MusicLifecycle( 2236): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4273b3a8 and intent Intent { act=com.google.android.music.IMPORT_COMPLETE flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
D/dalvikvm( 2131): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2131): VFY: unable to resolve instance field 36
,D/dalvikvm( 2131): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2131): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 2131): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2131): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2131): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2131): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 2131): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427ad940
D/dalvikvm( 2131): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427ad940
,D/dalvikvm( 2131): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427ad940, skipping init
,D/dalvikvm( 2131): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427ad940
,D/dalvikvm( 2131): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427ad940
,V/JNIHelp ( 2131): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MusicLifecycle( 2236): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,D/WearableService( 1002): callingUid 10007, callindPid: 1002
,D/MusicLifecycle( 2236): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,D/MusicLifecycle( 2236): com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4273b3a8 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,D/MusicLifecycle( 2236): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,D/MusicLifecycle( 2236): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,D/MusicLifecycle( 2236): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4273b3a8 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,D/AlertReceiver( 1766): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
,D/MusicLifecycle( 2236): com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,D/AlertService( 1766): 0 Action = android.intent.action.PROVIDER_CHANGED
D/dalvikvm( 2131): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427ad940
,D/dalvikvm( 2131): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x427ad940
,D/MusicLifecycle( 2236): com.google.android.music.download.cache.TrackCacheService generated event: Service created
D/dalvikvm( 2131): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427ad940
,D/dalvikvm( 2131): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427ad940
I/MusicLeanback( 2236): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 2236): Stop autocaching.
I/ActivityManager(  758): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
D/MusicLifecycle( 2236): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
E/GmsUtils( 2236): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/GmsUtils( 2236): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/GmsUtils( 2236): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/MusicLifecycle( 2236): com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
D/MusicLifecycle( 2236): com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
D/dalvikvm( 1766): GC_CONCURRENT freed 297K, 2% free 16796K/17124K, paused 3ms+2ms, total 19ms
,E/GmsUtils( 2236): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/MusicLifecycle( 2236): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,I/ProviderInstaller( 2131): Installed default security provider GmsCore_OpenSSL
,I/Icing.InternalIcingCorporaProvider( 1224): Updating corpora: A: com.google.android.gms, C: MAYBE
,W/Launcher( 1083): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@4264bac0 new=com.google.android.velvet.VelvetApplication@4264bac0
,D/PackageBroadcastService( 1327): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1327): Null package name or gms related package.  Ignoreing.
,D/dalvikvm( 1002): GC_CONCURRENT freed 551K, 4% free 18688K/19336K, paused 1ms+2ms, total 25ms
,I/Icing   ( 1327): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1327): GC_CONCURRENT freed 502K, 3% free 18646K/19180K, paused 3ms+1ms, total 16ms
,D/dalvikvm( 1327): GC_CONCURRENT freed 600K, 4% free 18636K/19268K, paused 4ms+4ms, total 31ms
,D/dalvikvm( 1224): GC_CONCURRENT freed 240K, 3% free 18630K/19108K, paused 1ms+1ms, total 12ms
,I/Icing.InternalIcingCorporaProvider( 1224): UpdateCorporaTask done [took 305 ms] updated apps [took 305 ms] 
,I/Icing   ( 1327): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/Icing   ( 1327): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1327): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/Icing   ( 1327): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,I/Icing   ( 1327): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,D/dalvikvm( 2236): GC_CONCURRENT freed 365K, 3% free 17898K/18292K, paused 5ms+1ms, total 18ms
,D/dalvikvm( 1327): GC_CONCURRENT freed 528K, 4% free 18633K/19268K, paused 1ms+3ms, total 18ms
,D/AlertService( 1766): Beginning updateAlertNotification
,D/AlertService( 1766): No fired or scheduled alerts
,D/AlertService( 1766): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1766): No events found starting within 1 week.
,D/Finsky  ( 2474): [1] 5.onFinished: Installation state replication succeeded.
,V/QcrilMsgTunnelSocket( 1900): After reading offset = 0 remaining = 4 countRead = 4
,D/QcrilMsgTunnelSocket( 1900): messageLength extracted from first 4 inputStream reads = 29
,V/QcrilMsgTunnelSocket( 1900): offset = 0 remaining = 29 countRead = 0
,V/QcrilMsgTunnelSocket( 1900): offset = 0 remaining = 29 countRead = 29
,D/QcrilMsgTunnelSocket( 1900): readRilMessage: Buffer = [B@4264d338 HexData = [0100000004040000110000005155414c434f4d4def0308000100000003]
V/QcrilMsgTunnelSocket( 1900): Read packet: 29 bytes. Data Available = 32 Position = 0
,D/QcrilMsgTunnelSocket( 1900): processResponse. message type = 1. Data Available = 28
,D/QcrilMsgTunnelSocket( 1900): ByteArray from parcel = 5155414c434f4d4def0308000100000003
D/QcrilMsgTunnelSocket( 1900): Received RIL_UNSOL_OEM_HOOK_RAW message
D/QcrilMsgTunnelSocket( 1900): Oem ID in RIL_UNSOL_OEM_HOOK_RAW is QUALCOMM
,D/QcrilMsgTunnelSocket( 1900): OEM ID check Passed
D/QcrilMsgTunnelSocket( 1900): Response ID in RIL_UNSOL_OEM_HOOK_RAW is 525295
D/QcrilMsgTunnelSocket( 1900): Response ID 525295is not served in this process.
,D/QcrilMsgTunnelSocket( 1900): To broadcast an Intent via the notifier to external apps
,V/QcrilMsgTunnelSocket( 1900): Before reading offset = 0 remaining = 4 countRead = 0
D/QcrilMsgTunnelIfaceManager( 1900): handleMessage what=0
,D/QcrilMsgTunnelIfaceManager( 1900): Broadcasting intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
,D/dalvikvm( 1036): GC_CONCURRENT freed 342K, 3% free 17066K/17436K, paused 4ms+4ms, total 41ms
,D/ConnectivityService(  758): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  758): Done.
,D/ConnectivityService(  758): Setting timer for 720seconds
,D/dalvikvm( 1120): GC_CONCURRENT freed 418K, 4% free 17994K/18636K, paused 2ms+1ms, total 30ms
,I/VacuumService( 1002): Vacuum at: now=1455019820844 tag=VacuumService
,D/dalvikvm( 1120): GC_CONCURRENT freed 484K, 4% free 17901K/18636K, paused 3ms+1ms, total 14ms
,I/PhenotypeConfigurator( 1002): Scheduling Phenotype for one-off execution 12776 seconds from now (1455019821128)
,D/GetConfigurationSnapshotOperation( 1002): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1002): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1002): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1002): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1120): GC_CONCURRENT freed 377K, 4% free 17910K/18636K, paused 3ms+2ms, total 35ms
,W/dalvikvm( 1002): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1002): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1002): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1002): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1002): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 1002): GC_CONCURRENT freed 514K, 4% free 18781K/19392K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 1002): GC_CONCURRENT freed 444K, 3% free 18931K/19512K, paused 4ms+4ms, total 25ms
,D/dalvikvm( 1002): GC_CONCURRENT freed 466K, 3% free 19151K/19712K, paused 2ms+3ms, total 20ms
,D/dalvikvm( 1002): GC_CONCURRENT freed 782K, 5% free 19210K/20084K, paused 3ms+8ms, total 40ms
,D/dalvikvm( 1002): GC_CONCURRENT freed 806K, 5% free 19171K/20084K, paused 3ms+4ms, total 22ms
,D/dalvikvm( 1002): GC_CONCURRENT freed 761K, 5% free 19164K/20084K, paused 2ms+4ms, total 21ms
,D/dalvikvm( 1002): GC_CONCURRENT freed 748K, 5% free 19155K/20084K, paused 2ms+4ms, total 21ms
,V/GLSActivity( 1120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1002): GC_FOR_ALLOC freed 399K, 6% free 18883K/20084K, paused 30ms, total 30ms
,I/rmt_storage(  177): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb846e160
I/rmt_storage(  177): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  177): wakelock acquired: 1, error no: 2
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1203314144)
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1203314144) wakelock released: 1, error no: 0
I/rmt_storage(  177): 
,I/rmt_storage(  177): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb846e160
,I/PowerManagerService(  758): Going to sleep due to screen timeout...
,I/Adreno-EGL(  758): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/PermissionCache(  181): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (816 us)
,D/SurfaceFlinger(  181): Screen released, type=0 flinger=0xb78ec450
,D/qdhwcomposer(  181): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  181): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  758): Excessive delay in blankDisplay() while turning screen off: 278ms
,V/KeyguardServiceDelegate(  758): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42e286d0)
,V/KeyguardServiceDelegate(  758): **** SHOWN CALLED ****
I/WindowManager(  758): No lock screen! windowToken=null
,I/SearchController( 1224): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1224): mic_close
,I/ActivityManager(  758): Killing 1915:com.google.android.youtube/u0a71 (adj 15): empty #17
,D/NfcService( 1072): NFC-C OFF
I/ActivityManager(  758): Killing 1878:com.lge.SprintHiddenMenu/1000 (adj 15): empty #18
,F/ActivityManager(  758): Service ServiceRecord{42d0e140 u0 com.google.android.youtube/com.google.android.libraries.youtube.offline.transfer.service.OfflineTransferService} in process ProcessRecord{42d21400 1915:com.google.android.youtube/u0a71} not same as in map: null
,I/MicroHotwordRecognitionRunner( 1224): Stopping hotword detection.
,I/MicroHotwordRecognitionRunner( 1224): Hotword detection finished
,D/dalvikvm( 1224): GC_CONCURRENT freed 1249K, 7% free 17901K/19180K, paused 2ms+1ms, total 12ms
,D/        (  758): Setting time of day to sec=1455019900
,W/        (  758): Unable to set rtc to 1455019900: Invalid argument
,D/dalvikvm(  758): GC_EXPLICIT freed 1095K, 7% free 24218K/25780K, paused 1ms+4ms, total 62ms
,V/AlarmClock( 1805): AlarmInitReceiver android.intent.action.TIME_SET
,I/AlarmClock( 1805): Displaying next alarm time: ''
,V/AlarmClock( 1805): AlarmInitReceiver finished
,I/ActivityManager(  758): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2727 uid=10052 gids={50052, 3003, 1028, 1015}
,D/dalvikvm( 2727): GC_CONCURRENT freed 177K, 2% free 16924K/17132K, paused 3ms+1ms, total 18ms
,I/ActivityManager(  758): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2745 uid=10068 gids={50068}
,D/dalvikvm( 2745): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42649fa0, skipping init
D/TimeService( 2745): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1455019901241
D/        ( 2745): TimeServiceNative: User Time to be set is 1455019901241
D/QC-time-services( 2745): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2745): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2745): Lib:time_genoff_operation: pargs->ts_val = 1455019901241
D/QC-time-services(  198): Daemon: Connection accepted:time_genoff
D/QC-time-services( 2745): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  198): Daemon:Received base = 2, unit = 1, operation = 0,value = 1455019901241
,D/QC-time-services(  198): Daemon:genoff_opr: Base = 2, val = 1455019901241, operation = 0
D/QC-time-services(  198): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/1/71 6:16:22
D/QC-time-services(  198): Daemon:Value read from RTC seconds = 39334582000
D/QC-time-services(  198): Daemon:new time 1455019901241 
D/QC-time-services(  198): Daemon: delta 1415685319241 genoff 1415685319241 
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1415685319241 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_2
,D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  198): Updating the TOD offset
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1415685319241 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  198): Daemon:Update to modem bit set
D/QC-time-services(  198): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  198): Daemon: Base = 2, Value being sent to MODEM = 1139055101241
,E/QC-time-services( 2745): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  198): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  198): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  758): Killing 2108:com.google.android.exchange/u0a37 (adj 15): empty #17
,I/CheckinService( 1327): Checkin interval check for package: unspecified last checkin: 1454991096946 min interval config: 0 actual interval: 28804314
,I/ActivityManager(  758): Killing 2188:com.google.android.apps.maps/u0a57 (adj 15): empty #17
,I/rmt_storage(  177): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb846e160
I/rmt_storage(  177): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  177): wakelock acquired: 1, error no: 2
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1203314992)
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1203314992) wakelock released: 1, error no: 0
I/rmt_storage(  177): 
,I/rmt_storage(  177): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb846e160
,D/ConnectivityService(  758): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  758): Done.
,D/ConnectivityService(  758): Setting timer for 720seconds
,I/ActivityManager(  758): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=2771 uid=10071 gids={50071, 3003, 1028, 1015}
,I/dalvikvm( 2771): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 2771): VFY: unable to resolve virtual method 573: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 2771): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 2771): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2771): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 2771): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2771): VFY: unable to resolve instance field 36
,D/dalvikvm( 2771): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2771): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2771): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2771): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2771): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2771): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 2771): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4269a0f8
D/dalvikvm( 2771): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4269a0f8
,D/dalvikvm( 2771): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4269a0f8, skipping init
,D/dalvikvm( 2771): GC_CONCURRENT freed 329K, 2% free 16829K/17164K, paused 3ms+0ms, total 18ms
,D/dalvikvm( 2771): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4269a0f8
D/dalvikvm( 2771): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4269a0f8
,V/JNIHelp ( 2771): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 2771): GC_CONCURRENT freed 336K, 2% free 17104K/17332K, paused 2ms+2ms, total 17ms
,D/dalvikvm( 2771): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4269a0f8
,D/dalvikvm( 2771): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4269a0f8
D/dalvikvm( 2771): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4269a0f8
,D/dalvikvm( 2771): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4269a0f8
,D/dalvikvm( 2771): GC_CONCURRENT freed 278K, 2% free 17361K/17596K, paused 2ms+9ms, total 27ms
,I/ProviderInstaller( 2771): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 2771): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.FragmentActivity.onBackPressed
W/dalvikvm( 2771): VFY: unable to resolve virtual method 93: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0012
,D/dalvikvm( 2771): GC_CONCURRENT freed 444K, 3% free 17378K/17856K, paused 2ms+4ms, total 18ms
,D/dalvikvm( 2771): GC_CONCURRENT freed 391K, 3% free 17488K/17912K, paused 4ms+2ms, total 20ms
,I/dalvikvm( 2771): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 2771): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 2771): GC_CONCURRENT freed 284K, 2% free 17715K/18028K, paused 4ms+3ms, total 21ms
D/dalvikvm( 2771): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 2771): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 2771): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/dalvikvm( 2771): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 2771): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 2771): VFY: replacing opcode 0x71 at 0x004e
,I/dalvikvm( 2771): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method com.google.ads.conversiontracking.a$b.getActivityBanner
W/dalvikvm( 2771): VFY: unable to resolve virtual method 544: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2771): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method com.google.ads.conversiontracking.a$b.getActivityBanner
W/dalvikvm( 2771): VFY: unable to resolve virtual method 545: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2771): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method com.google.ads.conversiontracking.a$b.getApplicationBanner
W/dalvikvm( 2771): VFY: unable to resolve virtual method 552: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2771): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method com.google.ads.conversiontracking.a$b.getApplicationBanner
W/dalvikvm( 2771): VFY: unable to resolve virtual method 553: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2771): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.ads.conversiontracking.a$b.getLeanbackLaunchIntentForPackage
W/dalvikvm( 2771): VFY: unable to resolve virtual method 569: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2771): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.ads.conversiontracking.a$b.getPackageInstaller
W/dalvikvm( 2771): VFY: unable to resolve virtual method 573: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2771): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method com.google.ads.conversiontracking.a$b.getUserBadgedDrawableForDensity
W/dalvikvm( 2771): VFY: unable to resolve virtual method 589: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2771): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method com.google.ads.conversiontracking.a$b.getUserBadgedIcon
W/dalvikvm( 2771): VFY: unable to resolve virtual method 590: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2771): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method com.google.ads.conversiontracking.a$b.getUserBadgedLabel
W/dalvikvm( 2771): VFY: unable to resolve virtual method 591: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0002
,D/dalvikvm( 2771): DexOpt: --- BEGIN 'ads316630776.jar' (bootstrap=0) ---
,D/dalvikvm( 2771): GC_CONCURRENT freed 295K, 2% free 17922K/18244K, paused 2ms+7ms, total 21ms
,W/InstanceID/Rpc( 2771): Found 10007
D/ConnectivityService(  758): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/dalvikvm( 2819): DexOpt: load 2ms, verify+opt 5ms, 188892 bytes
,I/dalvikvm( 2771): Could not find method android.content.Context.getSystemService, referenced from method com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onCreate
W/dalvikvm( 2771): VFY: unable to resolve virtual method 78: Landroid/content/Context;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0011
I/dalvikvm( 2771): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask
W/dalvikvm( 2771): VFY: unable to resolve virtual method 372: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 2771): VFY: replacing opcode 0x6e at 0x0008
D/dalvikvm( 2771): DexOpt: --- END 'ads316630776.jar' (success) ---
,D/dalvikvm( 2771): DEX prep '/data/data/com.google.android.youtube/cache/ads316630776.jar': unzip in 0ms, rewrite 51ms
,D/dalvikvm( 2771): GC_CONCURRENT freed 379K, 3% free 17966K/18372K, paused 3ms+3ms, total 24ms
,D/dalvikvm( 2771): GC_CONCURRENT freed 329K, 2% free 18073K/18432K, paused 2ms+2ms, total 17ms
,D/dalvikvm( 2771): GC_CONCURRENT freed 363K, 3% free 18146K/18544K, paused 2ms+3ms, total 16ms
,D/dalvikvm( 2771): GC_CONCURRENT freed 365K, 3% free 18178K/18572K, paused 2ms+1ms, total 14ms
,I/ActivityManager(  758): Killing 2223:com.android.settings/1000 (adj 15): empty #17
,D/dalvikvm( 1120): GC_CONCURRENT freed 321K, 4% free 17983K/18636K, paused 1ms+6ms, total 25ms
,W/ProcessCpuTracker(  758): Skipping unknown process pid 2786
,W/ProcessCpuTracker(  758): Skipping unknown process pid 2789
,TIME-OUT KILL (timeout was 1200000ms)
```
