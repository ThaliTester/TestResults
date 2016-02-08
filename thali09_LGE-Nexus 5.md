#### Test 58380500962e22b_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main,
D/Tethering(  756): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  756): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/        (  756): Setting time of day to sec=1454973324
W/        (  756): Unable to set rtc to 1454973324: Invalid argument
D/MusicLifecycle( 2106): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@429acc60 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
I/NetworkMonitor( 2106): type=WIFI subType= reason=null isConnected=true
W/GCoreFlp(  996): No location to return for getLastLocation()
I/SystemUpdateService( 1320): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1320): onCreate
D/SystemUpdateService( 1320): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1320): active receiver: enabled
I/SystemUpdateService( 1320): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1320): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1320): now status is 0 (complete)
I/SystemUpdateService( 1320): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1320): file has been verified
I/SystemUpdateService( 1320): OTA package size = 2571501
I/SystemUpdateService( 1320): showing system update notification
D/GpsLocationProvider(  756): NTP server returned: 1454973321154 (Tue Feb 09 00:15:21 CET 2016) reference: 37909 certainty: 12 system time offset: -3124
D/dalvikvm( 1320): GC_FOR_ALLOC freed 429K, 4% free 18702K/19404K, paused 15ms, total 15ms
I/dalvikvm( 1320): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1320): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1320): VFY: replacing opcode 0x6e at 0x003d
--------- beginning of /dev/log/system
E/ActivityThread( 1320): Failed to find provider info for com.android.contacts.metadata
D/SyncManager(  756): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 20456, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  756): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 41057, reason: UserStart
I/iu.SyncManager( 1320): SYNC; picasa accounts
D/AndroidRuntime( 2465): 
D/AndroidRuntime( 2465): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2465): CheckJNI is OFF
D/dalvikvm( 2465): Trying to load lib libjavacore.so 0x0
D/NetworkLogImpl( 1320): Loaded NetworkSpeedPredictor
D/dalvikvm( 2465): Added shared lib libjavacore.so 0x0
I/iu.Environment( 1320): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/dalvikvm( 2465): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2465): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2465): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/SystemUpdateService( 1320): onDestroy
I/iu.UploadsManager( 1320): num queued entries: 0
I/iu.UploadsManager( 1320): num updated entries: 0
I/iu.SyncManager( 1320): NEXT; no task
D/dalvikvm( 2465): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
V/AlarmClock( 1736): AlarmInitReceiver android.intent.action.TIME_SET
I/AlarmClock( 1736): Displaying next alarm time: ''
V/AlarmClock( 1736): AlarmInitReceiver finished
I/ActivityManager(  756): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2523 uid=10068 gids={50068}
D/dalvikvm( 2523): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x4288ec30, skipping init
D/TimeService( 2523): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454973324469
D/        ( 2523): TimeServiceNative: User Time to be set is 1454973324469
D/QC-time-services( 2523): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2523): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2523): Lib:time_genoff_operation: pargs->ts_val = 1454973324469
D/QC-time-services(  204): Daemon: Connection accepted:time_genoff
D/QC-time-services( 2523): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  204): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454973324469
D/QC-time-services(  204): Daemon:genoff_opr: Base = 2, val = 1454973324469, operation = 0
D/QC-time-services(  204): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/31/71 17:20:6
D/QC-time-services(  204): Daemon:Value read from RTC seconds = 39288006000
D/QC-time-services(  204): Daemon:new time 1454973324469 
D/QC-time-services(  204): Daemon: delta 1415685318469 genoff 1415685318469 
D/QC-time-services(  204): Daemon:genoff_persistent_update: Writing genoff = 1415685318469 to memory
D/QC-time-services(  204): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  204): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  204): Updating the TOD offset
D/QC-time-services(  204): Daemon:genoff_persistent_update: Writing genoff = 1415685318469 to memory
D/QC-time-services(  204): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  204): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  204): Daemon:Update to modem bit set
D/QC-time-services(  204): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  204): Daemon: Base = 2, Value being sent to MODEM = 1139008524469
E/QC-time-services( 2523): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  204): Daemon: Time-services: Waiting to acceptconnection
D/QC-time-services(  204): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  756): Killing 1751:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
I/Babel   ( 2013): connection state changed from UNKNOWN to CONNECTED
I/CheckinService( 1320): Checkin interval check for package: unspecified last checkin: 1454947937169 min interval config: 0 actual interval: 25387327
D/AndroidRuntime( 2465): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 2465): Shutting down VM
D/dalvikvm( 2465): GC_CONCURRENT freed 96K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2465
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,I/ActivityManager(  756): Killing 1812:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/CheckinService( 1320): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  756): Killing 1091:com.android.printspooler/u0a64 (adj 15): empty #17
,D/CaptivePortalTracker(  756): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  756): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  756): Checking http://216.58.209.46/generate_204
W/ActivityThread(  756): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker(  756): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  756): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  756): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  756): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  756): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,V/GLSActivity( 1002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1002): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
,W/dalvikvm( 1002): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1002): VFY: replacing opcode 0x6e at 0x0046
,D/dalvikvm( 1002): GC_CONCURRENT freed 388K, 4% free 17906K/18600K, paused 2ms+1ms, total 33ms
,D/InitAlarmsService( 1692): Clearing and rescheduling alarms.
,D/dalvikvm( 1652): GC_CONCURRENT freed 220K, 2% free 17282K/17536K, paused 2ms+2ms, total 15ms
,D/dalvikvm( 1652): GC_CONCURRENT freed 284K, 2% free 17384K/17700K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 1652): GC_CONCURRENT freed 164K, 2% free 17608K/17808K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 1652): GC_CONCURRENT freed 120K, 1% free 17871K/18036K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 1652): GC_CONCURRENT freed 248K, 2% free 18099K/18412K, paused 2ms+1ms, total 13ms
,D/dalvikvm( 1652): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 1652): GC_FOR_ALLOC freed 62K, 3% free 18163K/18540K, paused 19ms, total 19ms
,D/dalvikvm( 1652): GC_FOR_ALLOC freed 183K, 3% free 18226K/18668K, paused 19ms, total 19ms
,D/dalvikvm( 1652): GC_FOR_ALLOC freed 62K, 3% free 18289K/18668K, paused 11ms, total 11ms
,D/dalvikvm( 1652): GC_FOR_ALLOC freed 179K, 3% free 18350K/18796K, paused 10ms, total 10ms
,D/dalvikvm( 1652): GC_CONCURRENT freed 277K, 2% free 18619K/18932K, paused 2ms+4ms, total 25ms
,D/dalvikvm( 1652): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 1652): GC_CONCURRENT freed 194K, 2% free 19069K/19292K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 1652): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 1652): GC_CONCURRENT freed 494K, 3% free 19345K/19872K, paused 2ms+1ms, total 18ms
,D/Finsky  ( 1652): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/dalvikvm( 1652): GC_CONCURRENT freed 727K, 4% free 19499K/20260K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 1652): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 1652): WAIT_FOR_CONCURRENT_GC blocked 13ms
,V/GLSActivity( 1002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1652): Failed write_ctrl(u 51) res=-1 errno=22
I/qtaguid ( 1652): Untagging socket 51 failed errno=-22
,W/NetworkManagementSocketTagger( 1652): untagSocket(51) failed with errno -22
,D/dalvikvm( 1652): GC_CONCURRENT freed 538K, 3% free 19839K/20416K, paused 2ms+5ms, total 46ms
,D/Finsky  ( 1652): [1] DailyHygiene.flushEventLogs: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  756): Killing 1847:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  756): Service ServiceRecord{42ea6f18 u0 com.google.android.youtube/com.google.android.libraries.youtube.offline.transfer.service.OfflineTransferService} in process ProcessRecord{42fdd880 1847:com.google.android.youtube/u0a71} not same as in map: null
,D/dalvikvm( 1652): GC_CONCURRENT freed 1090K, 6% free 19711K/20844K, paused 3ms+3ms, total 39ms
,D/Finsky  ( 1652): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  756): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  756): Done.
,D/ConnectivityService(  756): Setting timer for 720seconds
,D/dalvikvm( 1002): GC_CONCURRENT freed 352K, 4% free 17964K/18600K, paused 3ms+14ms, total 26ms
,I/VacuumService(  996): Vacuum at: now=1454973377014 tag=VacuumService
,D/dalvikvm(  756): GC_CONCURRENT freed 1529K, 7% free 24190K/25756K, paused 1ms+4ms, total 41ms
,D/dalvikvm( 1002): GC_CONCURRENT freed 469K, 4% free 17901K/18600K, paused 2ms+1ms, total 15ms
,I/rmt_storage(  182): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8cb7160
I/rmt_storage(  182): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  182): wakelock acquired: 1, error no: 2
,I/rmt_storage(  182): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1194626528)
,I/rmt_storage(  182): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  182): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  182): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1194626528) wakelock released: 1, error no: 0
I/rmt_storage(  182): 
,I/rmt_storage(  182): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8cb7160
,I/PowerManagerService(  756): Going to sleep due to screen timeout...
,I/Adreno-EGL(  756): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/PermissionCache(  187): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (813 us)
,D/SurfaceFlinger(  187): Screen released, type=0 flinger=0xb70f0450
,D/qdhwcomposer(  187): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  187): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  756): Excessive delay in blankDisplay() while turning screen off: 302ms
,V/KeyguardServiceDelegate(  756): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42f07bb8)
,V/KeyguardServiceDelegate(  756): **** SHOWN CALLED ****
I/WindowManager(  756): No lock screen! windowToken=null
,I/SearchController( 1223): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1223): mic_close
,D/NfcService( 1064): NFC-C OFF
I/ActivityManager(  756): Killing 2049:com.google.android.apps.maps/u0a57 (adj 15): empty #17
I/ActivityManager(  756): Killing 2000:com.google.android.exchange/u0a37 (adj 15): empty #18
,D/dalvikvm(  996): GC_CONCURRENT freed 425K, 3% free 18653K/19208K, paused 8ms+5ms, total 57ms
,I/MicroHotwordRecognitionRunner( 1223): Hotword detection finished
,I/MicroHotwordRecognitionRunner( 1223): Stopping hotword detection.
,D/dalvikvm( 1223): GC_CONCURRENT freed 1107K, 6% free 17864K/19004K, paused 2ms+2ms, total 33ms
,I/PhenotypeConfigurator(  996): Scheduling Phenotype for one-off execution 2799 seconds from now (1454973457029)
,D/GetConfigurationSnapshotOperation(  996): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter(  996): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm(  996): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  996): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  996): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  996): Using platform SSLCertificateSocketFactory
,D/dalvikvm(  996): GC_CONCURRENT freed 509K, 4% free 18725K/19328K, paused 2ms+4ms, total 38ms
,I/dalvikvm(  996): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm(  996): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  996): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm(  996): GC_CONCURRENT freed 435K, 3% free 18882K/19412K, paused 3ms+2ms, total 25ms
,D/dalvikvm(  996): GC_CONCURRENT freed 537K, 4% free 19001K/19632K, paused 3ms+2ms, total 19ms
,D/dalvikvm(  996): GC_CONCURRENT freed 607K, 4% free 19156K/19856K, paused 1ms+5ms, total 26ms
,D/dalvikvm(  996): GC_CONCURRENT freed 816K, 5% free 19175K/20088K, paused 3ms+7ms, total 35ms
,D/dalvikvm(  996): GC_CONCURRENT freed 848K, 5% free 19130K/20116K, paused 4ms+6ms, total 37ms
,D/dalvikvm(  996): GC_CONCURRENT freed 728K, 5% free 19121K/20116K, paused 3ms+4ms, total 24ms
,D/dalvikvm(  996): GC_FOR_ALLOC freed 591K, 6% free 18997K/20116K, paused 18ms, total 18ms
,D/ConnectivityService(  756): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  756): Done.
,D/ConnectivityService(  756): Setting timer for 720seconds
,D/dalvikvm( 1002): GC_CONCURRENT freed 353K, 4% free 17932K/18600K, paused 16ms+1ms, total 46ms
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,TIME-OUT KILL (timeout was 1200000ms)
```
