#### Test 50388019c82294c_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 1983): GC_CONCURRENT freed 228K, 2% free 17560K/17828K, paused 12ms+1ms, total 36ms
,I/iu.UploadsManager( 1289): End new media; added: 0, uploading: 0, time: 66 ms
D/AndroidRuntime( 2205): 
D/AndroidRuntime( 2205): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2205): CheckJNI is OFF
D/dalvikvm( 2205): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2205): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2205): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2205): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2205): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2205): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2205): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2205
D/PermissionCache(  182): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (112 us)
D/dalvikvm(  758): GC_FOR_ALLOC freed 1335K, 10% free 24066K/26692K, paused 38ms, total 38ms
I/dalvikvm-heap(  758): Grow heap (frag case) to 24.353MB for 856096-byte allocation
D/dalvikvm(  758): GC_FOR_ALLOC freed 14K, 10% free 24887K/27532K, paused 42ms, total 42ms
D/dalvikvm(  758): GC_FOR_ALLOC freed 28K, 10% free 24865K/27532K, paused 37ms, total 37ms
I/dalvikvm-heap(  758): Grow heap (frag case) to 25.133MB for 856096-byte allocation
D/dalvikvm(  758): GC_FOR_ALLOC freed <1K, 10% free 25701K/28372K, paused 36ms, total 36ms
D/AndroidRuntime( 2205): Shutting down VM
D/dalvikvm( 2205): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  758): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2225 uid=10115 gids={50115, 3003, 3001, 3002}
I/SearchController( 1175): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1175): mic_close
I/ActivityManager(  758): Killing 1542:com.android.providers.calendar/u0a1 (adj 15): empty #17
I/ActivityManager(  758): Killing 1635:com.android.vending/u0a14 (adj 15): empty #18
V/WebViewChromiumFactoryProvider( 2225): Binding Chromium to main looper Looper (main, tid 1) {42681a58}
I/LibraryLoader( 2225): Expected native library version number "",actual native library version number ""
I/chromium( 2225): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2225): Initializing chromium process, renderers=0
I/MicroHotwordRecognitionRunner( 1175): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1175): Stopping hotword detection.
D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d5da00:true
D/BluetoothAdapter( 2225): 1114205776: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 2225): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2225): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2225): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2225): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2225): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2225): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2225): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2225): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2225): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2225): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2225): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2225): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2225): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2225): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2225): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2225): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2225): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2225): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2225): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2225): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2225): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2225): Enabling debug mode 0
,W/AwContents( 2225): nativeOnDraw failed; clearing to background color.
,D/AlertService( 1681): Beginning updateAlertNotification
,I/ActivityManager(  758): Displayed com.example.hello/.MainActivity: +286ms
I/ActivityManager(  758): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2278 uid=10001 gids={50001, 3003, 1028, 1015}
,I/CalendarProvider2( 2278): Created com.android.providers.calendar.CalendarAlarmManager@4269ba18(com.android.providers.calendar.CalendarProvider2@426936d8)
,D/AlertService( 1681): No fired or scheduled alerts
,D/AlertService( 1681): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1681): No events found starting within 1 week.
,I/chromium( 2225): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 2225): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 2225): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2225): GC_CONCURRENT freed 243K, 2% free 16887K/17160K, paused 3ms+2ms, total 18ms
,D/dalvikvm( 2225): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42685d48
,D/dalvikvm( 2225): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42685d48
,D/jxcore_app_log( 2225): JniHelper::setJavaVM(0x41568f00), pthread_self() = 1979397936
,D/JX-Cordova( 2225): jxcore cordova android initializing
,D/dalvikvm( 2225): GC_CONCURRENT freed 230K, 2% free 17141K/17404K, paused 1ms+2ms, total 10ms
,D/dalvikvm( 2225): GC_CONCURRENT freed 370K, 3% free 17214K/17620K, paused 2ms+1ms, total 10ms
,D/dalvikvm( 2225): WAIT_FOR_CONCURRENT_GC blocked 1ms
W/jxcore-log( 2225): Initializing JXcore engine
,W/jxcore-log( 2225): JXcore engine is ready
,D/dalvikvm( 2225): GC_CONCURRENT freed 300K, 3% free 17380K/17760K, paused 1ms+1ms, total 9ms
,D/dalvikvm( 2225): WAIT_FOR_CONCURRENT_GC blocked 7ms
,W/jxcore-log( 2225): Starting JXcore engine
,W/jxcore-log( 2225): Platform android
W/jxcore-log( 2225): 
,W/jxcore-log( 2225): Process ARCH arm
W/jxcore-log( 2225): 
,I/jxcore-log( 2225): JXcore Cordova bridge is ready!
I/jxcore-log( 2225): 
,W/jxcore-log( 2225): JXcore engine is started
,E/jxcore-log( 2225): >> LGE-Nexus 5
E/jxcore-log( 2225): 
,I/jxcore-log( 2225): Total memory 1945137152
I/jxcore-log( 2225): 
I/jxcore-log( 2225): Free memory 889630720
I/jxcore-log( 2225): 
I/jxcore-log( 2225): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2225): 
,I/jxcore-log( 2225): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2225): 
,I/jxcore-log( 2225): userPath [ 'www' ]
I/jxcore-log( 2225): 
,I/jxcore-log( 2225): Size 1080 1776
I/jxcore-log( 2225): 
,I/jxcore-log( 2225): Screen Brightness 1
I/jxcore-log( 2225): 
,E/jxcore-log( 2225): Dummy Error Log.
E/jxcore-log( 2225): 
,I/CalendarProvider2( 2278): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2278): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  758): Resuming delayed broadcast
I/ActivityManager(  758): Killing 1700:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/ActivityManager(  758): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Delay finish: com.google.android.gm/.GmailReceiver
,D/dalvikvm( 1746): GC_CONCURRENT freed 348K, 3% free 17331K/17712K, paused 3ms+3ms, total 13ms
,I/NotifUtils( 1746): Validating Notification, mapSize: 1 getAttention: true
,I/NotifUtils( 1746): Unseen count doesn't match cursor count.  unseen: 4 cursor count: 3
,I/NotifUtils( 1746): Showing notification with unreadCount of 12 and unseenCount of 3
,D/dalvikvm( 1746): GC_CONCURRENT freed 328K, 3% free 17398K/17760K, paused 2ms+3ms, total 14ms
,I/NotifUtils( 1746): Account: 61035162 vibrate: false
,I/NotifUtils( 1746): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
,I/jxcore-log( 2225): getBuffer is called!!!!
I/jxcore-log( 2225): 
,D/dalvikvm(  758): GC_FOR_ALLOC freed 125K, 9% free 25960K/28372K, paused 41ms, total 42ms
,I/dalvikvm-heap(  758): Grow heap (frag case) to 25.420MB for 36880-byte allocation
,D/dalvikvm(  758): GC_FOR_ALLOC freed 24K, 9% free 25971K/28412K, paused 37ms, total 37ms
,D/dalvikvm(  758): GC_FOR_ALLOC freed <1K, 9% free 25974K/28412K, paused 39ms, total 39ms
,I/dalvikvm-heap(  758): Grow heap (frag case) to 25.434MB for 36880-byte allocation
I/ActivityManager(  758): Resuming delayed broadcast
,D/dalvikvm(  758): GC_FOR_ALLOC freed 13K, 9% free 25997K/28452K, paused 38ms, total 38ms
,D/dalvikvm( 2225): GC_CONCURRENT freed 726K, 5% free 17090K/17908K, paused 7ms+1ms, total 16ms
,D/dalvikvm( 2225): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/ActivityManager(  758): Delay finish: com.google.android.gm/.GmailReceiver
,D/dalvikvm( 2225): GC_CONCURRENT freed 442K, 5% free 17145K/17908K, paused 9ms+2ms, total 21ms
I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
,D/dalvikvm( 1866): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1866): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1866): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 1866): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 1866): VFY: unable to resolve instance field 46
D/dalvikvm( 1866): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 1866): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
D/ConnectivityService(  758): handleInetConditionChange: no active default network - ignore
,D/dalvikvm( 2225): GC_CONCURRENT freed 408K, 5% free 17188K/17908K, paused 2ms+7ms, total 20ms
W/dalvikvm( 1866): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1866): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 1866): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 1866): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 1866): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4295e650
D/dalvikvm( 1866): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4295e650
,D/dalvikvm( 1866): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4295e650, skipping init
,D/dalvikvm( 1866): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4295e650
D/dalvikvm( 1866): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4295e650
,V/JNIHelp ( 1866): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  758): Delay finish: com.google.android.gms/.lockbox.LockboxAlarmReceiver
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/FusedLocationProvider( 1125): location=null
I/ActivityManager(  758): Resuming delayed broadcast
I/ActivityManager(  758): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/dalvikvm( 2225): GC_FOR_ALLOC freed 173K, 4% free 17264K/17908K, paused 9ms, total 9ms
,I/dalvikvm-heap( 2225): Grow heap (frag case) to 17.012MB for 130826-byte allocation
,D/dalvikvm( 2225): GC_FOR_ALLOC freed 0K, 4% free 17392K/18036K, paused 9ms, total 9ms
I/ActivityManager(  758): Resuming delayed broadcast
,D/dalvikvm( 1866): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4295e650
,D/dalvikvm( 1866): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4295e650
D/dalvikvm( 1866): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4295e650
,D/dalvikvm( 1866): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4295e650
,D/dalvikvm( 2225): GC_FOR_ALLOC freed 85K, 5% free 17307K/18036K, paused 9ms, total 9ms
,I/dalvikvm-heap( 2225): Grow heap (frag case) to 17.117MB for 196234-byte allocation
,D/dalvikvm( 1289): GC_CONCURRENT freed 330K, 3% free 18297K/18684K, paused 4ms+6ms, total 28ms
,D/dalvikvm( 2225): GC_FOR_ALLOC freed 0K, 4% free 17499K/18228K, paused 8ms, total 8ms
I/ActivityManager(  758): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,D/dalvikvm( 2225): GC_FOR_ALLOC freed 569K, 7% free 17076K/18228K, paused 9ms, total 10ms
I/ActivityManager(  758): Resuming delayed broadcast
,D/GCM     ( 1125): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ProviderInstaller( 1866): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 1125): GC_CONCURRENT freed 377K, 4% free 18093K/18680K, paused 2ms+2ms, total 17ms
,I/ActivityManager(  758): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2345 uid=10011 gids={50011, 3003}
,I/ActivityManager(  758): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2363 uid=10013 gids={50013, 3003, 3002}
,D/dalvikvm(  183): GC_EXPLICIT freed 42K, 1% free 16697K/16772K, paused 1ms+1ms, total 18ms
,D/dalvikvm(  183): GC_EXPLICIT freed <1K, 1% free 16697K/16772K, paused 1ms+1ms, total 13ms
I/ActivityManager(  758): Delay finish: com.android.musicfx/.Compatibility$Receiver
,D/dalvikvm(  183): GC_EXPLICIT freed <1K, 1% free 16697K/16772K, paused 0ms+2ms, total 11ms
I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2377 uid=10014 gids={50014, 3003, 1028, 1015}
,D/Finsky  ( 2377): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 2377): GC_CONCURRENT freed 253K, 2% free 16907K/17192K, paused 2ms+3ms, total 20ms
,D/Finsky  ( 2377): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 2377): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2377): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Icing.InternalIcingCorporaProvider( 1175): Updating corpora: A: com.example.hello, C: MAYBE
,D/dalvikvm( 2377): GC_CONCURRENT freed 274K, 2% free 17121K/17428K, paused 4ms+5ms, total 27ms
,D/Finsky  ( 2377): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2377): [1] 2.run: Finished loading 1 libraries.
I/ActivityManager(  758): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 2377): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  758): Delaying start of: ServiceRecord{42d12c80 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/dalvikvm( 1289): GC_CONCURRENT freed 436K, 3% free 18295K/18768K, paused 2ms+4ms, total 30ms
,I/ActivityManager(  758): Killing 1729:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,D/dalvikvm( 1175): GC_CONCURRENT freed 840K, 5% free 17788K/18660K, paused 2ms+2ms, total 13ms
,I/Icing.InternalIcingCorporaProvider( 1175): UpdateCorporaTask done [took 294 ms] updated apps [took 294 ms] 
I/ActivityManager(  758): Killing 1080:com.android.printspooler/u0a64 (adj 15): empty #17
,I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  758):   Scheme: "sms"
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "smsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/Launcher( 1043): Deferring update until onResume
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mms"
,I/Launcher( 1043): Deferring update until onResume
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mmsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "sms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "smsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mmsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,V/GmsNetworkLocationProvi(  981): DISABLE
,I/GCoreNlp(  981): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Icing   ( 1289): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/Icing   ( 1289): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1289): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,D/Finsky  ( 2377): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2440 uid=10063 gids={50063, 3003, 3002, 1028, 1015}
,E/dalvikvm( 2440): Could not find class 'android.app.Notification$Action$Builder', referenced from method a.a
,W/dalvikvm( 2440): VFY: unable to resolve new-instance 411 (Landroid/app/Notification$Action$Builder;) in La;
,D/dalvikvm( 2440): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 2440): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve new-instance 574 (Landroid/graphics/drawable/RippleDrawable;) in La;
,D/dalvikvm( 2440): VFY: replacing opcode 0x22 at 0x000b
,E/dalvikvm( 2440): Could not find class 'android.app.Notification$Action$Builder', referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve new-instance 411 (Landroid/app/Notification$Action$Builder;) in La;
,D/dalvikvm( 2440): VFY: replacing opcode 0x22 at 0x0000
,D/dalvikvm( 2440): GC_CONCURRENT freed 189K, 2% free 16934K/17156K, paused 3ms+2ms, total 15ms
W/dalvikvm( 2440): Unable to resolve superclass of Lcw; (794)
,W/dalvikvm( 2440): Link of class 'Lcw;' failed
E/dalvikvm( 2440): Could not find class 'cw', referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve new-instance 3213 (Lcw;) in La;
,D/dalvikvm( 2440): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 2440): Unable to resolve superclass of Lcy; (794)
W/dalvikvm( 2440): Link of class 'Lcy;' failed
E/dalvikvm( 2440): Could not find class 'cy', referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve new-instance 3267 (Lcy;) in La;
D/dalvikvm( 2440): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 2440): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve virtual method 5743: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 2440): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 2440): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve virtual method 6278: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 2440): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 2440): Could not find method android.view.View.getTransitionName, referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve virtual method 6078: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 2440): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 2440): Could not find method android.transition.Transition.getTargetNames, referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve virtual method 5732: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 2440): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 2440): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve interface method 6327: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 2440): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2440): Could not find method android.view.ViewParent.onNestedFling, referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve interface method 6326: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 2440): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2440): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve interface method 6328: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 2440): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 2440): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 2440): Could not find class 'android.app.RemoteInput[]', referenced from method a.a
W/dalvikvm( 2440): VFY: unable to resolve new-array 12979 ([Landroid/app/RemoteInput;) in La;
,D/dalvikvm( 2440): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 2440): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method a.b
,W/dalvikvm( 2440): VFY: unable to resolve virtual method 5743: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2440): VFY: replacing opcode 0x6e at 0x0009
,D/dalvikvm( 2440): DexOpt: unable to opt direct call 0x0c24 at 0x0e in La;.a
,D/dalvikvm( 2440): DexOpt: unable to opt direct call 0x0fba at 0x0e in La;.a
,D/dalvikvm( 2440): DexOpt: unable to opt direct call 0x0c24 at 0x0e in La;.a
W/dalvikvm( 2440): Unable to resolve superclass of Lcw; (794)
W/dalvikvm( 2440): Link of class 'Lcw;' failed
,D/dalvikvm( 2440): DexOpt: unable to opt direct call 0x5b57 at 0x08 in La;.a
W/dalvikvm( 2440): Unable to resolve superclass of Lcy; (794)
W/dalvikvm( 2440): Link of class 'Lcy;' failed
,D/dalvikvm( 2440): DexOpt: unable to opt direct call 0x5c42 at 0x30 in La;.a
,D/dalvikvm( 2440): DexOpt: unable to opt direct call 0x0c7c at 0x13 in La;.a
,D/dalvikvm( 2440): GC_CONCURRENT freed 357K, 3% free 17041K/17432K, paused 1ms+2ms, total 12ms
,D/dalvikvm( 2440): GC_CONCURRENT freed 226K, 2% free 17226K/17484K, paused 1ms+2ms, total 14ms
I/dalvikvm( 2440): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method ebx.a
W/dalvikvm( 2440): VFY: unable to resolve virtual method 3144: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2440): VFY: replacing opcode 0x6e at 0x022f
I/dalvikvm( 2440): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method ebx.a
W/dalvikvm( 2440): VFY: unable to resolve virtual method 3516: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2440): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 2440): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method ebx.c
W/dalvikvm( 2440): VFY: unable to resolve virtual method 3144: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2440): VFY: replacing opcode 0x6e at 0x0200
,D/dalvikvm( 2440): Trying to load lib /data/app-lib/com.google.android.apps.plus-1/libcrashreporterer.so 0x42684aa0
,D/dalvikvm( 2440): Added shared lib /data/app-lib/com.google.android.apps.plus-1/libcrashreporterer.so 0x42684aa0
,I/ActivityManager(  758): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  758): Resuming delayed broadcast
,D/dalvikvm( 2440): GC_CONCURRENT freed 228K, 2% free 17431K/17692K, paused 2ms+1ms, total 11ms
I/ActivityManager(  758): Killing 1774:com.google.android.keep/u0a52 (adj 15): empty #17
,D/PackageBroadcastService( 1289): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1289): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1289): Loading module APK com.google.android.play.games
,I/dalvikvm( 1289): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1289): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1289): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1289): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1289): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1289): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1289): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1289): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/dalvikvm( 1289): GC_CONCURRENT freed 435K, 3% free 18325K/18796K, paused 2ms+1ms, total 16ms
,D/ChimeraCfgMgr( 1289): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1289): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1289): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1289): Submit a task: h
,D/ChimeraCfgMgr( 1289): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/PeopleContactsSync( 1289): CP2 sync disabled
,D/ChimeraCfgMgr( 1289): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/h       ( 1289): Processing package: com.example.hello
I/dalvikvm( 1289): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1289): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1289): VFY: replacing opcode 0x6e at 0x000e
,D/GassUtils( 1289): Found app info for package com.example.hello:18. Hash: 7e411fc8c80adb766ff5747826a81d96c76dd9cb2b76f4f040d3bd27a68f585b
,D/h       ( 1289): Found info for package com.example.hello in db.
I/ActivityManager(  758): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2472 uid=10065 gids={50065, 3003, 1028, 1015}
,W/BaseAppContext( 1289): Using Auth Proxy for data requests.
,W/BaseAppContext( 1289): Using Auth Proxy for data requests.
,W/BaseAppContext( 1289): Using Auth Proxy for data requests.
,W/BaseAppContext( 1289): Using Auth Proxy for data requests.
,W/BaseAppContext( 1289): Using Auth Proxy for data requests.
,W/BaseAppContext( 1289): Using Auth Proxy for data requests.
,D/dalvikvm( 1289): GC_CONCURRENT freed 282K, 2% free 18505K/18820K, paused 2ms+3ms, total 17ms
,W/Quickoffice( 2472): Cleanup of storage: done
,D/com.google.android.apps.docs.quickoffice.X( 2472): Loading recent documents list
,D/Quickoffice( 2472): The number of lines present in  /proc/mount 21
,D/Quickoffice( 2472): Parsing the storagedefinition.xml.
,D/Quickoffice( 2472): # of Storagedefinitions - 35
D/Quickoffice( 2472): The # of storage definitions available - 35
D/Quickoffice( 2472): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2472): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
,D/Quickoffice( 2472): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2472): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2472): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2472): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
,D/Quickoffice( 2472): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2472): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
,D/Quickoffice( 2472): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2472): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
,D/Quickoffice( 2472): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2472): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
,D/Quickoffice( 2472): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2472): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
,D/Quickoffice( 2472): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
,D/Quickoffice( 2472): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2472): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
,D/Quickoffice( 2472): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2472): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
,D/Quickoffice( 2472): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/Quickoffice( 2472): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2472): Build properties are not configured for this storage definition.
,D/Quickoffice( 2472): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
,D/Quickoffice( 2472): The # of mounts identified -  1
,D/dalvikvm( 2472): GC_CONCURRENT freed 187K, 2% free 16930K/17148K, paused 3ms+4ms, total 20ms
,D/com.google.android.apps.docs.quickoffice.X( 2472): Checking validity of 0 items
I/ActivityManager(  758): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2496 uid=10035 gids={50035, 1028, 3003, 1015}
I/ActivityManager(  758): Killing 1796:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,D/ContentResolverUtil( 2472): There are 0 persisted uri permissions.
,D/com.google.android.apps.docs.quickoffice.X( 2472): 0 items were valid
W/ActivityManager(  758): No permission grants found for com.quickoffice.android
,W/Quickoffice( 2472): Could not load clipboard.
,W/Quickoffice( 2472): Could not store clipboard.
,D/dalvikvm(  758): GC_EXPLICIT freed 1188K, 9% free 26053K/28452K, paused 1ms+4ms, total 48ms
,D/dalvikvm( 1289): GC_CONCURRENT freed 323K, 2% free 18689K/19048K, paused 2ms+2ms, total 17ms
,D/ChimeraCfgMgr( 1289): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1289): Module APK com.google.android.play.games already loaded
I/ActivityManager(  758): Waited long enough for: ServiceRecord{42da1118 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,D/dalvikvm( 2496): GC_CONCURRENT freed 271K, 2% free 16865K/17168K, paused 1ms+2ms, total 14ms
,D/dalvikvm( 2496): GC_CONCURRENT freed 269K, 2% free 17063K/17360K, paused 2ms+2ms, total 13ms
I/dalvikvm( 2496): Could not find method android.app.Activity.finishAfterTransition, referenced from method bx.onBackPressed
W/dalvikvm( 2496): VFY: unable to resolve virtual method 1181: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 2496): VFY: replacing opcode 0x6e at 0x0012
I/dalvikvm( 2496): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gkz.a
W/dalvikvm( 2496): VFY: unable to resolve virtual method 1709: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2496): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 2496): Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2496):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2496):   adb logcat -s GAv4
,D/dalvikvm( 2496): GC_CONCURRENT freed 364K, 3% free 17210K/17608K, paused 3ms+1ms, total 13ms
,W/GAv4    ( 2496): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2496): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2496): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/dalvikvm( 2496): GC_CONCURRENT freed 238K, 2% free 17484K/17752K, paused 2ms+4ms, total 19ms
,D/dalvikvm( 2496): WAIT_FOR_CONCURRENT_GC blocked 5ms
,W/AnalyticsTrackerProxyImpl( 2496): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.414.31.35, sample rate 1.0
,I/dalvikvm( 2496): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method ecb.a
,W/dalvikvm( 2496): VFY: unable to resolve static method 2846: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 2496): VFY: replacing opcode 0x71 at 0x0075
,D/dalvikvm( 2496): GC_CONCURRENT freed 477K, 3% free 17520K/18028K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 2496): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2496): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2496): GC_CONCURRENT freed 235K, 2% free 17798K/18064K, paused 3ms+5ms, total 20ms
,D/dalvikvm( 2496): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2496): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/MusicLifecycle( 2121): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@426f7ad0 and intent Intent { act=com.google.android.music.IMPORT_COMPLETE flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,D/WearableService(  981): callingUid 10007, callindPid: 981
,D/MusicLifecycle( 2121): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,D/MusicLifecycle( 2121): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,D/MusicLifecycle( 2121): com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@426f7ad0 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
D/ConnectivityService(  758): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  758): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,D/MusicLifecycle( 2121): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,D/dalvikvm(  981): GC_CONCURRENT freed 365K, 3% free 17897K/18388K, paused 1ms+2ms, total 16ms
,E/GmsUtils( 2121): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/MusicLifecycle( 2121): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
E/GmsUtils( 2121): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/MusicLifecycle( 2121): com.google.android.music.download.TrackDownloadQueueService generated event: Service created
I/ActivityManager(  758): Resuming delayed broadcast
,D/MusicLifecycle( 2121): com.google.android.music.download.cache.TrackCacheService generated event: Service created
,D/MusicLifecycle( 2121): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,D/MusicLifecycle( 2121): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@426f7ad0 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,D/MusicLifecycle( 2121): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,D/MusicLifecycle( 2121): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,I/ActivityManager(  758): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
D/dalvikvm( 2496): GC_CONCURRENT freed 347K, 3% free 17962K/18340K, paused 5ms+2ms, total 41ms
D/dalvikvm( 2496): WAIT_FOR_CONCURRENT_GC blocked 5ms
,E/GmsUtils( 2121): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/dalvikvm( 2121): GC_CONCURRENT freed 265K, 2% free 17707K/18012K, paused 3ms+4ms, total 40ms
,D/dalvikvm( 2121): WAIT_FOR_CONCURRENT_GC blocked 25ms
,E/GmsUtils( 2121): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/MusicLifecycle( 2121): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,D/AlertReceiver( 1681): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
D/dalvikvm( 2496): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2496): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2496): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2496): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2496): VFY: unable to resolve instance field 46
D/dalvikvm( 2496): VFY: replacing opcode 0x54 at 0x005f
D/AlertService( 1681): 0 Action = android.intent.action.PROVIDER_CHANGED
I/MusicLeanback( 2121): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2121): Stop autocaching.
D/dalvikvm( 2496): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2496): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2496): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2496): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2496): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 2496): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427b6660
,I/ActivityManager(  758): Resuming delayed broadcast
D/MusicLifecycle( 2121): com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
D/MusicLifecycle( 2121): com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
D/dalvikvm( 2496): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427b6660
D/dalvikvm( 2496): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427b6660, skipping init
D/dalvikvm( 2496): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x427b6660
D/dalvikvm( 2496): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x427b6660
V/JNIHelp ( 2496): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  758): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,D/dalvikvm( 1681): GC_CONCURRENT freed 293K, 2% free 16796K/17120K, paused 2ms+1ms, total 19ms
I/ActivityManager(  758): Killing 1845:com.google.android.exchange/u0a37 (adj 15): empty #17
,I/ActivityManager(  758): Resuming delayed broadcast
,I/Icing.InternalIcingCorporaProvider( 1175): Updating corpora: A: com.google.android.gms, C: MAYBE
I/ActivityManager(  758): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/dalvikvm(  953): GC_CONCURRENT freed 220K, 2% free 17101K/17348K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 2496): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427b6660
,D/dalvikvm( 2496): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x427b6660
D/dalvikvm( 2496): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x427b6660
D/dalvikvm( 2496): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427b6660
,D/dalvikvm( 2496): GC_CONCURRENT freed 480K, 3% free 17950K/18468K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 2496): WAIT_FOR_CONCURRENT_GC blocked 3ms
,I/ProviderInstaller( 2496): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  758): Waited long enough for: ServiceRecord{42c85358 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,W/Launcher( 1043): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42689bd8 new=com.google.android.velvet.VelvetApplication@42689bd8
,D/dalvikvm( 1289): GC_CONCURRENT freed 506K, 3% free 18752K/19312K, paused 2ms+2ms, total 17ms
I/ActivityManager(  758): Resuming delayed broadcast
I/ActivityManager(  758): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  758): Resuming delayed broadcast
I/ActivityManager(  758): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  758): Resuming delayed broadcast
,D/PackageBroadcastService( 1289): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1289): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1289): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1175): GC_CONCURRENT freed 374K, 5% free 17802K/18660K, paused 1ms+1ms, total 11ms
,I/Icing.InternalIcingCorporaProvider( 1175): UpdateCorporaTask done [took 193 ms] updated apps [took 193 ms] 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  758): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  758): Message: 2
,I/jxcore-log( 2225): ****TEST TOOK:  5036  ms ****
I/jxcore-log( 2225): 
,I/jxcore-log( 2225): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2225): 
D/WifiService(  758): setWifiEnabled: false pid=2225, uid=10115
,D/AndroidRuntime( 2570): 
D/AndroidRuntime( 2570): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2570): CheckJNI is OFF
,D/dalvikvm( 2570): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 2570): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 2570): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2570): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 2570): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 2570): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,D/AndroidRuntime( 2570): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  758): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  758): Killing 2225:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  758): Force removing ActivityRecord{42c8df18 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/WindowState(  758): WIN DEATH: Window{4300b770 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  758): Skipping PackageSetting{427b4828 com.test.thalitest/10108} due to missing metadata
,I/ActivityManager(  758): Force stopping com.example.hello appid=10115 user=0: pkg removed
,W/GeofencerStateMachine(  981): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "sms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/LatinIME:LogUtils(  965): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
,W/Sidekick_LocationOracleImpl( 1175): Best location was null
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "smsto"
,I/Icing   ( 1289): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/Binder  (  965): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  965): java.lang.NullPointerException
W/Binder  (  965): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  965): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  965): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  965): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  758): Got RemoteException sending setActive(false) notification to pid 2225 uid 10115
,D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/Launcher.Workspace( 1043): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1043): 11683562 - stripEmptyScreens()
V/BackupManagerService(  758): removePackageParticipantsLocked: uid=10115 #1
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mms"
,I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/VoicemailCleanupService(  953): Cleaning up data for package: com.example.hello
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mmsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/ActivityManager(  758): Delay finish: com.android.musicfx/.Compatibility$Receiver
,D/dalvikvm(  758): GC_EXPLICIT freed 1839K, 12% free 25258K/28452K, paused 12ms+4ms, total 92ms
,W/GCoreFlp(  981): No location to return for getLastLocation()
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "sms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1003): GC_CONCURRENT freed 346K, 3% free 17052K/17428K, paused 1ms+1ms, total 14ms
,D/AndroidRuntime( 2570): Shutting down VM
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "smsto"
,D/dalvikvm( 2570): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 2ms
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/ActivityManager(  758): Resuming delayed broadcast
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mmsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/GCoreFlp(  981): No location to return for getLastLocation()
,I/Icing.InternalIcingCorporaProvider( 1175): Updating corpora: A: com.example.hello, C: MAYBE
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/Launcher( 1043): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42689bd8 new=com.google.android.velvet.VelvetApplication@42689bd8
,I/ActivityManager(  758): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2608 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/Velvet.VelvetNetworkClient( 1175): Network connection not availble
,D/dalvikvm( 1175): GC_FOR_ALLOC freed 443K, 6% free 17657K/18660K, paused 12ms, total 12ms
,I/dalvikvm-heap( 1175): Grow heap (frag case) to 17.882MB for 640016-byte allocation
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/GCoreFlp(  981): No location to return for getLastLocation()
W/ContextImpl( 2608): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
,D/dalvikvm( 1175): GC_FOR_ALLOC freed 1K, 6% free 18281K/19288K, paused 12ms, total 13ms
,I/MicroHotwordRecognitionRunner( 1175): Starting hotword detection.
I/ActivityManager(  758): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/dalvikvm( 1175): GC_CONCURRENT freed 24K, 6% free 18280K/19288K, paused 3ms+2ms, total 16ms
I/ActivityManager(  758): Resuming delayed broadcast
I/ActivityManager(  758): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  758): Resuming delayed broadcast
D/audio_hw_primary(  185): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  185): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  185): Error: ACDB AudProc vol returned = -19
D/PackageBroadcastService( 1289): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1289): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1289): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1289): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1289): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1289): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1289): Removing dialog suppression flag for package com.example.hello
,E/NetworkScheduler.SchedulerReceiver( 1125): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1125): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/dalvikvm( 1125): GC_CONCURRENT freed 373K, 4% free 18111K/18680K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 1289): GC_CONCURRENT freed 563K, 4% free 18826K/19424K, paused 3ms+3ms, total 28ms
I/ActivityManager(  758): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2639 uid=10034 gids={50034}
,D/gH_CompatibleDatabase( 1289): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1289): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1289): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1289): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/BaseAppContext( 1289): Using Auth Proxy for data requests.
,I/SearchController( 1175): #onHotwordDetectorStarted
,W/BaseAppContext( 1289): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 1289): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1289): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1289): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1289): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1289): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
E/SQLiteLog( 1289): (3850) statement aborts at 29: [DELETE FROM suggestions WHERE app_package_name="com.example.hello"] disk I/O error
D/gH_CompatibleDatabase( 1289): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,W/dalvikvm( 1289): threadid=37: thread exiting with uncaught exception (group=0x4162fba8)
W/FileUtils( 1289): Failed to chmod(/data/data/com.google.android.gms/databases/auto_complete_suggestions.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/AndroidRuntime( 1289): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1289): Process: com.google.android.gms, PID: 1289
E/AndroidRuntime( 1289): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1289): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1289): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1289): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1289): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1289): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1289): 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
E/AndroidRuntime( 1289): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
E/AndroidRuntime( 1289): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1289): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1289): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Documents( 2639): Loading roots for com.android.providers.downloads.documents
,I/GMPM-SVC( 1289): App measurement is starting up
,E/DropBoxManagerService(  758): Can't write: system_app_crash
E/DropBoxManagerService(  758): java.io.FileNotFoundException: /data/system/dropbox/drop73.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  758): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  758): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  758): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  758): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  758): 	... 5 more
I/PeopleContactsSync( 1289): CP2 sync disabled
I/Icing.InternalIcingCorporaProvider( 1175): UpdateCorporaTask done [took 255 ms] updated apps [took 255 ms] 
,E/SQLiteDatabase( 2639): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 2639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 2639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 2639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteDatabase( 2639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 2639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2639): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 2639): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 2639): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 2639): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 2639): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 2639): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2407)
E/SQLiteDatabase( 2639): 	at android.app.ActivityThread.access$1700(ActivityThread.java:135)
E/SQLiteDatabase( 2639): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1272)
E/SQLiteDatabase( 2639): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2639): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2639): 	at android.app.ActivityThread.main(ActivityThread.java:5001)
E/SQLiteDatabase( 2639): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 2639): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 2639): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 2639): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 2639): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 2639): Shutting down VM
,W/dalvikvm( 2639): threadid=1: thread exiting with uncaught exception (group=0x4162fba8)
D/Documents( 2639): Loading roots for com.android.externalstorage.documents
I/ActivityManager(  758): Killing 1983:com.google.android.apps.maps/u0a57 (adj 15): empty #17
E/AndroidRuntime( 2639): FATAL EXCEPTION: main
E/AndroidRuntime( 2639): Process: com.android.documentsui, PID: 2639
E/AndroidRuntime( 2639): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2639): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2414)
E/AndroidRuntime( 2639): 	at android.app.ActivityThread.access$1700(ActivityThread.java:135)
E/AndroidRuntime( 2639): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1272)
E/AndroidRuntime( 2639): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2639): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2639): 	at android.app.ActivityThread.main(ActivityThread.java:5001)
E/AndroidRuntime( 2639): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2639): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2639): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 2639): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 2639): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2639): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 2639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 2639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 2639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 2639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 2639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 2639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 2639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/AndroidRuntime( 2639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 2639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 2639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2639): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 2639): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 2639): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 2639): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 2639): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 2639): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2407)
E/AndroidRuntime( 2639): 	... 10 more
E/SQLiteDatabase( 1289): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1289): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1289): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteDatabase( 1289): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1062)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.d.k(SourceFile:281)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.d.e(SourceFile:724)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.ak.n(SourceFile:1003)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.ak.k(SourceFile:1014)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.ak.b(SourceFile:263)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.al.run(SourceFile:162)
E/SQLiteDatabase( 1289): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1289): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.aj.run(SourceFile:272)
E/DropBoxManagerService(  758): Can't write: system_app_crash
E/DropBoxManagerService(  758): java.io.FileNotFoundException: /data/system/dropbox/drop74.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  758): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  758): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  758): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  758): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  758): 	... 5 more
E/GMPM-SVC( 1289): Opening the database failed, dropping and recreating it
I/ActivityManager(  758): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2665 uid=10006 gids={50006, 1028, 1015, 1023}
I/SearchController( 1175): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1175): mic_close
D/dalvikvm( 1289): GC_CONCURRENT freed 544K, 3% free 18997K/19572K, paused 3ms+2ms, total 27ms
D/dalvikvm( 1289): WAIT_FOR_CONCURRENT_GC blocked 14ms
E/SQLiteDatabase( 1289): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1289): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1289): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteDatabase( 1289): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1289): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.d.k(SourceFile:281)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.d.e(SourceFile:724)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.ak.n(SourceFile:1003)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.ak.k(SourceFile:1014)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.ak.b(SourceFile:263)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.al.run(SourceFile:162)
E/SQLiteDatabase( 1289): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1289): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1289): 	at com.google.android.gms.measurement.internal.aj.run(SourceFile:272)
D/dalvikvm( 1289): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 1289): WAIT_FOR_CONCURRENT_GC blocked 2ms
,I/ActivityManager(  758): Killing 2017:com.google.android.youtube/u0a71 (adj 15): empty #17
D/dalvikvm( 1289): WAIT_FOR_CONCURRENT_GC blocked 14ms
E/GMPM-SVC( 1289): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
W/GMPM-SVC( 1289): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
E/GMPM-SVC( 1289): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
W/GMPM-SVC( 1289): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1058)
E/GMPM-SVC( 1289): Error deleting application data. appId, error: com.example.hello, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1058)
E/SharedPreferencesImpl( 1289): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1289): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1289): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1289): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1289): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1289): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/qdoverlay(  182): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  182): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  182): == Bad OVInfo is:  mdp_overlay z=3 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  182): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  182): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  182): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  182): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  182): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  182): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  182): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  182): Ctrl commit failed set overlay
E/qdhwcomposer(  182): configure: commit fails
E/qdhwcomposer(  182): int qhwc::MDPComp::prepare(hwc_context_t*, hwc_display_contents_1_t*) configure framebuffer failed
E/qdoverlay(  182): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  182): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  182): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  182): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  182): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  182): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  182): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  182): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  182): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  182): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  182): Ctrl commit failed set overlay
E/qdhwcomposer(  182): configure: commit fails
E/qdoverlay(  182): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  182): MdpCtrl close error in unset
I/ActivityManager(  758): Killing 1714:com.google.android.deskclock/u0a33 (adj 15): empty #17
F/ActivityManager(  758): Service ServiceRecord{42faace0 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42cb2fb8 2017:com.google.android.youtube/u0a71} not same as in map: null
E/DropBoxManagerService(  758): Can't write: system_server_wtf
E/DropBoxManagerService(  758): java.io.FileNotFoundException: /data/system/dropbox/drop63.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  758): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  758): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10025)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:9832)
E/DropBoxManagerService(  758): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService(  758): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/DropBoxManagerService(  758): 	at android.util.Log.wtf(Log.java:293)
E/DropBoxManagerService(  758): 	at android.util.Slog.wtf(Slog.java:82)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2081)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:12427)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:3606)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:3751)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1026)
E/DropBoxManagerService(  758): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService(  758): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService(  758): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  758): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  758): 	... 18 more
I/MicroHotwordRecognitionRunner( 1175): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1175): Stopping hotword detection.
,E/qdoverlay(  182): GenericPipe failed to close ctrl
E/qdoverlay(  182): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted

```
