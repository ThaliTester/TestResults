#### Test 5038801932cd575_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/MultiDex( 2135): VM with version 1.6.0 does not have multidex support
I/MultiDex( 2135): install
I/MultiDex( 2135): MultiDexExtractor.load(/data/app/com.google.android.music-1.apk, false)
I/MultiDex( 2135): loading existing secondary dex files
I/MultiDex( 2135): load found 1 secondary dex files
I/MultiDex( 2135): install done
D/dalvikvm( 2135): GC_CONCURRENT freed 232K, 2% free 16901K/17164K, paused 1ms+4ms, total 18ms
I/BaseStore( 2135): Store database version: 123
I/dalvikvm( 2135): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zza
W/dalvikvm( 2135): VFY: unable to resolve virtual method 613: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 2135): VFY: replacing opcode 0x6e at 0x00c2
I/dalvikvm( 2135): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzk
W/dalvikvm( 2135): VFY: unable to resolve virtual method 981: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 2135): VFY: replacing opcode 0x6e at 0x000b
D/dalvikvm( 2135): GC_CONCURRENT freed 328K, 3% free 17053K/17412K, paused 3ms+2ms, total 13ms
D/MusicLifecycle( 2135): com.google.android.music.MusicApplication generated event: Application created
D/dalvikvm( 2135): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2135): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2135): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2135): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2135): VFY: unable to resolve instance field 46
D/dalvikvm( 2135): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2135): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2135): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2135): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2135): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2135): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
D/dalvikvm( 2135): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4269bca0
D/dalvikvm( 2135): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4269bca0
D/dalvikvm( 2135): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4269bca0, skipping init
D/dalvikvm( 2135): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4269bca0
D/dalvikvm( 2135): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4269bca0
V/JNIHelp ( 2135): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/dalvikvm( 2135): GC_CONCURRENT freed 321K, 3% free 17169K/17524K, paused 1ms+2ms, total 12ms
D/dalvikvm( 2135): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4269bca0
D/dalvikvm( 2135): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4269bca0
D/dalvikvm( 2135): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4269bca0
D/dalvikvm( 2135): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4269bca0
D/dalvikvm( 2135): GC_CONCURRENT freed 208K, 2% free 17375K/17644K, paused 2ms+0ms, total 12ms
I/ProviderInstaller( 2135): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2135): GMSCore installation verified
I/BaseStore( 2135): ConfigStore database version: 1
I/MediaRouter( 2135): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, deviceType=0, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/MusicLifecycle( 2135): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42658878 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
D/MusicLifecycle( 2135): com.google.android.music.net.NetworkMonitor generated event: Service created
--------- beginning of /dev/log/system
I/ActivityManager(  775): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/MusicLifecycle( 2135): com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
D/MusicLifecycle( 2135): com.google.android.music.download.cache.StorageMigrationService generated event: Service created
D/MusicLifecycle( 2135): com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
D/MusicLifecycle( 2135): com.google.android.music.download.ArtDownloadQueueService generated event: Service created
I/ActivityManager(  775): Resuming delayed broadcast
I/GHttpClientFactory( 2135): Using our fixed implementation of GMSCore's GoogleHttpClient
W/dalvikvm( 2135): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2135): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2135): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.GoogleURLConnectionFactory.openConnection
W/dalvikvm( 2135): VFY: unable to resolve virtual method 1704: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 2135): VFY: replacing opcode 0x6e at 0x00a0
I/GoogleURLConnFactory( 2135): Using platform SSLCertificateSocketFactory
D/dalvikvm( 2135): GC_CONCURRENT freed 314K, 2% free 17494K/17840K, paused 2ms+1ms, total 14ms
D/MusicLifecycle( 2135): com.google.android.music.download.cache.ArtCacheService generated event: Service created
D/MusicLifecycle( 2135): com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
D/MusicLifecycle( 2135): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42658878 and intent Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
D/MusicLifecycle( 2135): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42658878 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
D/MusicLifecycle( 2135): com.google.android.music.store.MediaStoreImportService generated event: Service created
D/MusicLifecycle( 2135): com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
D/MusicLifecycle( 2135): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@42658878 and intent Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
I/ActivityManager(  775): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  775): Resuming delayed broadcast
D/MusicLifecycle( 2135): com.google.android.music.store.MediaStoreImportService generated event: Service created
I/ActivityManager(  775): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/MediaStoreImporter( 2135): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/MusicLifecycle( 2135): com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
D/AlertReceiver( 1663): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
D/AlertService( 1663): 0 Action = android.intent.action.PROVIDER_CHANGED
I/ActivityManager(  775): Resuming delayed broadcast
I/ActivityManager(  775): Killing 1594:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #17
I/ActivityManager(  775): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
I/GAV2    ( 1748): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime( 2176): 
D/AndroidRuntime( 2176): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2176): CheckJNI is OFF
D/dalvikvm( 2176): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2176): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2176): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2176): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2176): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2176): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2176): Calling main entry com.android.commands.am.Am
I/ActivityManager(  775): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2176
D/PermissionCache(  181): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (111 us)
D/dalvikvm(  775): GC_FOR_ALLOC freed 1697K, 10% free 24214K/26892K, paused 40ms, total 41ms
I/dalvikvm-heap(  775): Grow heap (frag case) to 24.498MB for 856096-byte allocation
D/dalvikvm(  775): GC_FOR_ALLOC freed 24K, 10% free 25026K/27732K, paused 54ms, total 54ms
D/dalvikvm(  775): GC_FOR_ALLOC freed 60K, 10% free 24967K/27732K, paused 44ms, total 44ms
I/dalvikvm-heap(  775): Grow heap (frag case) to 25.232MB for 856096-byte allocation
D/dalvikvm(  775): GC_FOR_ALLOC freed <1K, 10% free 25803K/28572K, paused 44ms, total 44ms
D/AndroidRuntime( 2176): Shutting down VM
D/dalvikvm( 2176): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/SearchController( 1194): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1194): mic_close
I/ActivityManager(  775): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2198 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  775): Killing 1078:com.android.printspooler/u0a64 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 2198): Binding Chromium to main looper Looper (main, tid 1) {425feae0}
I/LibraryLoader( 2198): Expected native library version number "",actual native library version number ""
I/chromium( 2198): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2198): Initializing chromium process, renderers=0
I/MicroHotwordRecognitionRunner( 1194): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1194): Stopping hotword detection.
D/BluetoothManagerService(  775): Message: 20
D/BluetoothManagerService(  775): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42cf1088:true
D/BluetoothAdapter( 2198): 1113669336: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 2198): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2198): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2198): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2198): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2198): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2198): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2198): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2198): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2198): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2198): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2198): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2198): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2198): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2198): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2198): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2198): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2198): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2198): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2198): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2198): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2198): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2198): Enabling debug mode 0
,W/AwContents( 2198): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  775): Displayed com.example.hello/.MainActivity: +283ms
,I/chromium( 2198): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 2198): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 2198): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2198): GC_CONCURRENT freed 226K, 2% free 16932K/17136K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 2198): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x42602dd0
,D/dalvikvm( 2198): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x42602dd0
,D/jxcore_app_log( 2198): JniHelper::setJavaVM(0x414e5f00), pthread_self() = 1978136936
,D/JX-Cordova( 2198): jxcore cordova android initializing
,D/dalvikvm( 2198): GC_CONCURRENT freed 249K, 2% free 17137K/17420K, paused 0ms+1ms, total 8ms
,D/dalvikvm( 2198): GC_CONCURRENT freed 332K, 3% free 17205K/17608K, paused 2ms+1ms, total 10ms
,W/jxcore-log( 2198): Initializing JXcore engine
,W/jxcore-log( 2198): JXcore engine is ready
,D/dalvikvm( 2198): GC_CONCURRENT freed 360K, 3% free 17353K/17748K, paused 1ms+1ms, total 9ms
,D/dalvikvm( 2198): WAIT_FOR_CONCURRENT_GC blocked 6ms
,W/jxcore-log( 2198): Starting JXcore engine
,W/jxcore-log( 2198): Platform android
W/jxcore-log( 2198): 
,W/jxcore-log( 2198): Process ARCH arm
W/jxcore-log( 2198): 
,I/jxcore-log( 2198): JXcore Cordova bridge is ready!
I/jxcore-log( 2198): 
,W/jxcore-log( 2198): JXcore engine is started
,E/jxcore-log( 2198): >> LGE-Nexus 5
E/jxcore-log( 2198): 
,I/jxcore-log( 2198): Total memory 1945137152
I/jxcore-log( 2198): 
I/jxcore-log( 2198): Free memory 878673920
I/jxcore-log( 2198): 
I/jxcore-log( 2198): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2198): 
,I/jxcore-log( 2198): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2198): 
,I/jxcore-log( 2198): userPath [ 'www' ]
I/jxcore-log( 2198): 
,I/jxcore-log( 2198): Size 1080 1776
I/jxcore-log( 2198): 
,I/jxcore-log( 2198): Screen Brightness 1
I/jxcore-log( 2198): 
,E/jxcore-log( 2198): Dummy Error Log.
E/jxcore-log( 2198): 
,I/jxcore-log( 2198): getBuffer is called!!!!
I/jxcore-log( 2198): 
,D/dalvikvm( 2198): GC_CONCURRENT freed 722K, 5% free 17098K/17896K, paused 1ms+2ms, total 10ms
,D/dalvikvm( 2198): GC_CONCURRENT freed 402K, 5% free 17146K/17896K, paused 2ms+2ms, total 13ms
,D/dalvikvm( 2198): GC_CONCURRENT freed 401K, 4% free 17181K/17896K, paused 1ms+1ms, total 10ms
,D/dalvikvm( 2198): GC_FOR_ALLOC freed 200K, 4% free 17265K/17896K, paused 8ms, total 8ms
,I/dalvikvm-heap( 2198): Grow heap (frag case) to 17.013MB for 130826-byte allocation
,D/dalvikvm( 2198): GC_FOR_ALLOC freed 0K, 4% free 17393K/18024K, paused 17ms, total 17ms
,D/dalvikvm( 2198): GC_FOR_ALLOC freed 85K, 4% free 17308K/18024K, paused 8ms, total 8ms
,D/dalvikvm( 2198): GC_FOR_ALLOC freed 127K, 4% free 17371K/18024K, paused 8ms, total 8ms
,I/dalvikvm-heap( 2198): Grow heap (frag case) to 17.135MB for 150022-byte allocation
,D/dalvikvm( 2198): GC_FOR_ALLOC freed 294K, 6% free 17224K/18172K, paused 8ms, total 8ms
,I/iu.UploadsManager( 1301): End new media; added: 0, uploading: 0, time: 96 ms
,I/ActivityManager(  775): Killing 1250:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,D/AlertService( 1663): Beginning updateAlertNotification
,I/ActivityManager(  775): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2275 uid=10001 gids={50001, 3003, 1028, 1015}
,I/CalendarProvider2( 2275): Created com.android.providers.calendar.CalendarAlarmManager@42618aa0(com.android.providers.calendar.CalendarProvider2@42610760)
,D/AlertService( 1663): No fired or scheduled alerts
,D/AlertService( 1663): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1663): No events found starting within 1 week.
,I/CalendarProvider2( 2275): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2275): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  775): Resuming delayed broadcast
I/ActivityManager(  775): Killing 1622:com.android.vending/u0a14 (adj 15): empty #17
I/ActivityManager(  775): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.gm/.GmailReceiver
,D/dalvikvm( 1748): GC_CONCURRENT freed 354K, 3% free 17283K/17672K, paused 3ms+2ms, total 33ms
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.gm/.GmailReceiver,
,I/NotifUtils( 1748): Validating Notification, mapSize: 1 getAttention: true
,I/NotifUtils( 1748): Unseen count doesn't match cursor count.  unseen: 4 cursor count: 2
,I/NotifUtils( 1748): Showing notification with unreadCount of 12 and unseenCount of 2
,D/dalvikvm( 1748): GC_CONCURRENT freed 354K, 3% free 17381K/17768K, paused 1ms+1ms, total 12ms
,I/NotifUtils( 1748): Account: 61035162 vibrate: false
,I/NotifUtils( 1748): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.gms/.lockbox.LockboxAlarmReceiver
,W/GCoreFlp(  993): No location to return for getLastLocation()
,W/FusedLocationProvider( 1124): location=null
I/ActivityManager(  775): Resuming delayed broadcast
I/ActivityManager(  775): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,D/dalvikvm( 1301): GC_CONCURRENT freed 428K, 3% free 18328K/18788K, paused 2ms+3ms, total 28ms
I/ActivityManager(  775): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,D/GCM     ( 1124): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1124): GC_CONCURRENT freed 397K, 4% free 18130K/18732K, paused 1ms+1ms, total 20ms
,I/ActivityManager(  775): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/dalvikvm( 1909): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 1909): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1909): VFY: replacing opcode 0x62 at 0x000a
,I/ActivityManager(  775): Resuming delayed broadcast
D/dalvikvm( 1909): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 1909): VFY: unable to resolve instance field 46
D/dalvikvm( 1909): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 1909): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1909): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1909): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 1909): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 1909): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
D/dalvikvm( 1909): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4291ad80
D/dalvikvm( 1909): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4291ad80
D/dalvikvm( 1909): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4291ad80, skipping init
,D/dalvikvm( 1909): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4291ad80
,D/dalvikvm( 1909): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4291ad80
,V/JNIHelp ( 1909): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/ActivityManager(  775): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2334 uid=10011 gids={50011, 3003}
,I/ActivityManager(  775): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2352 uid=10013 gids={50013, 3003, 3002}
,D/dalvikvm(  182): GC_EXPLICIT freed 42K, 1% free 16697K/16772K, paused 1ms+2ms, total 16ms
,D/dalvikvm( 1909): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4291ad80
,D/dalvikvm( 1909): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4291ad80
D/dalvikvm( 1909): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4291ad80
,D/dalvikvm( 1909): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4291ad80
,D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16697K/16772K, paused 1ms+1ms, total 12ms
I/ActivityManager(  775): Delay finish: com.android.musicfx/.Compatibility$Receiver
,D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16697K/16772K, paused 1ms+1ms, total 12ms
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2367 uid=10014 gids={50014, 3003, 1028, 1015}
,I/ActivityManager(  775): Killing 1698:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/ProviderInstaller( 1909): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 2367): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 2367): GC_CONCURRENT freed 230K, 2% free 16884K/17148K, paused 3ms+0ms, total 16ms
,D/Finsky  ( 2367): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 2367): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2367): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 2367): GC_CONCURRENT freed 254K, 2% free 17058K/17340K, paused 3ms+2ms, total 14ms
,I/Icing.InternalIcingCorporaProvider( 1194): Updating corpora: A: com.example.hello, C: MAYBE
,D/Finsky  ( 2367): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2367): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 2367): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  775): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  775): Delaying start of: ServiceRecord{42cc1b88 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/dalvikvm(  775): GC_EXPLICIT freed 424K, 9% free 26080K/28568K, paused 2ms+8ms, total 86ms
,D/BluetoothManagerService(  775): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  775): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  775): Message: 2
,I/jxcore-log( 2198): ****TEST TOOK:  5037  ms ****
I/jxcore-log( 2198): 
,I/jxcore-log( 2198): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2198): 
D/WifiService(  775): setWifiEnabled: false pid=2198, uid=10115
,D/dalvikvm( 1301): GC_CONCURRENT freed 459K, 3% free 18306K/18800K, paused 2ms+4ms, total 33ms
,D/dalvikvm( 1194): GC_CONCURRENT freed 892K, 5% free 18001K/18924K, paused 1ms+1ms, total 12ms
,I/Icing.InternalIcingCorporaProvider( 1194): UpdateCorporaTask done [took 425 ms] updated apps [took 425 ms] 
I/ActivityManager(  775): Killing 1731:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,D/AndroidRuntime( 2417): 
D/AndroidRuntime( 2417): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2417): CheckJNI is OFF
,D/dalvikvm( 2417): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 2417): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 2417): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2417): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 2417): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 2417): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,D/AndroidRuntime( 2417): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  775): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  775): Killing 2198:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  775): Force removing ActivityRecord{42e179d8 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/WindowState(  775): WIN DEATH: Window{42af06d0 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  775): Skipping PackageSetting{426fa3b0 com.test.thalitest/10108} due to missing metadata
,I/ActivityManager(  775): Force stopping com.example.hello appid=10115 user=0: pkg removed
,W/Sidekick_LocationOracleImpl( 1194): Best location was null
W/InputMethodManagerService(  775): Got RemoteException sending setActive(false) notification to pid 2198 uid 10115
,W/Binder  (  975): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  975): java.lang.NullPointerException
W/Binder  (  975): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  975): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  975): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  975): 	at dalvik.system.NativeStart.run(Native Method)
,W/GeofencerStateMachine(  993): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  775): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "sms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/LatinIME:LogUtils(  975): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
,D/dalvikvm( 1048): GC_EXPLICIT freed 832K, 7% free 26132K/27892K, paused 9ms+3ms, total 61ms
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
D/dalvikvm( 2135): GC_CONCURRENT freed 217K, 3% free 17661K/18036K, paused 1ms+1ms, total 31ms
,D/Launcher.Workspace( 1048): 11683562 - stripEmptyScreens()
,I/PackageManager(  775):   Scheme: "smsto"
,D/Launcher.Workspace( 1048): 11683562 - stripEmptyScreens()
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/BackupManagerService(  775): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  775): removePackageParticipantsLocked: uid=10115 #1
,W/GCoreFlp(  993): No location to return for getLastLocation()
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "mms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/Velvet.VelvetNetworkClient( 1194): Network connection not availble
D/dalvikvm( 1194): GC_FOR_ALLOC freed 250K, 6% free 17834K/18924K, paused 19ms, total 19ms
,I/dalvikvm-heap( 1194): Grow heap (frag case) to 18.054MB for 640016-byte allocation
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "mmsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1194): GC_FOR_ALLOC freed <1K, 3% free 18459K/18924K, paused 12ms, total 12ms
,I/MicroHotwordRecognitionRunner( 1194): Starting hotword detection.
,D/dalvikvm( 1194): GC_CONCURRENT freed 8K, 3% free 18456K/18924K, paused 2ms+1ms, total 13ms
,W/GCoreFlp(  993): No location to return for getLastLocation()
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "sms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  775): GC_EXPLICIT freed 1617K, 12% free 25360K/28568K, paused 1ms+7ms, total 180ms
,D/audio_hw_primary(  184): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  184): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  184): Error: ACDB AudProc vol returned = -19
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "smsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/AndroidRuntime( 2417): Shutting down VM
,D/dalvikvm( 2417): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 2ms
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "mms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "mmsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/InputReader(  775): Reconfiguring input devices.  changes=0x00000010
,W/GCoreFlp(  993): No location to return for getLastLocation()
,W/GCoreFlp(  993): No location to return for getLastLocation()
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "sms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/SearchController( 1194): #onHotwordDetectorStarted
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "smsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "mms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "mmsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/GCoreFlp(  993): No location to return for getLastLocation()
,W/GCoreFlp(  993): No location to return for getLastLocation()
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "sms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "smsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1013): GC_CONCURRENT freed 348K, 3% free 17053K/17432K, paused 2ms+1ms, total 12ms
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "mms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  775):   Scheme: "mmsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,V/GmsNetworkLocationProvi(  993): DISABLE
,I/GCoreNlp(  993): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/SQLiteLog( 1124): (3850) statement aborts at 46: [INSERT INTO partner(value,name) VALUES (?,?)] disk I/O error
,E/SQLiteDatabase( 1124): Error inserting value=0 name=network_location_opt_in
E/SQLiteDatabase( 1124): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 1124): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 1124): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 1124): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 1124): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 1124): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 1124): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 1124): 	at com.google.android.gsf.settings.GoogleSettingsProvider.insert(GoogleSettingsProvider.java:236)
E/SQLiteDatabase( 1124): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 1124): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:156)
E/SQLiteDatabase( 1124): 	at android.os.Binder.execTransact(Binder.java:404)
E/SQLiteDatabase( 1124): 	at dalvik.system.NativeStart.run(Native Method)
,W/AtomicFile(  775): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  775): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/dalvikvm(  993): GC_CONCURRENT freed 376K, 3% free 17908K/18380K, paused 2ms+2ms, total 17ms
,I/Icing   ( 1301): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,E/Icing   ( 1301): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
,E/Icing   ( 1301): Could not init tag ds.tag.deleted
,D/Icing   ( 1301): Loaded CLD2 Version V2.0 - 20141016
E/Icing   ( 1301): Bad write: Bad file number
,E/Icing   ( 1301): Error writing document: Write error to document store(6)
,E/Icing   ( 1301): Skipped indexing "1051" because it was not added to the document store
,I/Icing   ( 1301): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/Icing   ( 1301): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,I/Icing   ( 1301): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,E/Icing   ( 1301): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,E/Icing   ( 1301): Writing status failed
,E/Icing   ( 1301): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)

```
