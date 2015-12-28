#### Test 503880191ec81a5_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  776): Killing 1641:com.google.android.videos/u0a70 (adj 15): empty #17
,--------- beginning of /dev/log/main
D/AndroidRuntime( 2397): 
D/AndroidRuntime( 2397): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2397): CheckJNI is OFF
D/dalvikvm( 2397): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2397): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2397): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2397): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2397): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2397): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2397): Calling main entry com.android.commands.am.Am
D/PermissionCache(  181): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (104 us)
I/ActivityManager(  776): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2397
D/dalvikvm(  776): GC_FOR_ALLOC freed 1489K, 11% free 24112K/26952K, paused 41ms, total 41ms
I/dalvikvm-heap(  776): Grow heap (frag case) to 24.395MB for 856096-byte allocation
D/dalvikvm(  776): GC_FOR_ALLOC freed 8K, 11% free 24939K/27792K, paused 38ms, total 38ms
D/dalvikvm(  776): GC_FOR_ALLOC freed 54K, 11% free 24891K/27792K, paused 41ms, total 41ms
I/dalvikvm-heap(  776): Grow heap (frag case) to 25.157MB for 856096-byte allocation
D/dalvikvm(  776): GC_FOR_ALLOC freed <1K, 11% free 25727K/28632K, paused 37ms, total 37ms
D/AndroidRuntime( 2397): Shutting down VM
D/dalvikvm( 2397): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  776): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2417 uid=10116 gids={50116, 3003, 3001, 3002}
I/iu.UploadsManager( 1330): End new media; added: 0, uploading: 0, time: 251 ms
I/SearchController( 1226): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1226): mic_close
V/WebViewChromiumFactoryProvider( 2417): Binding Chromium to main looper Looper (main, tid 1) {425ab500}
I/LibraryLoader( 2417): Expected native library version number "",actual native library version number ""
I/chromium( 2417): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2417): Initializing chromium process, renderers=0
I/ActivityManager(  776): Killing 1847:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
D/BluetoothManagerService(  776): Message: 20
D/BluetoothManagerService(  776): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c343b0:true
I/MicroHotwordRecognitionRunner( 1226): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1226): Stopping hotword detection.
I/Adreno-EGL( 2417): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2417): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2417): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2417): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2417): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2417): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2417): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2417): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2417): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2417): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2417): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2417): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2417): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2417): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2417): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2417): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2417): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2417): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2417): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2417): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2417): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2417): Enabling debug mode 0
,W/AwContents( 2417): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  776): Displayed com.example.hello/.MainActivity: +295ms
,I/ActivityManager(  776): Killing 1865:com.google.android.deskclock/u0a33 (adj 15): empty #17
,E/AndroidProtocolHandler( 2417): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 2417): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 2417): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2417): GC_CONCURRENT freed 216K, 2% free 16893K/17136K, paused 1ms+2ms, total 15ms
,D/dalvikvm( 2417): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x425af7f0
,D/dalvikvm( 2417): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x425af7f0
,D/jxcore_app_log( 2417): JniHelper::setJavaVM(0x41499f00), pthread_self() = 1979025752
,D/JX-Cordova( 2417): jxcore cordova android initializing
,D/dalvikvm( 2417): GC_CONCURRENT freed 227K, 2% free 17127K/17388K, paused 1ms+2ms, total 11ms
,D/dalvikvm( 2417): GC_CONCURRENT freed 364K, 3% free 17211K/17608K, paused 2ms+1ms, total 12ms
,D/AlertService( 1810): Beginning updateAlertNotification
,W/jxcore-log( 2417): Initializing JXcore engine
,W/jxcore-log( 2417): JXcore engine is ready
I/ActivityManager(  776): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2479 uid=10001 gids={50001, 3003, 1028, 1015}
,D/dalvikvm( 2417): GC_CONCURRENT freed 351K, 3% free 17352K/17740K, paused 1ms+2ms, total 11ms
,D/dalvikvm( 2417): WAIT_FOR_CONCURRENT_GC blocked 9ms
,W/jxcore-log( 2417): Starting JXcore engine
,I/CalendarProvider2( 2479): Created com.android.providers.calendar.CalendarAlarmManager@425c5e18(com.android.providers.calendar.CalendarProvider2@425bdad8)
,D/AlertService( 1810): No fired or scheduled alerts
,D/AlertService( 1810): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1810): No events found starting within 1 week.
,W/jxcore-log( 2417): Platform android
W/jxcore-log( 2417): 
,W/jxcore-log( 2417): Process ARCH arm
W/jxcore-log( 2417): 
,I/jxcore-log( 2417): JXcore Cordova bridge is ready!
I/jxcore-log( 2417): 
,W/jxcore-log( 2417): JXcore engine is started
,E/jxcore-log( 2417): >> LGE-Nexus 5
E/jxcore-log( 2417): 
,I/jxcore-log( 2417): Total memory 1945137152
I/jxcore-log( 2417): 
I/jxcore-log( 2417): Free memory 850894848
I/jxcore-log( 2417): 
I/jxcore-log( 2417): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2417): 
,I/jxcore-log( 2417): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2417): 
,I/jxcore-log( 2417): userPath [ 'www' ]
I/jxcore-log( 2417): 
,I/jxcore-log( 2417): Size 1080 1776
I/jxcore-log( 2417): 
,I/jxcore-log( 2417): Screen Brightness 1
I/jxcore-log( 2417): 
,E/jxcore-log( 2417): Dummy Error Log.
E/jxcore-log( 2417): 
,I/jxcore-log( 2417): getBuffer is called!!!!
I/jxcore-log( 2417): 
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "sms"
,I/InputReader(  776): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "smsto"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "mms"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "mmsto"
,I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/Launcher( 1042): Deferring update until onResume
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "sms"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "smsto"
,I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/Launcher( 1042): Deferring update until onResume
,D/dalvikvm( 2417): GC_FOR_ALLOC freed 574K, 5% free 16933K/17768K, paused 7ms, total 7ms
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "mms"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "mmsto"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 2417): GC_CONCURRENT freed 268K, 4% free 17110K/17768K, paused 2ms+1ms, total 10ms
,I/GCoreNlp(  983): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/CalendarProvider2( 2479): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2479): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  776): Resuming delayed broadcast
I/ActivityManager(  776): Killing 1882:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,D/MusicLifecycle( 1482): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@425e5ec0 and intent Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
,D/dalvikvm( 2417): GC_CONCURRENT freed 401K, 4% free 17150K/17768K, paused 1ms+3ms, total 16ms
,I/ActivityManager(  776): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/MusicLifecycle( 1482): com.google.android.music.store.MediaStoreImportService generated event: Service created
,D/dalvikvm( 1482): GC_FOR_ALLOC freed 103K, 3% free 17692K/18128K, paused 10ms, total 10ms
,I/dalvikvm-heap( 1482): Grow heap (frag case) to 17.429MB for 131088-byte allocation
,D/dalvikvm( 1482): GC_FOR_ALLOC freed <1K, 3% free 17820K/18260K, paused 11ms, total 11ms
,D/dalvikvm( 2417): GC_CONCURRENT freed 395K, 4% free 17220K/17768K, paused 2ms+3ms, total 15ms
,D/dalvikvm( 2417): GC_FOR_ALLOC freed 37K, 3% free 17239K/17768K, paused 7ms, total 7ms
,I/dalvikvm-heap( 2417): Grow heap (frag case) to 16.944MB for 87220-byte allocation
,I/MediaStoreImporter( 1482): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/MusicLifecycle( 1482): com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
,I/ActivityManager(  776): Resuming delayed broadcast
D/dalvikvm( 2417): GC_FOR_ALLOC freed 0K, 3% free 17324K/17856K, paused 9ms, total 9ms
,I/ActivityManager(  776): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=2526 uid=10033 gids={50033, 1028}
,D/dalvikvm( 2417): GC_FOR_ALLOC freed 56K, 4% free 17267K/17856K, paused 7ms, total 7ms
,I/dalvikvm-heap( 2417): Grow heap (frag case) to 17.013MB for 130826-byte allocation
,D/dalvikvm( 2417): GC_FOR_ALLOC freed 85K, 4% free 17309K/17984K, paused 10ms, total 10ms
,I/ActivityManager(  776): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Killing 1086:com.android.printspooler/u0a64 (adj 15): empty #17
,D/dalvikvm( 2417): GC_FOR_ALLOC freed <1K, 4% free 17309K/17984K, paused 8ms, total 8ms
,I/dalvikvm-heap( 2417): Grow heap (frag case) to 17.118MB for 196234-byte allocation
I/ActivityManager(  776): Delay finish: com.google.android.gm/.GmailReceiver
,D/dalvikvm( 2417): GC_FOR_ALLOC freed 0K, 4% free 17501K/18176K, paused 9ms, total 9ms
I/ActivityManager(  776): Resuming delayed broadcast
,D/dalvikvm( 2417): GC_FOR_ALLOC freed 127K, 5% free 17373K/18176K, paused 8ms, total 8ms
I/ActivityManager(  776): Delay finish: com.google.android.gm/.GmailReceiver
,D/dalvikvm( 2417): GC_FOR_ALLOC freed 441K, 7% free 17079K/18176K, paused 10ms, total 10ms
I/ActivityManager(  776): Resuming delayed broadcast
I/ActivityManager(  776): Delay finish: com.google.android.gm/.GmailReceiver
,I/NotifUtils( 1900): Validating Notification, mapSize: 1 getAttention: true
,I/NotifUtils( 1900): Unseen count doesn't match cursor count.  unseen: 6 cursor count: 1
,D/dalvikvm( 1900): GC_CONCURRENT freed 372K, 3% free 17347K/17752K, paused 2ms+3ms, total 17ms
,I/NotifUtils( 1900): Showing notification with unreadCount of 14 and unseenCount of 1
,D/dalvikvm( 1900): GC_FOR_ALLOC freed 145K, 3% free 17420K/17836K, paused 9ms, total 9ms
,I/dalvikvm-heap( 1900): Grow heap (frag case) to 17.178MB for 147472-byte allocation
,D/dalvikvm( 1900): GC_FOR_ALLOC freed 0K, 3% free 17564K/17984K, paused 14ms, total 14ms
,I/NotifUtils( 1900): Account: 61035162 vibrate: false
,I/NotifUtils( 1900): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
,I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  776): Resuming delayed broadcast
,D/dalvikvm(  776): GC_FOR_ALLOC freed 897K, 7% free 26744K/28624K, paused 38ms, total 38ms
I/ActivityManager(  776): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,W/GCoreFlp(  983): No location to return for getLastLocation()
,W/FusedLocationProvider(  983): location=null
,D/dalvikvm( 1330): GC_CONCURRENT freed 589K, 4% free 18784K/19436K, paused 3ms+3ms, total 19ms
,I/ActivityManager(  776): Resuming delayed broadcast
,D/dalvikvm( 1126): GC_CONCURRENT freed 404K, 3% free 17990K/18524K, paused 3ms+3ms, total 30ms
,I/ActivityManager(  776): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver: pid=2558 uid=10063 gids={50063, 3003, 3002, 1028, 1015}
,D/CaptivePortalTracker(  776): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  776): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  776): Checking http://216.58.209.46/generate_204
W/ActivityThread(  776): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker(  776): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  776): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  776): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  776): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  776): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,E/dalvikvm( 2558): Could not find class 'android.app.Notification$Action$Builder', referenced from method efj.a
W/dalvikvm( 2558): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lefj;
,D/dalvikvm( 2558): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 2558): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method efj.a
,W/dalvikvm( 2558): VFY: unable to resolve new-instance 575 (Landroid/graphics/drawable/RippleDrawable;) in Lefj;
,D/dalvikvm( 2558): VFY: replacing opcode 0x22 at 0x000b
,E/dalvikvm( 2558): Could not find class 'android.app.Notification$Action$Builder', referenced from method efj.a
,W/dalvikvm( 2558): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lefj;
,D/dalvikvm( 2558): VFY: replacing opcode 0x22 at 0x0000
,D/dalvikvm( 2558): GC_CONCURRENT freed 208K, 2% free 16927K/17164K, paused 2ms+1ms, total 15ms
,W/dalvikvm( 2558): Unable to resolve superclass of Lcm; (800)
,W/dalvikvm( 2558): Link of class 'Lcm;' failed
E/dalvikvm( 2558): Could not find class 'cm', referenced from method efj.a
W/dalvikvm( 2558): VFY: unable to resolve new-instance 2378 (Lcm;) in Lefj;
,D/dalvikvm( 2558): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 2558): Unable to resolve superclass of Lco; (800)
W/dalvikvm( 2558): Link of class 'Lco;' failed
E/dalvikvm( 2558): Could not find class 'co', referenced from method efj.a
W/dalvikvm( 2558): VFY: unable to resolve new-instance 2432 (Lco;) in Lefj;
D/dalvikvm( 2558): VFY: replacing opcode 0x22 at 0x002c
,I/dalvikvm( 2558): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method efj.a
W/dalvikvm( 2558): VFY: unable to resolve virtual method 5224: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2558): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 2558): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method efj.a
W/dalvikvm( 2558): VFY: unable to resolve virtual method 5756: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 2558): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 2558): Could not find method android.view.View.getTransitionName, referenced from method efj.a
W/dalvikvm( 2558): VFY: unable to resolve virtual method 5560: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 2558): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 2558): VFY: unable to find class referenced in signature (Lx;)
,I/dalvikvm( 2558): Could not find method android.transition.Transition.getTargetNames, referenced from method efj.a
W/dalvikvm( 2558): VFY: unable to resolve virtual method 5213: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 2558): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 2558): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method efj.a
W/dalvikvm( 2558): VFY: unable to resolve interface method 5806: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 2558): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2558): Could not find method android.view.ViewParent.onNestedFling, referenced from method efj.a
W/dalvikvm( 2558): VFY: unable to resolve interface method 5805: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
,D/dalvikvm( 2558): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2558): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method efj.a
W/dalvikvm( 2558): VFY: unable to resolve interface method 5807: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 2558): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 2558): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 2558): Could not find class 'android.app.RemoteInput[]', referenced from method efj.a
W/dalvikvm( 2558): VFY: unable to resolve new-array 13337 ([Landroid/app/RemoteInput;) in Lefj;
,D/dalvikvm( 2558): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 2558): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method efj.b
,W/dalvikvm( 2558): VFY: unable to resolve virtual method 5224: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2558): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 2558): VFY: unable to find class referenced in signature (Lx;)
,D/dalvikvm( 2558): DexOpt: unable to opt direct call 0x09c0 at 0x0e in Lefj;.a
,D/dalvikvm( 2558): DexOpt: unable to opt direct call 0x0d49 at 0x0e in Lefj;.a
,D/dalvikvm( 2558): DexOpt: unable to opt direct call 0x09c0 at 0x0e in Lefj;.a
W/dalvikvm( 2558): Unable to resolve superclass of Lcm; (800)
W/dalvikvm( 2558): Link of class 'Lcm;' failed
D/dalvikvm( 2558): DexOpt: unable to opt direct call 0x39db at 0x08 in Lefj;.a
W/dalvikvm( 2558): Unable to resolve superclass of Lco; (800)
W/dalvikvm( 2558): Link of class 'Lco;' failed
,D/dalvikvm( 2558): DexOpt: unable to opt direct call 0x3b51 at 0x30 in Lefj;.a
,D/dalvikvm( 2558): DexOpt: unable to opt direct call 0x0a18 at 0x13 in Lefj;.a
,D/dalvikvm( 2558): GC_CONCURRENT freed 374K, 3% free 17054K/17456K, paused 2ms+10ms, total 26ms
,D/dalvikvm( 2558): GC_CONCURRENT freed 286K, 2% free 17267K/17580K, paused 4ms+8ms, total 46ms
,I/dalvikvm( 2558): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eer.a
W/dalvikvm( 2558): VFY: unable to resolve virtual method 2532: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2558): VFY: replacing opcode 0x6e at 0x023c
,I/dalvikvm( 2558): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eer.a
W/dalvikvm( 2558): VFY: unable to resolve virtual method 2906: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2558): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 2558): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eer.c
W/dalvikvm( 2558): VFY: unable to resolve virtual method 2532: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2558): VFY: replacing opcode 0x6e at 0x0207
,D/dalvikvm( 2558): Trying to load lib /data/app-lib/com.google.android.apps.plus-2/libcrashreporterer.so 0x425b79a0
,D/dalvikvm( 2558): Added shared lib /data/app-lib/com.google.android.apps.plus-2/libcrashreporterer.so 0x425b79a0
,D/dalvikvm( 2558): GC_CONCURRENT freed 251K, 2% free 17487K/17760K, paused 2ms+3ms, total 20ms
,I/CheckinService( 1330): Checkin interval check for package: unspecified last checkin: 1451341424468 min interval config: 0 actual interval: 7345
,I/SystemUpdateService( 1330): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1330): onCreate
I/CheckinService( 1330): Checking schedule, now: 1451341431817 next: 1451383913441
,I/CheckinService( 1330): active receiver: disabled
,D/SystemUpdateService( 1330): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1330): active receiver: enabled
,I/SystemUpdateService( 1330): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1330): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1330): now status is 0 (complete)
I/SystemUpdateService( 1330): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1330): file has been verified
,I/SystemUpdateService( 1330): OTA package size = 2571501
,I/SystemUpdateService( 1330): showing system update notification
,I/iu.SyncManager( 1330): SYNC; picasa accounts
,D/NetworkLogImpl( 1330): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1330): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1330): num queued entries: 0
,I/iu.UploadsManager( 1330): num updated entries: 0
,D/SystemUpdateService( 1330): onDestroy
,I/iu.SyncManager( 1330): NEXT; no task
,I/ActivityManager(  776): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=2597 uid=10031 gids={50031, 3003, 1028, 1015}
,D/dalvikvm( 2091): GC_CONCURRENT freed 1426K, 7% free 22413K/23872K, paused 2ms+2ms, total 34ms
,D/dalvikvm( 2091): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/Babel   ( 2091): connection state changed from UNKNOWN to CONNECTED
,D/dalvikvm( 2597): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2597): VFY: unable to resolve instance field 68
D/dalvikvm( 2597): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 2597): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2597): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2597): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2597): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2597): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2597): VFY: unable to resolve instance field 68
,D/dalvikvm( 2597): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 2597): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2597): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2597): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2597): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2597): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2597): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,V/AlarmClock( 2526): AlarmInitReceiver android.intent.action.TIME_SET
I/ActivityManager(  776): Killing 1064:com.google.android.keep/u0a52 (adj 15): empty #17
,D/dalvikvm( 1810): GC_CONCURRENT freed 293K, 2% free 16796K/17120K, paused 3ms+1ms, total 16ms
,I/AlarmClock( 2526): Displaying next alarm time: ''
,V/AlarmClock( 2526): AlarmInitReceiver finished
,I/ActivityManager(  776): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2622 uid=10052 gids={50052, 3003, 1028, 1015}
,D/dalvikvm( 2622): GC_CONCURRENT freed 193K, 2% free 16924K/17148K, paused 2ms+1ms, total 17ms
I/ActivityManager(  776): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2637 uid=10068 gids={50068}
,D/dalvikvm( 2637): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x425b5d40, skipping init
D/TimeService( 2637): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1451341432226
D/        ( 2637): TimeServiceNative: User Time to be set is 1451341432226
D/QC-time-services( 2637): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2637): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2637): Lib:time_genoff_operation: pargs->ts_val = 1451341432226
,D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1451341432226
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1451341432226, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/17/71 16:28:54
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 35656134000
D/QC-time-services(  197): Daemon:new time 1451341432226 
D/QC-time-services(  197): Daemon: delta 1415685298226 genoff 1415685298226 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1415685298226 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services( 2637): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1415685298226 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  197): Daemon:Update to modem bit set
D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1135376632226
,E/QC-time-services( 2637): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager(  776): Killing 1932:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
I/ActivityManager(  776): Killing 2075:com.google.android.exchange/u0a37 (adj 15): empty #17
,I/CheckinService( 1330): Checkin interval check for package: unspecified last checkin: 1451341424468 min interval config: 0 actual interval: 7782
,D/WearableService(  983): callingUid 10007, callindPid: 983
,D/LocationInitializer( 1330): Restart initialization of location
,E/MDM     (  983): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1126): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1126): Proximity feature is not enabled.
,V/GLSActivity( 1126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  776): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,W/GCoreFlp(  983): No location to return for getLastLocation()
,W/FusedLocationProvider(  983): location=null
I/ActivityManager(  776): Resuming delayed broadcast
I/ActivityManager(  776): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  776): Resuming delayed broadcast
,D/ConnectivityService(  776): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ActivityManager(  776): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/dalvikvm( 2091): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2091): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2091): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2091): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2091): VFY: unable to resolve instance field 36
D/dalvikvm( 2091): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2091): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2091): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2091): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2091): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2091): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2091): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427273b8
D/dalvikvm( 2091): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427273b8
,D/dalvikvm( 2091): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427273b8, skipping init
D/dalvikvm( 2091): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427273b8
,D/dalvikvm( 2091): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427273b8
V/JNIHelp ( 2091): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MusicLifecycle( 1482): com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@425e5ec0 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,D/MusicLifecycle( 1482): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
I/ActivityManager(  776): Resuming delayed broadcast
I/ActivityManager(  776): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,D/MusicLifecycle( 1482): com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,D/MusicLifecycle( 1482): com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,D/MusicLifecycle( 1482): com.google.android.music.download.cache.TrackCacheService generated event: Service created
I/MusicLeanback( 1482): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 1482): Stop autocaching.
,D/MusicLifecycle( 1482): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@425e5ec0 and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
I/ActivityManager(  776): Resuming delayed broadcast
,D/dalvikvm( 2091): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427273b8
,D/dalvikvm( 2091): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x427273b8
D/dalvikvm( 2091): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427273b8
,D/dalvikvm( 2091): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427273b8
,D/MusicLifecycle( 1482): com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,D/MusicLifecycle( 1482): com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,D/MusicLifecycle( 1482): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,I/ActivityManager(  776): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
D/MusicLifecycle( 1482): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,E/GmsUtils( 1482): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/GmsUtils( 1482): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/MusicLifecycle( 1482): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
I/ActivityManager(  776): Resuming delayed broadcast
,D/GCM     ( 1126): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ProviderInstaller( 2091): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  776): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2670 uid=10011 gids={50011, 3003}
,I/ActivityManager(  776): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2686 uid=10013 gids={50013, 3003, 3002}
,D/dalvikvm(  776): GC_EXPLICIT freed 1404K, 8% free 26751K/29068K, paused 1ms+4ms, total 47ms
I/ActivityManager(  776): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2701 uid=10014 gids={50014, 3003, 1028, 1015}
,I/ActivityManager(  776): Killing 2156:com.google.android.apps.maps/u0a57 (adj 15): empty #17
,D/Finsky  ( 2701): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 2701): GC_CONCURRENT freed 250K, 2% free 16887K/17168K, paused 2ms+1ms, total 14ms
,D/Finsky  ( 2701): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 2701): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2701): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 2701): GC_CONCURRENT freed 282K, 2% free 17073K/17384K, paused 2ms+2ms, total 15ms
,D/Finsky  ( 2701): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2701): [1] 2.run: Finished loading 1 libraries.
,I/Icing.InternalIcingCorporaProvider( 1226): Updating corpora: A: com.example.hello, C: MAYBE
I/ActivityManager(  776): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 2701): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  776): Delaying start of: ServiceRecord{42f72880 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,I/Icing.InternalIcingCorporaProvider( 1226): UpdateCorporaTask done [took 91 ms] updated apps [took 90 ms] 
,D/Finsky  ( 2701): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Killing 2192:com.google.android.youtube/u0a71 (adj 15): empty #17
,D/ChimeraCfgMgr( 1330): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1330): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1330): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/dalvikvm( 1330): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
,W/dalvikvm( 1330): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1330): VFY: replacing opcode 0x6e at 0x0053
,D/dalvikvm( 1330): GC_CONCURRENT freed 579K, 4% free 18820K/19436K, paused 3ms+11ms, total 39ms
,F/ActivityManager(  776): Service ServiceRecord{42d569a0 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42bbacd0 2192:com.google.android.youtube/u0a71} not same as in map: null
,I/dalvikvm( 1330): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1330): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1330): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1330): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1330): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1330): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1330): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1330): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1330): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1330): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1330): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1330): Submit a task: k
,D/ChimeraCfgMgr( 1330): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/BaseAppContext( 1330): Using Auth Proxy for data requests.
,W/BaseAppContext( 1330): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1330): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1330): Processing package: com.example.hello
,D/GassUtils( 1330): Found app info for package com.example.hello:18. Hash: 7e411fc8c80adb766ff5747826a81d96c76dd9cb2b76f4f040d3bd27a68f585b
,D/k       ( 1330): Found info for package com.example.hello in db.
,I/ActivityManager(  776): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2757 uid=10035 gids={50035, 1028, 3003, 1015}
,D/dalvikvm(  182): GC_EXPLICIT freed 42K, 1% free 16699K/16772K, paused 1ms+2ms, total 14ms
,W/BaseAppContext( 1330): Using Auth Proxy for data requests.
,D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 0ms+2ms, total 11ms
,D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+1ms, total 14ms
,W/BaseAppContext( 1330): Using Auth Proxy for data requests.
,W/BaseAppContext( 1330): Using Auth Proxy for data requests.
,W/BaseAppContext( 1330): Using Auth Proxy for data requests.
,D/dalvikvm( 1330): GC_CONCURRENT freed 499K, 3% free 18966K/19464K, paused 3ms+2ms, total 25ms
,W/BaseAppContext( 1330): Using Auth Proxy for data requests.
,W/dalvikvm( 1330): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1330): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1330): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1330): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1330): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1330): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1330): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1330): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1330): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1330): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1330): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1330): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1330): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1330): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1330): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1330): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1330): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1330): cleanUpNonGplusAccounts done.
,D/dalvikvm( 2757): GC_CONCURRENT freed 320K, 3% free 16875K/17228K, paused 2ms+2ms, total 16ms
,D/dalvikvm( 2757): GC_CONCURRENT freed 300K, 2% free 17075K/17396K, paused 5ms+4ms, total 22ms
,D/dalvikvm( 1330): GC_CONCURRENT freed 495K, 3% free 19212K/19740K, paused 3ms+3ms, total 36ms
,W/dalvikvm( 1330): VFY: unable to find class referenced in signature (Landroid/util/Size;)
I/dalvikvm( 2757): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gqa.a
W/dalvikvm( 2757): VFY: unable to resolve virtual method 1798: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2757): VFY: replacing opcode 0x6e at 0x000f
,I/GAv4    ( 2757): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2757):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2757):   adb logcat -s GAv4
D/ChimeraCfgMgr( 1330): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1330): Module APK com.google.android.play.games already loaded
,W/GAv4    ( 2757): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dalvikvm( 2757): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 2757): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 2757): VFY: replacing opcode 0x6e at 0x001b
,D/dalvikvm( 2757): GC_CONCURRENT freed 332K, 2% free 17326K/17596K, paused 1ms+0ms, total 14ms
,W/GAv4    ( 2757): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2757): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 2757): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.35, sample rate 1.0
,I/dalvikvm( 2757): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
,W/dalvikvm( 2757): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
,D/dalvikvm( 2757): VFY: replacing opcode 0x71 at 0x0075
,D/dalvikvm( 2757): GC_CONCURRENT freed 398K, 2% free 17484K/17828K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 2757): GC_CONCURRENT freed 295K, 2% free 17670K/17996K, paused 2ms+2ms, total 14ms
,I/ActivityManager(  776): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2797 uid=10065 gids={50065, 3003, 1028, 1015}
,I/ActivityManager(  776): Killing 2335:com.android.settings/1000 (adj 15): empty #17
,D/dalvikvm( 2757): GC_CONCURRENT freed 289K, 2% free 17802K/18120K, paused 3ms+1ms, total 17ms
,D/dalvikvm( 2757): GC_CONCURRENT freed 375K, 3% free 17894K/18300K, paused 1ms+3ms, total 15ms
,D/dalvikvm( 2757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2757): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2757): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2757): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2757): VFY: unable to resolve instance field 36
,D/dalvikvm( 2757): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2757): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 2757): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2757): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2757): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 2757): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4272e368
D/dalvikvm( 2757): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4272e368
,D/dalvikvm( 2757): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4272e368, skipping init
,D/dalvikvm( 2757): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4272e368
D/dalvikvm( 2757): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4272e368
,V/JNIHelp ( 2757): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 2757): GC_CONCURRENT freed 406K, 3% free 17956K/18396K, paused 2ms+2ms, total 15ms
,D/dalvikvm( 2757): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4272e368
,D/dalvikvm( 2757): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4272e368
D/dalvikvm( 2757): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4272e368
,D/dalvikvm( 2757): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4272e368
,D/dalvikvm( 2757): GC_FOR_ALLOC freed 94K, 3% free 18054K/18436K, paused 12ms, total 12ms
,W/Quickoffice( 2797): Cleanup of storage: done
,D/com.google.android.apps.docs.quickoffice.X( 2797): Loading recent documents list
,D/Quickoffice( 2797): The number of lines present in  /proc/mount 21
,D/Quickoffice( 2797): Parsing the storagedefinition.xml.
D/Quickoffice( 2797): # of Storagedefinitions - 35
D/Quickoffice( 2797): The # of storage definitions available - 35
,D/Quickoffice( 2797): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2797): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2797): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2797): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
,D/Quickoffice( 2797): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2797): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2797): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
,D/Quickoffice( 2797): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2797): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2797): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2797): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
,D/Quickoffice( 2797): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2797): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2797): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
,D/Quickoffice( 2797): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2797): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
,D/Quickoffice( 2797): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2797): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2797): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
,D/Quickoffice( 2797): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2797): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
,D/Quickoffice( 2797): Build properties are not configured for this storage definition.
,I/ProviderInstaller( 2757): Installed default security provider GmsCore_OpenSSL
,D/Quickoffice( 2797): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
,D/Quickoffice( 2797): The # of mounts identified -  1
,D/dalvikvm( 2797): GC_CONCURRENT freed 211K, 2% free 16934K/17176K, paused 3ms+4ms, total 18ms
I/ActivityManager(  776): Killing 2107:com.google.android.gms.unstable/u0a7 (adj 15): empty #17
,I/ActivityManager(  776): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,D/com.google.android.apps.docs.quickoffice.X( 2797): Checking validity of 0 items
D/ContentResolverUtil( 2797): There are 0 persisted uri permissions.
,D/com.google.android.apps.docs.quickoffice.X( 2797): 0 items were valid
W/ActivityManager(  776): No permission grants found for com.quickoffice.android
I/ActivityManager(  776): Resuming delayed broadcast
,I/Icing.InternalIcingCorporaProvider( 1226): Updating corpora: A: com.google.android.gms, C: MAYBE
I/ActivityManager(  776): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,W/Quickoffice( 2797): Could not load clipboard.
,W/Quickoffice( 2797): Could not store clipboard.
,I/Icing   ( 1330): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/dalvikvm( 1226): GC_CONCURRENT freed 1158K, 7% free 17951K/19140K, paused 1ms+1ms, total 15ms
,I/Icing   ( 1330): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/ActivityManager(  776): Waited long enough for: ServiceRecord{42ce5b20 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,W/Launcher( 1042): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@425baa80 new=com.google.android.velvet.VelvetApplication@425baa80
I/ActivityManager(  776): Resuming delayed broadcast
I/ActivityManager(  776): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,D/AlertReceiver( 1810): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
,D/AlertService( 1810): 0 Action = android.intent.action.PROVIDER_CHANGED
I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
D/PackageBroadcastService( 1330): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1330): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1330): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1330): GC_CONCURRENT freed 733K, 4% free 19353K/20056K, paused 2ms+3ms, total 33ms
,I/Icing.InternalIcingCorporaProvider( 1226): UpdateCorporaTask done [took 286 ms] updated apps [took 286 ms] 
I/ActivityManager(  776): Resuming delayed broadcast
I/ActivityManager(  776): Killing 1900:com.google.android.gm/u0a41 (adj 15): empty #17
,D/MusicLifecycle( 1482): com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@425e5ec0 and intent Intent { act=com.google.android.music.IMPORT_COMPLETE flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,D/dalvikvm( 1126): GC_EXPLICIT freed 256K, 3% free 18016K/18524K, paused 1ms+2ms, total 21ms
,I/ActivityManager(  776): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
,D/MusicLifecycle( 1482): com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,D/MusicLifecycle( 1482): com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,E/GmsUtils( 1482): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/GmsUtils( 1482): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  776): Resuming delayed broadcast
,D/MusicLifecycle( 1482): com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,D/dalvikvm( 1482): GC_CONCURRENT freed 316K, 3% free 17915K/18316K, paused 1ms+4ms, total 17ms
I/ActivityManager(  776): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=2837 uid=10041 gids={50041, 3003, 1028, 1015}
,I/Icing   ( 1330): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/ActivityThread( 2837): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
,D/dalvikvm( 2837): GC_CONCURRENT freed 283K, 2% free 16900K/17208K, paused 2ms+2ms, total 19ms
,W/GAV2    ( 2837): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 1330): GC_CONCURRENT freed 753K, 4% free 19403K/20184K, paused 2ms+6ms, total 29ms
,I/Icing   ( 1330): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/ActivityManager(  776): Killing 2044:com.google.android.email/u0a36 (adj 15): empty #17
,D/dalvikvm( 2837): GC_CONCURRENT freed 343K, 3% free 17012K/17384K, paused 1ms+1ms, total 15ms
,I/Gmail   ( 2837): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2837): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/dalvikvm( 2837): GC_CONCURRENT freed 315K, 2% free 17175K/17516K, paused 1ms+4ms, total 19ms
,I/Gmail   ( 2837): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2837): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/GCM     ( 1126): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  776): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Waited long enough for: ServiceRecord{42b392f0 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,D/BluetoothManagerService(  776): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  776): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42bb8fa8 mBinding = false
,D/BluetoothManagerService(  776): Message: 2
,D/BluetoothManagerService(  776): Sending off request.
,D/BluetoothAdapterState( 1549): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1549): Setting state to 13
,I/BluetoothAdapterState( 1549): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1549): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  776): Message: 60
D/BluetoothManagerService(  776): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  776): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothAdapterProperties( 1549): onBluetoothDisable()
,I/BluetoothAdapterProperties( 1549): adapterPropertyChangedCallback with type:7 len:4
,I/BluetoothAdapterState( 1549): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiService(  776): setWifiEnabled: false pid=2417, uid=10116
,D/BluetoothMapService( 1549): onReceive
,D/BluetoothMapService( 1549): STATE_TURNING_OFF
,D/BluetoothMapService( 1549): MAP Service closeService in
,E/bt-btif ( 1549): bta_jv_rfcomm_stop_server
,I/BtOppRfcommListener( 1549): stopping Accept Thread
,E/BtOppRfcommListener( 1549): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 1549): bta_jv_rfcomm_stop_server
,I/BtOppRfcommListener( 1549): BluetoothSocket listen thread finished
,D/BluetoothAdapterProperties( 1549): Scan Mode:20
,D/BluetoothAdapterState( 1549): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 1549): bta_jv_rfcomm_stop_server
W/bt-btif ( 1549): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 1549): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1549): L2CAP - PSM: 0x0017 not found for deregistration
,D/btif_config_util( 1549): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  776): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=2870 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
I/jxcore-log( 2417): ****TEST TOOK:  5092  ms ****
I/jxcore-log( 2417): 
I/jxcore-log( 2417): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2417): 
,D/CommandListener(  178): Clearing all IP addresses on wlan0
D/ConnectivityService(  776): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  776): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  776): Attempting to switch to mobile
,D/ConnectivityService(  776): Attempting to switch to BLUETOOTH_TETHER
,E/WifiStateMachine(  776): scanCount==0 - aborting
,D/NetUtils(  776): android_net_utils_resetConnections in env=0x760ab4d0 clazz=0x3df00001 iface=wlan0 mask=0x3
,D/ConnectivityService(  776): resetConnections(wlan0, 3)
V/NativeCrypto( 1126): Read error: ssl=0x78c30538: I/O error during system call, Connection timed out
,V/NativeCrypto( 1126): SSL shutdown failed: ssl=0x78c30538: I/O error during system call, Broken pipe
,W/ContextImpl( 2870): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  776): Message: 20
,D/BluetoothManagerService(  776): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@429a2bb8:true
,D/BluetoothManagerService(  776): Message: 30
,D/BluetoothManagerService(  776): Message: 30
,D/LocalBluetoothProfileManager( 2870): Adding local MAP profile
,D/BluetoothMap( 2870): Create BluetoothMap proxy object
,D/BluetoothManagerService(  776): Message: 30
W/ContextImpl( 2870): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
W/ContextImpl( 2870): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
,W/ContextImpl( 2870): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1376 
,D/BluetoothManagerService(  776): Message: 30
,D/CommandListener(  178): Clearing all IP addresses on wlan0
W/ContextImpl( 2870): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/LocalBluetoothProfileManager( 2870): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 2870): finishStartingService: stopping service
,W/bt-btif ( 1549): ag scb idx 1 not allocated
E/bt-btif ( 1549): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1549): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1549): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1549): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1549): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1549): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1549): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_hwcfg( 1549): hw_epilog_process
,D/Nat464Xlat(  776): requiresClat: netType=1, hasIPv4Address=false
,D/bt_hwcfg( 1549): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 1549): bt_hc_worker_thread exiting
W/bt_userial( 1549): select_read return size <=0:-1, exiting userial_read_thread
,I/bt_userial_vendor( 1549): device fd = 65 close
,D/ConnectivityService(  776): handleInetConditionChange: no active default network - ignore
D/BTSNOOP-DISP( 1549): btsnoop_close
I/GKI_LINUX( 1549): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1549): GKI_exit_task: GKI_exit_task 0 done
I/GKI_LINUX( 1549): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 1549): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1549): Received stop request...Stopping profile...
,D/BluetoothHeadset( 1003): Proxy object disconnected
D/BluetoothHeadset( 1003): Proxy object disconnected
,D/BluetoothHeadset(  776): Proxy object disconnected
,D/BluetoothHeadset( 1003): Proxy object disconnected
,D/A2dpService( 1549): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1549): Exit Disconnected: -1
D/BluetoothAdapterState( 1549): Stopping profile services that were post enabled
,D/BluetoothA2dp(  776): Proxy object disconnected
,D/HidService( 1549): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1549): Profile still running: com.android.bluetooth.hdp.HealthService
,D/HealthService( 1549): Received stop request...Stopping profile...
W/BluetoothHeadsetServiceJni( 1549): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1549): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 1549): Received stop request...Stopping profile...
D/BluetoothTethering(  776): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering(  776): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  776): BluetoothPAN Proxy object disconnected
,D/BtGatt.DebugUtils( 1549): handleDebugAction() action=null
D/BtGatt.GattService( 1549): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1549): stop()
D/BluetoothMapService( 1549): Received stop request...Stopping profile...
,D/BluetoothMapService( 1549): stop()
D/BluetoothMapService( 1549): MAP Service closeService in
,D/BluetoothAdapterService( 1549): Profile still running: com.android.bluetooth.hdp.HealthService
I/GKI_LINUX( 1549): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1549): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 1549): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService( 1549): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1549): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1549): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1549): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1549): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 1549): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1549): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 1549): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1549): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1549): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 1549): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 1549): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1549): Setting state to 10
I/BluetoothAdapterState( 1549): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 1549): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  776): Message: 60
D/BluetoothManagerService(  776): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
I/BluetoothAdapterState( 1549): Entering OffState
D/BluetoothManagerService(  776): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothMapService( 1549): cleanup()
D/BluetoothMapService( 1549): MAP Service closeService in
D/BluetoothHeadset(  776): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  776): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1003): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1003): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1003): onBluetoothStateChange: up=false
,D/BluetoothPbap( 2870): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 2870): onBluetoothStateChange: up=false
,D/BluetoothMap( 2870): onBluetoothStateChange: up=false
D/BluetoothManagerService(  776): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  776): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  776): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42bb8fa8 mBinding = false
,D/BluetoothManagerService(  776): Sending unbind request.
,D/BluetoothManagerService(  776): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapterService( 1549): Cleaning up adapter native....
I/GKI_LINUX( 1549): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1549): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1549): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 1549): cleanupNative: return from cleanup
D/BluetoothAdapter(  869): 1113791936: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapterService( 1549): Done cleaning up adapter native....
,D/BluetoothAdapterService(1113311784)( 1549): ****onDestroy()********
D/BtGatt.GattService( 1549): cleanup()
W/bt-btif ( 1549): GATTC Module not enabled/already disabled
,W/bt-btif ( 1549): GATTS Module not enabled/already disabled
,D/BluetoothAdapter(  983): 1114836488: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  983): 1114836488: getState() :  mService = null. Returning STATE_OFF
,D/dalvikvm(  776): GC_EXPLICIT freed 865K, 9% free 26739K/29068K, paused 1ms+5ms, total 66ms
,D/AuthorizationBluetoothService( 1126): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  776): Killing 2597:com.android.chrome/u0a31 (adj 15): empty #17
I/ActivityManager(  776): Killing 2622:com.google.android.keep/u0a52 (adj 15): empty #17
W/BroadcastQueue(  776): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,I/ActivityManager(  776): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2903 uid=10052 gids={50052, 3003, 1028, 1015}
I/wpa_supplicant(  952): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant(  952): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/AndroidRuntime( 2883): 
D/AndroidRuntime( 2883): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2883): CheckJNI is OFF
,D/dalvikvm( 2883): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 2883): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2883): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2883): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 2883): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 2883): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,D/dalvikvm( 2903): GC_CONCURRENT freed 179K, 2% free 16922K/17136K, paused 6ms+2ms, total 18ms
,W/ContextImpl( 2870): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 2870): finishStartingService: stopping service
,D/BluetoothAdapter( 2870): 1113323240: getState() :  mService = null. Returning STATE_OFF
,D/AuthorizationBluetoothService( 1126): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  776): Killing 2637:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
W/BroadcastQueue(  776): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,I/Icing   ( 1330): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,I/Icing   ( 1330): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/Icing   ( 1330): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/AndroidRuntime( 2883): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  776): Force stopping com.example.hello appid=10116 user=-1: uninstall pkg
,I/ActivityManager(  776): Killing 2417:com.example.hello/u0a116 (adj 0): stop com.example.hello
,I/wpa_supplicant(  952): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  776): InitialState.processMessage what=4
W/ActivityManager(  776): Force removing ActivityRecord{42cda8b0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/WindowState(  776): WIN DEATH: Window{42c199f0 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  776): Skipping PackageSetting{42669928 com.test.thalitest/10108} due to missing metadata
,D/Tethering(  776): sendTetherStateChangedBroadcast 0, 0, 0
I/ActivityManager(  776): Force stopping com.example.hello appid=10116 user=0: pkg removed
,W/Settings( 2091): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/GeofencerStateMachine(  983): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  776): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "sms"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1003): GC_CONCURRENT freed 334K, 3% free 17065K/17428K, paused 1ms+1ms, total 9ms
,I/LatinIME:LogUtils(  971): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
,W/Settings(  983): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "smsto"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/VoicemailCleanupService(  937): Cleaning up data for package: com.example.hello
,I/Icing   ( 1330): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,D/BackupManagerService(  776): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  776): removePackageParticipantsLocked: uid=10116 #1
,I/ActivityManager(  776): Delay finish: com.android.musicfx/.Compatibility$Receiver
I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "mms"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "mmsto"
,I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm(  776): GC_EXPLICIT freed 1656K, 11% free 25987K/29068K, paused 2ms+7ms, total 90ms
,D/AndroidRuntime( 2883): Shutting down VM
,D/dalvikvm( 2883): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+1ms, total 2ms
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "sms"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/ActivityManager(  776): Resuming delayed broadcast
I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "smsto"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "mms"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  776):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  776):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  776):   Scheme: "mmsto"
I/PackageManager(  776): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/Icing.InternalIcingCorporaProvider( 1226): Updating corpora: A: com.example.hello, C: MAYBE
,D/dalvikvm( 1226): GC_CONCURRENT freed 377K, 6% free 18085K/19140K, paused 1ms+1ms, total 15ms
,W/Launcher( 1042): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@425baa80 new=com.google.android.velvet.VelvetApplication@425baa80
,D/Launcher.Workspace( 1042): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1042): 11683562 - stripEmptyScreens()
,W/Sidekick_LocationOracleImpl( 1226): Best location was null
I/ActivityManager(  776): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2939 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,W/InputMethodManagerService(  776): Got RemoteException sending setActive(false) notification to pid 2417 uid 10116
W/Binder  (  971): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  971): java.lang.NullPointerException
W/Binder  (  971): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  971): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  971): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  971): 	at dalvik.system.NativeStart.run(Native Method)
,W/GCoreFlp(  983): No location to return for getLastLocation()
,I/Icing.InternalIcingCorporaProvider( 1226): UpdateCorporaTask done [took 70 ms] updated apps [took 70 ms] 
,W/GCoreFlp(  983): No location to return for getLastLocation()
,W/GCoreFlp(  983): No location to return for getLastLocation()
,W/GCoreFlp(  983): No location to return for getLastLocation()
W/ContextImpl( 2939): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
I/ActivityManager(  776): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,W/GCoreFlp(  983): No location to return for getLastLocation()
,W/GCoreFlp(  983): No location to return for getLastLocation()
I/ActivityManager(  776): Resuming delayed broadcast
,I/ActivityManager(  776): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/Velvet.VelvetNetworkClient( 1226): Network connection not availble
I/ActivityManager(  776): Resuming delayed broadcast
,D/dalvikvm( 1226): GC_FOR_ALLOC freed 235K, 7% free 17934K/19140K, paused 12ms, total 12ms
,I/dalvikvm-heap( 1226): Grow heap (frag case) to 18.150MB for 640016-byte allocation
,D/PackageBroadcastService( 1330): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1330): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1330): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1330): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1330): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1330): Module APK com.google.android.play.games already loaded
,D/dalvikvm(  983): GC_CONCURRENT freed 491K, 4% free 18681K/19268K, paused 3ms+6ms, total 28ms
D/dalvikvm( 1226): GC_CONCURRENT freed <1K, 4% free 18559K/19140K, paused 3ms+0ms, total 20ms
,D/dalvikvm( 1226): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 1226): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/LocationSettingsChecker( 1330): Removing dialog suppression flag for package com.example.hello
,I/MicroHotwordRecognitionRunner( 1226): Starting hotword detection.
,E/NetworkScheduler.SchedulerReceiver( 1126): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1126): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/audio_hw_primary(  184): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  184): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  184): Error: ACDB AudProc vol returned = -19
,D/BluetoothAdapter( 2870): 1113323240: getState() :  mService = null. Returning STATE_OFF
,W/BaseAppContext( 1330): Using Auth Proxy for data requests.
,W/BaseAppContext( 1330): Using Auth Proxy for data requests.
,I/ActivityManager(  776): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2970 uid=10034 gids={50034}
,D/gH_CompatibleDatabase( 1330): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1330): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1330): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1330): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/GMPM-SVC( 1330): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1330): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/SearchController( 1226): #onHotwordDetectorStarted
,D/gH_CompatibleDatabase( 1330): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1330): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,E/SQLiteLog( 1330): (3850) statement aborts at 25: [DELETE FROM help_responses WHERE app_package_name="com.example.hello"] disk I/O error
,D/dalvikvm( 1330): GC_CONCURRENT freed 830K, 5% free 19477K/20336K, paused 4ms+4ms, total 32ms
,D/dalvikvm( 1330): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 1330): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 1330): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/gH_CompatibleDatabase( 1330): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/dalvikvm( 1330): threadid=44: thread exiting with uncaught exception (group=0x41560ba8)
,E/AndroidRuntime( 1330): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1330): Process: com.google.android.gms, PID: 1330
E/AndroidRuntime( 1330): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1330): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1330): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1330): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1330): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1330): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1330): 	at com.google.android.gms.googlehelp.b.b.d(SourceFile:535)
E/AndroidRuntime( 1330): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
E/AndroidRuntime( 1330): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1330): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1330): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1330): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Documents( 2970): Loading roots for com.android.providers.downloads.documents
E/DropBoxManagerService(  776): Can't write: system_app_crash
E/DropBoxManagerService(  776): java.io.FileNotFoundException: /data/system/dropbox/drop85.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  776): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  776): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  776): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  776): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  776): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  776): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  776): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  776): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  776): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  776): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  776): 	... 5 more
,D/Documents( 2970): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 2970): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 2970): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2970): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2970): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2970): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 2970): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 2970): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2970): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteDatabase( 2970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 2970): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2970): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2970): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 2970): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 2970): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 2970): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 2970): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 2970): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2407)
E/SQLiteDatabase( 2970): 	at android.app.ActivityThread.access$1700(ActivityThread.java:135)
E/SQLiteDatabase( 2970): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1272)
E/SQLiteDatabase( 2970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2970): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2970): 	at android.app.ActivityThread.main(ActivityThread.java:5001)
E/SQLiteDatabase( 2970): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 2970): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 2970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 2970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 2970): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  776): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2986 uid=10006 gids={50006, 1028, 1015, 1023}
,I/ActivityManager(  776): Killing 2670:com.google.android.partnersetup/u0a11 (adj 15): empty #17
D/AndroidRuntime( 2970): Shutting down VM
W/dalvikvm( 2970): threadid=1: thread exiting with uncaught exception (group=0x41560ba8)
E/AndroidRuntime( 2970): FATAL EXCEPTION: main
E/AndroidRuntime( 2970): Process: com.android.documentsui, PID: 2970
E/AndroidRuntime( 2970): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2970): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2414)
E/AndroidRuntime( 2970): 	at android.app.ActivityThread.access$1700(ActivityThread.java:135)
E/AndroidRuntime( 2970): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1272)
E/AndroidRuntime( 2970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2970): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2970): 	at android.app.ActivityThread.main(ActivityThread.java:5001)
E/AndroidRuntime( 2970): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2970): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 2970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 2970): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2970): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2970): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 2970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 2970): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 2970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 2970): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 2970): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 2970): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 2970): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/AndroidRuntime( 2970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 2970): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 2970): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2970): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 2970): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 2970): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 2970): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 2970): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 2970): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2407)
E/AndroidRuntime( 2970): 	... 10 more
E/DropBoxManagerService(  776): Can't write: system_app_crash
E/DropBoxManagerService(  776): java.io.FileNotFoundException: /data/system/dropbox/drop86.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  776): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  776): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  776): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  776): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  776): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  776): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  776): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  776): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  776): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  776): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  776): 	... 5 more
I/ActivityManager(  776): Killing 2209:com.android.defcontainer/u0a4 (adj 15): empty #17
E/SQLiteLog( 1330): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1330): threadid=46: thread exiting with uncaught exception (group=0x41560ba8)
I/Process ( 1330): Sending signal. PID: 1330 SIG: 9
,E/qdoverlay(  181): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  181): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  181): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  181): src msmfb_img w=2176 h=1920 format=15 MDP_RGBX_8888
E/qdoverlay(  181): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  181): src msmfb_img w=2176 h=1920 format=15 MDP_RGBX_8888
E/qdoverlay(  181): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): Ctrl commit failed set overlay
E/qdhwcomposer(  181): configureLowRes: commit failed for low res panel
E/qdoverlay(  181): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  181): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  181): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  181): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  181): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  181): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  181): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  181): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  181): Ctrl commit failed set overlay
E/qdhwcomposer(  181): configure: commit fails
E/qdoverlay(  181): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  181): MdpCtrl close error in unset
I/ActivityManager(  776): Process com.google.android.gms (pid 1330) has died.
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 1000ms
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 10999ms
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.usagereporting.service.UsageReportingService in 20999ms
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 30998ms
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 30998ms
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 40998ms
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 40998ms
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 40997ms
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 40997ms
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 40997ms
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 50997ms
W/ActivityManager(  776): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 50997ms
,E/qdoverlay(  181): GenericPipe failed to close ctrl

```
