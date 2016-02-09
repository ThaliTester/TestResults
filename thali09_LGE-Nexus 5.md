#### Test 58751238ee11130_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/iu.UploadsManager( 1322): num queued entries: 0
I/iu.UploadsManager( 1322): num updated entries: 0
I/iu.SyncManager( 1322): NEXT; no task
D/dalvikvm( 2343): GC_CONCURRENT freed 279K, 2% free 17545K/17856K, paused 5ms+2ms, total 41ms
V/AlarmClock( 1774): AlarmInitReceiver android.intent.action.TIME_SET
I/AlarmClock( 1774): Displaying next alarm time: ''
V/AlarmClock( 1774): AlarmInitReceiver finished
D/dalvikvm( 1733): GC_CONCURRENT freed 292K, 2% free 16793K/17116K, paused 3ms+1ms, total 18ms
--------- beginning of /dev/log/system
I/ActivityManager(  774): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2390 uid=10068 gids={50068}
D/dalvikvm(  182): GC_EXPLICIT freed 42K, 1% free 16698K/16772K, paused 1ms+1ms, total 15ms
D/dalvikvm( 2390): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x4280bd68, skipping init
D/TimeService( 2390): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1455027643389
D/        ( 2390): TimeServiceNative: User Time to be set is 1455027643389
D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+1ms, total 13ms
D/QC-time-services( 2390): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2390): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2390): Lib:time_genoff_operation: pargs->ts_val = 1455027643389
D/QC-time-services( 2390): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  198): Daemon: Connection accepted:time_genoff
D/QC-time-services(  198): Daemon:Received base = 2, unit = 1, operation = 0,value = 1455027643389
D/QC-time-services(  198): Daemon:genoff_opr: Base = 2, val = 1455027643389, operation = 0
D/QC-time-services(  198): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/1/71 8:25:24
D/QC-time-services(  198): Daemon:Value read from RTC seconds = 39342324000
D/QC-time-services(  198): Daemon:new time 1455027643389 
D/QC-time-services(  198): Daemon: delta 1415685319389 genoff 1415685319389 
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1415685319389 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  198): Updating the TOD offset
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1415685319389 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+1ms, total 13ms
D/QC-time-services(  198): Daemon:Update to modem bit set
D/QC-time-services(  198): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  198): Daemon: Base = 2, Value being sent to MODEM = 1139062843389
E/QC-time-services( 2390): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  198): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
D/QC-time-services(  198): Daemon: Time-services: Waiting to acceptconnection
I/CheckinService( 1322): Checkin interval check for package: unspecified last checkin: 1454991096946 min interval config: 0 actual interval: 36546470
D/dalvikvm(  991): GC_CONCURRENT freed 539K, 4% free 18624K/19260K, paused 3ms+2ms, total 22ms
I/Babel   ( 2101): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  774): Killing 1798:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
I/ActivityManager(  774): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
I/ActivityManager(  774): Resuming delayed broadcast
I/ActivityManager(  774): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/dalvikvm( 2101): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2101): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2101): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2101): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2101): VFY: unable to resolve instance field 36
D/dalvikvm( 2101): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2101): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2101): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2101): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2101): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2101): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2101): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c1a1f8
D/dalvikvm( 2101): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c1a1f8
D/dalvikvm( 2101): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c1a1f8, skipping init
D/dalvikvm( 2101): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c1a1f8
D/dalvikvm( 2101): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c1a1f8
V/JNIHelp ( 2101): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  774): Resuming delayed broadcast
D/MusicLifecycle( 2195): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@428bb108 and intent Intent { act=com.google.android.music.IMPORT_COMPLETE flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
D/dalvikvm( 2101): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c1a1f8
D/dalvikvm( 2101): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42c1a1f8
D/dalvikvm( 2101): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c1a1f8
D/dalvikvm( 2101): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42c1a1f8
D/MusicLifecycle( 2195): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
I/ActivityManager(  774): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
D/WearableService(  991): callingUid 10007, callindPid: 991
D/MusicLifecycle( 2195): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
E/GmsUtils( 2195): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/GmsUtils( 2195): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/MusicLifecycle( 2195): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
D/MusicLifecycle( 2195): com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@428bb108 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
D/MusicLifecycle( 2195): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
I/ActivityManager(  774): Resuming delayed broadcast
I/ActivityManager(  774): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
D/MusicLifecycle( 2195): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
D/MusicLifecycle( 2195): com.google.android.music.download.TrackDownloadQueueService generated event: Service created
D/MusicLifecycle( 2195): com.google.android.music.download.cache.TrackCacheService generated event: Service created
I/MusicLeanback( 2195): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2195): Stop autocaching.
I/ProviderInstaller( 2101): Installed default security provider GmsCore_OpenSSL
D/MusicLifecycle( 2195): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@428bb108 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
I/ActivityManager(  774): Resuming delayed broadcast
I/ActivityManager(  774): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
D/MusicLifecycle( 2195): com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
D/MusicLifecycle( 2195): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
D/MusicLifecycle( 2195): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
D/MusicLifecycle( 2195): com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
E/GmsUtils( 2195): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/GmsUtils( 2195): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/MusicLifecycle( 2195): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
I/ActivityManager(  774): Resuming delayed broadcast
I/InputReader(  774): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  774):   Scheme: "sms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  774):   Scheme: "smsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  774):   Scheme: "mms"
I/ActivityManager(  774): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
D/ConnectivityService(  774): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  774):   Scheme: "mmsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/ActivityManager(  774): Resuming delayed broadcast
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  774):   Scheme: "sms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  774):   Scheme: "smsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/ActivityManager(  774): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2435 uid=10014 gids={50014, 3003, 1028, 1015}
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  774):   Scheme: "mms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  774):   Scheme: "mmsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/GCoreNlp(  991): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/Finsky  ( 2435): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/dalvikvm( 2435): GC_CONCURRENT freed 241K, 2% free 16900K/17172K, paused 3ms+1ms, total 14ms
D/Finsky  ( 2435): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 2435): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2435): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/dalvikvm( 2435): GC_CONCURRENT freed 257K, 2% free 17095K/17380K, paused 2ms+2ms, total 12ms
D/Finsky  ( 2435): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2435): [1] 2.run: Finished loading 1 libraries.
I/Icing.InternalIcingCorporaProvider( 1202): Updating corpora: A: com.google.android.gms, C: MAYBE
D/Finsky  ( 2435): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/Launcher( 1058): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42804b98 new=com.google.android.velvet.VelvetApplication@42804b98
I/ActivityManager(  774): Delay finish: com.google.android.googlequicksearchbox/com.android.launcher3.PackageChangedReceiver
D/Finsky  ( 2435): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  774): Resuming delayed broadcast
I/ActivityManager(  774): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  774): Resuming delayed broadcast
I/ActivityManager(  774): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  774): Resuming delayed broadcast
D/PackageBroadcastService( 1322): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1322): Null package name or gms related package.  Ignoreing.
D/dalvikvm( 1322): GC_CONCURRENT freed 510K, 3% free 18670K/19200K, paused 2ms+3ms, total 19ms
I/Icing   ( 1322): updateResources: need to parse f{com.google.android.gms}
D/dalvikvm( 1322): GC_CONCURRENT freed 589K, 4% free 18655K/19276K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 1202): GC_CONCURRENT freed 226K, 2% free 18451K/18708K, paused 2ms+1ms, total 13ms
I/Icing.InternalIcingCorporaProvider( 1202): UpdateCorporaTask done [took 279 ms] updated apps [took 279 ms] 
D/AndroidRuntime( 2481): 
D/AndroidRuntime( 2481): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2481): CheckJNI is OFF
D/dalvikvm( 2481): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2481): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2481): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2481): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2481): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2481): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/CaptivePortalTracker(  774): DelayedCaptiveCheckState{ when=-5ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/CaptivePortalTracker(  774): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  774): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/ActivityThread(  774): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/AndroidRuntime( 2481): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 2481): Shutting down VM
I/AndroidRuntime( 2481): NOTE: attach of thread 'Binder_2' failed
D/dalvikvm( 2481): GC_CONCURRENT freed 96K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  774): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2481
D/CaptivePortalTracker(  774): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  774): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  774): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/CaptivePortalTracker(  774): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  774): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
D/dalvikvm(  774): GC_CONCURRENT freed 1422K, 6% free 24297K/25756K, paused 3ms+4ms, total 46ms
,I/Icing   ( 1322): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/dalvikvm( 1322): GC_CONCURRENT freed 416K, 3% free 18778K/19276K, paused 4ms+5ms, total 37ms
,I/Icing   ( 1322): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/Icing   ( 1322): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,I/Icing   ( 1322): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/ActivityManager(  774): Waited long enough for: ServiceRecord{42ee3610 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  774): Waited long enough for: ServiceRecord{42f6e928 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  774): Killing 1869:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  774): Killing 1095:com.android.printspooler/u0a64 (adj 15): empty #17
,I/CheckinService( 1322): Done disabling old GoogleServicesFramework version
,D/InitAlarmsService( 1733): Clearing and rescheduling alarms.
,I/ActivityManager(  774): Killing 1902:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  774): Service ServiceRecord{42f746b8 u0 com.google.android.youtube/com.google.android.libraries.youtube.offline.transfer.service.OfflineTransferService} in process ProcessRecord{42f55e38 1902:com.google.android.youtube/u0a71} not same as in map: null
,V/GLSActivity( 1082): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1082): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1082): GC_CONCURRENT freed 383K, 4% free 18017K/18600K, paused 1ms+1ms, total 21ms
,D/dalvikvm( 2435): GC_CONCURRENT freed 223K, 2% free 17256K/17512K, paused 3ms+0ms, total 12ms
,D/dalvikvm( 2435): GC_CONCURRENT freed 275K, 2% free 17381K/17692K, paused 2ms+2ms, total 13ms
,D/dalvikvm( 2435): GC_CONCURRENT freed 134K, 1% free 17633K/17808K, paused 2ms+1ms, total 11ms
,D/dalvikvm( 2435): GC_CONCURRENT freed 120K, 1% free 17904K/18080K, paused 2ms+0ms, total 12ms
,D/dalvikvm( 2435): GC_CONCURRENT freed 236K, 2% free 18095K/18396K, paused 2ms+0ms, total 13ms
,D/dalvikvm( 2435): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2435): GC_FOR_ALLOC freed 62K, 2% free 18159K/18524K, paused 19ms, total 19ms
,D/dalvikvm( 2435): GC_FOR_ALLOC freed 183K, 3% free 18221K/18652K, paused 18ms, total 18ms
,D/dalvikvm( 2435): GC_FOR_ALLOC freed 62K, 2% free 18285K/18652K, paused 14ms, total 14ms
,D/dalvikvm( 2435): GC_FOR_ALLOC freed 179K, 3% free 18346K/18780K, paused 10ms, total 10ms
,D/dalvikvm( 2435): GC_CONCURRENT freed 276K, 2% free 18612K/18928K, paused 4ms+3ms, total 30ms
,D/dalvikvm( 2435): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2435): GC_CONCURRENT freed 194K, 2% free 19061K/19284K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 2435): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2435): GC_CONCURRENT freed 500K, 3% free 19350K/19880K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 2435): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/Finsky  ( 2435): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/dalvikvm( 2435): GC_CONCURRENT freed 696K, 4% free 19538K/20268K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 2435): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 2435): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 2435): WAIT_FOR_CONCURRENT_GC blocked 13ms
,V/GLSActivity( 1082): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1082): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2435): Failed write_ctrl(u 52) res=-1 errno=22
,I/qtaguid ( 2435): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2435): untagSocket(52) failed with errno -22
,D/dalvikvm( 2435): GC_CONCURRENT freed 555K, 3% free 19839K/20436K, paused 2ms+2ms, total 20ms
,D/Finsky  ( 2435): [1] DailyHygiene.flushEventLogs: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/dalvikvm( 2195): GC_CONCURRENT freed 331K, 2% free 17892K/18256K, paused 2ms+1ms, total 29ms
,D/dalvikvm( 2435): GC_CONCURRENT freed 1101K, 6% free 19690K/20832K, paused 3ms+2ms, total 34ms
,D/Finsky  ( 2435): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  774): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  774): Done.
,D/ConnectivityService(  774): Setting timer for 720seconds
,D/dalvikvm( 1082): GC_CONCURRENT freed 380K, 3% free 18044K/18600K, paused 1ms+0ms, total 16ms
,I/VacuumService(  991): Vacuum at: now=1455027702791 tag=VacuumService
,D/dalvikvm( 1082): GC_CONCURRENT freed 409K, 3% free 18056K/18600K, paused 1ms+2ms, total 18ms
,I/PhenotypeConfigurator(  991): Scheduling Phenotype for one-off execution 7406 seconds from now (1455027703090)
,D/GetConfigurationSnapshotOperation(  991): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm(  991): GC_CONCURRENT freed 454K, 3% free 18770K/19320K, paused 1ms+2ms, total 22ms
,I/PhenotypeFlagCommitter(  991): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  991): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  991): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  991): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  991): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  991): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  991): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  991): Using platform SSLCertificateSocketFactory
,I/dalvikvm(  991): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm(  991): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  991): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm(  991): GC_CONCURRENT freed 592K, 4% free 18890K/19580K, paused 3ms+4ms, total 32ms
,D/dalvikvm(  991): GC_CONCURRENT freed 533K, 4% free 18998K/19624K, paused 2ms+2ms, total 19ms
,D/dalvikvm(  991): GC_CONCURRENT freed 564K, 4% free 19134K/19792K, paused 2ms+3ms, total 20ms
,D/dalvikvm(  991): GC_CONCURRENT freed 749K, 5% free 19152K/19996K, paused 3ms+3ms, total 21ms
,D/dalvikvm(  991): GC_CONCURRENT freed 813K, 5% free 19086K/20052K, paused 3ms+3ms, total 20ms
,D/dalvikvm(  991): GC_CONCURRENT freed 739K, 5% free 19167K/20052K, paused 3ms+6ms, total 37ms
,D/dalvikvm(  991): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm(  991): GC_CONCURRENT freed 793K, 5% free 19144K/20084K, paused 2ms+3ms, total 23ms
,I/rmt_storage(  177): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb73db160
I/rmt_storage(  177): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  177): wakelock acquired: 1, error no: 2
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1220694320)
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1220694320) wakelock released: 1, error no: 0
I/rmt_storage(  177): 
,I/rmt_storage(  177): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb73db160
,I/PowerManagerService(  774): Going to sleep due to screen timeout...
,I/Adreno-EGL(  774): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/PermissionCache(  181): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (168 us)
,I/ClearcutLoggerApiImpl( 1082): disconnect managed GoogleApiClient
,D/SurfaceFlinger(  181): Screen released, type=0 flinger=0xb84ae450
,D/qdhwcomposer(  181): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  181): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  774): Excessive delay in blankDisplay() while turning screen off: 287ms
,V/KeyguardServiceDelegate(  774): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@43027318)
,V/KeyguardServiceDelegate(  774): **** SHOWN CALLED ****
I/WindowManager(  774): No lock screen! windowToken=null
,I/SearchController( 1202): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1202): mic_close
,D/NfcService( 1040): NFC-C OFF
,I/ActivityManager(  774): Killing 2140:com.google.android.apps.maps/u0a57 (adj 15): empty #17
,I/ActivityManager(  774): Killing 2088:com.google.android.exchange/u0a37 (adj 15): empty #18
,I/MicroHotwordRecognitionRunner( 1202): Stopping hotword detection.
,I/MicroHotwordRecognitionRunner( 1202): Hotword detection finished
,D/dalvikvm( 1202): GC_CONCURRENT freed 1105K, 6% free 17883K/19008K, paused 2ms+1ms, total 19ms
,D/ConnectivityService(  774): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  774): Done.
,D/ConnectivityService(  774): Setting timer for 720seconds
,D/ConnectivityService(  774): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/dalvikvm(  991): GC_FOR_ALLOC freed 372K, 6% free 18873K/20076K, paused 16ms, total 18ms
,D/dalvikvm( 2343): GC_CONCURRENT freed 238K, 2% free 17741K/18008K, paused 7ms+2ms, total 33ms
,E/BackupPromoManager( 2343): Invalid account id.
,D/dalvikvm(  774): GC_EXPLICIT freed 1510K, 7% free 24255K/25804K, paused 2ms+4ms, total 51ms
,TIME-OUT KILL (timeout was 1200000ms)
```
