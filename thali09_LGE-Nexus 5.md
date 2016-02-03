#### Test 58135655c662d33_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  758): Resuming delayed broadcast
I/ActivityManager(  758): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2486 uid=10014 gids={50014, 3003, 1028, 1015}
--------- beginning of /dev/log/main
D/dalvikvm(  940): GC_CONCURRENT freed 205K, 2% free 17110K/17344K, paused 3ms+1ms, total 23ms
D/Finsky  ( 2486): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/dalvikvm( 2486): GC_CONCURRENT freed 243K, 2% free 16892K/17164K, paused 2ms+1ms, total 14ms
D/Finsky  ( 2486): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 2486): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2486): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/dalvikvm( 2486): GC_CONCURRENT freed 252K, 2% free 17073K/17348K, paused 2ms+1ms, total 12ms
D/Finsky  ( 2486): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2486): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 2486): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/Launcher( 1040): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42658ae0 new=com.google.android.velvet.VelvetApplication@42658ae0
I/Icing.InternalIcingCorporaProvider( 1204): Updating corpora: A: com.google.android.gms, C: MAYBE
I/ActivityManager(  758): Delay finish: com.google.android.googlequicksearchbox/com.android.launcher3.PackageChangedReceiver
D/Finsky  ( 2486): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  758): Resuming delayed broadcast
I/ActivityManager(  758): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  758): Resuming delayed broadcast
I/ActivityManager(  758): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  758): Resuming delayed broadcast
D/PackageBroadcastService( 1323): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1323): Null package name or gms related package.  Ignoreing.
I/Icing   ( 1323): updateResources: need to parse f{com.google.android.gms}
D/dalvikvm( 1323): GC_CONCURRENT freed 651K, 4% free 18664K/19348K, paused 2ms+4ms, total 23ms
D/dalvikvm( 1323): GC_CONCURRENT freed 626K, 4% free 18645K/19348K, paused 2ms+2ms, total 28ms
D/dalvikvm( 1204): GC_CONCURRENT freed 380K, 3% free 18683K/19176K, paused 2ms+2ms, total 12ms
I/Icing.InternalIcingCorporaProvider( 1204): UpdateCorporaTask done [took 265 ms] updated apps [took 265 ms] 
I/ActivityManager(  758): Waited long enough for: ServiceRecord{42db4528 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/Babel   ( 2047): Account registration complete:1-Redacted-21
I/Babel   ( 2047): ProcessRegisterDeviceResponse
I/Babel   ( 2047): Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
D/AndroidRuntime( 2553): 
D/AndroidRuntime( 2553): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2553): CheckJNI is OFF
D/dalvikvm( 2553): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2553): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2553): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2553): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2553): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2553): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
I/Icing   ( 1323): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
D/AndroidRuntime( 2553): Calling main entry com.android.commands.am.Am
I/Icing   ( 1323): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
D/AndroidRuntime( 2553): Shutting down VM
D/dalvikvm( 2553): GC_CONCURRENT freed 96K, 15% free 586K/684K, paused 1ms+0ms, total 2ms
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2553
I/Icing   ( 1323): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
I/Icing   ( 1323): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
E/Babel   ( 2047): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
E/Babel   ( 2047): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
D/dalvikvm( 2047): GC_CONCURRENT freed 1720K, 8% free 23319K/25088K, paused 2ms+2ms, total 42ms
D/dalvikvm( 2047): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2047): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/AlertService( 1717): Beginning updateAlertNotification
,D/AlertService( 1717): No fired or scheduled alerts
,D/AlertService( 1717): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1717): No events found starting within 1 week.
,I/CheckinService( 1323): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  758): Killing 1840:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  758): Killing 1101:com.android.printspooler/u0a64 (adj 15): empty #17
,V/GLSActivity( 1145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2486): GC_CONCURRENT freed 189K, 2% free 17272K/17496K, paused 2ms+2ms, total 13ms
,D/dalvikvm( 2486): GC_CONCURRENT freed 360K, 3% free 17301K/17692K, paused 2ms+2ms, total 14ms
,D/dalvikvm( 2486): GC_CONCURRENT freed 272K, 2% free 17419K/17720K, paused 2ms+2ms, total 13ms
,D/dalvikvm( 2486): GC_CONCURRENT freed 111K, 1% free 17692K/17848K, paused 2ms+1ms, total 12ms
,D/InitAlarmsService( 1717): Clearing and rescheduling alarms.
,D/dalvikvm( 2486): GC_CONCURRENT freed 123K, 1% free 17956K/18128K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 2486): GC_FOR_ALLOC freed 214K, 2% free 18102K/18380K, paused 12ms, total 13ms
,D/dalvikvm( 2486): GC_FOR_ALLOC freed 245K, 3% free 18228K/18636K, paused 16ms, total 16ms
,D/dalvikvm( 2486): GC_FOR_ALLOC freed 241K, 3% free 18353K/18764K, paused 19ms, total 19ms
,D/dalvikvm( 2486): GC_CONCURRENT freed 277K, 2% free 18620K/18936K, paused 1ms+1ms, total 13ms
,D/dalvikvm( 2486): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2486): GC_CONCURRENT freed 194K, 2% free 19069K/19292K, paused 2ms+3ms, total 27ms
,D/dalvikvm( 2486): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2486): GC_CONCURRENT freed 501K, 3% free 19360K/19892K, paused 2ms+3ms, total 31ms
,D/dalvikvm( 2486): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/Finsky  ( 2486): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/dalvikvm( 2486): GC_CONCURRENT freed 743K, 4% free 19502K/20280K, paused 4ms+1ms, total 31ms
,D/dalvikvm( 2486): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2486): WAIT_FOR_CONCURRENT_GC blocked 23ms
,V/GLSActivity( 1145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1145): GC_CONCURRENT freed 374K, 4% free 17980K/18684K, paused 1ms+1ms, total 17ms
,I/qtaguid ( 2486): Failed write_ctrl(u 52) res=-1 errno=22
,I/qtaguid ( 2486): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2486): untagSocket(52) failed with errno -22
,D/dalvikvm( 2486): GC_CONCURRENT freed 487K, 3% free 19829K/20384K, paused 2ms+3ms, total 21ms
,D/Finsky  ( 2486): [1] DailyHygiene.flushEventLogs: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  758): Killing 1871:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  758): Service ServiceRecord{42d44858 u0 com.google.android.youtube/com.google.android.libraries.youtube.offline.transfer.service.OfflineTransferService} in process ProcessRecord{42d781b0 1871:com.google.android.youtube/u0a71} not same as in map: null
,D/dalvikvm( 2148): GC_CONCURRENT freed 341K, 3% free 17890K/18260K, paused 15ms+6ms, total 62ms
,D/dalvikvm( 2486): GC_CONCURRENT freed 1120K, 6% free 19651K/20812K, paused 3ms+2ms, total 34ms
,D/Finsky  ( 2486): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  758): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  758): Done.
,D/ConnectivityService(  758): Setting timer for 720seconds
,I/VacuumService(  978): Vacuum at: now=1454523164206 tag=VacuumService
,D/dalvikvm( 1145): GC_CONCURRENT freed 461K, 4% free 18021K/18684K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 1323): GC_CONCURRENT freed 527K, 4% free 18735K/19344K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 1145): GC_CONCURRENT freed 424K, 4% free 18031K/18684K, paused 2ms+2ms, total 22ms
,I/PhenotypeConfigurator(  978): Scheduling Phenotype for one-off execution 5300 seconds from now (1454523164505)
,D/GetConfigurationSnapshotOperation(  978): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm(  978): GC_CONCURRENT freed 554K, 4% free 18713K/19364K, paused 3ms+2ms, total 19ms
,I/PhenotypeFlagCommitter(  978): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  978): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  978): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  978): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm(  978): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  978): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  978): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  978): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1145): GC_CONCURRENT freed 439K, 4% free 17986K/18684K, paused 3ms+4ms, total 29ms
,I/dalvikvm(  978): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm(  978): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  978): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm(  978): GC_CONCURRENT freed 443K, 4% free 18847K/19444K, paused 3ms+3ms, total 21ms
,D/dalvikvm(  978): GC_CONCURRENT freed 631K, 4% free 18865K/19592K, paused 3ms+2ms, total 25ms
,D/dalvikvm(  978): GC_CONCURRENT freed 429K, 3% free 19090K/19616K, paused 2ms+5ms, total 21ms
,D/dalvikvm(  978): GC_CONCURRENT freed 713K, 5% free 19135K/19944K, paused 3ms+4ms, total 22ms
,D/dalvikvm(  978): GC_CONCURRENT freed 764K, 5% free 19133K/19992K, paused 3ms+4ms, total 23ms
,D/dalvikvm(  978): GC_CONCURRENT freed 767K, 5% free 19089K/20020K, paused 2ms+4ms, total 21ms
,D/dalvikvm(  978): GC_CONCURRENT freed 687K, 5% free 19110K/20020K, paused 3ms+3ms, total 20ms
,W/Uploader(  978): UNKNOWN no longer exists, so no auth token.
,D/dalvikvm(  978): GC_FOR_ALLOC freed 474K, 6% free 18859K/20020K, paused 29ms, total 30ms
,I/rmt_storage(  178): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8e34160
I/rmt_storage(  178): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  178): wakelock acquired: 1, error no: 2
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1193065952)
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1193065952) wakelock released: 1, error no: 0
I/rmt_storage(  178): 
,I/rmt_storage(  178): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8e34160
,I/PowerManagerService(  758): Going to sleep due to screen timeout...
,I/Adreno-EGL(  758): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/PermissionCache(  182): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (170 us)
,D/SurfaceFlinger(  182): Screen released, type=0 flinger=0xb88c0450
,D/qdhwcomposer(  182): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  182): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  758): Excessive delay in blankDisplay() while turning screen off: 296ms
,V/KeyguardServiceDelegate(  758): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42e02da0)
,V/KeyguardServiceDelegate(  758): **** SHOWN CALLED ****
I/WindowManager(  758): No lock screen! windowToken=null
,D/dalvikvm(  758): GC_EXPLICIT freed 1130K, 6% free 24221K/25736K, paused 1ms+4ms, total 48ms
,I/SearchController( 1204): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1204): mic_close
,D/NfcService( 1020): NFC-C OFF
I/ActivityManager(  758): Killing 2091:com.google.android.apps.maps/u0a57 (adj 15): empty #17
I/ActivityManager(  758): Killing 2030:com.google.android.exchange/u0a37 (adj 15): empty #18
,I/MicroHotwordRecognitionRunner( 1204): Hotword detection finished
,I/MicroHotwordRecognitionRunner( 1204): Stopping hotword detection.
,D/dalvikvm( 1204): GC_CONCURRENT freed 1315K, 7% free 17972K/19320K, paused 2ms+6ms, total 20ms

```
