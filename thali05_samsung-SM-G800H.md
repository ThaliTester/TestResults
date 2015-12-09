#### Test 5065027873d6a28_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5269): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5269):  
--------- beginning of /dev/log/system
I/ActivityManager(  790): Killing 3593:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
D/dalvikvm(  248): GC_EXPLICIT freed 46K, 50% free 9509K/18972K, paused 2ms+2ms, total 29ms
I/SELinux ( 5269): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5269):  
I/SELinux ( 5269):  
I/SELinux ( 5269): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18972K, paused 2ms+3ms, total 19ms
E/SELinux ( 5269): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5269): >>>>> Normal User
E/dalvikvm( 5269): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5269): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18972K, paused 1ms+2ms, total 18ms
D/TimaKeyStoreProvider( 5269): in addTimaSignatureService
D/TimaKeyStoreProvider( 5269): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5269): Added TimaKesytore provider
,W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5269, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5269): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5269): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  790): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
I/SA      ( 4042): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4042): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4042): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/AndroidRuntime( 5286): 
D/AndroidRuntime( 5286): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5286): CheckJNI is OFF
D/AndroidRuntime( 5286): setted country_code = Poland
D/AndroidRuntime( 5286): setted countryiso_code = PL
D/AndroidRuntime( 5286): setted sales_code = XEO
D/AndroidRuntime( 5286): readGMSProperty: start
D/AndroidRuntime( 5286): readGMSProperty: already setted!!
D/AndroidRuntime( 5286): readGMSProperty: end
D/AndroidRuntime( 5286): addProductProperty: start
D/dalvikvm( 5286): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5286): Added shared lib libjavacore.so 0x0
D/Mms/PackageInstallReceiver( 4332): loadAuthorityPref(): sEnableAuthority = true
D/dalvikvm( 5286): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5286): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5286): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/IcingCorporaProvider( 2183): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4673): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5307): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5307):  
I/SELinux ( 5307): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5307):  
I/SELinux ( 5307):  
I/SELinux ( 5307): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5307): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5307): >>>>> Normal User
E/dalvikvm( 5307): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5307): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5307): in addTimaSignatureService
D/TimaKeyStoreProvider( 5307): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5307): Added TimaKesytore provider
E/memtrack( 5286): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5286): failed to load memtrack module: -2
I/ActivityManager(  790): Killing 3967:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
I/IcingCorporaProvider( 2183): UpdateCorporaTask done [took 166 ms] updated apps [took 166 ms] 
D/dalvikvm( 5286): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/CapabilityManagerService New( 5307): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5307, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5320): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5320):  
I/ActivityManager(  790): Killing 3979:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/AndroidRuntime( 5286): Calling main entry com.android.commands.am.Am
I/SELinux ( 5320): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5320):  
I/SELinux ( 5320):  
I/SELinux ( 5320): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5320): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5320): >>>>> Normal User
E/dalvikvm( 5320): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5320): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5320): in addTimaSignatureService
D/TimaKeyStoreProvider( 5320): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5320): Added TimaKesytore provider
V/ApplicationPolicy(  790): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  790): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  790): mDVFSHelper.acquire()
I/SELinux ( 5334): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5334):  
D/LockPatternUtils( 1069): isPcwEnable = null
D/AndroidRuntime( 5286): Shutting down VM
D/dalvikvm( 5286): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5320, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5334): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5334):  
I/SELinux ( 5334):  
I/SELinux ( 5334): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5334): >>>>> Normal User
E/dalvikvm( 5334): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5334): in addTimaSignatureService
D/TimaKeyStoreProvider( 5334): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5334): Added TimaKesytore provider
D/LockPatternUtils( 1069): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2114): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2114): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1262): destroyHardwareResources():1126594304
I/SurfaceFlinger(  247): id=8 Removed Mauncher (7/11)
I/SurfaceFlinger(  247): id=8 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1450): [237392/5] Surface widget visibility changed visibility = false on instance = 1
W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5334, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
D/Launcher( 1262): onTrimMemory. Level: 20
W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5334, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5334): Binding Chromium to the background looper Looper (main, tid 1) {42338160}
I/chromium( 5334): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5334): Initializing chromium process, renderers=0
W/chromium( 5334): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5334): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5334): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5334): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5334): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5334): Remote Branch: 
I/Adreno-EGL( 5334): Local Patches: 
I/Adreno-EGL( 5334): Reconstruct Branch: 
,I/dalvikvm( 5334): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5334): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5334): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5334): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5334): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5334): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5334): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5334): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5334): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5334): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5334): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5334): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5334): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5334): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5334): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5334): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5334): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5334): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5334): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger(  247): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5334): EGLImpl-HWUI Protected EGL context created
I/PowerManagerService(  790): [PWL] Off : 50s ago
D/OpenGLRenderer( 5334): Enabling debug mode 0
W/AwContents( 5334): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  790): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  790): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  790): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 5377): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5377):  
I/ActivityManager(  790): Killing 4258:com.sec.android.service.health/u0a16 (adj 15): empty #43
W/GAV2    ( 5320): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5377): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5377):  
I/SELinux ( 5377):  
I/SELinux ( 5377): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5377): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5377): >>>>> Normal User
E/dalvikvm( 5377): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5377): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5377): in addTimaSignatureService
D/TimaKeyStoreProvider( 5377): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5377): Added TimaKesytore provider
D/PackageIntentReceiver( 5377): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5377): Not GearManger package! 
I/SELinux ( 5396): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5396):  
I/SELinux ( 5396): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5396):  
I/SELinux ( 5396):  
I/SELinux ( 5396): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5396): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5396): >>>>> Normal User
E/dalvikvm( 5396): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5396): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5396): in addTimaSignatureService
D/TimaKeyStoreProvider( 5396): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5396): Added TimaKesytore provider
D/JsMessageQueue( 5334): Set native->JS mode to OnlineEventsBridgeMode
D/MagazineService Version( 5396): Magazine-Channel: 13
D/MagazineService Version( 5396): Magazine-Provider: 13
D/MagazineService Version( 5396): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5396): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5396): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5396, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5396): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5410): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5410):  
D/MagazineService::MagazineService( 5396): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  790): Killing 3992:com.sec.android.soagent/u0a37 (adj 15): empty #43
W/GAV2    ( 5320): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  790): Killing 1346:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 5410): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5410):  
I/SELinux ( 5410):  
I/SELinux ( 5410): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5410): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5410): >>>>> Normal User
E/dalvikvm( 5410): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5410): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 5334): Trying to load lib /data/app-lib/com.test.thalitest-19/libjxcore.so 0x4265ee60
D/TimaKeyStoreProvider( 5410): in addTimaSignatureService
D/TimaKeyStoreProvider( 5410): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5410): Added TimaKesytore provider
D/dalvikvm( 5334): Added shared lib /data/app-lib/com.test.thalitest-19/libjxcore.so 0x4265ee60
D/jxcore_app_log( 5334): JniHelper::setJavaVM(0x417a1528), pthread_self() = 2033451712
D/JX-Cordova( 5334): jxcore cordova android initializing
I/dalvikvm( 5334): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 5334): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5334): VFY: replacing opcode 0x6e at 0x0045
,D/SSRMv2:SIOP(  790): SIOP:: AP = 320, Delta = 10
I/SELinux ( 5424): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5424):  
I/ActivityManager(  790): Killing 4371:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
I/SELinux ( 5424): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5424):  
I/SELinux ( 5424):  
I/SELinux ( 5424): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5424): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5424): >>>>> Normal User
E/dalvikvm( 5424): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 5424): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5424): in addTimaSignatureService
D/TimaKeyStoreProvider( 5424): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5424): Added TimaKesytore provider
D/dalvikvm( 5334): GC_CONCURRENT freed 4925K, 33% free 12765K/18972K, paused 1ms+3ms, total 30ms
D/dalvikvm( 5334): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm( 5334): WAIT_FOR_CONCURRENT_GC blocked 13ms
W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5424, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 5424): Package not found : com.sec.android.app.kidshome
E/SMD     (  241): DCD ON
I/SELinux ( 5436): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5436):  
I/ActivityManager(  790): Killing 4386:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
I/SELinux ( 5436): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5436):  
I/SELinux ( 5436):  
I/SELinux ( 5436): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5436): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5436): >>>>> Normal User
E/dalvikvm( 5436): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
E/SELinux ( 5436): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5436): in addTimaSignatureService
D/TimaKeyStoreProvider( 5436): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5436): Added TimaKesytore provider
I/ActivityManager(  790): Killing 4398:com.sec.esdk.elm/u0a94 (adj 15): empty #43
D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1784): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1784): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/CustomFrequencyManagerService(  790): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  tag : ACTIVITY_RESUME_BOOSTER@9
D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1784): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1784): Submit a task: h
D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/h       ( 1784): Processing package: com.test.thalitest
D/Finsky  ( 3720): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/GassUtils( 1784): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
D/h       ( 1784): Found info for package com.test.thalitest in db.
I/SELinux ( 5454): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5454):  
W/BaseAppContext( 1784): Using Auth Proxy for data requests.
W/BaseAppContext( 1784): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1784): CP2 sync disabled
I/dalvikvm( 1784): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
I/SELinux ( 5454): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5454):  
I/SELinux ( 5454):  
I/SELinux ( 5454): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5454): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5454): >>>>> Normal User
E/dalvikvm( 5454): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux ( 5454): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/dalvikvm( 1784): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1784): VFY: replacing opcode 0x6e at 0x000e
D/TimaKeyStoreProvider( 5454): in addTimaSignatureService
D/TimaKeyStoreProvider( 5454): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5454): Added TimaKesytore provider
W/BaseAppContext( 1784): Using Auth Proxy for data requests.
W/BaseAppContext( 1784): Using Auth Proxy for data requests.
W/BaseAppContext( 1784): Using Auth Proxy for data requests.
W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,I/VerificationService( 5454): verificationId{0} request received.
W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5454, uid=10021 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm( 5334): GC_FOR_ALLOC freed 4698K, 28% free 15767K/21768K, paused 36ms, total 37ms
,D/dalvikvm( 1323): GC_EXPLICIT freed 810K, 42% free 11142K/18972K, paused 8ms+5ms, total 69ms
,D/dalvikvm( 5454): GC_CONCURRENT freed 5778K, 38% free 11911K/18972K, paused 1ms+2ms, total 39ms
,D/dalvikvm( 5454): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 5334): GC_FOR_ALLOC freed 5051K, 32% free 16773K/24440K, paused 42ms, total 42ms
,I/dalvikvm-heap( 5334): Grow heap (frag case) to 21.976MB for 2459024-byte allocation
,D/PackageManager(  790): [MSG] PACKAGE_VERIFIED: observer{1126123200}
D/PackageManager(  790):           verificationId{0}
,D/PackageManager(  790): copyApk
,I/ActivityManager(  790): Killing 3581:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/Finsky  ( 3720): [1] PackageVerificationReceiver.onReceive: Verification requested, id = 0
,D/dalvikvm( 5334): GC_FOR_ALLOC freed 3768K, 35% free 17454K/26844K, paused 42ms, total 42ms
,I/PackageManager(  790): Copying native libraries to /data/app-lib/vmdl-2002583158
,D/dalvikvm( 5334): GC_FOR_ALLOC freed 1230K, 36% free 17360K/26844K, paused 30ms, total 30ms
,W/jxcore-log( 5334): Initializing JXcore engine
,W/jxcore-log( 5334): JXcore engine is ready
,D/PackageManager(  790): remove MCS_UNBIND and Posting MCS_UNBIND
,D/PackageManager(  790): [MSG] PROCESS_PENDING_INSTALL: observer{1126123200}
,D/PackageManager(  790): installPackageLI
,W/jxcore-log( 5334): Starting JXcore engine
,W/Resources(  790): Converting to boolean: TypedValue{t=0x3/d=0x21cc "false" a=3 r=0x7f120ac5}
,W/ResourceType(  790): Failure getting entry for 0x7f1303bb (t=18 e=955) in package 0 (error -75)
,W/jxcore-log( 5334): Platform android
W/jxcore-log( 5334): 
,W/jxcore-log( 5334): Process ARCH arm
W/jxcore-log( 5334): 
,D/dalvikvm(  790): GC_CONCURRENT freed 2469K, 56% free 25055K/55728K, paused 8ms+14ms, total 161ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 129ms
,D/dalvikvm(  790): GC_CONCURRENT freed 2541K, 53% free 26425K/55728K, paused 6ms+11ms, total 145ms
D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 78ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 79ms
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/jxcore-log( 5334): JXcore Cordova bridge is ready!
I/jxcore-log( 5334): 
,W/jxcore-log( 5334): JXcore engine is started
,I/chromium( 5334): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 5334): Error!: missing ) after argument list
E/jxcore  ( 5334): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5334): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1069): isPcwEnable = null
I/ActivityManager(  790): Killing 4425:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,I/SurfaceFlinger(  247): id=17 Removed NainActivit (7/11)
,I/SurfaceFlinger(  247): id=17 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  790): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  790): mDVFSHelper.acquire()
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/SurfaceWidgetView( 1262): destroyHardwareResources():1126594304
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1262): onRestart, Launcher: 1114658576
,D/Launcher( 1262): onStart, Launcher: 1114658576
,D/Launcher.HomeView( 1262): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1450): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1450): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  247): id=18 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=19 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1262): onStop
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  790): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  790): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  790): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/GAV2    ( 5320): Thread[GAThread,5,main]: No campaign data found.
,D/CustomFrequencyManagerService(  790): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  tag : ACTIVITY_RESUME_BOOSTER@9
,D/dalvikvm(  790): GC_CONCURRENT freed 3799K, 52% free 26880K/55728K, paused 6ms+12ms, total 148ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/PackageManager(  790): Time to collect certificates: 3.321 seconds
,D/ApplicationPolicy(  790): isApplicationInstallationEnabled
D/ApplicationPolicy(  790): isApplicationInstallationEnabled :  Checking PKG WL - false
,D/ApplicationPolicy(  790): isApplicationInstallationEnabled :  Checking PKG BL - true
,D/ApplicationPolicy(  790): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  790): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy(  790): isApplicationInstallationEnabled :  Checking PKG WL - false
,D/ApplicationPolicy(  790): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  790): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  790): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy(  790): isApplicationInstallationEnabled :  enabled true
W/PackageManager(  790): verifying app can be installed or not
,V/ApplicationPolicy(  790): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/PackageManager(  790): Replace existing pacakge: 
D/PackageManager(  790): Existing package: 
D/PackageManager(  790): doRename: 
D/PackageManager(  790): doRename apk path: 
D/PackageManager(  790): replacePackageLI
D/PackageManager(  790): replacePackageLI: 
D/PackageManager(  790): !@killApplicatoin: 10011, replace sys pkg
I/ActivityManager(  790): Killing 1220:com.google.android.gms.persistent/u0a11 (adj 1): stop com.google.android.gms
I/ActivityManager(  790): Killing 1784:com.google.android.gms/u0a11 (adj 5): stop com.google.android.gms
I/ActivityManager(  790): Killing 1323:com.google.process.gapps/u0a11 (adj 0): stop com.google.android.gms
,D/LocationManagerService(  790): Location listener died
,I/LocationManagerService(  790): remove 430db230 by com.google.android.gms
,D/LocationManagerService(  790): Location listener died
,D/GpsLocationProvider(  790): GPS status listener died
D/LocationManagerService(  790): provider request: passive ProviderRequest[ON interval=0]
,I/LocationManagerService(  790): remove 42daabd8 by com.google.android.gms
,D/LocationManagerService(  790): provider request: passive ProviderRequest[ON interval=0]
,D/PackageManager(  790): getApplicationInfo - Execution time: 117 ms
W/PackageManager(  790): Package com.google.android.gms desires unavailable shared library com.google.android.ble; ignoring!
W/PackageManager(  790): Trying to update system app code path from /data/app/com.google.android.gms-1.apk to /data/app/com.google.android.gms-2.apk
W/SELinuxMMAC(  790): assignSeinfoValue, matching key found
W/SELinuxMMAC(  790): assignSeinfoValue , step 2, pkgName:com.google.android.gms, seinfo:untrusted
W/SELinuxMMAC(  790): assignSeinfoValue, step 4, pkgName:com.google.android.gms, seinfo:untrusted
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4095): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,W/AlarmManager(  790): onSendFinished NameNotFoundException Pkg = com.google.android.gms
D/Headlines( 4095): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 4095): Breath 67416 latestRequest time : 1449626589671 current time : 1449626657088
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  790): stay LED for fully charged
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  790): mCoverManager.getCoverState() : true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/FactoryTest( 4742): Not factory mode
,D/FactoryTest( 4742): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4742): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4742): still no open session command from host, so toast
,W/ContextImpl( 4742): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4742): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  790): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  790): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  790): mDVFSHelper.acquire()
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/LockPatternUtils( 1069): isPcwEnable = null
,E/MTPRx   ( 4742): started activity for popup
,I/SQLiteSecureOpenHelper( 2114): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2114): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4742): PREF_DONT_ASK_AGAIN : false
,D/dalvikvm( 5499): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,D/SettingsReceiverActivity( 4742): dev.kiessupport is : TRUE
,I/SurfaceFlinger(  247): id=20 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4742): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4742): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4742): Remote Branch: 
I/Adreno-EGL( 4742): Local Patches: 
I/Adreno-EGL( 4742): Reconstruct Branch: 
,I/HWUI    ( 4742): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4742): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  790): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  790): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  790): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/dalvikvm( 5499): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
D/dalvikvm( 5499): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,D/dalvikvm( 5499): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,D/dalvikvm( 5499): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,D/dalvikvm( 5499): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,D/dalvikvm( 5499): DexOpt: load 159ms, verify+opt 977ms, 3139948 bytes
,D/PackageManager(  790): Time to dexopt: 1.596 seconds
,W/PackageManager(  790): Package com.google.android.gms declares lib com.google.android.gms that is not declared on system image; skipping
,D/PackageManager(  790): !@killApplicatoin: 10011, update pkg
,W/PackageManager(  790): Code path for pkg : com.google.android.gms changing from /data/app/com.google.android.gms-1.apk to /data/app/com.google.android.gms-2.apk
,W/PackageManager(  790): Resource path for pkg : com.google.android.gms changing from /data/app/com.google.android.gms-1.apk to /data/app/com.google.android.gms-2.apk
,D/PackageManager(  790): Time to scan apk: 1.894 seconds
,D/PackageManager(  790): updateSettingsLI: 
,W/PackageSettings(  790): Skipping PackageSetting{42ac1858 com.example.hello/10180} due to missing metadata
,D/dalvikvm(  790): GC_CONCURRENT freed 4076K, 52% free 27173K/55728K, paused 6ms+29ms, total 146ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 105ms
,D/PackageManager(  790): New package installed in 
,D/CustomFrequencyManagerService(  790): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1401600  uid : 1000  pid : 790  pkgName : SSRM_PKG_OPT@21
,D/dalvikvm(  790): GC_FOR_ALLOC freed 3554K, 58% free 23689K/55728K, paused 122ms, total 122ms
,I/dalvikvm-heap(  790): Grow heap (frag case) to 30.197MB for 3921416-byte allocation
,W/PackageManager(  790): Unknown permission com.sec.android.app.sns3.sp.facebook.permission.READ_DB in package com.sec.android.gallery3d
,W/PackageManager(  790): Unknown permission com.sec.knox.containeragent.USE_CONTAINERAGENT in package com.sec.android.gallery3d
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.sec.android.gallery3d
W/PackageManager(  790): Unknown permission com.sec.chaton.TOKEN_28e9e5f8058dc2fc70dea61856a21d58ed9c7edc1c5d9a9b15c7dc5cd78e317999676ad8618d2d2d9e600ebb75e8aee96abd57bdc06c6fe733898c5657971f32cffed5885a2efef4d9fd10ff675339558c04ab9e8c3dbc90c0d6b5b2f1f4f4e2d6f3c3658fae505e42224b61c140e442cd2c9faebf23df274bb173c5876a6912 in package com.sec.android.gallery3d
W/PackageManager(  790): Unknown permission com.sec.chaton.TOKEN_085376204d115cdd465b103094225633cb5e9707b4c76225285750054db230f38e719dd583e31939a616bac2e957cfb50beee4ff163f8c7903b2fdc7b6ef6f421570e4f459f9ebc0ac8c6cdd91cddf5c5945ddb36713571a55d279a9a711c785ec83dbe633884bbb80117461a05777408a335c9baa94f83d5da7b2acfb161fa1 in package com.sec.android.gallery3d
W/PackageManager(  790): Unknown permission com.samsung.android.app.episodes.permission.SEND_MULTIPLE_TO_STORYALBUM in package com.sec.android.gallery3d
W/PackageManager(  790): Unknown permission com.sec.android.spc.playerdb.READ_PLAYER_INFO in package com.sec.android.gallery3d
W/PackageManager(  790): Unknown permission com.sec.android.gallery3d.mapfragment.permission.MAPS_RECEIVE in package com.sec.android.gallery3d
,W/PackageManager(  790): Unknown permission sidesync.app.action.permission.KMS_FILETRANSFER_DRAG_FILEINFO in package com.sec.android.gallery3d
,W/PackageManager(  790): Unknown permission com.sec.dcm.provider.DCMProvider.data.READ in package com.sec.android.gallery3d
W/PackageManager(  790): Unknown permission com.sec.dcm.provider.DCMProvider.data.WRITE in package com.sec.android.gallery3d
,I/PowerManagerService-JNI(  790): >>>>>>>>in native...
W/PackageManager(  790): Unknown permission com.android.QualcommSettings.permission.UTS_DM_CMD in package com.android.phone
W/PackageManager(  790): Unknown permission android.permission.ADD_SYSTEM_SERVICE in package com.android.phone
W/PackageManager(  790): Unknown permission com.android.smspush.WAPPUSH_MANAGER_BIND in package com.android.phone
W/PackageManager(  790): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES_WRITE in package com.android.phone
W/PackageManager(  790): Unknown permission com.cequint.ecid.CALLER_ID_LOOKUP in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.InputEventApp.permission.UTS_DM_CMD in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsungtest.SlateTest.SLATE_DM_CMD in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.tmowfc.wfcprovider.permission.READ_WFCPROVIDER in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.tmowfc.wfcprovider.permission.WRITE_REGISTER in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.tmowfc.wfcprovider.permission.WRITE_SET_EMERGENCY in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.tmowfc.wfcprovider.permission.WRITE_EMERGENCY_CALL_STATE in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.rcs.cs.READ_PERMISSION in package com.android.phone
D/CustomFrequencyManagerService(  790): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 790  tag : ACTIVITY_RESUME_BOOSTER@9
D/CustomFrequencyManagerService(  790): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
W/PackageManager(  790): Unknown permission com.samsung.rcs.cs.WRITE_PERMISSION in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.rcs.serviceprovider.READ_PERMISSION in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.rcs.serviceprovider.WRITE_PERMISSION in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.rcs.permission.RCS_APP_PERMISSION in package com.android.phone
W/PackageManager(  790): Unknown permission com.sec.ims.android.PERMISSION in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.commonimsinterface.PERMISSION in package com.android.phone
W/PackageManager(  790): Unknown permission sstream.app.StoryProvider.WRITE.PERMISSION in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.android.sdk.smartassistant.permission.READ_CARD_PROVIDER in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.android.sdk.smartassistant.permission.WRITE_CARD_PROVIDER in package com.android.phone
W/PackageManager(  790): Unknown permission com.sec.android.app.hiddenmenu.permission.KEYSTRING in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.wmanager.ENABLE_NOTIFICATION in package com.android.phone
W/PackageManager(  790): Unknown permission com.itsoninc.android.permission.USE_ITSON_SERVICE in package com.android.phone
W/PackageManager(  790): Unknown permission com.samsung.syncservice.permission.OMADM.KEYSTRING in package com.android.phone
W/PackageManager(  790): Unknown permission com.skt.prod.permission.PHONE_SERVICE in package com.android.phone
,W/PackageManager(  790): Unknown permission com.verizon.vzwavs.permission.READ in package com.android.phone
W/PackageManager(  790): Unknown permission com.android.gallery3d.permission.GALLERY_PROVIDER in package com.android.bluetooth
W/PackageManager(  790): Unknown permission com.samsung.android.app.episodes.permission.IMPORT_STORYALBUM in package com.android.bluetooth
W/PackageManager(  790): Unknown permission com.samsung.android.app.shareaccessibilitysettings.permission.READ_WRITE in package com.android.bluetooth
W/PackageManager(  790): Unknown permission android.permission.READ_TASKS in package com.android.providers.calendar
W/PackageManager(  790): Unknown permission com.sec.dcm.provider.DCMProvider.START in package com.android.providers.calendar
W/PackageManager(  790): Unknown permission com.sec.android.widgetapp.q1_penmemo.permission.READ in package com.vlingo.midas
W/PackageManager(  790): Unknown permission com.sec.android.widgetapp.q1_penmemo.permission.WRITE in package com.vlingo.midas
W/PackageManager(  790): Unknown permission com.sec.android.permission.READ_MEMO in package com.vlingo.midas
W/PackageManager(  790): Unknown permission com.sec.android.permission.WRITE_MEMO in package com.vlingo.midas
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.vlingo.midas
W/PackageManager(  790): Unknown permission android.Manifest.permission.DISABLE_KEYGUARD in package com.vlingo.midas
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.READ in package com.vlingo.midas
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.WRITE in package com.vlingo.midas
W/PackageManager(  790): Unknown permission com.samsung.music.permission.READ_MUSIC_STORAGE in package com.vlingo.midas
W/PackageManager(  790): Unknown permission com.sec.android.daemonapp.ap.yonhapnews.permission.YONHAP_DAEMON_ACCESS_PROVIDER in package com.vlingo.midas
W/PackageManager(  790): Unknown permission com.sec.android.app.music.permission.READ_MUSICPROVIDER in package com.vlingo.midas
W/PackageManager(  790): Unknown permission samsung.android.snoteprovider.permission.READ in package com.vlingo.midas
W/PackageManager(  790): Not granting permission android.permission.INTERACT_ACROSS_USERS_FULL to package com.vlingo.midas (protectionLevel=2 flags=0x4098be45)
W/PackageManager(  790): Unknown permission com.android.mms.permission.RECEIVE_MESSAGES_INFORMATION in package com.vlingo.midas
W/PackageManager(  790): Unknown permission com.samsung.commonimsinterface.PERMISSION in package com.vlingo.midas
W/PackageManager(  790): Unknown permission samsung.snote.permission.MEMO_CONTROL in package com.vlingo.midas
W/PackageManager(  790): Unknown permission com.samsung.android.internal.intelligence.taskautomation.permission.ACTIVITYRULE in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission android.permission.WRITE_INTERNAL_STORAGE in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission com.sec.android.service.health.provider.READ in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission com.sec.android.service.health.provider.WRITE in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission com.sec.android.app.shealth.permission.MAPS_RECEIVE in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission com.rharham.RunningPro.permission.profile.Read in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission com.sec.android.permission.shealth_content_provider in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission com.samsung.accessory.permission.ACCESSORY_FRAMEWORK in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission com.sec.android.app.pedometer.COMMON_PERMISSION in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission com.samsung.android.sdk.samsunglink.permission.DB_READ_WRITE in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission com.samsung.android.sdk.samsunglink.permission.FILE_TRANSFER in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission com.samsung.android.sdk.samsunglink.permission.WAKE_LOCK in package com.sec.android.app.shealth
W/PackageManager(  790): Unknown permission com.sec.android.app.hiddenmenu.permission.KEYSTRING in package com.sec.factory
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.sec.factory
W/PackageManager(  790): Unknown permission android.permission.sec.BARCODE_READ in package com.sec.factory
W/PackageManager(  790): Unknown permission com.sec.android.widgetapp.q1_penmemo.permission.WRITE in package com.samsung.android.scloud.sync
W/PackageManager(  790): Unknown permission com.sec.android.widgetapp.q1_penmemo.permission.READ in package com.samsung.android.scloud.sync
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.READ in package com.samsung.android.scloud.sync
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.WRITE in package com.samsung.android.scloud.sync
W/PackageManager(  790): Unknown permission samsung.android.provider.snote2.permission.read in package com.samsung.android.scloud.sync
W/PackageManager(  790): Unknown permission samsung.android.provider.snote2.permission.write in package com.samsung.android.scloud.sync
W/PackageManager(  790): Unknown permission samsung.android.snoteprovider.permission.READ in package com.samsung.android.scloud.sync
W/PackageManager(  790): Unknown permission samsung.android.snoteprovider.permission.WRITE in package com.samsung.android.scloud.sync
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.sec.factory.camera
W/PackageManager(  790): Unknown permission com.samsung.android.app.episodes.permission.IMPORT_STORYALBUM in package com.android.providers.downloads.ui
W/PackageManager(  790): Unknown permission android.permission.INSTALL_DRM in package com.android.mms
W/PackageManager(  790): Unknown permission javax.microedition.gba.USE_GBA_SERVICE in package com.android.mms
W/PackageManager(  790): Unknown permission android.permission.ACCESS_GPS in package com.android.mms
W/PackageManager(  790): Unknown permission android.permission.ACCESS_LOCATION in package com.android.mms
W/PackageManager(  790): Unknown permission android.permission.ACCESS_ASSISTED_GPS in package com.android.mms
W/PackageManager(  790): Unknown permission android.permission.ACCESS_CELL_ID in package com.android.mms
W/PackageManager(  790): Unknown permission android.permission.ACCESS_COARSE_UPDATES in package com.android.mms
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.android.mms
W/PackageManager(  790): Not granting permission android.permission.MANAGE_NETWORK_POLICY to package com.android.mms (protectionLevel=2 flags=0x4098be65)
,W/PackageManager(  790): Not granting permission android.permission.ACCESS_SURFACE_FLINGER to package com.android.mms (protectionLevel=2 flags=0x4098be65)
W/PackageManager(  790): Unknown permission com.samsung.wmanager.ENABLE_NOTIFICATION in package com.android.mms
W/PackageManager(  790): Unknown permission com.samsung.tmowfc.wfcprovider.permission.READ_WFCPROVIDER in package com.android.mms
W/PackageManager(  790): Not granting permission android.permission.INTERNAL_SYSTEM_WINDOW to package com.android.mms (protectionLevel=2 flags=0x4098be65)
W/PackageManager(  790): Not granting permission android.permission.DEVICE_POWER to package com.android.mms (protectionLevel=2 flags=0x4098be65)
W/PackageManager(  790): Unknown permission com.samsung.commonimsinterface.PERMISSION in package com.android.mms
W/PackageManager(  790): Unknown permission com.sec.android.app.hiddenmenu.permission.KEYSTRING in package com.android.mms
W/PackageManager(  790): Not granting permission android.permission.CONTROL_KEYGUARD to package com.android.mms (protectionLevel=2 flags=0x4098be65)
W/PackageManager(  790): Unknown permission com.cequint.ecid.CALLER_ID_LOOKUP in package com.android.mms
W/PackageManager(  790): Unknown permission com.sec.android.app.groupvoicetalk.USE_ACTIVITY in package com.android.mms
W/PackageManager(  790): Unknown permission com.sec.android.service.health.provider.READ in package com.sec.android.service.health
W/PackageManager(  790): Unknown permission com.sec.android.service.health.provider.WRITE in package com.sec.android.service.health
W/PackageManager(  790): Unknown permission com.felicanetworks.mfc.permission.MFC_ACCESS in package com.sec.android.service.health
W/PackageManager(  790): Unknown permission com.sec.dcm.provider.DCMProvider.START in package com.android.providers.media
W/PackageManager(  790): Unknown permission com.sec.dcm.provider.DCMProvider.data.READ in package com.android.providers.media
W/PackageManager(  790): Unknown permission com.sec.dcm.provider.DCMProvider.data.WRITE in package com.android.providers.media
W/PackageManager(  790): Unknown permission com.android.setting.permission.NEARBY_SERVER in package com.sec.android.nearby.mediaserver
W/PackageManager(  790): Not granting permission android.permission.ACCESS_USB to package com.siso.app.generic (protectionLevel=18 flags=0x88be45)
W/PackageManager(  790): Unknown permission android.permission.READ_OWNER_DATA in package com.google.android.setupwizard
W/PackageManager(  790): Unknown permission android.permission.WRITE_OWNER_DATA in package com.google.android.setupwizard
W/PackageManager(  790): Unknown permission nof.permission.RECEIVE_USER_MODE in package com.sec.android.app.chromecustomizations
W/PackageManager(  790): Unknown permission android.permission.READ_INTERNAL_STORAGE in package com.sec.android.app.voicenote
W/PackageManager(  790): Unknown permission android.permission.ACCESS_DEV_STORAGE in package com.sec.android.app.voicenote
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.sec.android.app.voicenote
W/PackageManager(  790): Unknown permission com.sec.knox.containeragent.USE_CONTAINERAGENT in package com.sec.android.app.voicenote
W/PackageManager(  790): Unknown permission android.permission.WRITE_INTERNAL_STORAGE in package com.android.settings
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.android.settings
W/PackageManager(  790): Unknown permission com.sec.android.spc.account.READ_ACCOUNT_INFO in package com.android.settings
W/PackageManager(  790): Unknown permission com.sec.android.spc.account.WRITE_ACCOUNT_INFO in package com.android.settings
W/PackageManager(  790): Unknown permission com.samsung.rcs.settings.READ_PERMISSION in package com.android.settings
W/PackageManager(  790): Unknown permission com.samsung.rcs.settings.WRITE_PERMISSION in package com.android.settings
W/PackageManager(  790): Unknown permission com.samsung.tmowfc.wfcprovider.permission.READ_WFCPROVIDER in package com.android.settings
W/PackageManager(  790): Unknown permission com.samsung.tmowfc.wfcprovider.permission.WRITE_REGISTER in package com.android.settings
W/PackageManager(  790): Unknown permission com.sec.android.spc.MEMBER_MANAGEMENT in package com.android.settings
W/PackageManager(  790): Unknown permission com.sec.android.spc.service.BACKUP in package com.android.settings
W/PackageManager(  790): Unknown permission provider.settingsearch.permission.READ in package com.android.settings
W/PackageManager(  790): Unknown permission com.sec.android.permission.KNOX in package com.android.settings
W/PackageManager(  790): Unknown permission com.samsung.commonimsinterface.PERMISSION in package com.android.settings
W/PackageManager(  790): Unknown permission com.samsung.android.permission.GET_SECRET_PACKAGE_LIST in package com.android.settings
W/PackageManager(  790): Unknown permission com.samsung.android.sconnect.permission.ACCESS_QUICKCONNECT_WEARABLE in package com.android.settings
W/PackageManager(  790): Unknown permission com.google.android.voicesearch.SHORTCUTS_ACCESS in package com.google.android.googlequicksearchbox
W/PackageManager(  790): Unknown permission com.google.android.voicesearch.ACCESS_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager(  790): Unknown permission com.android.browser.permission.PRELOAD in package com.google.android.googlequicksearchbox
W/PackageManager(  790): Unknown permission com.google.android.ears.permission.WRITE in package com.google.android.googlequicksearchbox
W/PackageManager(  790): Unknown permission com.google.android.apps.googlevoice.permission.AUTO_SEND in package com.google.android.googlequicksearchbox
W/PackageManager(  790): Unknown permission com.google.android.launcher.permission.CONTENT_REDIRECT in package com.google.android.googlequicksearchbox
W/PackageManager(  790): Unknown permission com.android.email.ACCOUNT_INTENT in package com.android.exchange
W/PackageManager(  790): Unknown permission android.permission.READ_OWNER_DATA in package com.android.exchange
W/PackageManager(  790): Unknown permission android.permission.READ_TASKS in package com.sec.android.providers.tasks
W/PackageManager(  790): Unknown permission android.permission.WRITE_TASKS in package com.sec.android.providers.tasks
W/PackageManager(  790): Not granting permission android.permission.INTERACT_ACROSS_USERS_FULL to package com.samsung.groupcast (protectionLevel=2 flags=0x4098be45)
W/PackageManager(  790): Unknown permission com.TEDC.android.groupplay in package com.samsung.groupcast
W/PackageManager(  790): Unknown permission android.permission.SYSTEM_OVERLAY_WINDOW in package com.sec.android.app.safetyassurance
W/PackageManager(  790): Unknown permission com.sec.android.app.hiddenmenu.permission.KEYSTRING in package com.sec.android.RilServiceModeApp
W/PackageManager(  790): Unknown permission com.samsung.android.app.episodes.permission.IMPORT_STORYALBUM in package com.sec.android.app.FileShareClient
W/PackageManager(  790): Unknown permission android.permission.WRITE_SYNC_STATS in package com.google.android.apps.docs
W/PackageManager(  790): Unknown permission com.samsung.android.app.episodes.permission.IMPORT_STORYALBUM in package com.android.providers.downloads
W/PackageManager(  790): Unknown permission android.permission.ACCESS_DRM in package com.android.providers.downloads
W/PackageManager(  790): Unknown permission android.permission.INSTALL_DRM in package com.android.providers.downloads
W/PackageManager(  790): Not granting permission com.sec.enterprise.mdm.permission.BROWSER_PROXY to package com.android.providers.downloads (protectionLevel=2 flags=0x4088be45)
,W/PackageManager(  790): Unknown permission msc.permission.EXECUTE in package com.sec.android.app.msa
W/PackageManager(  790): Unknown permission msc.permission.STATUS in package com.sec.android.app.msa
W/PackageManager(  790): Unknown permission com.sec.android.permission.KNOX in package com.sec.android.app.msa
W/PackageManager(  790): Unknown permission com.samsung.android.permission.GET_SECRET_PACKAGE_LIST in package com.sec.android.app.easylauncher
W/PackageManager(  790): Not granting permission android.permission.DEVICE_POWER to package com.sec.android.app.easylauncher (protectionLevel=2 flags=0x40c8be45)
W/PackageManager(  790): Unknown permission android.permission.WRITE_INTERNAL_STORAGE in package com.sec.android.app.wallpaperchooser
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.READ in package com.sec.bcservice
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.WRITE in package com.sec.bcservice
W/PackageManager(  790): Unknown permission com.samsung.android.app.episodes.permission.IMPORT_STORYALBUM in package com.sec.android.app.FileShareServer
W/PackageManager(  790): Unknown permission android.permission.WRITE_INTERNAL_STORAGE in package com.sec.android.app.samsungapps
W/PackageManager(  790): Unknown permission android.permission.WIFI_LOCK in package com.sec.android.app.samsungapps
W/PackageManager(  790): Unknown permission com.sec.android.provider.una.astore.permission.WRITE in package com.sec.android.app.samsungapps
W/PackageManager(  790): Unknown permission com.sec.android.provider.una.astore.permission.READ in package com.sec.android.app.samsungapps
W/PackageManager(  790): Unknown permission com.sec.spp.push.permission.ACCESS_SPP_SERVER in package com.sec.android.app.samsungapps
W/PackageManager(  790): Unknown permission com.sec.android.wallet.permission in package com.sec.android.app.samsungapps
W/PackageManager(  790): Unknown permission sstream.app.StoryProvider.WRITE.PERMISSION in package com.sec.android.app.samsungapps
W/PackageManager(  790): Unknown permission com.samsung.android.permission.installApp in package com.sec.android.app.samsungapps
W/PackageManager(  790): Unknown permission com.sec.spp.permission.TOKEN_2e584d01f317fdee32cc8e855153d01df2a62f8194c5c4e621bf45bcc3807f066f637c5329f12f95158279f36aae6250df4a72e8d51fc6e578e248fcf11e8339654d20216c79a9d36fed33741d7190e77939da234b8157e48c3cdde7bc93bffdba1de18b6415d62b81b8d2dd41756f099ecb13fc4d975077a6d8cde99df4405b in package com.sec.android.app.samsungapps
W/PackageManager(  790): Unknown permission android.permission.ACCESS_FM_RECEIVER in package android
W/PackageManager(  790): Unknown permission com.sec.android.permission.SIDESYNC_SOURCE_PSS in package android
W/PackageManager(  790): Unknown permission com.sec.knox.migrationagent.permission.RECEIVE_MIGRATION in package android
,D/dalvikvm(  790): GC_CONCURRENT freed 347K, 54% free 27520K/59560K, paused 6ms+24ms, total 155ms
W/PackageManager(  790): Not granting permission android.permission.ACCESS_USB to package com.epson.mobilephone.samsungprintservice (protectionLevel=18 flags=0x88be45)
W/PackageManager(  790): Not granting permission android.permission.PACKAGE_USAGE_STATS to package com.android.providers.applications (protectionLevel=18 flags=0x88be45)
W/PackageManager(  790): Not granting permission com.sec.android.widgetapp.ap.hero.accuweather.permission.READ_ACCU_DATA to package com.sec.android.daemonapp (protectionLevel=18 flags=0x88be45)
W/PackageManager(  790): Not granting permission com.sec.android.widgetapp.ap.hero.accuweather.permission.WRITE_ACCU_DATA to package com.sec.android.daemonapp (protectionLevel=18 flags=0x88be45)
W/PackageManager(  790): Unknown permission com.samsung.commonimsinterface.PERMISSION in package com.android.incallui
W/PackageManager(  790): Unknown permission com.cequint.ecid.CALLER_ID_LOOKUP in package com.android.incallui
W/PackageManager(  790): Unknown permission com.samsung.rcs.cs.READ_PERMISSION in package com.android.incallui
W/PackageManager(  790): Unknown permission com.samsung.rcs.cs.WRITE_PERMISSION in package com.android.incallui
W/PackageManager(  790): Unknown permission com.samsung.rcs.serviceprovider.READ_PERMISSION in package com.android.incallui
W/PackageManager(  790): Unknown permission com.samsung.rcs.serviceprovider.WRITE_PERMISSION in package com.android.incallui
W/PackageManager(  790): Unknown permission com.samsung.rcs.permission.RCS_APP_PERMISSION in package com.android.incallui
W/PackageManager(  790): Unknown permission com.sec.ims.android.PERMISSION in package com.android.incallui
W/PackageManager(  790): Unknown permission com.samsung.tmowfc.wfcprovider.permission.READ_WFCPROVIDER in package com.android.incallui
W/PackageManager(  790): Unknown permission com.google.android.gallery3d.permission.PICASA_STORE in package com.google.android.apps.plus
W/PackageManager(  790): Unknown permission android.permission.REAL_GET_TASKS in package com.android.vending
W/PackageManager(  790): Not granting permission android.permission.SEND_DOWNLOAD_COMPLETED_INTENTS to package com.android.vending (protectionLevel=2 flags=0xcabec5)
W/PackageManager(  790): Unknown permission android.permission.USE_FINGERPRINT in package com.android.vending
W/PackageManager(  790): Unknown permission android.permission.GET_PACKAGE_IMPORTANCE in package com.android.vending
W/PackageManager(  790): Unknown permission android.permission.GET_ACCOUNTS_PRIVILEGED in package com.android.vending
W/PackageManager(  790): Unknown permission android.permission.INSTALL_GRANT_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  790): Unknown permission android.permission.GRANT_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  790): Unknown permission android.permission.REVOKE_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  790): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.android.vending
W/PackageManager(  790): Not granting permission android.permission.BATTERY_STATS to package com.android.vending (protectionLevel=18 flags=0xcabec5)
W/PackageManager(  790): Not granting permission android.permission.FORCE_STOP_PACKAGES to package com.android.vending (protectionLevel=2 flags=0xcabec5)
W/PackageManager(  790): Unknown permission android.permission.ACCESS_GPS in package com.sec.android.app.mt
W/PackageManager(  790): Unknown permission android.permission.ACCESS_LOCATION in package com.sec.android.app.mt
W/PackageManager(  790): Unknown permission com.sec.watchon.phone.BASIC_REMOCON in package com.samsung.android.sconnect
W/PackageManager(  790): Unknown permission com.sec.android.app.groupvoicetalk.USE_SCONNECT in package com.samsung.android.sconnect
W/PackageManager(  790): Unknown permission com.samsung.permission.wearable.CONNECT_ACCESS in package com.samsung.android.sconnect
W/PackageManage,r(  790): Unknown permission com.samsung.android.sconnect.permission.ACCESS_QUICKCONNECT_SIDESYNC in package com.samsung.android.sconnect
W/PackageManager(  790): Unknown permission com.sec.everglades.permission.ACCESS in package com.samsung.android.sdk.samsunglink
W/PackageManager(  790): Unknown permission com.smlds.permission.WSSDS in package com.wsomacp
W/PackageManager(  790): Unknown permission com.sec.android.app.browser.permission.Bookmark in package com.wsomacp
W/PackageManager(  790): Unknown permission com.sec.knox.containeragent.USE_KNOX_UI in package com.samsung.klmsagent
W/PackageManager(  790): Unknown permission android.permission.ACCESS_DRM in package com.sec.android.app.music
W/PackageManager(  790): Unknown permission com.sec.pcw.provider.PCloudContentProvider.READ_CONTENT in package com.sec.android.app.music
W/PackageManager(  790): Unknown permission com.sec.knox.containeragent.USE_CONTAINERAGENT in package com.sec.android.app.music
W/PackageManager(  790): Unknown permission com.samsung.musicplus.service.permission.ACCESSS_MUSIC_SERVICE in package com.sec.android.app.music
W/PackageManager(  790): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gsf (protectionLevel=2 flags=0x40883e45)
W/PackageManager(  790): Unknown permission android.intent.action.USER_PRESENT in package com.android.keyguard
W/PackageManager(  790): Unknown permission com.sec.android.signaturelock.permission.ACCESS_SIGNATURE in package com.android.keyguard
W/PackageManager(  790): Unknown permission com.sec.android.app.factorytest.permission.KEYSTRING in package com.sec.phone
W/PackageManager(  790): Unknown permission com.android.samsung.rmt_exercise.permission.KEYSTRING in package com.sec.phone
W/PackageManager(  790): Unknown permission com.samsungtest.SlateTest.SLATE_DM_CMD in package com.sec.phone
W/PackageManager(  790): Unknown permission com.samsung.InputEventApp.permission.UTS_DM_CMD in package com.sec.phone
W/PackageManager(  790): Unknown permission com.sec.android.app.InputEventApp.permission.KEYSTRING in package com.sec.phone
W/PackageManager(  790): Not granting permission android.permission.DEVICE_POWER to package com.android.contacts (protectionLevel=2 flags=0x4098be45)
W/PackageManager(  790): Unknown permission com.samsung.commonimsinterface.PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.sec.ims.android.volteenabled.READ_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.sec.ims.android.volteenabled.WRITE_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.sec.android.util.HiddenMenuContent.READ_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.sec.android.util.HiddenMenuContent.WRITE_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.samsung.tmowfc.wfcprovider.permission.READ_WFCPROVIDER in package com.android.contacts
W/PackageManager(  790): Unknown permission com.samsung.rcs.settings.READ_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.samsung.rcs.settings.WRITE_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.samsung.rcs.presence.READ_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.samsung.rcs.presence.WRITE_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.samsung.rcs.serviceprovider.READ_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.samsung.rcs.serviceprovider.WRITE_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.samsung.rcs.permission.RCS_APP_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.sec.ims.android.rcs.READ_PERMISSION in package com.android.contacts
W/PackageManager(  790): Unknown permission com.vcast.mediamanager.CLOUD_PERMISSION, in package com.android.contacts
W/PackageManager(  790): Unknown permission com.samsung.videohub.permission.CONTENT_READ in package com.samsung.everglades.video
W/PackageManager(  790): Unknown permission com.samsung.videohub.permission.CONTENT_WRITE in package com.samsung.everglades.video
W/PackageManager(  790): Unknown permission com.customermobile.demo.intent.action.DEMO_CONTROL in package com.sec.android.app.parser
W/PackageManager(  790): Unknown permission com.sec.android.app.hiddenmenu.permission.KEYSTRING in package com.sec.android.app.parser
W/PackageManager(  790): Unknown permission com.sec.android.voltesettings.permission.KEYSTRING in package com.sec.android.app.parser
W/PackageManager(  790): Unknown permission com.samsung.syncservice.permission.OMADM.KEYSTRING in package com.sec.android.app.parser
W/PackageManager(  790): Unknown permission com.samsung.difactorycamera.permission.ACCESS in package com.sec.android.app.parser
W/PackageManager(  790): Unknown permission com.samsung.dizoom.permission.ACCESS in package com.sec.android.app.parser
W/PackageManager(  790): Unknown permission com.marvell.diagsetting.permission.KEYSTRING in package com.sec.android.app.parser
W/PackageManager(  790): Unknown permission com.android.vending.billing.IBillingAccountService.BIND2 in package com.google.android.gsf.login
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.sec.android.inputmethod
W/PackageManager(  790): Unknown permission com.mirrorlink.android.service.ACCESS_PERMISSION in package com.sec.android.inputmethod
W/PackageManager(  790): Unknown permission com.sec.android.app.sns3.permission.READ_SNSDB in package com.android.calendar
W/PackageManager(  790): Unknown permission com.sec.android.app.sns3.sp.facebook.permission.READ_DB in package com.android.calendar
W/PackageManager(  790): Unknown permission com.sec.android.widgetapp.q1_penmemo.permission.READ in package com.android.calendar
W/PackageManager(  790): Unknown permission samsung.android.snoteprovider.permission.READ in package com.android.calendar
W/PackageManager(  790): Unknown permission samsung.android.snoteprovider.permission.WRITE in package com.android.calendar
W/PackageManager(  790): Unknown permission sstream.app.StoryProvider.WRITE.PERMISSION in package com.android.calendar
W/PackageManager(  790): Unknown permission com.sec.sCloudBackupApp.messages in package com.samsung.android.scloud.backup
W/PackageManager(  790): Unknown permission com.samsung.android.hostmanager.SCloudProvider.access in package com.samsung.android.scloud.backup
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.sec.android.app.sbrowser
W/PackageManager(  790): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES in package com.sec.android.app.sbrowser
W/PackageManager(  790): Unknown permission com.sec.android.permission.SIDESYNC_URL in package com.sec.android.app.sbrowser
W/PackageManager(  790): Unknown permission com.samsung.android.internal.intelligence.taskautomation.permission.ACTIVITYRULE in package com.sec.android.app.sbrowser
W/PackageManager(  790): Unknown permission com.samsung.android.sdk.smartassistant.permission.READ_CARD_PROVIDER in package com.sec.android.app.sbrowser
W/PackageManager(  790): Unknown permission com.samsung.android.sdk.smartassistant.permission.WRITE_CARD_PROVIDER in package com.sec.android.app.sbrowser
W/PackageManager(  790): Unknown permission nof.permission.RECEIVE_USER_MODE in package com.sec.android.app.sbrowser
W/PackageManager(  790): Unknown permission android.permission.SYSTEM_OVERLAY_WINDOW in package com.sec.android.GeoLookout
W/PackageManager(  790): Not granting permission android.permission.BROADCAST_PACKAGE_REMOVED to package com.google.android.marvin.talkback (protectionLevel=2 flags=0xc9be45)
W/PackageManager(  790): Unknown permission com.sec.android.gallery3d.permission.GALLERY_PROVIDER in package com.samsung.android.app.memo
W/PackageManager(  790): Not granting permission android.permission.ACCESS_USB to package com.siso.app.genericprintservice (protectionLevel=18 flags=0x88be45)
W/PackageManager(  790): Not granting permission android.permission.DEVICE_POWER to package com.sec.android.app.launcher (protectionLevel=2 flags=0x4098be45)
W/PackageManager(  790): Unknown permission com.dashwire.config.launcher.SEND_HOMESCREEN_RESULT in package com.sec.android.app.launcher
W/PackageManager(  790): Unknown permission com.samsung.android.providers.context.permission.READ_APP_USAGE_DB in package com.sec.android.app.launcher
W/PackageManager(  790): Unknown permission com.samsung.android.widgetapp.briefing4x2.permission.READ_APP_USAGE in package com.sec.android.app.launcher
W/PackageManager(  790): Unknown permission com.samsung.android.app.storyalbumwidget.permission.ACCESS_STORYALBUM_WIDGET in package com.sec.android.app.launcher
W/PackageManager(  790): Unknown permission com.samsung.android.tripwidget.permission.TRAVEL_WIDGET in package com.sec.android.app.launcher
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.sec.android.app.launcher
W/PackageManager(  790): Unknown permission com.sec.android.providers.insight.permission.READ_INSIGHT_DB in package com.sec.android.app.launcher
W/PackageManager(  790): Unknown permission sstream.app.StoryProvider.Covers.READ_PERMISSION in package com.sec.android.app.launcher
W/PackageManager(  790): Unknown permission com.sec.spp.permission.TOKEN_a1a30b694300dac6f59ae7b791d9eef52f677d5a5fe53412b7608126d463248f21f62f60c9bc92da81138bf6f292302d960c7273f648e5596bc9fea9ca594701e696c0917204658ac9f0e74745807472e9d3e9977f667274ee768334b7f9004f9a0046decafe7e068ad420d39e629d727f6b28195b118d7f7a4230be62243bd1 in package com.sec.spp.push
W/PackageManager(  790): Unknown permission com.sec.spp.permission.TOKEN_93826e86cec89c5a525ae83ddf9ebd98ecc233c92e8756bc704afa2d0778c64fdb5fef0d4cf09b8d73963b6df482827430806db3a69e587adc1c167cc50e7207453c58ea58cad7caaef5646b8deb9556378af5867696aa51fbca0e2f918d7d12a6f0b7acd5bba2d48c6688ee2089b816ad6fb0bc395f6986b71129090f423d3d in package com.sec.spp.push
W/PackageManager(  790): Unknown permission com.google.android.gallery3d.permission.PICASA_STORE in package com.android.dreams.phototable
W/PackageManager(  790): Not granting permission com.samsung.clipboardsaveservice.CLIPBOARDSAVESERVICE_PERMISSION to package com.infraware.polarisviewer5 (protectionLevel=18 flags=0x98be45)
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.infraware.polarisviewer5
W/PackageManager(  790): Unknown permission com.android.nfc.permission.NFCEE_ADMIN in package org.simalliance.openmobileapi.service
W/PackageManager(  790): Unknown permission android.permission.ACCESS_DEV_STORAGE in package com.samsung.indexservice
W/PackageManager(  790): Unknown permission tv.peel.smartremote.REMOTE_CONTROL in package tv.peel.smartremote
W/PackageManager(  790): Unknown permission android.permission.NETWORK_STATE_CHANGED_ACTION in package tv.peel.smartremote
W/PackageManager(  790): Not granting permission android.permission.DEVICE_POWER to package tv.peel.smartremote (protectionLevel=2 flags=0x882c45)
W/PackageManager(  790): Unknown permission sstream.app.StoryProvider.WRITE.PERMISSION in package tv.peel.smartremote
W/PackageManager(  790): Not granting permission com.samsung.android.internal.intelligence.useranalysis.permission.READ_PLACE to package tv.peel.smartremote (protectionLevel=18 flags=0x882c45)
W/PackageManager(  790): Not granting permission com.samsung.android.internal.intelligence.useranalysis.permission.WRITE_PLACE to package tv.peel.smartremote (protectionLevel=18 flags=0x882c45)
W/PackageManager(  790): Unknown permission tv.peel.samsung.app.permission.C2D_MESSAGE in package tv.peel.smartremote
W/PackageManager(  790): Unknown permission android.permission.READ_OWNER_DATA in package com.sec.android.app.SecSetupWizard
W/PackageManager(  790): Unknown permission android.permission.WRITE_OWNER_DATA in package com.sec.android.app.SecSetupWizard
W/PackageManager(  790): Not granting permission android.permission.INTERACT_ACROSS_USERS_FULL to package com.sec.android.app.sns3 (protectionLevel=2 flags=0x4088be45)
W/PackageManager(  790): Unknown permission com.twitter.android.permission.AUTH_APP in package com.sec.android.app.sns3
W/PackageManager(  790): Unknown permission com.samsung.difactorycamera.permission.ACCESS in package com.sec.android.app.hwmoduletest
W/PackageManager(  790): Unknown permission android.permission.sec.BARCODE_READ in package com.sec.android.app.hwmoduletest
W/PackageManager(  790): Unknown permission android.permission.WRITE_OWNER_DATA in package com.sec.android.app.hwmoduletest
W/PackageManager(  790): Unknown permission android.permission.sec.BARCODE_READ in package com.sec.android.app.factorykeystring
W/PackageManager(  790): Unknown permission android.permission.WRITE_OWNER_DATA in package com.sec.android.app.factorykeystring
W/PackageManager(  790): Unknown permission com.sec.knox.containeragent.USE_KNOX_UI in package com.android.packageinstaller
W/PackageManager(  790): Unknown permission com.sec.android.app.shealth.HELP in package com.samsung.helphub
W/PackageManager(  790): Unknown permission com.sec.android.emeeting.activities.HelpTryitActivity in package com.samsung.helphub
W/PackageManager(  790): Unknown permission com.samsung.android.snote.permission.HELP in package com.samsung.helphub
W/PackageManager(  790): Unknown permission com.samsung.android.chartbuilder.permission.HELP in package com.samsung.helphub
W/PackageManager(  790): Unknown permission com.sec.android.systemui.PICKUP_TUTORIAL_PERMISSION in package com.samsung.helphub
W/PackageManager(  790): Unknown permission com.samsung.android.sdk.smartassistant.permission.READ_CARD_PROVIDER in package com.sec.android.sviewcover
W/PackageManager(  790): Unknown permission com.samsung.android.sdk.smartassistant.permission.WRITE_CARD_PROVIDER in package com.sec.android.sviewcover
W/PackageManager(  790): Unknown permission com.mocana.vpn.android.permission.MOCANA_VPN_SERVICE in package com.sec.enterprise.knox.cloudmdm.smdms
W/PackageManager(  790): Unknown permission com.samsung.android.sdk.smartassistant.permission.READ_CARD_PROVIDER in package com.android.email
W/PackageManager(  790): Unknown permission com.samsung.android.sdk.smartassistant.permission.WRITE_CARD_PROVIDER in package com.android.email
W/PackageManager(  790): Unknown permission android.permission.READ_OWNER_DATA in package com.android.email
W/PackageManager(  790): Unknown permission com.sec.android.app.gallery3d.READ in package com.android.email
W/PackageManager(  790): Unknown permission com.sec.android.app.gallery3d.WRITE in package com.android.email
W/PackageManager(  790): Unknown permission com.samsung.wmanager.ENABLE_NOTIFICATION in package com.android.email
W/PackageManager(  790): Unknown permission com.seven.Z7.permission.ACCESS_PROVIDER in package com.android.email
W/PackageManager(  790): Unknown permission com.seven.Z7.permission.ACCESS_EVENTS in package com.android.email
W/PackageManager(  790): Unknown permission android.permission.ACCESS_DEV_STORAGE in package com.android.email
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.android.email
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.READ in package com.android.email
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.WRITE in package com.android.email
W/PackageManager(  790): Unknown permission android.permission.ACCESS_GPS in package com.android.email
W/PackageManager(  790): Unknown permission com.sds.mobiledesk.permission.READ_PROVIDER in package com.android.email
W/PackageManager(  790): Unknown permission com.sds.mobiledesk.permission.WRITE_PROVIDER in package com.android.email
W/PackageManager(  790): Unknown permission com.sec.android.app.gallery3d.READ in package com.sec.android.mimage.photoretouching
W/PackageManager(  790): Unknown permission com.sec.android.app.gallery3d.WRITE in package com.sec.android.mimage.photoretouching
W/PackageManager(  790): Unknown permission samsung.android.snoteprovider.permission.READ in package com.samsung.android.app.galaxyfinder
W/PackageManager(  790): Unknown permission com.samsung.android.app.episodes.permission.LAUNCH_MAGAZINE in package com.samsung.android.app.galaxyfinder
W/PackageManager(  790): Unknown permission com.samsung.android.app.episodes.permission.SEND_MULTIPLE_TO_STORYALBUM in package com.samsung.android.app.galaxyfinder
W/PackageManager(  790): Unknown permission com.samsung.android.app.lifetimes.permission.READ_LOGS in package com.samsung.android.app.galaxyfinder
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.samsung.android.app.galaxyfinder
W/PackageManager(  790): Unknown permission com.sec.chaton.TOKEN_42796342bfa89776ee3a3370879ddfa35c6dc31678caab1b811180618cc7b18c96d9806a4b0b3bc5513fdddd567d413187e0693a1eddc65b1462b571ff1a7a71192936384285c76367d367c250181be518d4857a8318e294ec06e8899fe77ea028c888292da8dad2f908952a38a590cd9479e6a9a1433875b435e16c4b90bb3a in package com.samsung.android.app.galaxyfinder
W/PackageManager(  790): Unknown permission com.sec.dcm.provider.DCMProvider.data.READ in package com.samsung.android.app.galaxyfinder
W/PackageManager(  790): Unknown permission com.sec.android.permission.READ_MEMO in package com.wssnps
W/PackageManager(  790): Unknown permission com.sec.android.permission.WRITE_MEMO in package com.wssnps
W/PackageManager(  790): Unknown permission com.sec.android.widgetapp.q1_penmemo.permission.READ in package com.wssnps
W/PackageManager(  790): Unknown permission com.sec.android.widgetapp.q1_penmemo.permission.WRITE in package com.wssnps
W/PackageManager(  790): Unknown permission android.permission.READ_MMS in package com.wssnps
W/PackageManager(  790): Unknown permission android.permission.WRITE_MMS in package com.wssnps
W/PackageManager(  790): Unknown permission android.permission.READ_TASKS in package com.wssnps
W/PackageManager(  790): Unknown permission android.permission.WRITE_TASKS in package com.wssnps
W/PackageManager(  790): Unknown permission com.sec.android.app.fm.BROADCAST_DETECT in package com.wssnps
W/PackageManager(  790): Unknown permission com.sec.mms.action.MMS_BNR in package com.wssnps
W/PackageManager(  790): Unknown permission com.sec.android.app.minidiary.service.BROADCAST_DETECT in package com.wssnps
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.READ in package com.wssnps
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.WRITE in package com.wssnps
W/PackageManager(  790): Unknown permission com.sec.permission.VZW_KIES_LOCATION_PERMISSION in package com.wssnps
W/PackageManager(  790): Unknown permission com.wss.android.spdagent.permission.C2D_MESSAGE in package com.policydm
W/PackageManager(  790): Unknown permission com.sec.android.permission.KNOX in package com.policydm
W/PackageManager(  790): Unknown permission com.samsung.spd.SBA_RELOAD in package com.policydm
W/PackageManager(  790): Unknown permission com.android.launcher.permission.PRELOAD_WORKSPACE in package com.google.android.partnersetup
W/PackageManager(  790): Unknown permission com.samsung.permission.wearable.CONNECT_ACCESS in package com.samsung.android.app.watchmanagerstub
W/PackageManager(  790): Unknown permission android.permission.ACCESS_DEV_STORAGE in package com.sec.android.app.camera
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.sec.android.app.camera
W/PackageManager(  790): Unknown permission com.samsung.android.provider.filterprovider.permission.READ_FILTER in package com.sec.android.app.camera
W/PackageManager(  790): Unknown permission com.samsung.android.provider.filterprovider.permission.WRITE_FILTER in package com.sec.android.app.camera
W/PackageManager(  790): Unknown permission android.permission.CALL in package com.sec.knox.bridge
W/PackageManager(  790): Unknown permission android.Manifest.permission.GET_TASKS in package com.sec.knox.bridge
W/PackageManager(  790): Unknown permission com.sec.knox.migrationagent.permission.RECEIVE_MIGRATION in package com.sec.knox.bridge
W/PackageManager(  790): Unknown permission android.permission.ACCESS_DEV_STORAGE in package com.sec.android.app.myfiles
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.sec.android.app.myfiles
W/PackageManager(  790): Unknown permission com.sec.knox.containeragent.USE_CONTAINERAGENT in package com.sec.android.app.myfiles
W/PackageManager(  790): Unknown permission sidesync.app.action.permission.KMS_FILETRANSFER_DRAG_FILEINFO in package com.sec.android.app.myfiles
W/PackageManager(  790): Unknown permission com.sec.spp.permission.TOKEN_afb2a3b493828da000991355f51942d432670bea558bcec99b4b797614a73ca5871b3ecc601cfa54ed06b0fb65813498197e9cc00edaca07676a14c64b581c990ef9b45f52888b7803c03a33df3fcdf242ab0764a3be7aa20c2c8dfd4c1266666249a01308aafd856aa29ad0522bf76fc31f873e5c1fe6120f218d0eb5b121d4 in package com.samsung.android.providers.context
W/PackageManager(  790): Unknown permission com.sec.android.homesync.EXCLUSIVE_APP in package com.osp.app.signin
W/PackageManager(  790): Not granting permission android.permission.INTERACT_ACROSS_USERS_FULL to package com.osp.app.signin (protectionLevel=2 flags=0x4098be05)
W/PackageManager(  790): Unknown permission android.permission.READ_SETTINGS in package com.osp.app.signin
W/PackageManager(  790): Unknown permission com.sec.spp.permission.TOKEN_629e52d85fa91d200413707985ff2b21bb923206e41b8543e55c1d440a5edeb2e28d48d440dc7c7fb7f60eb39577517265b780609c8556eddbc673d21db4d7db6f17fe1b322387178eb0dc77b180f6154e4ad60bf64418c03ee0990b8783734fde37e5f82e089a04273b4650527a6b1335e2e99e94450386fd1c692106b58553 in package com.osp.app.signin
W/PackageManager(  790): Unknown permission com.qualcomm.permission.ACCESS_LOCATION_API in package com.qualcomm.location
W/PackageManager(  790): Unknown permission android.permission.ACCESS_DRM in package com.samsung.android.MtpApplication
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.samsung.android.MtpApplication
W/PackageManager(  790): Not granting permission android.permission.INTERACT_ACROSS_USERS to package com.android.dreams.basic (protectionLevel=50 flags=0x88be45)
W/PackageManager(  790): Unknown permission android.permission.ACCESS_DEV_STORAGE in package com.sec.android.app.bcocr
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.sec.android.app.bcocr
W/PackageManager(  790): Not granting permission com.samsung.android.permission.SSRM_NOTIFICATION_PERMISSION to package com.sec.android.app.bcocr (protectionLevel=18 flags=0x98be45)
W/PackageManager(  790): Not granting permission android.permission.INTERACT_ACROSS_USERS_FULL to package com.sec.android.app.billing (protectionLevel=2 flags=0x4088be45)
W/PackageManager(  790): Unknown permission android.permission.READ_INTERNAL_STORAGE in package com.sec.android.app.billing
W/PackageManager(  790): Unknown permission android.permission.WRITE_INTERNAL_STORAGE in package com.sec.android.app.billing
W/PackageManager(  790): Unknown permission com.sec.spp.push.permission.ACCESS_SPP_SERVER in package com.sec.android.app.billing
W/PackageManager(  790): Unknown permission com.sec.android.app.gallery3d.READ in package com.sec.android.mimage.sstudio
W/PackageManager(  790): Unknown permission com.sec.android.app.gallery3d.WRITE in package com.sec.android.mimage.sstudio
W/PackageManager(  790): Unknown permission com.sec.android.daemonapp.ap.accuweather.permission.ACCU_DAEMON_ACCESS_INTENT in package com.sec.android.app.clockpackage
W/PackageManager(  790): Unknown permission com.sec.android.app.calendar.permission.CHANGE_CALENDAR_PREFERENCE in package com.sec.android.app.clockpackage
W/PackageManager(  790): Unknown permission com.samsung.tmowfc.wfcprovider.permission.READ_WFCPROVIDER in package com.android.systemui
W/PackageManager(  790): Unknown permission com.samsung.tmowfc.wfcprovider.permission.WRITE_REGISTER in package com.android.systemui
W/PackageManager(  790): Unknown permission com.sec.android.app.sbrowser.operatorbookmarks.permission.READ_OPERATOR_BOOKMARKS in package com.samsung.sec.android.application.csc
W/PackageManager(  790): Unknown permission com.sec.android.app.sbrowser.operatorbookmarks.permission.WRITE_OPERATOR_BOOKMARKS in package com.samsung.sec.android.application.csc
W/PackageManager(  790): Unknown permission com.sec.android.permission.READ_MEMO in package com.samsung.sec.android.application.csc
W/PackageManager(  790): Unknown permission com.sec.android.permission.WRITE_MEMO in package com.samsung.sec.android.application.csc
W/PackageManager(  790): Unknown permission com.sec.android.widgetapp.q1_penmemo.permission.READ in package com.samsung.sec.android.application.csc
W/PackageManager(  790): Unknown permission com.sec.android.widgetapp.q1_penmemo.permission.WRITE in package com.samsung.sec.android.application.csc
W/PackageManager(  790): Unknown permission android.permission.ACCESS_DRM in package com.sec.android.app.videoplayer
W/PackageManager(  790): Unknown permission com.sec.android.app.twdvfs.DVFS_BOOSTER_PERMISSION in package com.sec.android.app.videoplayer
W/PackageManager(  790): Unknown permission android.permission.SYSTEM_ALERT in package com.sec.android.app.videoplayer
W/PackageManager(  790): Unknown permission com.sec.pcw.provider.PCloudContentProvider.READ_CONTENT in package com.sec.android.app.videoplayer
W/PackageManager(  790): Unknown permission sstream.app.StoryProvider.WRITE.PERMISSION in package com.sec.android.app.videoplayer
W/PackageManager(  790): Unknown permission com.samsung.videohub.permission.CONTENT_READ in package com.sec.android.app.videoplayer
W/PackageManager(  790): Unknown permission com.samsung.videohub.permission.CONTENT_WRITE in package com.sec.android.app.videoplayer
W/PackageManager(  790): Unknown permission com.sec.android.permission.READ_MEMO in package com.sec.android.app.DataCreate
W/PackageManager(  790): Unknown permission com.sec.android.permission.WRITE_MEMO in package com.sec.android.app.DataCreate
W/PackageManager(  790): Unknown permission com.sec.android.widgetapp.q1_penmemo.permission.READ in package com.sec.android.app.DataCreate
W/PackageManager(  790): Unknown permission com.sec.android.widgetapp.q1_penmemo.permission.WRITE in package com.sec.android.app.DataCreate
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.READ in package com.sec.android.app.DataCreate
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.WRITE in package com.sec.android.app.DataCreate
W/PackageManager(  790): Not granting permission android.permission.WRITE_SECURE_SETTINGS to package com.sec.android.widgetapp.dualclockdigital (protectionLevel=50 flags=0x88be45)
W/PackageManager(  790): Not granting permission android.permission.CHANGE_CONFIGURATION to package com.blurb.checkout (protectionLevel=50 flags=0x88be45)
W/PackageManager(  790): Not granting permission android.permission.MOUNT_UNMOUNT_FILESYSTEMS to package com.blurb.checkout (protectionLevel=18 flags=0x88be45)
W/PackageManager(  790): Unknown permission com.samsung.android.app.episodes.permission.PUBLISH_IMAGES_COMPLETE in package com.blurb.checkout
W/PackageManager(  790): Not granting permission android.permission.MANAGE_DOCUMENTS to package com.google.android.youtube (protectionLevel=18 flags=0x98be45)
W/PackageManager(  790): Unknown permission com.sec.knox.migrationagent.permission.RECEIVE_MIGRATION in package com.sec.knox.knoxsetupwizardclient
W/PackageManager(  790): Unknown permission com.chrome.permission.DEVICE_EXTRAS in package com.android.chrome
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.READ in package com.sec.android.Kies
W/PackageManager(  790): Unknown permission com.infraware.provider.SNoteProvider.permission.WRITE in package com.sec.android.Kies
D/EnterpriseDeviceManagerService(  790): updateAdminPermissions
W/PackageManager(  790): Unknown permission com.sec.android.permission.KNOX in package com.sec.knox.seandroid
W/PackageManager(  790): Unknown permission android.permission.OBSERVE_GRANT_REVOKE_PERMISSIONS in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.RECOVERY in package com.google.android.gms
W/PackageManager(  790): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gms (protectionLevel=2 flags=0xc83ec5)
W/PackageManager(  790): Unknown permission android.permission.PROVIDE_TRUST_AGENT in package com.google.android.gms
W/PackageManager(  790): Unknown permission com.google.android.apps.enterprise.dmagent.permission.AutoSyncPermission in package com.google.android.gms
W/PackageManager(  790): Not granting permission android.permission.PACKAGE_USAGE_STATS to package com.google.android.gms (protectionLevel=18 flags=0xc83ec5)
W/PackageManager(  790): Unknown permission android.permission.MANAGE_VOICE_KEYPHRASES in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.REAL_GET_TASKS in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.READ_WIFI_CREDENTIAL in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.SCORE_NETWORKS in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.CONTROL_INCALL_EXPERIENCE in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.USER_ACTIVITY in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.MODIFY_AUDIO_ROUTING in package com.google.android.gms
W/PackageManager(  790): Unknown permission com.google.android.wearable.READ_SETTINGS in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.INTENT_FILTER_VERIFICATION_AGENT in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.LOCAL_MAC_ADDRESS in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.BODY_SENSORS in package com.google.android.gms
W/PackageManager(  790): Unknown permission android.permission.NOTIFY_PENDING_SYSTEM_UPDATE in package com.google.android.gms
W/PackageManager(  790): Unknown permission com.google.android.launcher.permission.RECEIVE_LAUNCH_BROADCASTS in package com.google.android.gms
W/PackageManager(  790): Unknown permission com.android.voicemail.permission.READ_VOICEMAIL in package com.google.android.gms
,I/PowerManagerService-JNI(  790): CheckForString returning : 2
W/PackageSettings(  790): Skipping PackageSetting{42ac1858 com.example.hello/10180} due to missing metadata
D/CustomFrequencyManagerService(  790): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1401600  uid : 1000  pid : 790  tag : SSRM_PKG_OPT@21
,D/PackageManager(  790): doPostInstall for uid{10011}
D/PackageManager(  790): + starting rerstore round-trip 2
,D/PackageManager(  790): No resotre for backup - queue post-install for 2
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "sms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "smsto"
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mmsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/PackageManager(  790): [MSG] MCS_UNBIND
I/PackageManager(  790): calling disconnectService()
,D/PackageManager(  790): Trying to unbind to DefaultContainerService
,D/PackageManager(  790): [MSG] CHECK_PENDING_VERIFICATION
D/PackageManager(  790): [MSG] POST_INSTALL: observer{1126123200}
D/PackageManager(  790):           Handling post-install for 2
,D/PackageManager(  790): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=false, android.intent.extra.UID=10011, android.intent.extra.DATA_REMOVED=false, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,I/ActivityManager(  790): Killing 4440:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,D/dalvikvm( 4692): GC_EXPLICIT freed 5141K, 47% free 10226K/18972K, paused 3ms+4ms, total 51ms
,D/dalvikvm( 2183): GC_EXPLICIT freed 1012K, 41% free 11240K/18972K, paused 8ms+4ms, total 93ms
,D/AdaptiveEventManager( 1069): action=android.intent.action.PACKAGE_REMOVED
,I/FPMS_FingerprintManagerService( 1088): onReceive: android.intent.action.PACKAGE_REMOVED
,D/QuickConnect[1.1][2] ( 3352): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.google.android.gms
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "sms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 5542): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5542):  
I/InputReader(  790): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 1413): GC_EXPLICIT freed 4282K, 48% free 10019K/18972K, paused 6ms+5ms, total 103ms
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "smsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService(  790): PackageReceiver onReceive()
I/SELinux ( 5542): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5542):  
I/SELinux ( 5542):  
,I/SELinux ( 5542): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5542): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5542): >>>>> Normal User
,E/dalvikvm( 5542): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 5542): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager(  790): Sending to user 0: act=android.intent.action.PACKAGE_ADDED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.UID=10011, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mms"
,I/HarmonyEASService(  790): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 5542): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5542): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5542): Added TimaKesytore provider
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mmsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PackageManager(  790): Sending to user 0: act=android.intent.action.PACKAGE_REPLACED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.UID=10011, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "sms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/QuickConnect[1.1][2] ( 3352): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_ADDED, package : com.google.android.gms
,I/InputReader(  790): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "smsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PackageManager(  790): Sending to user 0: act=android.intent.action.MY_PACKAGE_REPLACED flg=0x4000000 pkg=com.google.android.gms Bundle[{android.intent.extra.user_handle=0}]
,W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5542, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/BackupManagerService(  790): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mms"
,I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/InputReader(  790): Reconfiguring input devices.  changes=0x00000010
,D/elm:14132( 5542): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.gms flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 5542): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5542): MDMBridge.setEnterpriseBridge()
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mmsto"
,I/SELinux ( 5554): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5554):  
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService(  790): PackageReceiver onReceive()
,D/RCPManagerService(  790): App Installed with packageNAme = com.google.android.gms
D/RCPManagerService(  790):  PackageReceiver onReceive() bundle Bundle[{GoogleNowActions=2131230742, com.google.android.gms.MAJOR_RELEASE_NUMBER=8, com.google.android.gms.appdatasearch=2131230720, android.app.default_searchable=.googlehelp.helpactivities.HelpActivity, com.google.android.gms.API_KEY=AIzaSyAP-gfH3qvi6vgHZbSYwQ_XHqV_mXHhzIk, com.google.android.geo.API_KEY=AIzaSyAP-gfH3qvi6vgHZbSYwQ_XHqV_mXHhzIk, com.google.android.gms.version=8489000}]
,D/RCPManagerService(  790):  PackageReceiver onReceive() proxyName null proxyService null
,D/dalvikvm(  248): GC_EXPLICIT freed 43K, 50% free 9509K/18972K, paused 2ms+3ms, total 39ms
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "sms"
I/SELinux ( 5554): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5554):  
I/SELinux ( 5554):  
,I/SELinux ( 5554): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SELinux ( 5554): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5554): >>>>> Normal User
E/dalvikvm( 5554): >>>>> com.google.android.gms.persistent [ userId:0 | appId:10011 ]
E/SELinux ( 5554): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/SQLiteConnectionPool(  790): exportDB...
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18972K, paused 1ms+2ms, total 18ms
D/elm:14132( 5542): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.gms flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5542): ElmAgentService : onCreate()
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "smsto"
D/TimaKeyStoreProvider( 5554): in addTimaSignatureService
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18972K, paused 2ms+2ms, total 19ms
D/TimaKeyStoreProvider( 5554): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5554): Added TimaKesytore provider
,D/elm:14132( 5542): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.gms flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/BackupManagerService(  790): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
V/BackupManagerService(  790): removePackageParticipantsLocked: uid=10011 #1
,D/PersonaPolicyManagerService(  790): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
V/BackupManagerService(  790): addPackageParticipantsLocked: #1
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/SMD     (  241): DCD ON
,D/elm:14132( 5542): ElmAgentService : onDestroy().
,W/Babel   ( 4692): Gms package replaced. Will trigger a restart of babel
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mmsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 5570): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5570):  
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "sms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SQLiteConnectionPool(  790): ...exportDB
D/EnterpriseDeviceManagerService(  790): onPackageUpdateFinished - packageName: com.google.android.gms, uid: 10011
,D/EnterpriseDeviceManagerService(  790): Admin found on map with same package name!
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "smsto"
I/SELinux ( 5570): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5570):  
I/SELinux ( 5570):  
,I/SELinux ( 5570): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5570): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5570): >>>>> Normal User
,E/dalvikvm( 5570): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SELinux ( 5570): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "mmsto"
,D/TimaKeyStoreProvider( 5570): in addTimaSignatureService
,I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 5570): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5570): Added TimaKesytore provider
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "sms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/ActivityManager(  790): Killing 4467:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,W/dalvikvm( 5554): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5554): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 5554): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5554): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 5554): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5554): install
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "smsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/MultiDex( 5554): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,D/EnterpriseDeviceManagerService(  790): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  790): Admin package name: com.google.android.gms
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mmsto"
,I/MultiDex( 5554): Detected that extraction must be performed.
,I/MultiDex( 5554): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.dex of size 8190776
,I/MultiDex( 5554): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.dex
,I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/MultiDex( 5554): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.dex of size 6209128
I/MultiDex( 5554): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.dex
I/MultiDex( 5554): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.dex of size 7647760
I/MultiDex( 5554): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.dex
I/MultiDex( 5554): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip of size 2442399
I/MultiDex( 5554): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip
I/MultiDex( 5554): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip of size 2874084
I/MultiDex( 5554): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip
I/MultiDex( 5554): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip of size 2912239
I/MultiDex( 5554): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "sms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm(  790): GC_EXPLICIT freed 7336K, 57% free 24044K/55192K, paused 5ms+17ms, total 454ms
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "smsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PackageManager(  790): delete sourFile : 
,D/PackageManager(  790): delete native library directory: 
D/PackageManager(  790): return install result to caller: 1126123200
,D/Finsky  ( 3720): [338] PackageManagerHelper$OnCompleteListenerNotifier$1.packageInstalled: Package install status for com.google.android.gms is 1
,D/PackageManager(  790): returnCode: 1
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mms"
W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5570, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mmsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 5570): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4265dda8, skipping init
I/SecureStorage( 5570): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 5570): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  293): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5570
I/SecureStorage(  293): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
,I/SecureStorage( 5570): [INFO]: SPID(0x00000000)SS Daemon is running
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Finsky  ( 3720): [1] InstallerTask$3.installSucceeded: Successful install of com.google.android.gms
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/File    ( 3720): fail readDirectory() errno=2
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    (  228): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3720): Failed to ensure directory: /storage/extSdCard/Android/data/com.android.vending/files
I/MultiDex( 5554): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip
I/MultiDex( 5554): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes-198933658.zip
,I/SecureStorage( 5570): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  293): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5570
,I/SecureStorage(  293): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector(  790): onPackageUpdateFinished : com.google.android.gms
,I/SELinux ( 5588): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5588):  
,I/SELinux ( 5588): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5588):  
I/SELinux ( 5588):  
,I/SELinux ( 5588): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5588): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5588): >>>>> Normal User
,E/dalvikvm( 5588): >>>>> com.google.android.gms [ userId:0 | appId:10011 ]
,E/SELinux ( 5588): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/ApplicationsProvider( 1413): Could not fetch usage stats
W/ApplicationsProvider( 1413): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1413): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1413): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1413): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1413): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 1413): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1413): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1413): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/AlarmManager(  790): waitForAlarm result :4
,D/TimaKeyStoreProvider( 5588): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5588): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5588): Added TimaKesytore provider
,W/ApplicationsProvider( 1413): Could not fetch usage stats
W/ApplicationsProvider( 1413): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1413): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1413): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1413): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1413): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1413): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1413): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1413): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/SSRMv2:SIOP(  790): SIOP:: AP = 330, Delta = 10
,W/dalvikvm( 5588): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5588): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 5588): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5588): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 5588): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5588): install
,I/MultiDex( 5588): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 5588): Detected that extraction must be performed.
,I/MultiDex( 5588): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip
,I/MultiDex( 5588): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes1610579649.zip
,I/HarmonyEASService(  790): Updating for all 1
,I/SecureStorage(  293): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  293): [INFO]: SPID(0x00000004)PID: 5570, TID: 5570
D/PackageManager(  790): [MSG] CHECK_PENDING_VERIFICATION
,I/SecureStorage( 5570): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 5570): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 5570): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 5570): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 5570): Open platform.db in secure mode
,I/SQLiteSecureOpenHelper( 5570): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 5570): ...getDatabaseLocked(b,b,pwd)
,I/PCWCLIENTTRACE_PushUtil( 5214): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5214): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5214): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5214): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 4042): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4042): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager(  790): Killing 4603:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,I/SELinux ( 5607): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5607):  
,I/SELinux ( 5607): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5607):  
I/SELinux ( 5607):  
,I/SELinux ( 5607): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5607): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5607): >>>>> Normal User
,E/dalvikvm( 5607): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 5607): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5607): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5607): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5607): Added TimaKesytore provider
,D/UserAnalysis.PlaceProvider( 5607): Create SecureDbHelper
,W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5607, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
D/UserAnalysis.UserAnalysisBroadcastReceiver( 5607): Create SecureDbHelper
,W/ContextImpl( 4673): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
,D/RCPManager( 4780):  in createShortcut() for packageName: com.google.android.gms userId0
D/RCPManagerService(  790):  in createShortcut() for packageName: com.google.android.gms userId0
,D/RCPManagerService(  790): queryAllProviders():  providerCallBack is not register for 0
,D/CapabilityManagerService New( 5307): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
,D/CapabilityManagerService New( 5307): The package(com.google.android.gms) updated
,D/MagazineService::MagazineBroadcastReceiver( 5396): [onReceive] android.intent.action.PACKAGE_REMOVED com.google.android.gms
,I/MagazineService::MagazineService( 5396): [onHandleIntent] ACTION_PACKAGE_REMOVED
,I/SELinux ( 5621): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5621):  
,I/ActivityManager(  790): Killing 4621:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 5621): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5621):  
I/SELinux ( 5621):  
,I/SELinux ( 5621): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5621): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 5621): >>>>> Normal User
,E/dalvikvm( 5621): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 5621): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5621): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5621): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5621): Added TimaKesytore provider
,W/ContextImpl( 5621): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,D/KidsModeInstallReceiver( 5424): onReceive intent data =  package:com.google.android.gms
,D/KidsPlatformStub( 5424): Package not found : com.sec.android.app.kidshome
,V/AlarmManager(  790): waitForAlarm result :4
,I/ActivityManager(  790): Killing 3030:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,I/MultiDex( 5554): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip
,I/MultiDex( 5554): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip: 2898044
,I/MultiDex( 5554): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip
,I/MultiDex( 5554): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes-2002583158.zip
,I/MultiDex( 5588): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip
I/MultiDex( 5588): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip: 2898044
,I/MultiDex( 5588): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip
,I/MultiDex( 5588): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes-1413353980.zip
,D/AmoledAdjustTimer(  790): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/MultiDex( 5554): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip
I/MultiDex( 5554): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip: 3409737
,I/MultiDex( 5554): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip
,I/MultiDex( 5554): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes268394788.zip
,I/MultiDex( 5588): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip
,I/MultiDex( 5588): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip: 3409737
,I/MultiDex( 5588): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip
,I/MultiDex( 5588): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes244419608.zip
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  790): stay LED for fully charged
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/MultiDex( 5554): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip
,I/MultiDex( 5554): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip: 2767034
,I/MultiDex( 5554): load found 3 secondary dex files
,I/MultiDex( 5588): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip
,I/MultiDex( 5588): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip: 2767034
,I/MultiDex( 5588): load found 3 secondary dex files
,D/dalvikvm( 5588): DexOpt: sleeping on flock(/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.dex)
,D/dalvikvm( 5554): DexOpt: --- BEGIN 'com.google.android.gms-2.apk.classes2.zip' (bootstrap=0) ---
,E/SMD     (  241): DCD ON
,D/dalvikvm( 5667): GC_FOR_ALLOC freed 658K, 33% free 1388K/2048K, paused 4ms, total 4ms
,D/dalvikvm( 5667): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
,D/dalvikvm( 5667): DexOpt: load 326ms, verify+opt 662ms, 5447164 bytes
,D/dalvikvm( 5554): DexOpt: --- END 'com.google.android.gms-2.apk.classes2.zip' (success) ---
,D/dalvikvm( 5554): DEX prep '/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip': unzip in 182ms, rewrite 1653ms
,D/dalvikvm( 5554): DexOpt: sleeping on flock(/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.dex)
,D/dalvikvm( 5588): DexOpt: --- BEGIN 'com.google.android.gms-2.apk.classes3.zip' (bootstrap=0) ---
,D/SSRMv2:SIOP(  790): SIOP:: AP = 330, Delta = 0
,D/dalvikvm( 5669): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
,D/dalvikvm( 5669): GC_FOR_ALLOC freed 723K, 36% free 1319K/2048K, paused 5ms, total 5ms
,E/Watchdog(  790): !@Sync 4
,E/SMD     (  241): DCD ON
,D/dalvikvm( 5669): DexOpt: load 294ms, verify+opt 986ms, 5291140 bytes
,D/dalvikvm( 5588): DexOpt: --- END 'com.google.android.gms-2.apk.classes3.zip' (success) ---
,D/dalvikvm( 5588): DEX prep '/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip': unzip in 202ms, rewrite 1994ms
,D/dalvikvm( 5554): DexOpt: sleeping on flock(/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.dex)
,D/dalvikvm( 5588): DexOpt: --- BEGIN 'com.google.android.gms-2.apk.classes4.zip' (bootstrap=0) ---
,D/dalvikvm( 5671): DexOpt: load 249ms, verify+opt 754ms, 4699444 bytes
,D/dalvikvm( 5588): DexOpt: --- END 'com.google.android.gms-2.apk.classes4.zip' (success) ---
,D/dalvikvm( 5588): DEX prep '/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip': unzip in 161ms, rewrite 1585ms
I/MultiDex( 5588): install done
,I/MultiDex( 5554): install done
,I/SELinux ( 5674): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5674):  
,I/SELinux ( 5674): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5674):  
I/SELinux ( 5674):  
,I/SELinux ( 5674): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5674): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5674): >>>>> Normal User
,E/dalvikvm( 5674): >>>>> com.google.process.gapps [ userId:0 | appId:10011 ]
,E/SELinux ( 5674): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5674): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5674): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5674): Added TimaKesytore provider
D/AmoledAdjustTimer(  790): prevTemp = 293, currTemp = 295, prevStep = 4, currStep = 4
,I/GservicesProvider( 5674): Gservices pushing to system: true; secure/global: true
,D/dalvikvm( 5588): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5588): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5588): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5588): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5588): VFY: unable to resolve instance field 36
,D/dalvikvm( 5588): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5588): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5588): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5588): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 5588): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5588): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 5554): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5554): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5554): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5554): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5554): VFY: unable to resolve instance field 36
,D/dalvikvm( 5554): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5554): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5554): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5554): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5554): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5554): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5588): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4266b218
,D/dalvikvm( 5588): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4266b218
,D/dalvikvm( 5588): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4266b218, skipping init
D/dalvikvm( 5588): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4266b218
D/dalvikvm( 5554): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42669558
,D/dalvikvm( 5588): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4266b218
,V/JNIHelp ( 5588): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/dalvikvm( 5554): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42669558
,D/dalvikvm( 5554): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42669558, skipping init
D/dalvikvm( 5554): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42669558
,D/dalvikvm( 5554): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42669558
,V/JNIHelp ( 5554): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5588): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4266b218
,D/dalvikvm( 5588): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4266b218
D/dalvikvm( 5588): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4266b218
,D/dalvikvm( 5588): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4266b218
,D/dalvikvm( 5554): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42669558
,D/dalvikvm( 5554): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42669558
D/dalvikvm( 5554): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42669558
,D/dalvikvm( 5554): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42669558
,I/ProviderInstaller( 5588): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 5588): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 5588): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 5588): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 5588): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x000d
,I/ProviderInstaller( 5554): Installed default security provider GmsCore_OpenSSL
,D/NativeLibraryUtils( 5554): Installer failed to acquire lock.
D/NativeLibraryUtils( 5554): java.io.IOException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 5554): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
D/NativeLibraryUtils( 5554): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:177)
D/NativeLibraryUtils( 5554): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:587)
D/NativeLibraryUtils( 5554): 	at com.google.android.gms.common.util.ay.b(SourceFile:335)
D/NativeLibraryUtils( 5554): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
D/NativeLibraryUtils( 5554): Caused by: libcore.io.ErrnoException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 5554): 	at libcore.io.Posix.fcntlFlock(Native Method)
D/NativeLibraryUtils( 5554): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:54)
D/NativeLibraryUtils( 5554): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
D/NativeLibraryUtils( 5554): 	... 4 more
,E/ActivityThread( 5588): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  790): failed sync operation 
,D/SyncManager(  790): not retrying sync operation because the error is a hard error: 
,I/GAv4-SVC( 5588): Google Analytics 8.4.89 is starting up.
,I/dalvikvm( 5554): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5554): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 5554): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 5554): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 5554): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 5554): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 5554): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 5554): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5554): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 5554): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/NativeLibraryUtils( 5588): Install completed successfully. count=14 extracted=0
,I/dalvikvm( 5554): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 5554): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 5554): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 5554): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x000d
,D/DeviceConnectionService( 5554): client connected with version: 8296000
,I/dalvikvm( 5554): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method com.google.android.location.util.ao.c
W/dalvikvm( 5554): VFY: unable to resolve virtual method 1379: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x000c
,I/GCoreNlp( 5554): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  790): applying state to connected service
,D/LocationProviderProxy(  790): applying state to connected service
,D/PackageBroadcastService( 5588): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.gms
,I/PackageBroadcastService( 5588): Null package name or gms related package.  Ignoreing.
,E/SMD     (  241): DCD ON
,D/ChimeraCfgMgr( 5588): Reading stored module config
,D/GeofencerStateMachine( 5554): Creating GeofencerStateMachine
E/SensorService(  790): Permission Denial : SEC Private Sensor 
,E/SensorService(  790): Permission Denial : SEC Private Sensor 
,W/ChimeraCfgMgr( 5588): Stored Chimera config has different version (current=2,stored=1), ignoring
,D/ChimeraCfgMgr( 5588): Reading stored module config
,W/ChimeraCfgMgr( 5588): Stored Chimera config has different version (current=2,stored=1), ignoring
,D/GmsModuleFndr( 5588): Beginning GMS chimera module scan
D/dalvikvm( 5588): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 5588): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 5588): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 5588): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 5588): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5588): VFY: replacing opcode 0x62 at 0x0021
D/dalvikvm( 5588): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 5588): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 5588): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 5588): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5588): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5588): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 5588): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 5588): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 5588): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 5588): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 5588): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 5588): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,I/dalvikvm( 5554): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
,W/dalvikvm( 5554): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x0010
,I/dalvikvm( 5554): Failed resolving Lcom/google/android/gms/common/util/bo; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5554): Link of class 'Lcom/google/android/gms/common/util/bo;' failed
E/dalvikvm( 5554): Could not find class 'com.google.android.gms.common.util.bo', referenced from method com.google.android.gms.common.util.bm.a
W/dalvikvm( 5554): VFY: unable to resolve new-instance 2494 (Lcom/google/android/gms/common/util/bo;) in Lcom/google/android/gms/common/util/bm;
,D/dalvikvm( 5554): VFY: replacing opcode 0x22 at 0x0010
I/dalvikvm( 5554): Failed resolving Lcom/google/android/gms/common/util/bo; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 5554): Link of class 'Lcom/google/android/gms/common/util/bo;' failed
,D/dalvikvm( 5554): DexOpt: unable to opt direct call 0x3205 at 0x16 in Lcom/google/android/gms/common/util/bm;.a
,D/ChimeraCfgMgr( 5588): Beginning module configuration check
,D/ChimeraCfgMgr( 5588): Reading stored module config
W/ChimeraCfgMgr( 5588): Stored Chimera config has different version (current=2,stored=1), ignoring
,D/ChimeraModuleApk( 5588): Loading chimera manifest from InstalledApk(com.google.android.play.games)
,D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.games,v34120000) from InstalledApk(com.google.android.play.games)
,D/ChimeraFileApk( 5588): Loading chimera manifest from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk)
,D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.maps,v8301000) from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk)
D/ChimeraModuleApk( 5588): Loading chimera manifest from ContainerApk(com.google.android.gms)
I/dalvikvm( 5554): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.location.util.k.a
W/dalvikvm( 5554): VFY: unable to resolve virtual method 1377: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x000a
,D/ChimeraCfgMgr( 5588): Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
,D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.cast,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.games,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.gass,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.piccard,v1) from ContainerApk(com.google.android.gms)
,D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.vision,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgRslvr( 5588): Beginning module config resolution
D/ChimeraCfgRslvr( 5588): module(built-in,v0) has no external dependencies, accepted
D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.cast,v1) accepted
,D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.games,v34120000) accepted
D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.gass,v1) accepted
D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.kids,v3) accepted
D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.maps,v8301000) accepted
D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.piccard,v1) accepted
,D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.vision,v1) accepted
,D/ChimeraCfgRslvr( 5588): Module config resolution complete
,I/PowerManagerService(  790): [PWL] Off : 75s ago
,V/AlarmManager(  790): waitForAlarm result :4
,D/LocationManagerService(  790): request 43ea3918 passive Request[POWER_NONE passive fastest=0] from com.google.android.gms(10011)
,D/LocationManagerService(  790): provider request: passive ProviderRequest[ON interval=0]
,D/dalvikvm( 5588): GC_CONCURRENT freed 5662K, 38% free 11931K/18972K, paused 3ms+14ms, total 65ms
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5588): Loading module APK com.google.android.play.games
,I/dalvikvm( 5588): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 5588): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 5588): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 5588): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 5588): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 5588): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5588): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 5588): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,V/GeofencerHelper( 5554): Initializing geofence's system cache.
,I/dalvikvm( 5588): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
,W/dalvikvm( 5588): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x002b
W/dalvikvm( 5674): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5674): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 5674): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5674): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 5674): VM with version 1.6.0 does not have multidex support
,D/GeofenceStateCache( 5554): Recovered 0 geofences.
,I/MultiDex( 5674): install
,I/MultiDex( 5674): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 5674): loading existing secondary dex files
,V/AlarmManager(  790): waitForAlarm result :4
I/MultiDex( 5674): load found 3 secondary dex files
,I/MultiDex( 5674): install done
,V/AlarmManager(  790): waitForAlarm result :4
,I/GeofencerStateMachine( 5554): Network location disabled.
V/AlarmManager(  790): waitForAlarm result :4
,D/dalvikvm( 5674): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5674): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5674): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5674): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5674): VFY: unable to resolve instance field 36
,D/dalvikvm( 5674): VFY: replacing opcode 0x54 at 0x005f
I/dalvikvm( 5554): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.location.internal.server.o.f
W/dalvikvm( 5554): VFY: unable to resolve virtual method 1398: Landroid/os/UserHandle;.isOwner ()Z
D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x00ab
D/dalvikvm( 5674): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5674): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5674): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5674): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5674): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5674): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4266aab0
D/dalvikvm( 5674): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4266aab0
,D/dalvikvm( 5674): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4266aab0, skipping init
,D/dalvikvm( 5674): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4266aab0
D/dalvikvm( 5674): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4266aab0
,V/JNIHelp ( 5674): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5588): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4266b218
,D/dalvikvm( 5588): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4266b218
,D/dalvikvm( 5588): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4266b218, skipping init
,I/dalvikvm( 5588): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 5588): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x0010
,D/dalvikvm( 5674): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4266aab0
,D/dalvikvm( 5674): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4266aab0
D/dalvikvm( 5674): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4266aab0
,D/dalvikvm( 5674): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4266aab0
,I/Icing   ( 5588): Storage manager: low false usage 1.60MB avail 11.11GB capacity 11.95GB
,I/ProviderInstaller( 5674): Installed default security provider GmsCore_OpenSSL
I/dalvikvm( 5588): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.b.g.a
W/dalvikvm( 5588): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x0029
,D/GCM     ( 5674): COMPAT: Multi user not supported
,D/dalvikvm(  790): GC_EXPLICIT freed 2332K, 57% free 23936K/55192K, paused 5ms+13ms, total 149ms
,W/dalvikvm( 5674): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5674): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5674): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 5674): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 5674): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x00bb
,I/dalvikvm( 5674): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 5674): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 5674): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 5674): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 5674): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 5674): VFY: unable to resolve instance field 161
,D/dalvikvm( 5674): VFY: replacing opcode 0x52 at 0x0006
,I/dalvikvm( 5674): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.nts.a.c.b
W/dalvikvm( 5674): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 5554): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
W/dalvikvm( 5554): VFY: unable to resolve virtual method 1203: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x003e
,D/WearableService( 5554): callingUid 10011, callindPid: 5554
E/dalvikvm( 5554): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 5554): VFY: unable to resolve check-cast 516 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 5554): VFY: replacing opcode 0x1f at 0x0054
,W/dalvikvm( 5554): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 5674): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 5674): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x0010
,I/dalvikvm( 5588): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5588): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 5588): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 5588): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 5588): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 5588): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 5588): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 5588): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5588): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 5588): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,E/NetworkScheduler.SchedulerReceiver( 5674): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 5674): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,E/SamsungIME( 5158): InputManagerImpl.getInstance() == null
,E/GmsWearableNodeHelper( 5554): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/Babel   ( 4692): Gms package replaced. Will trigger a restart of babel
,I/PCWCLIENTTRACE_PushUtil( 5214): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5214): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5214): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5214): [onReceive] - android.intent.action.PACKAGE_ADDED
,W/IcingInternalCorpora( 5588): getNumBytesRead when not calculated.
,I/SA      ( 4042): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4042): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4042): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
,D/Mms/PackageInstallReceiver( 4332): loadAuthorityPref(): sEnableAuthority = true
,W/dalvikvm( 5554): VFY: unable to find class referenced in signature (Lcom/android/location/provider/ActivityChangedEvent;)
I/dalvikvm( 5554): Could not find method com.android.location.provider.ActivityChangedEvent.getActivityRecognitionEvents, referenced from method com.google.android.location.a.j.a
W/dalvikvm( 5554): VFY: unable to resolve virtual method 3610: Lcom/android/location/provider/ActivityChangedEvent;.getActivityRecognitionEvents ()Ljava/lang/Iterable;
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x0009
I/ActivityManager(  790): Killing 3948:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,I/IcingCorporaProvider( 2183): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/ContextImpl( 4673): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,D/CapabilityManagerService New( 5307): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
,D/PackageIntentReceiver( 5377): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 5377): Not GearManger package! 
,D/MagazineService::MagazineBroadcastReceiver( 5396): [onReceive] android.intent.action.PACKAGE_ADDED com.google.android.gms
,I/MagazineService::MagazineService( 5396): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,D/MagazineService::MagazineService( 5396): [onHandleIntent] Send broadcast to (com.google.android.gms).
,D/NativeLibraryUtils( 5674): Install completed successfully. count=14 extracted=0
,D/KidsPlatformStub( 5424): Package not found : com.sec.android.app.kidshome
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,D/Finsky  ( 3720): [1] GmsCoreHelper$GMSCoreNotifier$1.run: Set autoupdate of com.google.android.gms to 1 (install/update)
,D/dalvikvm( 5674): GC_EXPLICIT freed 4855K, 43% free 10966K/18972K, paused 3ms+6ms, total 46ms
,I/PCWCLIENTTRACE_PushUtil( 5214): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5214): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5214): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5214): [onReceive] - android.intent.action.PACKAGE_REPLACED
,D/PCWCLIENTTRACE_SYSTEMReceiver( 5214): ACTION_PACKAGE_REPLACED_START
,W/Babel   ( 4692): Gms package replaced. Will trigger a restart of babel
,I/SA      ( 4042): [PMR] Received action : android.intent.action.PACKAGE_REPLACED
,I/SA      ( 4042): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4042): [SUR] onReceive Intent=[ action_PACKAGE_REPLACED package ]
,W/ContextImpl( 4673): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:174 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 5770): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5770):  
,I/SELinux ( 5770): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5770):  
I/SELinux ( 5770):  
,I/SELinux ( 5770): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5770): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5770): >>>>> Normal User
,E/dalvikvm( 5770): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5770): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 5554): GC_EXPLICIT freed 5769K, 41% free 11363K/18972K, paused 5ms+7ms, total 86ms
,D/TimaKeyStoreProvider( 5770): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5770): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5770): Added TimaKesytore provider
,D/LocationManagerService(  790): request 4315d140 passive Request[POWER_NONE passive fastest=0] from com.google.android.gms(10011)
,D/LocationManagerService(  790): provider request: passive ProviderRequest[ON interval=0]
,W/Settings( 5554): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/dalvikvm( 5588): Total arena pages for JIT: 11
,I/dalvikvm( 5588): Total arena pages for JIT: 12
I/dalvikvm( 5588): Total arena pages for JIT: 13
,I/dalvikvm( 5588): Total arena pages for JIT: 14
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5770): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,W/Vold    (  228): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5770): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/GAV2    ( 5770): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5770): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
I/DatabaseHelper( 5554): Upgrade database: oldVersion=3 newVersion=4
,I/DatabaseHelper( 5554): Indexing LogEvents by PlayLoggerContext id
,W/ContextImpl( 5770): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,I/Icing   ( 5588): updateResources: need to parse f{com.google.android.gms}
,I/Scheduler( 5554): Use legacy PeriodicScheduler
,W/InstanceID/Rpc( 5554): Found 10011
,I/Icing   ( 5588): Removing corpus key 49CA7E3A917E607C6D98AA15891295369CED2106 for package com.google.android.gms
,V/WebViewChromium( 5770): Binding Chromium to the main looper Looper (main, tid 1) {4233b790}
,I/chromium( 5770): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5770): Initializing chromium process, renderers=0
,W/chromium( 5770): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5770): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5770): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5770): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5770): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5770): Remote Branch: 
I/Adreno-EGL( 5770): Local Patches: 
I/Adreno-EGL( 5770): Reconstruct Branch: 
,I/NSApplication( 5770): Starting up...
,W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=5770, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  790): Killing 4799:com.wssyncmldm/1000 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 3352): PeriphStartReceiver.onReceive - android.intent.action.PACKAGE_REPLACED
,D/daemonapp( 1468): [MSC_Daemon]>>> AWDCDS:27 [0:0] AWD CD Act : androidintentactionPACKAGE_REPLACED
,D/dalvikvm( 5588): GC_CONCURRENT freed 2960K, 43% free 10937K/18972K, paused 2ms+3ms, total 40ms
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/PackageBroadcastService( 5588): Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.gms
,D/AsyncTaskServiceImpl( 5588): Submit a task: k
,D/GmsModuleFndr( 5588): Beginning GMS chimera module scan
,D/ChimeraCfgMgr( 5588): Beginning module configuration check
,D/ChimeraCfgMgr( 5588): Module APKs unchanged, check complete
,I/PackageBroadcastService( 5588): Null package name or gms related package.  Ignoreing.
,I/dalvikvm( 5588): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 5588): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 5588): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 5674): GC_EXPLICIT freed 745K, 46% free 10311K/18972K, paused 2ms+3ms, total 25ms
,D/EnterpriseDeviceManagerService(  790): Creating context as user 0
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5588): Processing package: com.google.android.gms
,D/d       ( 5588): Database will be upgraded from 1 to 2
,D/d       ( 5588): Database upgraded to 2
,D/b       ( 5588): Look up (com.google.android.gms:8489036) returned no result
,D/k       ( 5588): Starting Hash for package com.google.android.gms:8.4.89 (2428711-036)
,D/FileApkUtils( 5588): Spent 55ms computing apk sha1.
,D/EnterpriseDeviceManagerService(  790): Creating context as user 0
,E/DynamiteModule( 5588): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5588): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-2.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-2, /data/app-lib/com.google.android.gms-2, /data/app-lib/com.google.android.gms-2, /data/app-lib/com.google.android.gms-2, /data/app-lib/com.google.android.gms-2, /vendor/lib, /system/lib]]
E/DynamiteModule( 5588): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:67)
E/DynamiteModule( 5588): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 5588): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 5588): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5588): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5588): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5588): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5588): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5588): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:72)
E/DynamiteModule( 5588): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DynamiteModule( 5588): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5588): 	at android.os.Looper.loop(Looper.java:146)
E/DynamiteModule( 5588): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DynamiteModule( 5588): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 5588): Selected local version of com.google.android.gms.flags
,D/FileApkUtils( 5588): Spent 74ms copying apk.
,D/FileApkUtils( 5588): Copied dynamite bytes to /data/data/com.google.android.gms/app_chimera/chimera-module-root/scratch-module-dir/MapsModule.apk
,D/FileApkUtils( 5588): Spent 5ms extracting native libraries.
D/DexOptUtils( 5588): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 5588): Pre-lollipop platform, odex will live alongside the dex.
D/DexOptUtils( 5588): Instantiating DexClassLoader to force creation of odex.
,D/DexOptUtils( 5588): Primary ABI of odexing process is armeabi-v7a
,W/dalvikvm( 5554): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5554): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5554): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 5554): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 5554): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 5554): Using platform SSLCertificateSocketFactory
,I/dalvikvm( 5554): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.tapandpay.j.f.a
W/dalvikvm( 5554): VFY: unable to resolve virtual method 1401: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x0037
,I/PhenotypeConfigurator( 5554): Scheduling Phenotype for one-off execution 12015 seconds from now (1449626676782)
,E/NetworkScheduler.SchedulerReceiver( 5674): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 5674): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/dalvikvm( 5588): DexOpt: --- BEGIN 'MapsModule.apk' (bootstrap=0) ---
,W/InstanceID/Rpc( 5674): Found 10011
,D/dalvikvm( 5588): GC_EXPLICIT freed 647K, 42% free 11136K/18972K, paused 134ms+6ms, total 170ms
,W/InstanceID/Rpc( 5588): Found 10011
,I/Icing   ( 5588): Internal init done: storage state 0
,I/Icing   ( 5588): Post-init done
,I/Icing   ( 5588): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/dalvikvm( 5588): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.stats.PlatformStatsCollectorService.a
W/dalvikvm( 5588): VFY: unable to resolve virtual method 1512: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x0070
,I/PlatformStatsCollectorService( 5588): Start Settingsstats in 47659 seconds.
,I/PlatformStatsCollectorService( 5588): Start Dropbox in 50084 seconds.
,I/PlatformStatsCollectorService( 5588): Start Graphicsstats in 67883 seconds.
,D/dalvikvm( 5588): GC_CONCURRENT freed 1914K, 41% free 11269K/18972K, paused 2ms+3ms, total 46ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 29ms
D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/PlatformStatsCollectorService( 5588): Start Fingerprintstats in 10551 seconds.
,I/PlatformStatsCollectorService( 5588): Start Procstats in 32312 seconds.
,I/PlatformStatsCollectorService( 5588): Start Diskstats in 84456 seconds.
,D/dalvikvm( 5674): GC_EXPLICIT freed 325K, 46% free 10375K/18972K, paused 3ms+4ms, total 27ms
,I/PlatformStatsCollectorService( 5588): Start Notificationstats in 5872 seconds.
,I/PlatformStatsCollectorService( 5588): Start Netstats in 58064 seconds.
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5588): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5588): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/dalvikvm( 5588): GC_CONCURRENT freed 1672K, 39% free 11604K/18972K, paused 3ms+3ms, total 29ms
,I/PerfProfileCollectorService( 5588): Scheduling Perf Profile Collection every 86400 seconds
,I/StatsUploadService( 5588): Turn off alarms uploading
,D/dalvikvm(  790): GC_CONCURRENT freed 3426K, 57% free 24141K/55192K, paused 4ms+11ms, total 138ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 62ms
,I/StatsUploadService( 5588): Turn off networkusage uploading
,I/StatsUploadService( 5588): Turn off wakelocks uploading
,I/StatsUploadService( 5588): Turn off internal_service_connections uploading
,I/dalvikvm( 5588): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
W/dalvikvm( 5588): VFY: unable to resolve virtual method 1203: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x003e
V/AlarmManager(  790): waitForAlarm result :4
V/AlarmManager(  790): waitForAlarm result :4
,E/SMD     (  241): DCD ON
,D/AuthorizationBluetoothService( 5674): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/dalvikvm( 5674): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 5674): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x002f
,E/AuthorizationBluetoothService( 5674): Proximity feature is not enabled.
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 5674): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.e.b.a
W/dalvikvm( 5674): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x000e
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Scheduler( 5588): Use legacy PeriodicScheduler
,D/dalvikvm( 5588): GC_CONCURRENT freed 3172K, 40% free 11504K/18972K, paused 3ms+11ms, total 40ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 5817): DexOpt: load 149ms, verify+opt 899ms, 2031916 bytes
,D/GmsModuleFndr( 5588): Beginning GMS chimera module scan
,D/FileApkUtils( 5588): Ignoring module currently being optimized: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 5588): Beginning module configuration check
,D/ChimeraCfgMgr( 5588): Module APKs unchanged, check complete
,D/k       ( 5588): Package com.google.android.gms's hash: a05ba025b6e6b4a49692d64a578be94965f04b9c510b10e0363a9fa4f9300b4e
,E/dalvikvm( 5588): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 5588): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 5588): VFY: replacing opcode 0x22 at 0x00af
,D/b       ( 5588): Look up (com.google.android.gms:8489036) returned no result
W/dalvikvm( 5588): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 5588): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 5588): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 5588): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 5588): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 5588): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 5588): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 5588): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 5588): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 5588): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Auth    ( 5674): [Change,LoginAccountsChangedIntentService] LoginAccountsChangedIntentService received unknown action: com.google.android.gms.auth.change.REFRESH
,V/AuthZen ( 5588): Handling intent: com.google.android.gms.GMS_UPDATED
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,D/k       ( 5588): Saved the app info in cache for package:com.google.android.gms.
V/AlarmManager(  790): waitForAlarm result :4
,E/dalvikvm( 5554): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 5554): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
D/dalvikvm( 5554): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 5554): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 5554): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 5554): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 5554): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 5554): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 5554): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 5554): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
D/GCM     ( 5588): COMPAT: Multi user not supported
W/dalvikvm( 5554): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 5554): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 5554): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,D/dalvikvm( 5588): DexOpt: --- END 'MapsModule.apk' (success) ---
,D/dalvikvm( 5588): DEX prep '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': unzip in 91ms, rewrite 1385ms
D/DexOptUtils( 5588): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.dex
,D/DexOptUtils( 5588): Set odex to world readable.
,D/DexOptUtils( 5588): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.odex
,D/FileApkUtils( 5588): Deleting stale module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/FileApkUtils( 5588): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/GmsModuleFndr( 5588): Beginning GMS chimera module scan
,D/ChimeraCfgMgr( 5588): Beginning module configuration check
,D/AuthZenEventHandler( 5588): Handling event: com.google.android.gms.GMS_UPDATED
,D/ChimeraModuleApk( 5588): Loading chimera manifest from InstalledApk(com.google.android.play.games)
,D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.games,v34120000) from InstalledApk(com.google.android.play.games)
,D/ChimeraFileApk( 5588): Loading chimera manifest from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk)
,D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.maps,v8489000) from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk)
,D/ChimeraModuleApk( 5588): Loading chimera manifest from ContainerApk(com.google.android.gms)
,D/ChimeraCfgMgr( 5588): Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.cast,v1) from ContainerApk(com.google.android.gms)
,D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.games,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.gass,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.piccard,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 5588): Considering module(com.google.android.gms.vision,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgRslvr( 5588): Beginning module config resolution
D/ChimeraCfgRslvr( 5588): module(built-in,v0) has no external dependencies, accepted
D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.cast,v1) accepted
D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.games,v34120000) accepted
,D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.gass,v1) accepted
D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.kids,v3) accepted
D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.maps,v8489000) accepted
,D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.piccard,v1) accepted
D/ChimeraCfgRslvr( 5588): module(com.google.android.gms.vision,v1) accepted
,D/ChimeraCfgRslvr( 5588): Module config resolution complete
,I/dalvikvm( 5674): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 5674): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x0059
,I/dalvikvm( 5674): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
,W/dalvikvm( 5674): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x0022
,W/BaseAppContext( 5588): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 5588): Upgrading from version 700 to 1405
,E/MDM     ( 5554): [574] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/dalvikvm( 5588): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5588): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5588): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 5588): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 5588): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x00bb
,E/MDM     ( 5554): [585] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 5674): GcmService start Intent { act=com.google.android.gms.GMS_UPDATED cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.GMS_UPDATED
,D/GCM     ( 5674): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,I/GCM     ( 5674): GCM config loaded
,I/dalvikvm( 5554): Total arena pages for JIT: 11
,I/dalvikvm( 5554): Total arena pages for JIT: 12
I/dalvikvm( 5554): Total arena pages for JIT: 13
,I/dalvikvm( 5554): Total arena pages for JIT: 14
,D/dalvikvm( 5588): GC_CONCURRENT freed 1750K, 38% free 11778K/18972K, paused 10ms+7ms, total 60ms
,W/dalvikvm( 5588): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 5588): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 5588): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 5588): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 5588): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 5588): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 5588): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 5588): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 5588): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 5588): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 5588): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 5588): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x0006
,I/LocationInitializer( 5588): Initializing location.
,D/LocationInitializer( 5588): Location services disabled.
,I/System.out( 5674): Thread-574(HTTPLog):isShipBuild true
,I/System.out( 5674): Thread-574(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/FileApkUtils( 5588): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 5588): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 5588): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/GmsModuleFndr( 5588): Beginning GMS chimera module scan
,D/AuthorizationBluetoothService( 5674): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ChimeraCfgMgr( 5588): Beginning module configuration check
,E/AuthorizationBluetoothService( 5674): Proximity feature is not enabled.
,E/BaseAppContext( 5588): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/ChimeraCfgMgr( 5588): Module APKs unchanged, check complete
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 5588): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 5588): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x002f
V/AlarmManager(  790): waitForAlarm result :4
V/AlarmManager(  790): waitForAlarm result :4
,E/MDM     ( 5554): [587] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 5674): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 5674): Proximity feature is not enabled.
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GmsModuleFndr( 5588): Beginning GMS chimera module scan
,I/AuthZen ( 5588): Fetching signing key...
,D/SystemEventReceiver( 5588): Received GMS_UPDATE broadcast
,I/OcrUtils( 5588): Updating ocr activity enabled=false
,D/ChimeraCfgMgr( 5588): Beginning module configuration check
,D/ChimeraCfgMgr( 5588): Module APKs unchanged, check complete
,I/AuthZen ( 5588): Signing key fetched successfully!
,D/dalvikvm( 5674): GC_EXPLICIT freed 1260K, 45% free 10606K/18972K, paused 2ms+6ms, total 36ms
,V/GMPM-SVC( 5588): Update service enabled state to: 1
,W/BaseAppContext( 5588): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 5588): cleanUpNonGplusAccounts done.
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5588): Module APK com.google.android.play.games already loaded
,I/PeopleSync( 5588): requestContactSyncCleanup [5005f081]
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,I/dalvikvm( 5674): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 5674): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x001c
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PlatformStatsCollectorService( 5588): Start Settingsstats in 81164 seconds.
,I/PlatformStatsCollectorService( 5588): Start Dropbox in 74358 seconds.
,D/dalvikvm( 5588): GC_CONCURRENT freed 2103K, 39% free 11722K/18972K, paused 4ms+3ms, total 31ms
D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/PlatformStatsCollectorService( 5588): Start Graphicsstats in 75400 seconds.
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5588): Module APK com.google.android.play.games already loaded
,V/AlarmManager(  790): waitForAlarm result :4
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/dalvikvm( 5588): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 5588): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x003d
,V/AlarmManager(  790): waitForAlarm result :4
D/BootCompletedReceiver( 5588): Will schedule periodic tasks:com.google.android.gms.GMS_UPDATED.
D/BootCompletedReceiver( 5588): Got a GmsCore update event.
I/PlatformStatsCollectorService( 5588): Start Fingerprintstats in 12776 seconds.
D/BootCompletedReceiver( 5588): Will NOT schedule AdAttestation signal task because it's disabled.
,E/dalvikvm( 5588): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 5588): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 5588): VFY: replacing opcode 0x1f at 0x000e
,I/PlatformStatsCollectorService( 5588): Start Procstats in 20964 seconds.
,W/ActivityManager(  790): Unable to start service Intent { act=com.google.android.gms.GMS_UPDATED pkg=com.google.android.gms } U=0: not found
,I/PlatformStatsCollectorService( 5588): Start Diskstats in 33756 seconds.
,I/PeopleSync( 5588): onPerformSync() [5005f081]
,D/OcrModelManager( 5588): Updating downloaded model state (gcore updated)
,I/MDM     ( 5588): [626] SitrepService.onHandleIntent: sending sitrep: [6, 0, [Uyj4xTZ24pLvH7HF-TZh6vCxLvo], null]
,W/BaseAppContext( 5588): Using Auth Proxy for data requests.
,I/dalvikvm( 5674): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 5674): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x001f
W/BaseAppContext( 5588): Using Auth Proxy for data requests.
,W/BaseAppContext( 5588): Using Auth Proxy for data requests.
,E/File    ( 5588): fail readDirectory() errno=2
,I/PlatformStatsCollectorService( 5588): Start Notificationstats in 79468 seconds.
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 5674): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 5674): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x0041
D/AuthorizationBluetoothService( 5674): Received GmsCore event: Intent { act=com.google.android.gms.GMS_UPDATED flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 5674): Proximity feature is not enabled.
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 5554): GC_CONCURRENT freed 2218K, 42% free 11079K/18972K, paused 4ms+19ms, total 79ms
,D/ConnectivityService(  790): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/dalvikvm(  790): GC_CONCURRENT freed 3437K, 56% free 24388K/55192K, paused 4ms+12ms, total 133ms
D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 77ms
D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 80ms
D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 78ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 77ms
D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 59ms
D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 74ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 58ms
,V/GoogleAuthProtoRequest( 5588): [626] a.<init>: mAccountName set to: thalitester@gmail.com
,I/PlatformStatsCollectorService( 5588): Start Netstats in 68396 seconds.
V/AlarmManager(  790): waitForAlarm result :4
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,V/AlarmManager(  790): waitForAlarm result :4
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,W/BaseAppContext( 5588): Using Auth Proxy for data requests.
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/c       ( 5588): Creating table: affiliation
,W/BaseAppContext( 5588): Using Auth Proxy for data requests.
V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
W/BaseAppContext( 5588): Using Auth Proxy for data requests.
,I/dalvikvm( 5674): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
,W/dalvikvm( 5674): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x0046
,W/BaseAppContext( 5588): Using Auth Proxy for data requests.
V/AlarmManager(  790): waitForAlarm result :4
V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,I/PeopleSync( 5588): Setting subscription: result=true [5005f081]
,I/PeopleSync( 5588): Starting sync, feed=null [5005f081]
,W/dalvikvm( 5674): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 5674): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 5674): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 5674): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 5674): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 5674): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 5674): VFY: replacing opcode 0x6e at 0x003d
V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,I/PeopleContactsSync( 5588): CP2 sync start [5005f081]
V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,E/dalvikvm( 5554): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
W/dalvikvm( 5554): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,D/dalvikvm( 5554): VFY: replacing opcode 0x1f at 0x001a
,V/AlarmManager(  790): waitForAlarm result :4
D/dalvikvm( 5554): DexOpt: unable to opt direct call 0x00e3 at 0x2b in Lcom/google/android/contextmanager/m/a/az;.i
,I/dalvikvm( 5554): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.contextmanager.m.a.bc.b
W/dalvikvm( 5554): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x0012
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,D/dalvikvm( 5588): GC_CONCURRENT freed 2634K, 37% free 12095K/18972K, paused 4ms+5ms, total 41ms
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,I/PeopleContactsSync( 5588): CP2 cleanup done, kept= duration=196 ms
D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5588): Module APK com.google.android.play.games already loaded
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,I/PhenotypeConfigurator( 5554): Scheduling Phenotype for one-off execution 127 seconds from now (1449626679621)
,I/PeopleContactsSync( 5588):   updateBabelActionMimeType
,I/dalvikvm( 5554): Could not find method android.accounts.AccountManager.getPreviousName, referenced from method com.google.android.location.util.c.a
W/dalvikvm( 5554): VFY: unable to resolve virtual method 11: Landroid/accounts/AccountManager;.getPreviousName (Landroid/accounts/Account;)Ljava/lang/String;
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x000a
V/AlarmManager(  790): waitForAlarm result :4
V/AlarmManager(  790): waitForAlarm result :4
,I/PerfProfileCollectorService( 5588): Scheduling Perf Profile Collection every 86400 seconds
,I/dalvikvm( 5588): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 5588): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x0053
W/ActivityManager(  790): Unable to start service Intent { act=INITIALIZE_SUBSCRIPTIONS cmp=com.google.android.gms/.nearby.sharing.NearbySharingIntentService } U=0: not found
,V/AlarmManager(  790): waitForAlarm result :4
,I/PeopleContactsSync( 5588): Updated babel action mime type
,V/AlarmManager(  790): waitForAlarm result :4
D/dalvikvm( 5674): GC_EXPLICIT freed 1465K, 43% free 10850K/18972K, paused 9ms+6ms, total 49ms
I/PhenotypeConfigurator( 5588): Scheduling Phenotype for one-off execution 5967 seconds from now (1449626679753)
,D/WearInitializer( 5588): Running WearInitializer
,I/PeopleContactsSync( 5588): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 5588): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/WearInitializer( 5588): enabled .WearableService
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,D/EnterpriseDeviceManagerService(  790): Creating context as user 0
,D/EnterpriseDeviceManagerService(  790): Creating context as user 0
,W/InstanceID/Rpc( 5588): Found 10011
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,W/IcingInternalCorpora( 5588): getNumBytesRead when not calculated.
,I/System.out( 5588): Thread-616(HTTPLog):isShipBuild true
,I/System.out( 5588): Thread-616(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/AlarmManager(  790): waitForAlarm result :4
,D/dalvikvm( 5588): GC_CONCURRENT freed 2087K, 37% free 12056K/18972K, paused 4ms+4ms, total 43ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 27ms
,V/AlarmManager(  790): waitForAlarm result :4
,I/PeopleContactsSync( 5588): CP2 cleanup done, kept= duration=164 ms
,I/PeopleContactsSync( 5588): ===CP2 sync finished, success=true, time=576,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,D/LocationInitializer( 5588): Restart initialization of location
,E/dalvikvm( 5588): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.gms.lockbox.LockboxService.a
,W/dalvikvm( 5588): VFY: unable to resolve check-cast 61 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/gms/lockbox/LockboxService;
,D/dalvikvm( 5588): VFY: replacing opcode 0x1f at 0x0035
,E/dalvikvm( 5554): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.gms.lockbox.LockboxService.a
,W/dalvikvm( 5554): VFY: unable to resolve check-cast 61 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/gms/lockbox/LockboxService;
,D/dalvikvm( 5554): VFY: replacing opcode 0x1f at 0x0035
V/AlarmManager(  790): waitForAlarm result :4
V/AlarmManager(  790): waitForAlarm result :4
,D/Icing   ( 5588): Loaded CLD2 Version V2.0 - 20141016
,D/LocationInitializer( 5588): Restart initialization of location
,W/GeofencerStateMachine( 5554): Ignoring removeGeofence because network location is disabled.
V/AlarmManager(  790): waitForAlarm result :4
,W/GCoreFlp( 5554): No location to return for getLastLocation()
,W/FusedLocationProvider( 5554): location=null
,D/LocationInitializer( 5588): Restart initialization of location
V/AlarmManager(  790): waitForAlarm result :4
V/AlarmManager(  790): waitForAlarm result :4
,E/ctxmgr  ( 5554): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
V/AlarmManager(  790): waitForAlarm result :4
,W/IcingInternalCorpora( 5588): getNumBytesRead when not calculated.
,W/GCoreFlp( 5554): No location to return for getLastLocation()
,W/FusedLocationProvider( 5554): location=null
V/AlarmManager(  790): waitForAlarm result :4
V/AlarmManager(  790): waitForAlarm result :4
,W/GCoreFlp( 5554): No location to return for getLastLocation()
,W/FusedLocationProvider( 5554): location=null
V/AlarmManager(  790): waitForAlarm result :4
V/AlarmManager(  790): waitForAlarm result :4
V/AlarmManager(  790): waitForAlarm result :4
V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,W/ctxmgr  ( 5554): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10011, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 5554): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
V/AlarmManager(  790): waitForAlarm result :4
,I/PeopleSync( 5588): ***Sync finished***, duration: 1201 [5005f081]
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,D/dalvikvm( 5588): GC_CONCURRENT freed 1942K, 36% free 12161K/18972K, paused 4ms+4ms, total 46ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 29ms
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,I/MDM     ( 5588): [626] SitrepService.onHandleIntent: Sitrep successful
,D/dalvikvm(  790): GC_CONCURRENT freed 3785K, 56% free 24347K/55192K, paused 5ms+12ms, total 132ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 62ms
D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 63ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 63ms
,D/EnterpriseDeviceManagerService(  790): Creating context as user 0
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): waitForAlarm result :4
,D/SSRMv2:SIOP(  790): SIOP:: AP = 330, Delta = 0
,D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5588): Module APK com.google.android.play.games already loaded
,W/PlaySystemBroadcastReceiver( 5588): Processed handlePeopleChanged at 148959
V/AlarmManager(  790): waitForAlarm result :4
D/ChimeraCfgMgr( 5588): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5588): Module APK com.google.android.play.games already loaded
V/AlarmManager(  790): waitForAlarm result :4
,W/DataBroker( 5588): No player ID found and calling context is not the dest app
,D/dalvikvm( 5588): GC_CONCURRENT freed 2763K, 35% free 12470K/18972K, paused 3ms+3ms, total 34ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/dalvikvm( 5588): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.isUninstalledAppPossiblyUpdating
,W/dalvikvm( 5588): VFY: unable to resolve virtual method 499: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5588): VFY: replacing opcode 0x6e at 0x000d
,E/SMD     (  241): DCD ON
,I/GAV2    ( 5770): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm( 5588): GC_CONCURRENT freed 1951K, 34% free 12543K/18972K, paused 3ms+3ms, total 32ms
,D/dalvikvm( 5588): GC_CONCURRENT freed 2120K, 35% free 12471K/18972K, paused 3ms+4ms, total 33ms
,D/dalvikvm( 5588): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/Icing   ( 5588): Indexing 59478A9356B7E22B0F7D1E3B5331D81E6FA15A0E from com.google.android.gms
,I/Icing   ( 5588): Indexing done 59478A9356B7E22B0F7D1E3B5331D81E6FA15A0E
,I/Icing   ( 5588): Indexing B99747EE099BE87AB5067ABA113A1984F9C06AEF from com.google.android.gms
,I/Icing   ( 5588): Indexing done B99747EE099BE87AB5067ABA113A1984F9C06AEF
,I/Icing   ( 5588): Indexing 1F88D4ACB7A44E3C2607D9C1958CD55DCD7CED5E from com.google.android.gms
,I/Icing   ( 5588): Indexing done 1F88D4ACB7A44E3C2607D9C1958CD55DCD7CED5E
,I/Icing   ( 5588): Indexing 7AE4612938666FB9CE7414062F616B44679193A3 from com.google.android.gms
,I/Icing   ( 5588): Indexing done 7AE4612938666FB9CE7414062F616B44679193A3
,I/Icing   ( 5588): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 5588): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/dalvikvm( 5588): GC_CONCURRENT freed 3288K, 36% free 12207K/18972K, paused 5ms+5ms, total 59ms
,I/IcingCorporaProvider( 2183): UpdateCorporaTask done [took 6535 ms] updated apps [took 6535 ms] 
,I/Icing   ( 5588): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 5588): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/Icing   ( 5588): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 5588): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/PackageManager(  790): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager(  790): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10011, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@4325be48, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/InputReader(  790): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "sms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/SMD     (  241): DCD ON
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "smsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mmsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 1262): GC_CONCURRENT freed 6146K, 32% free 18620K/27108K, paused 9ms+6ms, total 117ms
,D/dalvikvm( 1262): WAIT_FOR_CONCURRENT_GC blocked 87ms
,D/dalvikvm(  790): GC_CONCURRENT freed 3400K, 56% free 24681K/54952K, paused 9ms+21ms, total 221ms
D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 149ms
D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 152ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 144ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 145ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 83ms
,D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 151ms
,D/PackageManager(  790): queryIntentReceivers - Execution time: 156 ms
W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "sms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "smsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/IcingCorporaProvider( 2183): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  790):   Scheme: "mmsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 5988): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5988):  
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5988): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5988):  
I/SELinux ( 5988):  
,I/SELinux ( 5988): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5988): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5988): >>>>> Normal User
,E/dalvikvm( 5988): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 5988): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 5988): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5988): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5988): Added TimaKesytore provider
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/GCoreNlp( 5554): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/FileShare-Server( 5988): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/BezelQuickConnect( 3368): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 3368): BezelBroadcastReceiver - packageName : com.google.android.gms
,D/PackageBroadcastService( 5588): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5588): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5588): updateResources: need to parse f{com.google.android.gms}
,D/LocationProviderProxy(  790): applying state to connected service
,D/LocationProviderProxy(  790): applying state to connected service
,I/IcingCorporaProvider( 2183): UpdateCorporaTask done [took 461 ms] updated apps [took 461 ms] 
,W/ApplicationsProvider( 1413): Could not fetch usage stats
W/ApplicationsProvider( 1413): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1413): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1413): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1413): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1413): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 1413): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1413): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1413): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Icing   ( 5588): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 5588): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  790): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/AlarmManager(  790): waitForAlarm result :4
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  790): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP(  790): SIOP:: AP = 310, Delta = -20
,D/Headlines( 4095): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4095): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4095): Breath 101216 latestRequest time : 1449626589671 current time : 1449626690887
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 3720): Failed write_ctrl(u 73) res=-1 errno=22
,I/qtaguid ( 3720): Untagging socket 73 failed errno=-22
W/NetworkManagementSocketTagger( 3720): untagSocket(73) failed with errno -22
,I/System.out( 3720): Thread-346 calls detatch()
,D/Finsky  ( 3720): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 1 successful.
,D/Finsky  ( 3720): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = -10
,E/Watchdog(  790): !@Sync 5
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  790): [PWL] Off : 105s ago
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 295, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4095): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4095): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/Headlines( 4095): Breath 131935 latestRequest time : 1449626589671 current time : 1449626721625
,D/Headlines( 4095): stop 
D/BatteryService(  790): stay LED for fully charged
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Headlines( 4095): Breath.onDestroy : 
,I/ActivityManager(  790): Killing 4644:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,E/ActivityThread( 5588): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  790): failed sync operation 
,D/SyncManager(  790): not retrying sync operation because the error is a hard error: 
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 293, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  790): !@Sync 6
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,I/PowerManagerService(  790): [PWL] Off : 140s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): stay LED for fully charged
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 5554): GC_CONCURRENT freed 1541K, 40% free 11484K/18972K, paused 15ms+6ms, total 73ms
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  790): !@Sync 7
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  790): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  790): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  790): !@Sync 8
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5588): GC_CONCURRENT freed 1939K, 36% free 12250K/18972K, paused 15ms+24ms, total 168ms
,I/ClearcutLoggerApiImpl( 5588): disconnect managed GoogleApiClient
,D/dalvikvm( 5674): GC_CONCURRENT freed 1879K, 42% free 11019K/18972K, paused 3ms+6ms, total 51ms
,D/dalvikvm( 5674): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SELinux ( 6076): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6076):  
,D/GetConfigurationSnapshotOperation( 5554): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/SELinux ( 6076): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6076):  
I/SELinux ( 6076):  
,I/SELinux ( 6076): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6076): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6076): >>>>> Normal User
,E/dalvikvm( 6076): >>>>> com.google.android.gms.unstable [ userId:0 | appId:10011 ]
,E/SELinux ( 6076): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/PhenotypeFlagCommitter( 5554): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 5554): Using platform SSLCertificateSocketFactory
,D/TimaKeyStoreProvider( 6076): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6076): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6076): Added TimaKesytore provider
,D/LocationManagerService(  790): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 5554): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 5554): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 5554): VFY: replacing opcode 0x6e at 0x003d
W/dalvikvm( 6076): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6076): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 6076): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 6076): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 6076): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 6076): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6076): install
,I/MultiDex( 6076): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 6076): loading existing secondary dex files
,I/MultiDex( 6076): load found 3 secondary dex files
,I/System.out( 5554): Thread-609(HTTPLog):isShipBuild true
,I/System.out( 5554): Thread-609(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/MultiDex( 6076): install done
,D/dalvikvm( 6076): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6076): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6076): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6076): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6076): VFY: unable to resolve instance field 36
,D/dalvikvm( 6076): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 6076): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6076): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6076): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 6076): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6076): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 6076): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42664e80
D/dalvikvm( 6076): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42664e80
,D/dalvikvm( 6076): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42664e80, skipping init
,D/dalvikvm( 6076): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42664e80
D/dalvikvm( 6076): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42664e80
,V/JNIHelp ( 6076): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 6076): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42664e80
,D/dalvikvm( 6076): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42664e80
D/dalvikvm( 6076): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42664e80
,D/dalvikvm( 6076): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42664e80
,I/ProviderInstaller( 6076): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 5554): callingUid 10011, callindPid: 5554
,E/MDM     ( 5554): [613] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5588): Restart initialization of location
,D/AuthorizationBluetoothService( 5674): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 5674): Proximity feature is not enabled.
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 6076): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 6076): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6076): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 6076): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 6076): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6076): VFY: replacing opcode 0x6e at 0x000d
,E/SMD     (  241): DCD ON
,I/dalvikvm( 6076): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 6076): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 6076): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 6076): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 6076): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 6076): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 6076): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 6076): VFY: replacing opcode 0x6e at 0x0036
W/GCoreFlp( 5554): No location to return for getLastLocation()
,W/FusedLocationProvider( 5554): location=null
I/dalvikvm( 6076): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 6076): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 6076): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/LocationManagerService(  790): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,W/Uploader( 5554):  no longer exists, so no auth token.
,D/WVCdm   (  250): Instantiating CDM.
,I/WVCdm   (  250): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  250): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/QSEECOMAPI: (  250): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  250): App is not loaded in QSEE
E/QSEECOMAPI: (  250): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  250): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  250): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  250): App is not loaded in QSEE
,E/QSEECOMAPI: (  250): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  250): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  250): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  250): App is not loaded in QSEE
,I/dalvikvm( 6076): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 6076): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 6076): VFY: replacing opcode 0x6e at 0x003d
,W/dalvikvm( 6076): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 6076): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/QSEECOMAPI: (  250): Loaded image: APP id = 5
D/DrmWidevineDash(  250): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb25b7000
,E/DrmWidevineDash(  250): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb25b7000
,W/dalvikvm( 6076): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 6076): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 6076): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 6076): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 6076): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  250): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  250): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  250): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  250): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  250): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  250): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   (  250): CdmEngine::OpenSession
,D/DrmWidevineDash(  250): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  250): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  250): OEMCrypto_OpenSession returns 0
,D/LocationManagerService(  790): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/WVCdm   (  250): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  250): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  250): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
I/System.out( 6076): Thread-563(HTTPLog):isShipBuild true
,I/System.out( 6076): Thread-563(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
D/DrmWidevineDash(  250): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  250): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  250): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  250): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  250): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  250): PrepareKeyRequest: nonce=3245403031
,D/DrmWidevineDash(  250): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  250): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  250): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  250): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 6076): Install completed successfully. count=14 extracted=0
,D/LocationManagerService(  790): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  790): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  790): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/DrmWidevineDash(  250): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  250): CdmEngine::CloseSession
,D/DrmWidevineDash(  250): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  250): OEMCrypto_CloseSession returns 0
,D/LocationManagerService(  790): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 5554): GC_CONCURRENT freed 1637K, 38% free 11774K/18972K, paused 5ms+7ms, total 52ms
,D/LocationManagerService(  790): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  790): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 5674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 6076): GC_CONCURRENT freed 5955K, 39% free 11677K/18972K, paused 3ms+8ms, total 72ms
,D/dalvikvm(  790): GC_CONCURRENT freed 4186K, 56% free 24189K/54952K, paused 7ms+19ms, total 197ms
,D/dalvikvm( 6076): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429d5430
,D/dalvikvm( 6076): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429d5430
,D/dalvikvm( 6076): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429d5430, skipping init
,D/dalvikvm( 6076): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6129): DexOpt: load 6ms, verify+opt 8ms, 128252 bytes
,D/dalvikvm( 6076): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6076): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 164ms
,I/Adreno-EGL( 6076): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6076): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 6076): Build Date: 03/21/14 Fri
I/Adreno-EGL( 6076): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 6076): Remote Branch: 
I/Adreno-EGL( 6076): Local Patches: 
I/Adreno-EGL( 6076): Reconstruct Branch: 
,I/dalvikvm( 5674): Total arena pages for JIT: 11
,I/dalvikvm( 5674): Total arena pages for JIT: 12
I/dalvikvm( 5674): Total arena pages for JIT: 13
,I/dalvikvm( 5674): Total arena pages for JIT: 14
,D/GetConfigurationSnapshotOperation( 5554): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 5554): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 5554): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  790): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  790): Killing 4207:com.android.calendar/u0a142 (adj 15): empty #43
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  790): !@Sync 9
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  790): [PWL] Off : 225s ago
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService(  790): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  790): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  790): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  790): initializing...
,I/TLC_TIMA_PKM_initialize(  790): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  790): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  790): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  790): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  790): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  790): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  790): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  790): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  790): App is not loaded in QSEE
,D/QSEECOMAPI: (  790): Loaded image: APP id = 6
,I/TZ: qc_tlc_communication(  790): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  790): Trustlet response is completed
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  790): !@Sync 10
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService(  790): [PWL] Off : 275s ago
,V/AlarmManager(  790): waitForAlarm result :4
,V/AlarmManager(  790): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,I/SELinux ( 6165): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6165):  
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,I/SELinux ( 6165): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6165):  
I/SELinux ( 6165):  
,I/SELinux ( 6165): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6165): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 6165): >>>>> Normal User
,E/dalvikvm( 6165): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 6165): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6165): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6165): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6165): Added TimaKesytore provider
,E/SMD     (  241): DCD ON
,W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=6165, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  790): Killing 4648:com.android.providers.calendar/u0a44 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 11
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 12
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,I/ClearcutLoggerApiImpl( 5674): disconnect managed GoogleApiClient
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
I/PowerManagerService(  790): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 13
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,E/SMD     (  241): DCD ON
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 14
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  790): [PWL] Off : 390s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 15
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 16
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService(  790): [PWL] Off : 455s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 17
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 18
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 19
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService(  790): [PWL] Off : 525s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/TimaService(  790): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  790): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  790): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  790): !@Sync 20
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,E/SMD     (  241): DCD ON
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  790): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 21
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  790): [PWL] Off : 600s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/dalvikvm(  790): GC_CONCURRENT freed 3726K, 57% free 24045K/54952K, paused 24ms+38ms, total 447ms
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 22
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  790): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  790): <AppSync3 Whitelist>
,V/AlarmManager(  790): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 23
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 24
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  790): [PWL] Off : 680s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 25
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 26
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 27
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  790): [PWL] Off : 765s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,E/SMD     (  241): DCD ON
D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 28
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 29
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService(  790): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  790): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  790): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 30
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService(  790): [PWL] Off : 855s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 31
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :4
,I/SensorManagerA(  790): getReportingMode :: sensor.mType = 5
D/LightsService(  790): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors (  790): LightSensor setDelay = 200000000
,D/Sensors (  790): LightSensor setSensorDelay = 200000000
,D/Sensors (  790): Light sensor flush: not enabled 0
,D/Sensors (  790): LightSensor enable = 1
,D/Sensors (  790): LightSensor enableSensor = 1
,D/SensorManager(  790): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  790): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): stay LED for fully charged
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/Sensors (  790): LightSensor enable = 0
,D/Sensors (  790): LightSensor enableSensor = 0
,D/SensorManager(  790): unregisterListener ::   
D/LightsService(  790): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  790): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  241): DCD ON
,D/ConnectivityService(  790): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 32
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 33
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  790): [PWL] Off : 950s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 34
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 35
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 36
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  790): [PWL] Off : 1050s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 37
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/dalvikvm(  790): GC_CONCURRENT freed 3543K, 57% free 24073K/54952K, paused 20ms+38ms, total 444ms
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 38
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 39
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  790): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  790): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  790): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 40
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  790): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 41
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 42
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  790): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  790): <AppSync3 Whitelist>
,V/AlarmManager(  790): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 43
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  790): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 44
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 45
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,E/SMD     (  241): DCD ON
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 46
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 47
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  790): [PWL] Off : 1380s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 48
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 49
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  790): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  790): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  790): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 50
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 51
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  790): [PWL] Off : 1500s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 52
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 53
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 54
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/dalvikvm(  790): GC_CONCURRENT freed 3574K, 57% free 24078K/54952K, paused 23ms+37ms, total 444ms
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 55
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  790): [PWL] Off : 1625s ago
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 56
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 57
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 58
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  790): !@Sync 59
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/TimaService(  790): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  790): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  790): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  790): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  790): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 60
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  790): [PWL] Off : 1755s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,E/SMD     (  241): DCD ON
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  790): Prepared write state in 118ms
,I/ProcessStatsService(  790): Prepared write state in 96ms
,I/ProcessStatsService(  790): Pruning old procstats: /data/system/procstats/state-2015-12-08-13-39-31.bin
,E/Watchdog(  790): !@Sync 61
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  790): waitForAlarm result :4
,I/SensorManagerA(  790): getReportingMode :: sensor.mType = 5
,D/LightsService(  790): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  790): LightSensor setDelay = 200000000
D/Sensors (  790): LightSensor setSensorDelay = 200000000
D/Sensors (  790): Light sensor flush: not enabled 0
D/Sensors (  790): LightSensor enable = 1
D/Sensors (  790): LightSensor enableSensor = 1
D/SensorManager(  790): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NtpTrustedTime(  790): currentTimeMillis() cache hit
V/NetworkStats(  790): performPollLocked(flags=0x3)
,V/AlarmManager(  790): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): stay LED for fully charged
,V/AlarmManager(  790): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/LightsService(  790): [SvcLED]  onSensorChanged::light value = 0
,D/Sensors (  790): LightSensor enable = 0
,D/Sensors (  790): LightSensor enableSensor = 0
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SensorManager(  790): unregisterListener ::   
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/LightsService(  790): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/NtpTrustedTime(  790): currentTimeMillis() cache hit
V/NetworkStats(  790): performPollLocked() took 317ms
,D/NtpTrustedTime(  790): currentTimeMillis() cache hit
,D/NtpTrustedTime(  790): currentTimeMillis() cache hit
,E/SMD     (  241): DCD ON
,I/EventLogService( 5588): Aggregate from 1449625963642 (log), 1449625963642 (data)
,I/dalvikvm( 5588): Jit: resizing JitTable from 4096 to 8192
,D/ConnectivityService(  790): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 62
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  790): waitForAlarm result :8
,V/AlarmManager(  790): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  790): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  790): <AppSync3 Whitelist>
,V/AlarmManager(  790): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,I/ActivityManager(  790): Killing 4549:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1841s
,I/ActivityManager(  790): Killing 3886:com.google.android.music:main/u0a122 (adj 15): empty for 1841s
,I/ActivityManager(  790): Killing 4598:com.sec.phone/1001 (adj 15): empty for 1841s
,I/ActivityManager(  790): Killing 4413:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty for 1841s
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  790): !@Sync 63
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  790): stay LED for fully charged
,D/UiModeManager(  790): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,E/SMD     (  241): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1946): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/BatteryService(  790): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  790): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  790): stay LED for fully charged
D/UiModeManager(  790): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
V/HeadsetService( 1946): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 1946): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  241): DCD ON
E/SMD     (  241): DCD ON
D/SSRMv2:SIOP(  790): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  790): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
D/AndroidRuntime( 6530): 
D/AndroidRuntime( 6530): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6530): CheckJNI is OFF
D/AndroidRuntime( 6530): setted country_code = Poland
D/AndroidRuntime( 6530): setted countryiso_code = PL
D/AndroidRuntime( 6530): setted sales_code = XEO
D/AndroidRuntime( 6530): readGMSProperty: start
D/AndroidRuntime( 6530): readGMSProperty: already setted!!
D/AndroidRuntime( 6530): readGMSProperty: end
D/AndroidRuntime( 6530): addProductProperty: start
D/dalvikvm( 6530): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6530): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6530): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6530): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6530): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6530): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6530): failed to load memtrack module: -2
D/dalvikvm( 6530): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6530): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  790): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  790): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  790): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  790): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  790): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  790): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  790): START PACKAGE DELETE: observer{1130119992}
D/PackageManager(  790): pkg{<packageName>}
D/PackageManager(  790): user{0}
D/PackageManager(  790): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManagerService(  790): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  790): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  790): getApplicationUninstallationEnabled
D/ApplicationPolicy(  790): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  790): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  790): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  790): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  790): Killing 5334:com.test.thalitest/u0a179 (adj 15): stop com.test.thalitest
I/ActivityManager(  790): Killing 5621:com.android.keychain/1000 (adj 15): empty for 1806s
I/ActivityManager(  790): Killing 5607:com.samsung.android.intelligenceservice/u0a5 (adj 15): empty for 1806s
I/ActivityManager(  790): Killing 4483:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty for 1807s
I/ActivityManager(  790): Killing 5454:com.sec.android.app.mss/u0a21 (adj 15): empty for 1807s
I/ActivityManager(  790): Killing 5542:com.sec.esdk.elm/u0a94 (adj 15): empty for 1808s
I/ActivityManager(  790): Killing 5089:com.android.defcontainer/u0a6 (adj 15): empty for 1809s
W/PackageSettings(  790): Skipping PackageSetting{42ac1858 com.example.hello/10180} due to missing metadata
D/PackageManager(  790): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 2183): GC_EXPLICIT freed 1031K, 41% free 11261K/18972K, paused 5ms+3ms, total 33ms
D/dalvikvm( 1413): GC_EXPLICIT freed 644K, 48% free 10007K/18972K, paused 2ms+3ms, total 26ms
D/dalvikvm( 5588): GC_EXPLICIT freed 419K, 36% free 12279K/18972K, paused 13ms+6ms, total 58ms
D/PackageManager(  790): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 1088): onReceive: android.intent.action.PACKAGE_REMOVED
D/AdaptiveEventManager( 1069): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3352): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 5554): Ignoring removeGeofence because network location is disabled.
I/InputReader(  790): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "sms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6558): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6558):  
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "smsto"
D/EnterpriseDeviceManagerService(  790): Package has changed for user 0
D/EnterpriseDeviceManagerService(  790): Admin package name: com.google.android.gms
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  790): JIT code cache reset in 3 ms (1535832 bytes 1/0)
I/SELinux ( 6558): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6558):  
I/SELinux ( 6558):  
I/SELinux ( 6558): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6558): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6558): >>>>> Normal User
E/dalvikvm( 6558): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6558): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  790): GC_EXPLICIT freed 3594K, 57% free 24148K/54952K, paused 7ms+16ms, total 172ms
D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 117ms
D/TimaKeyStoreProvider( 6558): in addTimaSignatureService
D/TimaKeyStoreProvider( 6558): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6558): Added TimaKesytore provider
D/dalvikvm(  790): GC_EXPLICIT freed 141K, 57% free 24009K/54952K, paused 6ms+11ms, total 125ms
D/dalvikvm(  790): WAIT_FOR_CONCURRENT_GC blocked 180ms
D/PackageManager(  790): queryContentProviders - Execution time: 134 ms
D/PackageManager(  790): getApplicationInfo - Execution time: 201 ms
D/RCPManagerService(  790): PackageReceiver onReceive()
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "mms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PackageManager(  790): delete sourFile : 
D/PackageManager(  790): delete native library directory: 
D/PackageManager(  790): return delete result to caller: 1130119992
D/AndroidRuntime( 6530): Shutting down VM
D/dalvikvm( 6530): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
D/PackageManager(  790): returnCode: 1
I/HarmonyEASService(  790): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "mmsto"
W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=6558, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "sms"
W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 6558): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6558): ELMEngine.ELMEngine( context ).
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 6558): MDMBridge.setEnterpriseBridge()
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "smsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "sms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 6558): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6558): ElmAgentService : onCreate()
D/elm:14132( 6558): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6558): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6558): MDMBridge.getInstance()
D/elm:14132( 6558): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "mms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "smsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 6558): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "mms"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BackupManagerService(  790): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  790): removePackageParticipantsLocked: uid=10179 #1
I/SELinux ( 6576): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6576):  
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "mmsto"
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  248): GC_EXPLICIT freed 44K, 50% free 9509K/18972K, paused 2ms+3ms, total 33ms
D/elm:14132( 6558): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 6558): ElmAgentService : onDestroy().
I/SELinux ( 6576): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6576):  
I/SELinux ( 6576):  
I/SELinux ( 6576): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/PackageManager(  790): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  790):   Action: "android.intent.action.SENDTO"
E/SELinux ( 6576): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  790):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  790):   Scheme: "mmsto"
E/dalvikvm( 6576): >>>>> Normal User
E/dalvikvm( 6576): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18972K, paused 2ms+3ms, total 22ms
E/SELinux ( 6576): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6576): in addTimaSignatureService
D/TimaKeyStoreProvider( 6576): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6576): Added TimaKesytore provider
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9509K/18972K, paused 3ms+4ms, total 24ms
W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  790): Permission Denial: getCurrentUser() from pid=6576, uid=10021 requires android.permission.INTERACT_ACROSS_USERS
E/SQLiteDatabase( 6576): Failed to open database '/data/data/com.sec.android.app.mss/databases/user.db'.
E/SQLiteDatabase( 6576): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6576): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6576): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6576): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6576): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6576): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6576): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6576): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6576): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6576): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6576): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6576): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6576): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6576): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6576): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6576): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/SQLiteDatabase( 6576): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 6576): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 6576): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 6576): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 6576): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6576): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6576): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6576): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6576): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6576): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6576): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6576): 	at dalvik.system.NativeStart.main(Native Method)
W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 6576): Shutting down VM
W/dalvikvm( 6576): threadid=1: thread exiting with uncaught exception (group=0x418b0da0)
W/Resources(  790): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/AndroidRuntime( 6576): FATAL EXCEPTION: main
E/AndroidRuntime( 6576): Process: com.sec.android.app.mss, PID: 6576
E/AndroidRuntime( 6576): java.lang.RuntimeException: Unable to start receiver com.sec.android.app.mss.receiver.VerificationReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6576): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 6576): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 6576): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 6576): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6576): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6576): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 6576): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 6576): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 6576): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 6576): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 6576): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 6576): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6576): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6576): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6576): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6576): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6576): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6576): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6576): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6576): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6576): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6576): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6576): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6576): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6576): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6576): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6576): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/AndroidRuntime( 6576): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/AndroidRuntime( 6576): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 6576): 	... 10 more
D/InputReader(  790): Processing first event
I/PCWCLIENTTRACE_PushUtil( 5214): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5214): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5214): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5214): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/Process ( 6576): Sending signal. PID: 6576 SIG: 9
I/ActivityManager(  790): Process com.sec.android.app.mss (pid 6576) (adj 9) has died.

```
