#### Test 50650278e989a4f_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
I/PowerManagerService(  750): [PWL] Off : 50s ago
--------- beginning of /dev/log/main
I/SELinux ( 5172): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5172):  
,I/ActivityManager(  750): Killing 3975:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  247): GC_EXPLICIT freed 45K, 50% free 9507K/18800K, paused 2ms+2ms, total 35ms
I/SELinux ( 5172): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5172):  
I/SELinux ( 5172):  
I/SELinux ( 5172): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5172): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5172): >>>>> Normal User
E/dalvikvm( 5172): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5172): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/18800K, paused 1ms+3ms, total 25ms
D/TimaKeyStoreProvider( 5172): in addTimaSignatureService
D/TimaKeyStoreProvider( 5172): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5172): Added TimaKesytore provider
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/18800K, paused 2ms+2ms, total 25ms
D/SSRMv2:SIOP(  750): SIOP:: AP = 310, Delta = 0
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5172, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5172): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5172): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  750): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
I/SA      ( 4056): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4056): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4056): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4340): loadAuthorityPref(): sEnableAuthority = true
D/AndroidRuntime( 5190): 
D/AndroidRuntime( 5190): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5190): CheckJNI is OFF
D/AndroidRuntime( 5190): setted country_code = Poland
D/AndroidRuntime( 5190): setted countryiso_code = PL
D/AndroidRuntime( 5190): setted sales_code = XEO
D/AndroidRuntime( 5190): readGMSProperty: start
D/AndroidRuntime( 5190): readGMSProperty: already setted!!
D/AndroidRuntime( 5190): readGMSProperty: end
D/AndroidRuntime( 5190): addProductProperty: start
D/dalvikvm( 5190): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5190): Added shared lib libjavacore.so 0x0
I/IcingCorporaProvider( 2170): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/dalvikvm( 5190): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5190): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5190): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ContextImpl( 4693): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5213): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5213):  
I/SELinux ( 5213): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5213):  
I/SELinux ( 5213):  
I/SELinux ( 5213): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5213): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5213): >>>>> Normal User
E/dalvikvm( 5213): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5213): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5213): in addTimaSignatureService
D/TimaKeyStoreProvider( 5213): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5213): Added TimaKesytore provider
I/IcingCorporaProvider( 2170): UpdateCorporaTask done [took 132 ms] updated apps [took 132 ms] 
I/ActivityManager(  750): Killing 3987:com.samsung.klmsagent/u0a18 (adj 15): empty #43
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5213, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 5213): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
E/memtrack( 5190): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5190): failed to load memtrack module: -2
I/SELinux ( 5227): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5227):  
I/ActivityManager(  750): Killing 4271:com.sec.android.service.health/u0a16 (adj 15): empty #43
D/dalvikvm( 5190): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 5227): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5227):  
I/SELinux ( 5227):  
I/SELinux ( 5227): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5227): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5227): >>>>> Normal User
E/dalvikvm( 5227): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5227): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5227): in addTimaSignatureService
D/TimaKeyStoreProvider( 5227): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5227): Added TimaKesytore provider
D/AndroidRuntime( 5190): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy(  750): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  750): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 750  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  750): mDVFSHelper.acquire()
I/SELinux ( 5241): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5241):  
D/LockPatternUtils( 1063): isPcwEnable = null
D/AndroidRuntime( 5190): Shutting down VM
D/dalvikvm( 5190): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 5241): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5241):  
I/SELinux ( 5241):  
I/SELinux ( 5241): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5241): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5241): >>>>> Normal User
E/dalvikvm( 5241): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5241): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5241): in addTimaSignatureService
D/TimaKeyStoreProvider( 5241): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5241): Added TimaKesytore provider
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1440): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtils( 1063): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2093): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2093): getDatabaseLocked(b,b,pwd)...
D/SurfaceWidgetView( 1241): destroyHardwareResources():1125994584
I/SurfaceFlinger(  246): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  246): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5227, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
I/SurfaceFlinger(  246): id=8 Removed Mauncher (7/11)
I/SurfaceFlinger(  246): id=8 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/Launcher( 1241): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1241): destroyHardwareResources():1125994584
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5241, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5241, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5241): Binding Chromium to the background looper Looper (main, tid 1) {422a61d8}
I/chromium( 5241): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5241): Initializing chromium process, renderers=0
W/chromium( 5241): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5241): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5241): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5241): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5241): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5241): Remote Branch: 
I/Adreno-EGL( 5241): Local Patches: 
I/Adreno-EGL( 5241): Reconstruct Branch: 
,I/dalvikvm( 5241): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5241): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5241): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5241): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5241): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5241): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5241): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5241): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5241): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5241): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5241): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5241): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5241): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5241): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5241): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5241): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5241): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5241): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5241): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger(  246): id=18 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5241): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 5241): Enabling debug mode 0
W/AwContents( 5241): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  750): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 750  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  750): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  750): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 750  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 5284): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5284):  
I/ActivityManager(  750): Killing 4000:com.sec.android.soagent/u0a37 (adj 15): empty #43
W/GAV2    ( 5227): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5284): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5284):  
I/SELinux ( 5284):  
I/SELinux ( 5284): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5284): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5284): >>>>> Normal User
E/dalvikvm( 5284): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5284): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5284): in addTimaSignatureService
D/TimaKeyStoreProvider( 5284): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5284): Added TimaKesytore provider
D/PackageIntentReceiver( 5284): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5284): Not GearManger package! 
I/SELinux ( 5304): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5304):  
E/SMD     (  240): DCD ON
D/JsMessageQueue( 5241): Set native->JS mode to OnlineEventsBridgeMode
I/SELinux ( 5304): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5304):  
I/SELinux ( 5304):  
I/SELinux ( 5304): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5304): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5304): >>>>> Normal User
E/dalvikvm( 5304): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5304): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5304): in addTimaSignatureService
D/TimaKeyStoreProvider( 5304): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5304): Added TimaKesytore provider
D/MagazineService Version( 5304): Magazine-Channel: 13
D/MagazineService Version( 5304): Magazine-Provider: 13
D/MagazineService Version( 5304): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5304): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5304): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5304, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5304): [onHandleIntent] ACTION_PACKAGE_INSTALLED
D/dalvikvm( 5241): Trying to load lib /data/app-lib/com.test.thalitest-50/libjxcore.so 0x425ccf10
I/SELinux ( 5317): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5317):  
D/MagazineService::MagazineService( 5304): [onHandleIntent] Send broadcast to (com.test.thalitest).
D/dalvikvm( 5241): Added shared lib /data/app-lib/com.test.thalitest-50/libjxcore.so 0x425ccf10
D/jxcore_app_log( 5241): JniHelper::setJavaVM(0x4173a528), pthread_self() = 1943417152
D/JX-Cordova( 5241): jxcore cordova android initializing
I/ActivityManager(  750): Killing 1332:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 5317): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5317):  
I/SELinux ( 5317):  
I/SELinux ( 5317): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5317): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5317): >>>>> Normal User
E/dalvikvm( 5317): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5317): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/GAV2    ( 5227): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  750): Killing 4387:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
D/TimaKeyStoreProvider( 5317): in addTimaSignatureService
D/TimaKeyStoreProvider( 5317): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5317): Added TimaKesytore provider
I/SELinux ( 5331): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5331):  
I/ActivityManager(  750): Killing 4406:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,I/SELinux ( 5331): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5331):  
I/SELinux ( 5331):  
,I/SELinux ( 5331): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5331): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5331): >>>>> Normal User
,E/dalvikvm( 5331): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5331): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5331): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5331): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5331): Added TimaKesytore provider
,W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5331, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5331): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5343): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5343):  
,I/ActivityManager(  750): Killing 4419:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,D/dalvikvm( 5241): GC_CONCURRENT freed 4920K, 33% free 12767K/18800K, paused 1ms+2ms, total 30ms
,D/dalvikvm( 5241): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 5241): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SELinux ( 5343): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5343):  
I/SELinux ( 5343):  
,I/SELinux ( 5343): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5343): >>>>> Normal User
,E/dalvikvm( 5343): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5343): in addTimaSignatureService
D/TimaKeyStoreProvider( 5343): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5343): Added TimaKesytore provider
,I/ActivityManager(  750): Killing 3586:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/Finsky  ( 3686): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1786): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1786): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1786): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/dalvikvm( 1786): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1786): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1786): VFY: replacing opcode 0x6e at 0x0053
,D/CustomFrequencyManagerService(  750): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 750  tag : ACTIVITY_RESUME_BOOSTER@9
,I/dalvikvm( 1786): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1786): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1786): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1786): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1786): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1786): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1786): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1786): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1786): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1786): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 1786): GC_CONCURRENT freed 1960K, 38% free 11810K/18800K, paused 7ms+5ms, total 114ms
,D/dalvikvm( 1786): WAIT_FOR_CONCURRENT_GC blocked 35ms
D/ChimeraCfgMgr( 1786): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/dalvikvm( 1786): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/dalvikvm( 1786): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 1786): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/AsyncTaskServiceImpl( 1786): Submit a task: k
,D/ChimeraCfgMgr( 1786): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1786): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/BaseAppContext( 1786): Using Auth Proxy for data requests.
,W/BaseAppContext( 1786): Using Auth Proxy for data requests.
,D/k       ( 1786): Processing package: com.test.thalitest
,D/dalvikvm( 5241): GC_FOR_ALLOC freed 4716K, 28% free 15761K/21608K, paused 34ms, total 40ms
,D/GassUtils( 1786): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1786): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1786): Using Auth Proxy for data requests.
,W/BaseAppContext( 1786): Using Auth Proxy for data requests.
,W/BaseAppContext( 1786): Using Auth Proxy for data requests.
,W/BaseAppContext( 1786): Using Auth Proxy for data requests.
,W/BaseAppContext( 1786): Using Auth Proxy for data requests.
,W/dalvikvm( 1786): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1786): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1786): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1786): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1786): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1786): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1786): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1786): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1786): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1786): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1786): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1786): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1786): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1786): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1786): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1786): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1786): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1786): cleanUpNonGplusAccounts done.
,W/dalvikvm( 1786): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1786): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1786): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5241): GC_FOR_ALLOC freed 5081K, 31% free 16774K/24296K, paused 34ms, total 35ms
,I/dalvikvm-heap( 5241): Grow heap (frag case) to 21.827MB for 2475476-byte allocation
,D/dalvikvm( 5241): GC_FOR_ALLOC freed 3780K, 35% free 17459K/26716K, paused 31ms, total 33ms
,D/dalvikvm( 5241): GC_FOR_ALLOC freed 1242K, 36% free 17363K/26716K, paused 27ms, total 30ms
,I/Icing   ( 1786): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,W/jxcore-log( 5241): Initializing JXcore engine
,W/jxcore-log( 5241): JXcore engine is ready
,I/Icing   ( 1786): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,W/jxcore-log( 5241): Starting JXcore engine
,D/AmoledAdjustTimer(  750): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/jxcore-log( 5241): Platform android
W/jxcore-log( 5241): 
,W/jxcore-log( 5241): Process ARCH arm
W/jxcore-log( 5241): 
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5241): JXcore Cordova bridge is ready!
I/jxcore-log( 5241): 
,W/jxcore-log( 5241): JXcore engine is started
,I/chromium( 5241): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GAV2    ( 5227): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 5241): Toggling radios to true
I/jxcore-log( 5241): 
,D/BluetoothAdapter( 5241): enable(): BT is already enabled..!
,I/WifiManager( 5241): packageName : com.test.thalitest
I/WifiManager( 5241): setWifiEnabled : true
,I/WifiService(  750): setWifiEnabled: true pid=5241, uid=10179
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5241, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  750): Failed getting userId using ActivityManagerNative
W/WifiService(  750): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5241, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  750): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  750): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  750): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  750): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  750): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  750): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  750): disconnect: pid=5241, uid=10179
,I/jxcore-log( 5241): Radios toggled
I/jxcore-log( 5241): 
,I/wpa_supplicant( 1992): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5241): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5241): 
,I/jxcore-log( 5241): Perf Test app loaded loaded
I/jxcore-log( 5241): 
,I/jxcore-log( 5241): check test folder
I/jxcore-log( 5241): 
,I/jxcore-log( 5241): found test : ./testFindPeers.js
I/jxcore-log( 5241): 
,I/wpa_supplicant( 1992): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1992): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering(  750): interfaceLinkStateChanged wlan0, false
,D/Tethering(  750): interfaceStatusChanged wlan0, false
,D/Tethering(  750): InitialState.processMessage what=4
,E/Tethering(  750): No numeric data
D/Tethering(  750): interfaceLinkStateChanged wlan0, false
D/Tethering(  750): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1992): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  750): sendTetherStateChangedBroadcast 0, 0, 0
E/wpa_supplicant( 1992): Cmd 35605 not handled
E/wpa_supplicant( 1992): Cmd 35605 not handled
,I/wpa_supplicant( 1992): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
I/ConnectivityService(  750): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  750): performPollLocked(flags=0x1)
I/wpa_supplicant( 1992): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1992): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1992): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1992): First Scan Start
I/wpa_supplicant( 1992): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering(  750): interfaceLinkStateChanged wlan0, false
D/Tethering(  750): interfaceStatusChanged wlan0, false
,I/jxcore-log( 5241): found test : ./testSendData.js
I/jxcore-log( 5241): 
,W/Settings(  750): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  750): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService(  750): InactiveState{ what=143375 }
D/WifiP2pService(  750): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  237): Clearing all IP addresses on wlan0
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
V/AlarmManager(  750): waitForAlarm result :4
,V/NetworkStats(  750): performPollLocked() took 37ms
,I/WifiTrafficPoller(  750): evaluateTrafficStatsPolling
D/ConnectivityService(  750): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  750): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  750): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  750): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  750): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  750): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1063): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1063): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1063): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: GONE sig=2130837981 act=2130837934
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  750): Attempting to switch to mobile
D/ConnectivityService(  750): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 1063): checkOverflow(336), More:false, Req:false Child:2
,I/SELinux ( 5398): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5398):  
I/wpa_supplicant( 1992): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1992): Skip scan - already scanning
,V/RouteController(  237): /system/bin/ip -6 route del default table 2 2>&1
V/AlarmManager(  750): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WifiP2pService(  750): InactiveState{ what=143375 }
,V/RouteController(  237): RTNETLINK answers: No such process
,D/WifiP2pService(  750): P2pEnabledState{ what=143375 }
V/RouteController(  237): /system/bin/ip -6 rule del table 2 2>&1
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
D/BatteryService(  750): stay LED for fully charged
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,I/SELinux ( 5398): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5398):  
I/SELinux ( 5398):  
,I/SELinux ( 5398): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5398): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5398): >>>>> Normal User
,E/dalvikvm( 5398): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5398): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController(  237): RTNETLINK answers: No such file or directory
,D/CommandListener(  237): Clearing all IP addresses on wlan0
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
D/UiModeManager(  750): mCoverManager.getCoverState() : true
,W/NetworkManagementService(  750): route cmd failed: 
W/NetworkManagementService(  750): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  750): '
W/NetworkManagementService(  750): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  750): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  750): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  750): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  750): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  750): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  750): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  750): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  750): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  750): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  750): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  750): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  237): /system/bin/ip -4 route del default table 2 2>&1
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
E/WifiStateMachine(  750): Error! unhandled message{ when=-99ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  750): Error! unhandled message{ when=-99ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller(  750): evaluateTrafficStatsPolling
E/WifiStateMachine(  750): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController(  237): RTNETLINK answers: No such process
,V/RouteController(  237): /system/bin/ip -4 rule del table 2 2>&1
D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,D/TimaKeyStoreProvider( 5398): in addTimaSignatureService
V/RouteController(  237): /system/bin/ip route flush cached 2>&1
D/TimaKeyStoreProvider( 5398): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5398): Added TimaKesytore provider
D/STATUSBAR-IconMerger( 1063): checkOverflow(336), More:false, Req:false Child:2
,D/NetUtils(  750): android_net_utils_resetConnections in env=0x7950fcb8 clazz=0x6ae00001 iface=wlan0 mask=0x3
D/ConnectivityService(  750): resetConnections(wlan0, 3)
,V/NativeCrypto( 1310): Read error: ssl=0x7bfefc00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1310): SSL shutdown failed: ssl=0x7bfefc00: I/O error during system call, Broken pipe
,I/chromium( 5241): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/NetworkStats(  750): updateIfacesLocked()
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
D/NtpTrustedTime(  750): currentTimeMillis() cache hit
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
V/NetworkStats(  750): performPollLocked(flags=0x1)
D/ConnectivityService(  750): handleInetConditionChange: no active default network - ignore
V/NetworkStats(  750): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
V/NetworkStats(  750): performPollLocked() took 20ms
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
,I/System.out( 5398): Inside WakeupProvider
,I/System.out( 5398): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 5398): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5398): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5398): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/FactoryTest( 4764): Not factory mode
,D/FactoryTest( 4764): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4764): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4764): still no open session command from host, so toast
,V/ApplicationPolicy(  750): isApplicationStateBlocked userId 0 pkgname com.android.settings
W/ContextImpl( 4764): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4764): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
D/CustomFrequencyManagerService(  750): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 750  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  750): mDVFSHelper.acquire()
,I/SQLiteSecureOpenHelper( 2093): getWritableDatabase(pwd)
,D/LockPatternUtils( 1063): isPcwEnable = null
,I/SQLiteSecureOpenHelper( 2093): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1063): isPcwEnable = null
,E/MTPRx   ( 4764): started activity for popup
,E/SettingsReceiverActivity( 4764): PREF_DONT_ASK_AGAIN : false
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
I/ActivityManager(  750): Killing 4448:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/SettingsReceiverActivity( 4764): dev.kiessupport is : TRUE
,D/DialogFlow( 5398): initQueue()
,D/Headlines( 4122): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4122): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4122): Breath 67958 latestRequest time : 1450233025135 current time : 1450233093093
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/dalvikvm(  750): GC_EXPLICIT freed 2653K, 60% free 23907K/58660K, paused 7ms+14ms, total 145ms
,I/SurfaceFlinger(  246): id=19 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4764): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4764): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4764): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4764): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4764): Remote Branch: 
I/Adreno-EGL( 4764): Local Patches: 
I/Adreno-EGL( 4764): Reconstruct Branch: 
,I/HWUI    ( 4764): EGLImpl-HWUI Protected EGL context created
,I/ApplicationPolicy(  750): updateDataUsageMap
,D/Tethering(  750): Tethering got CONNECTIVITY_ACTION
D/Tethering(  750): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  750): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  750): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  750): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  750): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1440): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/OpenGLRenderer( 4764): Enabling debug mode 0
D/ConnectivityService(  750): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,I/NetworkMonitor( 3916): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5124): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5124): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5124): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5124): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5124): noConnectivity : true
,I/SELinux ( 5435): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5435):  
,E/SMD     (  240): DCD ON
,I/SELinux ( 5435): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5435):  
I/SELinux ( 5435):  
,I/SELinux ( 5435): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5435): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5435): >>>>> Normal User
,E/dalvikvm( 5435): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5435): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/TimaKeyStoreProvider( 5435): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5435): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5435): Added TimaKesytore provider
,D/CustomFrequencyManagerService(  750): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 750  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  750): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 750  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  750): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  750): mDVFSHelper.release()
,W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5435, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  750): Killing 4464:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/wpa_supplicant( 1992): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 1992): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1992): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1992): Trying to associate with  'G700'
D/Tethering(  750): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1992): Re-associate with C0.AA.48
D/Tethering(  750): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1992): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1992): Cmd 35609 not handled
,I/SELinux ( 5450): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5450):  
D/dalvikvm(  247): GC_EXPLICIT freed 43K, 50% free 9507K/18800K, paused 2ms+3ms, total 24ms
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/18800K, paused 1ms+2ms, total 18ms
E/wpa_supplicant( 1992): Cmd 35605 not handled
E/wpa_supplicant( 1992): Cmd 35847 not handled
E/wpa_supplicant( 1992): Cmd 35848 not handled
E/wpa_supplicant( 1992): Cmd 35605 not handled
I/wpa_supplicant( 1992): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1992): Associated with C0.AA.48
I/wpa_supplicant( 1992): freq(2412) increment count 2
I/wpa_supplicant( 1992): meet head of list.
I/wpa_supplicant( 1992): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/SELinux ( 5450): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5450):  
I/SELinux ( 5450):  
I/SELinux ( 5450): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5450): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5450): >>>>> Normal User
E/dalvikvm( 5450): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
E/SELinux ( 5450): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/Tethering(  750): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1992): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  750): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1992): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1992): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1992): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  750): interfaceLinkStateChanged wlan0, false
D/Tethering(  750): interfaceStatusChanged wlan0, false
D/Tethering(  750): interfaceLinkStateChanged wlan0, false
D/Tethering(  750): interfaceStatusChanged wlan0, false
D/WifiNative(  750): callSECApiVoid - ID [50]
D/Tethering(  750): interfaceLinkStateChanged wlan0, true
D/Tethering(  750): interfaceStatusChanged wlan0, true
E/Tethering(  750): No numeric data
D/Tethering(  750): sendTetherStateChangedBroadcast 1, 0, 0
D/NtpTrustedTime(  750): currentTimeMillis() cache hit
I/ConnectivityService(  750): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  750): performPollLocked(flags=0x1)
D/Tethering(  750): interfaceLinkStateChanged wlan0, true
D/Tethering(  750): interfaceStatusChanged wlan0, true
D/Tethering(  750): interfaceLinkStateChanged wlan0, true
D/Tethering(  750): interfaceStatusChanged wlan0, true
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/18800K, paused 4ms+3ms, total 29ms
D/Tethering(  750): interfaceLinkStateChanged wlan0, true
D/Tethering(  750): interfaceStatusChanged wlan0, true
D/Tethering(  750): interfaceLinkStateChanged wlan0, true
D/Tethering(  750): interfaceStatusChanged wlan0, true
D/TimaKeyStoreProvider( 5450): in addTimaSignatureService
D/NtpTrustedTime(  750): currentTimeMillis() cache hit
D/TimaKeyStoreProvider( 5450): Cannot add TimaSignature Service, License check Failed
V/NetworkStats(  750): performPollLocked() took 28ms
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/ActivityThread( 5450): Added TimaKesytore provider
D/NtpTrustedTime(  750): currentTimeMillis() cache hit
D/NtpTrustedTime(  750): currentTimeMillis() cache hit
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
D/WifiP2pService(  750): InactiveState{ what=143375 }
D/WifiP2pService(  750): P2pEnabledState{ what=143375 }
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5450, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  750): Killing 4492:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
I/SELinux ( 5463): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5463):  
I/SELinux ( 5463): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5463):  
I/SELinux ( 5463):  
I/SELinux ( 5463): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5463): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5463): >>>>> Normal User
E/dalvikvm( 5463): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 5463): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5463): in addTimaSignatureService
D/TimaKeyStoreProvider( 5463): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5463): Added TimaKesytore provider
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5463, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
D/KLMS-2.3.201 : ( 5463): KLMSValidator() : checkQATesting()
I/KLMS-2.3.201 : ( 5463): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450233093987
I/KLMS-2.3.201 : ( 5463): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
I/dhcpcd  ( 5475): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 5475): bssid match
I/ActivityManager(  750): Killing 4508:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
I/SELinux ( 5482): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5482):  
I/SELinux ( 5482): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5482):  
I/SELinux ( 5482):  
I/SELinux ( 5482): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5482): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5482): >>>>> Normal User
E/dalvikvm( 5482): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
E/SELinux ( 5482): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5482): in addTimaSignatureService
D/TimaKeyStoreProvider( 5482): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5482): Added TimaKesytore provider
D/SO_AGENT( 5482): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5482, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
I/SO_AGENT( 5482): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
I/SA      ( 4056): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4056): [BDLM] already registered in spp
I/SA      ( 4056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 4056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4056): [OR] == isSIMCardReady false ==
I/SA      ( 4056): [SCU] == networkStateCheck == false
I/SA      ( 4056): [OR] onReceive END
I/ActivityManager(  750): Killing 4622:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
D/PhoneNumberLocatorBootCompletedReceiver( 1237): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 1237): Phone number locator feature is dsiabled
I/SELinux ( 5494): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5494):  
I/SELinux ( 5494): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5494):  
I/SELinux ( 5494):  
I/SELinux ( 5494): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5494): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5494): >>>>> Normal User
E/dalvikvm( 5494): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
E/SELinux ( 5494): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5494): in addTimaSignatureService
D/TimaKeyStoreProvider( 5494): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5494): Added TimaKesytore provider
,I/sCloudBackupApp( 5494): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5494): Other Intent
,I/ActivityManager(  750): Killing 4667:com.sec.android.app.voicenote/1000 (adj 15): empty #43
D/com.samsung.app( 1440): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1440): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5507): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5507):  
,I/SELinux ( 5507): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5507):  
I/SELinux ( 5507):  
,I/SELinux ( 5507): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5507): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,E/dalvikvm( 5507): >>>>> Normal User
,E/dalvikvm( 5507): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5507): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5507): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5507): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5507): Added TimaKesytore provider
,D/CustomFrequencyManagerService(  750): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 750  tag : ACTIVITY_RESUME_BOOSTER@9
,W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5507, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  750): Killing 4655:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/Headlines( 4122): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4122): getCountryCode(): countryCode = PL
,D/Headlines( 4122): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4122): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 4122): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4122): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4122): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 4122): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4122): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5536): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5536):  
,I/SELinux ( 5536): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5536):  
I/SELinux ( 5536):  
,I/SELinux ( 5536): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5536): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5536): >>>>> Normal User
,E/dalvikvm( 5536): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5536): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5536): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5536): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5536): Added TimaKesytore provider
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5536): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5536): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 5536): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5536): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5536): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,D/WifiP2pService(  750): InactiveState{ what=143375 }
,D/WifiP2pService(  750): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  750): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  750): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  750): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  750): evaluateTrafficStatsPolling
D/ConnectivityService(  750): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  750): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  750): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  750): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  750): mBoosterFLAG : 2
,I/WifiTrafficPoller(  750): current booster mode : BTCoexMode
D/ConnectivityService(  750): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  750): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  750): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1063): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1063): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1063): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,D/ConnectivityService(  750): handleConnectivityChange: setting default proxy info 
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
V/RouteController(  237): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  237): /system/bin/ip -4 rule del table 2 2>&1
,V/WebViewChromium( 5536): Binding Chromium to the main looper Looper (main, tid 1) {422a7f48}
,I/chromium( 5536): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5536): Initializing chromium process, renderers=0
,V/RouteController(  237): RTNETLINK answers: No such file or directory
,V/RouteController(  237): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,W/chromium( 5536): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,I/Adreno-EGL( 5536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5536): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5536): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5536): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5536): Remote Branch: 
I/Adreno-EGL( 5536): Local Patches: 
I/Adreno-EGL( 5536): Reconstruct Branch: 
,V/RouteController(  237): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  237): RTNETLINK answers: No such process
,V/RouteController(  237): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,I/NSApplication( 5536): Starting up...
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
V/NetworkStats(  750): updateIfacesLocked()
V/NetworkStats(  750): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
V/NetworkStats(  750): advisePersistThreshold() given 9223372036854775, clamped to 2097152
V/NetworkStats(  750): performPollLocked() took 18ms
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
,D/NtpTrustedTime(  750): currentTimeMillis() cache hit
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5536, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  750): Killing 4714:com.google.android.talk/u0a105 (adj 15): empty #43
D/QuickConnect[1.1][2] ( 3361): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3361): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3361): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425da230
,I/SELinux ( 5590): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5590):  
,I/SELinux ( 5590): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5590):  
I/SELinux ( 5590):  
,I/SELinux ( 5590): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5590): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5590): >>>>> Normal User
,E/dalvikvm( 5590): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5590): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5590): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5590): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5590): Added TimaKesytore provider
,D/RCPManagerService(  750): exchangeData() failure , invalid userId
,D/RCPManagerService(  750): exchangeData() failure , invalid userId
,D/RCPManagerService(  750): exchangeData() failure , invalid userId
,D/RCPManagerService(  750): exchangeData() failure , invalid userId
,D/RCPManagerService(  750): exchangeData() failure , invalid userId
,D/RCPManagerService(  750): exchangeData() failure , invalid userId
I/ActivityManager(  750): Killing 3044:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,I/SELinux ( 5609): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5609):  
,I/SELinux ( 5613): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5613):  
W/ActivityManager(  750): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5609): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5609):  
I/SELinux ( 5609):  
,I/SELinux ( 5609): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5609): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5609): >>>>> Normal User
,E/dalvikvm( 5609): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5609): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5609): in addTimaSignatureService
I/SELinux ( 5613): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5613):  
I/SELinux ( 5613):  
,I/SELinux ( 5613): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5613): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5613): >>>>> Normal User
E/dalvikvm( 5613): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,D/TimaKeyStoreProvider( 5609): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5609): Added TimaKesytore provider
,E/SELinux ( 5613): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5613): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5613): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5613): Added TimaKesytore provider
,I/ActivityManager(  750): Killing 4792:com.sec.knox.bridge/1000 (adj 15): empty #43
,W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5609, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/hcjo    ( 4211): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4211): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4211): exit::IDLE
,D/InitializeManagerStateMachine( 4211): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4211): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4211): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4211): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4211): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4211): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4211): entry::SUCCESS
,D/hcjo    ( 4211): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4211): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4211): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4211): exit::SUCCESS
,D/InitializeManagerStateMachine( 4211): entry::IDLE
,D/BadgeProvider( 5613): onCreate
,D/BadgeProvider( 5613): DatabaseHelper
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5613, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  750): Killing 4812:com.wssyncmldm/1000 (adj 15): empty #43
,D/BadgeProvider( 5613): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/BadgeProvider( 5613): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5613): sendNotify, [notify] : null
D/BadgeProvider( 5613): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5613): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5613): update, [UpdateCount] : 1
,D/Launcher.Model( 1241): reloadBadges entered.
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/Tethering(  750): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  750): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  750): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController_dual( 1063): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
,D/LocSvc_java(  750): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  750): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  750): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1440): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,I/NetworkMonitor( 3916): type=WIFI subType= reason=null isConnected=true
,D/Toast   ( 1302):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1302): showing allowed
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 5124): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5124): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5124): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5124): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  246): id=20 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  750): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=750
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/dalvikvm( 1310): GC_EXPLICIT freed 1333K, 43% free 10783K/18800K, paused 3ms+5ms, total 37ms
,I/VacuumService( 1216): Vacuum at: now=1450233095711 tag=VacuumService
,I/KLMS-2.3.201 : ( 5463): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/dalvikvm( 1786): GC_CONCURRENT freed 1562K, 35% free 12246K/18800K, paused 4ms+10ms, total 41ms
,W/SQLiteConnectionPool( 1786): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/KLMS-2.3.201 : ( 5463): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450233095785
,I/KLMS-2.3.201 : ( 5463): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/LocationTagReadyService( 2547): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2547): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2547): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2547): [Slink platform] The state of Slink geocode service is true
,D/SO_AGENT( 5482): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5482): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 5641): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5641):  
,I/GallerySearchProvider( 2447): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5645): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5645):  
,I/SELinux ( 5641): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5641):  
I/SELinux ( 5641):  
,I/SELinux ( 5641): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5641): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 5641): >>>>> Normal User
,E/dalvikvm( 5641): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5641): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5641): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5641): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5641): Added TimaKesytore provider
,I/SELinux ( 5645): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5645):  
I/SELinux ( 5645):  
,I/SELinux ( 5645): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5645): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5645): >>>>> Normal User
,E/dalvikvm( 5645): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5645): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5645): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5645): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5645): Added TimaKesytore provider
I/SA      ( 4056): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4056): [BDLM] already registered in spp
,I/SA      ( 4056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4056): [OR] == isSIMCardReady false ==
I/SA      ( 4056): [SCU] == networkStateCheck == true
I/SA      ( 4056): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4056): isChinaCountryCode : false
,I/SA      ( 4056): [OR] == networkStateCheck true ==
,I/SA      ( 4056): [OR] GetMyCountryZoneTask
,I/SA      ( 4056): [OR] onReceive END
,I/SA      ( 4056): [SRS] prepareGetMyCountryZone
,I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4056): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5494): Other Intent
,I/SA      ( 4056): [TPMU] GetMccFromDB : null
,I/SA      ( 4056): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4056): [TPM] isNoProxy(default) : true
,I/SA      ( 4056): [RC New] Execute method=[GET] start
,D/com.samsung.app( 1440): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1440): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4122): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4122): getCountryCode(): countryCode = PL
D/Headlines( 4122): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4122): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4122): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4122): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4122): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4122): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4122): requestUpdateNewsWelcomeCard !!! no welcome card
,V/KVNProvider( 5645): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5645): getFindoCursor query string : 
,V/KVNProvider( 5645): getTagSearchCursor() tagSearchCursor count : 0
,D/QuickConnect[1.1][2] ( 3361): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3361): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3361): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425da230
,D/RCPManagerService(  750): exchangeData() failure , invalid userId
,D/RCPManagerService(  750): exchangeData() failure , invalid userId
I/ActivityManager(  750): Killing 4651:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/hcjo    ( 4211): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4211): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4211): exit::IDLE
,D/InitializeManagerStateMachine( 4211): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4211): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4211): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4211): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4211): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 4211): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4211): entry::SUCCESS
,D/hcjo    ( 4211): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4211): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4211): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4211): exit::SUCCESS
,D/InitializeManagerStateMachine( 4211): entry::IDLE
,D/SSRMv2:SIOP(  750): SIOP:: AP = 320, Delta = 10
,E/SMD     (  240): DCD ON
,I/SA      ( 4056): [RC New] [v2liruge] api execute + 653
,I/SA      ( 4056): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4056): AsyncTask #2 calls detatch()
,I/SA      ( 4056): [TPMU] getNetworkMcc : 
,I/SA      ( 4056): [SCU] saveMccToPreferece Start
,I/SA      ( 4056): [SCU] RegionMCC : 260
,I/SA      ( 4056): [SSP] query invoked
,I/SA      ( 4056): [TPMU] GetMccFromDB : null
I/SA      ( 4056): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4056): [SCU] saveMccToPreferece End
,I/SA      ( 4056): [RC New] executeRequest [v2liruge] end. 669
I/SA      ( 4056): [RC New] Execute end
I/SA      ( 4056): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4056): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 5241): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5241): 
,E/WifiStateMachine(  750): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/HarmonyEASService(  750): Updating for all 1
,I/ActivityManager(  750): Killing 4233:com.android.calendar/u0a142 (adj 15): empty #43
,I/SurfaceFlinger(  246): id=20 Removed Uoast (12/13)
,I/SurfaceFlinger(  246): id=20 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  750): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=750 (0x0)
,D/PowerManagerService(  750): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=750, ws=WorkSource{1000}) (elapsedTime=3480),
,E/SMD     (  240): DCD ON
,W/WifiP2pStateTracker(  750): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  750): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  750):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  750): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  750): updateSourceRoutes : no source routing conditions
,I/GAV2    ( 5536): Thread[GAThread,5,main]: No campaign data found.
,D/AmoledAdjustTimer(  750): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5124): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5124): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5124): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5124): ================================================
I/CSTORAGE( 5124):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5124): ================================================
D/dalvikvm( 5124): No JNI_OnLoad found in /system/lib/libterrier.so 0x425d42b8, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5124): [GetString-S]
,I/terrier ( 5124): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5124): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5124): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5124): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5124): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5124): QSEECom_shutdown_app, app_id = 3
,E/terrier ( 5124): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5124): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5124): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5124): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5124): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5124): [ensureRegistration] - No Samsung account
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  750): waitForAlarm result :4
,V/AlarmManager(  750): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3686): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3686): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  240): DCD ON
,D/PreloadUpdateManagerStateMachine( 4211): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4211): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4211): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4211): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4211): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4211): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4211): entry::IDLE
,D/CaptivePortalTracker(  750): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  750): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  750): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  750): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  750): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  750): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  750): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  750): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4211): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4211): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4211): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4211): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4211): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4211): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4211): entry::IDLE
,D/SSRMv2:SIOP(  750): SIOP:: AP = 310, Delta = -10
,E/Watchdog(  750): !@Sync 4
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 290, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService(  750): [PWL] Off : 75s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,D/Headlines( 4122): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4122): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4122): Breath 19148 latestRequest time : 1450233096026 current time : 1450233115174
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = -10
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 292, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 5
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 290, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService(  750): [PWL] Off : 105s ago
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :4
,V/AlarmManager(  750): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4122): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 4122): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4122): Breath 56710 latestRequest time : 1450233096026 current time : 1450233152736
,D/dalvikvm(  750): GC_EXPLICIT freed 3479K, 60% free 23876K/58660K, paused 27ms+19ms, total 302ms
,E/SMD     (  240): DCD ON
,I/PhenotypeConfigurator( 1216): Scheduling Phenotype for one-off execution 13527 seconds from now (1450233153619)
,D/GetConfigurationSnapshotOperation( 1216): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1216): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1216): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1216): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1216): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  750): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1216): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1216): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1216): Thread-106(HTTPLog):isShipBuild true
,I/System.out( 1216): Thread-106(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1216): GC_CONCURRENT freed 1495K, 37% free 11913K/18800K, paused 7ms+10ms, total 73ms
,E/SMD     (  240): DCD ON
D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 6
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,D/Headlines( 4122): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4122): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4122): Breath 79151 latestRequest time : 1450233096026 current time : 1450233175178
,I/PowerManagerService(  750): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 7
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,D/Headlines( 4122): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4122): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4122): Breath 109154 latestRequest time : 1450233096026 current time : 1450233205180
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  750): [PWL] Off : 180s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 8
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,D/Headlines( 4122): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4122): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4122): Breath 139150 latestRequest time : 1450233096026 current time : 1450233235177
,D/Headlines( 4122): stop 
,D/Headlines( 4122): Breath.onDestroy : 
,I/ActivityManager(  750): Killing 4434:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 9
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService(  750): [PWL] Off : 225s ago
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5241): Connected to the server!
I/jxcore-log( 5241): 
,I/chromium( 5241): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/TimaService(  750): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  750): TimaServiceHandler.handleMessage what =1
,D/TimaService(  750): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  750): initializing...
,I/TLC_TIMA_PKM_initialize(  750): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  750): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  750): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  750): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  750): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  750): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  750): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  750): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  750): App is not loaded in QSEE
,D/QSEECOMAPI: (  750): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  750): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_initialize(  750): Trustlet response is completed
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 10
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService(  750): [PWL] Off : 275s ago
,V/AlarmManager(  750): waitForAlarm result :4
,V/AlarmManager(  750): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,I/SELinux ( 5784): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5784):  
,V/AlarmManager(  750): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/dalvikvm(  247): GC_EXPLICIT freed 42K, 50% free 9507K/18800K, paused 26ms+33ms, total 287ms
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/18800K, paused 20ms+28ms, total 183ms
,I/SELinux ( 5784): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5784):  
I/SELinux ( 5784):  
,I/SELinux ( 5784): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5784): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5784): >>>>> Normal User
,E/dalvikvm( 5784): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5784): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/18800K, paused 19ms+38ms, total 197ms
,D/TimaKeyStoreProvider( 5784): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5784): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5784): Added TimaKesytore provider
,W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=5784, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,E/SMD     (  240): DCD ON
I/ActivityManager(  750): Killing 4613:com.sec.phone/1001 (adj 15): empty #43
,I/EventLogService( 1786): Aggregate from 1450231430732 (log), 1450231430732 (data)
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 11
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 12
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  750): [PWL] Off : 330s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 13
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 14
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  750): [PWL] Off : 390s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 15
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  750): !@Sync 16
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService(  750): [PWL] Off : 455s ago
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 17
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 18
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 275, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 19
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/dalvikvm(  750): GC_CONCURRENT freed 3599K, 60% free 23788K/58660K, paused 22ms+49ms, total 546ms
,I/PowerManagerService(  750): [PWL] Off : 525s ago
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService(  750): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  750): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  750): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  750): !@Sync 20
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/AmoledAdjustTimer(  750): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 21
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,I/SensorManagerA(  750): getReportingMode :: sensor.mType = 5
,D/Sensors (  750): LightSensor setDelay = 200000000
,D/LightsService(  750): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  750): LightSensor setSensorDelay = 200000000
D/Sensors (  750): Light sensor flush: not enabled 0
D/Sensors (  750): LightSensor enable = 1
D/Sensors (  750): LightSensor enableSensor = 1
D/SensorManager(  750): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService(  750): [PWL] Off : 600s ago
,D/Sensors (  750): LightSensor enable = 0
,D/Sensors (  750): LightSensor enableSensor = 0
,D/SensorManager(  750): unregisterListener ::   
D/LightsService(  750): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  750): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 22
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  750): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  750): <AppSync3 Whitelist>
,V/AlarmManager(  750): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  750): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 23
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 24
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  750): [PWL] Off : 680s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 25
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 26
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 27
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService(  750): [PWL] Off : 765s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 28
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  750): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 29
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  750): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  750): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  750): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  750): !@Sync 30
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService(  750): [PWL] Off : 855s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 31
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 32
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 33
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  750): [PWL] Off : 950s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 34
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/dalvikvm(  750): GC_CONCURRENT freed 3482K, 60% free 23776K/58660K, paused 31ms+51ms, total 589ms
,E/Watchdog(  750): !@Sync 35
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 36
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  750): [PWL] Off : 1050s ago
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 37
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  750): !@Sync 38
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 39
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/TimaService(  750): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  750): TimaServiceHandler.handleMessage what =1
,D/TimaService(  750): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  750): !@Sync 40
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,I/PowerManagerService(  750): [PWL] Off : 1155s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 41
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,D/LightsService(  750): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  750): getReportingMode :: sensor.mType = 5
D/Sensors (  750): LightSensor setDelay = 200000000
D/Sensors (  750): LightSensor setSensorDelay = 200000000
D/Sensors (  750): Light sensor flush: not enabled 0
D/Sensors (  750): LightSensor enable = 1
D/Sensors (  750): LightSensor enableSensor = 1
D/SensorManager(  750): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  750): LightSensor enable = 0
,D/Sensors (  750): LightSensor enableSensor = 0
,D/LightsService(  750): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  750): unregisterListener ::   
D/LightsService(  750): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): stay LED for fully charged
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  750): !@Sync 42
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  750): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  750): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
V/AlarmManager(  750): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 43
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  750): [PWL] Off : 1265s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 44
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  750): !@Sync 45
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  750): !@Sync 46
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,E/Watchdog(  750): !@Sync 47
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  750): [PWL] Off : 1380s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 48
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 49
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  750): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  750): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  750): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  750): !@Sync 50
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 51
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  750): [PWL] Off : 1500s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm(  750): GC_CONCURRENT freed 3461K, 60% free 23788K/58660K, paused 46ms+50ms, total 578ms
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 52
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 53
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 54
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 55
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  750): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 56
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 57
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 58
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 59
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/TimaService(  750): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  750): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  750): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  750): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  750): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 60
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  750): [PWL] Off : 1755s ago
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  750): Prepared write state in 134ms
,I/ProcessStatsService(  750): Prepared write state in 135ms
,I/ProcessStatsService(  750): Pruning old procstats: /data/system/procstats/state-2015-12-15-16-16-48.bin
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  750): stay LED for fully charged
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/UiModeManager(  750): mCoverManager.getCoverState() : true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 61
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/BatteryService(  750): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 62
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  750): waitForAlarm result :8
,V/AlarmManager(  750): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  750): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  750): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
V/AlarmManager(  750): (AppSync) ### 0 added ###
,I/ActivityManager(  750): Killing 4572:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1826s
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): stay LED for fully charged
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 269, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  750): !@Sync 63
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  750): stay LED for fully charged
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  240): DCD ON
D/UiModeManager(  750): mCoverManager.getCoverState() : true
D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  750): mCoverManager.getCoverState() : true
,D/BatteryService(  750): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  240): DCD ON
E/Watchdog(  750): !@Sync 64
E/SMD     (  240): DCD ON
D/BatteryService(  750): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService(  750): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  750): mCoverManager.getCoverState() : true
D/BatteryService(  750): stay LED for fully charged
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  240): DCD ON
D/SSRMv2:SIOP(  750): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  750): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
E/SMD     (  240): DCD ON
D/AndroidRuntime( 6152): 
D/AndroidRuntime( 6152): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6152): CheckJNI is OFF
D/AndroidRuntime( 6152): setted country_code = Poland
D/AndroidRuntime( 6152): setted countryiso_code = PL
D/AndroidRuntime( 6152): setted sales_code = XEO
D/AndroidRuntime( 6152): readGMSProperty: start
D/AndroidRuntime( 6152): readGMSProperty: already setted!!
D/AndroidRuntime( 6152): readGMSProperty: end
D/AndroidRuntime( 6152): addProductProperty: start
D/dalvikvm( 6152): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6152): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6152): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6152): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6152): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6152): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6152): failed to load memtrack module: -2
D/dalvikvm( 6152): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6152): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  750): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  750): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  750): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  750): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  750): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  750): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  750): START PACKAGE DELETE: observer{1126202608}
D/PackageManager(  750): pkg{<packageName>}
D/PackageManager(  750): user{0}
D/PackageManager(  750): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManagerService(  750): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  750): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  750): getApplicationUninstallationEnabled
D/ApplicationPolicy(  750): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  750): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  750): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  750): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  750): Killing 5241:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/ActivityManager(  750): Killing 5398:com.vlingo.midas/u0a33 (adj 15): empty for 1822s
I/ActivityManager(  750): Killing 5463:com.samsung.klmsagent/u0a18 (adj 15): empty for 1822s
I/ActivityManager(  750): Killing 5450:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1822s
I/ActivityManager(  750): Killing 3959:com.sec.android.diagmonagent/1000 (adj 15): empty for 1822s
I/ActivityManager(  750): Killing 5435:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1822s
I/ActivityManager(  750): Killing 3916:com.google.android.music:main/u0a122 (adj 15): empty for 1822s
I/ActivityManager(  750): Killing 5124:com.sec.pcw.device/1000 (adj 15): empty for 1822s
I/ActivityManager(  750): Killing 1302:com.android.settings/1000 (adj 15): empty for 1822s
I/ActivityManager(  750): Killing 5613:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1822s
I/ActivityManager(  750): Killing 5343:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1830s
I/ActivityManager(  750): Killing 5331:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1830s
I/ActivityManager(  750): Killing 5317:com.samsung.helphub/1000 (adj 15): empty for 1830s
I/ActivityManager(  750): Killing 5304:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1830s
I/ActivityManager(  750): Killing 5284:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1831s
I/ActivityManager(  750): Killing 5227:com.google.android.apps.docs/u0a90 (adj 15): empty for 1831s
I/ActivityManager(  750): Killing 5213:com.sec.android.service.cm/u0a78 (adj 15): empty for 1831s
I/ActivityManager(  750): Killing 4693:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1831s
I/ActivityManager(  750): Killing 4340:com.android.mms/u0a48 (adj 15): empty for 1832s
I/ActivityManager(  750): Killing 5172:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1832s
I/ActivityManager(  750): Killing 4248:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1832s
I/ActivityManager(  750): Killing 5136:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1832s
I/ActivityManager(  750): Killing 5108:com.android.musicfx/u0a24 (adj 15): empty for 1833s
I/ActivityManager(  750): Killing 5094:com.samsung.groupcast/u0a15 (adj 15): empty for 1833s
I/ActivityManager(  750): Killing 5078:com.google.android.partnersetup/u0a14 (adj 15): empty for 1833s
I/ActivityManager(  750): Killing 5066:com.sec.android.inputmethod/1000 (adj 15): empty for 1833s
I/ActivityManager(  750): Killing 5014:com.android.defcontainer/u0a6 (adj 15): empty for 1834s
I/SurfaceFlinger(  246): id=18 Removed NainActivit (7/12)
I/SurfaceFlinger(  246): id=18 Removed NainActivit (-2/12)
I/WindowState(  750): WIN DEATH: Window{438857e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=18 Removed NainActivit (-2/12)
D/CountryDetector(  750): No listener is left
E/SMD     (  240): DCD ON
D/dalvikvm(  750): GC_CONCURRENT freed 3594K, 60% free 23789K/58660K, paused 5ms+10ms, total 106ms
D/dalvikvm(  750): WAIT_FOR_CONCURRENT_GC blocked 90ms
W/PackageSettings(  750): Skipping PackageSetting{42af86f0 com.example.hello/10181} due to missing metadata
D/PackageManager(  750): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager(  750): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1063): action=android.intent.action.PACKAGE_REMOVED
I/FPMS_FingerprintManagerService( 1082): onReceive: android.intent.action.PACKAGE_REMOVED
I/InputReader(  750): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 1786): GC_EXPLICIT freed 344K, 35% free 12280K/18800K, paused 3ms+7ms, total 58ms
D/QuickConnect[1.1][2] ( 3361): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/RCPManagerService(  750): PackageReceiver onReceive()
I/HarmonyEASService(  750): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/GeofencerStateMachine( 1216): Ignoring removeGeofence because network location is disabled.
I/SELinux ( 6182): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6182):  
D/dalvikvm( 1395): GC_EXPLICIT freed 4302K, 47% free 10026K/18800K, paused 4ms+5ms, total 71ms
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "sms"
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "smsto"
I/SELinux ( 6182): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6182):  
I/SELinux ( 6182):  
I/SELinux ( 6182): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6182): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6182): >>>>> Normal User
E/dalvikvm( 6182): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6182): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "mms"
D/dalvikvm( 2170): GC_EXPLICIT freed 993K, 42% free 10994K/18800K, paused 5ms+5ms, total 133ms
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6182): in addTimaSignatureService
D/TimaKeyStoreProvider( 6182): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6182): Added TimaKesytore provider
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "mmsto"
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "sms"
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "smsto"
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "mms"
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SurfaceFlinger(  246): id=21 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "mmsto"
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  750): Package has changed for user 0
D/EnterpriseDeviceManagerService(  750): Admin package name: com.google.android.gms
D/elm:14132( 6182): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=6182, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/BackupManagerService(  750): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  750): removePackageParticipantsLocked: uid=10179 #1
D/elm:14132( 6182): ELMEngine.ELMEngine( context ).
D/elm:14132( 6182): MDMBridge.setEnterpriseBridge()
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6182): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6182): ElmAgentService : onCreate()
D/elm:14132( 6182): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6182): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6182): MDMBridge.getInstance()
D/elm:14132( 6182): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6182): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6197): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6197):  
D/elm:14132( 6182): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 6182): ElmAgentService : onDestroy().
I/ActivityManager(  750): Killing 5482:com.sec.android.soagent/u0a37 (adj 15): empty for 1823s
I/SELinux ( 6197): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6197):  
I/SELinux ( 6197):  
I/SELinux ( 6197): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6197): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6197): >>>>> Normal User
E/dalvikvm( 6197): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6197): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(  750): GC_EXPLICIT freed 1622K, 60% free 23758K/58660K, paused 6ms+20ms, total 323ms
D/PackageManager(  750): delete sourFile : 
D/TimaKeyStoreProvider( 6197): in addTimaSignatureService
D/TimaKeyStoreProvider( 6197): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6197): Added TimaKesytore provider
D/PackageManager(  750): delete native library directory: 
D/PackageManager(  750): return delete result to caller: 1126202608
D/AndroidRuntime( 6152): Shutting down VM
D/dalvikvm( 6152): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+0ms, total 4ms
D/PackageManager(  750): returnCode: 1
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "sms"
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "smsto"
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "mms"
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  750):   Action: "android.intent.action.SENDTO"
I/PackageManager(  750):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  750):   Scheme: "mmsto"
I/PackageManager(  750): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  750): Permission Denial: getCurrentUser() from pid=6197, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 6197): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425ccb40, skipping init
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 6197): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6197): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6197
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6197): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 6197): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6197
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher( 1241): onRestart, Launcher: 1114060904
D/Launcher( 1241): onStart, Launcher: 1114060904
D/Launcher.HomeView( 1241): onStart
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1440): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1440): [237392/5] SurfaceWidget drawing first frame
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SurfaceFlinger(  246): id=22 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  750): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  750): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  750): clearDefaults: com.test.thalitest
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/InputReader(  750): Processing first event
W/ApplicationsProvider( 1395): Could not fetch usage stats
W/ApplicationsProvider( 1395): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1395): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1395): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1395): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1395): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1395): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1395): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1395): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1395): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1395): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1395): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
