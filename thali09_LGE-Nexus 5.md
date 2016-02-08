#### Test 581356550b07fff_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  772): Killing 1094:com.android.printspooler/u0a64 (adj 15): empty #17
,--------- beginning of /dev/log/main
D/AndroidRuntime( 2655): 
D/AndroidRuntime( 2655): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2655): CheckJNI is OFF
D/dalvikvm( 2655): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2655): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2655): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2655): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2655): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2655): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2655): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 2655): Shutting down VM
D/dalvikvm( 2655): GC_CONCURRENT freed 96K, 15% free 586K/684K, paused 1ms+0ms, total 3ms
I/ActivityManager(  772): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2655
,I/CheckinService( 1326): Done disabling old GoogleServicesFramework version
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  772): Checking http://216.58.209.78/generate_204
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/ActivityThread(  772): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/ActivityManager(  772): Killing 1829:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,D/InitAlarmsService( 1721): Clearing and rescheduling alarms.
,I/ActivityManager(  772): Killing 1872:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  772): Service ServiceRecord{43072298 u0 com.google.android.youtube/com.google.android.libraries.youtube.offline.transfer.service.OfflineTransferService} in process ProcessRecord{42f57450 1872:com.google.android.youtube/u0a71} not same as in map: null
,D/dalvikvm( 1117): GC_CONCURRENT freed 375K, 4% free 17894K/18600K, paused 1ms+1ms, total 12ms
,V/GLSActivity( 1117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1117): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
,W/dalvikvm( 1117): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1117): VFY: replacing opcode 0x6e at 0x0046
,D/dalvikvm( 2448): GC_CONCURRENT freed 204K, 2% free 17277K/17516K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 2448): GC_CONCURRENT freed 283K, 2% free 17382K/17696K, paused 2ms+1ms, total 11ms
,D/dalvikvm( 2448): GC_CONCURRENT freed 197K, 2% free 17691K/17924K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 2448): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2448): GC_CONCURRENT freed 128K, 1% free 17968K/18144K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 2448): GC_CONCURRENT freed 269K, 2% free 18159K/18496K, paused 2ms+2ms, total 15ms
,D/dalvikvm( 2448): GC_FOR_ALLOC freed 183K, 3% free 18221K/18624K, paused 10ms, total 10ms
,D/dalvikvm( 2448): GC_FOR_ALLOC freed 241K, 3% free 18346K/18752K, paused 11ms, total 11ms
,D/dalvikvm( 2448): GC_CONCURRENT freed 277K, 2% free 18613K/18928K, paused 1ms+2ms, total 13ms
,D/dalvikvm( 2448): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2448): GC_CONCURRENT freed 194K, 2% free 19061K/19284K, paused 1ms+1ms, total 15ms
,D/dalvikvm( 2448): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2448): GC_CONCURRENT freed 500K, 3% free 19349K/19880K, paused 1ms+1ms, total 16ms
,D/dalvikvm( 2448): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/Finsky  ( 2448): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/dalvikvm( 2448): GC_CONCURRENT freed 718K, 4% free 19512K/20264K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 2448): WAIT_FOR_CONCURRENT_GC blocked 3ms
,V/GLSActivity( 1117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2448): Failed write_ctrl(u 52) res=-1 errno=22
,I/qtaguid ( 2448): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2448): untagSocket(52) failed with errno -22
,D/dalvikvm( 2448): GC_CONCURRENT freed 511K, 3% free 19821K/20392K, paused 2ms+2ms, total 22ms
,D/Finsky  ( 2448): [1] DailyHygiene.flushEventLogs: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/dalvikvm( 2448): GC_CONCURRENT freed 1121K, 6% free 19682K/20844K, paused 2ms+1ms, total 26ms
,D/Finsky  ( 2448): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  772): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  772): Done.
,D/ConnectivityService(  772): Setting timer for 720seconds
,D/dalvikvm( 1117): GC_CONCURRENT freed 385K, 4% free 17893K/18600K, paused 2ms+1ms, total 13ms
,I/VacuumService( 1010): Vacuum at: now=1454950382335 tag=VacuumService
,D/dalvikvm( 1117): GC_CONCURRENT freed 372K, 4% free 17974K/18600K, paused 2ms+2ms, total 16ms
,I/rmt_storage(  178): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb7a65160
I/rmt_storage(  178): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  178): wakelock acquired: 1, error no: 2
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1213836768)
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1213836768) wakelock released: 1, error no: 0
I/rmt_storage(  178): 
,I/rmt_storage(  178): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb7a65160
,I/PowerManagerService(  772): Going to sleep due to screen timeout...
,I/Adreno-EGL(  772): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/PermissionCache(  182): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (812 us)
,D/SurfaceFlinger(  182): Screen released, type=0 flinger=0xb7a72450
,D/qdhwcomposer(  182): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  182): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  772): Excessive delay in blankDisplay() while turning screen off: 288ms
,V/KeyguardServiceDelegate(  772): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@431d47d8)
,V/KeyguardServiceDelegate(  772): **** SHOWN CALLED ****
I/WindowManager(  772): No lock screen! windowToken=null
,I/SearchController( 1218): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1218): mic_close
,I/ActivityManager(  772): Killing 2085:com.google.android.apps.maps/u0a57 (adj 15): empty #17
,I/ActivityManager(  772): Killing 2033:com.google.android.exchange/u0a37 (adj 15): empty #18
,D/NfcService( 1067): NFC-C OFF
,I/MicroHotwordRecognitionRunner( 1218): Stopping hotword detection.
,I/MicroHotwordRecognitionRunner( 1218): Hotword detection finished
,D/dalvikvm( 1010): GC_CONCURRENT freed 449K, 3% free 18656K/19200K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 1218): GC_CONCURRENT freed 899K, 5% free 17724K/18656K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 1218): GC_CONCURRENT freed 265K, 5% free 17842K/18656K, paused 2ms+2ms, total 15ms
,I/PhenotypeConfigurator( 1010): Scheduling Phenotype for one-off execution 5433 seconds from now (1454950462217)
,D/GetConfigurationSnapshotOperation( 1010): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1010): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1010): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1010): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1010): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1010): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1010): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1010): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1010): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 1010): GC_CONCURRENT freed 505K, 4% free 18718K/19320K, paused 2ms+2ms, total 25ms
,I/dalvikvm( 1010): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1010): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1010): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 1117): GC_CONCURRENT freed 464K, 4% free 17941K/18600K, paused 3ms+1ms, total 17ms
,D/dalvikvm( 1010): GC_CONCURRENT freed 424K, 3% free 18882K/19400K, paused 3ms+4ms, total 32ms
,D/dalvikvm( 1010): GC_CONCURRENT freed 580K, 4% free 19023K/19700K, paused 4ms+6ms, total 36ms
,D/dalvikvm( 1010): GC_CONCURRENT freed 649K, 4% free 19149K/19892K, paused 3ms+7ms, total 34ms
,D/dalvikvm( 1010): GC_CONCURRENT freed 778K, 5% free 19144K/20016K, paused 2ms+4ms, total 21ms
,D/dalvikvm( 1010): GC_CONCURRENT freed 750K, 5% free 19123K/20016K, paused 3ms+6ms, total 22ms
,D/dalvikvm( 1010): GC_CONCURRENT freed 741K, 5% free 19130K/20016K, paused 3ms+4ms, total 22ms
,I/EventLogService( 1326): Aggregate from 1454948904466 (log), 1454948904466 (data)
,D/dalvikvm( 1326): GC_CONCURRENT freed 416K, 3% free 18740K/19188K, paused 3ms+2ms, total 18ms
,W/SQLiteConnectionPool( 1326): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ConnectivityService(  772): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  772): Done.
,D/ConnectivityService(  772): Setting timer for 720seconds
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/dalvikvm(  772): GC_CONCURRENT freed 1377K, 6% free 24227K/25644K, paused 30ms+4ms, total 105ms
,TIME-OUT KILL (timeout was 1200000ms)
```
