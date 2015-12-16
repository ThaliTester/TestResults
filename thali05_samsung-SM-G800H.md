#### Test 50650278923ff9f_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
D/TimaKeyStoreProvider( 5152): in addTimaSignatureService
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18432K, paused 2ms+3ms, total 23ms
D/TimaKeyStoreProvider( 5152): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5152): Added TimaKesytore provider
,--------- beginning of /dev/log/system
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5152, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5152): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5152): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  760): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
I/SA      ( 4038): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4038): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4038): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4331): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2179): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5185): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5185):  
I/ActivityManager(  760): Killing 3975:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/AndroidRuntime( 5170): 
D/AndroidRuntime( 5170): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5170): CheckJNI is OFF
D/AndroidRuntime( 5170): setted country_code = Poland
D/AndroidRuntime( 5170): setted countryiso_code = PL
D/AndroidRuntime( 5170): setted sales_code = XEO
D/AndroidRuntime( 5170): readGMSProperty: start
D/AndroidRuntime( 5170): readGMSProperty: already setted!!
D/AndroidRuntime( 5170): readGMSProperty: end
D/AndroidRuntime( 5170): addProductProperty: start
I/SELinux ( 5185): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5185):  
I/SELinux ( 5185):  
I/SELinux ( 5185): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5185): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5185): >>>>> Normal User
E/dalvikvm( 5185): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5185): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm( 5170): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5170): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5170): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5170): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5170): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/TimaKeyStoreProvider( 5185): in addTimaSignatureService
D/TimaKeyStoreProvider( 5185): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5185): Added TimaKesytore provider
I/IcingCorporaProvider( 2179): UpdateCorporaTask done [took 155 ms] updated apps [took 154 ms] 
D/CapabilityManagerService New( 5185): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5185, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5204): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5204):  
I/ActivityManager(  760): Killing 4258:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5204): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5204):  
I/SELinux ( 5204):  
I/SELinux ( 5204): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5204): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5204): >>>>> Normal User
E/dalvikvm( 5204): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5204): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5204): in addTimaSignatureService
D/TimaKeyStoreProvider( 5204): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5204): Added TimaKesytore provider
E/memtrack( 5170): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5170): failed to load memtrack module: -2
D/dalvikvm( 5170): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5170): Calling main entry com.android.commands.am.Am
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5204, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
V/ApplicationPolicy(  760): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  760): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 760  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  760): mDVFSHelper.acquire()
I/SELinux ( 5218): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5218):  
D/LockPatternUtils( 1067): isPcwEnable = null
D/AndroidRuntime( 5170): Shutting down VM
D/dalvikvm( 5170): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
I/SELinux ( 5218): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5218):  
I/SELinux ( 5218):  
I/SELinux ( 5218): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5218): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5218): >>>>> Normal User
E/dalvikvm( 5218): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5218): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5218): in addTimaSignatureService
D/TimaKeyStoreProvider( 5218): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5218): Added TimaKesytore provider
I/PowerManagerService(  760): [PWL] Off : 50s ago
D/LockPatternUtils( 1067): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2100): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2100): getDatabaseLocked(b,b,pwd)...
D/SurfaceWidgetView( 1247): destroyHardwareResources():1125772152
I/SurfaceFlinger(  246): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  246): id=13 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  246): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5218, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1247): onTrimMemory. Level: 20
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5218, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5218): Binding Chromium to the background looper Looper (main, tid 1) {4226f198}
I/chromium( 5218): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5218): Initializing chromium process, renderers=0
W/chromium( 5218): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5218): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5218): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5218): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5218): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5218): Remote Branch: 
I/Adreno-EGL( 5218): Local Patches: 
I/Adreno-EGL( 5218): Reconstruct Branch: 
I/dalvikvm( 5218): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5218): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5218): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5218): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5218): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5218): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5218): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5218): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5218): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5218): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5218): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5218): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5218): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5218): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5218): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5218): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5218): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5218): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5218): CordovaWebView is running on device made by: samsung
W/GAV2    ( 5204): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/SSRMv2:SIOP(  760): SIOP:: AP = 310, Delta = 0
I/SELinux ( 5261): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5261):  
I/SELinux ( 5261): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5261):  
I/SELinux ( 5261):  
I/SELinux ( 5261): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5261): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5261): >>>>> Normal User
E/dalvikvm( 5261): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5261): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SurfaceFlinger(  246): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 5261): in addTimaSignatureService
D/TimaKeyStoreProvider( 5261): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5261): Added TimaKesytore provider
I/HWUI    ( 5218): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 5218): Enabling debug mode 0
W/AwContents( 5218): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  760): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 760  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  760): mDVFSHelper.release()
D/CustomFrequencyManagerService(  760): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 760  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/PackageIntentReceiver( 5261): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5261): Not GearManger package! 
I/SELinux ( 5287): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5287):  
I/ActivityManager(  760): Killing 3988:com.sec.android.soagent/u0a37 (adj 15): empty #43
I/SELinux ( 5287): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5287):  
I/SELinux ( 5287):  
I/SELinux ( 5287): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5287): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5287): >>>>> Normal User
E/dalvikvm( 5287): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5287): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5287): in addTimaSignatureService
D/TimaKeyStoreProvider( 5287): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5287): Added TimaKesytore provider
D/MagazineService Version( 5287): Magazine-Channel: 13
D/MagazineService Version( 5287): Magazine-Provider: 13
D/MagazineService Version( 5287): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5287): [onCreate]
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5287, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/MagazineService::MagazineBroadcastReceiver( 5287): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
I/MagazineService::MagazineService( 5287): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5301): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5301):  
D/MagazineService::MagazineService( 5287): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  760): Killing 1338:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
W/GAV2    ( 5204): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/SELinux ( 5301): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5301):  
I/SELinux ( 5301):  
I/SELinux ( 5301): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5301): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5301): >>>>> Normal User
E/dalvikvm( 5301): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
I/ActivityManager(  760): Killing 4369:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
E/SELinux ( 5301): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5301): in addTimaSignatureService
D/TimaKeyStoreProvider( 5301): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5301): Added TimaKesytore provider
D/JsMessageQueue( 5218): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 5218): Trying to load lib /data/app-lib/com.test.thalitest-53/libjxcore.so 0x42595ed0
D/dalvikvm( 5218): Added shared lib /data/app-lib/com.test.thalitest-53/libjxcore.so 0x42595ed0
D/jxcore_app_log( 5218): JniHelper::setJavaVM(0x4175f528), pthread_self() = 2033337672
D/JX-Cordova( 5218): jxcore cordova android initializing
I/SELinux ( 5318): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5318):  
I/ActivityManager(  760): Killing 4385:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
I/SELinux ( 5318): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5318):  
I/SELinux ( 5318):  
I/SELinux ( 5318): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5318): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5318): >>>>> Normal User
E/dalvikvm( 5318): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 5318): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5318): in addTimaSignatureService
D/TimaKeyStoreProvider( 5318): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5318): Added TimaKesytore provider
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5318, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 5318): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5330): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5330):  
I/ActivityManager(  760): Killing 4397:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5330): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5330):  
I/SELinux ( 5330):  
,I/SELinux ( 5330): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5330): >>>>> Normal User
,E/dalvikvm( 5330): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5330): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5330): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5330): Added TimaKesytore provider
,I/ActivityManager(  760): Killing 3587:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/Finsky  ( 3687): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1756): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/dalvikvm( 1756): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1756): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0053
,D/dalvikvm( 5218): GC_CONCURRENT freed 4919K, 31% free 12772K/18432K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 5218): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 5218): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/dalvikvm( 1756): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1756): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 1756): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1756): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1756): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1756): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1756): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1756): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1756): Submit a task: k
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1756): Processing package: com.test.thalitest
,D/CustomFrequencyManagerService(  760): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 760  tag : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  240): DCD ON
D/GassUtils( 1756): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1756): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1756): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1756): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1756): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1756): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x000e
,I/dalvikvm( 1756): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1756): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1756): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1756): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 1756): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1756): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1756): cleanUpNonGplusAccounts done.
,D/dalvikvm( 5218): GC_FOR_ALLOC freed 4714K, 26% free 15766K/21240K, paused 32ms, total 34ms
,W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5218): GC_FOR_ALLOC freed 5081K, 30% free 16779K/23928K, paused 35ms, total 35ms
,I/dalvikvm-heap( 5218): Grow heap (frag case) to 21.468MB for 2475476-byte allocation
,D/dalvikvm( 5218): GC_FOR_ALLOC freed 3780K, 34% free 17464K/26348K, paused 32ms, total 32ms
,I/Icing   ( 1756): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1756): GC_CONCURRENT freed 1319K, 33% free 12463K/18432K, paused 4ms+4ms, total 48ms
,I/Icing   ( 1756): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/dalvikvm( 5218): GC_FOR_ALLOC freed 1242K, 35% free 17368K/26348K, paused 27ms, total 29ms
,W/jxcore-log( 5218): Initializing JXcore engine
,W/jxcore-log( 5218): JXcore engine is ready
,W/jxcore-log( 5218): Starting JXcore engine
,W/jxcore-log( 5218): Platform android
W/jxcore-log( 5218): 
,W/jxcore-log( 5218): Process ARCH arm
W/jxcore-log( 5218): 
,D/AmoledAdjustTimer(  760): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 5218): JXcore Cordova bridge is ready!
I/jxcore-log( 5218): 
,W/jxcore-log( 5218): JXcore engine is started
,I/chromium( 5218): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  240): DCD ON
,I/GAV2    ( 5204): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 5218): Toggling radios to true
I/jxcore-log( 5218): 
,D/BluetoothAdapter( 5218): enable(): BT is already enabled..!
,I/WifiManager( 5218): packageName : com.test.thalitest
I/WifiManager( 5218): setWifiEnabled : true
,I/WifiService(  760): setWifiEnabled: true pid=5218, uid=10179
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5218, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  760): Failed getting userId using ActivityManagerNative
W/WifiService(  760): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5218, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  760): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  760): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  760): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  760): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  760): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  760): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  760): disconnect: pid=5218, uid=10179
,I/jxcore-log( 5218): Radios toggled
I/jxcore-log( 5218): 
,I/jxcore-log( 5218): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5218): 
,I/wpa_supplicant( 1968): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5218): Perf Test app loaded loaded
I/jxcore-log( 5218): 
,I/jxcore-log( 5218): check test folder
I/jxcore-log( 5218): 
,I/jxcore-log( 5218): found test : ./testFindPeers.js
I/jxcore-log( 5218): 
,I/wpa_supplicant( 1968): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1968): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering(  760): interfaceLinkStateChanged wlan0, false
,D/Tethering(  760): interfaceStatusChanged wlan0, false
,D/Tethering(  760): InitialState.processMessage what=4
,E/Tethering(  760): No numeric data
,D/Tethering(  760): sendTetherStateChangedBroadcast 0, 0, 0
I/wpa_supplicant( 1968): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1968): Cmd 35605 not handled
E/wpa_supplicant( 1968): Cmd 35605 not handled
,I/wpa_supplicant( 1968): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/wpa_supplicant( 1968): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1968): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1968): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1968): First Scan Start
,I/wpa_supplicant( 1968): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering(  760): interfaceLinkStateChanged wlan0, false
,D/Tethering(  760): interfaceStatusChanged wlan0, false
,I/ConnectivityService(  760): defaultVal : 1, tetherEnabledInSettings : true
W/Settings(  760): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  760): ignore requestNetworkTransitionWakelock airplane:true
D/Tethering(  760): interfaceLinkStateChanged wlan0, false
D/Tethering(  760): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
V/NetworkStats(  760): performPollLocked(flags=0x1)
D/WifiP2pService(  760): InactiveState{ what=143375 }
D/WifiP2pService(  760): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  237): Clearing all IP addresses on wlan0
,V/NetworkStats(  760): performPollLocked() took 33ms
D/NtpTrustedTime(  760): currentTimeMillis() cache hit
D/NtpTrustedTime(  760): currentTimeMillis() cache hit
D/NtpTrustedTime(  760): currentTimeMillis() cache hit
I/jxcore-log( 5218): found test : ./testSendData.js
I/jxcore-log( 5218): 
,I/WifiTrafficPoller(  760): evaluateTrafficStatsPolling
D/ConnectivityService(  760): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  760): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  760): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  760): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  760): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  760): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  760): Attempting to switch to mobile
D/ConnectivityService(  760): Attempting to switch to BLUETOOTH_TETHER
,V/RouteController(  237): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-IconMerger( 1067): checkOverflow(336), More:false, Req:false Child:2
,I/SELinux ( 5384): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5384):  
I/wpa_supplicant( 1968): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1968): Skip scan - already scanning
,D/WifiP2pService(  760): InactiveState{ what=143375 }
,D/WifiP2pService(  760): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  237): RTNETLINK answers: No such process
,V/RouteController(  237): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController(  237): RTNETLINK answers: No such file or directory
,D/CommandListener(  237): Clearing all IP addresses on wlan0
,W/NetworkManagementService(  760): route cmd failed: 
W/NetworkManagementService(  760): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  760): '
W/NetworkManagementService(  760): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  760): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  760): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  760): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  760): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  760): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  760): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  760): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  760): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  760): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  760): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  237): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller(  760): evaluateTrafficStatsPolling
I/SELinux ( 5384): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5384):  
I/SELinux ( 5384):  
,I/SELinux ( 5384): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5384): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
E/dalvikvm( 5384): >>>>> Normal User
,E/dalvikvm( 5384): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5384): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/WifiStateMachine(  760): Error! unhandled message{ when=-86ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  760): Error! unhandled message{ when=-85ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  760): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  237): RTNETLINK answers: No such process
,V/RouteController(  237): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 5384): in addTimaSignatureService
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 5384): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5384): Added TimaKesytore provider
,D/NetUtils(  760): android_net_utils_resetConnections in env=0x747019f0 clazz=0x6bc00001 iface=wlan0 mask=0x3
D/ConnectivityService(  760): resetConnections(wlan0, 3)
,V/NativeCrypto( 1309): Read error: ssl=0x7c64aea0: I/O error during system call, Connection timed out
,I/chromium( 5218): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/NativeCrypto( 1309): SSL shutdown failed: ssl=0x7c64aea0: I/O error during system call, Broken pipe
,D/ConnectivityService(  760): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
V/NetworkStats(  760): updateIfacesLocked()
V/NetworkStats(  760): performPollLocked(flags=0x1)
V/NetworkStats(  760): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
V/NetworkStats(  760): performPollLocked() took 17ms
,I/System.out( 5384): Inside WakeupProvider
,I/System.out( 5384): Inside onCreate() of WakeupTriggerProvide
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,I/VlingoApplication( 5384): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5384): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5384): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1314): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1314): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5384): initQueue()
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1314): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1314): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  760): Killing 4424:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/Tethering(  760): Tethering got CONNECTIVITY_ACTION
D/Tethering(  760): MasterInitialState.processMessage what=3
I/ApplicationPolicy(  760): updateDataUsageMap
D/CaptivePortalTracker(  760): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  760): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  760): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  760): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  760): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
I/NetworkMonitor( 3895): type=WIFI subType= reason=null isConnected=false
D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_PushUtil( 5107): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5107): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5107): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5107): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 5107): noConnectivity : true
I/SELinux ( 5415): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5415):  
I/SELinux ( 5415): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5415):  
I/SELinux ( 5415):  
I/SELinux ( 5415): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5415): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5415): >>>>> Normal User
E/dalvikvm( 5415): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
E/SELinux ( 5415): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5415): in addTimaSignatureService
D/TimaKeyStoreProvider( 5415): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5415): Added TimaKesytore provider
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5415, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  760): Killing 4440:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
I/SELinux ( 5429): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5429):  
D/dalvikvm(  247): GC_EXPLICIT freed 43K, 49% free 9511K/18432K, paused 3ms+3ms, total 28ms
I/wpa_supplicant( 1968): nl80211: Received scan results (10 BSSes)
I/wpa_supplicant( 1968): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1968): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1968): Trying to associate with  'G700'
I/wpa_supplicant( 1968): Re-associate with C0.AA.48
I/wpa_supplicant( 1968): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/wpa_supplicant( 1968): Cmd 35609 not handled
D/Tethering(  760): interfaceLinkStateChanged wlan0, false
D/Tethering(  760): interfaceStatusChanged wlan0, false
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18432K, paused 2ms+3ms, total 21ms
I/SELinux ( 5429): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5429):  
I/SELinux ( 5429):  
I/SELinux ( 5429): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5429): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5429): >>>>> Normal User
E/dalvikvm( 5429): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18432K, paused 1ms+3ms, total 20ms
E/SELinux ( 5429): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5429): in addTimaSignatureService
D/TimaKeyStoreProvider( 5429): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5429): Added TimaKesytore provider
E/wpa_supplicant( 1968): Cmd 35605 not handled
E/wpa_supplicant( 1968): Cmd 35847 not handled
E/wpa_supplicant( 1968): Cmd 35848 not handled
E/wpa_supplicant( 1968): Cmd 35605 not handled
I/wpa_supplicant( 1968): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1968): Associated with C0.AA.48
I/wpa_supplicant( 1968): freq(2412) increment count 2
I/wpa_supplicant( 1968): meet head of list.
I/wpa_supplicant( 1968): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  760): interfaceLinkStateChanged wlan0, false
D/Tethering(  760): interfaceStatusChanged wlan0, false
D/Tethering(  760): interfaceLinkStateChanged wlan0, false
D/Tethering(  760): interfaceStatusChanged wlan0, false
D/Tethering(  760): interfaceLinkStateChanged wlan0, false
D/Tethering(  760): interfaceStatusChanged wlan0, false
D/Tethering(  760): interfaceLinkStateChanged wlan0, true
D/Tethering(  760): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1968): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1968): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1968): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1968): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
E/Tethering(  760): No numeric data
D/WifiNative(  760): callSECApiVoid - ID [50]
D/Tethering(  760): sendTetherStateChangedBroadcast 1, 0, 0
D/NtpTrustedTime(  760): currentTimeMillis() cache hit
I/ConnectivityService(  760): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  760): performPollLocked(flags=0x1)
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
D/Tethering(  760): interfaceLinkStateChanged wlan0, true
D/Tethering(  760): interfaceStatusChanged wlan0, true
D/Tethering(  760): interfaceLinkStateChanged wlan0, true
D/Tethering(  760): interfaceStatusChanged wlan0, true
D/Tethering(  760): interfaceLinkStateChanged wlan0, true
D/Tethering(  760): interfaceStatusChanged wlan0, true
D/Tethering(  760): interfaceLinkStateChanged wlan0, true
D/Tethering(  760): interfaceStatusChanged wlan0, true
D/NtpTrustedTime(  760): currentTimeMillis() cache hit
V/NetworkStats(  760): performPollLocked() took 35ms
D/NtpTrustedTime(  760): currentTimeMillis() cache hit
D/NtpTrustedTime(  760): currentTimeMillis() cache hit
D/WifiP2pService(  760): InactiveState{ what=143375 }
D/WifiP2pService(  760): P2pEnabledState{ what=143375 }
V/AlarmManager(  760): waitForAlarm result :4
V/AlarmManager(  760): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm(  760): GC_EXPLICIT freed 2859K, 59% free 23951K/58200K, paused 10ms+18ms, total 157ms
D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  760): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/UiModeManager(  760): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5429, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
D/STATUSBAR-IconMerger( 1067): checkOverflow(336), More:false, Req:false Child:2
I/ActivityManager(  760): Killing 4470:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
I/SELinux ( 5447): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5447):  
,I/SELinux ( 5447): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5447):  
I/SELinux ( 5447):  
,I/SELinux ( 5447): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5447): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5447): >>>>> Normal User
,E/dalvikvm( 5447): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5447): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5447): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5447): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5447): Added TimaKesytore provider
,I/dhcpcd  ( 5451): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5451): bssid match
,W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5447, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5447): KLMSValidator() : checkQATesting()
,E/SMD     (  240): DCD ON
,I/KLMS-2.3.201 : ( 5447): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450280784718
,I/KLMS-2.3.201 : ( 5447): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager(  760): Killing 4495:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5466): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5466):  
,D/FactoryTest( 4755): Not factory mode
,D/FactoryTest( 4755): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4755): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4755): still no open session command from host, so toast
W/ContextImpl( 4755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
V/ApplicationPolicy(  760): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/SELinux ( 5466): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5466):  
I/SELinux ( 5466):  
,I/SELinux ( 5466): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5466): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5466): >>>>> Normal User
,E/dalvikvm( 5466): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5466): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/CustomFrequencyManagerService(  760): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 760  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  760): mDVFSHelper.acquire()
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/TimaKeyStoreProvider( 5466): in addTimaSignatureService
,D/LockPatternUtils( 1067): isPcwEnable = null
,E/MTPRx   ( 4755): started activity for popup
,D/TimaKeyStoreProvider( 5466): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5466): Added TimaKesytore provider
,I/SQLiteSecureOpenHelper( 2100): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2100): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4755): PREF_DONT_ASK_AGAIN : false
,W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5466, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,D/SettingsReceiverActivity( 4755): dev.kiessupport is : TRUE
,D/SO_AGENT( 5466): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5466): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4038): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4038): [BDLM] already registered in spp
I/SA      ( 4038): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 4038): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4038): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4038): [OR] == isSIMCardReady false ==
I/SA      ( 4038): [SCU] == networkStateCheck == false
,I/SA      ( 4038): [OR] onReceive END
I/ActivityManager(  760): Killing 4617:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SELinux ( 5506): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5506):  
,I/SurfaceFlinger(  246): id=18 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4755): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4755): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4755): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4755): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4755): Remote Branch: 
I/Adreno-EGL( 4755): Local Patches: 
I/Adreno-EGL( 4755): Reconstruct Branch: 
,I/SELinux ( 5506): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5506):  
I/SELinux ( 5506):  
I/SELinux ( 5506): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/HWUI    ( 4755): EGLImpl-HWUI Protected EGL context created
,E/SELinux ( 5506): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5506): >>>>> Normal User
,E/dalvikvm( 5506): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5506): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/OpenGLRenderer( 4755): Enabling debug mode 0
,D/TimaKeyStoreProvider( 5506): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5506): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5506): Added TimaKesytore provider
,D/WifiP2pService(  760): InactiveState{ what=143375 }
,D/WifiP2pService(  760): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  760): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  760): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  760): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  760): evaluateTrafficStatsPolling
,D/WifiStateMachine(  760): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  760): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  760): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/WifiTrafficPoller(  760): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  760): mBoosterFLAG : 2
,I/WifiTrafficPoller(  760): current booster mode : BTCoexMode
D/ConnectivityService(  760): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  760): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  760): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/CustomFrequencyManagerService(  760): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 760  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  760): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/CustomFrequencyManagerService(  760): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 760  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/ConnectivityService(  760): handleConnectivityChange: setting default proxy info 
,V/RouteController(  237): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  237): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  237): RTNETLINK answers: No such file or directory
,V/RouteController(  237): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/sCloudBackupApp( 5506): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5506): Other Intent
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/ActivityManager(  760): Killing 4654:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,V/RouteController(  237): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,I/SELinux ( 5532): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5532):  
,V/RouteController(  237): RTNETLINK answers: No such process
,V/RouteController(  237): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,V/NetworkStats(  760): updateIfacesLocked()
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
I/SELinux ( 5532): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5532):  
I/SELinux ( 5532):  
,I/SELinux ( 5532): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/NetworkStats(  760): performPollLocked(flags=0x1)
,V/NetworkStats(  760): advisePersistThreshold() given 9223372036854775, clamped to 2097152
E/SELinux ( 5532): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5532): >>>>> Normal User
E/dalvikvm( 5532): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
E/SELinux ( 5532): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 5532): in addTimaSignatureService
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,V/NetworkStats(  760): performPollLocked() took 20ms
D/TimaKeyStoreProvider( 5532): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5532): Added TimaKesytore provider
,W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5532, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  760): Killing 4643:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/Headlines( 4091): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4091): getCountryCode(): countryCode = PL
,D/Headlines( 4091): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4091): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4091): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4091): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4091): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4091): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4091): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5550): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5550):  
,I/SELinux ( 5550): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5550):  
I/SELinux ( 5550):  
,I/SELinux ( 5550): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5550): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5550): >>>>> Normal User
,E/dalvikvm( 5550): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5550): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5550): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5550): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5550): Added TimaKesytore provider
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5550): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5550): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 5550): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5550): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5550): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 5550): Binding Chromium to the main looper Looper (main, tid 1) {42271100}
,I/chromium( 5550): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5550): Initializing chromium process, renderers=0
,W/chromium( 5550): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5550): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5550): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5550): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5550): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5550): Remote Branch: 
I/Adreno-EGL( 5550): Local Patches: 
I/Adreno-EGL( 5550): Reconstruct Branch: 
,I/NSApplication( 5550): Starting up...
,W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5550, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  760): Killing 4697:com.google.android.talk/u0a105 (adj 15): empty #43
D/QuickConnect[1.1][2] ( 3363): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3363): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3363): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a3270
,I/SELinux ( 5586): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5586):  
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/Tethering(  760): Tethering got CONNECTIVITY_ACTION
,D/LocSvc_java(  760): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  760): getAGpsConnectionInfo connType - 4
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  760): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/LocSvc_java(  760): ignore wifi update if we are not in OPENING or CLOSING
,I/SELinux ( 5586): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5586):  
I/SELinux ( 5586):  
,I/SELinux ( 5586): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5586): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5586): >>>>> Normal User
,E/dalvikvm( 5586): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5586): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/NetworkMonitor( 3895): type=WIFI subType= reason=null isConnected=true
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 5586): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5586): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5586): Added TimaKesytore provider
,D/RCPManagerService(  760): exchangeData() failure , invalid userId
,D/RCPManagerService(  760): exchangeData() failure , invalid userId
,D/RCPManagerService(  760): exchangeData() failure , invalid userId
,I/SELinux ( 5610): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5610):  
,D/RCPManagerService(  760): exchangeData() failure , invalid userId
,D/RCPManagerService(  760): exchangeData() failure , invalid userId
,D/RCPManagerService(  760): exchangeData() failure , invalid userId
I/ActivityManager(  760): Killing 3043:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,W/ActivityManager(  760): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5616): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5616):  
,I/SELinux ( 5610): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5610):  
I/SELinux ( 5610):  
,I/SELinux ( 5610): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5610): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5610): >>>>> Normal User
,E/dalvikvm( 5610): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5610): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5610): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5610): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5610): Added TimaKesytore provider
,I/ActivityManager(  760): Killing 4786:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 5616): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5616):  
I/SELinux ( 5616):  
,I/SELinux ( 5616): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5616): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5616): >>>>> Normal User
,E/dalvikvm( 5616): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5616): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5616): in addTimaSignatureService
,D/BadgeProvider( 5610): onCreate
,D/BadgeProvider( 5610): DatabaseHelper
,D/TimaKeyStoreProvider( 5616): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5616): Added TimaKesytore provider
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5610, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5610): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/CustomFrequencyManagerService(  760): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 760  tag : ACTIVITY_RESUME_BOOSTER@9
,D/Launcher.Model( 1247): reloadBadges entered.
,D/BadgeProvider( 5610): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5610): sendNotify, [notify] : null
D/BadgeProvider( 5610): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5610): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5610): update, [UpdateCount] : 1
,W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5616, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/hcjo    ( 4191): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4191): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4191): exit::IDLE
,D/InitializeManagerStateMachine( 4191): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4191): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4191): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4191): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4191): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4191): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4191): entry::SUCCESS
,D/hcjo    ( 4191): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4191): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4191): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4191): exit::SUCCESS
,D/InitializeManagerStateMachine( 4191): entry::IDLE
I/ActivityManager(  760): Killing 4806:com.wssyncmldm/1000 (adj 15): empty #43
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,D/Headlines( 4091): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 4091): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4091): Breath 865 latestRequest time : 1450280785524 current time : 1450280786389
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1314): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1314): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1314): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1314):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1314): showing allowed
,D/NearbySettings( 1314): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1314): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 5107): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5107): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5107): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5107): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  246): id=19 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  760): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=760
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/VacuumService( 1219): Vacuum at: now=1450280786571 tag=VacuumService
,I/KLMS-2.3.201 : ( 5447): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5447): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450280786629
,I/KLMS-2.3.201 : ( 5447): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5466): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5466): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/LocationTagReadyService( 2562): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2562): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2562): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2562): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 5642): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5642):  
,I/GallerySearchProvider( 2347): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5646): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5646):  
,I/SELinux ( 5642): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5642):  
I/SELinux ( 5642):  
,I/SELinux ( 5642): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5642): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5642): >>>>> Normal User
,E/dalvikvm( 5642): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5642): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5642): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5642): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5642): Added TimaKesytore provider
I/SELinux ( 5646): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5646):  
I/SELinux ( 5646):  
,I/SELinux ( 5646): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5646): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5646): >>>>> Normal User
,E/dalvikvm( 5646): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5646): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5646): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5646): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5646): Added TimaKesytore provider
,I/SA      ( 4038): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4038): [BDLM] already registered in spp
,I/SA      ( 4038): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4038): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4038): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4038): [OR] == isSIMCardReady false ==
,I/SA      ( 4038): [SCU] == networkStateCheck == true
I/SA      ( 4038): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4038): isChinaCountryCode : false
,I/SA      ( 4038): [OR] == networkStateCheck true ==
,I/SA      ( 4038): [OR] GetMyCountryZoneTask
,I/SA      ( 4038): [OR] onReceive END
,I/SA      ( 4038): [SRS] prepareGetMyCountryZone
,I/SA      ( 4038): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4038): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5506): Other Intent
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,V/KVNProvider( 5646): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5646): getFindoCursor query string : 
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      ( 4038): [TPMU] GetMccFromDB : null
,I/SA      ( 4038): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4038): [TPM] isNoProxy(default) : true
,V/KVNProvider( 5646): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4038): [RC New] Execute method=[GET] start
,D/Headlines( 4091): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4091): getCountryCode(): countryCode = PL
,D/Headlines( 4091): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4091): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4091): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4091): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4091): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4091): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4091): requestUpdateNewsWelcomeCard !!! no welcome card
,I/ActivityManager(  760): Killing 4631:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
D/QuickConnect[1.1][2] ( 3363): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3363): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3363): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a3270
D/RCPManagerService(  760): exchangeData() failure , invalid userId
D/RCPManagerService(  760): exchangeData() failure , invalid userId
,D/hcjo    ( 4191): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4191): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4191): exit::IDLE
,D/InitializeManagerStateMachine( 4191): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4191): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 4191): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4191): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4191): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4191): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4191): entry::SUCCESS
,D/hcjo    ( 4191): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4191): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4191): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4191): exit::SUCCESS
,D/InitializeManagerStateMachine( 4191): entry::IDLE
,I/SA      ( 4038): [RC New] [v2liruge] api execute + 641
,I/SA      ( 4038): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4038): AsyncTask #2 calls detatch()
,I/SA      ( 4038): [TPMU] getNetworkMcc : 
,I/SA      ( 4038): [SCU] saveMccToPreferece Start
,I/SA      ( 4038): [SCU] RegionMCC : 260
,I/SA      ( 4038): [SSP] query invoked
,I/SA      ( 4038): [TPMU] GetMccFromDB : null
I/SA      ( 4038): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4038): [SCU] saveMccToPreferece End
,I/SA      ( 4038): [RC New] executeRequest [v2liruge] end. 662
I/SA      ( 4038): [RC New] Execute end
,I/SA      ( 4038): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4038): [OR] GetMyCountryZoneTask Success
,D/SSRMv2:SIOP(  760): SIOP:: AP = 320, Delta = 10
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5218): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5218): 
,W/WifiP2pStateTracker(  760): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  760): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  760):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  760): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  760): updateSourceRoutes : no source routing conditions
,E/WifiStateMachine(  760): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/HarmonyEASService(  760): Updating for all 1
,I/ActivityManager(  760): Killing 4219:com.android.calendar/u0a142 (adj 15): empty #43
,I/SurfaceFlinger(  246): id=19 Removed Uoast (12/13)
,I/SurfaceFlinger(  246): id=19 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  760): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=760 (0x0)
,D/PowerManagerService(  760): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=760, ws=WorkSource{1000}) (elapsedTime=3527)
,E/SMD     (  240): DCD ON
,I/GAV2    ( 5550): Thread[GAThread,5,main]: No campaign data found.
,D/AmoledAdjustTimer(  760): prevTemp = 289, currTemp = 291, prevStep = 4, currStep = 4
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5107): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5107): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5107): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5107): ================================================
,I/CSTORAGE( 5107):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5107): ================================================,
D/dalvikvm( 5107): No JNI_OnLoad found in /system/lib/libterrier.so 0x4259d388, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5107): [GetString-S]
,I/terrier ( 5107): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5107): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5107): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5107): Loaded image: APP id = 4
,D/QSEECOMAPI: ( 5107): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5107): QSEECom_shutdown_app, app_id = 4
E/terrier ( 5107): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5107): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5107): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5107): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5107): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5107): [ensureRegistration] - No Samsung account
,V/AlarmManager(  760): waitForAlarm result :4
,V/AlarmManager(  760): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SMD     (  240): DCD ON
,D/Finsky  ( 3687): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3687): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  760): mCoverManager.getCoverState() : true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/CaptivePortalTracker(  760): DelayedCaptiveCheckState{ when=0 what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  760): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  760): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  760): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  760): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  760): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  760): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  760): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4191): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4191): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4191): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4191): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4191): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4191): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4191): entry::IDLE
,E/SMD     (  240): DCD ON
,D/PreloadUpdateManagerStateMachine( 4191): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4191): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4191): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4191): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4191): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4191): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4191): entry::IDLE
,D/SSRMv2:SIOP(  760): SIOP:: AP = 310, Delta = -10
,E/Watchdog(  760): !@Sync 4
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 291, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService(  760): [PWL] Off : 75s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,D/Headlines( 4091): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4091): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4091): Breath 19997 latestRequest time : 1450280786885 current time : 1450280806882
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = -10
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,E/SMD     (  240): DCD ON
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 292, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 5
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService(  760): [PWL] Off : 105s ago
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :4
,V/AlarmManager(  760): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 4091): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4091): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4091): Breath 57750 latestRequest time : 1450280786885 current time : 1450280844635
,E/SMD     (  240): DCD ON
,D/dalvikvm(  760): GC_EXPLICIT freed 3309K, 59% free 23888K/58200K, paused 37ms+19ms, total 251ms
,I/PhenotypeConfigurator( 1219): Scheduling Phenotype for one-off execution 1111 seconds from now (1450280845508)
,D/GetConfigurationSnapshotOperation( 1219): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1219): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1219): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1219): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1219): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1219): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  760): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1219): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1219): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1219): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1219): Thread-109(HTTPLog):isShipBuild true
,I/System.out( 1219): Thread-109(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1219): GC_CONCURRENT freed 1532K, 36% free 11863K/18432K, paused 8ms+8ms, total 77ms
,D/LocationManagerService(  760): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 289, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 6
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,D/Headlines( 4091): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4091): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4091): Breath 79995 latestRequest time : 1450280786885 current time : 1450280866881
,I/PowerManagerService(  760): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 7
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,D/Headlines( 4091): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4091): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4091): Breath 109995 latestRequest time : 1450280786885 current time : 1450280896880
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,I/PowerManagerService(  760): [PWL] Off : 180s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 8
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,D/Headlines( 4091): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4091): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4091): Breath 139982 latestRequest time : 1450280786885 current time : 1450280926867
,D/Headlines( 4091): stop 
,D/Headlines( 4091): Breath.onDestroy : 
,I/ActivityManager(  760): Killing 4412:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 9
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService(  760): [PWL] Off : 225s ago
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5218): Connected to the server!
I/jxcore-log( 5218): 
,I/chromium( 5218): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  760): initializing...
,I/TLC_TIMA_PKM_initialize(  760): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  760): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  760): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  760): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  760): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  760): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  760): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  760): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  760): App is not loaded in QSEE
,D/QSEECOMAPI: (  760): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  760): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  760): Trustlet response is completed
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 10
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService(  760): [PWL] Off : 275s ago
,V/AlarmManager(  760): waitForAlarm result :4
,V/AlarmManager(  760): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5762): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5762):  
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/dalvikvm(  247): GC_EXPLICIT freed 43K, 49% free 9511K/18432K, paused 19ms+24ms, total 223ms
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18432K, paused 23ms+22ms, total 172ms
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 5762): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5762):  
I/SELinux ( 5762):  
,I/SELinux ( 5762): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5762): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5762): >>>>> Normal User
,E/dalvikvm( 5762): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5762): [DEBUG] seapp_context_lookup: seinfoCategory = default
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18432K, paused 20ms+34ms, total 172ms
,D/TimaKeyStoreProvider( 5762): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5762): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5762): Added TimaKesytore provider
,W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=5762, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  760): Killing 4597:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 11
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 12
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0,
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 279, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 330s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 13
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 14
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 390s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 15
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  760): !@Sync 16
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService(  760): [PWL] Off : 455s ago
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 17
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 18
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 19
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/dalvikvm(  760): GC_CONCURRENT freed 3514K, 59% free 23875K/58200K, paused 22ms+51ms, total 589ms
,I/PowerManagerService(  760): [PWL] Off : 525s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  760): !@Sync 20
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  760): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 21
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,I/SensorManagerA(  760): getReportingMode :: sensor.mType = 5
,D/LightsService(  760): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  760): LightSensor setDelay = 200000000
D/Sensors (  760): LightSensor setSensorDelay = 200000000
D/Sensors (  760): Light sensor flush: not enabled 0
D/Sensors (  760): LightSensor enable = 1
D/Sensors (  760): LightSensor enableSensor = 1
D/SensorManager(  760): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService(  760): [PWL] Off : 600s ago
,D/Sensors (  760): LightSensor enable = 0
,D/Sensors (  760): LightSensor enableSensor = 0
,D/SensorManager(  760): unregisterListener ::   
D/LightsService(  760): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  760): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 22
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  760): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  760): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
V/AlarmManager(  760): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 23
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 24
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 680s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 25
,E/SMD     (  240): DCD ON
D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 26
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 27
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  760): [PWL] Off : 765s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 28
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 29
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  760): !@Sync 30
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService(  760): [PWL] Off : 855s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 31
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 32
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 33
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  760): [PWL] Off : 950s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 34
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/dalvikvm(  760): GC_CONCURRENT freed 3502K, 59% free 23861K/57984K, paused 32ms+50ms, total 588ms
,E/Watchdog(  760): !@Sync 35
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 36
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  760): [PWL] Off : 1050s ago
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 37
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 38
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 39
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  760): !@Sync 40
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService(  760): [PWL] Off : 1155s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  760): !@Sync 41
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,I/SensorManagerA(  760): getReportingMode :: sensor.mType = 5
,D/Sensors (  760): LightSensor setDelay = 200000000
,D/Sensors (  760): LightSensor setSensorDelay = 200000000
,D/Sensors (  760): Light sensor flush: not enabled 0
,D/Sensors (  760): LightSensor enable = 1
,D/LightsService(  760): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  760): LightSensor enableSensor = 1
D/SensorManager(  760): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  760): LightSensor enable = 0
,D/Sensors (  760): LightSensor enableSensor = 0
,D/LightsService(  760): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  760): unregisterListener ::   
D/LightsService(  760): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 42
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  760): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  760): <AppSync3 Whitelist>
,V/AlarmManager(  760): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  760): !@Sync 43
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  760): !@Sync 44
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  760): !@Sync 45
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  760): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  760): !@Sync 46
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 47
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 1380s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 48
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 49
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 50
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 51
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/dalvikvm(  760): GC_CONCURRENT freed 3490K, 59% free 23876K/57984K, paused 24ms+49ms, total 536ms
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 1500s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 52
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 53
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 54
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 55
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 56
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  760): stay LED for fully charged
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
E/SMD     (  240): DCD ON
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 57
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 58
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 59
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  760): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  760): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  760): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  760): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  760): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 60
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  760): [PWL] Off : 1755s ago
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  760): Prepared write state in 148ms
,I/ProcessStatsService(  760): Prepared write state in 113ms
,I/ProcessStatsService(  760): Pruning old procstats: /data/system/procstats/state-2015-12-16-02-32-56.bin
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 61
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :4
,V/NetworkStats(  760): performPollLocked(flags=0x3)
D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
V/AlarmManager(  760): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
V/NetworkStats(  760): performPollLocked() took 233ms
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,D/NtpTrustedTime(  760): currentTimeMillis() cache hit
,I/ActivityManager(  760): Killing 4557:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1802s
,I/SensorManagerA(  760): getReportingMode :: sensor.mType = 5
,D/Sensors (  760): LightSensor setDelay = 200000000
,D/Sensors (  760): LightSensor setSensorDelay = 200000000
,D/LightsService(  760): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  760): Light sensor flush: not enabled 0
D/Sensors (  760): LightSensor enable = 1
D/Sensors (  760): LightSensor enableSensor = 1
D/SensorManager(  760): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  760): LightSensor enable = 0
,D/LightsService(  760): [SvcLED]  onSensorChanged::light value = 0
D/Sensors (  760): LightSensor enableSensor = 0
,D/SensorManager(  760): unregisterListener ::   
D/LightsService(  760): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1756): Aggregate from 1450280711641 (log), 1450280711641 (data)
,V/NativeCrypto( 1309): SSL shutdown failed: ssl=0x7bbd2760: I/O error during system call, Connection timed out
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  760): !@Sync 62
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  760): waitForAlarm result :8
,V/AlarmManager(  760): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  760): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  760): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
V/AlarmManager(  760): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,E/Watchdog(  760): !@Sync 63
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/BatteryService(  760): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  760): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  760): stay LED for fully charged
,D/UiModeManager(  760): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
,TIME-OUT KILL (timeout was 1800000ms),D/AmoledAdjustTimer(  760): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
E/SMD     (  240): DCD ON
E/SMD     (  240): DCD ON
D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  760): mCoverManager.getCoverState() : true
D/BatteryService(  760): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
E/Watchdog(  760): !@Sync 64
E/SMD     (  240): DCD ON
E/SMD     (  240): DCD ON
D/SSRMv2:SIOP(  760): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  760): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
E/SMD     (  240): DCD ON
D/AndroidRuntime( 6145): 
D/AndroidRuntime( 6145): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6145): CheckJNI is OFF
D/AndroidRuntime( 6145): setted country_code = Poland
D/AndroidRuntime( 6145): setted countryiso_code = PL
D/AndroidRuntime( 6145): setted sales_code = XEO
D/AndroidRuntime( 6145): readGMSProperty: start
D/AndroidRuntime( 6145): readGMSProperty: already setted!!
D/AndroidRuntime( 6145): readGMSProperty: end
D/AndroidRuntime( 6145): addProductProperty: start
D/dalvikvm( 6145): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6145): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6145): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6145): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6145): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6145): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6145): failed to load memtrack module: -2
D/BatteryService(  760): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
D/BatteryService(  760): stay LED for fully charged
D/BatteryService(  760): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  760): mCoverManager.getCoverState() : true
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
D/dalvikvm( 6145): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6145): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  760): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  760): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  760): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  760): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  760): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  760): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  760): START PACKAGE DELETE: observer{1131021832}
D/PackageManager(  760): pkg{<packageName>}
D/PackageManager(  760): user{0}
D/PackageManager(  760): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  760): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  760): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  760): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  760): getApplicationUninstallationEnabled
D/ApplicationPolicy(  760): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  760): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  760): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  760): Killing 5218:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/ActivityManager(  760): Killing 5384:com.vlingo.midas/u0a33 (adj 15): empty for 1821s
I/ActivityManager(  760): Killing 5447:com.samsung.klmsagent/u0a18 (adj 15): empty for 1821s
D/dalvikvm(  760): GC_CONCURRENT freed 3561K, 59% free 23931K/57984K, paused 13ms+12ms, total 194ms
D/dalvikvm(  760): WAIT_FOR_CONCURRENT_GC blocked 51ms
D/dalvikvm(  760): WAIT_FOR_CONCURRENT_GC blocked 47ms
W/InputDispatcher(  760): channel ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  760): channel ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  760): Attempted to unregister already unregistered input channel
I/SurfaceFlinger(  246): id=17 Removed NainActivit (7/12)
I/ActivityManager(  760): Killing 5429:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1821s
I/ActivityManager(  760): Killing 3946:com.sec.android.diagmonagent/1000 (adj 15): empty for 1822s
I/ActivityManager(  760): Killing 5415:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1822s
I/ActivityManager(  760): Killing 3895:com.google.android.music:main/u0a122 (adj 15): empty for 1822s
I/ActivityManager(  760): Killing 5107:com.sec.pcw.device/1000 (adj 15): empty for 1822s
I/ActivityManager(  760): Killing 1314:com.android.settings/1000 (adj 15): empty for 1822s
I/ActivityManager(  760): Killing 5610:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1822s
I/ActivityManager(  760): Killing 5330:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1830s
I/WindowState(  760): WIN DEATH: Window{423f8fa8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  246): id=17 Removed NainActivit (-2/12)
I/ActivityManager(  760): Killing 5318:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1830s
I/ActivityManager(  760): Killing 5301:com.samsung.helphub/1000 (adj 15): empty for 1830s
I/ActivityManager(  760): Killing 5287:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1830s
I/ActivityManager(  760): Killing 5261:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1830s
I/ActivityManager(  760): Killing 5204:com.google.android.apps.docs/u0a90 (adj 15): empty for 1831s
I/ActivityManager(  760): Killing 5185:com.sec.android.service.cm/u0a78 (adj 15): empty for 1831s
I/ActivityManager(  760): Killing 4682:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1831s
I/ActivityManager(  760): Killing 4331:com.android.mms/u0a48 (adj 15): empty for 1831s
I/ActivityManager(  760): Killing 5152:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1831s
I/ActivityManager(  760): Killing 4239:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1832s
I/ActivityManager(  760): Killing 5121:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1832s
I/ActivityManager(  760): Killing 5093:com.android.musicfx/u0a24 (adj 15): empty for 1833s
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=17 Removed NainActivit (-2/12)
I/ActivityManager(  760): Killing 5081:com.samsung.groupcast/u0a15 (adj 15): empty for 1833s
I/ActivityManager(  760): Killing 5066:com.google.android.partnersetup/u0a14 (adj 15): empty for 1833s
I/ActivityManager(  760): Killing 5048:com.sec.android.inputmethod/1000 (adj 15): empty for 1833s
I/ActivityManager(  760): Killing 4990:com.android.defcontainer/u0a6 (adj 15): empty for 1833s
D/dalvikvm(  760): WAIT_FOR_CONCURRENT_GC blocked 111ms
D/CountryDetector(  760): No listener is left
W/PackageSettings(  760): Skipping PackageSetting{42655828 com.example.hello/10181} due to missing metadata
D/PackageManager(  760): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager(  760): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1067): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3363): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "sms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6176): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6176):  
D/RCPManagerService(  760): PackageReceiver onReceive()
I/FPMS_FingerprintManagerService( 1086): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 1405): GC_EXPLICIT freed 4301K, 46% free 10030K/18432K, paused 3ms+4ms, total 66ms
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "smsto"
I/HarmonyEASService(  760): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "mms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6176): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6176):  
I/SELinux ( 6176):  
I/SELinux ( 6176): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6176): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6176): >>>>> Normal User
E/dalvikvm( 6176): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6176): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6176): in addTimaSignatureService
D/TimaKeyStoreProvider( 6176): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6176): Added TimaKesytore provider
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "mmsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2179): GC_EXPLICIT freed 1028K, 39% free 11275K/18432K, paused 4ms+6ms, total 148ms
D/dalvikvm( 1756): GC_EXPLICIT freed 855K, 34% free 12256K/18432K, paused 4ms+5ms, total 158ms
W/SQLiteConnectionPool( 1756): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "sms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "smsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "mms"
I/SurfaceFlinger(  246): id=20 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  760): Package has changed for user 0
D/EnterpriseDeviceManagerService(  760): Admin package name: com.google.android.gms
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=6176, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "mmsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6176): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6176): ELMEngine.ELMEngine( context ).
D/elm:14132( 6176): MDMBridge.setEnterpriseBridge()
D/elm:14132( 6176): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/SELinux ( 6189): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6189):  
D/elm:14132( 6176): ElmAgentService : onCreate()
D/elm:14132( 6176): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6176): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6176): MDMBridge.getInstance()
D/elm:14132( 6176): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6176): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6176): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 6176): ElmAgentService : onDestroy().
D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  760): removePackageParticipantsLocked: uid=10179 #1
I/ActivityManager(  760): Killing 5466:com.sec.android.soagent/u0a37 (adj 15): empty for 1822s
I/SELinux ( 6189): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6189):  
I/SELinux ( 6189):  
I/SELinux ( 6189): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6189): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6189): >>>>> Normal User
E/dalvikvm( 6189): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6189): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 6189): in addTimaSignatureService
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 6189): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6189): Added TimaKesytore provider
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(  760): GC_EXPLICIT freed 2133K, 59% free 24035K/57984K, paused 21ms+16ms, total 275ms
D/PackageManager(  760): delete sourFile : 
D/PackageManager(  760): delete native library directory: 
D/PackageManager(  760): return delete result to caller: 1131021832
D/AndroidRuntime( 6145): Shutting down VM
D/dalvikvm( 6145): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+1ms, total 2ms
D/PackageManager(  760): returnCode: 1
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "sms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "smsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "mms"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  760):   Action: "android.intent.action.SENDTO"
I/PackageManager(  760):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  760):   Scheme: "mmsto"
I/PackageManager(  760): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  760): Permission Denial: getCurrentUser() from pid=6189, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 6189): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42595b60, skipping init
I/SecureStorage( 6189): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6189): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  377): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6189
I/SecureStorage(  377): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6189): [INFO]: SPID(0x00000000)SS Daemon is running
D/Launcher( 1247): onRestart, Launcher: 1113835464
D/Launcher( 1247): onStart, Launcher: 1113835464
D/Launcher.HomeView( 1247): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1447): [237392/5] SurfaceWidget drawing first frame
I/SecureStorage( 6189): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  377): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6189
I/SecureStorage(  377): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
I/SurfaceFlinger(  246): id=21 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  760): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  760): onPackageRemoved : com.test.thalitest
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/UsbSettingsManager(  760): clearDefaults: com.test.thalitest
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/InputReader(  760): Processing first event
W/ApplicationsProvider( 1405): Could not fetch usage stats
W/ApplicationsProvider( 1405): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1405): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1405): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1405): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1405): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1405): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1405): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1405): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1405): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1405): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SMD     (  240): DCD ON

```
