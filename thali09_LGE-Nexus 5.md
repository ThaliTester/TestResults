#### Test 5813565532fb33b_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/system
D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
I/ActivityManager(  756): Killing 1747:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,--------- beginning of /dev/log/main
D/AndroidRuntime( 2426): 
D/AndroidRuntime( 2426): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2426): CheckJNI is OFF
D/dalvikvm( 2426): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2426): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2426): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2426): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2426): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2426): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2426): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 2426): Shutting down VM
D/dalvikvm( 2426): GC_CONCURRENT freed 96K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2426
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/        (  756): Setting time of day to sec=1454527760
,W/        (  756): Unable to set rtc to 1454527760: Invalid argument
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-19ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/MusicLifecycle( 2094): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@427d05c8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2094): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/GCoreFlp(  987): No location to return for getLastLocation()
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
,I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1328): file has been verified
I/SystemUpdateService( 1328): OTA package size = 2571501
,I/iu.SyncManager( 1328): SYNC; picasa accounts
,I/SystemUpdateService( 1328): showing system update notification
,D/NetworkLogImpl( 1328): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/iu.SyncManager( 1328): NEXT; no task
,D/dalvikvm( 1328): GC_CONCURRENT freed 424K, 3% free 18636K/19212K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 1328): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/GpsLocationProvider(  756): NTP server returned: 1454527757990 (Wed Feb 03 20:29:17 CET 2016) reference: 38388 certainty: 9 system time offset: -3173
I/dalvikvm( 1328): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1328): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1328): VFY: replacing opcode 0x6e at 0x003d
,D/SystemUpdateService( 1328): onDestroy
,D/SyncManager(  756): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 20517, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  756): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 41592, reason: UserStart
E/ActivityThread( 1328): Failed to find provider info for com.android.contacts.metadata
,V/AlarmClock( 1726): AlarmInitReceiver android.intent.action.TIME_SET
,I/AlarmClock( 1726): Displaying next alarm time: ''
,D/dalvikvm( 1691): GC_CONCURRENT freed 292K, 2% free 16796K/17120K, paused 2ms+0ms, total 14ms
,V/AlarmClock( 1726): AlarmInitReceiver finished
,I/ActivityManager(  756): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2496 uid=10068 gids={50068}
,D/dalvikvm( 2496): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x427bdcc8, skipping init
D/TimeService( 2496): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454527761273
D/        ( 2496): TimeServiceNative: User Time to be set is 1454527761273
D/QC-time-services( 2496): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2496): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2496): Lib:time_genoff_operation: pargs->ts_val = 1454527761273
D/QC-time-services(  202): Daemon: Connection accepted:time_genoff
D/QC-time-services( 2496): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  202): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454527761273
D/QC-time-services(  202): Daemon:genoff_opr: Base = 2, val = 1454527761273, operation = 0
D/QC-time-services(  202): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/26/71 13:34:5
D/QC-time-services(  202): Daemon:Value read from RTC seconds = 38842445000
D/QC-time-services(  202): Daemon:new time 1454527761273 
D/QC-time-services(  202): Daemon: delta 1415685316273 genoff 1415685316273 
D/QC-time-services(  202): Daemon:genoff_persistent_update: Writing genoff = 1415685316273 to memory
D/QC-time-services(  202): Daemon:Opening File: /data/system/time/ats_2
,D/QC-time-services(  202): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  202): Updating the TOD offset
D/QC-time-services(  202): Daemon:genoff_persistent_update: Writing genoff = 1415685316273 to memory
D/QC-time-services(  202): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  202): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  202): Daemon:Update to modem bit set
D/QC-time-services(  202): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  202): Daemon: Base = 2, Value being sent to MODEM = 1138562961273
,E/QC-time-services( 2496): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  202): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  202): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/Babel   ( 2001): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  756): Killing 1799:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
D/dalvikvm( 1089): GC_CONCURRENT freed 407K, 5% free 17882K/18692K, paused 1ms+5ms, total 22ms
I/CheckinService( 1328): Checkin interval check for package: unspecified last checkin: 1454519409208 min interval config: 0 actual interval: 8352094
,I/GCM     ( 1089): GCM config loaded
,D/dalvikvm( 1089): GC_FOR_ALLOC freed 159K, 5% free 17868K/18692K, paused 11ms, total 11ms
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/CheckinService( 1328): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  756): Killing 1070:com.android.printspooler/u0a64 (adj 15): empty #17
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
,W/ActivityThread(  756): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/InitAlarmsService( 1691): Clearing and rescheduling alarms.
,D/dalvikvm( 2279): GC_CONCURRENT freed 225K, 2% free 17255K/17540K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 2279): GC_CONCURRENT freed 352K, 3% free 17309K/17692K, paused 2ms+2ms, total 14ms
,D/dalvikvm( 2279): GC_CONCURRENT freed 248K, 2% free 17447K/17728K, paused 2ms+1ms, total 11ms
,D/dalvikvm( 2279): GC_CONCURRENT freed 122K, 1% free 17710K/17876K, paused 2ms+1ms, total 11ms
,D/dalvikvm( 2279): GC_CONCURRENT freed 128K, 1% free 18028K/18208K, paused 2ms+2ms, total 17ms
,D/dalvikvm( 2279): GC_CONCURRENT freed 249K, 2% free 18165K/18500K, paused 2ms+0ms, total 13ms
,D/dalvikvm( 2279): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2279): GC_FOR_ALLOC freed 183K, 3% free 18227K/18628K, paused 11ms, total 11ms
,D/dalvikvm( 2279): GC_FOR_ALLOC freed 211K, 3% free 18320K/18756K, paused 10ms, total 10ms
,D/dalvikvm( 2279): GC_CONCURRENT freed 270K, 2% free 18540K/18884K, paused 3ms+1ms, total 14ms
,D/dalvikvm( 2279): GC_CONCURRENT freed 169K, 2% free 18922K/19120K, paused 2ms+1ms, total 14ms
,D/dalvikvm( 2279): GC_CONCURRENT freed 474K, 3% free 19179K/19684K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 2279): GC_CONCURRENT freed 317K, 2% free 19619K/19964K, paused 2ms+4ms, total 25ms
,D/Finsky  ( 2279): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2279): Failed write_ctrl(u 52) res=-1 errno=22
I/qtaguid ( 2279): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2279): untagSocket(52) failed with errno -22
,D/dalvikvm( 2279): GC_CONCURRENT freed 964K, 6% free 19545K/20584K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 2279): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2279): GC_CONCURRENT freed 520K, 4% free 19867K/20584K, paused 2ms+2ms, total 22ms
,D/Finsky  ( 2279): [1] DailyHygiene.flushEventLogs: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  756): Killing 1831:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  756): Service ServiceRecord{42c9c4a0 u0 com.google.android.youtube/com.google.android.libraries.youtube.offline.transfer.service.OfflineTransferService} in process ProcessRecord{42d7c1f0 1831:com.google.android.youtube/u0a71} not same as in map: null
,D/Finsky  ( 2279): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  756): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  756): Done.
,D/ConnectivityService(  756): Setting timer for 720seconds
,D/dalvikvm(  756): GC_CONCURRENT freed 1582K, 7% free 24198K/25816K, paused 3ms+6ms, total 56ms
,I/EventLogService( 1328): Aggregate from 1454526001062 (log), 1454526001062 (data)
,D/dalvikvm( 1089): GC_CONCURRENT freed 324K, 4% free 17965K/18692K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 1328): GC_CONCURRENT freed 529K, 4% free 18646K/19280K, paused 1ms+1ms, total 16ms
,W/SQLiteConnectionPool( 1328): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/VacuumService(  987): Vacuum at: now=1454527812539 tag=VacuumService
,D/dalvikvm( 1089): GC_CONCURRENT freed 455K, 5% free 17894K/18692K, paused 1ms+1ms, total 12ms
,D/dalvikvm(  987): GC_CONCURRENT freed 451K, 3% free 18668K/19224K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 1089): GC_CONCURRENT freed 383K, 5% free 17896K/18692K, paused 2ms+2ms, total 20ms
,I/PhenotypeConfigurator(  987): Scheduling Phenotype for one-off execution 10548 seconds from now (1454527812911)
,D/GetConfigurationSnapshotOperation(  987): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter(  987): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  987): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  987): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  987): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  987): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  987): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  987): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  987): Using platform SSLCertificateSocketFactory
,I/dalvikvm(  987): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm(  987): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  987): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm(  987): GC_CONCURRENT freed 539K, 4% free 18757K/19388K, paused 3ms+4ms, total 41ms
,D/dalvikvm(  987): GC_CONCURRENT freed 512K, 4% free 18845K/19524K, paused 2ms+5ms, total 23ms
,D/dalvikvm(  987): GC_CONCURRENT freed 515K, 4% free 19072K/19680K, paused 3ms+4ms, total 32ms
,D/dalvikvm(  987): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm(  987): GC_CONCURRENT freed 685K, 4% free 19108K/19888K, paused 2ms+3ms, total 20ms
,D/dalvikvm(  987): GC_CONCURRENT freed 720K, 5% free 19105K/19920K, paused 3ms+4ms, total 21ms
,D/dalvikvm(  987): GC_CONCURRENT freed 766K, 5% free 19138K/20000K, paused 4ms+6ms, total 33ms
,D/dalvikvm(  987): GC_CONCURRENT freed 785K, 5% free 19122K/20000K, paused 3ms+4ms, total 23ms
,D/dalvikvm(  987): GC_FOR_ALLOC freed 408K, 6% free 18842K/20032K, paused 31ms, total 31ms
,I/rmt_storage(  181): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb7695160
I/rmt_storage(  181): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  181): wakelock acquired: 1, error no: 2
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1217835312)
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1217835312) wakelock released: 1, error no: 0
I/rmt_storage(  181): 
,I/rmt_storage(  181): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb7695160
,I/PowerManagerService(  756): Going to sleep due to screen timeout...
,I/Adreno-EGL(  756): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/PermissionCache(  185): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (786 us)
,D/SurfaceFlinger(  185): Screen released, type=0 flinger=0xb7e8d450
,D/qdhwcomposer(  185): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  185): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  756): Excessive delay in blankDisplay() while turning screen off: 294ms
,V/KeyguardServiceDelegate(  756): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42e02fd8)
,V/KeyguardServiceDelegate(  756): **** SHOWN CALLED ****
I/WindowManager(  756): No lock screen! windowToken=null
,I/SearchController( 1212): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1212): mic_close
,D/NfcService( 1035): NFC-C OFF
I/ActivityManager(  756): Killing 2037:com.google.android.apps.maps/u0a57 (adj 15): empty #17
I/ActivityManager(  756): Killing 1985:com.google.android.exchange/u0a37 (adj 15): empty #18
,I/MicroHotwordRecognitionRunner( 1212): Hotword detection finished
,I/MicroHotwordRecognitionRunner( 1212): Stopping hotword detection.
,D/dalvikvm( 1212): GC_CONCURRENT freed 1278K, 7% free 17888K/19196K, paused 8ms+1ms, total 63ms
,D/ConnectivityService(  756): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  756): Done.
,D/ConnectivityService(  756): Setting timer for 720seconds
,I/GHttpClientFactory( 2094): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2094): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 2094): GC_CONCURRENT freed 435K, 3% free 17942K/18408K, paused 2ms+2ms, total 20ms
,D/MusicLifecycle( 2094): com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync started
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2094): GC_CONCURRENT freed 443K, 3% free 18009K/18484K, paused 4ms+3ms, total 25ms
,D/dalvikvm( 2094): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,W/InstanceID/Rpc( 2094): Found 10007
,I/MusicSyncAdapter( 2094): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
,I/MusicSyncAdapter( 2094): Periodic update
,D/dalvikvm( 1089): GC_CONCURRENT freed 352K, 4% free 17956K/18692K, paused 2ms+4ms, total 29ms
,D/dalvikvm( 2094): GC_CONCURRENT freed 330K, 3% free 18073K/18536K, paused 2ms+1ms, total 25ms
,W/MusicApiClient( 2094): Activity events list is null or empty. Skip reporting.
,D/MusicLifecycle( 2094): com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42883040 and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,D/MusicLifecycle( 2094): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,D/MusicLifecycle( 2094): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.ACTIVATE_AUTO_CACHE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,D/MusicLifecycle( 2094): com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42883040 and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,D/MusicLifecycle( 2094): com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,D/MusicLifecycle( 2094): com.google.android.music.download.cache.TrackCacheService generated event: Service created
,D/MusicLifecycle( 2094): com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service created
,D/MusicLifecycle( 2094): com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service started with intent Intent { act=com.google.android.music.SYNC_COMPLETE cmp=com.google.android.music/.store.KeepOnUpdater$SyncListener }
,D/MusicLifecycle( 2094): com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync ended
,I/MusicLeanback( 2094): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 2094): Stop autocaching.
,D/MusicLifecycle( 2094): com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,D/MusicLifecycle( 2094): com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,D/MusicLifecycle( 2094): com.google.android.music.sync.SyncAdapterService generated event: Service destroyed
,D/MusicLifecycle( 2094): com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42883040 and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,D/MusicLifecycle( 2094): com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service destroyed
,D/MusicLifecycle( 2094): com.google.android.music.download.keepon.KeeponSchedulingService generated event: Service created
,D/MusicLifecycle( 2094): com.google.android.music.download.cache.TrackCacheService generated event: Service created
,D/MusicLifecycle( 2094): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42883040 and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,D/MusicLifecycle( 2094): com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,D/WearableService(  987): callingUid 10007, callindPid: 987
,D/MusicLifecycle( 2094): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,D/MusicLifecycle( 2094): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,E/GmsUtils( 2094): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/GmsUtils( 2094): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/MusicLifecycle( 2094): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,D/MusicLifecycle( 2094): com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,D/MusicLifecycle( 2094): com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,W/ProcessCpuTracker(  756): Skipping unknown process pid 2707
,W/ProcessCpuTracker(  756): Skipping unknown process pid 2710
,I/wpa_supplicant(  919): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  756): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/dalvikvm(  756): GC_EXPLICIT freed 1155K, 7% free 24210K/25816K, paused 2ms+7ms, total 77ms
,D/ConnectivityService(  756): Attempting to switch to mobile
,D/ConnectivityService(  756): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  756): android_net_utils_resetConnections in env=0x77064e18 clazz=0x7f000001 iface=wlan0 mask=0x3
D/ConnectivityService(  756): resetConnections(wlan0, 3)
,V/NativeCrypto( 1089): Read error: ssl=0x79064978: I/O error during system call, Connection timed out
,V/NativeCrypto( 1089): SSL shutdown failed: ssl=0x79064978: I/O error during system call, Broken pipe
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  919): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  919): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  919): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  919): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  756): scanCount==0 - aborting
,W/SocketClient(  182): write error (Broken pipe)
,D/ConnectivityService(  756): handleInetConditionChange: no active default network - ignore
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2094): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@427d05c8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,D/dalvikvm( 1255): GC_CONCURRENT freed 353K, 3% free 16741K/17132K, paused 2ms+1ms, total 21ms
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,D/dalvikvm( 1328): GC_CONCURRENT freed 414K, 3% free 18776K/19276K, paused 3ms+6ms, total 43ms
,I/iu.UploadsManager( 1328): num queued entries: 0
I/iu.UploadsManager( 1328): num updated entries: 0
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,I/Babel   ( 2001): connection state changed from CONNECTED to DISCONNECTED
,D/SystemUpdateService( 1328): onDestroy
,D/WifiStateMachine(  756): VerifyingLinkState enter
D/WifiStateMachine(  756): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  756): CaptivePortalCheckState enter
,D/WifiStateMachine(  756): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  756): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  756): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b64bf8
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  756): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  756): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  756):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  756): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/MusicLifecycle( 2094): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@427d05c8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2094): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1328): active receiver: enabled
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,I/Babel   ( 2001): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,TIME-OUT KILL (timeout was 1200000ms)
```
