#### Test 506502785223c58_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5184): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5184):  
,--------- beginning of /dev/log/system
I/ActivityManager(  770): Killing 3968:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  251): GC_EXPLICIT freed 46K, 50% free 9514K/18708K, paused 2ms+3ms, total 34ms
I/SELinux ( 5184): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5184):  
I/SELinux ( 5184):  
I/SELinux ( 5184): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5184): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5184): >>>>> Normal User
E/dalvikvm( 5184): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5184): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9514K/18708K, paused 1ms+3ms, total 20ms
D/TimaKeyStoreProvider( 5184): in addTimaSignatureService
D/TimaKeyStoreProvider( 5184): Cannot add TimaSignature Service, License check Failed
D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9514K/18708K, paused 2ms+3ms, total 20ms
D/ActivityThread( 5184): Added TimaKesytore provider
I/PowerManagerService(  770): [PWL] Off : 50s ago
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5184, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5184): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
D/AndroidRuntime( 5197): 
D/AndroidRuntime( 5197): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5197): CheckJNI is OFF
D/AndroidRuntime( 5197): setted country_code = Poland
D/AndroidRuntime( 5197): setted countryiso_code = PL
D/AndroidRuntime( 5197): setted sales_code = XEO
D/AndroidRuntime( 5197): readGMSProperty: start
D/AndroidRuntime( 5197): readGMSProperty: already setted!!
D/AndroidRuntime( 5197): readGMSProperty: end
D/AndroidRuntime( 5197): addProductProperty: start
W/ActivityManager(  770): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5184): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
D/dalvikvm( 5197): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5197): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5197): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5197): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5197): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SA      ( 4042): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4042): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4042): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4324): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2173): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4671): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5219): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5219):  
I/SELinux ( 5219): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5219):  
I/SELinux ( 5219):  
I/SELinux ( 5219): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5219): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5219): >>>>> Normal User
E/dalvikvm( 5219): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/memtrack( 5197): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5197): failed to load memtrack module: -2
E/SELinux ( 5219): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5219): in addTimaSignatureService
D/TimaKeyStoreProvider( 5219): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5219): Added TimaKesytore provider
D/dalvikvm( 5197): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/dalvikvm( 2173): GC_CONCURRENT freed 1600K, 38% free 11714K/18708K, paused 3ms+2ms, total 75ms
D/dalvikvm( 2173): WAIT_FOR_CONCURRENT_GC blocked 48ms
I/IcingCorporaProvider( 2173): UpdateCorporaTask done [took 180 ms] updated apps [took 180 ms] 
D/CapabilityManagerService New( 5219): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
D/AndroidRuntime( 5197): Calling main entry com.android.commands.am.Am
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5219, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5234): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5234):  
I/ActivityManager(  770): Killing 3980:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/ActivityManager(  770): Killing 4253:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5234): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5234):  
I/SELinux ( 5234):  
I/SELinux ( 5234): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5234): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5234): >>>>> Normal User
E/dalvikvm( 5234): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5234): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
V/ApplicationPolicy(  770): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TimaKeyStoreProvider( 5234): in addTimaSignatureService
D/TimaKeyStoreProvider( 5234): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5234): Added TimaKesytore provider
D/CustomFrequencyManagerService(  770): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  770): mDVFSHelper.acquire()
I/SELinux ( 5246): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5246):  
D/SSRMv2:SIOP(  770): SIOP:: AP = 310, Delta = 0
D/LockPatternUtils( 1065): isPcwEnable = null
D/AndroidRuntime( 5197): Shutting down VM
D/dalvikvm( 5197): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
E/SMD     (  241): DCD ON
D/SurfaceWidgetView( 1250): destroyHardwareResources():1125786328
I/SurfaceFlinger(  250): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  250): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SELinux ( 5246): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5246):  
I/SELinux ( 5246):  
I/SELinux ( 5246): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5246): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5246): >>>>> Normal User
E/dalvikvm( 5246): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5246): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/SurfaceFlinger(  250): id=9 Removed Mauncher (7/11)
I/SurfaceFlinger(  250): id=9 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1444): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1250): onTrimMemory. Level: 20
D/TimaKeyStoreProvider( 5246): in addTimaSignatureService
D/TimaKeyStoreProvider( 5246): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5246): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/LockPatternUtils( 1065): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2067): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2067): getDatabaseLocked(b,b,pwd)...
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5246, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5246, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5246): Binding Chromium to the background looper Looper (main, tid 1) {422730f0}
I/chromium( 5246): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5246): Initializing chromium process, renderers=0
W/chromium( 5246): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5246): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5246): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5246): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5246): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5246): Remote Branch: 
I/Adreno-EGL( 5246): Local Patches: 
I/Adreno-EGL( 5246): Reconstruct Branch: 
,I/dalvikvm( 5246): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5246): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5246): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5246): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x0008
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5234, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
W/dalvikvm( 5246): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5246): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5246): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5246): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5246): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5246): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5246): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5246): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5246): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5246): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5246): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger(  250): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5246): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 5246): Enabling debug mode 0
W/AwContents( 5246): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  770): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  770): mDVFSHelper.release()
D/CustomFrequencyManagerService(  770): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1779979, pollInterval: 10000
I/SELinux ( 5305): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5305):  
I/ActivityManager(  770): Killing 3993:com.sec.android.soagent/u0a37 (adj 15): empty #43
D/JsMessageQueue( 5246): Set native->JS mode to OnlineEventsBridgeMode
W/GAV2    ( 5234): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5305): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5305):  
I/SELinux ( 5305):  
I/SELinux ( 5305): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5305): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5305): >>>>> Normal User
E/dalvikvm( 5305): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5305): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5305): in addTimaSignatureService
D/TimaKeyStoreProvider( 5305): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5305): Added TimaKesytore provider
D/dalvikvm( 5246): Trying to load lib /data/app-lib/com.test.thalitest-56/libjxcore.so 0x42599e28
D/PackageIntentReceiver( 5305): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5305): Not GearManger package! 
D/dalvikvm( 5246): Added shared lib /data/app-lib/com.test.thalitest-56/libjxcore.so 0x42599e28
D/jxcore_app_log( 5246): JniHelper::setJavaVM(0x4171e528), pthread_self() = 2033061736
D/JX-Cordova( 5246): jxcore cordova android initializing
I/SELinux ( 5321): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5321):  
I/SELinux ( 5321): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5321):  
I/SELinux ( 5321):  
I/SELinux ( 5321): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5321): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5321): >>>>> Normal User
E/dalvikvm( 5321): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5321): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5321): in addTimaSignatureService
D/TimaKeyStoreProvider( 5321): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5321): Added TimaKesytore provider
D/MagazineService Version( 5321): Magazine-Channel: 13
D/MagazineService Version( 5321): Magazine-Provider: 13
D/MagazineService Version( 5321): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5321): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5321): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5321, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5321): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5334): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5334):  
D/MagazineService::MagazineService( 5321): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  770): Killing 1335:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 5334): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5334):  
I/SELinux ( 5334):  
I/SELinux ( 5334): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5334): >>>>> Normal User
E/dalvikvm( 5334): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5334): in addTimaSignatureService
D/TimaKeyStoreProvider( 5334): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5334): Added TimaKesytore provider
W/GAV2    ( 5234): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  770): Killing 4368:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
,D/dalvikvm( 5246): GC_CONCURRENT freed 4909K, 32% free 12786K/18708K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 5246): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/SELinux ( 5348): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5348):  
I/ActivityManager(  770): Killing 4383:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,I/SELinux ( 5348): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5348):  
I/SELinux ( 5348):  
,I/SELinux ( 5348): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5348): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5348): >>>>> Normal User
,E/dalvikvm( 5348): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5348): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5348): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5348): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5348): Added TimaKesytore provider
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5348, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5348): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5360): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5360):  
,I/ActivityManager(  770): Killing 4395:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5360): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5360):  
I/SELinux ( 5360):  
,I/SELinux ( 5360): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5360): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5360): >>>>> Normal User
,E/dalvikvm( 5360): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5360): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5360): in addTimaSignatureService
D/TimaKeyStoreProvider( 5360): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5360): Added TimaKesytore provider
,I/ActivityManager(  770): Killing 3583:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/Finsky  ( 3687): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1754): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1754): Loading module APK com.google.android.play.games
,D/CustomFrequencyManagerService(  770): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  tag : ACTIVITY_RESUME_BOOSTER@9
D/PackageBroadcastService( 1754): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/dalvikvm( 1754): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1754): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1754): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1754): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1754): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1754): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1754): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1754): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1754): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1754): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1754): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/dalvikvm( 5246): GC_FOR_ALLOC freed 4672K, 27% free 15745K/21452K, paused 34ms, total 34ms
,D/ChimeraModuleLdr( 1754): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1754): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1754): Submit a task: k
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1754): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1754): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1754): Processing package: com.test.thalitest
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,D/dalvikvm( 1754): GC_CONCURRENT freed 1875K, 37% free 11914K/18708K, paused 5ms+5ms, total 96ms
,D/dalvikvm( 1754): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/dalvikvm( 1754): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/dalvikvm( 1754): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/dalvikvm( 1754): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/dalvikvm( 1754): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/dalvikvm( 1754): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 1754): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/GassUtils( 1754): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1754): Found info for package com.test.thalitest in db.
,D/dalvikvm( 1754): WAIT_FOR_CONCURRENT_GC blocked 46ms
,W/dalvikvm( 1754): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1754): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1754): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x000e
,W/dalvikvm( 1754): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1754): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1754): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1754): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1754): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1754): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1754): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1754): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
,W/dalvikvm( 1754): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1754): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1754): cleanUpNonGplusAccounts done.
,D/dalvikvm( 5246): GC_FOR_ALLOC freed 5057K, 31% free 16760K/24140K, paused 35ms, total 35ms
,I/dalvikvm-heap( 5246): Grow heap (frag case) to 21.715MB for 2475476-byte allocation
,W/dalvikvm( 1754): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1754): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1754): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5246): GC_FOR_ALLOC freed 3779K, 35% free 17445K/26560K, paused 31ms, total 31ms
,D/dalvikvm( 5246): GC_FOR_ALLOC freed 1132K, 35% free 17428K/26560K, paused 28ms, total 28ms
,W/jxcore-log( 5246): Initializing JXcore engine
,W/jxcore-log( 5246): JXcore engine is ready
,W/jxcore-log( 5246): Starting JXcore engine
,I/Icing   ( 1754): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,E/SMD     (  241): DCD ON
,W/jxcore-log( 5246): Platform android
W/jxcore-log( 5246): 
,W/jxcore-log( 5246): Process ARCH arm
W/jxcore-log( 5246): 
,I/Icing   ( 1754): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/jxcore-log( 5246): JXcore Cordova bridge is ready!
I/jxcore-log( 5246): 
,W/jxcore-log( 5246): JXcore engine is started
,I/chromium( 5246): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/AmoledAdjustTimer(  770): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 5246): Toggling radios to true
I/jxcore-log( 5246): 
,I/GAV2    ( 5234): Thread[GAThread,5,main]: No campaign data found.
,D/BluetoothAdapter( 5246): enable(): BT is already enabled..!
,I/WifiManager( 5246): packageName : com.test.thalitest
I/WifiManager( 5246): setWifiEnabled : true
,I/WifiService(  770): setWifiEnabled: true pid=5246, uid=10179
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5246, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  770): Failed getting userId using ActivityManagerNative
W/WifiService(  770): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5246, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  770): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  770): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  770): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  770): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  770): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  770): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  770): disconnect: pid=5246, uid=10179
,I/jxcore-log( 5246): Radios toggled
I/jxcore-log( 5246): 
,I/jxcore-log( 5246): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5246): 
I/wpa_supplicant( 1959): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5246): Perf Test app loaded loaded
I/jxcore-log( 5246): 
,I/jxcore-log( 5246): check test folder
I/jxcore-log( 5246): 
,I/jxcore-log( 5246): found test : ./testFindPeers.js
I/jxcore-log( 5246): 
,I/wpa_supplicant( 1959): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1959): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): InitialState.processMessage what=4
,E/Tethering(  770): No numeric data
,I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  770): sendTetherStateChangedBroadcast 0, 0, 0
E/wpa_supplicant( 1959): Cmd 35605 not handled
,E/wpa_supplicant( 1959): Cmd 35605 not handled
,I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
I/wpa_supplicant( 1959): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
V/NetworkStats(  770): performPollLocked(flags=0x1)
,I/wpa_supplicant( 1959): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1959): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 1959): First Scan Start
,I/wpa_supplicant( 1959): Scan requested (ret=0) - scan timeout 30 seconds
,I/jxcore-log( 5246): found test : ./testSendData.js
I/jxcore-log( 5246): 
,W/Settings(  770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  770): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService(  770): InactiveState{ what=143375 }
D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/CommandListener(  238): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,V/NetworkStats(  770): performPollLocked() took 49ms
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
D/ConnectivityService(  770): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  770): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  770): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  770): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1065): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
I/wpa_supplicant( 1959): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1959): Skip scan - already scanning
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/ConnectivityService(  770): Attempting to switch to mobile
D/ConnectivityService(  770): Attempting to switch to BLUETOOTH_TETHER
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1065): checkOverflow(336), More:false, Req:false Child:2
,D/WifiP2pService(  770): InactiveState{ what=143375 }
,I/SELinux ( 5407): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5407):  
D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,V/RouteController(  238): /system/bin/ip -6 route del default table 2 2>&1
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip -6 rule del table 2 2>&1
,I/SELinux ( 5407): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5407):  
I/SELinux ( 5407):  
,I/SELinux ( 5407): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5407): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5407): >>>>> Normal User
,E/dalvikvm( 5407): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5407): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
,E/SMD     (  241): DCD ON
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
E/WifiStateMachine(  770): Error! unhandled message{ when=-110ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  770): Error! unhandled message{ when=-110ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  770): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
W/NetworkManagementService(  770): route cmd failed: 
W/NetworkManagementService(  770): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 route del src v6 2' failed with '400 38 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  770): '
W/NetworkManagementService(  770): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  770): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  770): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  770): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  770): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  770): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  770): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  770): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  770): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  770): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  770): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  770): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  770): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/RouteController(  238): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 5407): in addTimaSignatureService
,V/RouteController(  238): RTNETLINK answers: No such process
,D/TimaKeyStoreProvider( 5407): Cannot add TimaSignature Service, License check Failed
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,D/ActivityThread( 5407): Added TimaKesytore provider
,I/Choreographer( 5246): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5246): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  770): android_net_utils_resetConnections in env=0x748121d8 clazz=0x6a800001 iface=wlan0 mask=0x3
D/ConnectivityService(  770): resetConnections(wlan0, 3)
,V/NativeCrypto( 1304): Read error: ssl=0x7bfdb0d0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1304): SSL shutdown failed: ssl=0x7bfdb0d0: I/O error during system call, Broken pipe
,I/System.out( 5407): Inside WakeupProvider
,I/System.out( 5407): Inside onCreate() of WakeupTriggerProvide
,V/NetworkStats(  770): updateIfacesLocked()
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked(flags=0x1)
D/ConnectivityService(  770): handleInetConditionChange: no active default network - ignore
V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 28ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/dalvikvm(  770): GC_EXPLICIT freed 2518K, 57% free 23922K/54872K, paused 7ms+15ms, total 160ms
,V/AlarmManager(  770): waitForAlarm result :4
,V/AlarmManager(  770): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/VlingoApplication( 5407): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
D/VlingoApplication( 5407): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5407): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  770): mCoverManager.getCoverState() : true
V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(336), More:false, Req:false Child:2
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1310): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1310): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5407): initQueue()
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1310): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1310): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  770): Killing 4424:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 67447 latestRequest time : 1450312705331 current time : 1450312772778
,I/ApplicationPolicy(  770): updateDataUsageMap
,D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  770): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  770): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1444): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_PushUtil( 5130): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5130): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5130): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5130): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5130): noConnectivity : true
D/LocSvc_java(  770): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/FactoryTest( 4731): Not factory mode
D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
,D/FactoryTest( 4731): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4731): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4731): still no open session command from host, so toast
W/ContextImpl( 4731): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4731): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  770): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  770): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  770): mDVFSHelper.acquire()
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/LockPatternUtils( 1065): isPcwEnable = null
,E/MTPRx   ( 4731): started activity for popup
I/SQLiteSecureOpenHelper( 2067): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2067): getDatabaseLocked(b,b,pwd)...
,I/SELinux ( 5445): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5445):  
,E/SettingsReceiverActivity( 4731): PREF_DONT_ASK_AGAIN : false
,I/SELinux ( 5445): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5445):  
I/SELinux ( 5445):  
,I/SELinux ( 5445): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5445): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5445): >>>>> Normal User
,E/dalvikvm( 5445): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5445): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/SettingsReceiverActivity( 4731): dev.kiessupport is : TRUE
,D/TimaKeyStoreProvider( 5445): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5445): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5445): Added TimaKesytore provider
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5445, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  770): Killing 4439:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/wpa_supplicant( 1959): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 1959): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1959): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1959): Trying to associate with  'G700'
I/wpa_supplicant( 1959): Re-associate with C0.AA.48
,I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1959): Cmd 35609 not handled
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,I/SurfaceFlinger(  250): id=18 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4731): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4731): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4731): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4731): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4731): Remote Branch: 
I/Adreno-EGL( 4731): Local Patches: 
I/Adreno-EGL( 4731): Reconstruct Branch: 
,I/HWUI    ( 4731): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4731): Enabling debug mode 0
,E/wpa_supplicant( 1959): Cmd 35605 not handled
E/wpa_supplicant( 1959): Cmd 35847 not handled
E/wpa_supplicant( 1959): Cmd 35848 not handled
,E/wpa_supplicant( 1959): Cmd 35605 not handled
I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1959): Associated with C0.AA.48
,I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1959): freq(2412) increment count 2
,I/wpa_supplicant( 1959): meet head of list.
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
,E/Tethering(  770): No numeric data
,I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1959): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1959): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative(  770): callSECApiVoid - ID [50]
I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
,D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
I/SELinux ( 5466): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5466):  
D/Tethering(  770): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked(flags=0x1)
,D/dalvikvm(  251): GC_EXPLICIT freed 43K, 50% free 9514K/18708K, paused 2ms+3ms, total 26ms
,D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9514K/18708K, paused 1ms+2ms, total 20ms
,I/SELinux ( 5466): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5466):  
I/SELinux ( 5466):  
,I/SELinux ( 5466): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5466): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5466): >>>>> Normal User
,E/dalvikvm( 5466): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5466): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
,D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9514K/18708K, paused 1ms+3ms, total 21ms
,D/Tethering(  770): interfaceLinkStateChanged wlan0, true
D/Tethering(  770): interfaceStatusChanged wlan0, true
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 80ms
,D/TimaKeyStoreProvider( 5466): in addTimaSignatureService
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  770): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  770): mDVFSHelper.release()
D/CustomFrequencyManagerService(  770): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
D/TimaKeyStoreProvider( 5466): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5466): Added TimaKesytore provider
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5466, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  770): Killing 4467:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5480): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5480):  
,I/SELinux ( 5480): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5480):  
I/SELinux ( 5480):  
,I/SELinux ( 5480): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5480): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5480): >>>>> Normal User
,E/dalvikvm( 5480): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5480): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5480): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5480): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5480): Added TimaKesytore provider
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5480, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5480): KLMSValidator() : checkQATesting()
,I/dhcpcd  ( 5492): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5492): bssid match
,I/KLMS-2.3.201 : ( 5480): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450312773714
,I/KLMS-2.3.201 : ( 5480): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager(  770): Killing 4489:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5499): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5499):  
,I/SELinux ( 5499): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5499):  
I/SELinux ( 5499):  
,I/SELinux ( 5499): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5499): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5499): >>>>> Normal User
,E/dalvikvm( 5499): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5499): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5499): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5499): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5499): Added TimaKesytore provider
,D/SO_AGENT( 5499): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5499, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
I/SO_AGENT( 5499): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4042): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4042): [BDLM] already registered in spp
,I/SA      ( 4042): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4042): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4042): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4042): [OR] == isSIMCardReady false ==
I/SA      ( 4042): [SCU] == networkStateCheck == false
,I/SA      ( 4042): [OR] onReceive END
I/ActivityManager(  770): Killing 4607:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SELinux ( 5511): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5511):  
,I/SELinux ( 5511): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5511):  
I/SELinux ( 5511):  
,I/SELinux ( 5511): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5511): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5511): >>>>> Normal User
,E/dalvikvm( 5511): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5511): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5511): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5511): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5511): Added TimaKesytore provider
,I/sCloudBackupApp( 5511): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5511): Other Intent
,I/ActivityManager(  770): Killing 4654:com.sec.android.app.voicenote/1000 (adj 15): empty #43
D/com.samsung.app( 1444): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5531): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5531):  
,I/SELinux ( 5531): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5531):  
I/SELinux ( 5531):  
,I/SELinux ( 5531): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5531): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5531): >>>>> Normal User
,E/dalvikvm( 5531): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5531): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5531): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5531): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5531): Added TimaKesytore provider
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5531, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  770): Killing 4632:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/Headlines( 4096): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4096): getCountryCode(): countryCode = PL
,I/SELinux ( 5557): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5557):  
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4096): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4096): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4096): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5557): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5557):  
I/SELinux ( 5557):  
,I/SELinux ( 5557): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5557): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5557): >>>>> Normal User
,E/dalvikvm( 5557): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5557): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5557): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5557): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5557): Added TimaKesytore provider
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5557): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5557): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
D/CustomFrequencyManagerService(  770): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  tag : ACTIVITY_RESUME_BOOSTER@9
,W/GAV2    ( 5557): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5557): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5557): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  770): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  770): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  770): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
,D/WifiStateMachine(  770): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  770): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  770): mBoosterFLAG : 2
,I/WifiTrafficPoller(  770): current booster mode : BTCoexMode
D/ConnectivityService(  770): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  770): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  770): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1065): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/RouteController(  238): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,V/RouteController(  238): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,D/dalvikvm( 1304): GC_EXPLICIT freed 902K, 43% free 10802K/18708K, paused 3ms+5ms, total 47ms
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,V/RouteController(  238): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  238): RTNETLINK answers: No such process
,V/WebViewChromium( 5557): Binding Chromium to the main looper Looper (main, tid 1) {42275080}
,V/RouteController(  238): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,I/chromium( 5557): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5557): Initializing chromium process, renderers=0
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,W/chromium( 5557): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): updateIfacesLocked()
V/NetworkStats(  770): performPollLocked(flags=0x1)
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,I/Adreno-EGL( 5557): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5557): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5557): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5557): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5557): Remote Branch: 
I/Adreno-EGL( 5557): Local Patches: 
I/Adreno-EGL( 5557): Reconstruct Branch: 
V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 17ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,I/NSApplication( 5557): Starting up...
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5557, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3359): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  770): Killing 4687:com.google.android.talk/u0a105 (adj 15): empty #43
I/QuickConnect[1.1][2] ( 3359): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3359): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a73e8
,I/SELinux ( 5607): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5607):  
,I/SELinux ( 5607): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5607):  
I/SELinux ( 5607):  
,I/SELinux ( 5607): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5607): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5607): >>>>> Normal User
,E/dalvikvm( 5607): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5607): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5607): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5607): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5607): Added TimaKesytore provider
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
D/RCPManagerService(  770): exchangeData() failure , invalid userId
D/RCPManagerService(  770): exchangeData() failure , invalid userId
D/RCPManagerService(  770): exchangeData() failure , invalid userId
D/RCPManagerService(  770): exchangeData() failure , invalid userId
D/RCPManagerService(  770): exchangeData() failure , invalid userId
I/ActivityManager(  770): Killing 3033:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
I/SELinux ( 5626): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5626):  
I/SELinux ( 5630): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5630):  
W/ActivityManager(  770): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/SELinux ( 5626): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5626):  
I/SELinux ( 5626):  
I/SELinux ( 5626): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5626): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5626): >>>>> Normal User
E/dalvikvm( 5626): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
E/SELinux ( 5626): [DEBUG] seapp_context_lookup: seinfoCategory = shared
I/SELinux ( 5630): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5630):  
I/SELinux ( 5630):  
I/SELinux ( 5630): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5630): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5630): >>>>> Normal User
E/dalvikvm( 5630): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
D/TimaKeyStoreProvider( 5626): in addTimaSignatureService
E/SELinux ( 5630): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5626): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5626): Added TimaKesytore provider
D/TimaKeyStoreProvider( 5630): in addTimaSignatureService
D/TimaKeyStoreProvider( 5630): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5630): Added TimaKesytore provider
I/ActivityManager(  770): Killing 4760:com.sec.knox.bridge/1000 (adj 15): empty #43
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5626, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
D/hcjo    ( 4191): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4191): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4191): exit::IDLE
D/InitializeManagerStateMachine( 4191): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4191): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4191): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4191): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4191): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4191): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4191): entry::SUCCESS
D/hcjo    ( 4191): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4191): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4191): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4191): exit::SUCCESS
D/InitializeManagerStateMachine( 4191): entry::IDLE
I/ActivityManager(  770): Killing 4777:com.wssyncmldm/1000 (adj 15): empty #43
D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1310): MountReceiver.onReceive - Keep current state
D/BadgeProvider( 5630): onCreate
D/BadgeProvider( 5630): DatabaseHelper
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5630, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
D/Tethering(  770): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  770): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
D/LocSvc_java(  770): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
D/accuweather( 1444): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/BadgeProvider( 5630): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=true
I/NearbySettings( 1310): MountReceiver.onReceive - Keep current state
D/BadgeProvider( 5630): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5630): sendNotify, [notify] : null
D/BadgeProvider( 5630): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5630): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5630): update, [UpdateCount] : 1
D/Launcher.Model( 1250): reloadBadges entered.
D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1310): MountReceiver.onReceive - Keep current state
D/Toast   ( 1310):  checkMirrorLinkEnabled returns : false
D/Toast   ( 1310): showing allowed
D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1310): MountReceiver.onReceive - Keep current state
I/PCWCLIENTTRACE_PushUtil( 5130): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5130): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5130): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5130): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
E/SMD     (  241): DCD ON
I/SurfaceFlinger(  250): id=19 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  770): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/VacuumService( 1209): Vacuum at: now=1450312775403 tag=VacuumService
I/KLMS-2.3.201 : ( 5480): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.3.201 : ( 5480): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450312775467
I/KLMS-2.3.201 : ( 5480): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
I/LocationTagReadyService( 2561): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 2561): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2561): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2561): [Slink platform] The state of Slink geocode service is true
D/SO_AGENT( 5499): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/SO_AGENT( 5499): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
I/GallerySearchProvider( 2347): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
I/SELinux ( 5657): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5657):  
,I/SELinux ( 5661): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5661):  
,I/SELinux ( 5657): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5657):  
I/SELinux ( 5657):  
,I/SELinux ( 5657): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5657): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5657): >>>>> Normal User
,E/dalvikvm( 5657): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5657): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5657): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5657): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5657): Added TimaKesytore provider
I/SELinux ( 5661): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5661):  
I/SELinux ( 5661):  
,I/SELinux ( 5661): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5661): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5661): >>>>> Normal User
,E/dalvikvm( 5661): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5661): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5661): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5661): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5661): Added TimaKesytore provider
,I/SA      ( 4042): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4042): [BDLM] already registered in spp
I/SA      ( 4042): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4042): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4042): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4042): [OR] == isSIMCardReady false ==
I/SA      ( 4042): [SCU] == networkStateCheck == true
I/SA      ( 4042): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4042): isChinaCountryCode : false
I/SA      ( 4042): [OR] == networkStateCheck true ==
,I/SA      ( 4042): [OR] GetMyCountryZoneTask
,I/SA      ( 4042): [OR] onReceive END
,I/SA      ( 4042): [SRS] prepareGetMyCountryZone
,I/SA      ( 4042): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4042): [SSP] query invoked
,I/SA      ( 4042): [TPMU] GetMccFromDB : null
I/SA      ( 4042): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4042): [TPM] isNoProxy(default) : true
D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SA      ( 4042): [RC New] Execute method=[GET] start
,I/SCloudBackupReceiver( 5511): Other Intent
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4096): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4096): getCountryCode(): countryCode = PL
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4096): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 4096): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4096): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3359): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3359): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3359): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a73e8
,V/KVNProvider( 5661): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5661): getFindoCursor query string : 
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,V/KVNProvider( 5661): getTagSearchCursor() tagSearchCursor count : 0
,D/dalvikvm(  770): GC_EXPLICIT freed 2393K, 57% free 23813K/54872K, paused 6ms+12ms, total 130ms
,D/hcjo    ( 4191): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4191): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4191): exit::IDLE
,D/InitializeManagerStateMachine( 4191): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4191): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4191): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4191): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4191): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4191): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4191): entry::SUCCESS
,D/hcjo    ( 4191): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4191): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4191): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4191): exit::SUCCESS
,D/InitializeManagerStateMachine( 4191): entry::IDLE
I/ActivityManager(  770): Killing 4628:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,I/SA      ( 4042): [RC New] [v2liruge] api execute + 639
,I/SA      ( 4042): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4042): AsyncTask #2 calls detatch()
,I/SA      ( 4042): [TPMU] getNetworkMcc : 
D/SSRMv2:SIOP(  770): SIOP:: AP = 320, Delta = 10
,I/SA      ( 4042): [SCU] saveMccToPreferece Start
,I/SA      ( 4042): [SCU] RegionMCC : 260
,I/SA      ( 4042): [SSP] query invoked
,I/SA      ( 4042): [TPMU] GetMccFromDB : null
I/SA      ( 4042): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4042): [SCU] saveMccToPreferece End
,I/SA      ( 4042): [RC New] executeRequest [v2liruge] end. 660
I/SA      ( 4042): [RC New] Execute end
,I/SA      ( 4042): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4042): [OR] GetMyCountryZoneTask Success
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1769977, pollInterval: 10000
,I/jxcore-log( 5246): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5246): 
,E/WifiStateMachine(  770): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/HarmonyEASService(  770): Updating for all 1
,E/SMD     (  241): DCD ON
,I/ActivityManager(  770): Killing 4219:com.android.calendar/u0a142 (adj 15): empty #43
,I/SurfaceFlinger(  250): id=19 Removed Uoast (12/13)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  770): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770 (0x0)
,D/PowerManagerService(  770): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=770, ws=WorkSource{1000}) (elapsedTime=3520)
,I/GAV2    ( 5557): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5130): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5130): [hasSamungAccount] - No Samsung Account
,W/WifiP2pStateTracker(  770): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  770): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  770):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  770): updateSourceRoutes : no source routing conditions
,W/linker  ( 5130): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5130): ================================================
,I/CSTORAGE( 5130):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5130): ================================================
,D/dalvikvm( 5130): No JNI_OnLoad found in /system/lib/libterrier.so 0x425a14f8, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5130): [GetString-S]
,I/terrier ( 5130): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5130): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5130): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5130): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5130): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5130): QSEECom_shutdown_app, app_id = 3
,E/terrier ( 5130): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5130): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5130): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5130): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5130): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5130): [ensureRegistration] - No Samsung account
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager(  770): waitForAlarm result :4
,V/AlarmManager(  770): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3687): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PreloadUpdateManagerStateMachine( 4191): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4191): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4191): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4191): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4191): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4191): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4191): entry::IDLE
,D/CaptivePortalTracker(  770): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  770): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  770): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  770): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  770): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  770): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4191): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4191): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4191): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4191): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4191): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4191): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4191): entry::IDLE
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = -20
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1759972, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 75s ago
,D/AmoledAdjustTimer(  770): prevTemp = 290, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 19695 latestRequest time : 1450312775683 current time : 1450312795378
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1749970, pollInterval: 10000
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 293, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1739966, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 291, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1729959, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 5
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 105s ago
,D/AmoledAdjustTimer(  770): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1719954, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :4
,V/AlarmManager(  770): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 57137 latestRequest time : 1450312775683 current time : 1450312832821
,I/PhenotypeConfigurator( 1209): Scheduling Phenotype for one-off execution 8589 seconds from now (1450312833597)
,D/GetConfigurationSnapshotOperation( 1209): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1209): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1209): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1209): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1209): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1209): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1209): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1209): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1209): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  770): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1209): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1209): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1209): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1209): Thread-107(HTTPLog):isShipBuild true
,I/System.out( 1209): Thread-107(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1209): GC_CONCURRENT freed 1589K, 37% free 11879K/18708K, paused 9ms+9ms, total 86ms
,D/LocationManagerService(  770): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1709948, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 288, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1699941, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 6
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 79688 latestRequest time : 1450312775683 current time : 1450312855371
,I/PowerManagerService(  770): [PWL] Off : 140s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1689928, pollInterval: 10000
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1679920, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1669909, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 7
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  770): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 109690 latestRequest time : 1450312775683 current time : 1450312885373
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1659892, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1649881, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1639874, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 8
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 139687 latestRequest time : 1450312775683 current time : 1450312915370
,D/Headlines( 4096): stop 
,D/Headlines( 4096): Breath.onDestroy : 
,I/ActivityManager(  770): Killing 4410:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1629860, pollInterval: 10000
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1936): Disconnected process message: 10
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1619852, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1609841, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 9
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  770): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1599825, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1589816, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  770): initializing...
,I/TLC_TIMA_PKM_initialize(  770): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  770): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  770): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  770): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  770): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  770): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  770): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  770): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  770): App is not loaded in QSEE
,D/QSEECOMAPI: (  770): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  770): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  770): Trustlet response is completed
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 5246): Connected to the server!
I/jxcore-log( 5246): 
,I/chromium( 5246): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1579809, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  770): !@Sync 10
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/jxcore-log( 5246): --- start :testFindPeers.js---
I/jxcore-log( 5246): 
,I/jxcore-log( 5246): testFindPeers created [object Object]
I/jxcore-log( 5246): 
,I/jxcore-log( 5246): serverPort is 8876
I/jxcore-log( 5246): 
,I/dalvikvm( 5246): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5246): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x0019
,I/dalvikvm( 5246): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5246): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5246): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 5246): Shutting down VM
,W/dalvikvm( 5246): threadid=1: thread exiting with uncaught exception (group=0x4182dda0)
,E/AndroidRuntime( 5246): FATAL EXCEPTION: main
E/AndroidRuntime( 5246): Process: com.test.thalitest, PID: 5246
E/AndroidRuntime( 5246): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 5246): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 5246): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 5246): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 5246): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 5246): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 5246): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 5246): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 5246): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 5246): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 5246): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5246): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5246): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5246): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 5246): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5246): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5246): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 5246): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 5246): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 5246): Sending signal. PID: 5246 SIG: 9
,D/CrashAnrDetector(  770): processName: com.test.thalitest
,D/CrashAnrDetector(  770): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 ,
,I/ActivityManager(  770): Process com.test.thalitest (pid 5246) (adj 1) has died.
,I/WindowState(  770): WIN DEATH: Window{4378db98 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  250): id=17 Removed NainActivit (7/12)
,I/SurfaceFlinger(  250): id=17 Removed NainActivit (-2/12)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,I/SELinux ( 5785): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5785):  
,D/dalvikvm(  251): GC_EXPLICIT freed 43K, 50% free 9514K/18708K, paused 7ms+4ms, total 92ms
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1569486, pollInterval: 10000
,D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9514K/18708K, paused 3ms+4ms, total 43ms
,I/SELinux ( 5785): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5785):  
I/SELinux ( 5785):  
,I/SELinux ( 5785): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5785): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5785): >>>>> Normal User
,E/dalvikvm( 5785): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
,E/SELinux ( 5785): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9514K/18708K, paused 3ms+5ms, total 32ms
,D/TimaKeyStoreProvider( 5785): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5785): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5785): Added TimaKesytore provider
,D/InputDispatcher(  770): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  250): id=20 createSurf (720x1280),2 flag=404, TcreenshotS
,D/PermissionCache(  250): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (241 us)
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5785, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5785, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,V/WebViewChromium( 5785): Binding Chromium to the background looper Looper (main, tid 1) {4227b058}
,I/chromium( 5785): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5785): Initializing chromium process, renderers=0
,W/chromium( 5785): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5785): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5785): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5785): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5785): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5785): Remote Branch: 
I/Adreno-EGL( 5785): Local Patches: 
I/Adreno-EGL( 5785): Reconstruct Branch: 
,I/dalvikvm( 5785): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 5785): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5785): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5785): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5785): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5785): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5785): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 5785): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5785): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5785): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5785): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5785): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,I/dalvikvm( 5785): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5785): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 5785): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5785): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5785): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5785): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5785): CordovaWebView is running on device made by: samsung
,I/SurfaceFlinger(  250): id=21 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5785): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 5785): Enabling debug mode 0
,W/AwContents( 5785): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/WindowManager(  770): Screen frozen for +462ms due to Window{430124e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  250): id=22 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  250): id=23 createSurf (720x2560),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  250): id=24 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  250): id=25 createSurf (720x2560),-1 flag=20004, ClackSurfac
,D/InputDispatcher(  770): setInputDispatchMode: enabled=0, frozen=0
,I/SurfaceFlinger(  250): id=20 Removed TcreenshotS (12/17)
I/SurfaceFlinger(  250): id=22 Removed ClackSurfac (12/16)
,I/SurfaceFlinger(  250): id=20 Removed TcreenshotS (-2/16)
I/SurfaceFlinger(  250): id=23 Removed ClackSurfac (12/15)
,I/SurfaceFlinger(  250): id=22 Removed ClackSurfac (-2/15)
I/SurfaceFlinger(  250): id=24 Removed ClackSurfac (12/14)
I/SurfaceFlinger(  250): id=23 Removed ClackSurfac (-2/14)
,I/SurfaceFlinger(  250): id=25 Removed ClackSurfac (12/13)
,I/SurfaceFlinger(  250): id=24 Removed ClackSurfac (-2/13)
,I/SurfaceFlinger(  250): id=25 Removed ClackSurfac (-2/13)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
V/WindowManager(  770): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/JsMessageQueue( 5785): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 5785): Trying to load lib /data/app-lib/com.test.thalitest-56/libjxcore.so 0x425a1db8
,D/dalvikvm( 5785): Added shared lib /data/app-lib/com.test.thalitest-56/libjxcore.so 0x425a1db8
,D/jxcore_app_log( 5785): JniHelper::setJavaVM(0x4171e528), pthread_self() = 2033071648
,D/JX-Cordova( 5785): jxcore cordova android initializing
,D/dalvikvm( 5785): GC_CONCURRENT freed 4923K, 32% free 12772K/18708K, paused 3ms+4ms, total 50ms
,D/dalvikvm( 5785): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 5785): WAIT_FOR_CONCURRENT_GC blocked 28ms
,E/SMD     (  241): DCD ON
,D/dalvikvm( 5785): GC_FOR_ALLOC freed 4717K, 27% free 15745K/21496K, paused 41ms, total 42ms
,V/AlarmManager(  770): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm(  770): GC_EXPLICIT freed 2973K, 57% free 23810K/54872K, paused 5ms+25ms, total 207ms
,D/dalvikvm( 5785): GC_FOR_ALLOC freed 5089K, 31% free 16760K/24184K, paused 44ms, total 44ms
,I/dalvikvm-heap( 5785): Grow heap (frag case) to 21.715MB for 2475476-byte allocation
,D/dalvikvm( 5785): GC_FOR_ALLOC freed 3781K, 35% free 17443K/26604K, paused 31ms, total 32ms
,D/dalvikvm( 5785): GC_FOR_ALLOC freed 1238K, 35% free 17347K/26604K, paused 28ms, total 28ms
,W/jxcore-log( 5785): Initializing JXcore engine
,W/jxcore-log( 5785): JXcore engine is ready
,W/jxcore-log( 5785): Starting JXcore engine
,W/jxcore-log( 5785): Platform android
W/jxcore-log( 5785): 
,W/jxcore-log( 5785): Process ARCH arm
W/jxcore-log( 5785): 
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/jxcore-log( 5785): JXcore Cordova bridge is ready!
I/jxcore-log( 5785): 
,W/jxcore-log( 5785): JXcore engine is started
,I/chromium( 5785): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  241): DCD ON
,I/jxcore-log( 5785): Toggling radios to true
I/jxcore-log( 5785): 
,D/BluetoothAdapter( 5785): enable(): BT is already enabled..!
,I/WifiManager( 5785): packageName : com.test.thalitest
I/WifiManager( 5785): setWifiEnabled : true
,I/WifiService(  770): setWifiEnabled: true pid=5785, uid=10179
,W/WifiService(  770): Failed getting userId using ActivityManagerNative
W/WifiService(  770): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5785, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  770): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  770): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  770): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  770): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  770): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  770): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  770): disconnect: pid=5785, uid=10179
,I/wpa_supplicant( 1959): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5785, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/jxcore-log( 5785): Radios toggled
I/jxcore-log( 5785): 
I/jxcore-log( 5785): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5785): 
I/jxcore-log( 5785): Perf Test app loaded loaded
I/jxcore-log( 5785): 
I/jxcore-log( 5785): check test folder
I/jxcore-log( 5785): 
I/jxcore-log( 5785): found test : ./testFindPeers.js
I/jxcore-log( 5785): 
,I/wpa_supplicant( 1959): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1959): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1959): Cmd 35605 not handled
,E/wpa_supplicant( 1959): Cmd 35605 not handled
,I/wpa_supplicant( 1959): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): InitialState.processMessage what=4
E/Tethering(  770): No numeric data
,D/Tethering(  770): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  770): performPollLocked(flags=0x1)
I/wpa_supplicant( 1959): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1959): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1959): First Scan Start
I/wpa_supplicant( 1959): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
D/Tethering(  770): interfaceStatusChanged wlan0, false
W/Settings(  770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  770): ignore requestNetworkTransitionWakelock airplane:true
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
D/Tethering(  770): interfaceStatusChanged wlan0, false
I/jxcore-log( 5785): found test : ./testSendData.js
I/jxcore-log( 5785): 
,D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 38ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
D/ConnectivityService(  770): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  770): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  770): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  770): net.tcp.delack.default not found in system default properties
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1065): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/ConnectivityService(  770): Attempting to switch to mobile
D/ConnectivityService(  770): Attempting to switch to BLUETOOTH_TETHER
,I/wpa_supplicant( 1959): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1959): Skip scan - already scanning
D/STATUSBAR-IconMerger( 1065): checkOverflow(336), More:false, Req:false Child:2
V/RouteController(  238): /system/bin/ip -6 route del default table 2 2>&1
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1310): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1310): MountReceiver.mPrefHandler - 7002
,V/RouteController(  238): RTNETLINK answers: No such process
D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
V/RouteController(  238): /system/bin/ip -6 rule del table 2 2>&1
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,W/NetworkManagementService(  770): route cmd failed: 
W/NetworkManagementService(  770): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '61 route del src v6 2' failed with '400 61 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  770): '
W/NetworkManagementService(  770): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  770): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  770): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  770): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  770): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  770): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  770): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  770): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  770): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  770): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  770): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  770): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  770): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
V/RouteController(  238): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
,E/WifiStateMachine(  770): Error! unhandled message{ when=-78ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  770): Error! unhandled message{ when=-77ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  770): Error! unhandled message{ when=-10ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1310): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1310): MountReceiver.mPrefHandler - 7002
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  770): android_net_utils_resetConnections in env=0x748121d8 clazz=0xa5100001 iface=wlan0 mask=0x3
D/ConnectivityService(  770): resetConnections(wlan0, 3)
,I/chromium( 5785): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): updateIfacesLocked()
V/NetworkStats(  770): performPollLocked(flags=0x1)
V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,V/NetworkStats(  770): performPollLocked() took 15ms
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,I/ApplicationPolicy(  770): updateDataUsageMap
,D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  770): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  770): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/accuweather( 1444): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5130): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5130): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5130): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5130): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5130): noConnectivity : true
,D/LocSvc_java(  770): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
,I/wpa_supplicant( 1959): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1959): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1959): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1959): Trying to associate with  'G700'
I/wpa_supplicant( 1959): Re-associate with C0.AA.48
,I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,E/wpa_supplicant( 1959): Cmd 35609 not handled
,I/KLMS-2.3.201 : ( 5480): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/wpa_supplicant( 1959): Cmd 35605 not handled
I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1959): Associated with C0.AA.48
I/wpa_supplicant( 1959): freq(2412) increment count 3
I/wpa_supplicant( 1959): meet head of list.
,I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1959): Cmd 35847 not handled
E/wpa_supplicant( 1959): Cmd 35848 not handled
,E/wpa_supplicant( 1959): Cmd 35605 not handled
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1959): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1959): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
D/WifiNative(  770): callSECApiVoid - ID [50]
,D/Tethering(  770): interfaceStatusChanged wlan0, true
,E/Tethering(  770): No numeric data
,D/Tethering(  770): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  770): performPollLocked(flags=0x1)
,D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,I/KLMS-2.3.201 : ( 5480): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450312984927
,I/KLMS-2.3.201 : ( 5480): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/SO_AGENT( 5499): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5499): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 47ms
,I/SA      ( 4042): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4042): [BDLM] already registered in spp
I/SA      ( 4042): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4042): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4042): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4042): [OR] == isSIMCardReady false ==
I/SA      ( 4042): [SCU] == networkStateCheck == false
,I/SA      ( 4042): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5511): Other Intent
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4096): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4096): getCountryCode(): countryCode = PL
,D/Headlines( 4096): Breath.onCreate
,D/Headlines( 4096): Breath timer started. interval : 30000
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4096): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4096): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4096): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3359): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3359): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3359): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a73e8
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,I/iu.Environment( 1754): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1754): num queued entries: 0
,I/iu.UploadsManager( 1754): num updated entries: 0
,I/iu.SyncManager( 1754): NEXT; no task
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1310): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1310): MountReceiver.mPrefHandler - 7002
,I/dhcpcd  ( 5887): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5887): bssid match
,E/SMD     (  241): DCD ON
,D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/WifiStateMachine(  770): VerifyingLinkState enter
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  770): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  770): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
D/ConnectivityService(  770): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  770): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1065): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837979 act=2130837934
,D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837979 act=2130837934
,D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837979 act=2130837934
,D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  770): mBoosterFLAG : 2
,I/WifiTrafficPoller(  770): current booster mode : BTCoexMode
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  770): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  770): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  770): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1310): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1559435, pollInterval: 10000
,V/RouteController(  238): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1310): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
D/Toast   ( 1310):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1310): showing allowed
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,V/RouteController(  238): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/SurfaceFlinger(  250): id=26 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  770): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/NearbySettings( 1310): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,V/NetworkStats(  770): updateIfacesLocked()
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,V/NetworkStats(  770): performPollLocked(flags=0x1)
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 31ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  770): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  770): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/LocSvc_java(  770): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/accuweather( 1444): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
,I/jxcore-log( 5785): Connected to the server!
I/jxcore-log( 5785): 
,I/chromium( 5785): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5130): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5130): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5130): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5130): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SMD     (  241): DCD ON
,I/KLMS-2.3.201 : ( 5480): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/WifiP2pStateTracker(  770): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  770): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  770):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  770): updateSourceRoutes : no source routing conditions
,I/KLMS-2.3.201 : ( 5480): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450312988684
,I/KLMS-2.3.201 : ( 5480): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5499): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/LocationTagReadyService( 2561): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 5499): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 2561): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2561): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2561): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 2347): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,V/KVNProvider( 5661): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5661): getFindoCursor query string : 
,V/KVNProvider( 5661): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4042): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4042): [BDLM] already registered in spp
I/SA      ( 4042): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4042): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4042): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4042): [OR] == isSIMCardReady false ==
,I/SA      ( 4042): [SCU] == networkStateCheck == true
I/SA      ( 4042): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4042): isChinaCountryCode : false
I/SA      ( 4042): [OR] == networkStateCheck true ==
,I/SA      ( 4042): [OR] GetMyCountryZoneTask
I/SA      ( 4042): [OR] onReceive END
,I/SA      ( 4042): [SRS] prepareGetMyCountryZone
,I/SA      ( 4042): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4042): [SSP] query invoked
I/SA      ( 4042): [TPMU] GetMccFromDB : null
,I/SA      ( 4042): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4042): [TPM] isNoProxy(default) : true
,I/SA      ( 4042): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5511): Other Intent
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4096): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4096): getCountryCode(): countryCode = PL
D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4096): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4096): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4096): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3359): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3359): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3359): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a73e8
,I/jxcore-log( 5785): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5785): 
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4191): notifyNetworkActivated
,D/hcjo    ( 4191): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4191): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4191): exit::IDLE
,D/InitializeManagerStateMachine( 4191): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4191): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4191): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4191): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4191): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 4191): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4191): entry::SUCCESS
,D/hcjo    ( 4191): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4191): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4191): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4191): exit::SUCCESS
,D/InitializeManagerStateMachine( 4191): entry::IDLE
,I/iu.Environment( 1754): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1754): num queued entries: 0
,I/iu.UploadsManager( 1754): num updated entries: 0
,I/iu.SyncManager( 1754): NEXT; no task
,I/SA      ( 4042): [RC New] [v2liruge] api execute + 863
,I/SA      ( 4042): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4042): AsyncTask #3 calls detatch()
,I/SA      ( 4042): [TPMU] getNetworkMcc : 
,I/SA      ( 4042): [SCU] saveMccToPreferece Start
,I/SA      ( 4042): [SCU] RegionMCC : 260
,I/SA      ( 4042): [SSP] query invoked
,I/SA      ( 4042): [TPMU] GetMccFromDB : null
,I/SA      ( 4042): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4042): [SCU] saveMccToPreferece End
,I/SA      ( 4042): [RC New] executeRequest [v2liruge] end. 919
,I/SA      ( 4042): [RC New] Execute end
,I/SA      ( 4042): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4042): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService(  770): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  770): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/PowerManagerService(  770): [PWL] Off : 275s ago
,I/SurfaceFlinger(  250): id=26 Removed Uoast (12/13)
,I/SurfaceFlinger(  250): id=26 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  770): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770 (0x0)
,D/PowerManagerService(  770): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=770, ws=WorkSource{1000}) (elapsedTime=3527)
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :4
,V/AlarmManager(  770): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,I/SELinux ( 6008): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6008):  
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 283, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,I/SELinux ( 6008): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6008):  
I/SELinux ( 6008):  
,I/SELinux ( 6008): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6008): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 6008): >>>>> Normal User
,E/dalvikvm( 6008): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 6008): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6008): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6008): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6008): Added TimaKesytore provider
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6008, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 3661 latestRequest time : 1450312988861 current time : 1450312992522
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5130): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5130): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5130): [GetString-S]
,I/terrier ( 5130): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5130): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5130): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5130): Loaded image: APP id = 6
,D/QSEECOMAPI: ( 5130): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5130): QSEECom_shutdown_app, app_id = 6
,E/terrier ( 5130): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5130): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5130): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5130): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5130): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5130): [ensureRegistration] - No Samsung account
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1549412, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/CaptivePortalTracker(  770): DelayedCaptiveCheckState{ when=0 what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  770): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  770): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  770): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  770): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  770): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4191): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4191): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4191): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4191): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4191): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4191): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4191): entry::IDLE
,E/Watchdog(  770): !@Sync 11
,I/ActivityManager(  770): Waited long enough for: ServiceRecord{4373de88 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1539396, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  770): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 26189 latestRequest time : 1450312988861 current time : 1450313015051
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1529389, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/AmoledAdjustTimer(  770): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1519381, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 12
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1509375, pollInterval: 10000
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 56307 latestRequest time : 1450312988861 current time : 1450313045169
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1499369, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1489362, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 13
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1936): Disconnected process message: 10
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1479352, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 86189 latestRequest time : 1450312988861 current time : 1450313075050
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1469341, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1459336, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 14
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1449328, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  770): waitForAlarm result :8
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 116300 latestRequest time : 1450312988861 current time : 1450313105162
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 390s ago
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1439322, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1429316, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 15
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1419310, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  770): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 146189 latestRequest time : 1450312988861 current time : 1450313135050
,D/Headlines( 4096): stop 
,D/Headlines( 4096): Breath.onDestroy : 
,I/ActivityManager(  770): Killing 4589:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1409304, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1399297, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 16
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1389291, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  770): GC_CONCURRENT freed 3371K, 57% free 23923K/54872K, paused 22ms+46ms, total 561ms
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1379283, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 455s ago
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1369278, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 17
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1359272, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1349268, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1339262, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 18
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1329252, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1319246, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1309240, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 19
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 525s ago
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1299234, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1289230, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1279225, pollInterval: 10000
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 20
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1269219, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1259212, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1249206, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 21
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1239200, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 600s ago
,V/AlarmManager(  770): waitForAlarm result :8
,I/SensorManagerA(  770): getReportingMode :: sensor.mType = 5
,D/Sensors (  770): LightSensor setDelay = 200000000
,D/LightsService(  770): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  770): LightSensor setSensorDelay = 200000000
D/Sensors (  770): Light sensor flush: not enabled 0
D/Sensors (  770): LightSensor enable = 1
D/Sensors (  770): LightSensor enableSensor = 1
D/SensorManager(  770): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  770): LightSensor enable = 0
,D/Sensors (  770): LightSensor enableSensor = 0
,D/SensorManager(  770): unregisterListener ::   
D/LightsService(  770): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  770): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1229194, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1219188, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 22
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1209181, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  770): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  770): <AppSync3 Whitelist>
,V/AlarmManager(  770): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1199175, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1189169, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 23
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1179150, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4,
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1169145, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1159138, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 24
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  770): [PWL] Off : 680s ago
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1149131, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1139123, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1129117, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 25
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1119111, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  770): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1109103, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1099098, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 26
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1089091, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1079083, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1069077, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 27
,I/PowerManagerService(  770): [PWL] Off : 765s ago
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1059071, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1049063, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1039053, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 28
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1029046, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1019040, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1009035, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 29
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 999029, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 989022, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 979012, pollInterval: 10000
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 30
,I/PowerManagerService(  770): [PWL] Off : 855s ago
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 968996, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  770): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 958988, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 948972, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 31
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 938967, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 928961, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 918954, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 32
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 908948, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm(  770): GC_CONCURRENT freed 3546K, 57% free 23902K/54372K, paused 23ms+25ms, total 695ms
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 898943, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 888936, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 33
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,I/PowerManagerService(  770): [PWL] Off : 950s ago
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 878923, pollInterval: 10000
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 868912, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 858903, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 34
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 848898, pollInterval: 10000
,E/SMD     (  241): DCD ON
D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 838893, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 828886, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 35
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 818879, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 808869, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 798854, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 36
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  770): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 788841, pollInterval: 10000
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 1050s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 778834, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 768827, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 37
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 758820, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 748812, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 738804, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 38
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 728796, pollInterval: 10000
,E/SMD     (  241): DCD ON
V/AlarmManager(  770): waitForAlarm result :8
V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 718790, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 708781, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 39
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 698775, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  770): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 688769, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  770): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 678750, pollInterval: 10000
D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  770): !@Sync 40
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  770): [PWL] Off : 1155s ago
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 668729, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,E/SMD     (  241): DCD ON
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 658723, pollInterval: 10000
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :4
,V/AlarmManager(  770): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/ConnectivityService(  770): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 648714, pollInterval: 10000
,E/Watchdog(  770): !@Sync 41
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 638707, pollInterval: 10000
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,I/SensorManagerA(  770): getReportingMode :: sensor.mType = 5
,D/Sensors (  770): LightSensor setDelay = 200000000
,D/Sensors (  770): LightSensor setSensorDelay = 200000000
,D/Sensors (  770): Light sensor flush: not enabled 0
,D/Sensors (  770): LightSensor enable = 1
,D/LightsService(  770): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  770): LightSensor enableSensor = 1
D/SensorManager(  770): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  770): LightSensor enable = 0
,D/Sensors (  770): LightSensor enableSensor = 0
,D/LightsService(  770): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  770): unregisterListener ::   
D/LightsService(  770): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 628699, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 618693, pollInterval: 10000
,E/Watchdog(  770): !@Sync 42
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 608686, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  770): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  770): <AppSync3 Whitelist>
,V/AlarmManager(  770): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 598680, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 588672, pollInterval: 10000
,E/Watchdog(  770): !@Sync 43
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 578665, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 568654, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  770): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 558648, pollInterval: 10000
,E/Watchdog(  770): !@Sync 44
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 548642, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 538633, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 528625, pollInterval: 10000
,E/Watchdog(  770): !@Sync 45
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 518619, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 508613, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 498600, pollInterval: 10000
,E/Watchdog(  770): !@Sync 46
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 488583, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 478567, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 468552, pollInterval: 10000
,E/Watchdog(  770): !@Sync 47
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 458536, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 1380s ago
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 448521, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 438507, pollInterval: 10000
,E/Watchdog(  770): !@Sync 48
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,D/dalvikvm(  770): GC_CONCURRENT freed 3521K, 57% free 23897K/54372K, paused 23ms+47ms, total 545ms
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 428492, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 418476, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 408461, pollInterval: 10000
,E/Watchdog(  770): !@Sync 49
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 398445, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 388428, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 378410, pollInterval: 10000
,E/Watchdog(  770): !@Sync 50
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 368394, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 358378, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 348362, pollInterval: 10000
,E/Watchdog(  770): !@Sync 51
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 338347, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 1500s ago
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 328340, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 318333, pollInterval: 10000
,E/Watchdog(  770): !@Sync 52
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 308325, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 298319, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 288311, pollInterval: 10000
,E/Watchdog(  770): !@Sync 53
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 278305, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 268298, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 258292, pollInterval: 10000
,E/Watchdog(  770): !@Sync 54
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 248286, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 238280, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 228273, pollInterval: 10000
,E/Watchdog(  770): !@Sync 55
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 218267, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 208255, pollInterval: 10000
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 1625s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 198250, pollInterval: 10000
,E/Watchdog(  770): !@Sync 56
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 188244, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 178239, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 168234, pollInterval: 10000
,E/Watchdog(  770): !@Sync 57
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 158229, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 148223, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 138218, pollInterval: 10000
,E/Watchdog(  770): !@Sync 58
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 128211, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 118206, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 108200, pollInterval: 10000
,E/Watchdog(  770): !@Sync 59
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 98194, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 88188, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,W/ProcessCpuTracker(  770): Skipping unknown process pid 6333
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 78179, pollInterval: 10000
,E/Watchdog(  770): !@Sync 60
,I/PowerManagerService(  770): [PWL] Off : 1755s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 68173, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  770): Prepared write state in 140ms
,I/ProcessStatsService(  770): Prepared write state in 120ms
,I/ProcessStatsService(  770): Pruning old procstats: /data/system/procstats/state-2015-12-16-12-10-10.bin
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 58168, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 48161, pollInterval: 10000
,E/Watchdog(  770): !@Sync 61
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 38153, pollInterval: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 28146, pollInterval: 10000
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 18139, pollInterval: 10000
,E/Watchdog(  770): !@Sync 62
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 8131, pollInterval: 10000
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  770): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  770): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  770): (AppSync) ### 0 added ###
,I/ActivityManager(  770): Killing 4551:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1826s
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  241): DCD ON
D/UiModeManager(  770): mCoverManager.getCoverState() : true
D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/dalvikvm(  770): GC_CONCURRENT freed 3497K, 57% free 23914K/54372K, paused 24ms+46ms, total 546ms
,E/SMD     (  241): DCD ON
,D/Finsky  ( 3687): [1] ExperimentsChangeHandler$2.run: Exiting process because of stale process stable experiments
,I/AndroidRuntime( 3687): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager(  770): Process com.android.vending (pid 3687) (adj 15) has died.
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  770): !@Sync 63
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1936): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  241): DCD ON
E/Watchdog(  770): !@Sync 64
E/SMD     (  241): DCD ON
D/AndroidRuntime( 6361): 
D/AndroidRuntime( 6361): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6361): CheckJNI is OFF
D/AndroidRuntime( 6361): setted country_code = Poland
D/AndroidRuntime( 6361): setted countryiso_code = PL
D/AndroidRuntime( 6361): setted sales_code = XEO
D/AndroidRuntime( 6361): readGMSProperty: start
D/AndroidRuntime( 6361): readGMSProperty: already setted!!
D/AndroidRuntime( 6361): readGMSProperty: end
D/AndroidRuntime( 6361): addProductProperty: start
D/dalvikvm( 6361): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6361): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6361): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6361): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6361): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6361): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6361): failed to load memtrack module: -2
D/dalvikvm( 6361): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6361): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  770): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  770): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  770): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  770): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  770): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  770): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  770): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  770): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  770): getApplicationUninstallationEnabled
D/PackageManager(  770): START PACKAGE DELETE: observer{1125766632}
D/PackageManager(  770): pkg{<packageName>}
D/PackageManager(  770): user{0}
D/PackageManager(  770): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  770): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy(  770): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  770): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  770): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  770): Killing 5785:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/ActivityManager(  770): Killing 5630:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1817s
I/ActivityManager(  770): Killing 5360:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1824s
I/ActivityManager(  770): Killing 5348:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1824s
I/ActivityManager(  770): Killing 5334:com.samsung.helphub/1000 (adj 15): empty for 1824s
I/ActivityManager(  770): Killing 5321:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1825s
I/ActivityManager(  770): Killing 5305:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1825s
I/ActivityManager(  770): Killing 5234:com.google.android.apps.docs/u0a90 (adj 15): empty for 1825s
I/ActivityManager(  770): Killing 5219:com.sec.android.service.cm/u0a78 (adj 15): empty for 1826s
I/ActivityManager(  770): Killing 4671:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1826s
I/ActivityManager(  770): Killing 4324:com.android.mms/u0a48 (adj 15): empty for 1826s
I/ActivityManager(  770): Killing 5184:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1826s
I/ActivityManager(  770): Killing 4235:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1827s
I/ActivityManager(  770): Killing 5142:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1827s
I/ActivityManager(  770): Killing 5114:com.android.musicfx/u0a24 (adj 15): empty for 1827s
I/ActivityManager(  770): Killing 5100:com.samsung.groupcast/u0a15 (adj 15): empty for 1827s
I/ActivityManager(  770): Killing 5085:com.google.android.partnersetup/u0a14 (adj 15): empty for 1827s
I/ActivityManager(  770): Killing 5073:com.sec.android.inputmethod/1000 (adj 15): empty for 1828s
I/ActivityManager(  770): Killing 5000:com.android.defcontainer/u0a6 (adj 15): empty for 1828s
I/SurfaceFlinger(  250): id=21 Removed NainActivit (7/12)
I/SurfaceFlinger(  250): id=21 Removed NainActivit (-2/12)
I/SurfaceFlinger(  250): id=21 Removed NainActivit (-2/12)
I/WindowState(  770): WIN DEATH: Window{430124e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CountryDetector(  770): No listener is left
W/PackageSettings(  770): Skipping PackageSetting{42c9de88 com.example.hello/10181} due to missing metadata
D/PackageManager(  770): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1065): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3359): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/PackageManager(  770): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "sms"
W/GeofencerStateMachine( 1209): Ignoring removeGeofence because network location is disabled.
I/InputReader(  770): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6387): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6387):  
D/dalvikvm( 2173): GC_EXPLICIT freed 540K, 40% free 11227K/18708K, paused 5ms+7ms, total 50ms
I/FPMS_FingerprintManagerService( 1084): onReceive: android.intent.action.PACKAGE_REMOVED
D/RCPManagerService(  770): PackageReceiver onReceive()
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "smsto"
I/HarmonyEASService(  770): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 1406): GC_EXPLICIT freed 4306K, 47% free 10036K/18708K, paused 3ms+13ms, total 82ms
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  770):   Scheme: "mms"
I/SELinux ( 6387): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6387):  
I/SELinux ( 6387):  
I/SELinux ( 6387): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6387): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6387): >>>>> Normal User
E/dalvikvm( 6387): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6387): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6387): in addTimaSignatureService
D/dalvikvm( 1754): GC_EXPLICIT freed 1588K, 35% free 12205K/18708K, paused 5ms+8ms, total 132ms
D/TimaKeyStoreProvider( 6387): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6387): Added TimaKesytore provider
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "mmsto"
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "sms"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SurfaceFlinger(  250): id=27 createSurf (1x1),2 flag=404, CatteryCove
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "smsto"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "mms"
D/EnterpriseDeviceManagerService(  770): Package has changed for user 0
D/EnterpriseDeviceManagerService(  770): Admin package name: com.google.android.gms
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "mmsto"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6387, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 6387): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6387): ELMEngine.ELMEngine( context ).
D/elm:14132( 6387): MDMBridge.setEnterpriseBridge()
D/elm:14132( 6387): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6387): ElmAgentService : onCreate()
D/BackupManagerService(  770): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/BackupManagerService(  770): removePackageParticipantsLocked: uid=10179 #1
D/elm:14132( 6387): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6387): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6387): MDMBridge.getInstance()
D/elm:14132( 6387): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6387): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 6403): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6403):  
D/elm:14132( 6387): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 6387): ElmAgentService : onDestroy().
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6403): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6403):  
I/SELinux ( 6403):  
I/SELinux ( 6403): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6403): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6403): >>>>> Normal User
E/dalvikvm( 6403): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6403): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 6403): in addTimaSignatureService
D/TimaKeyStoreProvider( 6403): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6403): Added TimaKesytore provider
D/dalvikvm(  770): GC_EXPLICIT freed 2436K, 56% free 24037K/54372K, paused 6ms+16ms, total 238ms
D/dalvikvm(  770): WAIT_FOR_CONCURRENT_GC blocked 64ms
D/PackageManager(  770): delete sourFile : 
D/PackageManager(  770): delete native library directory: 
D/PackageManager(  770): return delete result to caller: 1125766632
D/AndroidRuntime( 6361): Shutting down VM
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  770): returnCode: 1
D/dalvikvm( 6361): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "sms"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "smsto"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "mms"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "mmsto"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  770): GC_EXPLICIT freed 742K, 57% free 23679K/54372K, paused 6ms+14ms, total 158ms
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6403, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 6403): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4259aa60, skipping init
I/SecureStorage( 6403): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6403): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6403
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6403): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher( 1250): onRestart, Launcher: 1113852168
D/Launcher( 1250): onStart, Launcher: 1113852168
D/Launcher.HomeView( 1250): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1444): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1444): [237392/5] SurfaceWidget drawing first frame
I/SecureStorage( 6403): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6403
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
I/SurfaceFlinger(  250): id=28 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  770): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  770): clearDefaults: com.test.thalitest
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/InputReader(  770): Processing first event
W/ApplicationsProvider( 1406): Could not fetch usage stats
W/ApplicationsProvider( 1406): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1406): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1406): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1406): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1406): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1406): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1406): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1406): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1406): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1406): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1406): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1406): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
D/BatteryService(  770): stay LED for fully charged
D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  770): mCoverManager.getCoverState() : true
V/HeadsetService( 1936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1936): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2

```
