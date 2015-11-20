#### Test 50388019aa1a16d_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  758): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2194 uid=10058 gids={50058, 3003, 1028, 1015}
--------- beginning of /dev/log/main
I/MultiDex( 2194): VM with version 1.6.0 does not have multidex support
I/MultiDex( 2194): install
I/MultiDex( 2194): MultiDexExtractor.load(/data/app/com.google.android.music-2.apk, false)
I/MultiDex( 2194): loading existing secondary dex files
I/MultiDex( 2194): load found 1 secondary dex files
I/MultiDex( 2194): install done
D/dalvikvm( 2194): GC_CONCURRENT freed 241K, 2% free 16900K/17176K, paused 2ms+3ms, total 23ms
I/BaseStore( 2194): Store database version: 123
I/dalvikvm( 2194): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zza
W/dalvikvm( 2194): VFY: unable to resolve virtual method 613: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 2194): VFY: replacing opcode 0x6e at 0x00c2
I/dalvikvm( 2194): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzk
W/dalvikvm( 2194): VFY: unable to resolve virtual method 981: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 2194): VFY: replacing opcode 0x6e at 0x000b
D/dalvikvm( 2194): GC_CONCURRENT freed 327K, 3% free 17052K/17412K, paused 1ms+2ms, total 12ms
D/MusicLifecycle( 2194): com.google.android.music.MusicApplication generated event: Application created
D/dalvikvm( 2194): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2194): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2194): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2194): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2194): VFY: unable to resolve instance field 46
D/dalvikvm( 2194): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2194): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2194): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2194): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2194): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2194): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
D/dalvikvm( 2194): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42648238
D/dalvikvm( 2194): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42648238
D/dalvikvm( 2194): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42648238, skipping init
D/dalvikvm( 2194): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42648238
D/dalvikvm( 2194): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42648238
V/JNIHelp ( 2194): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/dalvikvm( 2194): GC_CONCURRENT freed 350K, 3% free 17174K/17556K, paused 2ms+2ms, total 12ms
D/dalvikvm( 2194): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42648238
D/dalvikvm( 2194): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42648238
D/dalvikvm( 2194): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42648238
D/dalvikvm( 2194): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42648238
I/ProviderInstaller( 2194): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2194): GMSCore installation verified
D/dalvikvm( 2194): GC_CONCURRENT freed 188K, 2% free 17374K/17676K, paused 2ms+1ms, total 10ms
I/BaseStore( 2194): ConfigStore database version: 1
I/MediaRouter( 2194): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, deviceType=0, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/MusicLifecycle( 2194): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@426b4880 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
D/MusicLifecycle( 2194): com.google.android.music.net.NetworkMonitor generated event: Service created
I/NetworkMonitor( 2194): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  758): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/MusicLifecycle( 2194): com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
D/MusicLifecycle( 2194): com.google.android.music.download.cache.StorageMigrationService generated event: Service created
D/MusicLifecycle( 2194): com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
D/MusicLifecycle( 2194): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@4271f288 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
I/NetworkMonitor( 2194): type=WIFI subType= reason=null isConnected=true
D/MusicLifecycle( 2194): com.google.android.music.download.ArtDownloadQueueService generated event: Service created
I/ActivityManager(  758): Resuming delayed broadcast
W/ContextImpl( 2179): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42f69dc8:true
I/GHttpClientFactory( 2194): Using our fixed implementation of GMSCore's GoogleHttpClient
D/LocalBluetoothProfileManager( 2179): Adding local A2DP profile
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  758): Message: 30
W/BluetoothAdapter( 1568): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1568): SOCK FLAG = 1 ***********************
D/LocalBluetoothProfileManager( 2179): Adding local HEADSET profile
D/BluetoothManagerService(  758): Message: 30
D/BluetoothManagerService(  758): Message: 30
W/ContextImpl( 2179): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
W/ContextImpl( 2179): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
W/dalvikvm( 2194): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2194): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2194): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.GoogleURLConnectionFactory.openConnection
W/dalvikvm( 2194): VFY: unable to resolve virtual method 1704: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 2194): VFY: replacing opcode 0x6e at 0x00a0
D/BluetoothManagerService(  758): Message: 30
I/GoogleURLConnFactory( 2194): Using platform SSLCertificateSocketFactory
D/LocalBluetoothProfileManager( 2179): Adding local MAP profile
D/BluetoothMap( 2179): Create BluetoothMap proxy object
D/BluetoothManagerService(  758): Message: 30
D/BluetoothManagerService(  758): Message: 30
W/ContextImpl( 2179): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
W/ContextImpl( 2179): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
W/ContextImpl( 2179): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1376 
W/ContextImpl( 2179): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 2179): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 2179): finishStartingService: stopping service
D/dalvikvm( 2194): GC_CONCURRENT freed 312K, 2% free 17485K/17832K, paused 2ms+3ms, total 22ms
D/BluetoothAdapterService(1113877048)( 1568): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1568): getBondedDevices: length=4
D/MusicLifecycle( 2194): com.google.android.music.download.cache.ArtCacheService generated event: Service created
D/MusicLifecycle( 2194): com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
D/dalvikvm( 2179): GC_CONCURRENT freed 354K, 3% free 16844K/17236K, paused 2ms+1ms, total 17ms
D/dalvikvm( 2179): WAIT_FOR_CONCURRENT_GC blocked 3ms
D/BluetoothA2dp( 2179): Proxy object connected
D/A2dpProfile( 2179): Bluetooth service connected
D/BluetoothHeadset( 2179): Proxy object connected
D/HeadsetProfile( 2179): Bluetooth service connected
D/BluetoothInputDevice( 2179): Proxy object connected
D/HidProfile( 2179): Bluetooth service connected
D/BluetoothPan( 2179): BluetoothPAN Proxy object connected
D/PanProfile( 2179): Bluetooth service connected
D/BluetoothMap( 2179): Proxy object connected
D/MapProfile( 2179): Bluetooth service connected
D/BluetoothMap( 2179): getConnectedDevices()
D/BluetoothPbap( 2179): Proxy object connected
D/PbapServerProfile( 2179): Bluetooth service connected
D/AuthorizationBluetoothService( 1113): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1113): Proximity feature is not enabled.
I/ActivityManager(  758): Killing 1258:com.google.android.partnersetup/u0a11 (adj 15): empty #17
W/BroadcastQueue(  758): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
D/MusicLifecycle( 2194): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@426b4880 and intent Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
D/dalvikvm( 1568): GC_CONCURRENT freed 300K, 2% free 16854K/17188K, paused 3ms+2ms, total 21ms
D/MusicLifecycle( 2194): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@426b4880 and intent Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
D/MusicLifecycle( 2194): com.google.android.music.store.MediaStoreImportService generated event: Service created
D/MusicLifecycle( 2194): com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
D/MusicLifecycle( 2194): com.google.android.music.store.MediaStoreImportService$Receiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@426b4880 and intent Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.google.android.music/.store.MediaStoreImportService$Receiver }
I/ActivityManager(  758): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  758): Resuming delayed broadcast
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 1568): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1568): SOCK FLAG = 0 ***********************
I/BtOppRfcommListener( 1568): Accept thread started.
D/MusicLifecycle( 2194): com.google.android.music.store.MediaStoreImportService generated event: Service created
I/ActivityManager(  758): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/dalvikvm( 2194): GC_FOR_ALLOC freed 192K, 2% free 17667K/18012K, paused 9ms, total 9ms
I/MediaStoreImporter( 2194): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/MusicLifecycle( 2194): com.google.android.music.store.MediaStoreImportService generated event: Service destroyed
D/AlertReceiver( 1771): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
I/ActivityManager(  758): Resuming delayed broadcast
I/ActivityManager(  758): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
D/AlertService( 1771): 0 Action = android.intent.action.PROVIDER_CHANGED
I/GAV2    ( 1207): Thread[GAThread,5,main]: No campaign data found.
I/GAv4-SVC( 1321): Google Analytics 8.3.01 is starting up.
D/dalvikvm( 1321): GC_CONCURRENT freed 405K, 3% free 18252K/18688K, paused 2ms+2ms, total 16ms
,D/AndroidRuntime( 2255): 
D/AndroidRuntime( 2255): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2255): CheckJNI is OFF
D/dalvikvm( 2255): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2255): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2255): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2255): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2255): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2255): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2255): Calling main entry com.android.commands.am.Am
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2255
D/PermissionCache(  185): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (308 us)
D/dalvikvm(  758): GC_FOR_ALLOC freed 1738K, 10% free 24298K/26956K, paused 43ms, total 45ms
I/dalvikvm-heap(  758): Grow heap (frag case) to 24.579MB for 856096-byte allocation
D/dalvikvm(  758): GC_FOR_ALLOC freed 30K, 10% free 25103K/27796K, paused 38ms, total 38ms
D/dalvikvm(  758): GC_FOR_ALLOC freed 62K, 10% free 25046K/27796K, paused 37ms, total 37ms
I/dalvikvm-heap(  758): Grow heap (frag case) to 25.310MB for 856096-byte allocation
D/dalvikvm(  758): GC_FOR_ALLOC freed <1K, 10% free 25882K/28636K, paused 43ms, total 43ms
D/AndroidRuntime( 2255): Shutting down VM
D/dalvikvm( 2255): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  758): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2271 uid=10115 gids={50115, 3003, 3001, 3002}
I/SearchController( 1207): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1207): mic_close
I/ActivityManager(  758): Killing 1087:com.android.printspooler/u0a64 (adj 15): empty #17
I/MicroHotwordRecognitionRunner( 1207): Stopping hotword detection.
I/MicroHotwordRecognitionRunner( 1207): Hotword detection finished
V/WebViewChromiumFactoryProvider( 2271): Binding Chromium to main looper Looper (main, tid 1) {4263fab0}
I/LibraryLoader( 2271): Expected native library version number "",actual native library version number ""
I/chromium( 2271): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2271): Initializing chromium process, renderers=0
D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d16898:true
I/Adreno-EGL( 2271): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2271): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2271): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2271): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2271): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2271): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2271): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2271): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2271): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2271): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2271): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2271): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2271): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2271): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2271): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2271): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2271): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2271): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2271): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2271): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2271): CordovaWebView is running on device made by: LGE
I/GAV2    ( 1854): Thread[GAThread,5,main]: No campaign data found.
,D/OpenGLRenderer( 2271): Enabling debug mode 0
,W/AwContents( 2271): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  758): Displayed com.example.hello/.MainActivity: +282ms
,I/chromium( 2271): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 2271): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 2271): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2271): GC_CONCURRENT freed 243K, 2% free 16909K/17156K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 2271): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42643da0
,D/dalvikvm( 2271): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42643da0
D/jxcore_app_log( 2271): JniHelper::setJavaVM(0x41524f00), pthread_self() = 1978389960
,D/JX-Cordova( 2271): jxcore cordova android initializing
,D/dalvikvm( 2271): GC_CONCURRENT freed 271K, 2% free 17129K/17436K, paused 1ms+2ms, total 15ms
,D/dalvikvm( 2271): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2271): GC_CONCURRENT freed 330K, 3% free 17204K/17624K, paused 1ms+1ms, total 10ms
,W/jxcore-log( 2271): Initializing JXcore engine
,W/jxcore-log( 2271): JXcore engine is ready
,D/dalvikvm( 2271): GC_FOR_ALLOC freed 233K, 3% free 17338K/17740K, paused 9ms, total 9ms
,W/jxcore-log( 2271): Starting JXcore engine
,W/jxcore-log( 2271): Platform android
W/jxcore-log( 2271): 
,W/jxcore-log( 2271): Process ARCH arm
W/jxcore-log( 2271): 
,I/jxcore-log( 2271): JXcore Cordova bridge is ready!
I/jxcore-log( 2271): 
,W/jxcore-log( 2271): JXcore engine is started
,E/jxcore-log( 2271): >> LGE-Nexus 5
E/jxcore-log( 2271): 
,I/jxcore-log( 2271): Total memory 1945137152
I/jxcore-log( 2271): 
I/jxcore-log( 2271): Free memory 880857088
I/jxcore-log( 2271): 
I/jxcore-log( 2271): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2271): 
,I/jxcore-log( 2271): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2271): 
,I/jxcore-log( 2271): userPath [ 'www' ]
I/jxcore-log( 2271): 
,I/jxcore-log( 2271): Size 1080 1776
I/jxcore-log( 2271): 
,I/jxcore-log( 2271): Screen Brightness 1
I/jxcore-log( 2271): 
,E/jxcore-log( 2271): Dummy Error Log.
E/jxcore-log( 2271): 
,I/jxcore-log( 2271): getBuffer is called!!!!
I/jxcore-log( 2271): 
,D/dalvikvm( 2271): GC_FOR_ALLOC freed 686K, 5% free 16930K/17768K, paused 8ms, total 8ms
,D/dalvikvm( 2271): GC_CONCURRENT freed 223K, 4% free 17125K/17768K, paused 2ms+4ms, total 12ms
,D/dalvikvm( 2271): GC_CONCURRENT freed 411K, 4% free 17146K/17768K, paused 2ms+2ms, total 12ms
,D/dalvikvm( 2271): GC_CONCURRENT freed 404K, 4% free 17204K/17768K, paused 1ms+2ms, total 16ms
,D/dalvikvm( 2271): GC_FOR_ALLOC freed 63K, 3% free 17236K/17768K, paused 8ms, total 8ms
,D/dalvikvm( 2271): GC_FOR_ALLOC freed 56K, 3% free 17264K/17768K, paused 8ms, total 8ms
,I/dalvikvm-heap( 2271): Grow heap (frag case) to 17.013MB for 130826-byte allocation
,D/dalvikvm( 2271): GC_FOR_ALLOC freed 85K, 4% free 17307K/17896K, paused 9ms, total 9ms
,D/dalvikvm( 2271): GC_FOR_ALLOC freed <1K, 4% free 17307K/17896K, paused 7ms, total 7ms
,I/dalvikvm-heap( 2271): Grow heap (frag case) to 17.117MB for 196234-byte allocation
,D/dalvikvm( 2271): GC_FOR_ALLOC freed 0K, 4% free 17499K/18088K, paused 15ms, total 15ms
,D/dalvikvm( 2271): GC_FOR_ALLOC freed 127K, 4% free 17371K/18088K, paused 8ms, total 8ms
,I/dalvikvm-heap( 2271): Grow heap (frag case) to 17.135MB for 150022-byte allocation
,D/dalvikvm( 2271): GC_FOR_ALLOC freed 294K, 6% free 17223K/18236K, paused 7ms, total 7ms
,I/ActivityManager(  758): Killing 1794:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/iu.UploadsManager( 1321): End new media; added: 0, uploading: 0, time: 85 ms
,D/AlertService( 1771): Beginning updateAlertNotification
,D/dalvikvm(  186): GC_EXPLICIT freed 42K, 1% free 16696K/16772K, paused 1ms+2ms, total 17ms
I/ActivityManager(  758): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2349 uid=10001 gids={50001, 3003, 1028, 1015}
,D/dalvikvm(  186): GC_EXPLICIT freed <1K, 1% free 16696K/16772K, paused 1ms+1ms, total 15ms
,D/dalvikvm(  186): GC_EXPLICIT freed <1K, 1% free 16696K/16772K, paused 1ms+2ms, total 15ms
,I/CalendarProvider2( 2349): Created com.android.providers.calendar.CalendarAlarmManager@42659a68(com.android.providers.calendar.CalendarProvider2@42651728)
,D/AlertService( 1771): No fired or scheduled alerts
,D/AlertService( 1771): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1771): No events found starting within 1 week.
,I/CalendarProvider2( 2349): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2349): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  758): Resuming delayed broadcast
I/ActivityManager(  758): Killing 1807:com.google.android.deskclock/u0a33 (adj 15): empty #17
,I/ActivityManager(  758): Killing 1707:com.android.vending/u0a14 (adj 15): empty #17
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=2383 uid=10033 gids={50033, 1028}
,I/ActivityManager(  758): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Delay finish: com.google.android.gm/.GmailReceiver
,I/NotifUtils( 1854): Validating Notification, mapSize: 1 getAttention: true
D/dalvikvm( 1854): GC_CONCURRENT freed 348K, 3% free 17322K/17704K, paused 2ms+1ms, total 12ms
I/NotifUtils( 1854): Unseen count doesn't match cursor count.  unseen: 4 cursor count: 2
I/NotifUtils( 1854): Showing notification with unreadCount of 12 and unseenCount of 2
,I/NotifUtils( 1854): Account: 61035162 vibrate: false
,I/NotifUtils( 1854): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  758): Resuming delayed broadcast
,I/ActivityManager(  758): Killing 1835:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/ActivityManager(  758): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver: pid=2428 uid=10063 gids={50063, 3003, 3002, 1028, 1015},
,D/CaptivePortalTracker(  758): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  758): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  758): Checking http://216.58.209.46/generate_204
W/ActivityThread(  758): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/dalvikvm(  758): GC_FOR_ALLOC freed 268K, 9% free 26157K/28612K, paused 43ms, total 43ms
,I/dalvikvm-heap(  758): Grow heap (frag case) to 25.655MB for 79892-byte allocation
,D/dalvikvm(  758): GC_FOR_ALLOC freed 41K, 9% free 26193K/28692K, paused 44ms, total 44ms
,E/dalvikvm( 2428): Could not find class 'android.app.Notification$Action$Builder', referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve new-instance 411 (Landroid/app/Notification$Action$Builder;) in La;
,D/dalvikvm( 2428): VFY: replacing opcode 0x22 at 0x0000
,D/CaptivePortalTracker(  758): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  758): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  758): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  758): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  758): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,E/dalvikvm( 2428): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve new-instance 574 (Landroid/graphics/drawable/RippleDrawable;) in La;
,D/dalvikvm( 2428): VFY: replacing opcode 0x22 at 0x000b
,E/dalvikvm( 2428): Could not find class 'android.app.Notification$Action$Builder', referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve new-instance 411 (Landroid/app/Notification$Action$Builder;) in La;
,D/dalvikvm( 2428): VFY: replacing opcode 0x22 at 0x0000
,D/dalvikvm( 2428): GC_CONCURRENT freed 185K, 2% free 16933K/17152K, paused 2ms+4ms, total 20ms
,W/dalvikvm( 2428): Unable to resolve superclass of Lcw; (794)
,W/dalvikvm( 2428): Link of class 'Lcw;' failed
E/dalvikvm( 2428): Could not find class 'cw', referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve new-instance 3213 (Lcw;) in La;
,D/dalvikvm( 2428): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 2428): Unable to resolve superclass of Lcy; (794)
W/dalvikvm( 2428): Link of class 'Lcy;' failed
E/dalvikvm( 2428): Could not find class 'cy', referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve new-instance 3267 (Lcy;) in La;
D/dalvikvm( 2428): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 2428): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve virtual method 5743: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2428): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 2428): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve virtual method 6278: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 2428): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 2428): Could not find method android.view.View.getTransitionName, referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve virtual method 6078: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 2428): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 2428): Could not find method android.transition.Transition.getTargetNames, referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve virtual method 5732: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 2428): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 2428): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve interface method 6327: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 2428): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2428): Could not find method android.view.ViewParent.onNestedFling, referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve interface method 6326: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 2428): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 2428): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve interface method 6328: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 2428): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 2428): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 2428): Could not find class 'android.app.RemoteInput[]', referenced from method a.a
W/dalvikvm( 2428): VFY: unable to resolve new-array 12979 ([Landroid/app/RemoteInput;) in La;
,D/dalvikvm( 2428): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 2428): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method a.b
W/dalvikvm( 2428): VFY: unable to resolve virtual method 5743: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 2428): VFY: replacing opcode 0x6e at 0x0009
,D/dalvikvm( 2428): DexOpt: unable to opt direct call 0x0c24 at 0x0e in La;.a
,D/dalvikvm( 2428): DexOpt: unable to opt direct call 0x0fba at 0x0e in La;.a
,D/dalvikvm( 2428): DexOpt: unable to opt direct call 0x0c24 at 0x0e in La;.a
W/dalvikvm( 2428): Unable to resolve superclass of Lcw; (794)
W/dalvikvm( 2428): Link of class 'Lcw;' failed
,D/dalvikvm( 2428): DexOpt: unable to opt direct call 0x5b57 at 0x08 in La;.a
W/dalvikvm( 2428): Unable to resolve superclass of Lcy; (794)
W/dalvikvm( 2428): Link of class 'Lcy;' failed
D/dalvikvm( 2428): DexOpt: unable to opt direct call 0x5c42 at 0x30 in La;.a
,D/dalvikvm( 2428): DexOpt: unable to opt direct call 0x0c7c at 0x13 in La;.a
,D/dalvikvm( 2428): GC_CONCURRENT freed 305K, 2% free 17033K/17372K, paused 2ms+1ms, total 10ms
,D/dalvikvm( 2428): GC_CONCURRENT freed 246K, 2% free 17195K/17476K, paused 2ms+1ms, total 12ms
,I/dalvikvm( 2428): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method ebx.a
,W/dalvikvm( 2428): VFY: unable to resolve virtual method 3144: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2428): VFY: replacing opcode 0x6e at 0x022f
I/dalvikvm( 2428): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method ebx.a
W/dalvikvm( 2428): VFY: unable to resolve virtual method 3516: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2428): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 2428): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method ebx.c
W/dalvikvm( 2428): VFY: unable to resolve virtual method 3144: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2428): VFY: replacing opcode 0x6e at 0x0200
,D/dalvikvm( 2428): Trying to load lib /data/app-lib/com.google.android.apps.plus-1/libcrashreporterer.so 0x42640a30
,D/dalvikvm( 2428): Added shared lib /data/app-lib/com.google.android.apps.plus-1/libcrashreporterer.so 0x42640a30
,I/ActivityManager(  758): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=2455 uid=10031 gids={50031, 3003, 1028, 1015}
,I/ActivityManager(  758): Killing 1100:com.google.android.keep/u0a52 (adj 15): empty #17
,D/dalvikvm( 2428): GC_CONCURRENT freed 325K, 3% free 17350K/17708K, paused 1ms+2ms, total 17ms
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  758): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42e76ee0 mBinding = false
,D/BluetoothManagerService(  758): Message: 2
,D/BluetoothManagerService(  758): Sending off request.
,D/BluetoothAdapterState( 1568): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1568): Setting state to 13
I/BluetoothAdapterState( 1568): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1568): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  758): Message: 60
,D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothAdapterProperties( 1568): onBluetoothDisable()
D/BluetoothManagerService(  758): Bluetooth State Change Intent: 12 -> 13
I/BluetoothAdapterState( 1568): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/BluetoothAdapterProperties( 1568): adapterPropertyChangedCallback with type:7 len:4
,D/WifiService(  758): setWifiEnabled: false pid=2271, uid=10115
D/BluetoothMapService( 1568): onReceive
D/BluetoothMapService( 1568): STATE_TURNING_OFF
D/BluetoothMapService( 1568): MAP Service closeService in
I/BtOppRfcommListener( 1568): stopping Accept Thread
E/BtOppRfcommListener( 1568): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 1568): BluetoothSocket listen thread finished
E/bt-btif ( 1568): bta_jv_rfcomm_stop_server
E/bt-btif ( 1568): bta_jv_rfcomm_stop_server
D/BluetoothAdapterProperties( 1568): Scan Mode:20
D/BluetoothAdapterState( 1568): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 1568): bta_jv_rfcomm_stop_server
W/bt-btif ( 1568): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 1568): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1568): L2CAP - PSM: 0x0017 not found for deregistration
D/btif_config_util( 1568): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/CachedBluetoothDevice( 2179):  Clearing all connection state for dev:XT1039
D/CachedBluetoothDevice( 2179):  Clearing all connection state for dev:G3s-1
D/CachedBluetoothDevice( 2179):  Clearing all connection state for dev:Note3-1
D/CachedBluetoothDevice( 2179):  Clearing all connection state for dev:G4-1
,I/jxcore-log( 2271): ****TEST TOOK:  5077  ms ****
I/jxcore-log( 2271): 
,I/jxcore-log( 2271): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2271): 
,D/CommandListener(  182): Clearing all IP addresses on wlan0
D/ConnectivityService(  758): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,E/WifiStateMachine(  758): scanCount==0 - aborting
D/ConnectivityService(  758): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  758): Attempting to switch to mobile
D/ConnectivityService(  758): Attempting to switch to BLUETOOTH_TETHER
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/NetUtils(  758): android_net_utils_resetConnections in env=0x7603b9d0 clazz=0x3d100001 iface=wlan0 mask=0x3
D/ConnectivityService(  758): resetConnections(wlan0, 3)
,V/NativeCrypto( 1113): Read error: ssl=0x78abdac0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1113): SSL shutdown failed: ssl=0x78abdac0: I/O error during system call, Broken pipe
,D/dalvikvm( 2455): DexOpt: couldn't find static field Landroid/support/v4/e/a;.common_ic_googleplayservices
W/dalvikvm( 2455): VFY: unable to resolve static field 811 (common_ic_googleplayservices) in Landroid/support/v4/e/a;
,D/dalvikvm( 2455): VFY: replacing opcode 0x60 at 0x0051
I/dalvikvm( 2455): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.e.a
W/dalvikvm( 2455): VFY: unable to resolve virtual method 323: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2455): VFY: replacing opcode 0x6e at 0x018f
I/dalvikvm( 2455): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.e.a
W/dalvikvm( 2455): VFY: unable to resolve virtual method 671: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2455): VFY: replacing opcode 0x6e at 0x000b
D/dalvikvm( 2455): DexOpt: couldn't find static field Landroid/support/v4/e/a;.common_full_open_on_phone
,I/dalvikvm( 2455): DexOpt: unable to optimize static field ref 0x032a at 0x85 in Lcom/google/android/gms/common/e;.a
D/bt_hwcfg( 1568): hw_epilog_process
W/bt-btif ( 1568): ag scb idx 1 not allocated
E/bt-btif ( 1568): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1568): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1568): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1568): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1568): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1568): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1568): L2CAP - PSM: 0x0017 not found for deregistration
,D/dalvikvm( 2455): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2455): VFY: unable to resolve instance field 71
D/dalvikvm( 2455): VFY: replacing opcode 0x54 at 0x000c
,D/dalvikvm( 2455): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2455): DexOpt: unable to optimize instance field ref 0x0047 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2455): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2455): DexOpt: unable to optimize instance field ref 0x0047 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/Nat464Xlat(  758): requiresClat: netType=1, hasIPv4Address=false
,D/dalvikvm( 2455): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2455): VFY: unable to resolve instance field 71
D/dalvikvm( 2455): VFY: replacing opcode 0x54 at 0x0011
,D/ConnectivityService(  758): handleInetConditionChange: no active default network - ignore
D/dalvikvm( 2455): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2455): DexOpt: unable to optimize instance field ref 0x0047 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2455): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2455): DexOpt: unable to optimize instance field ref 0x0047 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2455): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2455): DexOpt: unable to optimize instance field ref 0x003d at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/bt_hwcfg( 1568): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 1568): bt_hc_worker_thread exiting
W/bt_userial( 1568): select_read return size <=0:-1, exiting userial_read_thread
I/bt_userial_vendor( 1568): device fd = 65 close
D/BTSNOOP-DISP( 1568): btsnoop_close
I/GKI_LINUX( 1568): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1568): GKI_exit_task: GKI_exit_task 0 done
I/GKI_LINUX( 1568): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 1568): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 1568): Received stop request...Stopping profile...
D/BluetoothHeadset(  758): Proxy object disconnected
D/BluetoothHeadset( 1003): Proxy object disconnected
D/BluetoothHeadset( 1003): Proxy object disconnected
D/BluetoothHeadset( 1003): Proxy object disconnected
D/A2dpService( 1568): Received stop request...Stopping profile...
D/A2dpStateMachine( 1568): Exit Disconnected: -1
D/BluetoothA2dp(  758): Proxy object disconnected
D/BluetoothAdapterService( 1568): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHeadsetServiceJni( 1568): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1568): Cleaning up Bluetooth Handsfree callback object
D/BluetoothHeadset( 2179): Proxy object disconnected
D/HeadsetProfile( 2179): Bluetooth service disconnected
D/BluetoothA2dp( 2179): Proxy object disconnected
D/A2dpProfile( 2179): Bluetooth service disconnected
D/HidService( 1568): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1568): Profile still running: com.android.bluetooth.hdp.HealthService
I/GKI_LINUX( 1568): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1568): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 1568): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/HealthService( 1568): Received stop request...Stopping profile...
D/BluetoothAdapterState( 1568): Stopping profile services that were post enabled
D/BluetoothInputDevice( 2179): Proxy object disconnected
D/HidProfile( 2179): Bluetooth service disconnected
D/PanService( 1568): Received stop request...Stopping profile...
D/BluetoothPan(  758): BluetoothPAN Proxy object disconnected
D/BluetoothTethering(  758): got CMD_CHANNEL_DISCONNECTED
D/BluetoothAdapterService( 1568): Profile still running: com.android.bluetooth.hdp.HealthService
D/BtGatt.DebugUtils( 1568): handleDebugAction() action=null
E/BluetoothTethering(  758): attempted to stop reverse tether with nothing tethered
D/BtGatt.GattService( 1568): Received stop request...Stopping profile...
D/BtGatt.GattService( 1568): stop()
W/BluetoothHidServiceJni( 1568): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1568): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1568): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1568): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 1568): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1568): Cleaning up Bluetooth Health object
D/BluetoothMapService( 1568): Received stop request...,Stopping profile...
D/BluetoothMapService( 1568): stop()
D/BluetoothMapService( 1568): MAP Service closeService in
D/BluetoothAdapterService( 1568): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1568): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1568): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 1568): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 1568): cleanup()
D/BluetoothMapService( 1568): MAP Service closeService in
D/BluetoothAdapterState( 1568): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1568): Setting state to 10
I/BluetoothAdapterState( 1568): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1568): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 1568): Entering OffState
D/BluetoothManagerService(  758): Message: 60
D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothPan( 2179): BluetoothPAN Proxy object disconnected
D/PanProfile( 2179): Bluetooth service disconnected
D/BluetoothManagerService(  758): Broadcasting onBluetoothStateChange(false) to 12 receivers.
D/BluetoothHeadset( 1003): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1003): onBluetoothStateChange: up=false
D/BluetoothMap( 2179): Proxy object disconnected
D/MapProfile( 2179): Bluetooth service disconnected
D/BluetoothHeadset( 1003): onBluetoothStateChange: up=false
D/BluetoothA2dp(  758): onBluetoothStateChange: up=false
D/BluetoothHeadset(  758): onBluetoothStateChange: up=false
D/BluetoothA2dp( 2179): onBluetoothStateChange: up=false
D/BluetoothHeadset( 2179): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 2179): onBluetoothStateChange: up=false
D/BluetoothMap( 2179): onBluetoothStateChange: up=false
D/BluetoothPbap( 2179): onBluetoothStateChange: up=false
D/BluetoothManagerService(  758): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  758): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothManagerService(  758): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42e76ee0 mBinding = false
D/BluetoothManagerService(  758): Sending unbind request.
D/BluetoothAdapterService( 1568): Cleaning up adapter native....
I/GKI_LINUX( 1568): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1568): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1568): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 1568): cleanupNative: return from cleanup
D/BluetoothAdapterService( 1568): Done cleaning up adapter native....
D/BluetoothAdapterService(1113877048)( 1568): ****onDestroy()********
D/BluetoothManagerService(  758): Bluetooth State Change Intent: 13 -> 10
D/BtGatt.GattService( 1568): cleanup()
W/bt-btif ( 1568): GATTC Module not enabled/already disabled
W/bt-btif ( 1568): GATTS Module not enabled/already disabled
D/BluetoothAdapter(  867): 1114360832: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  980): 1115176360: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  980): 1115176360: getState() :  mService = null. Returning STATE_OFF
I/Babel   ( 1968): connection state changed from UNKNOWN to DISCONNECTED
,I/iu.SyncManager( 1321): SYNC; picasa accounts
,D/NetworkLogImpl( 1321): Loaded NetworkSpeedPredictor
,I/wpa_supplicant(  940): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant(  940): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/SystemUpdateService( 1321): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1321): onCreate
,D/SystemUpdateService( 1321): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1321): active receiver: enabled
,I/SystemUpdateService( 1321): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1321): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1321): now status is 0 (complete)
I/SystemUpdateService( 1321): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1321): file has been verified
,I/SystemUpdateService( 1321): OTA package size = 2571501
,I/SystemUpdateService( 1321): showing system update notification
,V/AlarmClock( 2383): AlarmInitReceiver android.intent.action.TIME_SET
,D/dalvikvm( 1771): GC_CONCURRENT freed 291K, 2% free 16791K/17116K, paused 3ms+1ms, total 14ms
,D/SystemUpdateService( 1321): onDestroy
,D/AndroidRuntime( 2473): 
D/AndroidRuntime( 2473): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/AlarmClock( 2383): Displaying next alarm time: ''
,D/AndroidRuntime( 2473): CheckJNI is OFF
,V/AlarmClock( 2383): AlarmInitReceiver finished
,D/dalvikvm( 2473): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 2473): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2473): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2473): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 2473): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/ActivityManager(  758): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2494 uid=10052 gids={50052, 3003, 1028, 1015}
I/ActivityManager(  758): Killing 1889:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,D/dalvikvm( 2473): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,D/dalvikvm( 1113): null clazz in OP_INSTANCE_OF, single-stepping
,I/ActivityManager(  758): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2517 uid=10068 gids={50068}
,D/dalvikvm( 2494): GC_CONCURRENT freed 187K, 2% free 16927K/17148K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 2517): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x4263ee70, skipping init
,D/TimeService( 2517): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448020197030
D/        ( 2517): TimeServiceNative: User Time to be set is 1448020197031
D/QC-time-services( 2517): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2517): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2517): Lib:time_genoff_operation: pargs->ts_val = 1448020197031
,D/QC-time-services(  201): Daemon: Connection accepted:time_genoff
D/QC-time-services( 2517): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  201): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448020197031
D/QC-time-services(  201): Daemon:genoff_opr: Base = 2, val = 1448020197031, operation = 0
D/QC-time-services(  201): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/10/71 5:55:18
D/QC-time-services(  201): Daemon:Value read from RTC seconds = 32334918000
D/QC-time-services(  201): Daemon:new time 1448020197031 
D/QC-time-services(  201): Daemon: delta 1415685279031 genoff 1415685279031 
D/QC-time-services(  201): Daemon:genoff_persistent_update: Writing genoff = 1415685279031 to memory
D/QC-time-services(  201): Daemon:Opening File: /data/system/time/ats_2
,D/QC-time-services(  201): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  201): Updating the TOD offset
D/QC-time-services(  201): Daemon:genoff_persistent_update: Writing genoff = 1415685279031 to memory
D/QC-time-services(  201): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  201): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  201): Daemon:Update to modem bit set
D/QC-time-services(  201): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  201): Daemon: Base = 2, Value being sent to MODEM = 1132055397031
,E/QC-time-services( 2517): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  201): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  201): Daemon: Time-services: Waiting to acceptconnection
D/Tethering(  758): InitialState.processMessage what=4
,I/wpa_supplicant(  940): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  758): sendTetherStateChangedBroadcast 0, 0, 0
,D/AndroidRuntime( 2473): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  758): Killing 1955:com.google.android.exchange/u0a37 (adj 15): empty #17
,I/ActivityManager(  758): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  758): Killing 2271:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  758): Force removing ActivityRecord{42ff0a20 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/WindowState(  758): WIN DEATH: Window{42d35ba8 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  758): Skipping PackageSetting{426d4f68 com.test.thalitest/10108} due to missing metadata
,I/ActivityManager(  758): Force stopping com.example.hello appid=10115 user=0: pkg removed
,W/Settings( 1968): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/CheckinService( 1321): Checkin interval check for package: unspecified last checkin: 1448008797369 min interval config: 0 actual interval: 11399783
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "sms"
,I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/Launcher.Workspace( 1051): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1051): 11683562 - stripEmptyScreens()
,W/GeofencerStateMachine(  980): Ignoring removeGeofence because network location is disabled.
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "smsto"
,W/Sidekick_LocationOracleImpl( 1207): Best location was null
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/LatinIME:LogUtils(  966): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
,W/Binder  (  966): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  966): java.lang.NullPointerException
W/Binder  (  966): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  966): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  966): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  966): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  758): Got RemoteException sending setActive(false) notification to pid 2271 uid 10115
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mmsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm(  758): GC_EXPLICIT freed 2073K, 11% free 25627K/28692K, paused 1ms+7ms, total 108ms
,D/AndroidRuntime( 2473): Shutting down VM
D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  758): removePackageParticipantsLocked: uid=10115 #1
D/dalvikvm( 2473): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 1ms
W/GCoreFlp(  980): No location to return for getLastLocation()
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "sms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "smsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mmsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/GCoreFlp(  980): No location to return for getLastLocation()
,W/GCoreFlp(  980): No location to return for getLastLocation()
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "sms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/GCoreFlp(  980): No location to return for getLastLocation()
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "smsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1003): GC_CONCURRENT freed 336K, 3% free 17063K/17428K, paused 1ms+1ms, total 11ms
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mmsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "sms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "smsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1051): GC_EXPLICIT freed 1413K, 7% free 26146K/27996K, paused 2ms+8ms, total 41ms
,I/Velvet.VelvetNetworkClient( 1207): Network connection not availble
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  758):   Scheme: "mmsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1207): GC_FOR_ALLOC freed 800K, 5% free 17575K/18460K, paused 12ms, total 12ms
,I/dalvikvm-heap( 1207): Grow heap (frag case) to 17.802MB for 640016-byte allocation
,D/dalvikvm( 1207): GC_FOR_ALLOC freed 0K, 2% free 18200K/18460K, paused 11ms, total 11ms
,I/MicroHotwordRecognitionRunner( 1207): Starting hotword detection.
,D/dalvikvm( 1207): GC_CONCURRENT freed 12K, 2% free 18195K/18460K, paused 2ms+1ms, total 13ms
,W/GCoreFlp(  980): No location to return for getLastLocation()
,W/GCoreFlp(  980): No location to return for getLastLocation()
,D/audio_hw_primary(  188): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  188): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  188): Error: ACDB AudProc vol returned = -19
,W/AtomicFile(  758): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  758): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/dalvikvm( 1113): GC_EXPLICIT freed 306K, 3% free 18134K/18600K, paused 2ms+3ms, total 23ms
,V/GmsNetworkLocationProvi(  980): DISABLE
,I/GCoreNlp(  980): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/SQLiteLog( 1113): (3850) statement aborts at 46: [INSERT INTO partner(value,name) VALUES (?,?)] disk I/O error
,E/SQLiteDatabase( 1113): Error inserting value=0 name=network_location_opt_in
E/SQLiteDatabase( 1113): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 1113): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 1113): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 1113): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 1113): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 1113): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 1113): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 1113): 	at com.google.android.gsf.settings.GoogleSettingsProvider.insert(GoogleSettingsProvider.java:236)
E/SQLiteDatabase( 1113): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 1113): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:156)
E/SQLiteDatabase( 1113): 	at android.os.Binder.execTransact(Binder.java:404)
E/SQLiteDatabase( 1113): 	at dalvik.system.NativeStart.run(Native Method)
,W/AtomicFile(  758): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  758): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/qdhwcomposer(  185): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  185): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=16 dpy=0 numHwLayers=5
E/qdoverlay(  185): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  185): MdpData failed to play
E/qdoverlay(  185): == Dump MdpData start ==
E/qdoverlay(  185): == Dump OvFD fd=39 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  185): mOvData msmfb_overlay_data id=64
E/qdoverlay(  185): data msmfb_data offset=0 memid=46 id=0 flags=0x0 priv=0
E/qdoverlay(  185): == Dump MdpData end ==
E/qdhwcomposer(  185): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  185): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  185): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
,E/qdhwcomposer(  185): hwc_set_primary: display commit fail!
,I/SearchController( 1207): #onHotwordDetectorStarted
,E/qdhwcomposer(  185): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  185): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=16 dpy=0 numHwLayers=5
E/qdoverlay(  185): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  185): MdpData failed to play
E/qdoverlay(  185): == Dump MdpData start ==
E/qdoverlay(  185): == Dump OvFD fd=39 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  185): mOvData msmfb_overlay_data id=64
E/qdoverlay(  185): data msmfb_data offset=0 memid=46 id=0 flags=0x0 priv=0
E/qdoverlay(  185): == Dump MdpData end ==
E/qdhwcomposer(  185): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  185): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  185): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
,E/qdhwcomposer(  185): hwc_set_primary: display commit fail!

```
