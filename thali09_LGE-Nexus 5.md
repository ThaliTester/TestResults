#### Test 58741471ee11130_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 2392): GC_CONCURRENT freed 216K, 2% free 16880K/17128K, paused 2ms+0ms, total 12ms
D/Finsky  ( 2392): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 2392): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2392): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/dalvikvm( 2392): GC_CONCURRENT freed 272K, 2% free 17120K/17364K, paused 3ms+2ms, total 26ms
D/Finsky  ( 2392): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2392): [1] 2.run: Finished loading 1 libraries.
I/Icing.InternalIcingCorporaProvider( 1219): Updating corpora: A: com.google.android.gms, C: MAYBE
W/Launcher( 1066): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@425a8b80 new=com.google.android.velvet.VelvetApplication@425a8b80
--------- beginning of /dev/log/system
I/ActivityManager(  758): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  758): Resuming delayed broadcast
D/Finsky  ( 2392): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  758): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  758): Delaying start of: ServiceRecord{42dee498 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
D/Finsky  ( 2392): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  758): Resuming delayed broadcast
D/PackageBroadcastService( 1327): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1327): Null package name or gms related package.  Ignoreing.
I/Icing   ( 1327): updateResources: need to parse f{com.google.android.gms}
D/dalvikvm( 1327): GC_CONCURRENT freed 714K, 4% free 18640K/19384K, paused 1ms+2ms, total 19ms
D/dalvikvm( 1327): GC_CONCURRENT freed 570K, 4% free 18616K/19384K, paused 1ms+1ms, total 15ms
I/Icing.InternalIcingCorporaProvider( 1219): UpdateCorporaTask done [took 317 ms] updated apps [took 317 ms] 
D/dalvikvm( 1219): GC_CONCURRENT freed 288K, 3% free 18227K/18700K, paused 2ms+1ms, total 12ms
,D/AndroidRuntime( 2451): 
D/AndroidRuntime( 2451): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2451): CheckJNI is OFF
D/dalvikvm( 2451): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2451): Added shared lib libjavacore.so 0x0
I/Icing   ( 1327): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
D/dalvikvm( 2451): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2451): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2451): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2451): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/Icing   ( 1327): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1327): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
I/Icing   ( 1327): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 2451): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 2451): Shutting down VM
D/dalvikvm( 2451): GC_CONCURRENT freed 96K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2451
I/Icing   ( 1327): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/ActivityManager(  758): Waited long enough for: ServiceRecord{42dd1180 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  758): Waited long enough for: ServiceRecord{42ca1590 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  758): Killing 1855:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  758): Killing 1094:com.android.printspooler/u0a64 (adj 15): empty #17
,I/CheckinService( 1327): Done disabling old GoogleServicesFramework version
,D/InitAlarmsService( 1745): Clearing and rescheduling alarms.
,I/ActivityManager(  758): Killing 1888:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  758): Service ServiceRecord{42c84648 u0 com.google.android.youtube/com.google.android.libraries.youtube.offline.transfer.service.OfflineTransferService} in process ProcessRecord{42d33498 1888:com.google.android.youtube/u0a71} not same as in map: null
,V/GLSActivity( 1081): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1081): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1081): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
,W/dalvikvm( 1081): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1081): VFY: replacing opcode 0x6e at 0x0046
,D/dalvikvm( 2392): GC_CONCURRENT freed 243K, 2% free 17269K/17544K, paused 2ms+1ms, total 10ms
,D/dalvikvm( 2392): GC_CONCURRENT freed 295K, 2% free 17425K/17752K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 2392): GC_CONCURRENT freed 166K, 2% free 17761K/17968K, paused 1ms+2ms, total 20ms
,D/dalvikvm( 2392): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2392): GC_CONCURRENT freed 217K, 2% free 18035K/18304K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 2392): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2392): GC_FOR_ALLOC freed 142K, 2% free 18159K/18496K, paused 19ms, total 19ms
,D/dalvikvm( 2392): GC_FOR_ALLOC freed 183K, 3% free 18221K/18624K, paused 21ms, total 21ms
,D/dalvikvm( 2392): GC_FOR_ALLOC freed 211K, 3% free 18314K/18752K, paused 14ms, total 14ms
,D/dalvikvm( 2392): GC_CONCURRENT freed 251K, 3% free 18482K/18880K, paused 2ms+1ms, total 13ms
,D/dalvikvm( 2392): GC_CONCURRENT freed 182K, 2% free 18897K/19108K, paused 1ms+1ms, total 15ms
,D/dalvikvm( 2392): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2392): GC_CONCURRENT freed 465K, 3% free 19139K/19636K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 2392): GC_CONCURRENT freed 242K, 2% free 19650K/19924K, paused 2ms+1ms, total 19ms
,D/Finsky  ( 2392): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,V/GLSActivity( 1081): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1081): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1081): GC_CONCURRENT freed 396K, 4% free 17921K/18520K, paused 1ms+1ms, total 18ms
,I/qtaguid ( 2392): Failed write_ctrl(u 52) res=-1 errno=22
,I/qtaguid ( 2392): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2392): untagSocket(52) failed with errno -22
,D/dalvikvm( 2392): GC_CONCURRENT freed 1057K, 6% free 19540K/20648K, paused 3ms+2ms, total 37ms
,D/dalvikvm( 2392): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2392): GC_CONCURRENT freed 584K, 4% free 19853K/20648K, paused 2ms+1ms, total 30ms
,D/Finsky  ( 2392): [1] DailyHygiene.flushEventLogs: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/dalvikvm( 2161): GC_CONCURRENT freed 367K, 3% free 17900K/18296K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 1327): GC_CONCURRENT freed 501K, 4% free 18635K/19380K, paused 2ms+2ms, total 18ms
,D/Finsky  ( 2392): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  758): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  758): Done.
,D/ConnectivityService(  758): Setting timer for 720seconds
,D/dalvikvm(  758): GC_CONCURRENT freed 1566K, 7% free 24267K/25868K, paused 2ms+6ms, total 46ms
,D/dalvikvm( 1081): GC_CONCURRENT freed 453K, 4% free 17961K/18520K, paused 1ms+3ms, total 14ms
,I/VacuumService(  994): Vacuum at: now=1455023203542 tag=VacuumService
,D/dalvikvm( 1081): GC_CONCURRENT freed 443K, 4% free 17963K/18520K, paused 1ms+1ms, total 19ms
,D/dalvikvm(  994): GC_CONCURRENT freed 467K, 3% free 18691K/19252K, paused 3ms+4ms, total 28ms
,I/PhenotypeConfigurator(  994): Scheduling Phenotype for one-off execution 2079 seconds from now (1455023203847)
,D/GetConfigurationSnapshotOperation(  994): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter(  994): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  994): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  994): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  994): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  994): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  994): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  994): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  994): Using platform SSLCertificateSocketFactory
,I/dalvikvm(  994): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm(  994): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  994): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm(  994): GC_CONCURRENT freed 556K, 4% free 18757K/19404K, paused 2ms+7ms, total 34ms
,D/dalvikvm(  994): GC_CONCURRENT freed 519K, 4% free 18843K/19516K, paused 3ms+3ms, total 21ms
,D/dalvikvm(  994): GC_CONCURRENT freed 473K, 3% free 19010K/19576K, paused 2ms+2ms, total 19ms
,D/dalvikvm(  994): GC_CONCURRENT freed 627K, 4% free 19120K/19840K, paused 2ms+4ms, total 21ms
,D/dalvikvm(  994): GC_CONCURRENT freed 789K, 5% free 19161K/20044K, paused 3ms+6ms, total 37ms
,D/dalvikvm(  994): GC_CONCURRENT freed 843K, 5% free 19163K/20100K, paused 3ms+6ms, total 37ms
,D/dalvikvm(  994): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm(  994): GC_CONCURRENT freed 790K, 5% free 19118K/20100K, paused 3ms+4ms, total 22ms
,D/dalvikvm(  994): GC_FOR_ALLOC freed 465K, 6% free 18912K/20100K, paused 30ms, total 31ms
,I/dalvikvm-heap(  994): Grow heap (frag case) to 18.574MB for 16400-byte allocation
,D/dalvikvm(  994): GC_FOR_ALLOC freed 40K, 7% free 18887K/20120K, paused 21ms, total 21ms
,I/rmt_storage(  176): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8cdb160
I/rmt_storage(  176): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  176): wakelock acquired: 1, error no: 2
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1194479920)
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1194479920) wakelock released: 1, error no: 0
I/rmt_storage(  176): 
,I/rmt_storage(  176): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8cdb160
,I/PowerManagerService(  758): Going to sleep due to screen timeout...
,I/Adreno-EGL(  758): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/PermissionCache(  180): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (157 us)
,D/SurfaceFlinger(  180): Screen released, type=0 flinger=0xb8e5c450
,D/qdhwcomposer(  180): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  180): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  758): Excessive delay in blankDisplay() while turning screen off: 284ms
,V/KeyguardServiceDelegate(  758): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42dd3f80)
,V/KeyguardServiceDelegate(  758): **** SHOWN CALLED ****
I/WindowManager(  758): No lock screen! windowToken=null
,I/SearchController( 1219): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1219): mic_close
,I/ActivityManager(  758): Killing 2104:com.google.android.apps.maps/u0a57 (adj 15): empty #17
,D/NfcService( 1044): NFC-C OFF
I/ActivityManager(  758): Killing 2052:com.google.android.exchange/u0a37 (adj 15): empty #18
,I/MicroHotwordRecognitionRunner( 1219): Hotword detection finished
,I/MicroHotwordRecognitionRunner( 1219): Stopping hotword detection.
,D/dalvikvm( 1219): GC_CONCURRENT freed 899K, 6% free 17722K/18700K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 1219): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 1219): GC_CONCURRENT freed 279K, 5% free 17833K/18700K, paused 2ms+1ms, total 11ms
,D/ConnectivityService(  758): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  758): Done.
,D/ConnectivityService(  758): Setting timer for 720seconds
,D/ConnectivityService(  758): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,TIME-OUT KILL (timeout was 1200000ms)
```
