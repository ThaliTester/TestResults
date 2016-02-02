#### Test 575312435db8e90_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  756): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2425 uid=10068 gids={50068}
--------- beginning of /dev/log/main
D/dalvikvm( 2425): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x4266fbe0, skipping init
D/TimeService( 2425): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454412262095
D/        ( 2425): TimeServiceNative: User Time to be set is 1454412262095
D/QC-time-services( 2425): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2425): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2425): Lib:time_genoff_operation: pargs->ts_val = 1454412262095
D/QC-time-services(  198): Daemon: Connection accepted:time_genoff
D/QC-time-services( 2425): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  198): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454412262095
D/QC-time-services(  198): Daemon:genoff_opr: Base = 2, val = 1454412262095, operation = 0
D/QC-time-services(  198): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/25/71 5:29:7
D/QC-time-services(  198): Daemon:Value read from RTC seconds = 38726947000
D/QC-time-services(  198): Daemon:new time 1454412262095 
D/QC-time-services(  198): Daemon: delta 1415685315095 genoff 1415685315095 
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1415685315095 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  198): Updating the TOD offset
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1415685315095 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  198): Daemon:Update to modem bit set
D/QC-time-services(  198): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  198): Daemon: Base = 2, Value being sent to MODEM = 1138447462095
E/QC-time-services( 2425): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  198): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  756): Killing 1791:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
D/QC-time-services(  198): Daemon: Time-services: Waiting to acceptconnection
I/CheckinService( 1326): Checkin interval check for package: unspecified last checkin: 1454391004844 min interval config: 0 actual interval: 21257270
I/Babel   ( 2013): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  756): Killing 1829:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
I/ActivityManager(  756): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
I/ActivityManager(  756): Delay finish: com.google.android.gm/.GmailReceiver
I/ActivityManager(  756): Resuming delayed broadcast
I/ActivityManager(  756): Delay finish: com.google.android.gm/.GmailReceiver
I/NotifUtils( 1849): Validating Notification, mapSize: 0 getAttention: true
I/NotifUtils( 1849): validateNotifications - cancelling account 61035162 / folder -317575340
I/ActivityManager(  756): Resuming delayed broadcast
I/ActivityManager(  756): Delay finish: com.google.android.gm/.GmailReceiver
I/ActivityManager(  756): Resuming delayed broadcast
D/dalvikvm( 1849): GC_CONCURRENT freed 340K, 3% free 17309K/17680K, paused 3ms+1ms, total 25ms
W/GCoreFlp( 1005): No location to return for getLastLocation()
W/FusedLocationProvider( 1005): location=null
D/GCM     (  992): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/dalvikvm( 1326): GC_CONCURRENT freed 495K, 3% free 18698K/19224K, paused 3ms+2ms, total 29ms
D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/dalvikvm(  992): GC_CONCURRENT freed 377K, 4% free 17971K/18708K, paused 2ms+1ms, total 16ms
D/AndroidRuntime( 2450): 
D/AndroidRuntime( 2450): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2450): CheckJNI is OFF
D/dalvikvm( 2450): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2450): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2450): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2450): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2450): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2450): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
I/ActivityManager(  756): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
I/ActivityManager(  756): Resuming delayed broadcast
I/ActivityManager(  756): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/dalvikvm( 2013): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2013): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2013): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2013): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2013): VFY: unable to resolve instance field 36
D/dalvikvm( 2013): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2013): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2013): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2013): VFY: replacing opcode 0x62 at 0x0047
D/MusicLifecycle( 2192): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4275e2b8 and intent Intent { act=com.google.android.music.IMPORT_COMPLETE flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
D/dalvikvm( 2013): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2013): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2013): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42776ea0
D/dalvikvm( 2013): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42776ea0
D/dalvikvm( 2013): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42776ea0, skipping init
D/dalvikvm( 2013): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42776ea0
D/dalvikvm( 2013): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42776ea0
V/JNIHelp ( 2013): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  756): Resuming delayed broadcast
D/AndroidRuntime( 2450): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 2450): Shutting down VM
D/dalvikvm( 2450): GC_CONCURRENT freed 96K, 15% free 586K/684K, paused 0ms+1ms, total 2ms
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2450
I/ActivityManager(  756): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
D/MusicLifecycle( 2192): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
D/WearableService( 1005): callingUid 10007, callindPid: 1005
D/MusicLifecycle( 2192): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
E/GmsUtils( 2192): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/dalvikvm( 2013): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42776ea0
D/dalvikvm( 2013): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42776ea0
D/dalvikvm( 2013): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42776ea0
E/GmsUtils( 2192): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/dalvikvm( 2013): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42776ea0
D/MusicLifecycle( 2192): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
D/MusicLifecycle( 2192): com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4275e2b8 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
I/ActivityManager(  756): Resuming delayed broadcast
D/MusicLifecycle( 2192): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
D/MusicLifecycle( 2192): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
D/MusicLifecycle( 2192): com.google.android.music.download.TrackDownloadQueueService generated event: Service created
I/ActivityManager(  756): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
D/MusicLifecycle( 2192): com.google.android.music.download.cache.TrackCacheService generated event: Service created
I/MusicLeanback( 2192): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2192): Stop autocaching.
I/ActivityManager(  756): Resuming delayed broadcast
D/MusicLifecycle( 2192): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4275e2b8 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
D/MusicLifecycle( 2192): com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
D/MusicLifecycle( 2192): com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
D/MusicLifecycle( 2192): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
D/MusicLifecycle( 2192): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
D/dalvikvm( 1005): GC_CONCURRENT freed 500K, 4% free 18611K/19252K, paused 3ms+5ms, total 34ms
E/GmsUtils( 2192): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/GmsUtils( 2192): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  756): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
D/MusicLifecycle( 2192): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
D/AlertReceiver( 1755): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
D/AlertService( 1755): 0 Action = android.intent.action.PROVIDER_CHANGED
I/ProviderInstaller( 2013): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  756): Resuming delayed broadcast
I/ActivityManager(  756): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  756): Waited long enough for: ServiceRecord{42d8a638 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2497 uid=10014 gids={50014, 3003, 1028, 1015}
,D/Finsky  ( 2497): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 2497): GC_CONCURRENT freed 218K, 2% free 16876K/17124K, paused 2ms+2ms, total 15ms
,D/Finsky  ( 2497): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 2497): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2497): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 2497): GC_CONCURRENT freed 275K, 2% free 17058K/17364K, paused 1ms+2ms, total 11ms
,D/Finsky  ( 2497): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2497): [1] 2.run: Finished loading 1 libraries.
,D/dalvikvm(  756): GC_EXPLICIT freed 1016K, 5% free 24150K/25204K, paused 2ms+5ms, total 48ms
,I/Icing.InternalIcingCorporaProvider( 1212): Updating corpora: A: com.google.android.gms, C: MAYBE
,W/Launcher( 1074): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42672ab0 new=com.google.android.velvet.VelvetApplication@42672ab0
,D/Finsky  ( 2497): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  756): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  756): Delaying start of: ServiceRecord{42d44200 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/Finsky  ( 2497): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  756): Resuming delayed broadcast
I/ActivityManager(  756): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  756): Resuming delayed broadcast
,D/PackageBroadcastService( 1326): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1326): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1326): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1326): GC_CONCURRENT freed 615K, 4% free 18650K/19296K, paused 3ms+2ms, total 18ms
,D/dalvikvm( 1212): GC_CONCURRENT freed 323K, 3% free 18689K/19128K, paused 3ms+3ms, total 21ms
I/Icing.InternalIcingCorporaProvider( 1212): UpdateCorporaTask done [took 289 ms] updated apps [took 289 ms] 
,I/ActivityManager(  756): Waited long enough for: ServiceRecord{42c4f650 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/Icing   ( 1326): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/dalvikvm( 1326): GC_CONCURRENT freed 531K, 4% free 18644K/19296K, paused 3ms+1ms, total 18ms
,I/Icing   ( 1326): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/Icing   ( 1326): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,I/Icing   ( 1326): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,D/AlertService( 1755): Beginning updateAlertNotification
,D/AlertService( 1755): No fired or scheduled alerts
,D/AlertService( 1755): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1755): No events found starting within 1 week.
,I/ActivityManager(  756): Killing 1889:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/CheckinService( 1326): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  756): Killing 1999:com.google.android.exchange/u0a37 (adj 15): empty #17
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  992): GC_CONCURRENT freed 480K, 4% free 17981K/18708K, paused 2ms+1ms, total 49ms
,D/dalvikvm( 2497): GC_CONCURRENT freed 189K, 2% free 17277K/17500K, paused 3ms+2ms, total 14ms
,D/dalvikvm( 2497): GC_CONCURRENT freed 366K, 3% free 17298K/17696K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 2497): GC_CONCURRENT freed 270K, 2% free 17414K/17716K, paused 2ms+1ms, total 14ms
,D/InitAlarmsService( 1755): Clearing and rescheduling alarms.
,D/dalvikvm( 2497): GC_CONCURRENT freed 118K, 1% free 17703K/17868K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 2497): GC_CONCURRENT freed 128K, 1% free 17982K/18160K, paused 2ms+2ms, total 15ms
,D/dalvikvm( 2497): GC_CONCURRENT freed 266K, 2% free 18165K/18500K, paused 2ms+1ms, total 14ms
,D/dalvikvm( 2497): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2497): GC_FOR_ALLOC freed 183K, 3% free 18228K/18628K, paused 19ms, total 19ms
,D/dalvikvm( 2497): GC_FOR_ALLOC freed 241K, 3% free 18352K/18756K, paused 19ms, total 19ms
,D/dalvikvm( 2497): GC_CONCURRENT freed 277K, 2% free 18618K/18936K, paused 1ms+2ms, total 23ms
,D/dalvikvm( 2497): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2497): GC_CONCURRENT freed 178K, 2% free 19031K/19240K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 2497): GC_CONCURRENT freed 496K, 3% free 19314K/19840K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 2497): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/Finsky  ( 2497): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/dalvikvm( 2497): GC_CONCURRENT freed 710K, 4% free 19477K/20220K, paused 4ms+2ms, total 23ms
,D/dalvikvm( 2497): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2497): WAIT_FOR_CONCURRENT_GC blocked 9ms
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2497): Failed write_ctrl(u 52) res=-1 errno=22
,I/qtaguid ( 2497): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2497): untagSocket(52) failed with errno -22
,D/dalvikvm( 2497): GC_CONCURRENT freed 525K, 3% free 19774K/20372K, paused 2ms+2ms, total 21ms
,D/Finsky  ( 2497): [1] InstallerImpl.requestInstall: Request install of com.google.android.youtube v=110156634 for auto_update
,D/Finsky  ( 2497): [1] InstallerImpl.kick: Installer kick com.google.android.youtube - starting com.google.android.youtube
,D/Finsky  ( 2497): [1] InstallerImpl.requestInstall: Request install of com.google.android.apps.docs v=60141735 for auto_update
,D/Finsky  ( 2497): [1] InstallerImpl.kick: Installer kick com.google.android.apps.docs - no action because busy.
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2497): GC_CONCURRENT freed 828K, 5% free 19909K/20772K, paused 2ms+1ms, total 37ms
,D/Finsky  ( 2497): [1] UpdateChecker.showUpdateNotifications: Notifying user [12/12] applications have updates that require approval.
,D/Finsky  ( 2497): [1] DailyHygiene.flushEventLogs: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/MarketUpdateReceiver( 1074): market has promised to install: com.google.android.youtube
,D/MarketUpdateReceiver( 1074): market has promised to install: com.google.android.apps.docs
,I/ActivityManager(  756): Killing 2054:com.google.android.apps.maps/u0a57 (adj 15): empty #17
,I/qtaguid ( 2497): Failed write_ctrl(u 52) res=-1 errno=22
,I/qtaguid ( 2497): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2497): untagSocket(52) failed with errno -22
,D/Finsky  ( 2497): [1] DownloadImpl.setState: com.google.android.youtube from null to UNQUEUED.
,D/Finsky  ( 2497): [1] DownloadQueueImpl.add: Download com.google.android.youtube added to DownloadQueue
,D/Finsky  ( 2497): [1] DownloadImpl.setState: com.google.android.youtube from UNQUEUED to QUEUED.
,I/installd(  186): free_cache(12459084) avail 12333744128
,D/Finsky  ( 2497): [1] DownloadQueueImpl.startDownload: Download com.google.android.youtube starting
,D/Finsky  ( 2497): [165] 7.run: Enqueued com.google.android.youtube as content://downloads/my_downloads/643
,D/Finsky  ( 2497): [1] DownloadImpl.setState: com.google.android.youtube from QUEUED to DOWNLOADING.
,D/Finsky  ( 2497): [1] DownloadQueueImpl.onStart: com.google.android.youtube: onStart
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/Finsky  ( 2497): [1] DownloadQueueImpl.notifyProgress: com.google.android.youtube: onProgress 0/-1 Status: 190.
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/Finsky  ( 2497): [1] DownloadQueueImpl.notifyProgress: com.google.android.youtube: onProgress 0/-1 Status: 192.
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,I/DownloadManager( 1172): Download 643 starting
W/ActivityThread( 1172): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/dalvikvm( 1172): GC_CONCURRENT freed 378K, 3% free 17130K/17540K, paused 2ms+2ms, total 15ms
,D/dalvikvm( 1172): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 1172): GC_CONCURRENT freed 362K, 3% free 17192K/17632K, paused 2ms+3ms, total 16ms
,D/dalvikvm( 1172): GC_CONCURRENT freed 410K, 3% free 17186K/17684K, paused 2ms+3ms, total 13ms
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/dalvikvm( 2192): GC_CONCURRENT freed 368K, 3% free 17892K/18292K, paused 6ms+2ms, total 40ms
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/dalvikvm( 1172): GC_CONCURRENT freed 342K, 3% free 17233K/17680K, paused 10ms+1ms, total 25ms
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/dalvikvm( 2497): GC_CONCURRENT freed 936K, 5% free 19968K/20936K, paused 2ms+3ms, total 32ms
,D/Finsky  ( 2497): [1] 5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  756): Waited long enough for: ServiceRecord{42bd7930 u0 com.android.providers.downloads/.DownloadService}
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/dalvikvm(  756): GC_CONCURRENT freed 1696K, 7% free 24251K/25988K, paused 3ms+3ms, total 73ms
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/Finsky  ( 2497): [1] DownloadBroadcastReceiver.onReceive: Intent received at DownloadBroadcastReceiver
,I/DownloadManager( 1172): Download 643 finished with status SUCCESS
,D/Finsky  ( 2497): [1] DownloadQueueImpl.notifyProgress: com.google.android.youtube: onProgress 12459084/12459084 Status: 200.
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.youtube
,D/Finsky  ( 2497): [1] DownloadImpl.setState: com.google.android.youtube from DOWNLOADING to SUCCESS.
,D/Finsky  ( 2497): [1] DownloadQueueImpl.onComplete: com.google.android.youtube: onComplete
,D/Finsky  ( 2497): [1] DownloadQueueImpl.remove: Download com.google.android.youtube removed from DownloadQueue
,I/installd(  186): free_cache(0) avail 12321296384
,D/Finsky  ( 2497): [1] 6.onPostExecute: Successfully applied patch to update com.google.android.youtube
,D/MarketUpdateReceiver( 1074): market is installing: com.google.android.youtube
,W/ActivityManager(  756): No content provider found for permission revoke: file:///data/data/com.android.vending/cache/patches/com.google.android.youtube-555575893.apk
D/Finsky  ( 2497): [1] PackageVerificationReceiver.checkPrerequisites: Skipping verification because own installation
D/Finsky  ( 2497): [1] PackageVerificationReceiver.onReceive: Verification requested, id = 0
,W/ActivityManager(  756): No content provider found for permission revoke: file:///data/data/com.android.vending/cache/patches/com.google.android.youtube-555575893.apk
,I/PackageManager(  756): Copying native libraries to /data/app-lib/vmdl-2009089960
,D/dalvikvm(  756): GC_FOR_ALLOC freed 839K, 5% free 24899K/26116K, paused 49ms, total 49ms
,D/dalvikvm(  756): GC_FOR_ALLOC freed 668K, 7% free 25173K/26816K, paused 46ms, total 46ms
,D/dalvikvm(  756): GC_CONCURRENT freed 1129K, 5% free 26168K/27332K, paused 3ms+3ms, total 50ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/dalvikvm(  756): GC_CONCURRENT freed 1784K, 7% free 26679K/28508K, paused 2ms+6ms, total 56ms
,D/dalvikvm(  756): GC_FOR_ALLOC freed 2114K, 9% free 26712K/29208K, paused 47ms, total 47ms
,D/dalvikvm(  756): GC_FOR_ALLOC freed 2203K, 9% free 26720K/29256K, paused 47ms, total 47ms
,D/dalvikvm(  756): GC_FOR_ALLOC freed 2212K, 9% free 26733K/29268K, paused 49ms, total 49ms
,D/dalvikvm(  756): GC_FOR_ALLOC freed 2222K, 9% free 26758K/29280K, paused 53ms, total 53ms
,D/dalvikvm(  756): GC_FOR_ALLOC freed 2282K, 9% free 26782K/29316K, paused 49ms, total 49ms
,D/dalvikvm(  756): GC_FOR_ALLOC freed 2321K, 9% free 26796K/29340K, paused 49ms, total 49ms
,D/dalvikvm(  756): GC_FOR_ALLOC freed 2340K, 9% free 26817K/29364K, paused 51ms, total 51ms
,D/dalvikvm(  756): GC_FOR_ALLOC freed 2371K, 9% free 26831K/29388K, paused 50ms, total 50ms
,I/ActivityManager(  756): Force stopping com.google.android.youtube appid=10071 user=-1: replace sys pkg
,I/ActivityManager(  756): Killing 2081:com.google.android.youtube/u0a71 (adj 15): stop com.google.android.youtube
,F/ActivityManager(  756): Service ServiceRecord{42de7200 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42d85520 2081:com.google.android.youtube/u0a71} not same as in map: null
,W/PackageManager(  756): Trying to update system app code path from /data/app/com.google.android.youtube-2.apk to /data/app/com.google.android.youtube-1.apk
,I/PackageManager(  756): Running dexopt on: com.google.android.youtube
,D/ConnectivityService(  756): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  756): Done.
,D/ConnectivityService(  756): Setting timer for 720seconds
,D/dalvikvm( 2713): GC_FOR_ALLOC freed 37K, 2% free 2009K/2048K, paused 4ms, total 4ms
,D/dalvikvm( 2713): DexOpt: load 319ms, verify+opt 1923ms, 7055348 bytes
,I/ActivityManager(  756): Force stopping com.google.android.youtube appid=10071 user=-1: update pkg
W/PackageManager(  756): Code path for pkg : com.google.android.youtube changing from /data/app/com.google.android.youtube-2.apk to /data/app/com.google.android.youtube-1.apk
,W/PackageManager(  756): Resource path for pkg : com.google.android.youtube changing from /data/app/com.google.android.youtube-2.apk to /data/app/com.google.android.youtube-1.apk
,W/PackageSettings(  756): Skipping PackageSetting{427171b0 com.example.hello/10116} due to missing metadata
,W/PackageSettings(  756): Skipping PackageSetting{42705680 com.test.thalitest/10108} due to missing metadata
,W/PackageManager(  756): Unknown permission com.android.smspush.WAPPUSH_MANAGER_BIND in package com.android.phone
,W/PackageManager(  756): Unknown permission com.android.nfc.permission.NFCEE_ADMIN in package com.google.android.apps.walletnfcrel
,W/PackageManager(  756): Unknown permission com.android.vending.billing.IBillingAccountService.BIND2 in package com.google.android.gsf.login
W/PackageManager(  756): Unknown permission com.android.gallery3d.permission.GALLERY_PROVIDER in package com.android.bluetooth
,W/PackageManager(  756): Unknown permission android.permission.MMS_SEND_OUTBOX_MSG in package com.android.bluetooth
,W/PackageManager(  756): Not granting permission android.permission.BROADCAST_PACKAGE_REMOVED to package com.google.android.marvin.talkback (protectionLevel=2 flags=0x40c9be45)
W/PackageManager(  756): Not granting permission android.permission.DEVICE_POWER to package com.google.android.deskclock (protectionLevel=2 flags=0xc8be45)
,W/PackageManager(  756): Unknown permission android.permission.OBSERVE_GRANT_REVOKE_PERMISSIONS in package com.google.android.gms
,W/PackageManager(  756): Unknown permission android.permission.RECOVERY in package com.google.android.gms
W/PackageManager(  756): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gms (protectionLevel=2 flags=0x40c83ec5)
,W/PackageManager(  756): Unknown permission android.permission.PROVIDE_TRUST_AGENT in package com.google.android.gms
,W/PackageManager(  756): Unknown permission com.google.android.apps.enterprise.dmagent.permission.AutoSyncPermission in package com.google.android.gms
,W/PackageManager(  756): Not granting permission android.permission.PACKAGE_USAGE_STATS to package com.google.android.gms (protectionLevel=18 flags=0x40c83ec5)
W/PackageManager(  756): Unknown permission com.google.android.googlequicksearchbox.permission.PAUSE_HOTWORD in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.MANAGE_VOICE_KEYPHRASES in package com.google.android.gms
,W/PackageManager(  756): Unknown permission android.permission.REAL_GET_TASKS in package com.google.android.gms
,W/PackageManager(  756): Unknown permission android.permission.READ_WIFI_CREDENTIAL in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.SCORE_NETWORKS in package com.google.android.gms
,W/PackageManager(  756): Unknown permission android.permission.CONTROL_INCALL_EXPERIENCE in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.USER_ACTIVITY in package com.google.android.gms
,W/PackageManager(  756): Unknown permission android.permission.MODIFY_AUDIO_ROUTING in package com.google.android.gms
W/PackageManager(  756): Unknown permission com.google.android.wearable.READ_SETTINGS in package com.google.android.gms
,W/PackageManager(  756): Unknown permission android.permission.INTENT_FILTER_VERIFICATION_AGENT in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.LOCAL_MAC_ADDRESS in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.BODY_SENSORS in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.NOTIFY_PENDING_SYSTEM_UPDATE in package com.google.android.gms
,W/PackageManager(  756): Unknown permission com.google.android.launcher.permission.RECEIVE_LAUNCH_BROADCASTS in package com.google.android.gms
,W/PackageManager(  756): Unknown permission com.android.voicemail.permission.READ_VOICEMAIL in package com.google.android.gms
,W/PackageManager(  756): Unknown permission android.permission.READ_OWNER_DATA in package com.google.android.setupwizard
,W/PackageManager(  756): Unknown permission android.permission.WRITE_OWNER_DATA in package com.google.android.setupwizard
W/PackageManager(  756): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.android.settings
,W/PackageManager(  756): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.android.settings
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES in package com.redbend.vdmc
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES_WRITE in package com.redbend.vdmc
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.CONNECTIONMANAGER in package com.redbend.vdmc
,W/PackageManager(  756): Unknown permission com.sprint.internal.permission.PLATFORM in package com.redbend.vdmc
W/PackageManager(  756): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.googlequicksearchbox
,W/PackageManager(  756): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager(  756): Unknown permission com.google.android.voicesearch.SHORTCUTS_ACCESS in package com.google.android.googlequicksearchbox
W/PackageManager(  756): Unknown permission com.google.android.voicesearch.ACCESS_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager(  756): Unknown permission com.android.browser.permission.PRELOAD in package com.google.android.googlequicksearchbox
W/PackageManager(  756): Unknown permission com.google.android.apps.googlevoice.permission.AUTO_SEND in package com.google.android.googlequicksearchbox
,W/PackageManager(  756): Unknown permission com.android.chrome.PRERENDER_URL in package com.google.android.googlequicksearchbox
,W/PackageManager(  756): Unknown permission com.google.android.gms.permission.CAR_SPEED in package com.google.android.apps.maps
W/PackageManager(  756): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.launcher
W/PackageManager(  756): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.launcher
,W/PackageManager(  756): Unknown permission android.permission.WRITE_SYNC_STATS in package com.google.android.apps.docs
,W/PackageManager(  756): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.onetimeinitializer
W/PackageManager(  756): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.onetimeinitializer
W/PackageManager(  756): Unknown permission com.android.launcher.permission.PRELOAD_WORKSPACE in package com.google.android.partnersetup
,W/PackageManager(  756): Unknown permission android.permission.REGISTER_CONNECTION_MANAGER in package com.google.android.talk
,W/PackageManager(  756): Not granting permission android.permission.SEND_DOWNLOAD_COMPLETED_INTENTS to package com.android.vending (protectionLevel=2 flags=0x408abe45)
,W/PackageManager(  756): Unknown permission android.permission.SEND_SMS_NO_CONFIRMATION in package com.android.vending
,W/PackageManager(  756): Not granting permission android.permission.BIND_WALLPAPER to package com.google.android.GoogleCamera (protectionLevel=18 flags=0xd83cc5)
,W/PackageManager(  756): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gsf (protectionLevel=2 flags=0x40883e45)
,W/PackageManager(  756): Unknown permission com.chrome.permission.DEVICE_EXTRAS in package com.android.chrome
,W/PackageManager(  756): Unknown permission com.sec.enterprise.knox.MDM_CONTENT_PROVIDER in package com.android.chrome
,W/PackageManager(  756): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES in package com.lge.SprintHiddenMenu
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES_WRITE in package com.lge.SprintHiddenMenu
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.CONNECTIONMANAGER in package com.lge.SprintHiddenMenu
,W/PackageManager(  756): Unknown permission com.sprint.internal.permission.PLATFORM in package com.lge.SprintHiddenMenu
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.OMADM in package com.lge.SprintHiddenMenu
W/PackageManager(  756): Unknown permission android.permission.FACTORY in package com.lge.SprintHiddenMenu
W/PackageManager(  756): Unknown permission com.lge.permission.LGHIDDEN in package com.lge.SprintHiddenMenu
,W/PackageManager(  756): Unknown permission android.permission.MMS_PUSH in package com.lge.SprintHiddenMenu
,W/PackageManager(  756): Not granting permission android.permission.MANAGE_DOCUMENTS to package com.google.android.youtube (protectionLevel=2 flags=0x583ec5)
,D/dalvikvm(  756): GC_CONCURRENT freed 2500K, 9% free 26879K/29404K, paused 3ms+14ms, total 59ms
,W/PackageSettings(  756): Skipping PackageSetting{427171b0 com.example.hello/10116} due to missing metadata
,W/PackageSettings(  756): Skipping PackageSetting{42705680 com.test.thalitest/10108} due to missing metadata
,I/ActivityManager(  756): Force stopping com.google.android.youtube appid=10071 user=0: pkg removed
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 1074): GC_EXPLICIT freed 1074K, 7% free 26009K/27760K, paused 1ms+13ms, total 35ms
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/ActivityManager(  756): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2714 uid=10013 gids={50013, 3003, 3002}
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.youtube flg=0x4000010 (has extras) }
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
,I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.google.android.youtube flg=0x4000010 (has extras) }
,V/BackupManagerService(  756): removePackageParticipantsLocked: uid=10071 #1
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,V/BackupManagerService(  756): addPackageParticipantsLocked: #1
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  756): GC_EXPLICIT freed 3674K, 18% free 24378K/29404K, paused 5ms+5ms, total 99ms
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/Finsky  ( 2497): [148] 1.packageInstalled: Package install status for "com.google.android.youtube" is 1
,D/dalvikvm( 1030): GC_CONCURRENT freed 336K, 3% free 17066K/17428K, paused 3ms+2ms, total 18ms
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
,W/Launcher( 1074): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42672ab0 new=com.google.android.velvet.VelvetApplication@42672ab0
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
,D/Finsky  ( 2497): [1] InstallerImpl.kick: Installer kick null - starting com.google.android.apps.docs
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2742 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
W/ContextImpl( 2742): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  756): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  756): Resuming delayed broadcast
,D/PackageBroadcastService( 1326): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.youtube
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1326): Loading module APK com.google.android.play.games
I/ActivityManager(  756): Killing 2175:com.android.settings/1000 (adj 15): empty #17
,I/dalvikvm( 1326): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1326): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1326): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1326): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1326): VFY: replacing opcode 0x22 at 0x001a
,I/dalvikvm( 1326): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1326): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1326): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,E/NetworkScheduler.SchedulerReceiver(  992): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver(  992): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  756): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2762 uid=10035 gids={50035, 1028, 3003, 1015}
,D/dalvikvm( 2762): GC_CONCURRENT freed 283K, 2% free 16867K/17180K, paused 3ms+1ms, total 14ms
,D/dalvikvm( 2762): GC_CONCURRENT freed 293K, 2% free 16997K/17320K, paused 2ms+4ms, total 16ms
,I/dalvikvm( 2762): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
W/dalvikvm( 2762): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2762): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 2762): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2762):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2762):   adb logcat -s GAv4
,W/GAv4    ( 2762): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/dalvikvm( 2762): GC_CONCURRENT freed 281K, 2% free 17230K/17540K, paused 2ms+2ms, total 14ms
I/dalvikvm( 2762): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 2762): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 2762): VFY: replacing opcode 0x6e at 0x001b
,D/dalvikvm( 2762): WAIT_FOR_CONCURRENT_GC blocked 2ms
,W/GAv4    ( 2762): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2762): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/dalvikvm( 2762): GC_CONCURRENT freed 286K, 2% free 17456K/17772K, paused 2ms+1ms, total 14ms
,D/dalvikvm( 2762): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2762): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2762): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 2762): WAIT_FOR_CONCURRENT_GC blocked 7ms
,W/AnalyticsTrackerProxyImpl( 2762): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.35, sample rate 1.0
,I/dalvikvm( 2762): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
,W/dalvikvm( 2762): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 2762): VFY: replacing opcode 0x71 at 0x0075
,D/dalvikvm( 2762): GC_CONCURRENT freed 447K, 3% free 17524K/18000K, paused 3ms+1ms, total 14ms
,D/dalvikvm( 2762): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2762): GC_FOR_ALLOC freed 35K, 3% free 17580K/18040K, paused 10ms, total 10ms
,I/ActivityManager(  756): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2791 uid=10065 gids={50065, 3003, 1028, 1015}
,I/ActivityManager(  756): Killing 2396:com.android.chrome/u0a31 (adj 15): empty #17
,D/dalvikvm( 2762): GC_CONCURRENT freed 243K, 2% free 17816K/18120K, paused 2ms+3ms, total 19ms
,D/dalvikvm( 2762): GC_CONCURRENT freed 364K, 3% free 17904K/18300K, paused 1ms+3ms, total 21ms
,D/dalvikvm( 2762): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2762): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2762): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2762): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2762): VFY: unable to resolve instance field 36
,D/dalvikvm( 2762): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2762): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2762): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2762): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2762): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2762): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 2762): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4273b748
D/dalvikvm( 2762): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4273b748
,D/dalvikvm( 2762): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4273b748, skipping init
,D/dalvikvm( 2762): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4273b748
D/dalvikvm( 2762): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4273b748
,V/JNIHelp ( 2762): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 2762): GC_CONCURRENT freed 409K, 3% free 17954K/18396K, paused 2ms+9ms, total 22ms
,W/Quickoffice( 2791): Cleanup of storage: done
,D/com.google.android.apps.docs.quickoffice.X( 2791): Loading recent documents list
,D/Quickoffice( 2791): The number of lines present in  /proc/mount 21
,D/Quickoffice( 2791): Parsing the storagedefinition.xml.
,D/dalvikvm( 2762): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4273b748
D/dalvikvm( 2762): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4273b748
D/dalvikvm( 2762): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4273b748
D/Quickoffice( 2791): # of Storagedefinitions - 35
D/Quickoffice( 2791): The # of storage definitions available - 35
D/Quickoffice( 2791): Processing mountline rootfs / rootfs ro,relatime 0 0
,D/dalvikvm( 2762): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4273b748
D/Quickoffice( 2791): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2791): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2791): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2791): Processing mountline proc /proc proc rw,relatime 0 0
,D/Quickoffice( 2791): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2791): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2791): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2791): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
,D/Quickoffice( 2791): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
,D/Quickoffice( 2791): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2791): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2791): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
,D/Quickoffice( 2791): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2791): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2791): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
,D/Quickoffice( 2791): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2791): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/Quickoffice( 2791): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2791): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2791): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/Quickoffice( 2791): Build properties are not configured for this storage definition.
,D/Quickoffice( 2791): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
,D/dalvikvm( 2791): GC_CONCURRENT freed 191K, 2% free 16915K/17136K, paused 2ms+1ms, total 13ms
,D/Quickoffice( 2791): The # of mounts identified -  1
,D/dalvikvm( 2762): GC_FOR_ALLOC freed 151K, 3% free 18057K/18436K, paused 13ms, total 14ms
,I/ActivityManager(  756): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2814 uid=10011 gids={50011, 3003}
,D/dalvikvm(  945): GC_CONCURRENT freed 256K, 2% free 17063K/17348K, paused 1ms+1ms, total 17ms
,D/com.google.android.apps.docs.quickoffice.X( 2791): Checking validity of 0 items
I/ActivityManager(  756): Killing 961:com.google.android.keep/u0a52 (adj 15): empty #17
,D/ContentResolverUtil( 2791): There are 0 persisted uri permissions.
,D/com.google.android.apps.docs.quickoffice.X( 2791): 0 items were valid
,W/Quickoffice( 2791): Could not load clipboard.
W/ActivityManager(  756): No permission grants found for com.quickoffice.android
,I/ProviderInstaller( 2762): Installed default security provider GmsCore_OpenSSL
,W/Quickoffice( 2791): Could not store clipboard.
,I/Icing.InternalIcingCorporaProvider( 1212): Updating corpora: A: com.google.android.youtube, C: MAYBE
,I/ActivityManager(  756): Killing 2425:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
,D/PackageBroadcastService( 1326): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.youtube
D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1326): Module APK com.google.android.play.games already loaded
I/dalvikvm( 1326): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1326): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1326): VFY: replacing opcode 0x6e at 0x0053
,D/dalvikvm( 1326): GC_CONCURRENT freed 585K, 4% free 18687K/19296K, paused 3ms+3ms, total 25ms
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1326): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1326): Submit a task: k
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1326): Processing package: com.google.android.youtube
,D/b       ( 1326): Look up (com.google.android.youtube:110156634) returned no result
,D/k       ( 1326): Starting Hash for package com.google.android.youtube:11.01.56
,W/BaseAppContext( 1326): Using Auth Proxy for data requests.
,W/BaseAppContext( 1326): Using Auth Proxy for data requests.
,D/GCM     (  992): GcmService start Intent { act=com.google.android.gms.gcm.PACKAGE_REPLACED cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gms.gcm.PACKAGE_REPLACED
,D/dalvikvm(  992): GC_CONCURRENT freed 370K, 4% free 18031K/18708K, paused 2ms+3ms, total 27ms
,W/Launcher( 1074): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42672ab0 new=com.google.android.velvet.VelvetApplication@42672ab0
,I/ContactLoggerTask( 1212): canRun() : Disabled
,I/Icing.InternalIcingCorporaProvider( 1212): UpdateCorporaTask done [took 155 ms] updated apps [took 112 ms] updated contacts [took 43 ms]
I/ActivityManager(  756): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=2855 uid=10056 gids={50056, 3003, 1028, 1015}
,W/BaseAppContext( 1326): Using Auth Proxy for data requests.
,W/BaseAppContext( 1326): Using Auth Proxy for data requests.
,W/BaseAppContext( 1326): Using Auth Proxy for data requests.
,W/BaseAppContext( 1326): Using Auth Proxy for data requests.
,W/dalvikvm( 1326): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1326): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1326): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1326): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1326): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1326): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1326): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1326): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1326): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1326): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1326): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1326): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1326): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1326): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1326): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1326): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1326): VFY: replacing opcode 0x6e at 0x0006
,W/BaseAppContext( 1326): Using Auth Proxy for data requests.
,V/WebViewChromiumFactoryProvider( 2855): Binding Chromium to main looper Looper (main, tid 1) {426703e0}
,I/LibraryLoader( 2855): Expected native library version number "",actual native library version number ""
D/dalvikvm( 1326): GC_CONCURRENT freed 499K, 3% free 18831K/19360K, paused 3ms+3ms, total 22ms
,I/chromium( 2855): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2855): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 2855): BLUETOOTH permission is missing!
,I/Adreno-EGL( 2855): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,I/PeopleDatabaseHelper( 1326): cleanUpNonGplusAccounts done.
,W/chromium( 2855): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,D/k       ( 1326): Package com.google.android.youtube's hash: cd40511d62c51c147535609b2758c449d983669a78d374829ca813c4a56bd1b3
,D/b       ( 1326): Look up (com.google.android.youtube:110156634) returned no result
,D/k       ( 1326): Saved the app info in cache for package:com.google.android.youtube.
,D/dalvikvm( 2855): GC_CONCURRENT freed 266K, 2% free 16861K/17160K, paused 3ms+0ms, total 18ms
,W/GAV2    ( 2855): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 2855): GC_CONCURRENT freed 194K, 2% free 17072K/17296K, paused 2ms+2ms, total 14ms
,I/NSApplication( 2855): Starting up...
,D/PackageBroadcastService( 1326): Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.youtube
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/ActivityManager(  756): Killing 1965:com.google.android.email/u0a36 (adj 15): empty #17
,D/dalvikvm( 1326): GC_CONCURRENT freed 426K, 3% free 19065K/19524K, paused 2ms+4ms, total 28ms
,D/AsyncTaskServiceImpl( 1326): Submit a task: k
,D/k       ( 1326): Processing package: com.google.android.youtube
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/GassUtils( 1326): Found app info for package com.google.android.youtube:110156634. Hash: cd40511d62c51c147535609b2758c449d983669a78d374829ca813c4a56bd1b3
,D/k       ( 1326): Found info for package com.google.android.youtube in db.
,W/dalvikvm( 1326): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1326): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver(  992): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver(  992): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  756): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=2901 uid=10071 gids={50071, 3003, 1028, 1015}
,I/ActivityManager(  756): Start proc com.google.android.apps.cloudprint for broadcast com.google.android.apps.cloudprint/.printdialog.receivers.UpgradeBroadcastReceiver: pid=2913 uid=10032 gids={50032, 3003, 1028}
,D/dalvikvm(  183): GC_EXPLICIT freed 41K, 1% free 16698K/16772K, paused 2ms+2ms, total 17ms
,W/MultiDex( 2901): Trying to delete old file /data/data/com.google.android.youtube/files/secondary-dexes/com.google.android.youtube-2.apk.classes2.dex of size 835904
,D/dalvikvm(  183): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+2ms, total 15ms
W/MultiDex( 2901): Deleted old file /data/data/com.google.android.youtube/files/secondary-dexes/com.google.android.youtube-2.apk.classes2.dex
,W/MultiDex( 2901): Trying to delete old file /data/data/com.google.android.youtube/files/secondary-dexes/com.google.android.youtube-2.apk.classes2.zip of size 345196
,W/MultiDex( 2901): Deleted old file /data/data/com.google.android.youtube/files/secondary-dexes/com.google.android.youtube-2.apk.classes2.zip
,D/dalvikvm(  183): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+1ms, total 14ms
,D/dalvikvm( 2901): GC_CONCURRENT freed 241K, 2% free 16970K/17240K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 2901): WAIT_FOR_CONCURRENT_GC blocked 4ms
,I/ActivityManager(  756): Killing 2192:com.google.android.music:main/u0a58 (adj 15): empty #17
,F/ActivityManager(  756): Service ServiceRecord{42e0e820 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42bd1fe0 2192:com.google.android.music:main/u0a58} not same as in map: null
,D/dalvikvm( 2901): GC_CONCURRENT freed 123K, 1% free 17275K/17440K, paused 1ms+1ms, total 11ms
F/ActivityManager(  756): Service ServiceRecord{42dece50 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42bd1fe0 2192:com.google.android.music:main/u0a58} not same as in map: null
F/ActivityManager(  756): Service ServiceRecord{42dcd210 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42bd1fe0 2192:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  756): Service ServiceRecord{42dc6cc0 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42bd1fe0 2192:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  756): Service ServiceRecord{42dc6b38 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42bd1fe0 2192:com.google.android.music:main/u0a58} not same as in map: null
,I/Icing   ( 1326): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/dalvikvm( 2901): DexOpt: --- BEGIN 'com.google.android.youtube-1.apk.classes2.zip' (bootstrap=0) ---
,D/dalvikvm( 1212): GC_CONCURRENT freed 682K, 4% free 18559K/19272K, paused 2ms+4ms, total 18ms
,I/Icing   ( 1326): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/Icing   ( 1326): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/dalvikvm( 1326): GC_CONCURRENT freed 541K, 3% free 19243K/19816K, paused 1ms+2ms, total 18ms
,I/Icing   ( 1326): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/dalvikvm( 2934): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,D/dalvikvm( 2934): DexOpt: load 63ms, verify+opt 101ms, 1390132 bytes
,I/Icing   ( 1326): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,I/Icing   ( 1326): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/dalvikvm( 2901): DexOpt: --- END 'com.google.android.youtube-1.apk.classes2.zip' (success) ---
,D/dalvikvm( 2901): DEX prep '/data/data/com.google.android.youtube/files/secondary-dexes/com.google.android.youtube-1.apk.classes2.zip': unzip in 51ms, rewrite 357ms
,I/dalvikvm( 2901): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 2901): VFY: unable to resolve virtual method 573: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 2901): GC_CONCURRENT freed 324K, 2% free 17397K/17752K, paused 4ms+3ms, total 16ms
,D/dalvikvm( 2901): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2901): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2901): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2901): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2901): VFY: unable to resolve instance field 36
,D/dalvikvm( 2901): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 2901): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2901): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2901): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 2901): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2901): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 2901): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426e2ce0
D/dalvikvm( 2901): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426e2ce0
,D/dalvikvm( 2901): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426e2ce0, skipping init
,D/dalvikvm( 2901): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426e2ce0
D/dalvikvm( 2901): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426e2ce0
,V/JNIHelp ( 2901): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 2901): GC_CONCURRENT freed 894K, 6% free 17015K/17940K, paused 2ms+1ms, total 11ms
,D/dalvikvm( 2901): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2901): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2901): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426e2ce0
,D/dalvikvm( 2901): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x426e2ce0
D/dalvikvm( 2901): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426e2ce0
,D/dalvikvm( 2901): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x426e2ce0
,D/dalvikvm( 2901): GC_CONCURRENT freed 315K, 5% free 17155K/17940K, paused 2ms+2ms, total 12ms
,D/dalvikvm( 2901): GC_FOR_ALLOC freed 52K, 5% free 17187K/17940K, paused 8ms, total 8ms
,I/dalvikvm-heap( 2901): Grow heap (frag case) to 16.849MB for 39954-byte allocation
,D/dalvikvm( 2901): GC_FOR_ALLOC freed <1K, 5% free 17226K/17980K, paused 9ms, total 9ms
,D/dalvikvm( 2901): GC_FOR_ALLOC freed <1K, 5% free 17226K/17980K, paused 10ms, total 10ms
,I/dalvikvm-heap( 2901): Grow heap (frag case) to 16.925MB for 79892-byte allocation
,D/dalvikvm( 2901): GC_FOR_ALLOC freed 0K, 5% free 17305K/18060K, paused 8ms, total 8ms
,I/ProviderInstaller( 2901): Installed default security provider GmsCore_OpenSSL
I/dalvikvm( 2901): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.FragmentActivity.onBackPressed
W/dalvikvm( 2901): VFY: unable to resolve virtual method 93: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0012
,D/dalvikvm( 2901): GC_CONCURRENT freed 322K, 4% free 17426K/18060K, paused 1ms+3ms, total 11ms
,I/qtaguid ( 2497): Failed write_ctrl(u 52) res=-1 errno=22
I/qtaguid ( 2497): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2497): untagSocket(52) failed with errno -22
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2901): GC_CONCURRENT freed 370K, 4% free 17516K/18060K, paused 4ms+3ms, total 18ms
,D/dalvikvm(  756): GC_CONCURRENT freed 1758K, 17% free 24447K/29404K, paused 2ms+6ms, total 63ms
,I/dalvikvm( 2901): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 2901): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 2901): GC_FOR_ALLOC freed 228K, 3% free 17659K/18060K, paused 12ms, total 12ms
,I/dalvikvm( 2901): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 2901): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 2901): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 2901): DexOpt: --- BEGIN 'ads-555575893.jar' (bootstrap=0) ---
,D/dalvikvm( 2901): GC_CONCURRENT freed 304K, 2% free 17845K/18184K, paused 2ms+10ms, total 25ms
,I/dalvikvm( 2901): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method com.google.ads.conversiontracking.a$b.getActivityBanner
W/dalvikvm( 2901): VFY: unable to resolve virtual method 544: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2901): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method com.google.ads.conversiontracking.a$b.getActivityBanner
W/dalvikvm( 2901): VFY: unable to resolve virtual method 545: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2901): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method com.google.ads.conversiontracking.a$b.getApplicationBanner
W/dalvikvm( 2901): VFY: unable to resolve virtual method 552: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2901): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method com.google.ads.conversiontracking.a$b.getApplicationBanner
W/dalvikvm( 2901): VFY: unable to resolve virtual method 553: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2901): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.ads.conversiontracking.a$b.getLeanbackLaunchIntentForPackage
W/dalvikvm( 2901): VFY: unable to resolve virtual method 569: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2901): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.ads.conversiontracking.a$b.getPackageInstaller
W/dalvikvm( 2901): VFY: unable to resolve virtual method 573: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2901): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method com.google.ads.conversiontracking.a$b.getUserBadgedDrawableForDensity
W/dalvikvm( 2901): VFY: unable to resolve virtual method 589: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2901): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method com.google.ads.conversiontracking.a$b.getUserBadgedIcon
W/dalvikvm( 2901): VFY: unable to resolve virtual method 590: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2901): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method com.google.ads.conversiontracking.a$b.getUserBadgedLabel
W/dalvikvm( 2901): VFY: unable to resolve virtual method 591: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0002
,W/InstanceID/Rpc( 2901): Found 10007
,D/dalvikvm( 2964): DexOpt: load 4ms, verify+opt 10ms, 188892 bytes
,D/dalvikvm( 2901): DexOpt: --- END 'ads-555575893.jar' (success) ---
,D/dalvikvm( 2901): DEX prep '/data/data/com.google.android.youtube/cache/ads-555575893.jar': unzip in 2ms, rewrite 55ms
,I/dalvikvm( 2901): Could not find method android.content.Context.getSystemService, referenced from method com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onCreate
W/dalvikvm( 2901): VFY: unable to resolve virtual method 78: Landroid/content/Context;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0011
I/dalvikvm( 2901): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask
W/dalvikvm( 2901): VFY: unable to resolve virtual method 372: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 2901): VFY: replacing opcode 0x6e at 0x0008
,D/dalvikvm( 2901): GC_CONCURRENT freed 363K, 3% free 17967K/18360K, paused 1ms+4ms, total 17ms
,D/MarketUpdateReceiver( 1074): market has installed: com.google.android.youtube
,D/dalvikvm( 2901): GC_CONCURRENT freed 299K, 2% free 18077K/18420K, paused 3ms+1ms, total 18ms
,I/ActivityManager(  756): Killing 1849:com.google.android.gm/u0a41 (adj 15): empty #17
,D/Volley  ( 2497): [156] BasicNetwork.logSlowRequests: HTTP response for request=<[ ] https://android.clients.google.com/fdfe/delivery?doc=com.google.android.apps.docs&ot=1&st=EPajwrUFGYGVs30krNVBIhUI76Gmlc_RygIQAxABEAQQAhAGGAA%3D%0A&vc=60141735&bvc=54742335&pf=1&ch=OJGKRT0HGZNU-LGa8F7GViztV4g 0xe8d195d1 NORMAL 4> [lifetime=3160], [size=980], [rc=200], [retryCount=1]
,D/dalvikvm( 2497): GC_CONCURRENT freed 1173K, 6% free 19783K/20988K, paused 3ms+3ms, total 28ms
,D/dalvikvm( 2901): GC_CONCURRENT freed 503K, 3% free 18087K/18620K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 2901): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/Finsky  ( 2497): [1] DownloadImpl.setState: com.google.android.apps.docs from null to UNQUEUED.
,D/Finsky  ( 2497): [1] DownloadQueueImpl.add: Download com.google.android.apps.docs added to DownloadQueue
,D/Finsky  ( 2497): [1] DownloadImpl.setState: com.google.android.apps.docs from UNQUEUED to QUEUED.
,I/installd(  186): free_cache(12520472) avail 12316434432
,D/Volley  ( 2497): [1] Request.finish: 3419 ms: [ ] https://android.clients.google.com/fdfe/delivery?doc=com.google.android.apps.docs&ot=1&st=EPajwrUFGYGVs30krNVBIhUI76Gmlc_RygIQAxABEAQQAhAGGAA%3D%0A&vc=60141735&bvc=54742335&pf=1&ch=OJGKRT0HGZNU-LGa8F7GViztV4g 0xe8d195d1 NORMAL 4
,D/Finsky  ( 2497): [1] DownloadQueueImpl.startDownload: Download com.google.android.apps.docs starting
,D/Finsky  ( 2497): [165] 7.run: Enqueued com.google.android.apps.docs as content://downloads/my_downloads/644
,D/Finsky  ( 2497): [1] DownloadImpl.setState: com.google.android.apps.docs from QUEUED to DOWNLOADING.
,D/Finsky  ( 2497): [1] DownloadQueueImpl.onStart: com.google.android.apps.docs: onStart
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.apps.docs
,D/Finsky  ( 2497): [1] DownloadQueueImpl.notifyProgress: com.google.android.apps.docs: onProgress 0/-1 Status: 190.
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.apps.docs
,I/DownloadManager( 1172): Download 644 starting
,D/Finsky  ( 2497): [1] DownloadQueueImpl.notifyProgress: com.google.android.apps.docs: onProgress 0/-1 Status: 192.
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.apps.docs
,D/dalvikvm( 1172): GC_CONCURRENT freed 399K, 3% free 17295K/17724K, paused 1ms+2ms, total 19ms
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.apps.docs
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.apps.docs
,I/GAV2    ( 2855): Thread[GAThread,5,main]: No campaign data found.
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.apps.docs
,D/dalvikvm( 1172): GC_CONCURRENT freed 469K, 4% free 17211K/17756K, paused 3ms+1ms, total 17ms
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.apps.docs
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.apps.docs
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.apps.docs
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
,I/Icing.InternalIcingCorporaProvider( 1212): Updating corpora: A: com.google.android.youtube, C: MAYBE
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  756):   Scheme: "sms"
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  756): GC_CONCURRENT freed 1907K, 17% free 24482K/29404K, paused 4ms+5ms, total 69ms
D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/Launcher( 1074): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42672ab0 new=com.google.android.velvet.VelvetApplication@42672ab0
,D/PackageBroadcastService( 1326): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.youtube
,I/Icing.InternalIcingCorporaProvider( 1212): UpdateCorporaTask done [took 322 ms] updated apps [took 322 ms] 
,I/ActivityManager(  756): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.android.providers.contacts/.PackageIntentReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/Icing.InternalIcingCorporaProvider( 1212): Updating corpora: A: com.google.android.gms, C: MAYBE
,W/Launcher( 1074): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42672ab0 new=com.google.android.velvet.VelvetApplication@42672ab0
,D/PackageBroadcastService( 1326): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1326): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1326): updateResources: need to parse f{com.google.android.gms}
,I/GCoreNlp( 1005): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/dalvikvm( 1326): GC_CONCURRENT freed 913K, 5% free 19123K/20076K, paused 2ms+3ms, total 26ms
,I/Icing.InternalIcingCorporaProvider( 1212): UpdateCorporaTask done [took 315 ms] updated apps [took 315 ms] 
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.apps.docs
,I/DownloadManager( 1172): Download 644 finished with status SUCCESS
,D/Finsky  ( 2497): [1] DownloadBroadcastReceiver.onReceive: Intent received at DownloadBroadcastReceiver
,D/Finsky  ( 2497): [1] DownloadQueueImpl.notifyProgress: com.google.android.apps.docs: onProgress 12520472/12520472 Status: 200.
,D/Finsky  ( 2497): [1] DownloadImpl.setState: com.google.android.apps.docs from DOWNLOADING to SUCCESS.
,D/Finsky  ( 2497): [1] DownloadQueueImpl.onComplete: com.google.android.apps.docs: onComplete
,D/Finsky  ( 2497): [1] DownloadQueueImpl.remove: Download com.google.android.apps.docs removed from DownloadQueue
,I/installd(  186): free_cache(0) avail 12316426240
,D/MarketUpdateReceiver( 1074): market is downloading (0%): com.google.android.apps.docs
,I/Icing   ( 1326): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/dalvikvm( 1326): GC_CONCURRENT freed 699K, 5% free 19121K/20076K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 1212): GC_CONCURRENT freed 508K, 4% free 18545K/19272K, paused 3ms+1ms, total 13ms
,I/Icing   ( 1326): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/Icing   ( 1326): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,I/Icing   ( 1326): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/Icing   ( 1326): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,I/Icing   ( 1326): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/Icing   ( 1326): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,I/Icing   ( 1326): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/Icing   ( 1326): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,I/Icing   ( 1326): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/dalvikvm(  756): Jit: resizing JitTable from 8192 to 16384
,D/Finsky  ( 2497): [1] 6.onPostExecute: Successfully applied patch to update com.google.android.apps.docs
,D/MarketUpdateReceiver( 1074): market is installing: com.google.android.apps.docs
,D/Finsky  ( 2497): [1] PackageVerificationReceiver.checkPrerequisites: Skipping verification because own installation
,W/ActivityManager(  756): No content provider found for permission revoke: file:///data/data/com.android.vending/cache/patches/com.google.android.apps.docs-2009089960.apk
D/Finsky  ( 2497): [1] PackageVerificationReceiver.onReceive: Verification requested, id = 1
,W/ActivityManager(  756): No content provider found for permission revoke: file:///data/data/com.android.vending/cache/patches/com.google.android.apps.docs-2009089960.apk
,I/PackageManager(  756): Copying native libraries to /data/app-lib/vmdl634615039
,D/dalvikvm(  756): GC_CONCURRENT freed 1385K, 16% free 24970K/29404K, paused 2ms+3ms, total 49ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/dalvikvm(  756): GC_CONCURRENT freed 1191K, 13% free 25853K/29404K, paused 2ms+3ms, total 53ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 44ms
,D/dalvikvm(  756): GC_CONCURRENT freed 2146K, 12% free 25998K/29404K, paused 3ms+3ms, total 52ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 45ms
,D/dalvikvm(  756): GC_CONCURRENT freed 2318K, 12% free 26008K/29404K, paused 3ms+4ms, total 58ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/dalvikvm(  756): GC_CONCURRENT freed 2313K, 12% free 26022K/29404K, paused 3ms+3ms, total 86ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 80ms
,D/dalvikvm(  756): GC_CONCURRENT freed 2303K, 12% free 26054K/29404K, paused 3ms+3ms, total 54ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/dalvikvm(  756): GC_CONCURRENT freed 2318K, 12% free 26079K/29404K, paused 3ms+3ms, total 52ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/ActivityManager(  756): Force stopping com.google.android.apps.docs appid=10035 user=-1: replace sys pkg
,I/ActivityManager(  756): Killing 2762:com.google.android.apps.docs/u0a35 (adj 15): stop com.google.android.apps.docs
,W/PackageManager(  756): Trying to update system app code path from /data/app/com.google.android.apps.docs-1.apk to /data/app/com.google.android.apps.docs-2.apk
,I/PackageManager(  756): Running dexopt on: com.google.android.apps.docs
,D/dalvikvm( 2497): GC_CONCURRENT freed 727K, 5% free 19963K/20988K, paused 2ms+2ms, total 26ms
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  992): GC_CONCURRENT freed 376K, 4% free 18047K/18708K, paused 2ms+2ms, total 16ms
,D/dalvikvm( 3078): GC_FOR_ALLOC freed 1K, 1% free 2045K/2048K, paused 4ms, total 4ms
,D/dalvikvm( 3078): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
,I/qtaguid ( 2497): Failed write_ctrl(u 52) res=-1 errno=22
I/qtaguid ( 2497): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2497): untagSocket(52) failed with errno -22
,D/Finsky  ( 2497): [1] 5.onFinished: Installation state replication succeeded.
,D/dalvikvm( 3078): DexOpt: load 340ms, verify+opt 1988ms, 7235340 bytes
,W/PackageManager(  756): Code path for pkg : com.google.android.apps.docs changing from /data/app/com.google.android.apps.docs-1.apk to /data/app/com.google.android.apps.docs-2.apk
,W/PackageManager(  756): Resource path for pkg : com.google.android.apps.docs changing from /data/app/com.google.android.apps.docs-1.apk to /data/app/com.google.android.apps.docs-2.apk
,I/ActivityManager(  756): Force stopping com.google.android.apps.docs appid=10035 user=-1: update pkg
,D/dalvikvm(  756): GC_CONCURRENT freed 2290K, 12% free 26141K/29404K, paused 2ms+10ms, total 50ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 36ms
,W/PackageSettings(  756): Skipping PackageSetting{427171b0 com.example.hello/10116} due to missing metadata
,W/PackageSettings(  756): Skipping PackageSetting{42705680 com.test.thalitest/10108} due to missing metadata
,W/PackageManager(  756): Unknown permission com.android.smspush.WAPPUSH_MANAGER_BIND in package com.android.phone
,W/PackageManager(  756): Unknown permission com.android.nfc.permission.NFCEE_ADMIN in package com.google.android.apps.walletnfcrel
,W/PackageManager(  756): Unknown permission com.android.vending.billing.IBillingAccountService.BIND2 in package com.google.android.gsf.login
W/PackageManager(  756): Unknown permission com.android.gallery3d.permission.GALLERY_PROVIDER in package com.android.bluetooth
,W/PackageManager(  756): Unknown permission android.permission.MMS_SEND_OUTBOX_MSG in package com.android.bluetooth
,W/PackageManager(  756): Not granting permission android.permission.BROADCAST_PACKAGE_REMOVED to package com.google.android.marvin.talkback (protectionLevel=2 flags=0x40c9be45)
W/PackageManager(  756): Not granting permission android.permission.DEVICE_POWER to package com.google.android.deskclock (protectionLevel=2 flags=0xc8be45)
W/PackageManager(  756): Unknown permission android.permission.OBSERVE_GRANT_REVOKE_PERMISSIONS in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.RECOVERY in package com.google.android.gms
,W/PackageManager(  756): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gms (protectionLevel=2 flags=0x40c83ec5)
W/PackageManager(  756): Unknown permission android.permission.PROVIDE_TRUST_AGENT in package com.google.android.gms
,W/PackageManager(  756): Unknown permission com.google.android.apps.enterprise.dmagent.permission.AutoSyncPermission in package com.google.android.gms
W/PackageManager(  756): Not granting permission android.permission.PACKAGE_USAGE_STATS to package com.google.android.gms (protectionLevel=18 flags=0x40c83ec5)
W/PackageManager(  756): Unknown permission com.google.android.googlequicksearchbox.permission.PAUSE_HOTWORD in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.MANAGE_VOICE_KEYPHRASES in package com.google.android.gms
,W/PackageManager(  756): Unknown permission android.permission.REAL_GET_TASKS in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.READ_WIFI_CREDENTIAL in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.SCORE_NETWORKS in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.CONTROL_INCALL_EXPERIENCE in package com.google.android.gms
,W/PackageManager(  756): Unknown permission android.permission.USER_ACTIVITY in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.MODIFY_AUDIO_ROUTING in package com.google.android.gms
W/PackageManager(  756): Unknown permission com.google.android.wearable.READ_SETTINGS in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.INTENT_FILTER_VERIFICATION_AGENT in package com.google.android.gms
,W/PackageManager(  756): Unknown permission android.permission.LOCAL_MAC_ADDRESS in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.BODY_SENSORS in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.NOTIFY_PENDING_SYSTEM_UPDATE in package com.google.android.gms
W/PackageManager(  756): Unknown permission com.google.android.launcher.permission.RECEIVE_LAUNCH_BROADCASTS in package com.google.android.gms
,W/PackageManager(  756): Unknown permission com.android.voicemail.permission.READ_VOICEMAIL in package com.google.android.gms
W/PackageManager(  756): Unknown permission android.permission.READ_OWNER_DATA in package com.google.android.setupwizard
,W/PackageManager(  756): Unknown permission android.permission.WRITE_OWNER_DATA in package com.google.android.setupwizard
W/PackageManager(  756): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.android.settings
,W/PackageManager(  756): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.android.settings
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES in package com.redbend.vdmc
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES_WRITE in package com.redbend.vdmc
,W/PackageManager(  756): Unknown permission com.sprint.internal.permission.CONNECTIONMANAGER in package com.redbend.vdmc
,W/PackageManager(  756): Unknown permission com.sprint.internal.permission.PLATFORM in package com.redbend.vdmc
W/PackageManager(  756): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager(  756): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager(  756): Unknown permission com.google.android.voicesearch.SHORTCUTS_ACCESS in package com.google.android.googlequicksearchbox
W/PackageManager(  756): Unknown permission com.google.android.voicesearch.ACCESS_SETTINGS in package com.google.android.googlequicksearchbox
,W/PackageManager(  756): Unknown permission com.android.browser.permission.PRELOAD in package com.google.android.googlequicksearchbox
W/PackageManager(  756): Unknown permission com.google.android.apps.googlevoice.permission.AUTO_SEND in package com.google.android.googlequicksearchbox
,W/PackageManager(  756): Unknown permission com.android.chrome.PRERENDER_URL in package com.google.android.googlequicksearchbox
,W/PackageManager(  756): Unknown permission com.google.android.gms.permission.CAR_SPEED in package com.google.android.apps.maps
W/PackageManager(  756): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.launcher
,W/PackageManager(  756): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.launcher
W/PackageManager(  756): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.onetimeinitializer
,W/PackageManager(  756): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.onetimeinitializer
W/PackageManager(  756): Unknown permission com.android.launcher.permission.PRELOAD_WORKSPACE in package com.google.android.partnersetup
,W/PackageManager(  756): Unknown permission android.permission.REGISTER_CONNECTION_MANAGER in package com.google.android.talk
,W/PackageManager(  756): Not granting permission android.permission.SEND_DOWNLOAD_COMPLETED_INTENTS to package com.android.vending (protectionLevel=2 flags=0x408abe45)
,W/PackageManager(  756): Unknown permission android.permission.SEND_SMS_NO_CONFIRMATION in package com.android.vending
,W/PackageManager(  756): Not granting permission android.permission.BIND_WALLPAPER to package com.google.android.GoogleCamera (protectionLevel=18 flags=0xd83cc5)
,W/PackageManager(  756): Not granting permission android.permission.MANAGE_DOCUMENTS to package com.google.android.youtube (protectionLevel=2 flags=0xd83ec5)
,W/PackageManager(  756): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gsf (protectionLevel=2 flags=0x40883e45)
,W/PackageManager(  756): Unknown permission com.chrome.permission.DEVICE_EXTRAS in package com.android.chrome
,W/PackageManager(  756): Unknown permission com.sec.enterprise.knox.MDM_CONTENT_PROVIDER in package com.android.chrome
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES in package com.lge.SprintHiddenMenu
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES_WRITE in package com.lge.SprintHiddenMenu
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.CONNECTIONMANAGER in package com.lge.SprintHiddenMenu
W/PackageManager(  756): Unknown permission com.sprint.internal.permission.PLATFORM in package com.lge.SprintHiddenMenu
,W/PackageManager(  756): Unknown permission com.sprint.internal.permission.OMADM in package com.lge.SprintHiddenMenu
W/PackageManager(  756): Unknown permission android.permission.FACTORY in package com.lge.SprintHiddenMenu
W/PackageManager(  756): Unknown permission com.lge.permission.LGHIDDEN in package com.lge.SprintHiddenMenu
W/PackageManager(  756): Unknown permission android.permission.MMS_PUSH in package com.lge.SprintHiddenMenu
,W/PackageManager(  756): Unknown permission android.permission.WRITE_SYNC_STATS in package com.google.android.apps.docs
,W/PackageSettings(  756): Skipping PackageSetting{427171b0 com.example.hello/10116} due to missing metadata
,W/PackageSettings(  756): Skipping PackageSetting{42705680 com.test.thalitest/10108} due to missing metadata
,I/ActivityManager(  756): Force stopping com.google.android.apps.docs appid=10035 user=0: pkg removed
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1074): GC_EXPLICIT freed 1260K, 8% free 26017K/28272K, paused 1ms+1ms, total 28ms
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.apps.docs flg=0x4000010 (has extras) }
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.google.android.apps.docs flg=0x4000010 (has extras) }
,V/BackupManagerService(  756): removePackageParticipantsLocked: uid=10035 #1
,V/BackupManagerService(  756): addPackageParticipantsLocked: #1
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1061): GC_CONCURRENT freed 479K, 3% free 16956K/17464K, paused 1ms+0ms, total 10ms
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  756): GC_EXPLICIT freed 3167K, 17% free 24498K/29404K, paused 2ms+4ms, total 87ms
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
,D/Finsky  ( 2497): [148] 1.packageInstalled: Package install status for "com.google.android.apps.docs" is 1
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,W/Launcher( 1074): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42672ab0 new=com.google.android.velvet.VelvetApplication@42672ab0
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
W/ContextImpl( 2742): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/PackageBroadcastService( 1326): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.apps.docs
D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1326): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver(  992): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver(  992): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/dalvikvm( 2346): GC_CONCURRENT freed 325K, 2% free 17587K/17944K, paused 2ms+1ms, total 24ms
,I/ActivityManager(  756): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3130 uid=10035 gids={50035, 1028, 3003, 1015}
,D/dalvikvm( 3130): GC_CONCURRENT freed 317K, 3% free 16894K/17240K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 6ms
,I/dalvikvm( 3130): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gvw.a
W/dalvikvm( 3130): VFY: unable to resolve virtual method 1824: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3130): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 3130): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3130):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3130):   adb logcat -s GAv4
,W/GAv4    ( 3130): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/dalvikvm( 3130): GC_CONCURRENT freed 355K, 3% free 17052K/17436K, paused 3ms+2ms, total 18ms
D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 9ms
,W/GAv4    ( 3130): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3130): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/dalvikvm( 3130): GC_CONCURRENT freed 293K, 2% free 17264K/17588K, paused 1ms+2ms, total 19ms
,D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/dalvikvm( 3130): Could not find method android.content.Context.checkSelfPermission, referenced from method auo.a
W/dalvikvm( 3130): VFY: unable to resolve virtual method 1642: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3130): VFY: replacing opcode 0x6e at 0x001b
,D/dalvikvm( 3130): GC_CONCURRENT freed 262K, 2% free 17517K/17808K, paused 2ms+2ms, total 20ms
D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 9ms
,W/DatabaseHelper( 3130): Upgrading database /data/data/com.google.android.apps.docs/databases/DocList.db from version 150 to 156 databaseName=DocList.db
,D/dalvikvm( 3130): GC_CONCURRENT freed 345K, 3% free 17672K/18048K, paused 2ms+4ms, total 23ms
,D/dalvikvm( 3130): GC_CONCURRENT freed 264K, 2% free 17973K/18200K, paused 1ms+2ms, total 27ms
,I/Icing.InternalIcingCorporaProvider( 1212): Updating corpora: A: com.google.android.apps.docs, C: MAYBE
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1326): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1326): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.apps.docs
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1326): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1326): Submit a task: k
,D/dalvikvm( 1005): GC_CONCURRENT freed 452K, 3% free 18712K/19260K, paused 2ms+3ms, total 23ms
,D/dalvikvm( 3130): GC_CONCURRENT freed 408K, 3% free 17994K/18428K, paused 4ms+7ms, total 36ms
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 1326): Processing package: com.google.android.apps.docs
,I/Icing.InternalIcingCorporaProvider( 1212): UpdateCorporaTask done [took 81 ms] updated apps [took 81 ms] 
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/b       ( 1326): Look up (com.google.android.apps.docs:60141735) returned no result
,D/k       ( 1326): Starting Hash for package com.google.android.apps.docs:2.3.544.17.35
,W/DatabaseHelper( 3130): Creating a new database at version 151 for /data/data/com.google.android.apps.docs/databases/DocList.db
,D/dalvikvm( 1326): GC_CONCURRENT freed 750K, 5% free 19184K/20068K, paused 4ms+4ms, total 30ms
,D/dalvikvm( 3130): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3130): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3130): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3130): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3130): VFY: unable to resolve instance field 36
,D/dalvikvm( 3130): VFY: replacing opcode 0x54 at 0x005f
,D/GCM     (  992): GcmService start Intent { act=com.google.android.gms.gcm.PACKAGE_REPLACED cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gms.gcm.PACKAGE_REPLACED
D/dalvikvm( 3130): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3130): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3130): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3130): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3130): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 3130): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427568a0
D/dalvikvm( 3130): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427568a0
,D/dalvikvm( 3130): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427568a0, skipping init
,D/dalvikvm( 3130): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427568a0
,D/dalvikvm( 3130): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427568a0
,V/JNIHelp ( 3130): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Launcher( 1074): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42672ab0 new=com.google.android.velvet.VelvetApplication@42672ab0
,D/PackageBroadcastService( 1326): Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.apps.docs
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1326): Submit a task: k
,D/ChimeraCfgMgr( 1326): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/dalvikvm( 3130): GC_CONCURRENT freed 510K, 3% free 17989K/18532K, paused 3ms+2ms, total 17ms
,E/NetworkScheduler.SchedulerReceiver(  992): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver(  992): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/MarketUpdateReceiver( 1074): market has installed: com.google.android.apps.docs
,D/dalvikvm( 3130): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427568a0
,D/dalvikvm( 3130): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x427568a0
D/dalvikvm( 3130): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427568a0
,D/dalvikvm( 3130): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427568a0
,D/k       ( 1326): Package com.google.android.apps.docs's hash: 43988db98c233529520bff530ecdbe99e6dc1aa1e3fa5d9b83ffdcf297309b9e
D/dalvikvm( 3130): GC_CONCURRENT freed 445K, 3% free 18055K/18532K, paused 3ms+1ms, total 18ms
,D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/b       ( 1326): Look up (com.google.android.apps.docs:60141735) returned no result
,D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/k       ( 1326): Saved the app info in cache for package:com.google.android.apps.docs.
,D/k       ( 1326): Processing package: com.google.android.apps.docs
,D/dalvikvm( 3130): GC_FOR_ALLOC freed 173K, 3% free 18098K/18572K, paused 12ms, total 12ms
,I/dalvikvm-heap( 3130): Grow heap (frag case) to 17.776MB for 79892-byte allocation
D/GassUtils( 1326): Found app info for package com.google.android.apps.docs:60141735. Hash: 43988db98c233529520bff530ecdbe99e6dc1aa1e3fa5d9b83ffdcf297309b9e
,D/k       ( 1326): Found info for package com.google.android.apps.docs in db.
,D/dalvikvm( 3130): GC_FOR_ALLOC freed <1K, 3% free 18176K/18652K, paused 12ms, total 12ms
,D/dalvikvm(  992): GC_CONCURRENT freed 439K, 4% free 18101K/18708K, paused 1ms+1ms, total 15ms
,I/VacuumService( 1005): Vacuum at: now=1454412326421 tag=VacuumService
,I/ProviderInstaller( 3130): Installed default security provider GmsCore_OpenSSL
,W/DatabaseHelper( 3130): Creating a new database at version 156 for /data/data/com.google.android.apps.docs/databases/DocList.db
,D/dalvikvm( 3130): GC_CONCURRENT freed 420K, 3% free 18202K/18652K, paused 1ms+1ms, total 15ms
,D/dalvikvm( 3130): GC_CONCURRENT freed 528K, 3% free 18164K/18720K, paused 1ms+3ms, total 18ms
,D/dalvikvm( 3130): GC_CONCURRENT freed 509K, 3% free 18165K/18720K, paused 3ms+1ms, total 41ms
,D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm(  992): GC_CONCURRENT freed 515K, 4% free 18062K/18708K, paused 3ms+3ms, total 29ms
,D/dalvikvm(  756): GC_CONCURRENT freed 1877K, 17% free 24481K/29404K, paused 1ms+4ms, total 47ms
,I/PhenotypeConfigurator( 1005): Scheduling Phenotype for one-off execution 5651 seconds from now (1454412326720)
,D/dalvikvm( 3130): GC_CONCURRENT freed 473K, 3% free 18175K/18720K, paused 2ms+1ms, total 22ms
,D/GetConfigurationSnapshotOperation( 1005): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1005): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1005): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1005): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1005): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1005): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1005): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1005): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1005): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 3130): GC_CONCURRENT freed 518K, 3% free 18168K/18720K, paused 2ms+1ms, total 15ms
,D/dalvikvm( 3130): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 1005): GC_CONCURRENT freed 596K, 4% free 18731K/19420K, paused 3ms+2ms, total 22ms
,I/dalvikvm( 1005): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1005): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1005): VFY: replacing opcode 0x6e at 0x003d
,I/dalvikvm( 3130): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method eij.a
,W/dalvikvm( 3130): VFY: unable to resolve static method 3024: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 3130): VFY: replacing opcode 0x71 at 0x0075
,D/dalvikvm( 1005): GC_CONCURRENT freed 455K, 4% free 18892K/19500K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 3130): GC_CONCURRENT freed 367K, 3% free 18276K/18720K, paused 2ms+2ms, total 16ms
,I/Icing   ( 1326): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/dalvikvm( 1005): GC_CONCURRENT freed 564K, 4% free 19019K/19680K, paused 1ms+4ms, total 19ms
,D/dalvikvm( 1212): GC_CONCURRENT freed 508K, 4% free 18553K/19272K, paused 1ms+1ms, total 11ms
,I/Icing   ( 1326): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/Icing   ( 1326): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,I/Icing   ( 1326): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/dalvikvm( 1326): GC_CONCURRENT freed 714K, 4% free 19271K/20068K, paused 2ms+2ms, total 19ms
,I/Icing   ( 1326): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,I/Icing   ( 1326): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/dalvikvm( 1005): GC_CONCURRENT freed 598K, 4% free 19148K/19840K, paused 3ms+4ms, total 26ms
,D/dalvikvm( 1005): GC_CONCURRENT freed 793K, 5% free 19166K/20056K, paused 1ms+7ms, total 30ms
,D/dalvikvm( 1005): GC_CONCURRENT freed 805K, 5% free 19089K/20084K, paused 3ms+4ms, total 23ms
,D/dalvikvm( 1005): GC_CONCURRENT freed 716K, 5% free 19129K/20084K, paused 2ms+4ms, total 22ms
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1005): GC_FOR_ALLOC freed 600K, 6% free 18961K/20084K, paused 35ms, total 35ms
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  756):   Scheme: "mms"
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
,I/Icing.InternalIcingCorporaProvider( 1212): Updating corpora: A: com.google.android.gms, C: MAYBE
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/Launcher( 1074): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42672ab0 new=com.google.android.velvet.VelvetApplication@42672ab0
,D/PackageBroadcastService( 1326): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1326): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1326): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1074): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42672ab0 new=com.google.android.velvet.VelvetApplication@42672ab0
,I/GCoreNlp( 1005): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PackageBroadcastService( 1326): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.quickoffice.android
,D/dalvikvm( 1326): GC_CONCURRENT freed 906K, 5% free 19141K/20084K, paused 3ms+2ms, total 22ms
,I/Icing.InternalIcingCorporaProvider( 1212): UpdateCorporaTask done [took 417 ms] updated apps [took 417 ms] 
,I/Icing.InternalIcingCorporaProvider( 1212): Updating corpora: A: com.quickoffice.android, C: MAYBE
,I/Icing.InternalIcingCorporaProvider( 1212): UpdateCorporaTask done [took 45 ms] updated apps [took 45 ms] 
,D/dalvikvm( 1212): GC_CONCURRENT freed 502K, 4% free 18548K/19256K, paused 3ms+1ms, total 17ms
,I/Icing   ( 1326): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/dalvikvm(  756): GC_CONCURRENT freed 1816K, 17% free 24500K/29404K, paused 3ms+5ms, total 92ms
,D/dalvikvm( 1326): GC_CONCURRENT freed 719K, 5% free 19110K/20084K, paused 2ms+4ms, total 21ms
,I/Icing   ( 1326): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/Icing   ( 1326): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,I/Icing   ( 1326): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/rmt_storage(  178): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb82b6160
I/rmt_storage(  178): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  178): wakelock acquired: 1, error no: 2
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1205116384)
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1205116384) wakelock released: 1, error no: 0
I/rmt_storage(  178): 
,I/rmt_storage(  178): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb82b6160
,D/dalvikvm( 2497): GC_CONCURRENT freed 1002K, 6% free 19934K/20988K, paused 4ms+1ms, total 39ms
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2497): Failed write_ctrl(u 52) res=-1 errno=22
,I/qtaguid ( 2497): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2497): untagSocket(52) failed with errno -22
,D/Finsky  ( 2497): [1] 5.onFinished: Installation state replication succeeded.
,I/PowerManagerService(  756): Going to sleep due to screen timeout...
,I/Adreno-EGL(  756): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/PermissionCache(  182): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (806 us)
,D/SurfaceFlinger(  182): Screen released, type=0 flinger=0xb8c4c450
,D/qdhwcomposer(  182): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  182): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  756): Excessive delay in blankDisplay() while turning screen off: 277ms
,V/KeyguardServiceDelegate(  756): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42d1df10)
,V/KeyguardServiceDelegate(  756): **** SHOWN CALLED ****
,I/WindowManager(  756): No lock screen! windowToken=null
,I/SearchController( 1212): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1212): mic_close
,I/ActivityManager(  756): Killing 1806:com.google.android.deskclock/u0a33 (adj 15): empty #17
,I/ActivityManager(  756): Killing 1755:com.google.android.calendar/u0a28 (adj 15): empty #18
D/NfcService( 1061): NFC-C OFF
,I/MicroHotwordRecognitionRunner( 1212): Stopping hotword detection.
,I/MicroHotwordRecognitionRunner( 1212): Hotword detection finished
,D/dalvikvm( 1212): GC_CONCURRENT freed 1133K, 7% free 17991K/19252K, paused 2ms+6ms, total 20ms
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  756): Attempting to switch to mobile
,D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService(  756): resetConnections(wlan0, 3)
D/NetUtils(  756): android_net_utils_resetConnections in env=0x7710d4e8 clazz=0x5ef00001 iface=wlan0 mask=0x3
,V/NativeCrypto(  992): Read error: ssl=0x78e8fcf0: I/O error during system call, Connection timed out
,V/NativeCrypto(  992): SSL shutdown failed: ssl=0x78e8fcf0: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  932): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  932): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  932): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 1244): GC_CONCURRENT freed 353K, 3% free 16741K/17124K, paused 1ms+1ms, total 16ms
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/SystemUpdateService( 1326): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/SystemUpdateService( 1326): showing system update notification
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/Babel   ( 2013): connection state changed from CONNECTED to DISCONNECTED
,I/iu.SyncManager( 1326): NEXT; no task
I/ActivityManager(  756): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=3414 uid=10031 gids={50031, 3003, 1028, 1015}
,D/SystemUpdateService( 1326): onDestroy
,D/dalvikvm( 3414): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3414): VFY: unable to resolve instance field 68
D/dalvikvm( 3414): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 3414): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3414): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 3414): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 3414): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 3414): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3414): VFY: unable to resolve instance field 68
,D/dalvikvm( 3414): VFY: replacing opcode 0x54 at 0x0011
D/dalvikvm( 3414): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3414): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3414): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3414): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3414): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3414): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
I/ActivityManager(  756): Killing 2282:com.android.providers.calendar/u0a1 (adj 15): empty #17
,D/WifiStateMachine(  756): VerifyingLinkState enter
D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
,D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aca6a0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1030): GC_CONCURRENT freed 409K, 3% free 17051K/17488K, paused 1ms+3ms, total 24ms
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/iu.SyncManager( 1326): NEXT; no task
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1326): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1326): now status is 0 (complete)
,I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/SystemUpdateService( 1326): showing system update notification
,D/SystemUpdateService( 1326): onDestroy
,I/Babel   ( 2013): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ClearcutLoggerApiImpl(  992): disconnect managed GoogleApiClient
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.78/generate_204,
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  756): Attempting to switch to mobile
,D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x7710d4e8 clazz=0x7c200001 iface=wlan0 mask=0x3
D/ConnectivityService(  756): resetConnections(wlan0, 3)
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto(  992): Read error: ssl=0x78e8fcf0: I/O error during system call, Connection timed out
,V/NativeCrypto(  992): SSL shutdown failed: ssl=0x78e8fcf0: I/O error during system call, Broken pipe
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  932): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  932): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  932): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/Babel   ( 2013): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/SystemUpdateService( 1326): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
I/SystemUpdateService( 1326): OTA package size = 2571501
,I/iu.SyncManager( 1326): NEXT; no task
,I/SystemUpdateService( 1326): showing system update notification
,D/SystemUpdateService( 1326): onDestroy
,D/dalvikvm(  992): GC_CONCURRENT freed 436K, 4% free 18010K/18708K, paused 3ms+2ms, total 23ms
,D/WifiStateMachine(  756): VerifyingLinkState enter
,D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aca6a0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm(  756): GC_CONCURRENT freed 1858K, 17% free 24484K/29404K, paused 21ms+3ms, total 83ms
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1326): num queued entries: 0
I/iu.UploadsManager( 1326): num updated entries: 0
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1326): NEXT; no task
I/SystemUpdateService( 1326): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/SystemUpdateService( 1326): showing system update notification
,D/SystemUpdateService( 1326): onDestroy
,I/Babel   ( 2013): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity(  992): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  756): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3625 uid=10033 gids={50033, 1028}
,I/ActivityManager(  756): Killing 2901:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  756): Service ServiceRecord{43197bb0 u0 com.google.android.youtube/com.google.android.libraries.youtube.offline.transfer.service.OfflineTransferService} in process ProcessRecord{431665b0 2901:com.google.android.youtube/u0a71} not same as in map: null
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  756): Attempting to switch to mobile
,D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x7710d4e8 clazz=0x9a300001 iface=wlan0 mask=0x3
D/ConnectivityService(  756): resetConnections(wlan0, 3)
,V/NativeCrypto(  992): Read error: ssl=0x78e8fcf0: I/O error during system call, Connection timed out
,V/NativeCrypto(  992): SSL shutdown failed: ssl=0x78e8fcf0: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  932): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  932): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  932): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/Babel   ( 2013): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1326): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
I/SystemUpdateService( 1326): now status is 0 (complete)
I/iu.UploadsManager( 1326): num updated entries: 0
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
I/SystemUpdateService( 1326): OTA package size = 2571501
I/iu.SyncManager( 1326): NEXT; no task
,I/SystemUpdateService( 1326): showing system update notification
,D/SystemUpdateService( 1326): onDestroy
,D/dalvikvm( 1326): GC_CONCURRENT freed 646K, 5% free 19153K/20080K, paused 8ms+2ms, total 24ms
,D/WifiStateMachine(  756): VerifyingLinkState enter
,D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
,D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aca6a0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/SystemUpdateService( 1326): active receiver: enabled
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1326): num updated entries: 0
I/SystemUpdateService( 1326): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/SystemUpdateService( 1326): showing system update notification
,I/iu.SyncManager( 1326): NEXT; no task
,D/SystemUpdateService( 1326): onDestroy
,D/dalvikvm( 2013): GC_CONCURRENT freed 1573K, 7% free 22814K/24428K, paused 4ms+3ms, total 62ms
,I/Babel   ( 2013): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  756): Attempting to switch to mobile
,D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x7710d4e8 clazz=0xb8a00001 iface=wlan0 mask=0x3
D/ConnectivityService(  756): resetConnections(wlan0, 3)
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto(  992): Read error: ssl=0x78e8fcf0: I/O error during system call, Connection timed out
,V/NativeCrypto(  992): SSL shutdown failed: ssl=0x78e8fcf0: I/O error during system call, Broken pipe
D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  932): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  932): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/Babel   ( 2013): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/iu.SyncManager( 1326): NEXT; no task
I/SystemUpdateService( 1326): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/SystemUpdateService( 1326): showing system update notification
,D/SystemUpdateService( 1326): onDestroy
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,D/dalvikvm(  992): GC_CONCURRENT freed 412K, 4% free 17990K/18708K, paused 8ms+1ms, total 53ms
,I/wpa_supplicant(  932): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/WifiStateMachine(  756): VerifyingLinkState enter
,D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aca6a0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/iu.UploadsManager( 1326): num updated entries: 0
I/iu.SyncManager( 1326): NEXT; no task
,I/SystemUpdateService( 1326): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,D/dalvikvm( 3130): GC_CONCURRENT freed 324K, 2% free 18359K/18732K, paused 48ms+1ms, total 68ms
,I/SystemUpdateService( 1326): showing system update notification
,D/dalvikvm(  756): GC_CONCURRENT freed 1866K, 17% free 24488K/29404K, paused 1ms+7ms, total 65ms
,D/SystemUpdateService( 1326): onDestroy
,I/Babel   ( 2013): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  756): Attempting to switch to mobile
,D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x7710d4e8 clazz=0xd7700001 iface=wlan0 mask=0x3
D/ConnectivityService(  756): resetConnections(wlan0, 3)
,V/NativeCrypto(  992): Read error: ssl=0x78e8fcf0: I/O error during system call, Connection timed out
,V/NativeCrypto(  992): SSL shutdown failed: ssl=0x78e8fcf0: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  932): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  932): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  932): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1326): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1326): file has been verified
I/SystemUpdateService( 1326): OTA package size = 2571501
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/iu.SyncManager( 1326): NEXT; no task
,I/SystemUpdateService( 1326): showing system update notification
,D/SystemUpdateService( 1326): onDestroy
,I/Babel   ( 2013): connection state changed from CONNECTED to DISCONNECTED
,D/WifiStateMachine(  756): VerifyingLinkState enter
D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
,D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
,D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aca6a0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true,
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1326): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1326): now status is 0 (complete)
,I/ActivityManager(  756): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/SystemUpdateService( 1326): showing system update notification
,D/dalvikvm(  992): GC_CONCURRENT freed 372K, 4% free 18005K/18708K, paused 2ms+4ms, total 28ms
I/ActivityManager(  756): Resuming delayed broadcast
,I/iu.SyncManager( 1326): NEXT; no task
,D/SystemUpdateService( 1326): onDestroy
,I/Babel   ( 2013): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=0, published condition=0
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=6 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  756): Attempting to switch to mobile
,D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x7710d4e8 clazz=0xfa500001 iface=wlan0 mask=0x3
D/ConnectivityService(  756): resetConnections(wlan0, 3)
,V/NativeCrypto(  992): Read error: ssl=0x78f7b568: I/O error during system call, Connection timed out
,V/NativeCrypto(  992): SSL shutdown failed: ssl=0x78f7b568: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  932): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  932): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  932): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/SystemUpdateService( 1326): active receiver: enabled
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/Babel   ( 2013): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1326): num updated entries: 0
I/SystemUpdateService( 1326): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
,I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/iu.SyncManager( 1326): NEXT; no task
,I/SystemUpdateService( 1326): showing system update notification
,D/SystemUpdateService( 1326): onDestroy
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  179): write error (Broken pipe)
,D/WifiStateMachine(  756): VerifyingLinkState enter
,D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aca6a0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/SystemUpdateService( 1326): active receiver: enabled
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/iu.SyncManager( 1326): NEXT; no task
,I/SystemUpdateService( 1326): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
,I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/SystemUpdateService( 1326): showing system update notification
,D/dalvikvm( 2346): GC_CONCURRENT freed 309K, 2% free 17663K/18004K, paused 7ms+1ms, total 18ms
,D/SystemUpdateService( 1326): onDestroy
,I/Babel   ( 2013): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm(  756): GC_CONCURRENT freed 1841K, 17% free 24491K/29404K, paused 4ms+3ms, total 129ms
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  756): Attempting to switch to mobile
,D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x7710d4e8 clazz=0x18800001 iface=wlan0 mask=0x3
D/ConnectivityService(  756): resetConnections(wlan0, 3)
,V/NativeCrypto(  992): Read error: ssl=0x78e8fcf0: I/O error during system call, Connection timed out
,V/NativeCrypto(  992): SSL shutdown failed: ssl=0x78e8fcf0: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  932): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  932): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  932): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/Babel   ( 2013): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1326): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
I/SystemUpdateService( 1326): OTA package size = 2571501
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/SystemUpdateService( 1326): showing system update notification
,I/iu.SyncManager( 1326): NEXT; no task
,D/SystemUpdateService( 1326): onDestroy
,D/WifiStateMachine(  756): VerifyingLinkState enter
,D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
,D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aca6a0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm( 1172): GC_CONCURRENT freed 310K, 3% free 17288K/17756K, paused 1ms+1ms, total 21ms
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1326): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/SystemUpdateService( 1326): showing system update notification
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/iu.SyncManager( 1326): NEXT; no task
,D/SystemUpdateService( 1326): onDestroy
,D/dalvikvm( 1326): GC_CONCURRENT freed 697K, 5% free 19183K/20080K, paused 3ms+2ms, total 26ms
,I/Babel   ( 2013): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm(  992): GC_CONCURRENT freed 409K, 4% free 18000K/18708K, paused 1ms+2ms, total 16ms
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=8 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  756): Attempting to switch to mobile
,D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x7710d4e8 clazz=0x36200001 iface=wlan0 mask=0x3
D/ConnectivityService(  756): resetConnections(wlan0, 3)
,V/NativeCrypto(  992): Read error: ssl=0x78f64c30: I/O error during system call, Connection timed out
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto(  992): SSL shutdown failed: ssl=0x78f64c30: I/O error during system call, Broken pipe
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  756): Sampling interval elapsed, updating statistics ..
,I/wpa_supplicant(  932): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/ConnectivityService(  756): Done.
,D/ConnectivityService(  756): Setting timer for 720seconds
,I/wpa_supplicant(  932): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  932): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/SystemUpdateService( 1326): active receiver: enabled
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/Babel   ( 2013): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1326): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/iu.UploadsManager( 1326): num updated entries: 0
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/iu.SyncManager( 1326): NEXT; no task
,I/SystemUpdateService( 1326): showing system update notification
,D/SystemUpdateService( 1326): onDestroy
,D/WifiStateMachine(  756): VerifyingLinkState enter
,D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
,D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aca6a0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm( 1244): GC_CONCURRENT freed 396K, 3% free 16744K/17228K, paused 22ms+0ms, total 31ms
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/iu.SyncManager( 1326): NEXT; no task
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1326): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/SystemUpdateService( 1326): showing system update notification
,I/ActivityManager(  756): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,D/SystemUpdateService( 1326): onDestroy
I/ActivityManager(  756): Resuming delayed broadcast
,I/Babel   ( 2013): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm(  756): GC_CONCURRENT freed 1926K, 17% free 24516K/29404K, paused 28ms+3ms, total 76ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  756): Attempting to switch to mobile
,D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x7710d4e8 clazz=0x79300001 iface=wlan0 mask=0x3
,V/NativeCrypto(  992): Read error: ssl=0x78e8fcf0: I/O error during system call, Connection timed out
D/ConnectivityService(  756): resetConnections(wlan0, 3)
,V/NativeCrypto(  992): SSL shutdown failed: ssl=0x78e8fcf0: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  932): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
E/wpa_supplicant(  932): Retrying assoc: 1 
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/Babel   ( 2013): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1326): num queued entries: 0
I/SystemUpdateService( 1326): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/iu.UploadsManager( 1326): num updated entries: 0
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/iu.SyncManager( 1326): NEXT; no task
,I/SystemUpdateService( 1326): showing system update notification
,D/SystemUpdateService( 1326): onDestroy
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  932): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  932): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  932): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/WifiStateMachine(  756): VerifyingLinkState enter
,D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aca6a0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/SystemUpdateService( 1326): active receiver: enabled
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1326): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/iu.UploadsManager( 1326): num updated entries: 0
I/SystemUpdateService( 1326): showing system update notification
,I/iu.SyncManager( 1326): NEXT; no task
,D/SystemUpdateService( 1326): onDestroy
,D/dalvikvm( 1005): GC_FOR_ALLOC freed 433K, 6% free 18900K/20084K, paused 30ms, total 30ms
,D/dalvikvm(  992): GC_CONCURRENT freed 407K, 4% free 18006K/18708K, paused 1ms+1ms, total 13ms
,I/Babel   ( 2013): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 2346): GC_CONCURRENT freed 318K, 2% free 17758K/18108K, paused 3ms+2ms, total 16ms
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=10 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  756): Attempting to switch to mobile
,D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x7710d4e8 clazz=0x97c00001 iface=wlan0 mask=0x3
,V/NativeCrypto(  992): Read error: ssl=0x78f7b568: I/O error during system call, Connection timed out
D/ConnectivityService(  756): resetConnections(wlan0, 3)
,V/NativeCrypto(  992): SSL shutdown failed: ssl=0x78f7b568: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/dalvikvm( 1040): GC_CONCURRENT freed 334K, 3% free 16743K/17104K, paused 1ms+0ms, total 29ms
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  932): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  932): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  932): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  932): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 2855): GC_CONCURRENT freed 286K, 2% free 17173K/17492K, paused 4ms+1ms, total 20ms
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
,I/Babel   ( 2013): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1326): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
,I/iu.SyncManager( 1326): NEXT; no task
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/SystemUpdateService( 1326): showing system update notification
,D/SystemUpdateService( 1326): onDestroy
,D/WifiStateMachine(  756): VerifyingLinkState enter
,D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aca6a0
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1326): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1326): onCreate
,D/SystemUpdateService( 1326): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1326): active receiver: enabled
,I/iu.Environment( 1326): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1326): num queued entries: 0
,I/iu.UploadsManager( 1326): num updated entries: 0
,I/iu.SyncManager( 1326): NEXT; no task
,I/SystemUpdateService( 1326): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1326): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1326): now status is 0 (complete)
I/SystemUpdateService( 1326): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1326): file has been verified
,I/SystemUpdateService( 1326): OTA package size = 2571501
,I/SystemUpdateService( 1326): showing system update notification
,D/dalvikvm( 3414): GC_CONCURRENT freed 281K, 2% free 16803K/17116K, paused 1ms+2ms, total 17ms
,D/SystemUpdateService( 1326): onDestroy
,I/Babel   ( 2013): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm(  756): GC_CONCURRENT freed 1933K, 17% free 24540K/29404K, paused 2ms+3ms, total 99ms
,D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,TIME-OUT KILL (timeout was 1200000ms)
```
