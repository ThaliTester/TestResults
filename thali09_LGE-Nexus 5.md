#### Test 55634150e857e16_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/iu.UploadsManager( 1331): End new media; added: 0, uploading: 0, time: 63 ms
,D/AndroidRuntime( 2310): 
D/AndroidRuntime( 2310): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2310): CheckJNI is OFF
D/dalvikvm( 2310): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2310): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2310): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2310): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2310): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2310): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2310): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2310
D/PermissionCache(  184): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (100 us)
D/dalvikvm(  760): GC_FOR_ALLOC freed 1335K, 11% free 24157K/27004K, paused 49ms, total 49ms
I/dalvikvm-heap(  760): Grow heap (frag case) to 24.440MB for 856096-byte allocation
D/dalvikvm(  760): GC_FOR_ALLOC freed 6K, 11% free 24987K/27844K, paused 37ms, total 37ms
D/dalvikvm(  760): GC_FOR_ALLOC freed 9K, 11% free 24984K/27844K, paused 40ms, total 43ms
I/dalvikvm-heap(  760): Grow heap (frag case) to 25.247MB for 856096-byte allocation
D/dalvikvm(  760): GC_FOR_ALLOC freed 40K, 11% free 25779K/28684K, paused 47ms, total 47ms
D/AndroidRuntime( 2310): Shutting down VM
D/dalvikvm( 2310): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  760): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2330 uid=10116 gids={50116, 3003, 3001, 3002}
I/SearchController( 1206): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1206): mic_close
I/ActivityManager(  760): Killing 1706:com.android.vending/u0a14 (adj 15): empty #17
I/ActivityManager(  760): Killing 1206:com.google.android.googlequicksearchbox:search/u0a19 (adj 15): empty #18
V/WebViewChromiumFactoryProvider( 2330): Binding Chromium to main looper Looper (main, tid 1) {42841a70}
I/LibraryLoader( 2330): Expected native library version number "",actual native library version number ""
I/chromium( 2330): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2330): Initializing chromium process, renderers=0
D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42f057f8:true
I/Adreno-EGL( 2330): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2330): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2330): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2330): VFY: unable to resolve virtual method 170: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2330): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2330): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2330): VFY: unable to resolve virtual method 165: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 2330): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 2330): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2330): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2330): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2330): VFY: unable to resolve virtual method 223: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 2330): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 2330): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2330): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2330): VFY: unable to resolve virtual method 181: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2330): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2330): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2330): VFY: unable to resolve virtual method 186: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 2330): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 2330): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2330): Enabling debug mode 0
,W/AwContents( 2330): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  760): Displayed com.example.hello/.MainActivity: +317ms
,I/chromium( 2330): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 2330): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 2330): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2330): GC_CONCURRENT freed 243K, 2% free 16880K/17152K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 2330): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42845d60
,D/dalvikvm( 2330): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42845d60
,D/jxcore_app_log( 2330): JniHelper::setJavaVM(0x417dbed0), pthread_self() = 1977830312
,D/JX-Cordova( 2330): jxcore cordova android initializing
,D/dalvikvm( 2330): GC_CONCURRENT freed 222K, 2% free 17135K/17388K, paused 1ms+1ms, total 11ms
,D/dalvikvm( 2330): GC_CONCURRENT freed 397K, 3% free 17214K/17648K, paused 2ms+2ms, total 15ms
,D/dalvikvm( 2330): WAIT_FOR_CONCURRENT_GC blocked 4ms
,W/jxcore-log( 2330): Initializing JXcore engine
,W/jxcore-log( 2330): JXcore engine is ready
,D/dalvikvm( 2330): GC_CONCURRENT freed 264K, 3% free 17342K/17756K, paused 2ms+1ms, total 11ms
,D/dalvikvm( 2330): WAIT_FOR_CONCURRENT_GC blocked 9ms
,W/jxcore-log( 2330): Starting JXcore engine
,W/jxcore-log( 2330): Platform android
W/jxcore-log( 2330): 
,W/jxcore-log( 2330): Process ARCH arm
W/jxcore-log( 2330): 
,I/jxcore-log( 2330): JXcore Cordova bridge is ready!
I/jxcore-log( 2330): 
,W/jxcore-log( 2330): JXcore engine is started
,E/jxcore-log( 2330): >> LGE-Nexus 5
E/jxcore-log( 2330): 
,I/jxcore-log( 2330): Total memory 1945137152
I/jxcore-log( 2330): 
,I/jxcore-log( 2330): Free memory 876466176
I/jxcore-log( 2330): 
I/jxcore-log( 2330): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2330): 
,I/jxcore-log( 2330): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2330): 
,I/jxcore-log( 2330): userPath [ 'www', 'www' ]
I/jxcore-log( 2330): 
,I/jxcore-log( 2330): Size 1080 1776
I/jxcore-log( 2330): 
,I/jxcore-log( 2330): Screen Brightness 1
I/jxcore-log( 2330): 
,E/jxcore-log( 2330): Dummy Error Log.
E/jxcore-log( 2330): 
,D/AlertService( 1748): Beginning updateAlertNotification
,I/ActivityManager(  760): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2390 uid=10001 gids={50001, 3003, 1028, 1015}
,D/dalvikvm(  185): GC_EXPLICIT freed 42K, 1% free 16699K/16772K, paused 2ms+1ms, total 15ms
,D/dalvikvm(  185): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 2ms+1ms, total 14ms
,D/dalvikvm(  185): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+2ms, total 11ms
,I/CalendarProvider2( 2390): Created com.android.providers.calendar.CalendarAlarmManager@4285ba28(com.android.providers.calendar.CalendarProvider2@428536e8)
,D/AlertService( 1748): No fired or scheduled alerts
,D/AlertService( 1748): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1748): No events found starting within 1 week.
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "sms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/jxcore-log( 2330): getBuffer is called!!!!
I/jxcore-log( 2330): 
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "smsto"
,I/Launcher( 1077): Deferring update until onResume
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mmsto"
,I/Launcher( 1077): Deferring update until onResume
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "sms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "smsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 2330): GC_FOR_ALLOC freed 657K, 5% free 16932K/17784K, paused 8ms, total 8ms
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mmsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 2330): GC_CONCURRENT freed 243K, 4% free 17110K/17784K, paused 2ms+2ms, total 11ms
,I/GCoreNlp(  997): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/dalvikvm( 2330): GC_CONCURRENT freed 394K, 4% free 17148K/17784K, paused 0ms+2ms, total 10ms
,D/dalvikvm( 2330): GC_CONCURRENT freed 384K, 4% free 17224K/17784K, paused 1ms+2ms, total 16ms
,D/dalvikvm( 2330): GC_FOR_ALLOC freed 80K, 4% free 17238K/17784K, paused 7ms, total 7ms
,D/dalvikvm( 2330): GC_FOR_ALLOC freed 56K, 3% free 17267K/17784K, paused 8ms, total 8ms
,I/dalvikvm-heap( 2330): Grow heap (frag case) to 17.013MB for 130826-byte allocation
,D/dalvikvm( 2330): GC_FOR_ALLOC freed 85K, 4% free 17309K/17912K, paused 15ms, total 15ms
,D/dalvikvm( 2330): GC_FOR_ALLOC freed <1K, 4% free 17309K/17912K, paused 8ms, total 8ms
,I/dalvikvm-heap( 2330): Grow heap (frag case) to 17.117MB for 196234-byte allocation
,D/dalvikvm( 2330): GC_FOR_ALLOC freed 127K, 5% free 17373K/18104K, paused 15ms, total 15ms
,D/dalvikvm( 2330): GC_FOR_ALLOC freed <1K, 5% free 17373K/18104K, paused 8ms, total 8ms
,I/dalvikvm-heap( 2330): Grow heap (frag case) to 17.135MB for 150022-byte allocation
,D/dalvikvm( 2330): GC_FOR_ALLOC freed 0K, 5% free 17520K/18252K, paused 16ms, total 16ms
,D/dalvikvm( 2330): GC_FOR_ALLOC freed 441K, 7% free 17078K/18252K, paused 16ms, total 16ms
,I/CalendarProvider2( 2390): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2390): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Killing 1771:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/ActivityManager(  760): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.gm/.GmailReceiver
,I/NotifUtils( 1818): Validating Notification, mapSize: 1 getAttention: true
,I/NotifUtils( 1818): Unseen count doesn't match cursor count.  unseen: 7 cursor count: 1
,D/dalvikvm( 1818): GC_CONCURRENT freed 350K, 3% free 17337K/17716K, paused 2ms+2ms, total 13ms
,I/NotifUtils( 1818): Showing notification with unreadCount of 15 and unseenCount of 1
,D/dalvikvm( 1818): GC_FOR_ALLOC freed 246K, 3% free 17446K/17848K, paused 13ms, total 13ms
,I/dalvikvm-heap( 1818): Grow heap (frag case) to 17.204MB for 147472-byte allocation
,D/dalvikvm( 1818): GC_FOR_ALLOC freed 0K, 3% free 17590K/17996K, paused 10ms, total 10ms
,I/NotifUtils( 1818): Account: 61035162 vibrate: false
,I/NotifUtils( 1818): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
,D/dalvikvm(  760): GC_FOR_ALLOC freed 840K, 9% free 26195K/28644K, paused 63ms, total 63ms
,I/dalvikvm-heap(  760): Grow heap (frag case) to 25.754MB for 147472-byte allocation
,D/dalvikvm(  760): GC_FOR_ALLOC freed <1K, 9% free 26338K/28792K, paused 39ms, total 39ms
,D/dalvikvm(  760): GC_FOR_ALLOC freed 4K, 9% free 26335K/28792K, paused 61ms, total 61ms
,I/dalvikvm-heap(  760): Grow heap (frag case) to 25.891MB for 147472-byte allocation
,D/dalvikvm(  760): GC_FOR_ALLOC freed <1K, 9% free 26478K/28940K, paused 38ms, total 38ms
,D/dalvikvm(  760): GC_FOR_ALLOC freed 2K, 9% free 26489K/28940K, paused 38ms, total 38ms
,I/dalvikvm-heap(  760): Grow heap (frag case) to 26.041MB for 147472-byte allocation
,D/dalvikvm(  760): GC_FOR_ALLOC freed <1K, 9% free 26633K/29088K, paused 42ms, total 42ms
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.gm/.GmailReceiver
,D/dalvikvm( 1818): GC_CONCURRENT freed 538K, 4% free 17471K/18040K, paused 2ms+1ms, total 23ms
,D/dalvikvm(  760): GC_FOR_ALLOC freed 109K, 9% free 26529K/29088K, paused 38ms, total 39ms
,I/dalvikvm-heap(  760): Grow heap (frag case) to 26.081MB for 147472-byte allocation
,D/dalvikvm(  760): GC_FOR_ALLOC freed <1K, 9% free 26673K/29236K, paused 37ms, total 37ms
,D/dalvikvm(  760): GC_FOR_ALLOC freed <1K, 9% free 26676K/29236K, paused 40ms, total 40ms
,I/dalvikvm-heap(  760): Grow heap (frag case) to 26.223MB for 147472-byte allocation
,D/dalvikvm(  760): GC_FOR_ALLOC freed <1K, 9% free 26820K/29384K, paused 38ms, total 38ms
,D/dalvikvm(  760): GC_FOR_ALLOC freed 1K, 9% free 26823K/29384K, paused 38ms, total 38ms
,I/dalvikvm-heap(  760): Grow heap (frag case) to 26.368MB for 147472-byte allocation
,D/dalvikvm(  760): GC_FOR_ALLOC freed <1K, 9% free 26967K/29532K, paused 37ms, total 37ms
,D/dalvikvm(  760): GC_FOR_ALLOC freed <1K, 9% free 26973K/29532K, paused 38ms, total 38ms
,I/dalvikvm-heap(  760): Grow heap (frag case) to 26.513MB for 147472-byte allocation
,D/dalvikvm(  760): GC_FOR_ALLOC freed <1K, 9% free 27117K/29680K, paused 40ms, total 40ms
I/ActivityManager(  760): Resuming delayed broadcast
,D/dalvikvm( 1011): GC_CONCURRENT freed 330K, 4% free 17886K/18520K, paused 4ms+2ms, total 34ms
,D/CaptivePortalTracker(  760): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  760): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/GCM     ( 1011): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  760): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/CaptivePortalTracker(  760): Checking http://216.58.209.46/generate_204
W/ActivityThread(  760): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/GCoreFlp(  997): No location to return for getLastLocation()
,W/FusedLocationProvider(  997): location=null
,D/dalvikvm( 1331): GC_CONCURRENT freed 491K, 3% free 18594K/19120K, paused 22ms+3ms, total 60ms
,D/CaptivePortalTracker(  760): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  760): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  760): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  760): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  760): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver: pid=2471 uid=10063 gids={50063, 3003, 3002, 1028, 1015}
,D/dalvikvm( 1991): GC_CONCURRENT freed 1414K, 7% free 22370K/23816K, paused 1ms+1ms, total 44ms
,E/dalvikvm( 2471): Could not find class 'android.app.Notification$Action$Builder', referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lefj;
,D/dalvikvm( 2471): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 2471): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve new-instance 575 (Landroid/graphics/drawable/RippleDrawable;) in Lefj;
,D/dalvikvm( 2471): VFY: replacing opcode 0x22 at 0x000b
,E/dalvikvm( 2471): Could not find class 'android.app.Notification$Action$Builder', referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lefj;
,D/dalvikvm( 2471): VFY: replacing opcode 0x22 at 0x0000
,D/dalvikvm( 2471): GC_CONCURRENT freed 195K, 2% free 16936K/17164K, paused 2ms+2ms, total 17ms
,W/dalvikvm( 2471): Unable to resolve superclass of Lcm; (800)
,W/dalvikvm( 2471): Link of class 'Lcm;' failed
E/dalvikvm( 2471): Could not find class 'cm', referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve new-instance 2378 (Lcm;) in Lefj;
,D/dalvikvm( 2471): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 2471): Unable to resolve superclass of Lco; (800)
W/dalvikvm( 2471): Link of class 'Lco;' failed
E/dalvikvm( 2471): Could not find class 'co', referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve new-instance 2432 (Lco;) in Lefj;
D/dalvikvm( 2471): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 2471): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve virtual method 5224: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2471): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 2471): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve virtual method 5756: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 2471): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 2471): Could not find method android.view.View.getTransitionName, referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve virtual method 5560: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 2471): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 2471): VFY: unable to find class referenced in signature (Lx;)
I/dalvikvm( 2471): Could not find method android.transition.Transition.getTargetNames, referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve virtual method 5213: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 2471): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 2471): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve interface method 5806: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 2471): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2471): Could not find method android.view.ViewParent.onNestedFling, referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve interface method 5805: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 2471): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2471): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve interface method 5807: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 2471): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 2471): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 2471): Could not find class 'android.app.RemoteInput[]', referenced from method efj.a
W/dalvikvm( 2471): VFY: unable to resolve new-array 13337 ([Landroid/app/RemoteInput;) in Lefj;
,D/dalvikvm( 2471): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 2471): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method efj.b
W/dalvikvm( 2471): VFY: unable to resolve virtual method 5224: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2471): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 2471): VFY: unable to find class referenced in signature (Lx;)
,D/dalvikvm( 2471): DexOpt: unable to opt direct call 0x09c0 at 0x0e in Lefj;.a
,D/dalvikvm( 2471): DexOpt: unable to opt direct call 0x0d49 at 0x0e in Lefj;.a
,D/dalvikvm( 2471): DexOpt: unable to opt direct call 0x09c0 at 0x0e in Lefj;.a
W/dalvikvm( 2471): Unable to resolve superclass of Lcm; (800)
W/dalvikvm( 2471): Link of class 'Lcm;' failed
D/dalvikvm( 2471): DexOpt: unable to opt direct call 0x39db at 0x08 in Lefj;.a
W/dalvikvm( 2471): Unable to resolve superclass of Lco; (800)
,W/dalvikvm( 2471): Link of class 'Lco;' failed
D/dalvikvm( 2471): DexOpt: unable to opt direct call 0x3b51 at 0x30 in Lefj;.a
,D/dalvikvm( 2471): DexOpt: unable to opt direct call 0x0a18 at 0x13 in Lefj;.a
,D/dalvikvm( 2471): GC_CONCURRENT freed 322K, 3% free 17091K/17444K, paused 2ms+2ms, total 16ms
,D/dalvikvm( 2471): GC_CONCURRENT freed 332K, 3% free 17255K/17616K, paused 3ms+3ms, total 20ms
,I/dalvikvm( 2471): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eer.a
W/dalvikvm( 2471): VFY: unable to resolve virtual method 2532: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2471): VFY: replacing opcode 0x6e at 0x023c
I/dalvikvm( 2471): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eer.a
W/dalvikvm( 2471): VFY: unable to resolve virtual method 2906: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2471): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 2471): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eer.c
W/dalvikvm( 2471): VFY: unable to resolve virtual method 2532: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2471): VFY: replacing opcode 0x6e at 0x0207
,D/dalvikvm( 2471): Trying to load lib /data/app-lib/com.google.android.apps.plus-2/libcrashreporterer.so 0x42841b18
,D/dalvikvm( 2471): Added shared lib /data/app-lib/com.google.android.apps.plus-2/libcrashreporterer.so 0x42841b18
,D/dalvikvm( 2471): GC_CONCURRENT freed 312K, 2% free 17436K/17776K, paused 2ms+1ms, total 18ms
,I/SystemUpdateService( 1331): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1331): onCreate
,D/SystemUpdateService( 1331): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1331): active receiver: enabled
,I/SystemUpdateService( 1331): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1331): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1331): now status is 0 (complete)
I/SystemUpdateService( 1331): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1331): file has been verified
,I/SystemUpdateService( 1331): OTA package size = 2571501
,I/SystemUpdateService( 1331): showing system update notification
,I/iu.SyncManager( 1331): SYNC; picasa accounts
,D/NetworkLogImpl( 1331): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1331): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1331): num queued entries: 0
,I/iu.UploadsManager( 1331): num updated entries: 0
,I/iu.SyncManager( 1331): NEXT; no task
,D/SystemUpdateService( 1331): onDestroy
,I/ActivityManager(  760): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=2501 uid=10031 gids={50031, 3003, 1028, 1015}
,V/GLSActivity( 1011): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1011): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1011): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
,W/dalvikvm( 1011): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1011): VFY: replacing opcode 0x6e at 0x0046
,D/dalvikvm( 1011): GC_CONCURRENT freed 401K, 4% free 17886K/18520K, paused 1ms+1ms, total 17ms
,W/dalvikvm( 1011): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/dalvikvm( 1011): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1011): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1011): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1011): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1011): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1011): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 2501): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2501): VFY: unable to resolve instance field 68
,D/dalvikvm( 2501): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 2501): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2501): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2501): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2501): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2501): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2501): VFY: unable to resolve instance field 68
,D/dalvikvm( 2501): VFY: replacing opcode 0x54 at 0x0011
,V/AlarmClock( 1785): AlarmInitReceiver android.intent.action.TIME_SET
,D/dalvikvm( 2501): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2501): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2501): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2501): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2501): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2501): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/AlarmClock( 1785): Displaying next alarm time: ''
,V/AlarmClock( 1785): AlarmInitReceiver finished
,I/Babel   ( 1991): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  760): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2526 uid=10068 gids={50068}
,D/dalvikvm( 2526): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x4283ef80, skipping init
D/TimeService( 2526): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452528603096
D/        ( 2526): TimeServiceNative: User Time to be set is 1452528603097
D/QC-time-services( 2526): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 2526): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2526): Lib:time_genoff_operation: pargs->ts_val = 1452528603097
D/QC-time-services( 2526): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  200): Daemon: Connection accepted:time_genoff
D/QC-time-services(  200): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452528603097
D/QC-time-services(  200): Daemon:genoff_opr: Base = 2, val = 1452528603097, operation = 0
D/QC-time-services(  200): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/3/71 10:14:58
D/QC-time-services(  200): Daemon:Value read from RTC seconds = 36843298000
D/QC-time-services(  200): Daemon:new time 1452528603097 
D/QC-time-services(  200): Daemon: delta 1415685305097 genoff 1415685305097 
D/QC-time-services(  200): Daemon:genoff_persistent_update: Writing genoff = 1415685305097 to memory
D/QC-time-services(  200): Daemon:Opening File: /data/system/time/ats_2
,D/QC-time-services(  200): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  200): Updating the TOD offset
D/QC-time-services(  200): Daemon:genoff_persistent_update: Writing genoff = 1415685305097 to memory
D/QC-time-services(  200): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  200): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  200): Daemon:Update to modem bit set
D/QC-time-services(  200): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  200): Daemon: Base = 2, Value being sent to MODEM = 1136563803097
,E/QC-time-services( 2526): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  200): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  200): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager(  760): Killing 1800:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/CheckinService( 1331): Checkin interval check for package: unspecified last checkin: 1452521145934 min interval config: 0 actual interval: 7457191
,D/dalvikvm( 1011): GC_CONCURRENT freed 471K, 4% free 17920K/18520K, paused 1ms+2ms, total 35ms
I/ActivityManager(  760): Killing 1861:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,D/dalvikvm( 1748): GC_CONCURRENT freed 292K, 2% free 16794K/17116K, paused 4ms+2ms, total 80ms
,I/EventLogService( 1331): Aggregate from 1452526794185 (log), 1452526794185 (data)
,D/dalvikvm( 1331): GC_CONCURRENT freed 487K, 3% free 18627K/19144K, paused 3ms+3ms, total 25ms
,D/dalvikvm( 1011): GC_FOR_ALLOC freed 210K, 4% free 17907K/18528K, paused 11ms, total 11ms
,D/dalvikvm(  997): GC_CONCURRENT freed 497K, 4% free 18618K/19212K, paused 1ms+1ms, total 21ms
,I/ActivityManager(  760): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,D/dalvikvm( 1991): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1991): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1991): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 1991): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 1991): VFY: unable to resolve instance field 36
,D/dalvikvm( 1991): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 1991): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1991): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1991): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 1991): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 1991): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 1991): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42910dd8
,D/dalvikvm( 1991): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42910dd8
,D/dalvikvm( 1991): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42910dd8, skipping init
,D/dalvikvm( 1991): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42910dd8
,D/dalvikvm( 1991): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42910dd8
,V/JNIHelp ( 1991): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 1991): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42910dd8
,D/dalvikvm( 1991): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42910dd8
D/dalvikvm( 1991): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42910dd8
,D/dalvikvm( 1991): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42910dd8
,D/ConnectivityService(  760): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ProviderInstaller( 1991): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
D/MusicLifecycle( 2182): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@428fc708 and intent Intent { act=com.google.android.music.IMPORT_COMPLETE flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,D/MusicLifecycle( 2182): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
I/dalvikvm( 1331): Could not find method android.content.Context.getNoBackupFilesDir, referenced from method com.google.android.gms.iid.n.<init>
W/dalvikvm( 1331): VFY: unable to resolve virtual method 378: Landroid/content/Context;.getNoBackupFilesDir ()Ljava/io/File;
,D/dalvikvm( 1331): VFY: replacing opcode 0x6e at 0x002c
I/dalvikvm( 1331): Could not find method android.content.Context.getDrawable, referenced from method android.support.v4.content.g.a
W/dalvikvm( 1331): VFY: unable to resolve virtual method 287: Landroid/content/Context;.getDrawable (I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 1331): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1331): Could not find method android.content.Context.getColor, referenced from method android.support.v4.content.g.b
W/dalvikvm( 1331): VFY: unable to resolve virtual method 283: Landroid/content/Context;.getColor (I)I
,D/dalvikvm( 1331): VFY: replacing opcode 0x6e at 0x0006
,D/MusicLifecycle( 2182): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,I/ActivityManager(  760): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
D/WearableService(  997): callingUid 10007, callindPid: 997
,E/GmsUtils( 2182): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/GmsUtils( 2182): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  760): Resuming delayed broadcast
D/MusicLifecycle( 2182): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,I/ActivityManager(  760): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2569 uid=10011 gids={50011, 3003}
,I/ActivityManager(  760): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2585 uid=10013 gids={50013, 3003, 3002}
,I/ActivityManager(  760): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2599 uid=10014 gids={50014, 3003, 1028, 1015}
,I/ActivityManager(  760): Killing 1096:com.android.printspooler/u0a64 (adj 15): empty #17
,D/Finsky  ( 2599): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 2599): GC_CONCURRENT freed 235K, 2% free 16887K/17152K, paused 3ms+2ms, total 18ms
,D/dalvikvm(  760): GC_EXPLICIT freed 1388K, 10% free 26853K/29680K, paused 2ms+4ms, total 54ms
,D/Finsky  ( 2599): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 2599): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2599): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 2599): GC_CONCURRENT freed 282K, 2% free 17129K/17396K, paused 2ms+2ms, total 15ms
,I/ActivityManager(  760): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver: pid=2636 uid=10019 gids={50019, 3003, 1028, 3002, 1015}
,I/ActivityManager(  760): Killing 1978:com.google.android.exchange/u0a37 (adj 15): empty #17
,D/Finsky  ( 2599): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2599): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 2599): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2599): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1011): GC_CONCURRENT freed 344K, 4% free 17948K/18528K, paused 1ms+2ms, total 26ms
,D/dalvikvm( 1991): Trying to load lib /data/app-lib/com.google.android.talk-1/libcronet.so 0x428431a0
,I/Icing.InternalIcingCorporaProvider( 2636): Updating corpora: A: com.example.hello, C: MAYBE
,I/ActivityManager(  760): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
D/dalvikvm( 1991): Added shared lib /data/app-lib/com.google.android.talk-1/libcronet.so 0x428431a0
,D/dalvikvm( 2636): GC_CONCURRENT freed 210K, 2% free 16943K/17172K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 1991): GC_CONCURRENT freed 1209K, 6% free 22966K/24224K, paused 1ms+3ms, total 37ms
,D/dalvikvm( 1991): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/dalvikvm( 1991): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 1991): VFY: unable to resolve instance field 1289
D/dalvikvm( 1991): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 1991): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 1991): DexOpt: unable to optimize instance field ref 0x0509 at 0x10 in Lorg/chromium/base/BuildInfo;.hasApkSplits
,D/dalvikvm( 1331): GC_CONCURRENT freed 432K, 3% free 18766K/19228K, paused 3ms+3ms, total 21ms
,D/dalvikvm( 2636): GC_CONCURRENT freed 251K, 2% free 17086K/17368K, paused 2ms+1ms, total 12ms
,I/Icing.InternalIcingCorporaProvider( 2636): UpdateCorporaTask done [took 268 ms] updated apps [took 268 ms] 
I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Killing 2042:com.google.android.apps.maps/u0a57 (adj 15): empty #17
,D/ChimeraCfgMgr( 1331): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1331): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1331): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/dalvikvm( 1331): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1331): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1331): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1331): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1331): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1331): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1331): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1331): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1331): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1331): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1331): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1331): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1331): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1331): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1331): Submit a task: k
,D/dalvikvm( 1331): GC_CONCURRENT freed 610K, 4% free 18788K/19396K, paused 2ms+5ms, total 31ms
,D/ChimeraCfgMgr( 1331): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/ActivityManager(  760): Killing 2070:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  760): Service ServiceRecord{4301db20 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{430013c0 2070:com.google.android.youtube/u0a71} not same as in map: null
,D/ChimeraCfgMgr( 1331): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1331): Processing package: com.example.hello
,W/BaseAppContext( 1331): Using Auth Proxy for data requests.
,W/BaseAppContext( 1331): Using Auth Proxy for data requests.
I/ActivityManager(  760): Waited long enough for: ServiceRecord{42fb8ea8 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  760): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2683 uid=10035 gids={50035, 1028, 3003, 1015}
D/GassUtils( 1331): Found app info for package com.example.hello:18. Hash: 7e411fc8c80adb766ff5747826a81d96c76dd9cb2b76f4f040d3bd27a68f585b
D/k       ( 1331): Found info for package com.example.hello in db.
,W/BaseAppContext( 1331): Using Auth Proxy for data requests.
,W/BaseAppContext( 1331): Using Auth Proxy for data requests.
,W/BaseAppContext( 1331): Using Auth Proxy for data requests.
,W/BaseAppContext( 1331): Using Auth Proxy for data requests.
,W/BaseAppContext( 1331): Using Auth Proxy for data requests.
,W/dalvikvm( 1331): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1331): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1331): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1331): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1331): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1331): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1331): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1331): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1331): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1331): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1331): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1331): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1331): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1331): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 1331): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1331): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1331): VFY: replacing opcode 0x6e at 0x0006
,I/Babel   ( 1991): Account registration complete:1-Redacted-21
,I/Babel   ( 1991): ProcessRegisterDeviceResponse
,I/Babel   ( 1991): Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
,D/dalvikvm( 1331): GC_CONCURRENT freed 424K, 3% free 19063K/19516K, paused 3ms+7ms, total 33ms
,D/dalvikvm( 1331): WAIT_FOR_CONCURRENT_GC blocked 2ms
,D/dalvikvm( 1331): WAIT_FOR_CONCURRENT_GC blocked 4ms
,I/PeopleDatabaseHelper( 1331): cleanUpNonGplusAccounts done.
,D/dalvikvm( 2683): GC_CONCURRENT freed 257K, 2% free 16849K/17136K, paused 3ms+1ms, total 14ms
,W/dalvikvm( 1331): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1331): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1331): Module APK com.google.android.play.games already loaded
D/dalvikvm( 2683): GC_CONCURRENT freed 298K, 2% free 17065K/17392K, paused 1ms+2ms, total 16ms
,D/dalvikvm( 2683): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2683): WAIT_FOR_CONCURRENT_GC blocked 7ms
,I/dalvikvm( 2683): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
,W/dalvikvm( 2683): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2683): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 2683): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2683):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2683):   adb logcat -s GAv4
,W/GAv4    ( 2683): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/dalvikvm( 2683): GC_CONCURRENT freed 384K, 3% free 17195K/17608K, paused 3ms+1ms, total 11ms
,D/dalvikvm( 2683): WAIT_FOR_CONCURRENT_GC blocked 2ms
,D/dalvikvm( 2683): WAIT_FOR_CONCURRENT_GC blocked 4ms
,W/GAv4    ( 2683): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2683): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/dalvikvm( 2683): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 2683): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 2683): VFY: replacing opcode 0x6e at 0x001b
,W/AnalyticsTrackerProxyImpl( 2683): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.35, sample rate 1.0
,D/dalvikvm( 2683): GC_CONCURRENT freed 364K, 3% free 17343K/17736K, paused 2ms+1ms, total 13ms
,D/dalvikvm( 2683): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2683): WAIT_FOR_CONCURRENT_GC blocked 3ms
,I/dalvikvm( 2683): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 2683): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 2683): VFY: replacing opcode 0x71 at 0x0075
,D/dalvikvm( 2683): GC_CONCURRENT freed 307K, 2% free 17561K/17856K, paused 2ms+2ms, total 18ms
,I/ActivityManager(  760): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2727 uid=10065 gids={50065, 3003, 1028, 1015}
,I/ActivityManager(  760): Killing 2166:com.android.settings/1000 (adj 15): empty #17
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  760): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42ec4ab0 mBinding = false
,D/dalvikvm( 2683): GC_CONCURRENT freed 248K, 2% free 17827K/18104K, paused 1ms+13ms, total 34ms
,D/dalvikvm( 2683): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/dalvikvm( 2683): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2683): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/BluetoothManagerService(  760): Message: 2
,D/BluetoothManagerService(  760): Sending off request.
D/BluetoothAdapterState( 1542): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1542): Setting state to 13
I/BluetoothAdapterState( 1542): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1542): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 1542): onBluetoothDisable()
,I/BluetoothAdapterState( 1542): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 1542): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService(  760): Message: 60
,D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothAdapterProperties( 1542): Scan Mode:20
,D/BluetoothAdapterState( 1542): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 1542): onReceive
D/BluetoothMapService( 1542): STATE_TURNING_OFF
D/BluetoothMapService( 1542): MAP Service closeService in
E/bt-btif ( 1542): bta_jv_rfcomm_stop_server
,I/BtOppRfcommListener( 1542): stopping Accept Thread
E/BtOppRfcommListener( 1542): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 1542): BluetoothSocket listen thread finished
E/bt-btif ( 1542): bta_jv_rfcomm_stop_server
E/bt-btif ( 1542): bta_jv_rfcomm_stop_server
W/bt-btif ( 1542): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 1542): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1542): L2CAP - PSM: 0x0017 not found for deregistration
,D/btif_config_util( 1542): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/WifiService(  760): setWifiEnabled: false pid=2330, uid=10116
,I/jxcore-log( 2330): ****TEST TOOK:  5075  ms ****
I/jxcore-log( 2330): 
,I/jxcore-log( 2330): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2330): 
,D/CommandListener(  180): Clearing all IP addresses on wlan0
I/ActivityManager(  760): Waited long enough for: ServiceRecord{42dc8de8 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,D/ConnectivityService(  760): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,E/WifiStateMachine(  760): scanCount==0 - aborting
D/ConnectivityService(  760): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  760): Attempting to switch to mobile
D/ConnectivityService(  760): Attempting to switch to BLUETOOTH_TETHER
,D/dalvikvm( 2683): GC_CONCURRENT freed 316K, 2% free 18016K/18364K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 2683): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2683): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2683): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2683): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2683): VFY: unable to resolve instance field 36
D/dalvikvm( 2683): VFY: replacing opcode 0x54 at 0x005f
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/dalvikvm( 2683): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2683): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2683): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2683): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2683): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 2683): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429cb620
D/dalvikvm( 2683): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429cb620
D/dalvikvm( 2683): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429cb620, skipping init
,D/NetUtils(  760): android_net_utils_resetConnections in env=0x753ed038 clazz=0x3e300001 iface=wlan0 mask=0x3
,D/ConnectivityService(  760): resetConnections(wlan0, 3)
D/dalvikvm( 2683): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429cb620
D/dalvikvm( 2683): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429cb620
V/JNIHelp ( 2683): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
V/NativeCrypto( 1011): Read error: ssl=0x78ff93f8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1011): SSL shutdown failed: ssl=0x78ff93f8: I/O error during system call, Broken pipe
,W/bt-btif ( 1542): ag scb idx 1 not allocated
E/bt-btif ( 1542): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1542): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1542): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1542): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1542): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1542): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1542): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_hwcfg( 1542): hw_epilog_process
,D/dalvikvm( 2683): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429cb620
D/dalvikvm( 2683): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x429cb620
D/dalvikvm( 2683): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429cb620
,D/dalvikvm( 2683): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x429cb620
,D/dalvikvm( 2683): GC_CONCURRENT freed 477K, 3% free 17947K/18460K, paused 2ms+1ms, total 18ms
D/bt_hwcfg( 1542): hw_epilog_cback Opcode:0x0C03 Status: 0
,I/bt_hci_bdroid( 1542): bt_hc_worker_thread exiting
W/bt_userial( 1542): select_read return size <=0:-1, exiting userial_read_thread
,I/bt_userial_vendor( 1542): device fd = 65 close
,D/BTSNOOP-DISP( 1542): btsnoop_close
,I/GKI_LINUX( 1542): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1542): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 1542): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,W/Quickoffice( 2727): Cleanup of storage: done
,D/com.google.android.apps.docs.quickoffice.X( 2727): Loading recent documents list
,D/BluetoothAdapterState( 1542): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 1542): Received stop request...Stopping profile...
,D/Quickoffice( 2727): The number of lines present in  /proc/mount 21
,D/BluetoothHeadset( 1033): Proxy object disconnected
D/BluetoothHeadset( 1033): Proxy object disconnected
D/BluetoothHeadset(  760): Proxy object disconnected
,D/BluetoothHeadset( 1033): Proxy object disconnected
,D/BluetoothAdapterService( 1542): Profile still running: com.android.bluetooth.hdp.HealthService
D/A2dpService( 1542): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1542): Exit Disconnected: -1
,D/Quickoffice( 2727): Parsing the storagedefinition.xml.
,D/BluetoothA2dp(  760): Proxy object disconnected
,D/BluetoothAdapterState( 1542): Stopping profile services that were post enabled
,W/BluetoothHeadsetServiceJni( 1542): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1542): Cleaning up Bluetooth Handsfree callback object
,D/HidService( 1542): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1542): Profile still running: com.android.bluetooth.hdp.HealthService
,D/HealthService( 1542): Received stop request...Stopping profile...
,D/PanService( 1542): Received stop request...Stopping profile...
D/BluetoothPan(  760): BluetoothPAN Proxy object disconnected
D/BtGatt.DebugUtils( 1542): handleDebugAction() action=null
D/Quickoffice( 2727): # of Storagedefinitions - 35
D/Quickoffice( 2727): The # of storage definitions available - 35
D/Quickoffice( 2727): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2727): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/BtGatt.GattService( 1542): Received stop request...Stopping profile...
D/BtGatt.GattService( 1542): stop()
,D/Quickoffice( 2727): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
,D/Quickoffice( 2727): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
I/GKI_LINUX( 1542): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1542): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 1542): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothMapService( 1542): Received stop request...Stopping profile...
,D/BluetoothMapService( 1542): stop()
,D/BluetoothMapService( 1542): MAP Service closeService in
D/BluetoothAdapterService( 1542): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1542): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1542): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1542): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1542): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 1542): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1542): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 1542): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1542): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1542): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1542): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 1542): cleanup()
D/BluetoothMapService( 1542): MAP Service closeService in
D/BluetoothAdapterState( 1542): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 1542): Setting state to 10
I/BluetoothAdapterState( 1542): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1542): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 1542): Entering OffState
D/BluetoothManagerService(  760): Message: 60
,D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(false) to 6 receivers.
D/BluetoothA2dp(  760): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  760): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1033): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1033): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1033): onBluetoothStateChange: up=false
D/BluetoothManagerService(  760): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceDown() to 7 receivers.
D/BluetoothTethering(  760): got CMD_CHANNEL_DISCONNECTED
D/BluetoothManagerService(  760): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42ec4ab0 mBinding = false
,E/BluetoothTethering(  760): attempted to stop reverse tether with nothing tethered
,D/BluetoothManagerService(  760): Sending unbind request.
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 13 -> 10
D/Nat464Xlat(  760): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService(  760): handleInetConditionChange: no active default network - ignore
,D/BluetoothAdapter(  868): 1118578792: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapterService( 1542): Cleaning up adapter native....
I/GKI_LINUX( 1542): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1542): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1542): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 1542): cleanupNative: return from cleanup
,D/BluetoothAdapterService( 1542): Done cleaning up adapter native....
D/dalvikvm( 2683): GC_FOR_ALLOC freed 31K, 3% free 17966K/18460K, paused 21ms, total 21ms
D/BluetoothAdapterService(1115982384)( 1542): ****onDestroy()********
D/BtGatt.GattService( 1542): cleanup()
W/bt-btif ( 1542): GATTC Module not enabled/already disabled
,W/bt-btif ( 1542): GATTS Module not enabled/already disabled
,D/BluetoothAdapter(  997): 1116301184: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  997): 1116301184: getState() :  mService = null. Returning STATE_OFF
,D/Quickoffice( 2727): Processing mountline proc /proc proc rw,relatime 0 0
,D/Quickoffice( 2727): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
,D/dalvikvm( 2683): GC_FOR_ALLOC freed <1K, 3% free 18005K/18500K, paused 13ms, total 13ms
,I/dalvikvm-heap( 2683): Grow heap (frag case) to 17.685MB for 79892-byte allocation
,D/dalvikvm( 2727): GC_CONCURRENT freed 173K, 2% free 16913K/17116K, paused 11ms+2ms, total 39ms
D/Quickoffice( 2727): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
,D/Quickoffice( 2727): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2727): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2727): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
,D/Quickoffice( 2727): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2727): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
,D/Quickoffice( 2727): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2727): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
,D/Quickoffice( 2727): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2727): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
,D/Quickoffice( 2727): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2727): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/Quickoffice( 2727): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2727): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/Quickoffice( 2727): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/Quickoffice( 2727): Build properties are not configured for this storage definition.
,D/Quickoffice( 2727): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
,D/dalvikvm( 2683): GC_FOR_ALLOC freed 0K, 3% free 18083K/18580K, paused 15ms, total 15ms
,D/Quickoffice( 2727): The # of mounts identified -  1
,I/ActivityManager(  760): Killing 1818:com.google.android.gm/u0a41 (adj 15): empty #17
,D/MusicLifecycle( 2182): com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@428fc708 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,D/MusicLifecycle( 2182): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,D/MusicLifecycle( 2182): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,D/MusicLifecycle( 2182): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@428fc708 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,D/MusicLifecycle( 2182): com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,D/com.google.android.apps.docs.quickoffice.X( 2727): Checking validity of 0 items
I/ActivityManager(  760): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,W/ActivityManager(  760): No permission grants found for com.quickoffice.android
D/ContentResolverUtil( 2727): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2727): 0 items were valid
D/MusicLifecycle( 2182): com.google.android.music.download.cache.TrackCacheService generated event: Service created
I/Icing   ( 1331): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
I/MusicLeanback( 2182): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2182): Stop autocaching.
D/MusicLifecycle( 2182): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,D/MusicLifecycle( 2182): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
I/ActivityManager(  760): Resuming delayed broadcast
,E/GmsUtils( 2182): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/MusicLifecycle( 2182): com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,D/MusicLifecycle( 2182): com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,E/GmsUtils( 2182): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/MusicLifecycle( 2182): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,D/AndroidRuntime( 2751): 
D/AndroidRuntime( 2751): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2751): CheckJNI is OFF
,D/dalvikvm(  955): GC_CONCURRENT freed 206K, 2% free 17101K/17336K, paused 3ms+0ms, total 13ms
,I/wpa_supplicant(  926): p2p0: CTRL-EVENT-TERMINATING 
,W/Quickoffice( 2727): Could not load clipboard.
,W/Launcher( 1077): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42840ac8 new=com.google.android.velvet.VelvetApplication@42840ac8
,I/Icing.InternalIcingCorporaProvider( 2636): Updating corpora: A: com.google.android.gms, C: MAYBE
,D/dalvikvm( 2751): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 2751): Added shared lib libjavacore.so 0x0
I/wpa_supplicant(  926): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/dalvikvm( 2751): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2751): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 2751): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,I/ActivityManager(  760): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  760): Resuming delayed broadcast
,D/AlertReceiver( 1748): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
,D/AlertService( 1748): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/dalvikvm( 2751): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,D/dalvikvm( 1331): GC_CONCURRENT freed 610K, 4% free 19183K/19824K, paused 4ms+3ms, total 54ms
,D/PackageBroadcastService( 1331): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1331): Null package name or gms related package.  Ignoreing.
,W/Quickoffice( 2727): Could not store clipboard.
I/ActivityManager(  760): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=2784 uid=10041 gids={50041, 3003, 1028, 1015}
,I/ProviderInstaller( 2683): Installed default security provider GmsCore_OpenSSL
,D/Icing   ( 1331): Loaded CLD2 Version V2.0 - 20141016
,D/ActivityThread( 2784): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
,D/dalvikvm( 2784): GC_CONCURRENT freed 273K, 2% free 16840K/17144K, paused 3ms+2ms, total 15ms
,I/Icing   ( 1331): updateResources: need to parse f{com.google.android.gms}
,D/AndroidRuntime( 2751): Calling main entry com.android.commands.pm.Pm
,D/dalvikvm(  760): GC_EXPLICIT freed 837K, 10% free 26837K/29680K, paused 2ms+4ms, total 55ms
,W/GAV2    ( 2784): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  760): Force stopping com.example.hello appid=10116 user=-1: uninstall pkg
,I/ActivityManager(  760): Killing 2330:com.example.hello/u0a116 (adj 0): stop com.example.hello
,D/Tethering(  760): InitialState.processMessage what=4
,I/wpa_supplicant(  926): wlan0: CTRL-EVENT-TERMINATING 
W/ActivityManager(  760): Force removing ActivityRecord{42f7a6a0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/Tethering(  760): sendTetherStateChangedBroadcast 0, 0, 0
,W/Settings( 1991): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/InputDispatcher(  760): channel '430cae88 com.example.hello/com.example.hello.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  760): channel '430cae88 com.example.hello/com.example.hello.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,D/dalvikvm( 2784): GC_CONCURRENT freed 186K, 2% free 17073K/17288K, paused 2ms+2ms, total 22ms
,W/InputDispatcher(  760): Attempted to unregister already unregistered input channel '430cae88 com.example.hello/com.example.hello.MainActivity (server)'
I/WindowState(  760): WIN DEATH: Window{430cae88 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  760): Skipping PackageSetting{42977a68 com.test.thalitest/10108} due to missing metadata
,D/dalvikvm( 2784): GC_CONCURRENT freed 365K, 3% free 17135K/17532K, paused 1ms+1ms, total 10ms
,W/Settings(  997): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  760): Force stopping com.example.hello appid=10116 user=0: pkg removed
,I/Gmail   ( 2784): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2784): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/GeofencerStateMachine(  997): Ignoring removeGeofence because network location is disabled.
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "sms"
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/LatinIME:LogUtils(  981): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "smsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/Gmail   ( 2784): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2784): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1033): GC_CONCURRENT freed 335K, 3% free 17065K/17428K, paused 1ms+1ms, total 10ms
D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService(  760): removePackageParticipantsLocked: uid=10116 #1
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mmsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  760):   Scheme: "sms"
,W/Binder  (  981): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  981): java.lang.NullPointerException
W/Binder  (  981): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  981): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  981): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  981): 	at dalvik.system.NativeStart.run(Native Method)
,D/dalvikvm( 2636): GC_CONCURRENT freed 378K, 3% free 17130K/17536K, paused 1ms+3ms, total 13ms
W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 2330 uid 10116
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "smsto"
,D/Launcher.Workspace( 1077): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1077): 11683562 - stripEmptyScreens()
,I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/Icing   ( 1331): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/Sidekick_LocationOracleImpl( 2636): Best location was null
,D/dalvikvm(  760): GC_EXPLICIT freed 1742K, 12% free 26134K/29680K, paused 3ms+8ms, total 99ms
,I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  760):   Scheme: "mmsto"
,D/AndroidRuntime( 2751): Shutting down VM
,I/PackageManager(  760): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm( 2751): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 2ms
,D/dalvikvm( 2636): GC_CONCURRENT freed 176K, 2% free 17339K/17548K, paused 2ms+1ms, total 13ms
,W/GCoreFlp(  997): No location to return for getLastLocation()
,W/GCoreFlp(  997): No location to return for getLastLocation()
,D/dalvikvm( 1331): GC_CONCURRENT freed 717K, 4% free 19179K/19928K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 1077): GC_EXPLICIT freed 1359K, 7% free 26094K/27940K, paused 1ms+3ms, total 38ms
,W/GCoreFlp(  997): No location to return for getLastLocation()
,D/dalvikvm( 2636): GC_FOR_ALLOC freed 282K, 3% free 17395K/17772K, paused 18ms, total 18ms
,W/GCoreFlp(  997): No location to return for getLastLocation()
,W/GCoreFlp(  997): No location to return for getLastLocation()
,W/GCoreFlp(  997): No location to return for getLastLocation()
,I/dalvikvm-heap( 2636): Grow heap (frag case) to 17.255MB for 253968-byte allocation
,D/GCM     ( 1011): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/ActivityManager(  760): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,D/dalvikvm( 2636): GC_FOR_ALLOC freed 120K, 3% free 17522K/18024K, paused 25ms, total 26ms
,I/Icing   ( 1331): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/dalvikvm( 2636): GC_FOR_ALLOC freed 21K, 3% free 17525K/18024K, paused 11ms, total 13ms
,I/dalvikvm-heap( 2636): Grow heap (frag case) to 17.633MB for 516112-byte allocation
,D/dalvikvm( 2636): GC_FOR_ALLOC freed 248K, 5% free 17781K/18532K, paused 16ms, total 17ms
,I/Velvet.VelvetNetworkClient( 2636): Network connection not availble
,D/dalvikvm( 2636): GC_CONCURRENT freed 48K, 3% free 18061K/18532K, paused 2ms+2ms, total 16ms
,I/VS.Container( 2636): create_speech_recognizer
,I/ActivityManager(  760): Resuming delayed broadcast
,D/dalvikvm( 2636): No JNI_OnLoad found in /system/lib/libgoogle_hotword_jni.so 0x428456a0, skipping init
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=2841 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
E/Babel_CronetHttpRequestSender( 1991): Http error response 
W/Babel_CronetHttpRequestSender( 1991): Cronet HTTP request failed
W/Babel_RequestWriter( 1991): Error making http request: url https://www.googleapis.com/chat/v1android/conversations/syncrecentconversations?alt=proto
D/dalvikvm( 2636): GC_FOR_ALLOC freed 592K, 6% free 17596K/18532K, paused 11ms, total 12ms
I/dalvikvm-heap( 2636): Grow heap (frag case) to 17.820MB for 640016-byte allocation
D/dalvikvm(  185): GC_EXPLICIT freed 42K, 1% free 16699K/16772K, paused 1ms+1ms, total 15ms
,D/dalvikvm( 2636): GC_FOR_ALLOC freed <1K, 2% free 18221K/18532K, paused 12ms, total 12ms
,D/dalvikvm(  185): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 0ms+1ms, total 13ms
,D/dalvikvm( 2636): GC_CONCURRENT freed 4K, 2% free 18225K/18532K, paused 2ms+1ms, total 12ms
,I/MicroHotwordRecognitionRunner( 2636): Starting hotword detection.
,D/dalvikvm(  185): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+1ms, total 13ms
,I/Babel   ( 1991): connection state changed from CONNECTED to DISCONNECTED
,D/audio_hw_primary(  187): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  187): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  187): Error: ACDB AudProc vol returned = -19
,W/Babel   ( 1991): Failed to get self info. ErrorCode:0
,I/Icing   ( 1331): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/BluetoothManagerService(  760): Message: 20
,D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42fb3710:true
,D/BluetoothAdapter( 2841): 1116027072: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  760): Message: 30
W/ContextImpl( 2841): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/ActivityManager(  760): Killing 1945:com.google.android.email/u0a36 (adj 15): empty #17
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 2841): Adding local MAP profile
D/BluetoothMap( 2841): Create BluetoothMap proxy object
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 2841): LocalBluetoothProfileManager construction complete
W/ContextImpl( 2841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
W/ContextImpl( 2841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
W/ContextImpl( 2841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1376 
,W/ContextImpl( 2841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/DockEventReceiver( 2841): finishStartingService: stopping service
,D/AuthorizationBluetoothService( 1011): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  760): Killing 2501:com.android.chrome/u0a31 (adj 15): empty #17
W/BroadcastQueue(  760): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,I/ActivityManager(  760): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,W/ContextImpl( 2841): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/DockEventReceiver( 2841): finishStartingService: stopping service
D/BluetoothAdapter( 2841): 1116027072: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2841): 1116027072: getState() :  mService = null. Returning STATE_OFF
,D/AuthorizationBluetoothService( 1011): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapter( 2841): 1116027072: getState() :  mService = null. Returning STATE_OFF
W/BroadcastQueue(  760): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
I/ActivityManager(  760): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/SearchController( 2636): #onHotwordDetectorStarted
,D/VoicemailCleanupService(  955): Cleaning up data for package: com.example.hello
I/ActivityManager(  760): Delay finish: com.android.providers.contacts/.PackageIntentReceiver
,E/SharedPreferencesImpl( 1331): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,E/SQLiteLog( 2636): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog(  955): (3850) statement aborts at 22: [DELETE FROM calls WHERE (((source_package = 'com.example.hello'))) AND ((type = 4))] disk I/O error
,W/dalvikvm(  955): threadid=12: thread exiting with uncaught exception (group=0x417edba8)
,E/Icing.InternalIcingCorporaProvider( 2636): Exception thrown from registerCorpora
E/Icing.InternalIcingCorporaProvider( 2636): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:297)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.content.ContentResolver.update(ContentResolver.java:1316)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.os.Looper.loop(Looper.java:136)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Icing.InternalIcingCorporaProvider( 2636): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/Icing.InternalIcingCorporaProvider( 2636): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase.cleanSequenceTable(AppDataSearchDbOpenHelperBase.java:352)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.requestIndexingIfRequired(AppDataSearchProviderBase.java:321)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.gms.ap,pdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:165)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/Icing.InternalIcingCorporaProvider( 2636): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/Icing.InternalIcingCorporaProvider( 2636): 	... 15 more
W/Icing.InternalIcingCorporaProvider( 2636): Corpora registration failed
E/SQLiteLog( 2636): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 2636): threadid=10: thread exiting with uncaught exception (group=0x417edba8)
E/AndroidRuntime(  955): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime(  955): Process: android.process.acore, PID: 955
E/AndroidRuntime(  955): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime(  955): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime(  955): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime(  955): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime(  955): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime(  955): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime(  955): 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:156)
E/AndroidRuntime(  955): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:207)
E/AndroidRuntime(  955): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime(  955): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime(  955): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/AndroidRuntime(  955): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime(  955): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime(  955): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(  955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(  955): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime(  955): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 2636): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2636): Process: com.google.android.googlequicksearchbox:search, PID: 2636
E/AndroidRuntime( 2636): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2636): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2636): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 2636): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2636): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2636): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 2636): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 2636): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 2636): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 2636): 	at android.content.ContentResolver.update(ContentResolver.java:1316)
E/AndroidRuntime( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 2636): 	at com.google.and,roid.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 2636): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 2636): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2636): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2636): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2636): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  760): Can't write: system_app_crash
E/DropBoxManagerService(  760): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  760): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  760): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  760): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  760): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  760): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  760): 	... 5 more
E/DropBoxManagerService(  760): Can't write: system_app_crash
E/DropBoxManagerService(  760): java.io.FileNotFoundException: /data/system/dropbox/drop87.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  760): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  760): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  760): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  760): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  760): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  760): 	... 5 more
,E/qdoverlay(  184): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  184): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  184): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
,E/qdoverlay(  184): src msmfb_img w=2176 h=1920 format=15 MDP_RGBX_8888
E/qdoverlay(  184): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  184): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  184): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  184): src msmfb_img w=2176 h=1920 format=15 MDP_RGBX_8888
E/qdoverlay(  184): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  184): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  184): Ctrl commit failed set overlay
E/qdhwcomposer(  184): configureLowRes: commit failed for low res panel
E/qdoverlay(  184): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  184): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  184): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  184): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  184): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  184): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  184): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  184): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  184): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  184): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  184): Ctrl commit failed set overlay
E/qdhwcomposer(  184): configure: commit fails
E/qdoverlay(  184): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,E/qdoverlay(  184): MdpCtrl close error in unset
,I/SearchController( 2636): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 2636): mic_close
,I/MicroHotwordRecognitionRunner( 2636): Hotword detection finished
,I/MicroHotwordRecognitionRunner( 2636): Stopping hotword detection.
,I/Icing   ( 1331): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,E/qdoverlay(  184): GenericPipe failed to close ctrl
E/qdoverlay(  184): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  184): MdpCtrl close error in unset
E/qdoverlay(  184): GenericPipe failed to close ctrl
E/qdoverlay(  184): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  184): MdpCtrl close error in unset
E/qdoverlay(  184): GenericPipe failed to close ctrl
E/qdoverlay(  184): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  184): MdpCtrl close error in unset

```
