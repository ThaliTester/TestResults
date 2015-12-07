#### Test 50242285e707819_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 1175): Thread[Thread-60,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/GAV2    ( 1175): Thread[Thread-60,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/dalvikvm(  934): GC_CONCURRENT freed 251K, 2% free 17027K/17304K, paused 2ms+1ms, total 13ms
D/AlertReceiver( 1721): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver (has extras) }
D/AlertUtils( 1721): Flushing old alerts from shared prefs table
--------- beginning of /dev/log/system
I/ActivityManager(  638): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=1742 uid=10029 gids={50029}
D/AlertService( 1721): 0 Action = android.intent.action.BOOT_COMPLETED
D/AlertService( 1721): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
V/MediaScanner(  934): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42631648
V/MediaScanner(  934): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42631648
D/AlarmScheduler( 1721): No events found starting within 1 week.
D/CellBroadcastReceiver( 1742): onReceive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 1742): Registering for ServiceState updates
D/CellBroadcastReceiver( 1742): Service state changed! 1 Full: 1 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=true
I/ActivityManager(  638): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=1756 uid=10033 gids={50033, 1028}
V/AlarmClock( 1756): AlarmInitReceiver android.intent.action.BOOT_COMPLETED
V/AlarmClock( 1756): AlarmInitReceiver - Reset timers and clear stopwatch data
I/AlarmClock( 1756): Displaying next alarm time: ''
V/AlarmClock( 1756): AlarmInitReceiver finished
I/ActivityManager(  638): Start proc com.google.android.apps.genie.geniewidget for broadcast com.google.android.apps.genie.geniewidget/.miniwidget.MiniWidgetProvider: pid=1772 uid=10040 gids={50040, 3003, 1028, 1015}
I/System.out( 1772): [INFO:4]: LogSource: Logging disabled
W/Genie   ( 1772): Cache file not found: java.io.FileNotFoundException: /data/data/com.google.android.apps.genie.geniewidget/cache/genie_masfcache: open failed: ENOENT (No such file or directory)
W/Genie   ( 1772): Cache file not found: java.io.FileNotFoundException: /data/data/com.google.android.apps.genie.geniewidget/cache/genie_iconcache: open failed: ENOENT (No such file or directory)
I/Genie   ( 1772): MiniWidgetModel()
V/Genie   ( 1772): onReceive: intent action=android.intent.action.BOOT_COMPLETED
I/Genie   ( 1772): ignoring BOOT_COMPLETE since app has never been started
I/ActivityManager(  638): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=1789 uid=10041 gids={50041, 3003, 1028, 1015}
D/ActivityThread( 1789): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
D/dalvikvm( 1789): GC_CONCURRENT freed 312K, 2% free 16899K/17240K, paused 4ms+2ms, total 32ms
D/dalvikvm( 1789): WAIT_FOR_CONCURRENT_GC blocked 8ms
D/dalvikvm( 1089): GC_CONCURRENT freed 351K, 4% free 18020K/18696K, paused 4ms+3ms, total 21ms
W/GAV2    ( 1789): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/dalvikvm( 1789): GC_CONCURRENT freed 326K, 3% free 17007K/17368K, paused 3ms+1ms, total 15ms
I/ActivityManager(  638): Delay finish: com.google.android.gm/.MailIntentReceiver
D/dalvikvm(  638): GC_EXPLICIT freed 804K, 10% free 23595K/26116K, paused 2ms+4ms, total 58ms
I/ActivityManager(  638): Resuming delayed broadcast
I/ActivityManager(  638): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=1828 uid=10052 gids={50052, 3003, 1028, 1015}
D/dalvikvm( 1789): GC_CONCURRENT freed 292K, 2% free 17149K/17472K, paused 2ms+2ms, total 12ms
I/Gmail   ( 1789): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 1789): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 1789): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 1789): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
I/Gmail   ( 1789): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 1789): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
I/Gmail   ( 1789): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
I/Gmail   ( 1789): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^iim (has extras) }
D/dalvikvm( 1789): GC_CONCURRENT freed 293K, 2% free 17270K/17592K, paused 3ms+1ms, total 15ms
D/dalvikvm( 1828): GC_CONCURRENT freed 244K, 2% free 16900K/17176K, paused 2ms+1ms, total 14ms
I/LauncherIconVisibilityManager(  960): Boot has been completed
I/LauncherIconVisibilityManager(  960): Activity has already been disabled: ComponentInfo{com.google.android.inputmethod.latin/com.android.inputmethod.latin.setup.SetupActivity}
I/ActivityManager(  638): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=1855 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
D/dalvikvm(  181): GC_EXPLICIT freed 41K, 1% free 16699K/16772K, paused 1ms+1ms, total 14ms
D/dalvikvm(  181): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+1ms, total 11ms
I/ActivityManager(  638): Killing 1449:com.google.android.apps.magazines/u0a56 (adj 15): empty #17
D/dalvikvm(  181): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+1ms, total 11ms
I/ActivityManager(  638): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=1869 uid=1001 gids={41001, 3002, 3001, 3003, 2001, 1028, 1015}
D/QcrilMsgTunnelAutoboot( 1869): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
D/QcrilMsgTunnelService( 1869): onCreate method
D/QcrilMsgTunnelIfaceManager( 1869): : Instantiated
V/QcrilMsgTunnelSocket( 1869): Starting QcRilReceiver
D/QcrilMsgTunnelIfaceManager( 1869):  Registered for UNSOL OEM HOOK Responses to deliver external apps
D/QcrilMsgTunnelSocket( 1869): Connecting to socket android.net.LocalSocket@425ed760 impl:android.net.LocalSocketImpl@425ed788 fd:FileDescriptor[42]
I/QcrilMsgTunnelSocket( 1869): Connected to 'qmux_radio/rild_oem0' socket
V/QcrilMsgTunnelSocket( 1869): Before reading offset = 0 remaining = 4 countRead = 0
I/ActivityManager(  638): Start proc com.google.android.email for broadcast com.google.android.email/com.android.email.service.EmailBroadcastReceiver: pid=1884 uid=10036 gids={50036, 3003, 1028, 1015}
D/ActivityThread( 1884): Loading provider com.google.android.email.provider;com.google.android.email.notifier: com.android.email.provider.EmailProvider
,D/ActivityThread( 1884): Loading provider com.google.android.email.provider;com.google.android.email.notifier: com.android.email.provider.EmailProvider
D/ActivityThread( 1884): Loading provider com.google.android.email.provider;com.google.android.email.notifier: com.android.email.provider.EmailProvider
I/ActivityManager(  638): Delay finish: com.google.android.email/com.android.email.service.EmailBroadcastReceiver
D/dalvikvm( 1884): GC_CONCURRENT freed 215K, 2% free 16891K/17136K, paused 4ms+1ms, total 20ms
D/AndroidRuntime( 1904): 
D/AndroidRuntime( 1904): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 1904): CheckJNI is OFF
D/dalvikvm( 1904): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 1904): Added shared lib libjavacore.so 0x0
D/dalvikvm( 1904): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 1904): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 1904): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 1904): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
I/Email   ( 1884): Observing account changes for notifications
W/ActivityManager(  638): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
D/AndroidRuntime( 1904): Calling main entry com.android.commands.am.Am
I/ActivityManager(  638): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 1904
D/PermissionCache(  180): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (118 us)
D/dalvikvm(  638): GC_FOR_ALLOC freed 189K, 10% free 23563K/26116K, paused 35ms, total 35ms
I/dalvikvm-heap(  638): Grow heap (frag case) to 23.859MB for 856096-byte allocation
D/dalvikvm(  638): GC_FOR_ALLOC freed 6K, 10% free 24392K/26956K, paused 39ms, total 39ms
D/dalvikvm(  638): GC_FOR_ALLOC freed <1K, 10% free 24393K/26956K, paused 40ms, total 40ms
I/dalvikvm-heap(  638): Grow heap (frag case) to 24.669MB for 856096-byte allocation
D/dalvikvm(  638): GC_FOR_ALLOC freed 3K, 10% free 25225K/27796K, paused 35ms, total 35ms
W/ActivityManager(  638): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
W/ActivityManager(  638): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
W/ActivityManager(  638): Unable to start service Intent { cmp=com.google.android.email/com.android.email.service.AttachmentDownloadService } U=0: not found
D/AndroidRuntime( 1904): Shutting down VM
D/dalvikvm( 1904): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  638): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=1924 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  638): Delaying start of: ServiceRecord{42d927e8 u0 com.google.android.exchange/com.android.exchange.service.EmailSyncAdapterService}
I/SearchController( 1175): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1175): mic_close
I/ActivityManager(  638): Start proc com.google.android.exchange for service com.google.android.exchange/com.android.exchange.service.EmailSyncAdapterService: pid=1936 uid=10037 gids={50037, 3003, 1028, 1015}
I/ActivityManager(  638): Killing 1426:com.android.settings/1000 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 1924): Binding Chromium to main looper Looper (main, tid 1) {425e38a0}
I/LibraryLoader( 1924): Expected native library version number "",actual native library version number ""
I/chromium( 1924): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 1924): Initializing chromium process, renderers=0
I/ActivityManager(  638): Killing 1389:com.google.android.apps.maps/u0a57 (adj 15): empty #17
D/BluetoothManagerService(  638): Message: 20
D/BluetoothManagerService(  638): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42b81e88:true
D/BluetoothAdapter( 1924): 1113559392: getState() :  mService = null. Returning STATE_OFF
I/MicroHotwordRecognitionRunner( 1175): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1175): Stopping hotword detection.
I/Adreno-EGL( 1924): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 1924): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 1924): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 1924): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 1924): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 1924): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 1924): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 1924): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 1924): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 1924): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 1924): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 1924): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 1924): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 1924): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 1924): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 1924): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 1924): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 1924): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 1924): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 1924): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 1924): CordovaWebView is running on device made by: LGE
I/ActivityManager(  638): Resuming delayed broadcast
I/ActivityManager(  638): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=1980 uid=10051 gids={50051, 3003, 1028, 1015, 3002}
I/ActivityManager(  638): Killing 1067:com.android.printspooler/u0a64 (adj 15): empty #17
,D/OpenGLRenderer( 1924): Enabling debug mode 0
,W/AwContents( 1924): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  638): Displayed com.example.hello/.MainActivity: +303ms
,I/dalvikvm( 1980): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 1980): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 1980): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 1980): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 1980): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 1980): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
,W/dalvikvm( 1980): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 1980): VFY: replacing opcode 0x22 at 0x0037
,W/dalvikvm( 1980): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 1980): Link of class 'Ldqp;' failed
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 1980): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 1980): Link of class 'Ldqp;' failed
I/dalvikvm( 1980): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 1980): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 1980): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 1980): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 1980): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 1980): Link of class 'Ldqp;' failed
,D/dalvikvm( 1980): GC_CONCURRENT freed 206K, 2% free 16878K/17116K, paused 2ms+0ms, total 12ms
,W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 1980): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1980): Link of class 'Ldqp;' failed
I/dalvikvm( 1980): Could not find method dqp.getState, referenced from method g.a
,W/dalvikvm( 1980): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 1980): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
D/dalvikvm( 1980): VFY: replacing opcode 0x1c at 0x0026
W/dalvikvm( 1980): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1980): Link of class 'Ldqp;' failed
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 1980): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 1980): Link of class 'Ldqp;' failed
I/dalvikvm( 1980): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 1980): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 1980): Link of class 'Lax;' failed
E/dalvikvm( 1980): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
D/dalvikvm( 1980): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 1980): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 1980): Link of class 'Laz;' failed
E/dalvikvm( 1980): Could not find class 'az', referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
D/dalvikvm( 1980): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 1980): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 1980): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 1980): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1980): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 1980): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 1980): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 1980): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 1980): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 1980): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
D/dalvikvm( 1980): VFY: replacing opcode 0x72 at 0x0000
W/dalvikvm( 1980): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 1980): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 1980): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
D/dalvikvm( 1980): VFY: replacing opcode 0x23 at 0x0005
I/dalvikvm( 1980): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 1980): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 1980): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
,W/dalvikvm( 1980): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 1980): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 1980): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 1980): VFY: replacing opcode 0x1c at 0x0002
,E/dalvikvm( 1980): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 1980): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 1980): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 1980): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 1980): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1980): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 1980): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 1980): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 1980): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 1980): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 1980): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 1980): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 1980): Link of class 'Lax;' failed
,D/dalvikvm( 1980): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 1980): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 1980): Link of class 'Laz;' failed
,D/dalvikvm( 1980): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 1980): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 1980): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 1980): GC_CONCURRENT freed 297K, 2% free 16978K/17308K, paused 3ms+1ms, total 10ms
,D/dalvikvm( 1980): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x425ed0c8
,D/dalvikvm( 1980): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x425ed0c8
,I/chromium( 1924): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 1924): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/dalvikvm( 1980): GC_CONCURRENT freed 284K, 2% free 17184K/17492K, paused 2ms+2ms, total 11ms
,D/JsMessageQueue( 1924): Set native->JS mode to OnlineEventsBridgeMode
,I/dalvikvm( 1980): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 1980): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x0076
I/Babel_SMS( 1980): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 1980): MmsConfig.loadMmsSettings
I/Babel_SMS( 1980): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 1980): MmsConfig.loadFromDatabase
,D/dalvikvm( 1924): GC_CONCURRENT freed 246K, 2% free 16913K/17192K, paused 2ms+0ms, total 15ms
,D/dalvikvm( 1980): GC_CONCURRENT freed 250K, 2% free 17445K/17724K, paused 3ms+1ms, total 26ms
D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 10ms
,E/Babel_SMS( 1980): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 1980): MmsConfig.loadFromResources
,E/Babel_SMS( 1980): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 1980): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,D/dalvikvm( 1980): GC_CONCURRENT freed 186K, 2% free 17770K/17980K, paused 4ms+1ms, total 14ms
,I/Babel_SMS( 1980): ApnsOta: OTA version -1
,W/dalvikvm( 1980): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 1980): Link of class 'Lfzc;' failed
E/dalvikvm( 1980): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 1980): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 1980): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
D/dalvikvm( 1924): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x425e8058
I/dalvikvm( 1980): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 1980): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
D/dalvikvm( 1980): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 1980): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 1980): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 1980): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 1980): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 1980): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 1980): Link of class 'Lfzc;' failed
D/dalvikvm( 1980): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
I/Babel   ( 1980): deleted: false for 0
D/dalvikvm( 1924): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x425e8058
D/jxcore_app_log( 1924): JniHelper::setJavaVM(0x414cff00), pthread_self() = 1978848456
,D/JX-Cordova( 1924): jxcore cordova android initializing
,D/dalvikvm( 1980): GC_CONCURRENT freed 303K, 2% free 17895K/18204K, paused 2ms+5ms, total 24ms
,W/Settings( 1980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 1924): GC_CONCURRENT freed 263K, 2% free 17139K/17436K, paused 2ms+2ms, total 12ms
,I/Babel_Crash( 1980): startup - clean
I/dalvikvm( 1980): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 1980): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 1980): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 1980): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 1980): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 1980): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 1980): VFY: replacing opcode 0x22 at 0x0071
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 1980): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 1980): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
D/dalvikvm( 1980): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 1980): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 1980): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,V/Babel   ( 1980): babel boot account: thalitester@gmail.com
,I/ActivityManager(  638): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver
I/dalvikvm( 1980): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 1980): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
D/dalvikvm( 1980): VFY: replacing opcode 0x6e at 0x0074
,D/dalvikvm( 1924): GC_CONCURRENT freed 323K, 3% free 17208K/17600K, paused 1ms+1ms, total 12ms
,D/dalvikvm( 1924): WAIT_FOR_CONCURRENT_GC blocked 10ms
W/jxcore-log( 1924): Initializing JXcore engine
,W/jxcore-log( 1924): JXcore engine is ready
,D/dalvikvm( 1980): GC_CONCURRENT freed 266K, 2% free 18056K/18356K, paused 2ms+3ms, total 16ms
,D/dalvikvm( 1924): GC_CONCURRENT freed 257K, 3% free 17341K/17744K, paused 1ms+1ms, total 9ms
,D/dalvikvm( 1924): WAIT_FOR_CONCURRENT_GC blocked 8ms
,W/jxcore-log( 1924): Starting JXcore engine
,I/vclib   ( 1980): onServiceConnected
,W/Babel   ( 1980): Attempted to change video mute state without an active call.
,D/dalvikvm( 1980): GC_CONCURRENT freed 174K, 2% free 18379K/18596K, paused 1ms+1ms, total 13ms
,D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 1980): GC_CONCURRENT freed 187K, 2% free 18736K/18972K, paused 1ms+1ms, total 17ms
D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/ActivityManager(  638): Resuming delayed broadcast
E/dalvikvm( 1980): Could not find class 'android.content.pm.LauncherApps', referenced from method cbk.a
W/dalvikvm( 1980): VFY: unable to resolve check-cast 469 (Landroid/content/pm/LauncherApps;) in Lcbk;
,D/dalvikvm( 1980): VFY: replacing opcode 0x1f at 0x0014
W/jxcore-log( 1924): Platform android
W/jxcore-log( 1924): 
,W/jxcore-log( 1924): Process ARCH arm
W/jxcore-log( 1924): 
I/ActivityManager(  638): Killing 1542:com.google.android.dialer/u0a8 (adj 15): empty #17
,I/jxcore-log( 1924): JXcore Cordova bridge is ready!
I/jxcore-log( 1924): 
,W/jxcore-log( 1924): JXcore engine is started
,D/dalvikvm( 1980): GC_CONCURRENT freed 260K, 2% free 19124K/19448K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 6ms
,E/jxcore-log( 1924): >> LGE-Nexus 5
E/jxcore-log( 1924): 
,I/jxcore-log( 1924): Total memory 1945137152
I/jxcore-log( 1924): 
I/jxcore-log( 1924): Free memory 962027520
I/jxcore-log( 1924): 
I/jxcore-log( 1924): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1924): 
,I/jxcore-log( 1924): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 1924): 
,D/dalvikvm( 1980): GC_FOR_ALLOC freed 372K, 3% free 19233K/19748K, paused 14ms, total 14ms
,I/jxcore-log( 1924): userPath [ 'www' ]
I/jxcore-log( 1924): 
,I/jxcore-log( 1924): Size 1080 1776
I/jxcore-log( 1924): 
,I/jxcore-log( 1924): Screen Brightness 1
I/jxcore-log( 1924): 
,E/jxcore-log( 1924): Dummy Error Log.
E/jxcore-log( 1924): 
,D/dalvikvm( 1980): GC_FOR_ALLOC freed 126K, 4% free 19361K/20004K, paused 16ms, total 16ms
,I/dalvikvm-heap( 1980): Grow heap (frag case) to 19.431MB for 521860-byte allocation
D/dalvikvm( 1301): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1301): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1301): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1980): GC_FOR_ALLOC freed 254K, 5% free 19617K/20516K, paused 33ms, total 33ms
,D/dalvikvm( 1301): GC_FOR_ALLOC freed 294K, 4% free 17835K/18420K, paused 13ms, total 14ms
,D/FileApkUtils( 1301): Spent 43ms computing apk sha1.
,D/FileApkUtils( 1301): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1301): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-2707d05c501ef4bf821813f1789ad0e56682eb5a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1301): Keeping up-to-date module: module-2707d05c501ef4bf821813f1789ad0e56682eb5a
,D/dalvikvm( 1980): GC_FOR_ALLOC freed 628K, 5% free 19547K/20516K, paused 22ms, total 22ms
,D/GmsModuleFndr( 1301): Beginning GMS chimera module scan
,D/dalvikvm( 1980): GC_FOR_ALLOC freed 126K, 5% free 19675K/20516K, paused 19ms, total 19ms
,I/dalvikvm-heap( 1980): Grow heap (frag case) to 19.737MB for 520922-byte allocation
E/dalvikvm( 1301): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1301): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 1301): VFY: replacing opcode 0x1f at 0x000e
,D/dalvikvm( 1980): GC_FOR_ALLOC freed 254K, 6% free 19930K/21028K, paused 20ms, total 20ms
,E/dalvikvm( 1301): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1301): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 1301): VFY: replacing opcode 0x1f at 0x00ef
,W/dalvikvm( 1301): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1301): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1301): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 1301): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1301): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1301): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1301): VFY: replacing opcode 0x62 at 0x0022
D/dalvikvm( 1301): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1301): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1301): VFY: replacing opcode 0x62 at 0x0008
,D/ChimeraCfgMgr( 1301): Beginning module configuration check
D/ChimeraCfgMgr( 1301): Module APKs unchanged, check complete
D/dalvikvm( 1301): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 1301): DexOpt: unable to optimize static field ref 0x00a2 at 0x0c in Lcom/google/android/gms/checkin/d;.a
,D/GCM     ( 1301): COMPAT: Multi user not supported
,D/GCM     ( 1089): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 1301): GC_CONCURRENT freed 395K, 3% free 17934K/18420K, paused 3ms+1ms, total 18ms
,I/GCoreUlr( 1301): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr(  979): DispatchingService.onCreate()
,I/CheckinService( 1301): Checkin interval check for package: unspecified last checkin: 1449470925449 min interval config: 0 actual interval: 28016265
,D/dalvikvm( 1980): GC_FOR_ALLOC freed 624K, 6% free 19860K/21028K, paused 27ms, total 32ms
,I/CheckinService( 1301): Disabling old GoogleServicesFramework version
,W/dalvikvm( 1301): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm(  979): GC_CONCURRENT freed 424K, 3% free 17876K/18404K, paused 1ms+1ms, total 16ms
,W/dalvikvm( 1301): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1980): GC_FOR_ALLOC freed 126K, 5% free 19988K/21028K, paused 27ms, total 27ms
,D/SystemUpdateService( 1301): onCreate
,D/dalvikvm( 1980): GC_FOR_ALLOC freed 254K, 4% free 20242K/21028K, paused 23ms, total 23ms
,I/GCoreUlr(  979): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 1301): GC_FOR_ALLOC freed 265K, 3% free 18039K/18460K, paused 13ms, total 13ms
,I/CheckinService( 1301): Checking schedule, now: 1449498941798 next: 1449513414402
,I/CheckinService( 1301): active receiver: disabled
,D/SystemUpdateService( 1301): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/dalvikvm( 1301): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1301): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 1301): VFY: replacing opcode 0x6e at 0x040d
,V/AuthZen ( 1301): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 1301): Handling event: android.intent.action.BOOT_COMPLETED
,W/Auth    ( 1089): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/SystemUpdateService( 1301): active receiver: enabled
,D/dalvikvm( 1089): GC_EXPLICIT freed 328K, 4% free 18023K/18696K, paused 2ms+3ms, total 24ms
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1089): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.n.a
W/dalvikvm( 1089): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1089): VFY: replacing opcode 0x6e at 0x001c
,D/dalvikvm( 1301): GC_CONCURRENT freed 392K, 3% free 18067K/18492K, paused 3ms+3ms, total 17ms
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1301): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,I/EventLogService( 1301): Aggregate from 1449496544415 (log), 1449496544415 (data)
,W/BaseAppContext( 1301): Using Auth Proxy for data requests.
,I/SystemUpdateService( 1301): Already downloaded, skipping offpeak checks.
,W/dalvikvm( 1301): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1980): GC_CONCURRENT freed 771K, 4% free 20655K/21456K, paused 3ms+6ms, total 49ms
,W/dalvikvm( 1301): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/dalvikvm( 1301): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/SystemUpdateService( 1301): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/dalvikvm( 1301): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1301): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1301): VFY: replacing opcode 0x6e at 0x00bb
,I/dalvikvm( 1089): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.o.a
W/dalvikvm( 1089): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 1089): VFY: replacing opcode 0x6e at 0x001f
D/dalvikvm( 1301): GC_CONCURRENT freed 395K, 3% free 18178K/18608K, paused 2ms+2ms, total 22ms
D/dalvikvm( 1301): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 1301): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 1301): WAIT_FOR_CONCURRENT_GC blocked 8ms
,I/GCoreUlr(  979): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/dalvikvm( 1301): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 1301): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/GCoreUlr(  979): Unbound from all location providers
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1089): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.r.a
W/dalvikvm( 1089): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 1089): VFY: replacing opcode 0x6e at 0x0041
,D/PersistentNotificationBroadcastReceiver( 1089): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/dalvikvm( 1301): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
,W/dalvikvm( 1301): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1301): VFY: replacing opcode 0x6e at 0x002f
I/ActivityManager(  638): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=2060 uid=10057 gids={50057, 3003, 1028, 1015}
,I/AuthZen ( 1301): Fetching signing key...
,I/GCoreUlr(  979): DispatchingService.onDestroy()
,I/GCoreUlr(  979): Stopping handler for UlrDispSvcFast
,I/GCoreUlr(  979): Unbound from all location providers
,I/AuthZen ( 1301): Signing key fetched successfully!
,W/dalvikvm( 1301): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/BaseAppContext( 1301): Using Auth Proxy for data requests.
,D/dalvikvm( 2060): Trying to load lib /data/app-lib/com.google.android.apps.maps-1/libcrashreporterer.so 0x425eb9a0
,D/dalvikvm( 2060): Added shared lib /data/app-lib/com.google.android.apps.maps-1/libcrashreporterer.so 0x425eb9a0
,D/dalvikvm( 2060): Trying to load lib /data/app-lib/com.google.android.apps.maps-1/libgmm-jni.so 0x425eb9a0
,D/dalvikvm( 1980): GC_CONCURRENT freed 393K, 2% free 21586K/22008K, paused 1ms+1ms, total 43ms
,D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 1301): GC_CONCURRENT freed 325K, 2% free 18305K/18660K, paused 3ms+33ms, total 58ms
,D/dalvikvm(  638): GC_EXPLICIT freed 476K, 9% free 25327K/27796K, paused 2ms+5ms, total 57ms
,D/AuthZenTransactionCache( 1301): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1301): Clearing transaction cache
,D/dalvikvm( 2060): GC_CONCURRENT freed 320K, 3% free 16821K/17172K, paused 3ms+4ms, total 39ms
,I/jxcore-log( 1924): getBuffer is called!!!!
I/jxcore-log( 1924): 
,I/DownloadAttempt( 1301): current file is /cache/update.zip
,I/DownloadAttempt( 1301): mSize 2571501 mDownloaded 2571501
I/SystemUpdateService( 1301): status is 0 (complete)
I/SystemUpdateService( 1301): now status is 0 (complete)
,I/SystemUpdateService( 1301): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1301): file has been verified
,I/SystemUpdateService( 1301): OTA package size = 2571501
,I/SystemUpdateService( 1301): showing system update notification
D/dalvikvm( 2060): GC_CONCURRENT freed 247K, 2% free 17088K/17364K, paused 2ms+1ms, total 15ms
,D/dalvikvm( 2060): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2060): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2060): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2060): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/SystemUpdateService( 1301): onDestroy
,D/dalvikvm( 2060): GC_CONCURRENT freed 331K, 3% free 17241K/17600K, paused 3ms+4ms, total 30ms
,D/dalvikvm( 1924): GC_FOR_ALLOC freed 627K, 5% free 16932K/17744K, paused 9ms, total 9ms
,I/ActivityManager(  638): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2089 uid=10071 gids={50071, 3003, 1028, 1015}
,I/ActivityManager(  638): Killing 1592:com.google.android.configupdater/u0a2 (adj 15): empty #17
,D/dalvikvm( 1924): GC_CONCURRENT freed 266K, 4% free 17110K/17744K, paused 2ms+8ms, total 19ms
,I/dalvikvm( 2060): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.d.a
,W/dalvikvm( 2060): VFY: unable to resolve virtual method 311: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2060): VFY: replacing opcode 0x6e at 0x01fb
I/dalvikvm( 2060): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.d.a
W/dalvikvm( 2060): VFY: unable to resolve virtual method 556: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2060): VFY: replacing opcode 0x6e at 0x000f
,D/dalvikvm( 2060): Added shared lib /data/app-lib/com.google.android.apps.maps-1/libgmm-jni.so 0x425eb9a0
I/dalvikvm( 2060): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method com.google.android.apps.gmm.iamhere.ble.o.b
W/dalvikvm( 2060): VFY: unable to resolve virtual method 1434: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 2060): VFY: replacing opcode 0x6e at 0x00a6
,D/dalvikvm( 1980): GC_CONCURRENT freed 1126K, 5% free 22090K/23248K, paused 3ms+2ms, total 60ms
,D/dalvikvm( 1980): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/dalvikvm( 2060): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.d.c
W/dalvikvm( 2060): VFY: unable to resolve virtual method 311: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2060): VFY: replacing opcode 0x6e at 0x01c0
,D/dalvikvm( 2060): GC_CONCURRENT freed 289K, 2% free 17393K/17712K, paused 2ms+3ms, total 14ms
,D/dalvikvm( 1924): GC_CONCURRENT freed 395K, 4% free 17148K/17744K, paused 1ms+1ms, total 10ms
,W/com.google.a.a.b.d.a( 2060): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  638): Message: 20
,D/BluetoothManagerService(  638): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c51e00:true
,D/dalvikvm( 1924): GC_CONCURRENT freed 402K, 3% free 17219K/17744K, paused 2ms+4ms, total 14ms
D/dalvikvm( 1924): GC_FOR_ALLOC freed 37K, 3% free 17238K/17744K, paused 9ms, total 9ms
I/dalvikvm-heap( 1924): Grow heap (frag case) to 16.943MB for 87220-byte allocation
D/dalvikvm( 1924): GC_FOR_ALLOC freed 56K, 4% free 17266K/17832K, paused 9ms, total 9ms
,D/dalvikvm( 1924): GC_FOR_ALLOC freed <1K, 4% free 17266K/17832K, paused 9ms, total 9ms
,I/dalvikvm-heap( 1924): Grow heap (frag case) to 17.012MB for 130826-byte allocation
,D/dalvikvm( 1924): GC_FOR_ALLOC freed 85K, 4% free 17309K/17960K, paused 9ms, total 9ms
,D/dalvikvm( 1924): GC_FOR_ALLOC freed <1K, 4% free 17309K/17960K, paused 10ms, total 10ms
,I/dalvikvm-heap( 1924): Grow heap (frag case) to 17.117MB for 196234-byte allocation
,D/dalvikvm( 1924): GC_FOR_ALLOC freed 127K, 5% free 17373K/18152K, paused 9ms, total 9ms
,D/dalvikvm( 1924): GC_FOR_ALLOC freed 441K, 6% free 17078K/18152K, paused 12ms, total 13ms
E/dalvikvm( 2089): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 2089): VFY: unable to resolve new-instance 404 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 2089): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 2089): Unable to resolve superclass of Lal; (761)
W/dalvikvm( 2089): Link of class 'Lal;' failed
,E/dalvikvm( 2089): Could not find class 'al', referenced from method b.a
W/dalvikvm( 2089): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 2089): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 2089): Unable to resolve superclass of Lan; (761)
,W/dalvikvm( 2089): Link of class 'Lan;' failed
E/dalvikvm( 2089): Could not find class 'an', referenced from method b.a
W/dalvikvm( 2089): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 2089): VFY: replacing opcode 0x22 at 0x002a
,I/dalvikvm( 2089): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 2089): VFY: unable to resolve virtual method 5625: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 2089): Could not find method android.view.View.getTransitionName, referenced from method b.a
,W/dalvikvm( 2089): VFY: unable to resolve virtual method 5440: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x0006
,D/dalvikvm( 2089): GC_CONCURRENT freed 264K, 2% free 16863K/17156K, paused 3ms+3ms, total 20ms
,W/dalvikvm( 2089): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 2089): Could not find class 'android.app.RemoteInput[]', referenced from method b.b
W/dalvikvm( 2089): VFY: unable to resolve new-array 12965 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 2089): VFY: replacing opcode 0x23 at 0x0007
,D/dalvikvm( 2089): DexOpt: unable to opt direct call 0x09cd at 0x0e in Lb;.a
W/dalvikvm( 2089): Unable to resolve superclass of Lal; (761)
,W/dalvikvm( 2089): Link of class 'Lal;' failed
D/dalvikvm( 2089): DexOpt: unable to opt direct call 0x0741 at 0x08 in Lb;.a
W/dalvikvm( 2089): Unable to resolve superclass of Lan; (761)
W/dalvikvm( 2089): Link of class 'Lan;' failed
,D/dalvikvm( 2089): DexOpt: unable to opt direct call 0x08c3 at 0x2c in Lb;.a
,D/dalvikvm( 2089): DexOpt: unable to opt direct call 0x0a11 at 0x0f in Lb;.b
,I/dalvikvm( 2089): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eau.a
W/dalvikvm( 2089): VFY: unable to resolve virtual method 2836: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 2089): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2089): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2089): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 2089): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2089): VFY: unable to resolve instance field 46
,D/dalvikvm( 2089): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2089): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2089): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2089): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2089): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2089): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 2089): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42601ea0
,D/dalvikvm( 2089): GC_CONCURRENT freed 335K, 3% free 17024K/17380K, paused 3ms+5ms, total 22ms
D/dalvikvm( 2089): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42601ea0
,D/dalvikvm( 2089): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42601ea0, skipping init
,D/dalvikvm( 2089): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42601ea0
,I/ActivityManager(  638): Killing 1634:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #17
D/dalvikvm( 2089): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42601ea0
V/JNIHelp ( 2089): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 2089): GC_CONCURRENT freed 285K, 2% free 17209K/17524K, paused 2ms+3ms, total 12ms
,D/dalvikvm( 2089): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42601ea0
,D/dalvikvm( 2089): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42601ea0
D/dalvikvm( 2089): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42601ea0
,D/dalvikvm( 2089): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42601ea0
,I/ProviderInstaller( 2089): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 2089): GC_CONCURRENT freed 184K, 2% free 17416K/17644K, paused 1ms+2ms, total 19ms
,E/YouTube MDX( 2089): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 2089): GC_CONCURRENT freed 331K, 3% free 17596K/17956K, paused 3ms+5ms, total 24ms
,D/dalvikvm( 2089): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 2089): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 2089): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/dalvikvm( 2089): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 2089): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 2089): VFY: replacing opcode 0x71 at 0x0046
,I/dalvikvm( 2089): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 2089): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2089): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 2089): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x0220
,D/dalvikvm( 2089): GC_CONCURRENT freed 250K, 2% free 17857K/18136K, paused 3ms+3ms, total 26ms
,D/dalvikvm( 2089): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 2089): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2089): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2089): DexOpt: --- BEGIN 'ads772557141.jar' (bootstrap=0) ---
,D/dalvikvm( 2137): DexOpt: load 4ms, verify+opt 11ms, 188892 bytes
I/dalvikvm( 2089): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method aex.getActivityBanner
W/dalvikvm( 2089): VFY: unable to resolve virtual method 2807: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2089): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method aex.getActivityBanner
W/dalvikvm( 2089): VFY: unable to resolve virtual method 2808: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2089): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method aex.getApplicationBanner
,W/dalvikvm( 2089): VFY: unable to resolve virtual method 2815: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2089): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method aex.getApplicationBanner
W/dalvikvm( 2089): VFY: unable to resolve virtual method 2816: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2089): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method aex.getLeanbackLaunchIntentForPackage
W/dalvikvm( 2089): VFY: unable to resolve virtual method 2832: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2089): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method aex.getPackageInstaller
W/dalvikvm( 2089): VFY: unable to resolve virtual method 2836: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2089): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method aex.getUserBadgedDrawableForDensity
W/dalvikvm( 2089): VFY: unable to resolve virtual method 2852: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2089): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method aex.getUserBadgedIcon
,W/dalvikvm( 2089): VFY: unable to resolve virtual method 2853: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 2089): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method aex.getUserBadgedLabel
W/dalvikvm( 2089): VFY: unable to resolve virtual method 2854: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 2089): VFY: replacing opcode 0x6e at 0x0002
,W/InstanceID/Rpc( 2089): Found 10007
,D/dalvikvm( 2089): DexOpt: --- END 'ads772557141.jar' (success) ---
,D/dalvikvm( 2089): DEX prep '/data/data/com.google.android.youtube/cache/ads772557141.jar': unzip in 0ms, rewrite 84ms
,D/dalvikvm( 2089): GC_CONCURRENT freed 315K, 2% free 18056K/18400K, paused 3ms+3ms, total 36ms
,D/dalvikvm( 2089): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2089): WAIT_FOR_CONCURRENT_GC blocked 2ms
,I/ActivityManager(  638): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver
,D/dalvikvm( 2089): GC_CONCURRENT freed 280K, 2% free 18174K/18484K, paused 4ms+9ms, total 36ms
,I/ActivityManager(  638): Resuming delayed broadcast
,I/ActivityManager(  638): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.ads.preload.PreloadVideosTransferService$DeviceStateReceiver
,I/ActivityManager(  638): Resuming delayed broadcast
,W/BroadcastQueue(  638): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.google.android.apps.plus/com.google.android.libraries.social.notifications.impl.BootCompletedReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/ActivityManager(  638): Killing 1207:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,D/WearableService(  979): callingUid 10007, callindPid: 979
,E/MDM     (  979): [67] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  638): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,D/dalvikvm( 1301): GC_CONCURRENT freed 374K, 3% free 18382K/18784K, paused 1ms+2ms, total 18ms
,D/LocationInitializer( 1301): Restart initialization of location
,W/GCoreFlp(  979): No location to return for getLastLocation()
,W/FusedLocationProvider( 1089): location=null
,D/GCM     ( 1089): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  638): Resuming delayed broadcast
D/AuthorizationBluetoothService( 1089): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1089): Proximity feature is not enabled.
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  638): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  638): Resuming delayed broadcast
I/ActivityManager(  638): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,D/dalvikvm( 1089): GC_CONCURRENT freed 359K, 4% free 18076K/18696K, paused 1ms+1ms, total 19ms
,V/GmsCoreStatsServiceLauncher( 1301): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  638): Resuming delayed broadcast
,E/MDM     (  979): [68] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1301): Restart initialization of location
I/ActivityManager(  638): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp(  979): No location to return for getLastLocation()
,W/FusedLocationProvider( 1089): location=null
,I/ActivityManager(  638): Resuming delayed broadcast
D/GCM     ( 1089): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1089): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1089): Proximity feature is not enabled.
,V/GLSActivity( 1089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  638): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  638): Resuming delayed broadcast
,V/GmsCoreStatsServiceLauncher( 1301): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  638): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  638): Resuming delayed broadcast
,I/ActivityManager(  638): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2185 uid=10011 gids={50011, 3003}
,I/ActivityManager(  638): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  638): Resuming delayed broadcast
,I/ActivityManager(  638): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  638): Resuming delayed broadcast
,I/ActivityManager(  638): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2200 uid=10013 gids={50013, 3003, 3002}
,I/ActivityManager(  638): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  638): Resuming delayed broadcast
,I/Icing.InternalIcingCorporaProvider( 1175): Updating corpora: A: com.example.hello, C: MAYBE
I/ActivityManager(  638): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/dalvikvm( 1301): GC_CONCURRENT freed 555K, 4% free 18318K/18912K, paused 3ms+1ms, total 17ms
,D/dalvikvm( 1175): GC_CONCURRENT freed 884K, 5% free 17631K/18544K, paused 2ms+1ms, total 16ms
,I/Icing.InternalIcingCorporaProvider( 1175): UpdateCorporaTask done [took 227 ms] updated apps [took 227 ms] 
I/ActivityManager(  638): Killing 1564:com.android.providers.calendar/u0a1 (adj 15): empty #17
,I/GAV2    ( 1175): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1301): Google Analytics 8.3.01 is starting up.
,I/GAV2    ( 1789): Thread[GAThread,5,main]: No campaign data found.
,I/Icing   ( 1301): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/Icing   ( 1301): Loaded CLD2 Version V2.0 - 20141016
,D/dalvikvm( 1301): GC_CONCURRENT freed 386K, 3% free 18349K/18912K, paused 3ms+4ms, total 21ms
,D/dalvikvm( 1175): GC_CONCURRENT freed 353K, 5% free 17664K/18544K, paused 2ms+3ms, total 17ms
,I/Icing   ( 1301): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/ActivityManager(  638): Resuming delayed broadcast
,I/ActivityManager(  638): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2230 uid=10035 gids={50035, 1028, 3003, 1015}
,I/dalvikvm( 2230): Could not find method android.app.Activity.finishAfterTransition, referenced from method bx.onBackPressed
W/dalvikvm( 2230): VFY: unable to resolve virtual method 1145: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 2230): VFY: replacing opcode 0x6e at 0x0012
,D/dalvikvm( 2230): GC_CONCURRENT freed 318K, 3% free 16874K/17224K, paused 1ms+1ms, total 13ms
,D/dalvikvm( 2230): GC_CONCURRENT freed 334K, 3% free 17041K/17404K, paused 2ms+1ms, total 11ms
,I/dalvikvm( 2230): Could not find method android.content.Context.checkSelfPermission, referenced from method arg.a
W/dalvikvm( 2230): VFY: unable to resolve virtual method 1515: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 2230): VFY: replacing opcode 0x6e at 0x001b
,I/dalvikvm( 2230): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gwe.a
W/dalvikvm( 2230): VFY: unable to resolve virtual method 1697: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2230): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 2230): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2230):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2230):   adb logcat -s GAv4
,D/dalvikvm( 2230): GC_CONCURRENT freed 296K, 2% free 17280K/17584K, paused 2ms+3ms, total 16ms
,W/GAv4    ( 2230): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2230): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/dalvikvm( 2230): GC_CONCURRENT freed 288K, 2% free 17515K/17808K, paused 2ms+1ms, total 13ms
,W/GAv4    ( 2230): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 2230): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.453.15.35, sample rate 1.0
I/dalvikvm( 2230): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method efh.a
W/dalvikvm( 2230): VFY: unable to resolve static method 2872: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 2230): VFY: replacing opcode 0x71 at 0x0075
,D/dalvikvm( 2230): GC_CONCURRENT freed 361K, 3% free 17665K/18044K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 2230): WAIT_FOR_CONCURRENT_GC blocked 1ms
,I/ActivityManager(  638): Killing 1742:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,D/dalvikvm( 2230): GC_CONCURRENT freed 358K, 3% free 17821K/18208K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 2230): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2230): WAIT_FOR_CONCURRENT_GC blocked 6ms
I/ActivityManager(  638): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 1301): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/ActivityManager(  638): Resuming delayed broadcast
,D/ChimeraCfgMgr( 1301): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1301): Loading module APK com.google.android.play.games
,I/PeopleContactsSync( 1301): CP2 sync disabled
I/dalvikvm( 1301): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1301): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1301): VFY: replacing opcode 0x6e at 0x000e
,D/dalvikvm( 2230): GC_CONCURRENT freed 303K, 2% free 17982K/18324K, paused 5ms+1ms, total 19ms
,D/dalvikvm( 2230): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2230): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2230): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2230): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2230): VFY: unable to resolve instance field 46
,D/dalvikvm( 2230): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2230): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2230): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2230): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2230): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2230): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 2230): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426c2db8
D/dalvikvm( 2230): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426c2db8
,D/dalvikvm( 2230): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426c2db8, skipping init
,D/dalvikvm( 2230): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x426c2db8
D/dalvikvm( 2230): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x426c2db8
,V/JNIHelp ( 2230): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/dalvikvm( 1301): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1301): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1301): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1301): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1301): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1301): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1301): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1301): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/dalvikvm( 1089): GC_CONCURRENT freed 371K, 4% free 18111K/18696K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 2230): GC_CONCURRENT freed 465K, 3% free 17942K/18440K, paused 2ms+4ms, total 19ms
,D/dalvikvm( 2230): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426c2db8
D/dalvikvm( 2230): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x426c2db8
,D/dalvikvm( 2230): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x426c2db8
,D/dalvikvm( 2230): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x426c2db8
,D/dalvikvm( 2230): GC_FOR_ALLOC freed 107K, 3% free 18050K/18440K, paused 13ms, total 13ms
,D/ChimeraCfgMgr( 1301): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1301): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1301): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1301): Submit a task: h
,D/ChimeraCfgMgr( 1301): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1301): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/h       ( 1301): Processing package: com.example.hello
,I/ActivityManager(  638): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2286 uid=10065 gids={50065, 3003, 1028, 1015}
,D/GassUtils( 1301): Found app info for package com.example.hello:18. Hash: 7e411fc8c80adb766ff5747826a81d96c76dd9cb2b76f4f040d3bd27a68f585b
,D/h       ( 1301): Found info for package com.example.hello in db.
,D/dalvikvm(  181): GC_EXPLICIT freed 42K, 1% free 16699K/16772K, paused 1ms+2ms, total 14ms
,I/ProviderInstaller( 2230): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 1301): GC_CONCURRENT freed 329K, 3% free 18461K/18912K, paused 2ms+2ms, total 23ms
W/BaseAppContext( 1301): Using Auth Proxy for data requests.
,W/BaseAppContext( 1301): Using Auth Proxy for data requests.
,D/dalvikvm(  181): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+1ms, total 12ms
,D/dalvikvm(  181): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+2ms, total 12ms
,W/BaseAppContext( 1301): Using Auth Proxy for data requests.
,D/dalvikvm( 1089): null clazz in OP_INSTANCE_OF, single-stepping
,W/BaseAppContext( 1301): Using Auth Proxy for data requests.
,W/BaseAppContext( 1301): Using Auth Proxy for data requests.
,W/BaseAppContext( 1301): Using Auth Proxy for data requests.
,W/Quickoffice( 2286): Cleanup of storage: done
,D/com.google.android.apps.docs.quickoffice.X( 2286): Loading recent documents list
,D/Quickoffice( 2286): The number of lines present in  /proc/mount 21
,D/Quickoffice( 2286): Parsing the storagedefinition.xml.
,D/Quickoffice( 2286): # of Storagedefinitions - 35
D/Quickoffice( 2286): The # of storage definitions available - 35
,D/Quickoffice( 2286): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2286): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
,D/Quickoffice( 2286): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
,D/Quickoffice( 2286): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2286): Processing mountline proc /proc proc rw,relatime 0 0
,D/Quickoffice( 2286): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
,D/Quickoffice( 2286): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2286): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
,D/Quickoffice( 2286): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
,D/Quickoffice( 2286): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2286): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
,D/Quickoffice( 2286): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
,D/Quickoffice( 2286): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
,D/Quickoffice( 2286): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
,D/Quickoffice( 2286): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
,D/Quickoffice( 2286): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
,D/Quickoffice( 2286): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
,D/Quickoffice( 2286): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/dalvikvm( 2286): GC_CONCURRENT freed 197K, 2% free 16913K/17140K, paused 2ms+1ms, total 14ms
D/Quickoffice( 2286): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2286): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/Quickoffice( 2286): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2286): Build properties are not configured for this storage definition.
,D/Quickoffice( 2286): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
,D/Quickoffice( 2286): The # of mounts identified -  1
,D/com.google.android.apps.docs.quickoffice.X( 2286): Checking validity of 0 items
I/ActivityManager(  638): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2304 uid=10063 gids={50063, 3003, 3002, 1028, 1015}
I/ActivityManager(  638): Killing 1756:com.google.android.deskclock/u0a33 (adj 15): empty #17
W/ActivityManager(  638): No permission grants found for com.quickoffice.android
,D/ContentResolverUtil( 2286): There are 0 persisted uri permissions.
,D/com.google.android.apps.docs.quickoffice.X( 2286): 0 items were valid
,D/dalvikvm( 1301): GC_CONCURRENT freed 267K, 2% free 18693K/18984K, paused 3ms+5ms, total 25ms
,W/Quickoffice( 2286): Could not load clipboard.
,W/Quickoffice( 2286): Could not store clipboard.
,I/ActivityManager(  638): Killing 1772:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,D/ChimeraCfgMgr( 1301): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1301): Module APK com.google.android.play.games already loaded
,E/dalvikvm( 2304): Could not find class 'android.app.Notification$Action$Builder', referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Ltp;
,D/dalvikvm( 2304): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 2304): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve new-instance 575 (Landroid/graphics/drawable/RippleDrawable;) in Ltp;
,D/dalvikvm( 2304): VFY: replacing opcode 0x22 at 0x000b
,E/dalvikvm( 2304): Could not find class 'android.app.Notification$Action$Builder', referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Ltp;
,D/dalvikvm( 2304): VFY: replacing opcode 0x22 at 0x0000
,D/dalvikvm( 2304): GC_CONCURRENT freed 201K, 2% free 16942K/17172K, paused 2ms+3ms, total 21ms
W/dalvikvm( 2304): Unable to resolve superclass of Lcb; (795)
W/dalvikvm( 2304): Link of class 'Lcb;' failed
E/dalvikvm( 2304): Could not find class 'cb', referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve new-instance 2076 (Lcb;) in Ltp;
,D/dalvikvm( 2304): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 2304): Unable to resolve superclass of Lcd; (795)
,W/dalvikvm( 2304): Link of class 'Lcd;' failed
E/dalvikvm( 2304): Could not find class 'cd', referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve new-instance 2130 (Lcd;) in Ltp;
D/dalvikvm( 2304): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 2304): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve virtual method 5252: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2304): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 2304): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve virtual method 5837: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 2304): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 2304): Could not find method android.view.View.getTransitionName, referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve virtual method 5588: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 2304): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 2304): Could not find method android.transition.Transition.getTargetNames, referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve virtual method 5241: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 2304): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 2304): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve interface method 5907: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 2304): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2304): Could not find method android.view.ViewParent.onNestedFling, referenced from method tp.a
,W/dalvikvm( 2304): VFY: unable to resolve interface method 5906: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 2304): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2304): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve interface method 5911: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 2304): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 2304): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 2304): Could not find class 'android.app.RemoteInput[]', referenced from method tp.a
W/dalvikvm( 2304): VFY: unable to resolve new-array 13298 ([Landroid/app/RemoteInput;) in Ltp;
,D/dalvikvm( 2304): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 2304): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method tp.b
,W/dalvikvm( 2304): VFY: unable to resolve virtual method 5252: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2304): VFY: replacing opcode 0x6e at 0x0009
,D/dalvikvm( 2304): DexOpt: unable to opt direct call 0x09ef at 0x0e in Ltp;.a
,D/dalvikvm( 2304): DexOpt: unable to opt direct call 0x0d75 at 0x0e in Ltp;.a
,D/dalvikvm( 2304): DexOpt: unable to opt direct call 0x09ef at 0x0e in Ltp;.a
W/dalvikvm( 2304): Unable to resolve superclass of Lcb; (795)
W/dalvikvm( 2304): Link of class 'Lcb;' failed
,D/dalvikvm( 2304): DexOpt: unable to opt direct call 0x314d at 0x08 in Ltp;.a
W/dalvikvm( 2304): Unable to resolve superclass of Lcd; (795)
W/dalvikvm( 2304): Link of class 'Lcd;' failed
D/dalvikvm( 2304): DexOpt: unable to opt direct call 0x3301 at 0x30 in Ltp;.a
,D/dalvikvm( 2304): DexOpt: unable to opt direct call 0x0a47 at 0x13 in Ltp;.a
,D/dalvikvm( 2304): GC_CONCURRENT freed 356K, 3% free 17047K/17436K, paused 1ms+1ms, total 9ms
,D/dalvikvm(  638): GC_EXPLICIT freed 634K, 9% free 25413K/27684K, paused 1ms+6ms, total 69ms
,D/dalvikvm( 2304): GC_CONCURRENT freed 225K, 2% free 17228K/17484K, paused 2ms+2ms, total 13ms
,I/dalvikvm( 2304): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eds.a
,W/dalvikvm( 2304): VFY: unable to resolve virtual method 2579: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2304): VFY: replacing opcode 0x6e at 0x023c
I/dalvikvm( 2304): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eds.a
W/dalvikvm( 2304): VFY: unable to resolve virtual method 2951: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2304): VFY: replacing opcode 0x6e at 0x000f
,I/dalvikvm( 2304): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eds.c
W/dalvikvm( 2304): VFY: unable to resolve virtual method 2579: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2304): VFY: replacing opcode 0x6e at 0x0207
,D/dalvikvm( 2304): GC_CONCURRENT freed 284K, 2% free 17387K/17700K, paused 2ms+2ms, total 11ms
,D/dalvikvm( 2304): Trying to load lib /data/app-lib/com.google.android.apps.plus-2/libcrashreporterer.so 0x425eab68
,D/dalvikvm( 2304): Added shared lib /data/app-lib/com.google.android.apps.plus-2/libcrashreporterer.so 0x425eab68
,I/ActivityManager(  638): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  638): Resuming delayed broadcast
,I/ActivityManager(  638): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  638): Resuming delayed broadcast
,I/ActivityManager(  638): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2335 uid=10058 gids={50058, 3003, 1028, 1015}
,I/ActivityManager(  638): Killing 1789:com.google.android.gm/u0a41 (adj 15): empty #17
,I/MultiDex( 2335): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 2335): install
,I/MultiDex( 2335): MultiDexExtractor.load(/data/app/com.google.android.music-1.apk, false)
,I/MultiDex( 2335): loading existing secondary dex files
,I/MultiDex( 2335): load found 1 secondary dex files
,I/MultiDex( 2335): install done
,D/dalvikvm( 2335): GC_CONCURRENT freed 208K, 2% free 16891K/17128K, paused 4ms+5ms, total 20ms
,I/BaseStore( 2335): Store database version: 123
,I/dalvikvm( 2335): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zza
,W/dalvikvm( 2335): VFY: unable to resolve virtual method 613: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2335): VFY: replacing opcode 0x6e at 0x00c2
,I/dalvikvm( 2335): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzk
W/dalvikvm( 2335): VFY: unable to resolve virtual method 981: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2335): VFY: replacing opcode 0x6e at 0x000b
,D/dalvikvm( 2335): GC_CONCURRENT freed 344K, 3% free 17059K/17432K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 2335): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/BluetoothManagerService(  638): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  638): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  638): Message: 2
,I/jxcore-log( 1924): ****TEST TOOK:  5020  ms ****
I/jxcore-log( 1924): 
,D/WifiService(  638): setWifiEnabled: false pid=1924, uid=10115
I/jxcore-log( 1924): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 1924): 
,D/MusicLifecycle( 2335): com.google.android.music.MusicApplication generated event: Application created
,D/dalvikvm( 2335): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 2335): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2335): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2335): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2335): VFY: unable to resolve instance field 46
,D/dalvikvm( 2335): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2335): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2335): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2335): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2335): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2335): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 2335): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426378a0
D/dalvikvm( 2335): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426378a0
,D/dalvikvm( 2335): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426378a0, skipping init
D/dalvikvm( 2335): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x426378a0
D/dalvikvm( 2335): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x426378a0
,V/JNIHelp ( 2335): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 2335): GC_CONCURRENT freed 351K, 3% free 17191K/17572K, paused 1ms+1ms, total 11ms
,D/dalvikvm( 2335): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x426378a0
,D/dalvikvm( 2335): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x426378a0
D/dalvikvm( 2335): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x426378a0
,D/dalvikvm( 2335): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x426378a0
,I/ProviderInstaller( 2335): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 2335): GMSCore installation verified
,D/dalvikvm( 2335): GC_CONCURRENT freed 191K, 2% free 17418K/17692K, paused 2ms+8ms, total 19ms
,I/BaseStore( 2335): ConfigStore database version: 1
,I/MediaRouter( 2335): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, deviceType=0, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/MusicLifecycle( 2335): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4264aee0 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,I/ActivityManager(  638): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/MusicLifecycle( 2335): com.google.android.music.net.NetworkMonitor generated event: Service created
,D/MusicLifecycle( 2335): com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
,D/MusicLifecycle( 2335): com.google.android.music.download.cache.StorageMigrationService generated event: Service created
,D/MusicLifecycle( 2335): com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
,D/AndroidRuntime( 2356): 
D/AndroidRuntime( 2356): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2356): CheckJNI is OFF
,D/MusicLifecycle( 2335): com.google.android.music.download.ArtDownloadQueueService generated event: Service created
,I/ActivityManager(  638): Resuming delayed broadcast
D/dalvikvm( 2356): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2356): Added shared lib libjavacore.so 0x0
I/GHttpClientFactory( 2335): Using our fixed implementation of GMSCore's GoogleHttpClient
W/dalvikvm( 2335): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2335): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/dalvikvm( 2356): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2356): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2356): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/dalvikvm( 2335): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.GoogleURLConnectionFactory.openConnection
W/dalvikvm( 2335): VFY: unable to resolve virtual method 1704: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 2335): VFY: replacing opcode 0x6e at 0x00a0
I/GoogleURLConnFactory( 2335): Using platform SSLCertificateSocketFactory
,D/MusicLifecycle( 2335): com.google.android.music.download.cache.ArtCacheService generated event: Service created
,D/MusicLifecycle( 2335): com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
,D/MusicLifecycle( 2335): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4264aee0 and intent Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,D/dalvikvm( 2356): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,D/dalvikvm( 2335): GC_CONCURRENT freed 319K, 2% free 17502K/17852K, paused 2ms+1ms, total 13ms
,D/MusicLifecycle( 2335): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@4264aee0 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,I/ActivityManager(  638): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/MusicLifecycle( 2335): com.google.android.music.store.MediaStoreImportService generated event: Service created
,D/MusicLifecycle( 2335): com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
I/ActivityManager(  638): Resuming delayed broadcast
I/ActivityManager(  638): Killing 1828:com.google.android.keep/u0a52 (adj 15): empty #17
,D/AlertReceiver( 1721): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
,D/AlertService( 1721): 0 Action = android.intent.action.PROVIDER_CHANGED
I/ActivityManager(  638): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,D/AndroidRuntime( 2356): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  638): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
I/ActivityManager(  638): Killing 1924:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  638): Force removing ActivityRecord{427054e0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/WindowState(  638): WIN DEATH: Window{42cf86d8 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  638): Skipping PackageSetting{426c62c8 com.test.thalitest/10108} due to missing metadata
,I/ActivityManager(  638): Force stopping com.example.hello appid=10115 user=0: pkg removed
,W/GeofencerStateMachine(  979): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  638):   Action: "android.intent.action.SENDTO"
I/PackageManager(  638):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  638):   Scheme: "sms"
I/PackageManager(  638): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/InputReader(  638): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  638):   Action: "android.intent.action.SENDTO"
I/PackageManager(  638):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  638):   Scheme: "smsto"
,W/Sidekick_LocationOracleImpl( 1175): Best location was null
I/PackageManager(  638): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/BackupManagerService(  638): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  638): removePackageParticipantsLocked: uid=10115 #1
,W/InputMethodManagerService(  638): Got RemoteException sending setActive(false) notification to pid 1924 uid 10115
I/PackageManager(  638):   Action: "android.intent.action.SENDTO"
I/PackageManager(  638):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  638):   Scheme: "mms"
,D/Launcher.Workspace( 1044): 11683562 - stripEmptyScreens()
,W/Binder  (  960): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  960): java.lang.NullPointerException
W/Binder  (  960): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  960): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  960): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  960): 	at dalvik.system.NativeStart.run(Native Method)
,D/Launcher.Workspace( 1044): 11683562 - stripEmptyScreens()
I/PackageManager(  638): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  960): GC_CONCURRENT freed 281K, 2% free 17006K/17316K, paused 5ms+2ms, total 14ms
,I/LatinIME:LogUtils(  960): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
,I/PackageManager(  638):   Action: "android.intent.action.SENDTO"
I/PackageManager(  638):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  638):   Scheme: "mmsto"
I/PackageManager(  638): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  638): GC_EXPLICIT freed 1654K, 11% free 24655K/27684K, paused 1ms+4ms, total 119ms
,I/PackageManager(  638):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  638):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  638):   Scheme: "sms"
I/PackageManager(  638): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/AndroidRuntime( 2356): Shutting down VM
,D/dalvikvm( 2356): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 1ms
,W/GCoreFlp(  979): No location to return for getLastLocation()
I/PackageManager(  638):   Action: "android.intent.action.SENDTO"
I/PackageManager(  638):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  638):   Scheme: "smsto"
I/PackageManager(  638): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1175): GC_FOR_ALLOC freed 55K, 5% free 17661K/18544K, paused 15ms, total 15ms
,I/dalvikvm-heap( 1175): Grow heap (frag case) to 17.883MB for 640016-byte allocation
,I/PackageManager(  638):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  638):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  638):   Scheme: "mms"
,D/dalvikvm( 1175): GC_FOR_ALLOC freed 1K, 5% free 18285K/19172K, paused 12ms, total 12ms
,I/PackageManager(  638): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/MicroHotwordRecognitionRunner( 1175): Starting hotword detection.
,D/dalvikvm( 1175): GC_CONCURRENT freed 2K, 5% free 18288K/19172K, paused 2ms+1ms, total 11ms
,I/PackageManager(  638):   Action: "android.intent.action.SENDTO"
I/PackageManager(  638):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  638):   Scheme: "mmsto"
I/PackageManager(  638): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/audio_hw_primary(  183): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
,D/        (  183): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  183): Error: ACDB AudProc vol returned = -19
,W/GCoreFlp(  979): No location to return for getLastLocation()
,W/GCoreFlp(  979): No location to return for getLastLocation()
,W/GCoreFlp(  979): No location to return for getLastLocation()
,W/GCoreFlp(  979): No location to return for getLastLocation()
,W/GCoreFlp(  979): No location to return for getLastLocation()
,D/dalvikvm( 1044): GC_EXPLICIT freed 1435K, 7% free 26119K/27880K, paused 2ms+2ms, total 24ms
,I/SearchController( 1175): #onHotwordDetectorStarted

```
