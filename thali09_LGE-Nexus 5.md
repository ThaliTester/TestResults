#### Test 50242285576d0b0_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/Velvet.VelvetFactory( 1190): refreshing search history.
I/Icing.InternalIcingCorporaProvider( 1190): Updating corpora: A: MAYBE, C: MAYBE
I/CalendarProvider2( 1558): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 1558): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/dalvikvm(  943): GC_CONCURRENT freed 247K, 2% free 17019K/17292K, paused 4ms+4ms, total 22ms
D/Finsky  ( 1657): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/GAV2    ( 1190): Thread[Thread-62,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/Sidekick_LocationOracleImpl( 1190): Best location was null
W/GAV2    ( 1190): Thread[Thread-62,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/Search.GservicesUpdateTask( 1190): Updating Gservices keys
D/Finsky  ( 1657): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/dalvikvm( 1102): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.n.a
W/dalvikvm( 1102): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/dalvikvm( 1102): VFY: replacing opcode 0x6e at 0x001c
D/dalvikvm( 1190): GC_CONCURRENT freed 244K, 3% free 18290K/18776K, paused 1ms+9ms, total 20ms
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AlertReceiver( 1698): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver (has extras) }
--------- beginning of /dev/log/system
I/ActivityManager(  627): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=1733 uid=10029 gids={50029}
V/MediaScanner(  943): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@4266df60
D/AlertUtils( 1698): Flushing old alerts from shared prefs table
D/AlertService( 1698): 0 Action = android.intent.action.BOOT_COMPLETED
V/MediaScanner(  943): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@4266df60
D/AlertService( 1698): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/dalvikvm( 1102): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.o.a
W/dalvikvm( 1102): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
D/dalvikvm( 1102): VFY: replacing opcode 0x6e at 0x001f
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1102): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.r.a
W/dalvikvm( 1102): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
D/dalvikvm( 1102): VFY: replacing opcode 0x6e at 0x0041
E/dalvikvm( 1102): Could not find class 'android.net.Network', referenced from method com.google.android.gms.auth.be.account.b.d.a
W/dalvikvm( 1102): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/auth/be/account/b/d;
D/dalvikvm( 1102): VFY: replacing opcode 0x1f at 0x031e
I/dalvikvm( 1102): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
W/dalvikvm( 1102): VFY: unable to resolve virtual method 24: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/dalvikvm( 1102): VFY: replacing opcode 0x6e at 0x0046
I/dalvikvm( 1102): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.account.a.a
W/dalvikvm( 1102): VFY: unable to resolve virtual method 23: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
D/dalvikvm( 1102): VFY: replacing opcode 0x6e at 0x00ba
D/AlarmScheduler( 1698): No events found starting within 1 week.
W/Search.LoginHelper( 1190): InterruptedException while waiting for token.
D/CellBroadcastReceiver( 1733): onReceive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 1733): Registering for ServiceState updates
D/dalvikvm( 1102): GC_CONCURRENT freed 349K, 4% free 18014K/18604K, paused 2ms+2ms, total 22ms
D/CellBroadcastReceiver( 1733): Service state changed! 1 Full: 1 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=true
I/dalvikvm( 1102): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1102): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1102): VFY: replacing opcode 0x6e at 0x0033
D/dalvikvm( 1304): GC_FOR_ALLOC freed 267K, 4% free 17831K/18412K, paused 12ms, total 12ms
I/ActivityManager(  627): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=1750 uid=10033 gids={50033, 1028}
V/AlarmClock( 1750): AlarmInitReceiver android.intent.action.BOOT_COMPLETED
W/Search.LoginHelper( 1190): IO exception for scope: mobilepersonalfeeds
W/SocketClient(  178): write error (Broken pipe)
W/Search.LoginHelper( 1190): IO exception for scope: mobilepersonalfeeds
W/Search.LoginHelper( 1190): IO exception for scope: mobilepersonalfeeds
V/AlarmClock( 1750): AlarmInitReceiver - Reset timers and clear stopwatch data
W/Search.LoginHelper( 1190): IO exception for scope: mobilepersonalfeeds
D/dalvikvm( 1102): GC_CONCURRENT freed 388K, 3% free 18068K/18604K, paused 1ms+2ms, total 15ms
W/Search.LoginHelper( 1190): IO exception for scope: mobilepersonalfeeds
W/Search.LoginHelper( 1190): IO exception for scope: mobilepersonalfeeds
I/AlarmClock( 1750): Displaying next alarm time: ''
D/dalvikvm(  627): GC_EXPLICIT freed 878K, 10% free 23586K/26076K, paused 2ms+3ms, total 50ms
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmClock( 1750): AlarmInitReceiver finished
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 1190): GC_CONCURRENT freed 369K, 3% free 18328K/18776K, paused 3ms+1ms, total 15ms
I/ActivityManager(  627): Start proc com.google.android.apps.genie.geniewidget for broadcast com.google.android.apps.genie.geniewidget/.miniwidget.MiniWidgetProvider: pid=1774 uid=10040 gids={50040, 3003, 1028, 1015}
W/Search.LoginHelper( 1190): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/System.out( 1774): [INFO:4]: LogSource: Logging disabled
W/Genie   ( 1774): Cache file not found: java.io.FileNotFoundException: /data/data/com.google.android.apps.genie.geniewidget/cache/genie_masfcache: open failed: ENOENT (No such file or directory)
W/Genie   ( 1774): Cache file not found: java.io.FileNotFoundException: /data/data/com.google.android.apps.genie.geniewidget/cache/genie_iconcache: open failed: ENOENT (No such file or directory)
W/Search.LoginHelper( 1190): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
I/Genie   ( 1774): MiniWidgetModel()
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/Genie   ( 1774): onReceive: intent action=android.intent.action.BOOT_COMPLETED
I/Genie   ( 1774): ignoring BOOT_COMPLETE since app has never been started
I/ActivityManager(  627): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=1792 uid=10041 gids={50041, 3003, 1028, 1015}
W/Search.LoginHelper( 1190): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 1102): GC_CONCURRENT freed 400K, 3% free 18072K/18624K, paused 1ms+2ms, total 14ms
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 1190): GC_CONCURRENT freed 220K, 2% free 18548K/18856K, paused 1ms+3ms, total 15ms
W/Search.LoginHelper( 1190): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Search.LoginHelper( 1190): IO exception for scope: mobilepersonalfeeds
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Search.LoginHelper( 1190): IO exception for scope: mobilepersonalfeeds
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityThread( 1792): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
W/Search.LoginHelper( 1190): IO exception for scope: mobilepersonalfeeds
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 1190): GC_CONCURRENT freed 569K, 4% free 18543K/19144K, paused 2ms+2ms, total 15ms
D/dalvikvm( 1792): GC_CONCURRENT freed 273K, 2% free 16847K/17152K, paused 6ms+3ms, total 23ms
I/ContactLoggerTask( 1190): canRun() : Disabled
I/Icing.InternalIcingCorporaProvider( 1190): UpdateCorporaTask done [took 572 ms] updated apps [took 536 ms] updated contacts [took 36 ms]
W/Search.LoginHelper( 1190): IO exception for scope: mobilepersonalfeeds
D/dalvikvm( 1102): GC_CONCURRENT freed 402K, 3% free 18079K/18624K, paused 1ms+16ms, total 31ms
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 1792): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/Search.LoginHelper( 1190): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/dalvikvm( 1792): GC_CONCURRENT freed 182K, 2% free 17072K/17284K, paused 1ms+1ms, total 12ms
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Search.LoginHelper( 1190): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  627): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=1824 uid=10052 gids={50052, 3003, 1028, 1015}
W/Search.LoginHelper( 1190): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 1304): GC_FOR_ALLOC freed 345K, 4% free 17838K/18412K, paused 15ms, total 15ms
W/Search.LoginHelper( 1190): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/dalvikvm( 1102): GC_CONCURRENT freed 374K, 3% free 18111K/18624K, paused 1ms+1ms, total 14ms
D/dalvikvm( 1792): GC_CONCURRENT freed 376K, 3% free 17136K/17544K, paused 2ms+2ms, total 14ms
I/Gmail   ( 1792): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 1792): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 1792): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 1792): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/dalvikvm( 1792): GC_CONCURRENT freed 363K, 3% free 17204K/17600K, paused 2ms+2ms, total 12ms
I/ActivityManager(  627): Delay finish: com.google.android.keep/.notification.AlertReceiver
D/dalvikvm( 1824): GC_CONCURRENT freed 199K, 2% free 16939K/17172K, paused 2ms+2ms, total 19ms
I/Gmail   ( 1792): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
I/Gmail   ( 1792): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
I/Gmail   ( 1792): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
I/Gmail   ( 1792): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^iim (has extras) }
I/ActivityManager(  627): Resuming delayed broadcast
I/LauncherIconVisibilityManager(  959): Boot has been completed
I/LauncherIconVisibilityManager(  959): Activity has already been disabled: ComponentInfo{com.google.android.inputmethod.latin/com.android.inputmethod.latin.setup.SetupActivity}
I/ActivityManager(  627): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=1847 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,D/dalvikvm(  182): GC_EXPLICIT freed 41K, 1% free 16698K/16772K, paused 1ms+1ms, total 14ms
D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+1ms, total 11ms
D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+1ms, total 11ms
I/ActivityManager(  627): Killing 1454:com.google.android.apps.magazines/u0a56 (adj 15): empty #17
I/ActivityManager(  627): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=1865 uid=1001 gids={41001, 3002, 3001, 3003, 2001, 1028, 1015}
D/QcrilMsgTunnelAutoboot( 1865): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
D/QcrilMsgTunnelService( 1865): onCreate method
D/QcrilMsgTunnelIfaceManager( 1865): : Instantiated
V/QcrilMsgTunnelSocket( 1865): Starting QcRilReceiver
D/QcrilMsgTunnelIfaceManager( 1865):  Registered for UNSOL OEM HOOK Responses to deliver external apps
D/QcrilMsgTunnelSocket( 1865): Connecting to socket android.net.LocalSocket@4263c9e8 impl:android.net.LocalSocketImpl@4263ca10 fd:FileDescriptor[42]
I/QcrilMsgTunnelSocket( 1865): Connected to 'qmux_radio/rild_oem0' socket
V/QcrilMsgTunnelSocket( 1865): Before reading offset = 0 remaining = 4 countRead = 0
I/ActivityManager(  627): Start proc com.google.android.email for broadcast com.google.android.email/com.android.email.service.EmailBroadcastReceiver: pid=1880 uid=10036 gids={50036, 3003, 1028, 1015}
D/ActivityThread( 1880): Loading provider com.google.android.email.provider;com.google.android.email.notifier: com.android.email.provider.EmailProvider
D/ActivityThread( 1880): Loading provider com.google.android.email.provider;com.google.android.email.notifier: com.android.email.provider.EmailProvider
I/ActivityManager(  627): Delay finish: com.google.android.email/com.android.email.service.EmailBroadcastReceiver
D/dalvikvm( 1880): GC_CONCURRENT freed 194K, 2% free 16910K/17136K, paused 2ms+1ms, total 13ms
D/AndroidRuntime( 1859): 
D/AndroidRuntime( 1859): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 1859): CheckJNI is OFF
D/dalvikvm( 1859): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 1859): Added shared lib libjavacore.so 0x0
D/dalvikvm( 1859): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 1859): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 1859): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 1859): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/dalvikvm(  627): GC_EXPLICIT freed 503K, 10% free 23610K/26076K, paused 2ms+4ms, total 47ms
W/ActivityManager(  627): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
W/ActivityManager(  627): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
I/Email   ( 1880): Observing account changes for notifications
W/ActivityManager(  627): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
I/ActivityManager(  627): Delaying start of: ServiceRecord{42d322c0 u0 com.google.android.exchange/com.android.exchange.service.EmailSyncAdapterService}
I/ActivityManager(  627): Start proc com.google.android.exchange for service com.google.android.exchange/com.android.exchange.service.EmailSyncAdapterService: pid=1910 uid=10037 gids={50037, 3003, 1028, 1015}
I/ActivityManager(  627): Killing 1434:com.android.settings/1000 (adj 15): empty #17
D/AndroidRuntime( 1859): Calling main entry com.android.commands.am.Am
D/PermissionCache(  181): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (100 us)
I/ActivityManager(  627): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 1859
I/Icing   ( 1304): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/dalvikvm(  627): GC_FOR_ALLOC freed 90K, 10% free 23581K/26076K, paused 41ms, total 41ms
I/dalvikvm-heap(  627): Grow heap (frag case) to 23.877MB for 856096-byte allocation
D/dalvikvm(  627): GC_FOR_ALLOC freed <1K, 10% free 24417K/26916K, paused 45ms, total 45ms
D/dalvikvm(  627): GC_FOR_ALLOC freed 4K, 10% free 24415K/26916K, paused 42ms, total 42ms
I/dalvikvm-heap(  627): Grow heap (frag case) to 24.693MB for 856096-byte allocation
D/dalvikvm(  627): GC_FOR_ALLOC freed <1K, 10% free 25251K/27756K, paused 36ms, total 36ms
D/AndroidRuntime( 1859): Shutting down VM
D/dalvikvm( 1859): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+1ms, total 2ms
D/dalvikvm( 1190): null clazz in OP_INSTANCE_OF, single-stepping
I/SearchController( 1190): #onHotwordDetectorStopped(false)
I/ActivityManager(  627): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=1928 uid=10115 gids={50115, 3003, 3001, 3002}
I/MicrophoneInputStream( 1190): mic_close
I/MicroHotwordRecognitionRunner( 1190): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1190): Stopping hotword detection.
I/ActivityManager(  627): Resuming delayed broadcast
I/ActivityManager(  627): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=1949 uid=10051 gids={50051, 3003, 1028, 1015, 3002}
I/ActivityManager(  627): Killing 1389:com.google.android.apps.maps/u0a57 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 1928): Binding Chromium to main looper Looper (main, tid 1) {42633178}
I/LibraryLoader( 1928): Expected native library version number "",actual native library version number ""
I/chromium( 1928): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 1928): Initializing chromium process, renderers=0
D/BluetoothManagerService(  627): Message: 20
D/BluetoothAdapter( 1928): 1113886888: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  627): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c34b78:true
I/Adreno-EGL( 1928): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
I/ActivityManager(  627): Killing 1536:com.google.android.dialer/u0a8 (adj 15): empty #17
D/Icing   ( 1304): Loaded CLD2 Version V2.0 - 20141016
W/chromium( 1928): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 1928): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 1928): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 1928): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 1928): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 1928): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 1928): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 1928): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 1928): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 1928): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 1928): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 1928): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 1928): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 1928): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 1928): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 1928): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 1928): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 1928): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 1928): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 1928): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 1928): Enabling debug mode 0
,W/AwContents( 1928): nativeOnDraw failed; clearing to background color.
,I/Icing   ( 1304): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/dalvikvm( 1949): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 1949): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x0008
,I/ActivityManager(  627): Displayed com.example.hello/.MainActivity: +311ms
,E/dalvikvm( 1949): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 1949): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 1949): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 1949): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 1949): VFY: replacing opcode 0x22 at 0x0037
,W/dalvikvm( 1949): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1949): Link of class 'Ldqp;' failed
,W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 1949): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1949): Link of class 'Ldqp;' failed
I/dalvikvm( 1949): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 1949): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 1949): VFY: replacing opcode 0x22 at 0x0000
W/dalvikvm( 1949): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 1949): Link of class 'Ldqp;' failed
,W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 1949): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1949): Link of class 'Ldqp;' failed
I/dalvikvm( 1949): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 1949): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 1949): VFY: replacing opcode 0x1c at 0x0026
W/dalvikvm( 1949): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1949): Link of class 'Ldqp;' failed
,W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 1949): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 1949): Link of class 'Ldqp;' failed
I/dalvikvm( 1949): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 1949): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 1949): Link of class 'Lax;' failed
E/dalvikvm( 1949): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 1949): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 1949): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 1949): Link of class 'Laz;' failed
,E/dalvikvm( 1949): Could not find class 'az', referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
D/dalvikvm( 1949): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 1949): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x0008
D/dalvikvm( 1949): GC_CONCURRENT freed 290K, 2% free 16885K/17208K, paused 2ms+3ms, total 22ms
I/dalvikvm( 1949): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 1949): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1949): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 1949): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 1949): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 1949): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 1949): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 1949): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
D/dalvikvm( 1949): VFY: replacing opcode 0x72 at 0x0000
W/dalvikvm( 1949): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 1949): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 1949): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
D/dalvikvm( 1949): VFY: replacing opcode 0x23 at 0x0005
I/dalvikvm( 1949): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 1949): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 1949): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
,W/dalvikvm( 1949): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 1949): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 1949): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 1949): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 1949): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 1949): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 1949): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 1949): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1949): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1949): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 1949): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 1949): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 1949): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 1949): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
D/dalvikvm( 1949): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 1949): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 1949): Link of class 'Lax;' failed
D/dalvikvm( 1949): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 1949): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 1949): Link of class 'Laz;' failed
D/dalvikvm( 1949): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 1949): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 1949): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 1949): GC_CONCURRENT freed 315K, 2% free 17081K/17428K, paused 3ms+1ms, total 10ms
,D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 1949): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4263bfd0
,D/dalvikvm( 1949): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4263bfd0
,D/dalvikvm( 1949): GC_CONCURRENT freed 257K, 2% free 17338K/17624K, paused 2ms+10ms, total 22ms
,D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/dalvikvm( 1949): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 1949): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 1949): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 1949): MmsConfig.loadMmsSettings
I/Babel_SMS( 1949): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 1949): MmsConfig.loadFromDatabase
,I/chromium( 1928): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 1928): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Babel_SMS( 1949): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 1949): MmsConfig.loadFromResources
,E/Babel_SMS( 1949): canonicalizeMccMnc: invalid mccmnc nullnull
D/dalvikvm( 1949): GC_CONCURRENT freed 213K, 1% free 17728K/17880K, paused 2ms+3ms, total 26ms
,D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/Babel_SMS( 1949): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,W/dalvikvm( 1949): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 1949): Link of class 'Lfzc;' failed
E/dalvikvm( 1949): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 1949): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
D/dalvikvm( 1949): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 1949): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 1949): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 1949): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 1949): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 1949): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x0033
,I/Babel_SMS( 1949): ApnsOta: OTA version -1
,I/dalvikvm( 1949): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 1949): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x0030
,W/dalvikvm( 1949): Unable to resolve superclass of Lfzc; (613)
,I/Babel   ( 1949): deleted: false for 0
W/dalvikvm( 1949): Link of class 'Lfzc;' failed
,D/dalvikvm( 1949): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,D/dalvikvm( 1949): GC_CONCURRENT freed 396K, 3% free 17800K/18228K, paused 2ms+1ms, total 13ms
,D/JsMessageQueue( 1928): Set native->JS mode to OnlineEventsBridgeMode
,W/Settings( 1949): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 1949): startup - clean
,I/dalvikvm( 1949): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 1949): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 1928): GC_CONCURRENT freed 217K, 2% free 16878K/17128K, paused 3ms+2ms, total 16ms
,D/dalvikvm( 1949): GC_CONCURRENT freed 206K, 2% free 18099K/18344K, paused 2ms+1ms, total 13ms
D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 4ms
W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 1949): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 1949): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 1949): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 1949): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
D/dalvikvm( 1949): VFY: replacing opcode 0x22 at 0x0071
W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 1949): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 1949): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
D/dalvikvm( 1949): VFY: replacing opcode 0x1f at 0x0021
W/dalvikvm( 1949): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 1949): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,V/Babel   ( 1949): babel boot account: thalitester@gmail.com
I/dalvikvm( 1949): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 1949): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 1949): VFY: replacing opcode 0x6e at 0x0074
I/ActivityManager(  627): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver
,D/dalvikvm( 1949): GC_CONCURRENT freed 214K, 2% free 18277K/18532K, paused 2ms+1ms, total 14ms
,I/vclib   ( 1949): onServiceConnected
,W/Babel   ( 1949): Attempted to change video mute state without an active call.
,D/dalvikvm( 1928): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42637fa0
,D/dalvikvm( 1928): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42637fa0
D/jxcore_app_log( 1928): JniHelper::setJavaVM(0x4151ef00), pthread_self() = 1979560952
,D/JX-Cordova( 1928): jxcore cordova android initializing
,D/dalvikvm( 1949): GC_CONCURRENT freed 163K, 2% free 18619K/18836K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 1928): GC_CONCURRENT freed 247K, 2% free 17142K/17420K, paused 1ms+2ms, total 14ms
,D/dalvikvm( 1949): GC_CONCURRENT freed 194K, 2% free 18998K/19252K, paused 3ms+2ms, total 19ms
,I/ActivityManager(  627): Resuming delayed broadcast
E/dalvikvm( 1949): Could not find class 'android.content.pm.LauncherApps', referenced from method cbk.a
W/dalvikvm( 1949): VFY: unable to resolve check-cast 469 (Landroid/content/pm/LauncherApps;) in Lcbk;
,D/dalvikvm( 1949): VFY: replacing opcode 0x1f at 0x0014
I/ActivityManager(  627): Killing 1586:com.google.android.configupdater/u0a2 (adj 15): empty #17
,D/dalvikvm( 1928): GC_CONCURRENT freed 376K, 3% free 17213K/17624K, paused 3ms+1ms, total 13ms
,D/dalvikvm( 1928): WAIT_FOR_CONCURRENT_GC blocked 4ms
,W/jxcore-log( 1928): Initializing JXcore engine
,W/jxcore-log( 1928): JXcore engine is ready
,D/dalvikvm( 1928): GC_CONCURRENT freed 263K, 3% free 17340K/17740K, paused 1ms+1ms, total 12ms
,D/dalvikvm( 1928): WAIT_FOR_CONCURRENT_GC blocked 10ms
,W/jxcore-log( 1928): Starting JXcore engine
,D/dalvikvm( 1949): GC_FOR_ALLOC freed 459K, 3% free 19179K/19716K, paused 13ms, total 14ms
,D/dalvikvm( 1949): GC_FOR_ALLOC freed 197K, 4% free 19361K/19972K, paused 13ms, total 13ms
,I/dalvikvm-heap( 1949): Grow heap (frag case) to 19.432MB for 521860-byte allocation
,D/dalvikvm( 1949): GC_FOR_ALLOC freed 254K, 5% free 19617K/20484K, paused 17ms, total 17ms
,D/dalvikvm( 1304): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1304): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1304): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1949): GC_FOR_ALLOC freed 628K, 5% free 19547K/20484K, paused 16ms, total 16ms
,D/FileApkUtils( 1304): Spent 22ms computing apk sha1.
,D/FileApkUtils( 1304): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1304): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-2707d05c501ef4bf821813f1789ad0e56682eb5a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1304): Keeping up-to-date module: module-2707d05c501ef4bf821813f1789ad0e56682eb5a
,D/dalvikvm( 1304): GC_CONCURRENT freed 385K, 3% free 17943K/18412K, paused 2ms+2ms, total 21ms
,D/GmsModuleFndr( 1304): Beginning GMS chimera module scan
,E/dalvikvm( 1304): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1304): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 1304): VFY: replacing opcode 0x1f at 0x000e
,D/dalvikvm( 1949): GC_FOR_ALLOC freed 126K, 4% free 19675K/20484K, paused 45ms, total 45ms
,I/dalvikvm-heap( 1949): Grow heap (frag case) to 19.738MB for 520922-byte allocation
D/dalvikvm( 1304): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1304): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1304): VFY: replacing opcode 0x62 at 0x0022
,D/ChimeraCfgMgr( 1304): Beginning module configuration check
,D/ChimeraCfgMgr( 1304): Module APKs unchanged, check complete
,E/dalvikvm( 1304): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1304): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 1304): VFY: replacing opcode 0x1f at 0x00ef
,W/dalvikvm( 1304): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1304): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1304): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 1304): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1304): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1304): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1304): VFY: replacing opcode 0x62 at 0x0008
,D/GCM     ( 1304): COMPAT: Multi user not supported
D/dalvikvm( 1304): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 1304): DexOpt: unable to optimize static field ref 0x00a2 at 0x0c in Lcom/google/android/gms/checkin/d;.a
,D/GCM     ( 1102): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,W/jxcore-log( 1928): Platform android
W/jxcore-log( 1928): 
,W/jxcore-log( 1928): Process ARCH arm
W/jxcore-log( 1928): 
,I/GoogleURLConnFactory( 1102): Using platform SSLCertificateSocketFactory
,I/GCoreUlr( 1304): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr(  978): DispatchingService.onCreate()
E/dalvikvm( 1102): Could not find class 'android.net.Network', referenced from method com.google.android.gms.auth.be.k.a
W/dalvikvm( 1102): VFY: unable to resolve check-cast 195 (Landroid/net/Network;) in Lcom/google/android/gms/auth/be/k;
,D/dalvikvm( 1102): VFY: replacing opcode 0x1f at 0x0149
,D/dalvikvm( 1304): GC_CONCURRENT freed 439K, 3% free 17996K/18472K, paused 2ms+3ms, total 23ms
,I/CheckinService( 1304): Checkin interval check for package: unspecified last checkin: 1449181161304 min interval config: 0 actual interval: 229800281
,D/dalvikvm( 1949): GC_FOR_ALLOC freed 254K, 6% free 19930K/20996K, paused 67ms, total 67ms
,I/jxcore-log( 1928): JXcore Cordova bridge is ready!
I/jxcore-log( 1928): 
,W/jxcore-log( 1928): JXcore engine is started
,D/dalvikvm(  978): GC_CONCURRENT freed 452K, 4% free 17863K/18416K, paused 3ms+7ms, total 38ms
,E/Recovery( 1102): Error while talking to recovery backend
E/Recovery( 1102): Error while updating recovery info: IOException
,E/Recovery( 1102): Error while talking to server: IOException
,D/dalvikvm( 1949): GC_FOR_ALLOC freed 750K, 5% free 19988K/20996K, paused 18ms, total 18ms
,W/dalvikvm( 1304): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1304): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/CheckinService( 1304): Disabling old GoogleServicesFramework version
,E/jxcore-log( 1928): >> LGE-Nexus 5
E/jxcore-log( 1928): 
,I/jxcore-log( 1928): Total memory 1945137152
I/jxcore-log( 1928): 
I/jxcore-log( 1928): Free memory 951099392
I/jxcore-log( 1928): 
I/jxcore-log( 1928): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1928): 
,I/jxcore-log( 1928): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1928): 
,I/jxcore-log( 1928): userPath [ 'www' ]
I/jxcore-log( 1928): 
,I/jxcore-log( 1928): Size 1080 1776
I/jxcore-log( 1928): 
,I/jxcore-log( 1928): Screen Brightness 1
I/jxcore-log( 1928): 
,E/jxcore-log( 1928): Dummy Error Log.
E/jxcore-log( 1928): 
,D/dalvikvm( 1949): GC_FOR_ALLOC freed 254K, 4% free 20243K/20996K, paused 37ms, total 37ms
,D/SystemUpdateService( 1304): onCreate
,I/CheckinService( 1304): Checking schedule, now: 1449410961659 next: 1449223650264
,I/CheckinService( 1304): active receiver: enabled
,D/SystemUpdateService( 1304): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/dalvikvm( 1304): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1304): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 1304): VFY: replacing opcode 0x6e at 0x040d
,I/GCoreUlr(  978): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,V/AuthZen ( 1304): Handling intent: android.intent.action.BOOT_COMPLETED
,W/Auth    ( 1102): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/dalvikvm( 1304): GC_CONCURRENT freed 384K, 3% free 18087K/18512K, paused 2ms+2ms, total 21ms
,V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AuthZenEventHandler( 1304): Handling event: android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 1102): GC_CONCURRENT freed 308K, 3% free 18205K/18684K, paused 2ms+3ms, total 21ms
,V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1304): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,I/SystemUpdateService( 1304): active receiver: enabled
,I/EventLogService( 1304): Aggregate from 1449408715881 (log), 1449408715881 (data)
,W/BaseAppContext( 1304): Using Auth Proxy for data requests.
,W/dalvikvm( 1304): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1304): GC_CONCURRENT freed 417K, 3% free 18176K/18628K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 1304): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 1304): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 1304): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 1304): WAIT_FOR_CONCURRENT_GC blocked 10ms
,W/dalvikvm( 1304): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1304): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/dalvikvm( 1304): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1304): WAIT_FOR_CONCURRENT_GC blocked 17ms
I/dalvikvm( 1304): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1304): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1304): VFY: replacing opcode 0x6e at 0x00bb
,I/SystemUpdateService( 1304): Already downloaded, skipping offpeak checks.
,I/dalvikvm( 1304): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1304): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1304): VFY: replacing opcode 0x6e at 0x002f
,D/PersistentNotificationBroadcastReceiver( 1102): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/dalvikvm( 1304): GC_CONCURRENT freed 407K, 3% free 18209K/18652K, paused 4ms+4ms, total 21ms
I/ActivityManager(  627): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=2053 uid=10057 gids={50057, 3003, 1028, 1015}
,D/dalvikvm( 1949): GC_CONCURRENT freed 771K, 4% free 20655K/21456K, paused 2ms+3ms, total 27ms
,D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/SystemUpdateService( 1304): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/GCoreUlr(  978): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/AuthZen ( 1304): Fetching signing key...
,I/GCoreUlr(  978): Unbound from all location providers
,I/AuthZen ( 1304): Signing key fetched successfully!
,W/BaseAppContext( 1304): Using Auth Proxy for data requests.
,W/dalvikvm( 1304): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/AuthZenTransactionCache( 1304): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1304): Clearing transaction cache
I/GCoreUlr(  978): DispatchingService.onDestroy()
,I/GCoreUlr(  978): Stopping handler for UlrDispSvcFast
,I/GCoreUlr(  978): Unbound from all location providers
,D/dalvikvm( 1304): GC_CONCURRENT freed 275K, 2% free 18359K/18668K, paused 2ms+2ms, total 16ms
,I/DownloadAttempt( 1304): current file is /cache/update.zip
,I/DownloadAttempt( 1304): mSize 2571501 mDownloaded 2571501
I/SystemUpdateService( 1304): status is 0 (complete)
I/SystemUpdateService( 1304): now status is 0 (complete)
I/SystemUpdateService( 1304): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1304): file has been verified
,I/SystemUpdateService( 1304): OTA package size = 2571501
,D/dalvikvm( 2053): GC_CONCURRENT freed 307K, 2% free 16823K/17160K, paused 4ms+2ms, total 20ms
,D/dalvikvm( 2053): Trying to load lib /data/app-lib/com.google.android.apps.maps-1/libcrashreporterer.so 0x4263a998
,I/SystemUpdateService( 1304): showing system update notification
,D/dalvikvm( 2053): Added shared lib /data/app-lib/com.google.android.apps.maps-1/libcrashreporterer.so 0x4263a998
,D/dalvikvm( 2053): Trying to load lib /data/app-lib/com.google.android.apps.maps-1/libgmm-jni.so 0x4263a998
,D/SystemUpdateService( 1304): onDestroy
,D/dalvikvm( 1949): GC_CONCURRENT freed 393K, 2% free 21586K/22008K, paused 10ms+1ms, total 34ms
,D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 2053): GC_CONCURRENT freed 255K, 2% free 17079K/17364K, paused 2ms+3ms, total 17ms
,D/dalvikvm( 2053): WAIT_FOR_CONCURRENT_GC blocked 2ms
,D/dalvikvm( 2053): WAIT_FOR_CONCURRENT_GC blocked 2ms
,D/dalvikvm( 2053): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2053): Added shared lib /data/app-lib/com.google.android.apps.maps-1/libgmm-jni.so 0x4263a998
,D/dalvikvm( 2053): GC_CONCURRENT freed 305K, 2% free 17274K/17556K, paused 2ms+2ms, total 21ms
,I/dalvikvm( 2053): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.d.a
W/dalvikvm( 2053): VFY: unable to resolve virtual method 311: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2053): VFY: replacing opcode 0x6e at 0x01fb
I/dalvikvm( 2053): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method com.google.android.apps.gmm.iamhere.ble.o.b
W/dalvikvm( 2053): VFY: unable to resolve virtual method 1434: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 2053): VFY: replacing opcode 0x6e at 0x00a6
I/ActivityManager(  627): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2079 uid=10071 gids={50071, 3003, 1028, 1015}
I/ActivityManager(  627): Killing 1625:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #17
,I/dalvikvm( 2053): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.d.a
W/dalvikvm( 2053): VFY: unable to resolve virtual method 556: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2053): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 2053): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.d.c
W/dalvikvm( 2053): VFY: unable to resolve virtual method 311: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2053): VFY: replacing opcode 0x6e at 0x01c0
,D/dalvikvm( 2053): GC_CONCURRENT freed 304K, 2% free 17386K/17720K, paused 2ms+3ms, total 16ms
,I/jxcore-log( 1928): getBuffer is called!!!!
I/jxcore-log( 1928): 
,D/dalvikvm(  627): GC_EXPLICIT freed 572K, 9% free 25367K/27748K, paused 2ms+4ms, total 69ms
,D/dalvikvm( 1949): GC_CONCURRENT freed 1126K, 5% free 22089K/23248K, paused 3ms+1ms, total 39ms
,D/dalvikvm( 1949): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/com.google.a.a.b.d.a( 2053): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  627): Message: 20
,D/BluetoothManagerService(  627): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e0b150:true
,D/dalvikvm( 2053): GC_CONCURRENT freed 243K, 2% free 17530K/17804K, paused 3ms+1ms, total 16ms
,D/dalvikvm( 1928): GC_FOR_ALLOC freed 643K, 5% free 16932K/17768K, paused 8ms, total 8ms
,D/dalvikvm( 1928): GC_CONCURRENT freed 269K, 4% free 17110K/17768K, paused 2ms+2ms, total 12ms
,D/dalvikvm( 1928): GC_CONCURRENT freed 374K, 4% free 17178K/17768K, paused 2ms+7ms, total 18ms
,E/dalvikvm( 2079): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 2079): VFY: unable to resolve new-instance 404 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 2079): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 2079): Unable to resolve superclass of Lal; (761)
,W/dalvikvm( 2079): Link of class 'Lal;' failed
E/dalvikvm( 2079): Could not find class 'al', referenced from method b.a
W/dalvikvm( 2079): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 2079): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 2079): Unable to resolve superclass of Lan; (761)
,W/dalvikvm( 2079): Link of class 'Lan;' failed
E/dalvikvm( 2079): Could not find class 'an', referenced from method b.a
W/dalvikvm( 2079): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 2079): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 2079): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 2079): VFY: unable to resolve virtual method 5625: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 2079): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 2079): VFY: unable to resolve virtual method 5440: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x0006
,D/dalvikvm( 2079): GC_CONCURRENT freed 260K, 2% free 16860K/17152K, paused 1ms+3ms, total 19ms
,W/dalvikvm( 2079): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 2079): Could not find class 'android.app.RemoteInput[]', referenced from method b.b
W/dalvikvm( 2079): VFY: unable to resolve new-array 12965 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 2079): VFY: replacing opcode 0x23 at 0x0007
,D/dalvikvm( 1928): GC_CONCURRENT freed 421K, 4% free 17219K/17768K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 1928): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2079): DexOpt: unable to opt direct call 0x09cd at 0x0e in Lb;.a
W/dalvikvm( 2079): Unable to resolve superclass of Lal; (761)
,W/dalvikvm( 2079): Link of class 'Lal;' failed
,D/dalvikvm( 2079): DexOpt: unable to opt direct call 0x0741 at 0x08 in Lb;.a
W/dalvikvm( 2079): Unable to resolve superclass of Lan; (761)
,W/dalvikvm( 2079): Link of class 'Lan;' failed
,D/dalvikvm( 2079): DexOpt: unable to opt direct call 0x08c3 at 0x2c in Lb;.a
,D/dalvikvm( 2079): DexOpt: unable to opt direct call 0x0a11 at 0x0f in Lb;.b
,D/dalvikvm( 1928): GC_FOR_ALLOC freed 37K, 3% free 17238K/17768K, paused 8ms, total 8ms
,I/dalvikvm-heap( 1928): Grow heap (frag case) to 16.944MB for 87220-byte allocation
I/dalvikvm( 2079): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eau.a
W/dalvikvm( 2079): VFY: unable to resolve virtual method 2836: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 1928): GC_FOR_ALLOC freed 56K, 4% free 17266K/17856K, paused 12ms, total 12ms
I/ActivityManager(  627): Killing 1060:com.android.printspooler/u0a64 (adj 15): empty #17
,D/dalvikvm( 1928): GC_FOR_ALLOC freed <1K, 4% free 17266K/17856K, paused 8ms, total 8ms
,I/dalvikvm-heap( 1928): Grow heap (frag case) to 17.013MB for 130826-byte allocation
,D/dalvikvm( 1928): GC_FOR_ALLOC freed 0K, 4% free 17394K/17984K, paused 9ms, total 9ms
,D/dalvikvm( 2079): GC_CONCURRENT freed 280K, 2% free 17056K/17372K, paused 2ms+2ms, total 12ms
D/dalvikvm( 2079): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2079): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2079): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2079): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2079): VFY: unable to resolve instance field 46
,D/dalvikvm( 2079): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 2079): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2079): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2079): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2079): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2079): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 2079): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4262e980
,D/dalvikvm( 2079): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4262e980
,D/dalvikvm( 2079): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4262e980, skipping init
,D/dalvikvm( 2079): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4262e980
,D/dalvikvm( 2079): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4262e980
,V/JNIHelp ( 2079): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 1928): GC_FOR_ALLOC freed 85K, 4% free 17308K/17984K, paused 8ms, total 8ms
,I/dalvikvm-heap( 1928): Grow heap (frag case) to 17.117MB for 196234-byte allocation
,D/dalvikvm( 1928): GC_FOR_ALLOC freed 0K, 4% free 17500K/18176K, paused 9ms, total 9ms
,D/dalvikvm( 1928): GC_FOR_ALLOC freed 127K, 5% free 17372K/18176K, paused 7ms, total 7ms
,D/dalvikvm( 2079): GC_CONCURRENT freed 332K, 3% free 17213K/17576K, paused 2ms+1ms, total 11ms
,D/dalvikvm( 1928): GC_FOR_ALLOC freed 441K, 7% free 17078K/18176K, paused 9ms, total 9ms
D/dalvikvm( 2079): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4262e980
D/dalvikvm( 2079): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4262e980
D/dalvikvm( 2079): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4262e980
,D/dalvikvm( 2079): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4262e980
,I/ProviderInstaller( 2079): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 2079): GC_CONCURRENT freed 197K, 2% free 17415K/17696K, paused 3ms+1ms, total 11ms
,E/YouTube MDX( 2079): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 2079): GC_CONCURRENT freed 346K, 3% free 17582K/17956K, paused 4ms+5ms, total 36ms
D/dalvikvm( 2079): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 2079): WAIT_FOR_CONCURRENT_GC blocked 13ms
I/dalvikvm( 2079): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 2079): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 2079): VFY: replacing opcode 0x71 at 0x0046
,I/dalvikvm( 2079): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 2079): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 2079): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 2079): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x0220
,D/dalvikvm( 2079): DexOpt: --- BEGIN 'ads675703040.jar' (bootstrap=0) ---
,D/dalvikvm( 2079): GC_CONCURRENT freed 280K, 2% free 17815K/18120K, paused 4ms+5ms, total 40ms
,D/dalvikvm( 2137): DexOpt: load 4ms, verify+opt 12ms, 188892 bytes
,D/dalvikvm( 2079): DexOpt: --- END 'ads675703040.jar' (success) ---
,D/dalvikvm( 2079): DEX prep '/data/data/com.google.android.youtube/cache/ads675703040.jar': unzip in 0ms, rewrite 81ms
,D/dalvikvm( 2079): GC_CONCURRENT freed 302K, 2% free 18024K/18356K, paused 4ms+1ms, total 22ms
D/dalvikvm( 2079): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2079): WAIT_FOR_CONCURRENT_GC blocked 7ms
,I/dalvikvm( 2079): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method aex.getActivityBanner
W/dalvikvm( 2079): VFY: unable to resolve virtual method 2807: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2079): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method aex.getActivityBanner
W/dalvikvm( 2079): VFY: unable to resolve virtual method 2808: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2079): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method aex.getApplicationBanner
W/dalvikvm( 2079): VFY: unable to resolve virtual method 2815: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2079): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method aex.getApplicationBanner
W/dalvikvm( 2079): VFY: unable to resolve virtual method 2816: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2079): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method aex.getLeanbackLaunchIntentForPackage
W/dalvikvm( 2079): VFY: unable to resolve virtual method 2832: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2079): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method aex.getPackageInstaller
W/dalvikvm( 2079): VFY: unable to resolve virtual method 2836: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2079): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method aex.getUserBadgedDrawableForDensity
W/dalvikvm( 2079): VFY: unable to resolve virtual method 2852: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2079): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method aex.getUserBadgedIcon
,W/dalvikvm( 2079): VFY: unable to resolve virtual method 2853: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x0002
W/InstanceID/Rpc( 2079): Found 10007
,I/dalvikvm( 2079): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method aex.getUserBadgedLabel
W/dalvikvm( 2079): VFY: unable to resolve virtual method 2854: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 2079): VFY: replacing opcode 0x6e at 0x0002
,I/ActivityManager(  627): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver
,D/dalvikvm( 2079): GC_CONCURRENT freed 250K, 2% free 18172K/18452K, paused 2ms+6ms, total 20ms
,I/ActivityManager(  627): Resuming delayed broadcast
,I/ActivityManager(  627): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.ads.preload.PreloadVideosTransferService$DeviceStateReceiver
,I/ActivityManager(  627): Resuming delayed broadcast
,W/BroadcastQueue(  627): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.google.android.apps.plus/com.google.android.libraries.social.notifications.impl.BootCompletedReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/ActivityManager(  627): Killing 1207:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,D/WearableService(  978): callingUid 10007, callindPid: 978
,E/MDM     (  978): [66] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1304): Restart initialization of location
I/ActivityManager(  627): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp(  978): No location to return for getLastLocation()
,W/FusedLocationProvider( 1102): location=null
,I/ActivityManager(  627): Resuming delayed broadcast
D/GCM     ( 1102): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1102): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1102): Proximity feature is not enabled.
,V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  627): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  627): Resuming delayed broadcast
,V/GmsCoreStatsServiceLauncher( 1304): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  627): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  627): Resuming delayed broadcast
,E/MDM     (  978): [67] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1304): Restart initialization of location
I/ActivityManager(  627): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp(  978): No location to return for getLastLocation()
,W/FusedLocationProvider( 1102): location=null
,D/GCM     ( 1102): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1102): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1102): Proximity feature is not enabled.
I/ActivityManager(  627): Resuming delayed broadcast
,V/GLSActivity( 1102): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  627): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  627): Resuming delayed broadcast
I/ActivityManager(  627): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,V/GmsCoreStatsServiceLauncher( 1304): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  627): Resuming delayed broadcast
,D/dalvikvm( 1102): GC_CONCURRENT freed 422K, 3% free 18191K/18708K, paused 1ms+2ms, total 18ms
,I/ActivityManager(  627): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2185 uid=10011 gids={50011, 3003}
,I/ActivityManager(  627): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  627): Resuming delayed broadcast
,I/ActivityManager(  627): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  627): Resuming delayed broadcast
,I/ActivityManager(  627): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2200 uid=10013 gids={50013, 3003, 3002}
,I/ActivityManager(  627): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  627): Resuming delayed broadcast
,I/Icing.InternalIcingCorporaProvider( 1190): Updating corpora: A: com.example.hello, C: MAYBE
I/ActivityManager(  627): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/dalvikvm( 1190): GC_CONCURRENT freed 1130K, 7% free 18024K/19184K, paused 1ms+1ms, total 11ms
,I/Icing.InternalIcingCorporaProvider( 1190): UpdateCorporaTask done [took 51 ms] updated apps [took 51 ms] 
I/ActivityManager(  627): Killing 1733:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,D/dalvikvm( 1304): GC_CONCURRENT freed 496K, 3% free 18298K/18828K, paused 1ms+1ms, total 19ms
,I/GAV2    ( 1190): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1304): Google Analytics 8.3.01 is starting up.
,I/GAV2    ( 1792): Thread[GAThread,5,main]: No campaign data found.
,I/Icing   ( 1304): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,I/Icing   ( 1304): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/ActivityManager(  627): Resuming delayed broadcast
,I/ActivityManager(  627): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2229 uid=10035 gids={50035, 1028, 3003, 1015}
,I/dalvikvm( 2229): Could not find method android.app.Activity.finishAfterTransition, referenced from method bx.onBackPressed
,W/dalvikvm( 2229): VFY: unable to resolve virtual method 1145: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 2229): VFY: replacing opcode 0x6e at 0x0012
,D/dalvikvm( 2229): GC_CONCURRENT freed 309K, 2% free 16870K/17208K, paused 2ms+2ms, total 14ms
,D/dalvikvm( 2229): GC_CONCURRENT freed 304K, 2% free 17000K/17332K, paused 0ms+2ms, total 10ms
,I/dalvikvm( 2229): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gwe.a
W/dalvikvm( 2229): VFY: unable to resolve virtual method 1697: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2229): VFY: replacing opcode 0x6e at 0x000f
,I/dalvikvm( 2229): Could not find method android.content.Context.checkSelfPermission, referenced from method arg.a
W/dalvikvm( 2229): VFY: unable to resolve virtual method 1515: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 2229): VFY: replacing opcode 0x6e at 0x001b
,I/GAv4    ( 2229): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2229):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2229):   adb logcat -s GAv4
,D/dalvikvm( 2229): GC_CONCURRENT freed 260K, 2% free 17261K/17500K, paused 2ms+1ms, total 13ms
,W/GAv4    ( 2229): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2229): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2229): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/dalvikvm( 2229): GC_CONCURRENT freed 328K, 3% free 17446K/17804K, paused 1ms+2ms, total 16ms
,D/dalvikvm( 2229): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2229): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2229): WAIT_FOR_CONCURRENT_GC blocked 2ms
,W/AnalyticsTrackerProxyImpl( 2229): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.453.15.35, sample rate 1.0
I/dalvikvm( 2229): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method efh.a
W/dalvikvm( 2229): VFY: unable to resolve static method 2872: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 2229): VFY: replacing opcode 0x71 at 0x0075
,D/dalvikvm( 2229): GC_CONCURRENT freed 386K, 3% free 17573K/17988K, paused 1ms+2ms, total 15ms
,D/dalvikvm( 2229): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 2229): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 2229): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2229): GC_CONCURRENT freed 299K, 2% free 17788K/18116K, paused 2ms+2ms, total 16ms
,D/dalvikvm( 2229): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2229): WAIT_FOR_CONCURRENT_GC blocked 4ms
,I/ActivityManager(  627): Killing 1558:com.android.providers.calendar/u0a1 (adj 15): empty #17
,I/ActivityManager(  627): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 1304): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1304): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1304): Loading module APK com.google.android.play.games
I/ActivityManager(  627): Resuming delayed broadcast
,D/dalvikvm( 2229): GC_CONCURRENT freed 383K, 3% free 17902K/18316K, paused 6ms+2ms, total 33ms
,I/PeopleContactsSync( 1304): CP2 sync disabled
,I/dalvikvm( 1304): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1304): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1304): VFY: replacing opcode 0x6e at 0x000e
,D/dalvikvm( 1304): GC_CONCURRENT freed 323K, 3% free 18400K/18828K, paused 18ms+2ms, total 35ms
D/dalvikvm( 2229): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2229): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2229): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2229): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2229): VFY: unable to resolve instance field 46
,D/dalvikvm( 2229): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2229): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2229): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2229): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 2229): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2229): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 2229): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42716e88
D/dalvikvm( 2229): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42716e88
,D/dalvikvm( 2229): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42716e88, skipping init
,D/dalvikvm( 2229): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42716e88
D/dalvikvm( 2229): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42716e88
,V/JNIHelp ( 2229): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/dalvikvm( 1304): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1304): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1304): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1304): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1304): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1304): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1304): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1304): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
D/dalvikvm( 2229): GC_CONCURRENT freed 458K, 3% free 17952K/18444K, paused 1ms+2ms, total 15ms
,D/dalvikvm( 2229): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2229): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42716e88
,D/dalvikvm( 2229): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42716e88
D/dalvikvm( 2229): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42716e88
,D/dalvikvm( 2229): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42716e88
,D/dalvikvm( 2229): GC_FOR_ALLOC freed 108K, 3% free 18049K/18484K, paused 12ms, total 13ms
,D/ChimeraCfgMgr( 1304): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1304): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1304): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1304): Submit a task: h
,I/ProviderInstaller( 2229): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 1304): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1304): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/h       ( 1304): Processing package: com.example.hello
,I/ActivityManager(  627): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2285 uid=10065 gids={50065, 3003, 1028, 1015}
D/GassUtils( 1304): Found app info for package com.example.hello:18. Hash: 7e411fc8c80adb766ff5747826a81d96c76dd9cb2b76f4f040d3bd27a68f585b
D/h       ( 1304): Found info for package com.example.hello in db.
,W/BaseAppContext( 1304): Using Auth Proxy for data requests.
,W/BaseAppContext( 1304): Using Auth Proxy for data requests.
,D/dalvikvm(  182): GC_EXPLICIT freed 42K, 1% free 16698K/16772K, paused 1ms+2ms, total 15ms
,D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+1ms, total 13ms
,W/BaseAppContext( 1304): Using Auth Proxy for data requests.
,D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+1ms, total 14ms
,W/BaseAppContext( 1304): Using Auth Proxy for data requests.
,W/BaseAppContext( 1304): Using Auth Proxy for data requests.
,W/BaseAppContext( 1304): Using Auth Proxy for data requests.
,D/dalvikvm( 1304): GC_CONCURRENT freed 335K, 2% free 18546K/18912K, paused 3ms+2ms, total 20ms
,W/Quickoffice( 2285): Cleanup of storage: done
,D/com.google.android.apps.docs.quickoffice.X( 2285): Loading recent documents list
,D/Quickoffice( 2285): The number of lines present in  /proc/mount 21
,D/Quickoffice( 2285): Parsing the storagedefinition.xml.
,D/Quickoffice( 2285): # of Storagedefinitions - 35
D/Quickoffice( 2285): The # of storage definitions available - 35
,D/Quickoffice( 2285): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2285): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
,D/Quickoffice( 2285): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2285): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2285): Processing mountline proc /proc proc rw,relatime 0 0
,D/Quickoffice( 2285): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2285): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2285): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
,D/Quickoffice( 2285): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2285): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
,D/Quickoffice( 2285): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2285): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2285): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
,D/Quickoffice( 2285): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2285): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
,D/Quickoffice( 2285): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2285): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
,D/Quickoffice( 2285): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2285): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
,D/Quickoffice( 2285): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/Quickoffice( 2285): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/Quickoffice( 2285): Build properties are not configured for this storage definition.
,D/Quickoffice( 2285): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
,D/dalvikvm( 2285): GC_CONCURRENT freed 207K, 2% free 16915K/17152K, paused 3ms+2ms, total 13ms
,D/Quickoffice( 2285): The # of mounts identified -  1
,D/com.google.android.apps.docs.quickoffice.X( 2285): Checking validity of 0 items
,I/ActivityManager(  627): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2302 uid=10063 gids={50063, 3003, 3002, 1028, 1015}
,I/ActivityManager(  627): Killing 1750:com.google.android.deskclock/u0a33 (adj 15): empty #17
,W/ActivityManager(  627): No permission grants found for com.quickoffice.android
,D/ContentResolverUtil( 2285): There are 0 persisted uri permissions.
,D/com.google.android.apps.docs.quickoffice.X( 2285): 0 items were valid
,W/Quickoffice( 2285): Could not load clipboard.
,W/Quickoffice( 2285): Could not store clipboard.
,D/dalvikvm( 1304): GC_CONCURRENT freed 345K, 2% free 18743K/19120K, paused 1ms+2ms, total 18ms
,D/ChimeraCfgMgr( 1304): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1304): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  627): Killing 1774:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,E/dalvikvm( 2302): Could not find class 'android.app.Notification$Action$Builder', referenced from method tp.a
,W/dalvikvm( 2302): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Ltp;
,D/dalvikvm( 2302): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 2302): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve new-instance 575 (Landroid/graphics/drawable/RippleDrawable;) in Ltp;
,D/dalvikvm( 2302): VFY: replacing opcode 0x22 at 0x000b
,E/dalvikvm( 2302): Could not find class 'android.app.Notification$Action$Builder', referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Ltp;
,D/dalvikvm( 2302): VFY: replacing opcode 0x22 at 0x0000
,D/dalvikvm( 2302): GC_CONCURRENT freed 192K, 2% free 16932K/17156K, paused 2ms+2ms, total 14ms
,W/dalvikvm( 2302): Unable to resolve superclass of Lcb; (795)
W/dalvikvm( 2302): Link of class 'Lcb;' failed
E/dalvikvm( 2302): Could not find class 'cb', referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve new-instance 2076 (Lcb;) in Ltp;
,D/dalvikvm( 2302): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 2302): Unable to resolve superclass of Lcd; (795)
W/dalvikvm( 2302): Link of class 'Lcd;' failed
E/dalvikvm( 2302): Could not find class 'cd', referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve new-instance 2130 (Lcd;) in Ltp;
D/dalvikvm( 2302): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 2302): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve virtual method 5252: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2302): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 2302): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve virtual method 5837: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 2302): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 2302): Could not find method android.view.View.getTransitionName, referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve virtual method 5588: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 2302): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 2302): Could not find method android.transition.Transition.getTargetNames, referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve virtual method 5241: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 2302): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 2302): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve interface method 5907: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 2302): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2302): Could not find method android.view.ViewParent.onNestedFling, referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve interface method 5906: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 2302): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2302): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve interface method 5911: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 2302): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 2302): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 2302): Could not find class 'android.app.RemoteInput[]', referenced from method tp.a
W/dalvikvm( 2302): VFY: unable to resolve new-array 13298 ([Landroid/app/RemoteInput;) in Ltp;
,D/dalvikvm( 2302): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 2302): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method tp.b
W/dalvikvm( 2302): VFY: unable to resolve virtual method 5252: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2302): VFY: replacing opcode 0x6e at 0x0009
,D/dalvikvm( 2302): DexOpt: unable to opt direct call 0x09ef at 0x0e in Ltp;.a
,D/dalvikvm( 2302): DexOpt: unable to opt direct call 0x0d75 at 0x0e in Ltp;.a
,D/dalvikvm( 2302): DexOpt: unable to opt direct call 0x09ef at 0x0e in Ltp;.a
W/dalvikvm( 2302): Unable to resolve superclass of Lcb; (795)
W/dalvikvm( 2302): Link of class 'Lcb;' failed
,D/dalvikvm( 2302): DexOpt: unable to opt direct call 0x314d at 0x08 in Ltp;.a
W/dalvikvm( 2302): Unable to resolve superclass of Lcd; (795)
W/dalvikvm( 2302): Link of class 'Lcd;' failed
D/dalvikvm( 2302): DexOpt: unable to opt direct call 0x3301 at 0x30 in Ltp;.a
,D/dalvikvm( 2302): DexOpt: unable to opt direct call 0x0a47 at 0x13 in Ltp;.a
,D/dalvikvm( 2302): GC_CONCURRENT freed 318K, 3% free 17041K/17392K, paused 1ms+1ms, total 10ms
,D/dalvikvm( 2302): GC_CONCURRENT freed 272K, 2% free 17227K/17532K, paused 2ms+2ms, total 11ms
,I/dalvikvm( 2302): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eds.a
W/dalvikvm( 2302): VFY: unable to resolve virtual method 2579: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2302): VFY: replacing opcode 0x6e at 0x023c
I/dalvikvm( 2302): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eds.a
W/dalvikvm( 2302): VFY: unable to resolve virtual method 2951: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2302): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 2302): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eds.c
W/dalvikvm( 2302): VFY: unable to resolve virtual method 2579: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2302): VFY: replacing opcode 0x6e at 0x0207
,D/dalvikvm( 2302): GC_CONCURRENT freed 288K, 2% free 17391K/17708K, paused 2ms+2ms, total 12ms
,D/dalvikvm( 2302): Trying to load lib /data/app-lib/com.google.android.apps.plus-2/libcrashreporterer.so 0x42639b68
,D/dalvikvm( 2302): Added shared lib /data/app-lib/com.google.android.apps.plus-2/libcrashreporterer.so 0x42639b68
,I/ActivityManager(  627): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  627): Resuming delayed broadcast
,I/ActivityManager(  627): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  627): Resuming delayed broadcast
,I/ActivityManager(  627): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2332 uid=10058 gids={50058, 3003, 1028, 1015}
,I/ActivityManager(  627): Killing 1792:com.google.android.gm/u0a41 (adj 15): empty #17
,I/MultiDex( 2332): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 2332): install
,I/MultiDex( 2332): MultiDexExtractor.load(/data/app/com.google.android.music-1.apk, false)
,I/MultiDex( 2332): loading existing secondary dex files
,I/MultiDex( 2332): load found 1 secondary dex files
,I/MultiDex( 2332): install done
,D/dalvikvm( 2332): GC_CONCURRENT freed 213K, 2% free 16902K/17148K, paused 1ms+3ms, total 15ms
,I/BaseStore( 2332): Store database version: 123
,I/dalvikvm( 2332): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zza
W/dalvikvm( 2332): VFY: unable to resolve virtual method 613: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2332): VFY: replacing opcode 0x6e at 0x00c2
I/dalvikvm( 2332): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzk
W/dalvikvm( 2332): VFY: unable to resolve virtual method 981: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2332): VFY: replacing opcode 0x6e at 0x000b
,D/dalvikvm(  627): GC_EXPLICIT freed 555K, 9% free 25418K/27748K, paused 1ms+4ms, total 44ms
,D/dalvikvm( 2332): GC_CONCURRENT freed 320K, 3% free 17050K/17400K, paused 2ms+0ms, total 10ms
,D/MusicLifecycle( 2332): com.google.android.music.MusicApplication generated event: Application created
,D/dalvikvm( 2332): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2332): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2332): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2332): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2332): VFY: unable to resolve instance field 46
,D/dalvikvm( 2332): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2332): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2332): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2332): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2332): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2332): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 2332): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426bad10
D/dalvikvm( 2332): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426bad10
,D/dalvikvm( 2332): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426bad10, skipping init
,D/dalvikvm( 2332): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x426bad10
D/dalvikvm( 2332): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x426bad10
,V/JNIHelp ( 2332): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 2332): GC_CONCURRENT freed 373K, 3% free 17189K/17592K, paused 1ms+2ms, total 14ms
,D/dalvikvm( 2332): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2332): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426bad10
,D/dalvikvm( 2332): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x426bad10
D/dalvikvm( 2332): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x426bad10
,D/dalvikvm( 2332): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x426bad10
,I/ProviderInstaller( 2332): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 2332): GMSCore installation verified
,D/dalvikvm( 2332): GC_CONCURRENT freed 203K, 2% free 17389K/17712K, paused 3ms+2ms, total 18ms
,I/BaseStore( 2332): ConfigStore database version: 1
,I/MediaRouter( 2332): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, deviceType=0, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/MusicLifecycle( 2332): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@426d9f78 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,D/MusicLifecycle( 2332): com.google.android.music.net.NetworkMonitor generated event: Service created
I/ActivityManager(  627): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/MusicLifecycle( 2332): com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
,D/MusicLifecycle( 2332): com.google.android.music.download.cache.StorageMigrationService generated event: Service created
,D/MusicLifecycle( 2332): com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
,D/MusicLifecycle( 2332): com.google.android.music.download.ArtDownloadQueueService generated event: Service created
I/ActivityManager(  627): Resuming delayed broadcast
,I/GHttpClientFactory( 2332): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/dalvikvm( 2332): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2332): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2332): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.GoogleURLConnectionFactory.openConnection
W/dalvikvm( 2332): VFY: unable to resolve virtual method 1704: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2332): VFY: replacing opcode 0x6e at 0x00a0
,I/GoogleURLConnFactory( 2332): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 2332): GC_CONCURRENT freed 284K, 2% free 17493K/17808K, paused 2ms+1ms, total 13ms
,D/MusicLifecycle( 2332): com.google.android.music.download.cache.ArtCacheService generated event: Service created
,D/MusicLifecycle( 2332): com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
,D/MusicLifecycle( 2332): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@426d9f78 and intent Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,D/MusicLifecycle( 2332): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@426d9f78 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,D/MusicLifecycle( 2332): com.google.android.music.store.MediaStoreImportService generated event: Service created
,D/MusicLifecycle( 2332): com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
,D/AlertReceiver( 1698): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
I/ActivityManager(  627): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  627): Resuming delayed broadcast
I/ActivityManager(  627): Killing 1824:com.google.android.keep/u0a52 (adj 15): empty #17
,D/AlertService( 1698): 0 Action = android.intent.action.PROVIDER_CHANGED
I/ActivityManager(  627): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,D/BluetoothManagerService(  627): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  627): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  627): Message: 2
,I/jxcore-log( 1928): ****TEST TOOK:  5019  ms ****
I/jxcore-log( 1928): 
,I/jxcore-log( 1928): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1928): 
D/WifiService(  627): setWifiEnabled: false pid=1928, uid=10115
,D/AndroidRuntime( 2362): 
D/AndroidRuntime( 2362): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2362): CheckJNI is OFF
,D/dalvikvm( 2362): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 2362): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 2362): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2362): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 2362): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 2362): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,D/AndroidRuntime( 2362): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  627): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  627): Killing 1928:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  627): Force removing ActivityRecord{4273c6a8 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/WindowState(  627): WIN DEATH: Window{42de0768 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  627): Skipping PackageSetting{42716cb0 com.test.thalitest/10108} due to missing metadata
,I/ActivityManager(  627): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/InputReader(  627): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine(  978): Ignoring removeGeofence because network location is disabled.
,I/PackageManager(  627):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  627):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  627):   Scheme: "sms"
I/PackageManager(  627): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  627):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  627):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  627):   Scheme: "smsto"
I/PackageManager(  627): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/BackupManagerService(  627): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  627): removePackageParticipantsLocked: uid=10115 #1
,I/PackageManager(  627):   Action: "android.intent.action.SENDTO"
I/PackageManager(  627):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  627):   Scheme: "mms"
I/PackageManager(  627): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  959): GC_CONCURRENT freed 291K, 2% free 17004K/17320K, paused 2ms+1ms, total 13ms
,I/LatinIME:LogUtils(  959): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
,I/PackageManager(  627):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  627):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  627):   Scheme: "mmsto"
,I/PackageManager(  627): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/Sidekick_LocationOracleImpl( 1190): Best location was null
,W/Binder  (  959): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  959): java.lang.NullPointerException
W/Binder  (  959): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  959): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  959): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  959): 	at dalvik.system.NativeStart.run(Native Method)
,D/Launcher.Workspace( 1040): 11683562 - stripEmptyScreens()
,W/InputMethodManagerService(  627): Got RemoteException sending setActive(false) notification to pid 1928 uid 10115
D/Launcher.Workspace( 1040): 11683562 - stripEmptyScreens()
,I/PackageManager(  627):   Action: "android.intent.action.SENDTO"
I/PackageManager(  627):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  627):   Scheme: "sms"
I/PackageManager(  627): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  627):   Action: "android.intent.action.SENDTO"
I/PackageManager(  627):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  627):   Scheme: "smsto"
I/PackageManager(  627): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/GCoreFlp(  978): No location to return for getLastLocation()
,I/PackageManager(  627): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  627):   Action: "android.intent.action.SENDTO"
I/PackageManager(  627):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  627):   Scheme: "mms"
,D/dalvikvm(  627): GC_EXPLICIT freed 1700K, 11% free 24750K/27748K, paused 3ms+4ms, total 77ms
,I/PackageManager(  627):   Action: "android.intent.action.SENDTO"
I/PackageManager(  627):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  627):   Scheme: "mmsto"
I/PackageManager(  627): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/AndroidRuntime( 2362): Shutting down VM
,D/dalvikvm( 2362): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 1ms
,W/GCoreFlp(  978): No location to return for getLastLocation()
,W/GCoreFlp(  978): No location to return for getLastLocation()
,W/GCoreFlp(  978): No location to return for getLastLocation()
,W/GCoreFlp(  978): No location to return for getLastLocation()
,W/GCoreFlp(  978): No location to return for getLastLocation()
,I/Velvet.VelvetNetworkClient( 1190): Network connection not availble
,D/dalvikvm( 1190): GC_FOR_ALLOC freed 409K, 7% free 17911K/19184K, paused 13ms, total 13ms
,I/dalvikvm-heap( 1190): Grow heap (frag case) to 18.128MB for 640016-byte allocation
,D/dalvikvm( 1040): GC_EXPLICIT freed 1053K, 7% free 26018K/27784K, paused 1ms+3ms, total 25ms
,D/dalvikvm( 1190): GC_FOR_ALLOC freed <1K, 4% free 18536K/19184K, paused 13ms, total 13ms
,I/MicroHotwordRecognitionRunner( 1190): Starting hotword detection.
,D/dalvikvm( 1190): GC_CONCURRENT freed 14K, 4% free 18530K/19184K, paused 1ms+2ms, total 16ms
D/audio_hw_primary(  184): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  184): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  184): Error: ACDB AudProc vol returned = -19
,D/dalvikvm(  978): GC_CONCURRENT freed 359K, 3% free 17897K/18412K, paused 2ms+2ms, total 19ms
,I/SearchController( 1190): #onHotwordDetectorStarted
,E/qdhwcomposer(  181): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  181): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=16 dpy=0 numHwLayers=5
E/qdoverlay(  181): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  181): MdpData failed to play
E/qdoverlay(  181): == Dump MdpData start ==
E/qdoverlay(  181): == Dump OvFD fd=39 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  181): mOvData msmfb_overlay_data id=64
E/qdoverlay(  181): data msmfb_data offset=0 memid=58 id=0 flags=0x0 priv=0
E/qdoverlay(  181): == Dump MdpData end ==
E/qdhwcomposer(  181): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  181): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  181): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
,E/qdhwcomposer(  181): hwc_set_primary: display commit fail!

```
