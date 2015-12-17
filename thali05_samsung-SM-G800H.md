#### Test 539786639813e59_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5233, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
I/PowerManagerService(  770): [PWL] Off : 50s ago
--------- beginning of /dev/log/main
E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5233): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5233): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  770): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
I/SA      ( 4056): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4056): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4056): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4363): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2168): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4709): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5264): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5264):  
I/SELinux ( 5264): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5264):  
I/SELinux ( 5264):  
I/SELinux ( 5264): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5264): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5264): >>>>> Normal User
E/dalvikvm( 5264): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5264): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/IcingCorporaProvider( 2168): UpdateCorporaTask done [took 101 ms] updated apps [took 101 ms] 
D/TimaKeyStoreProvider( 5264): in addTimaSignatureService
D/TimaKeyStoreProvider( 5264): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5264): Added TimaKesytore provider
I/ActivityManager(  770): Killing 3990:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/CapabilityManagerService New( 5264): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5264, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5278): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5278):  
I/ActivityManager(  770): Killing 4291:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5278): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5278):  
I/SELinux ( 5278):  
I/SELinux ( 5278): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5278): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5278): >>>>> Normal User
E/dalvikvm( 5278): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5278): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5278): in addTimaSignatureService
D/TimaKeyStoreProvider( 5278): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5278): Added TimaKesytore provider
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5278, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5312): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5312):  
W/GAV2    ( 5278): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5312): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5312):  
I/SELinux ( 5312):  
I/SELinux ( 5312): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5312): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5312): >>>>> Normal User
E/dalvikvm( 5312): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5312): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5312): in addTimaSignatureService
D/TimaKeyStoreProvider( 5312): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5312): Added TimaKesytore provider
D/PackageIntentReceiver( 5312): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5312): Not GearManger package! 
I/SELinux ( 5332): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5332):  
I/ActivityManager(  770): Killing 4003:com.sec.android.soagent/u0a37 (adj 15): empty #43
D/AndroidRuntime( 5296): 
D/AndroidRuntime( 5296): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5296): CheckJNI is OFF
D/AndroidRuntime( 5296): setted country_code = Poland
D/AndroidRuntime( 5296): setted countryiso_code = PL
D/AndroidRuntime( 5296): setted sales_code = XEO
D/AndroidRuntime( 5296): readGMSProperty: start
D/AndroidRuntime( 5296): readGMSProperty: already setted!!
D/AndroidRuntime( 5296): readGMSProperty: end
D/AndroidRuntime( 5296): addProductProperty: start
I/SELinux ( 5332): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5332):  
I/SELinux ( 5332):  
I/SELinux ( 5332): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm( 5296): Trying to load lib libjavacore.so 0x0
E/SELinux ( 5332): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5332): >>>>> Normal User
E/dalvikvm( 5332): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
D/dalvikvm( 5296): Added shared lib libjavacore.so 0x0
E/SELinux ( 5332): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm( 5296): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5296): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5296): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/SSRMv2:SIOP(  770): SIOP:: AP = 310, Delta = 0
D/TimaKeyStoreProvider( 5332): in addTimaSignatureService
D/TimaKeyStoreProvider( 5332): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5332): Added TimaKesytore provider
D/MagazineService Version( 5332): Magazine-Channel: 13
D/MagazineService Version( 5332): Magazine-Provider: 13
D/MagazineService Version( 5332): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5332): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5332): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5332, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5332): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5352): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5352):  
D/MagazineService::MagazineService( 5332): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  770): Killing 4400:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
E/memtrack( 5296): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5296): failed to load memtrack module: -2
I/SELinux ( 5352): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5352):  
I/SELinux ( 5352):  
I/SELinux ( 5352): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5352): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5352): >>>>> Normal User
E/dalvikvm( 5352): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5352): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/GAV2    ( 5278): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  770): Killing 4415:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
D/TimaKeyStoreProvider( 5352): in addTimaSignatureService
D/TimaKeyStoreProvider( 5352): Cannot add TimaSignature Service, License check Failed
D/dalvikvm( 5296): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/ActivityThread( 5352): Added TimaKesytore provider
D/AndroidRuntime( 5296): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy(  770): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  770): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  770): mDVFSHelper.acquire()
I/SELinux ( 5368): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5368):  
D/LockPatternUtils( 1069): isPcwEnable = null
D/AndroidRuntime( 5296): Shutting down VM
D/dalvikvm( 5296): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
I/SELinux ( 5372): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5372):  
I/ActivityManager(  770): Killing 4427:com.sec.esdk.elm/u0a94 (adj 15): empty #43
I/SELinux ( 5368): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5368):  
I/SELinux ( 5368):  
I/SELinux ( 5368): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5368): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5368): >>>>> Normal User
E/dalvikvm( 5368): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5368): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5368): in addTimaSignatureService
D/TimaKeyStoreProvider( 5368): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5368): Added TimaKesytore provider
I/SELinux ( 5372): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5372):  
I/SELinux ( 5372):  
I/SELinux ( 5372): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5372): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5372): >>>>> Normal User
E/dalvikvm( 5372): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = false on instance = 1
E/SELinux ( 5372): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/LockPatternUtils( 1069): isPcwEnable = null
D/SurfaceWidgetView( 1254): destroyHardwareResources():1125755128
D/TimaKeyStoreProvider( 5372): in addTimaSignatureService
D/TimaKeyStoreProvider( 5372): Cannot add TimaSignature Service, License check Failed
I/SQLiteSecureOpenHelper( 2126): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2126): getDatabaseLocked(b,b,pwd)...
D/ActivityThread( 5372): Added TimaKesytore provider
I/SurfaceFlinger(  249): id=7 Removed Mauncher (7/12)
I/SurfaceFlinger(  249): id=7 Removed Mauncher (-2/12)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/Launcher( 1254): onTrimMemory. Level: 20
I/SurfaceFlinger(  249): id=13 Removed CatteryCove (7/11)
I/SurfaceFlinger(  249): id=13 Removed CatteryCove (-2/11)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5368, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5372, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5368, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 5372): Package not found : com.sec.android.app.kidshome
V/WebViewChromium( 5368): Binding Chromium to the background looper Looper (main, tid 1) {4226e2c0}
I/chromium( 5368): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5368): Initializing chromium process, renderers=0
I/ActivityManager(  770): Killing 3587:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
I/SELinux ( 5395): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5395):  
,I/Adreno-EGL( 5368): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5368): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5368): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5368): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5368): Remote Branch: 
I/Adreno-EGL( 5368): Local Patches: 
I/Adreno-EGL( 5368): Reconstruct Branch: 
,W/chromium( 5368): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/SELinux ( 5395): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5395):  
I/SELinux ( 5395):  
,I/SELinux ( 5395): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5395): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5395): >>>>> Normal User
,E/dalvikvm( 5395): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5395): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5395): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5395): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5395): Added TimaKesytore provider
,I/dalvikvm( 5368): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5368): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5368): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5368): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5368): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5368): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5368): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5368): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5368): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5368): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5368): VFY: replacing opcode 0x6f at 0x001a
,I/ActivityManager(  770): Killing 4454:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
W/dalvikvm( 5368): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5368): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5368): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5368): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5368): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5368): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5368): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5368): CordovaWebView is running on device made by: samsung
,D/Finsky  ( 3684): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 1788): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1788): Loading module com.google.android.gms.games from APK com.google.android.play.games
,I/dalvikvm( 1788): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1788): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1788): VFY: replacing opcode 0x6e at 0x0053
,D/ChimeraModuleLdr( 1788): Loading module APK com.google.android.play.games
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5368): EGLImpl-HWUI Protected EGL context created
I/dalvikvm( 1788): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1788): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1788): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1788): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1788): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1788): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1788): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1788): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/OpenGLRenderer( 5368): Enabling debug mode 0
,W/AwContents( 5368): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  770): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  770): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  770): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/dalvikvm( 1788): GC_CONCURRENT freed 2047K, 38% free 11834K/18968K, paused 8ms+12ms, total 133ms
,D/dalvikvm( 1788): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/ChimeraCfgMgr( 1788): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1788): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1788): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1788): Submit a task: k
,D/ChimeraCfgMgr( 1788): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1788): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/BaseAppContext( 1788): Using Auth Proxy for data requests.
,W/BaseAppContext( 1788): Using Auth Proxy for data requests.
,D/k       ( 1788): Processing package: com.test.thalitest
,D/JsMessageQueue( 5368): Set native->JS mode to OnlineEventsBridgeMode
,W/BaseAppContext( 1788): Using Auth Proxy for data requests.
D/GassUtils( 1788): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1788): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1788): Using Auth Proxy for data requests.
,W/BaseAppContext( 1788): Using Auth Proxy for data requests.
,W/BaseAppContext( 1788): Using Auth Proxy for data requests.
,W/BaseAppContext( 1788): Using Auth Proxy for data requests.
,D/dalvikvm( 5368): Trying to load lib /data/app-lib/com.test.thalitest-57/libjxcore.so 0x42594fc0
,D/dalvikvm( 5368): Added shared lib /data/app-lib/com.test.thalitest-57/libjxcore.so 0x42594fc0
D/jxcore_app_log( 5368): JniHelper::setJavaVM(0x416d5528), pthread_self() = 2032675320
,D/JX-Cordova( 5368): jxcore cordova android initializing
,W/dalvikvm( 1788): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1788): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1788): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1788): VFY: replacing opcode 0x6e at 0x000e
,W/dalvikvm( 1788): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1788): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1788): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1788): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1788): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1788): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1788): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1788): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1788): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1788): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 1788): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1788): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1788): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1788): cleanUpNonGplusAccounts done.
,W/dalvikvm( 1788): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1788): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1788): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5368): GC_CONCURRENT freed 4918K, 33% free 12772K/18968K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 5368): WAIT_FOR_CONCURRENT_GC blocked 19ms
,E/SMD     (  243): DCD ON
,D/CustomFrequencyManagerService(  770): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  tag : ACTIVITY_RESUME_BOOSTER@9
,D/dalvikvm( 5368): GC_FOR_ALLOC freed 4732K, 28% free 15759K/21788K, paused 32ms, total 32ms
,I/Icing   ( 1788): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1788): GC_CONCURRENT freed 1216K, 34% free 12571K/18968K, paused 4ms+6ms, total 39ms
,W/SQLiteConnectionPool( 1788): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Icing   ( 1788): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/dalvikvm( 5368): GC_FOR_ALLOC freed 5135K, 32% free 16791K/24516K, paused 35ms, total 35ms
,I/dalvikvm-heap( 5368): Grow heap (frag case) to 22.039MB for 2511452-byte allocation
,D/dalvikvm( 5368): GC_FOR_ALLOC freed 3809K, 36% free 17481K/26972K, paused 33ms, total 33ms
,D/dalvikvm( 5368): GC_FOR_ALLOC freed 1248K, 36% free 17383K/26972K, paused 31ms, total 31ms
,W/jxcore-log( 5368): Initializing JXcore engine
,W/jxcore-log( 5368): JXcore engine is ready
,W/jxcore-log( 5368): Starting JXcore engine
,W/jxcore-log( 5368): Platform android
W/jxcore-log( 5368): 
,W/jxcore-log( 5368): Process ARCH arm
W/jxcore-log( 5368): 
,I/jxcore-log( 5368): JXcore Cordova bridge is ready!
I/jxcore-log( 5368): 
,W/jxcore-log( 5368): JXcore engine is started
,I/chromium( 5368): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/AmoledAdjustTimer(  770): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/jxcore-log( 5368): Toggling radios to true
I/jxcore-log( 5368): 
,D/BluetoothAdapter( 5368): enable(): BT is already enabled..!
,I/WifiManager( 5368): packageName : com.test.thalitest
,I/WifiManager( 5368): setWifiEnabled : true
,I/WifiService(  770): setWifiEnabled: true pid=5368, uid=10179
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5368, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  770): Failed getting userId using ActivityManagerNative
W/WifiService(  770): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5368, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  770): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  770): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  770): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  770): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  770): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  770): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  770): disconnect: pid=5368, uid=10179
,I/jxcore-log( 5368): Radios toggled
I/jxcore-log( 5368): 
,I/wpa_supplicant( 1995): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1995): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1995): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): InitialState.processMessage what=4
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
D/Tethering(  770): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1995): Cmd 35605 not handled
E/wpa_supplicant( 1995): Cmd 35605 not handled
D/Tethering(  770): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1995): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,E/Tethering(  770): No numeric data
,I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
,D/Tethering(  770): sendTetherStateChangedBroadcast 0, 0, 0
I/wpa_supplicant( 1995): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1995): wlan0: Setting scan request: 0 sec 0 usec
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1995): First Scan Start
,I/wpa_supplicant( 1995): Scan requested (ret=0) - scan timeout 30 seconds
V/NetworkStats(  770): performPollLocked(flags=0x1)
,W/Settings(  770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  770): ignore requestNetworkTransitionWakelock airplane:true
,D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,V/NetworkStats(  770): performPollLocked() took 36ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/CommandListener(  240): Clearing all IP addresses on wlan0
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
E/SMD     (  243): DCD ON
D/ConnectivityService(  770): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  770): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  770): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  770): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/ConnectivityService(  770): Attempting to switch to mobile
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/ConnectivityService(  770): Attempting to switch to BLUETOOTH_TETHER
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
I/wpa_supplicant( 1995): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1995): Skip scan - already scanning
I/SELinux ( 5472): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5472):  
D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
D/WifiP2pService(  770): InactiveState{ what=143375 }
D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
V/RouteController(  240): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
I/SELinux ( 5472): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5472):  
I/SELinux ( 5472):  
I/SELinux ( 5472): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/RouteController(  240): RTNETLINK answers: No such process
E/SELinux ( 5472): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5472): >>>>> Normal User
E/dalvikvm( 5472): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
V/RouteController(  240): /system/bin/ip -6 rule del table 2 2>&1
E/SELinux ( 5472): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
V/RouteController(  240): RTNETLINK answers: No such file or directory
D/CommandListener(  240): Clearing all IP addresses on wlan0
D/TimaKeyStoreProvider( 5472): in addTimaSignatureService
I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
W/NetworkManagementService(  770): route cmd failed: 
W/NetworkManagementService(  770): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
V/RouteController(  240): /system/bin/ip -4 route del default table 2 2>&1
E/WifiStateMachine(  770): Error! unhandled message{ when=-116ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  770): Error! unhandled message{ when=-115ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  770): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/TimaKeyStoreProvider( 5472): Cannot add TimaSignature Service, License check Failed
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/ActivityThread( 5472): Added TimaKesytore provider
V/RouteController(  240): RTNETLINK answers: No such process
V/RouteController(  240): /system/bin/ip -4 rule del table 2 2>&1
V/RouteController(  240): /system/bin/ip route flush cached 2>&1
D/NetUtils(  770): android_net_utils_resetConnections in env=0x77dcf928 clazz=0x6a500001 iface=wlan0 mask=0x3
D/ConnectivityService(  770): resetConnections(wlan0, 3)
V/NativeCrypto( 1320): Read error: ssl=0x7c3d4c30: I/O error during system call, Connection timed out
V/NativeCrypto( 1320): SSL shutdown failed: ssl=0x7c3d4c30: I/O error during system call, Broken pipe
I/GAV2    ( 5278): Thread[GAThread,5,main]: No campaign data found.
D/ConnectivityService(  770): handleInetConditionChange: no active default network - ignore
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): updateIfacesLocked()
V/NetworkStats(  770): performPollLocked(flags=0x1)
V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 18ms
I/System.out( 5472): Inside WakeupProvider
I/System.out( 5472): Inside onCreate() of WakeupTriggerProvide
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
I/VlingoApplication( 5472): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
D/VlingoApplication( 5472): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 5472): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
D/DialogFlow( 5472): initQueue()
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  770): Killing 4469:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/ApplicationPolicy(  770): updateDataUsageMap
,D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  770): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  770): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/LocSvc_java(  770): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): noConnectivity : true
,I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=false
,I/SELinux ( 5512): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5512):  
,I/SELinux ( 5512): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5512):  
I/SELinux ( 5512):  
I/SELinux ( 5512): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5512): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5512): >>>>> Normal User
E/dalvikvm( 5512): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
E/SELinux ( 5512): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5512): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5512): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5512): Added TimaKesytore provider
,I/wpa_supplicant( 1995): nl80211: Received scan results (9 BSSes)
I/wpa_supplicant( 1995): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1995): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1995): Trying to associate with  'G700'
I/wpa_supplicant( 1995): Re-associate with C0.AA.48
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1995): Cmd 35609 not handled
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5512, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  770): Killing 4494:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,E/wpa_supplicant( 1995): Cmd 35605 not handled
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1995): Associated with C0.AA.48
I/wpa_supplicant( 1995): freq(2412) increment count 2
,I/wpa_supplicant( 1995): meet head of list.
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1995): Cmd 35847 not handled
E/wpa_supplicant( 1995): Cmd 35848 not handled
,E/wpa_supplicant( 1995): Cmd 35605 not handled
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
,E/Tethering(  770): No numeric data
,D/Tethering(  770): sendTetherStateChangedBroadcast 1, 0, 0
I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
D/Tethering(  770): interfaceStatusChanged wlan0, true
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
,V/NetworkStats(  770): performPollLocked(flags=0x1)
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1995): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1995): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/WifiNative(  770): callSECApiVoid - ID [50]
,D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 32ms
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/WifiP2pService(  770): InactiveState{ what=143375 }
D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,I/SELinux ( 5529): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5529):  
,D/dalvikvm(  250): GC_EXPLICIT freed 43K, 50% free 9510K/18968K, paused 2ms+3ms, total 27ms
,I/SELinux ( 5529): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5529):  
I/SELinux ( 5529):  
,I/SELinux ( 5529): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5529): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5529): >>>>> Normal User
,E/dalvikvm( 5529): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5529): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9510K/18968K, paused 1ms+3ms, total 20ms
,D/TimaKeyStoreProvider( 5529): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5529): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5529): Added TimaKesytore provider
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9510K/18968K, paused 1ms+3ms, total 20ms
,D/dalvikvm(  770): GC_EXPLICIT freed 2922K, 58% free 23977K/55984K, paused 6ms+16ms, total 160ms
,I/dhcpcd  ( 5541): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5541): bssid match
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5529, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  770): Killing 4516:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5548): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5548):  
,I/SELinux ( 5548): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5548):  
I/SELinux ( 5548):  
,I/SELinux ( 5548): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5548): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5548): >>>>> Normal User
,E/dalvikvm( 5548): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5548): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5548): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5548): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5548): Added TimaKesytore provider
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5548, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5548): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5548): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361514423
,I/KLMS-2.3.201 : ( 5548): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager(  770): Killing 1338:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 5560): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5560):  
,I/SELinux ( 5560): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5560):  
I/SELinux ( 5560):  
,I/SELinux ( 5560): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5560): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5560): >>>>> Normal User
,E/dalvikvm( 5560): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5560): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5560): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5560): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5560): Added TimaKesytore provider
,D/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5560, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/SA      ( 4056): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4056): [BDLM] already registered in spp
I/SA      ( 4056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4056): [OR] == isSIMCardReady false ==
I/SA      ( 4056): [SCU] == networkStateCheck == false
,I/SA      ( 4056): [OR] onReceive END
I/ActivityManager(  770): Killing 4654:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): Phone number locator feature is dsiabled
,I/SELinux ( 5572): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5572):  
,I/SELinux ( 5572): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5572):  
I/SELinux ( 5572):  
,I/SELinux ( 5572): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5572): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5572): >>>>> Normal User
,E/dalvikvm( 5572): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5572): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5572): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5572): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5572): Added TimaKesytore provider
,I/sCloudBackupApp( 5572): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5572): Other Intent
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
V/AlarmManager(  770): waitForAlarm result :4
I/ActivityManager(  770): Killing 4683:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,V/AlarmManager(  770): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5586): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5586):  
,I/SELinux ( 5586): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5586):  
I/SELinux ( 5586):  
,I/SELinux ( 5586): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5586): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5586): >>>>> Normal User
,E/dalvikvm( 5586): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5586): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5586): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5586): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5586): Added TimaKesytore provider
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
D/BatteryService(  770): stay LED for fully charged
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  770): mCoverManager.getCoverState() : true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5586, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  770): Killing 4660:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/Headlines( 4111): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4111): getCountryCode(): countryCode = PL
D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4111): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4111): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4111): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5599): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5599):  
,I/SELinux ( 5599): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5599):  
I/SELinux ( 5599):  
,I/SELinux ( 5599): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5599): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5599): >>>>> Normal User
,E/dalvikvm( 5599): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5599): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5599): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5599): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5599): Added TimaKesytore provider
,W/GAV2    ( 5599): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5599): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5599): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
,E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5599): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5599): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
,D/FactoryTest( 4774): Not factory mode
,D/FactoryTest( 4774): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4774): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4774): still no open session command from host, so toast
W/ContextImpl( 4774): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4774): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
V/ApplicationPolicy(  770): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  770): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  770): mDVFSHelper.acquire()
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/LockPatternUtils( 1069): isPcwEnable = null
,E/MTPRx   ( 4774): started activity for popup
,I/SQLiteSecureOpenHelper( 2126): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2126): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4774): PREF_DONT_ASK_AGAIN : false
,D/SettingsReceiverActivity( 4774): dev.kiessupport is : TRUE
,D/dalvikvm( 1320): GC_EXPLICIT freed 893K, 43% free 10910K/18968K, paused 4ms+5ms, total 46ms
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4774): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4774): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4774): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4774): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4774): Remote Branch: 
I/Adreno-EGL( 4774): Local Patches: 
I/Adreno-EGL( 4774): Reconstruct Branch: 
,I/HWUI    ( 4774): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4774): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/WebViewChromium( 5599): Binding Chromium to the main looper Looper (main, tid 1) {4226d040}
,I/chromium( 5599): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5599): Initializing chromium process, renderers=0
D/CustomFrequencyManagerService(  770): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  770): mDVFSHelper.release()
D/CustomFrequencyManagerService(  770): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  pkgName : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  243): DCD ON
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 5599): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5599): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5599): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5599): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5599): Remote Branch: 
I/Adreno-EGL( 5599): Local Patches: 
I/Adreno-EGL( 5599): Reconstruct Branch: 
,W/chromium( 5599): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/NSApplication( 5599): Starting up...
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5599, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  770): Killing 4726:com.google.android.talk/u0a105 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3365): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4259f1b0
,I/SELinux ( 5661): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5661):  
,I/SELinux ( 5661): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5661):  
I/SELinux ( 5661):  
,I/SELinux ( 5661): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5661): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5661): >>>>> Normal User
,E/dalvikvm( 5661): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5661): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5661): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5661): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5661): Added TimaKesytore provider
,D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/WifiStateMachine(  770): VerifyingLinkState enter
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  770): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  770): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
D/ConnectivityService(  770): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  770): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  770): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  770): mBoosterFLAG : 2
,I/WifiTrafficPoller(  770): current booster mode : BTCoexMode
D/ConnectivityService(  770): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService(  770): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  770): net.tcp.delack.wifi not found in system properties. Using defaults
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/RouteController(  240): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  240): /system/bin/ip -4 rule del table 2 2>&1
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,V/RouteController(  240): RTNETLINK answers: No such file or directory
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,V/RouteController(  240): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
I/ActivityManager(  770): Killing 3051:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
,I/SELinux ( 5690): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5690):  
V/RouteController(  240): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  240): RTNETLINK answers: No such process
,V/RouteController(  240): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,I/SELinux ( 5698): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5698):  
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
W/ActivityManager(  770): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5690): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5690):  
I/SELinux ( 5690):  
,I/SELinux ( 5690): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5690): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5690): >>>>> Normal User
,E/dalvikvm( 5690): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5690): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): updateIfacesLocked()
V/NetworkStats(  770): performPollLocked(flags=0x1)
V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/TimaKeyStoreProvider( 5690): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5690): Cannot add TimaSignature Service, License check Failed
I/SELinux ( 5698): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5698):  
I/SELinux ( 5698):  
I/SELinux ( 5698): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5698): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5698): >>>>> Normal User
,E/dalvikvm( 5698): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5698): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/ActivityThread( 5690): Added TimaKesytore provider
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 25ms
I/ActivityManager(  770): Killing 4807:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 5698): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5698): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5698): Added TimaKesytore provider
,D/BadgeProvider( 5690): onCreate
,D/BadgeProvider( 5690): DatabaseHelper
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5698, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5690, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5690): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5690): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5690): sendNotify, [notify] : null
D/BadgeProvider( 5690): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5690): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5690): update, [UpdateCount] : 1
,D/Launcher.Model( 1254): reloadBadges entered.
,D/hcjo    ( 4212): AutoUpdateManager:IDLE:execute
,I/jxcore-log( 5368): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): my name is : samsung-SM-G800H_PT617
I/jxcore-log( 5368): 
,D/InitializeManagerStateMachine( 4212): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4212): exit::IDLE
,D/InitializeManagerStateMachine( 4212): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4212): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4212): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4212): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4212): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4212): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4212): entry::SUCCESS
,D/hcjo    ( 4212): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4212): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4212): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4212): exit::SUCCESS
,D/InitializeManagerStateMachine( 4212): entry::IDLE
,I/ActivityManager(  770): Killing 4826:com.wssyncmldm/1000 (adj 15): empty #43
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/Headlines( 4111): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4111): Breath 1537 latestRequest time : 1450361514975 current time : 1450361516512
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/jxcore-log( 5368): attempting to connect to test coordinator
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): check test folder
I/jxcore-log( 5368): 
,I/jxcore-log( 5368): found test : ./testFindPeers.js
I/jxcore-log( 5368): 
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/jxcore-log( 5368): found test : ./testReConnect.js
I/jxcore-log( 5368): 
D/Toast   ( 1304):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1304): showing allowed
,I/jxcore-log( 5368): found test : ./testSendData.js
I/jxcore-log( 5368): 
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger(  249): id=18 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  770): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/jxcore-log( 5368): Test app app.js loaded
I/jxcore-log( 5368): 
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  770): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 770  tag : ACTIVITY_RESUME_BOOSTER@9
,I/chromium( 5368): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/jxcore-log( 5368): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5368): 
,I/VacuumService( 1221): Vacuum at: now=1450361516716 tag=VacuumService
,D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  770): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  770): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=true
,D/LocSvc_java(  770): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.3.201 : ( 5548): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5548): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361516963
,I/KLMS-2.3.201 : ( 5548): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/LocationTagReadyService( 2521): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 5728): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5728):  
,I/GallerySearchProvider( 2446): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5732): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5732):  
,I/SELinux ( 5728): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5728):  
I/SELinux ( 5728):  
,I/SELinux ( 5728): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5728): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5728): >>>>> Normal User
,E/dalvikvm( 5728): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5728): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5728): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5728): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5728): Added TimaKesytore provider
,I/SA      ( 4056): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4056): [BDLM] already registered in spp
,I/SA      ( 4056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4056): [OR] == isSIMCardReady false ==
,I/SA      ( 4056): [SCU] == networkStateCheck == true
I/SA      ( 4056): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4056): isChinaCountryCode : false
I/SA      ( 4056): [OR] == networkStateCheck true ==
I/SA      ( 4056): [OR] GetMyCountryZoneTask
I/SA      ( 4056): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5572): Other Intent
,I/SELinux ( 5732): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5732):  
I/SELinux ( 5732):  
,I/SELinux ( 5732): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5732): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5732): >>>>> Normal User
,E/dalvikvm( 5732): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/SELinux ( 5732): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      ( 4056): [SRS] prepareGetMyCountryZone
,D/TimaKeyStoreProvider( 5732): in addTimaSignatureService
,I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/TimaKeyStoreProvider( 5732): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5732): Added TimaKesytore provider
,D/Headlines( 4111): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4111): getCountryCode(): countryCode = PL
D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4111): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4111): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4111): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SA      ( 4056): [SSP] query invoked
,V/KVNProvider( 5732): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5732): getFindoCursor query string : 
,D/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3365): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4259f1b0
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,V/KVNProvider( 5732): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4056): [TPMU] GetMccFromDB : null
,I/SA      ( 4056): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4056): [TPM] isNoProxy(default) : true
,I/SA      ( 4056): [RC New] Execute method=[GET] start
,D/hcjo    ( 4212): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4212): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4212): exit::IDLE
,D/InitializeManagerStateMachine( 4212): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4212): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4212): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4212): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4212): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4212): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4212): entry::SUCCESS
,D/hcjo    ( 4212): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4212): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4212): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4212): exit::SUCCESS
,D/InitializeManagerStateMachine( 4212): entry::IDLE
I/ActivityManager(  770): Killing 4672:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,I/SA      ( 4056): [RC New] [v2liruge] api execute + 655
,I/SA      ( 4056): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4056): AsyncTask #2 calls detatch()
,I/SA      ( 4056): [TPMU] getNetworkMcc : 
,I/SA      ( 4056): [SCU] saveMccToPreferece Start
,I/SA      ( 4056): [SCU] RegionMCC : 260
,I/SA      ( 4056): [SSP] query invoked
I/SA      ( 4056): [TPMU] GetMccFromDB : null
,I/SA      ( 4056): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4056): [SCU] saveMccToPreferece End
I/SA      ( 4056): [RC New] executeRequest [v2liruge] end. 676
,I/SA      ( 4056): [RC New] Execute end
I/SA      ( 4056): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4056): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 5368): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5368): 
,D/SSRMv2:SIOP(  770): SIOP:: AP = 330, Delta = 20
,E/SMD     (  243): DCD ON
,E/WifiStateMachine(  770): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/HarmonyEASService(  770): Updating for all 1
,I/jxcore-log( 5368): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5368): 
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  770): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  770): <AppSync3 Whitelist>
,V/AlarmManager(  770): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager(  770): Killing 4248:com.android.calendar/u0a142 (adj 15): empty #43
,I/SurfaceFlinger(  249): id=18 Removed Uoast (12/13)
,I/SurfaceFlinger(  249): id=18 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  770): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770 (0x0)
D/PowerManagerService(  770): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=770, ws=WorkSource{1000}) (elapsedTime=3494)
,I/GAV2    ( 5599): Thread[GAThread,5,main]: No campaign data found.
,W/WifiP2pStateTracker(  770): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  770): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  770):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  770): updateSourceRoutes : no source routing conditions
,I/dalvikvm( 5368): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5368): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5368): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 5368): Shutting down VM
,W/dalvikvm( 5368): threadid=1: thread exiting with uncaught exception (group=0x417e4da0)
,E/AndroidRuntime( 5368): FATAL EXCEPTION: main
E/AndroidRuntime( 5368): Process: com.test.thalitest, PID: 5368
E/AndroidRuntime( 5368): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 5368): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 5368): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 5368): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 5368): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 5368): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:153)
E/AndroidRuntime( 5368): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 5368): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 5368): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 5368): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 5368): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5368): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5368): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5368): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 5368): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5368): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 5368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 5368): 	at dalvik.system.NativeStart.main(Native Method)
,D/CrashAnrDetector(  770): processName: com.test.thalitest
,D/CrashAnrDetector(  770): broadcastEvent : com.test.thalitest data_app_crash
,I/Process ( 5368): Sending signal. PID: 5368 SIG: 9
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): mConnectivityHandler : connected
,I/ActivityManager(  770): Process com.test.thalitest (pid 5368) (adj 1) has died.
,I/WindowState(  770): WIN DEATH: Window{441dd2f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  249): id=16 Removed NainActivit (7/12)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 5785): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5785):  
,D/dalvikvm(  250): GC_EXPLICIT freed 43K, 50% free 9510K/18968K, paused 8ms+17ms, total 154ms
,W/PCWCLIENTTRACE_AccountUtil( 5181): [hasSamungAccount] - No Samsung Account
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9510K/18968K, paused 2ms+4ms, total 47ms
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9510K/18968K, paused 3ms+4ms, total 30ms
I/SELinux ( 5785): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5785):  
I/SELinux ( 5785):  
,I/SELinux ( 5785): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5785): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5785): >>>>> Normal User
,E/dalvikvm( 5785): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
,E/SELinux ( 5785): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5785): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5785): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5785): Added TimaKesytore provider
,D/InputDispatcher(  770): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  249): id=19 createSurf (720x1280),2 flag=404, TcreenshotS
,D/PermissionCache(  249): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (228 us)
,W/linker  ( 5181): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5181): ================================================
I/CSTORAGE( 5181):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 5181): ================================================
D/dalvikvm( 5181): No JNI_OnLoad found in /system/lib/libterrier.so 0x42599248, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5181): [GetString-S]
,I/terrier ( 5181): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 5181): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5181): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5181): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5181): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5181): QSEECom_shutdown_app, app_id = 3
E/terrier ( 5181): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5181): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5181): [ensureRegistration] - No Samsung account
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5785, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,D/AmoledAdjustTimer(  770): prevTemp = 292, currTemp = 294, prevStep = 4, currStep = 4
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5785, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,V/WebViewChromium( 5785): Binding Chromium to the background looper Looper (main, tid 1) {42273010}
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
W/dalvikvm( 5785): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 5785): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5785): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5785): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5785): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5785): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5785): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5785): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5785): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5785): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5785): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5785): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5785): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 5785): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5785): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5785): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5785): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5785): CordovaWebView is running on device made by: samsung,
,D/dalvikvm(  770): GC_EXPLICIT freed 2513K, 58% free 23829K/55984K, paused 9ms+19ms, total 199ms
,I/SurfaceFlinger(  249): id=20 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5785): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 5785): Enabling debug mode 0
,W/AwContents( 5785): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/WindowManager(  770): Screen frozen for +708ms due to Window{4230d5a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  249): id=21 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  249): id=22 createSurf (720x2560),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  249): id=23 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  249): id=24 createSurf (720x2560),-1 flag=20004, ClackSurfac
,D/InputDispatcher(  770): setInputDispatchMode: enabled=0, frozen=0
,I/SurfaceFlinger(  249): id=19 Removed TcreenshotS (12/17)
I/SurfaceFlinger(  249): id=21 Removed ClackSurfac (12/16)
,I/SurfaceFlinger(  249): id=19 Removed TcreenshotS (-2/16)
I/SurfaceFlinger(  249): id=22 Removed ClackSurfac (12/15)
I/SurfaceFlinger(  249): id=21 Removed ClackSurfac (-2/15)
I/SurfaceFlinger(  249): id=23 Removed ClackSurfac (12/14)
,I/SurfaceFlinger(  249): id=22 Removed ClackSurfac (-2/14)
I/SurfaceFlinger(  249): id=24 Removed ClackSurfac (12/13)
,I/SurfaceFlinger(  249): id=23 Removed ClackSurfac (-2/13)
,I/SurfaceFlinger(  249): id=24 Removed ClackSurfac (-2/13)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
V/WindowManager(  770): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/JsMessageQueue( 5785): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 5785): Trying to load lib /data/app-lib/com.test.thalitest-57/libjxcore.so 0x42599d38
,D/dalvikvm( 5785): Added shared lib /data/app-lib/com.test.thalitest-57/libjxcore.so 0x42599d38
,D/jxcore_app_log( 5785): JniHelper::setJavaVM(0x416d5528), pthread_self() = 1942985424
,D/JX-Cordova( 5785): jxcore cordova android initializing
,V/AlarmManager(  770): waitForAlarm result :4
,V/AlarmManager(  770): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 5785): GC_CONCURRENT freed 4924K, 33% free 12766K/18968K, paused 4ms+4ms, total 51ms
,D/dalvikvm( 5785): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 5785): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/Finsky  ( 3684): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3684): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  243): DCD ON
,D/dalvikvm( 5785): GC_FOR_ALLOC freed 4770K, 28% free 15760K/21828K, paused 55ms, total 58ms
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  770): stay LED for fully charged
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm(  770): GC_EXPLICIT freed 431K, 58% free 23741K/55984K, paused 9ms+19ms, total 220ms
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5785): GC_FOR_ALLOC freed 5173K, 32% free 16791K/24556K, paused 44ms, total 44ms
,I/dalvikvm-heap( 5785): Grow heap (frag case) to 22.039MB for 2511452-byte allocation
,D/dalvikvm( 5785): GC_FOR_ALLOC freed 3812K, 36% free 17479K/27012K, paused 41ms, total 43ms
,D/PreloadUpdateManagerStateMachine( 4212): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4212): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4212): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4212): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4212): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4212): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4212): entry::IDLE
,D/dalvikvm( 5785): GC_FOR_ALLOC freed 1278K, 36% free 17386K/27012K, paused 37ms, total 37ms
,W/jxcore-log( 5785): Initializing JXcore engine
,W/jxcore-log( 5785): JXcore engine is ready
,W/jxcore-log( 5785): Starting JXcore engine
,D/CaptivePortalTracker(  770): DelayedCaptiveCheckState{ when=-4ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  770): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  770): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  770): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  770): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  770): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/jxcore-log( 5785): Platform android
W/jxcore-log( 5785): 
,W/jxcore-log( 5785): Process ARCH arm
W/jxcore-log( 5785): 
,D/PreloadUpdateManagerStateMachine( 4212): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4212): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4212): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4212): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4212): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4212): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4212): entry::IDLE
,E/SMD     (  243): DCD ON
,I/jxcore-log( 5785): JXcore Cordova bridge is ready!
I/jxcore-log( 5785): 
,W/jxcore-log( 5785): JXcore engine is started
,I/chromium( 5785): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5785): Toggling radios to true
I/jxcore-log( 5785): 
,D/BluetoothAdapter( 5785): enable(): BT is already enabled..!
,I/WifiManager( 5785): packageName : com.test.thalitest
,I/WifiManager( 5785): setWifiEnabled : true
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
,I/jxcore-log( 5785): Radios toggled
I/jxcore-log( 5785): 
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=5785, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/wpa_supplicant( 1995): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1995): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1995): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1995): Cmd 35605 not handled
E/wpa_supplicant( 1995): Cmd 35605 not handled
,I/wpa_supplicant( 1995): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): InitialState.processMessage what=4
I/wpa_supplicant( 1995): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1995): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1995): First Scan Start
,I/wpa_supplicant( 1995): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings(  770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  770): ignore requestNetworkTransitionWakelock airplane:true
,E/Tethering(  770): No numeric data
D/SSRMv2:SIOP(  770): SIOP:: AP = 310, Delta = -20
I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/Tethering(  770): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiP2pService(  770): InactiveState{ what=143375 }
D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
V/NetworkStats(  770): performPollLocked(flags=0x1)
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
D/Tethering(  770): interfaceStatusChanged wlan0, false
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/CommandListener(  240): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
I/wpa_supplicant( 1995): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1995): Skip scan - already scanning
D/ConnectivityService(  770): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  770): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  770): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  770): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,V/NetworkStats(  770): performPollLocked() took 38ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  770): Attempting to switch to mobile
D/ConnectivityService(  770): Attempting to switch to BLUETOOTH_TETHER
D/WifiP2pService(  770): InactiveState{ what=143375 }
D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
,D/CommandListener(  240): Clearing all IP addresses on wlan0
,V/RouteController(  240): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,V/RouteController(  240): RTNETLINK answers: No such process
,V/RouteController(  240): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController(  240): RTNETLINK answers: No such file or directory
,W/NetworkManagementService(  770): route cmd failed: 
W/NetworkManagementService(  770): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '62 route del src v6 2' failed with '400 62 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,V/RouteController(  240): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
,E/WifiStateMachine(  770): Error! unhandled message{ when=-80ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  770): Error! unhandled message{ when=-80ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  240): RTNETLINK answers: No such process
,V/RouteController(  240): /system/bin/ip -4 rule del table 2 2>&1
,E/WifiStateMachine(  770): Error! unhandled message{ when=-12ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  770): android_net_utils_resetConnections in env=0x77dcf928 clazz=0xa6200001 iface=wlan0 mask=0x3
D/ConnectivityService(  770): resetConnections(wlan0, 3)
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): updateIfacesLocked()
V/NetworkStats(  770): performPollLocked(flags=0x1)
V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 19ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,I/ApplicationPolicy(  770): updateDataUsageMap
,D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  770): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  770): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/LocSvc_java(  770): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): noConnectivity : true
,I/KLMS-2.3.201 : ( 5548): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5548): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361529151
,I/KLMS-2.3.201 : ( 5548): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4056): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4056): [BDLM] already registered in spp
I/SA      ( 4056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4056): [OR] == isSIMCardReady false ==
I/SA      ( 4056): [SCU] == networkStateCheck == false
,I/SA      ( 4056): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5572): Other Intent
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/wpa_supplicant( 1995): nl80211: Received scan results (10 BSSes)
I/wpa_supplicant( 1995): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1995): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1995): Trying to associate with  'G700'
I/wpa_supplicant( 1995): Re-associate with C0.AA.48
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1995): Cmd 35609 not handled
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Headlines( 4111): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4111): getCountryCode(): countryCode = PL
,D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4111): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4111): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4111): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3365): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4259f1b0
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,I/iu.Environment( 1788): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1788): num queued entries: 0
,I/iu.UploadsManager( 1788): num updated entries: 0
,I/iu.SyncManager( 1788): NEXT; no task
,E/wpa_supplicant( 1995): Cmd 35605 not handled
E/wpa_supplicant( 1995): Cmd 35847 not handled
E/wpa_supplicant( 1995): Cmd 35848 not handled
,E/wpa_supplicant( 1995): Cmd 35605 not handled
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1995): Associated with C0.AA.48
I/wpa_supplicant( 1995): freq(2412) increment count 3
,I/wpa_supplicant( 1995): meet head of list.
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1995): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1995): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
E/Tethering(  770): No numeric data
,D/WifiNative(  770): callSECApiVoid - ID [50]
,D/Tethering(  770): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  770): performPollLocked(flags=0x1)
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
D/Tethering(  770): interfaceStatusChanged wlan0, true
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
D/Tethering(  770): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 34ms
D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/dhcpcd  ( 5904): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5904): bssid match
,E/Watchdog(  770): !@Sync 4
,E/SMD     (  243): DCD ON
,I/jxcore-log( 5785): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5785): 
,I/jxcore-log( 5785): my name is : samsung-SM-G800H_PT4625
I/jxcore-log( 5785): 
,I/jxcore-log( 5785): attempting to connect to test coordinator
I/jxcore-log( 5785): 
,I/jxcore-log( 5785): check test folder
I/jxcore-log( 5785): 
,I/jxcore-log( 5785): found test : ./testFindPeers.js
I/jxcore-log( 5785): 
,I/jxcore-log( 5785): found test : ./testReConnect.js
I/jxcore-log( 5785): 
,I/jxcore-log( 5785): found test : ./testSendData.js
I/jxcore-log( 5785): 
,I/jxcore-log( 5785): Test app app.js loaded
I/jxcore-log( 5785): 
,I/jxcore-log( 5785): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5785): 
,I/chromium( 5785): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiP2pService(  770): InactiveState{ what=143375 }
D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
,D/WifiStateMachine(  770): VerifyingLinkState enter
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  770): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  770): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
,D/WifiStateMachine(  770): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  770): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  770): mBoosterFLAG : 2
,I/WifiTrafficPoller(  770): current booster mode : BTCoexMode
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  770): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  770): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  770): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,V/RouteController(  240): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/Toast   ( 1304):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1304): showing allowed
,V/RouteController(  240): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  240): RTNETLINK answers: No such file or directory
,V/RouteController(  240): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/SurfaceFlinger(  249): id=25 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  770): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,V/RouteController(  240): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,V/RouteController(  240): RTNETLINK answers: No such process
V/RouteController(  240): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/NetworkStats(  770): updateIfacesLocked()
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked(flags=0x1)
V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 17ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,I/PowerManagerService(  770): [PWL] Off : 75s ago
,D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  770): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  770): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
,I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=true
I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  770): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
,I/jxcore-log( 5785): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5785): 
,I/KLMS-2.3.201 : ( 5548): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5548): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361532363
,I/KLMS-2.3.201 : ( 5548): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/LocationTagReadyService( 2521): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 2446): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,V/KVNProvider( 5732): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5732): getFindoCursor query string : 
,V/KVNProvider( 5732): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4056): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4056): [BDLM] already registered in spp
,I/SA      ( 4056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4056): [OR] == isSIMCardReady false ==
I/SA      ( 4056): [SCU] == networkStateCheck == true
I/SA      ( 4056): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4056): isChinaCountryCode : false
I/SA      ( 4056): [OR] == networkStateCheck true ==
,I/SA      ( 4056): [OR] GetMyCountryZoneTask
,I/SA      ( 4056): [OR] onReceive END
,I/SA      ( 4056): [SRS] prepareGetMyCountryZone
,I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4056): [SSP] query invoked
,I/SA      ( 4056): [TPMU] GetMccFromDB : null
I/SA      ( 4056): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4056): [TPM] isNoProxy(default) : true
,I/SA      ( 4056): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 1242): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5572): Other Intent
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/AmoledAdjustTimer(  770): prevTemp = 294, currTemp = 297, prevStep = 4, currStep = 4
,D/Headlines( 4111): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4111): getCountryCode(): countryCode = PL
,D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 4111): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4111): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4111): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3365): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4259f1b0
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4212): notifyNetworkActivated
,D/hcjo    ( 4212): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4212): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4212): exit::IDLE
,D/InitializeManagerStateMachine( 4212): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4212): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4212): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4212): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4212): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 4212): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4212): entry::SUCCESS
,D/hcjo    ( 4212): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4212): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4212): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4212): exit::SUCCESS
,D/InitializeManagerStateMachine( 4212): entry::IDLE
,I/iu.Environment( 1788): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1788): num queued entries: 0
,I/iu.UploadsManager( 1788): num updated entries: 0
,I/iu.SyncManager( 1788): NEXT; no task
,I/SA      ( 4056): [RC New] [v2liruge] api execute + 432
,I/SA      ( 4056): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4056): AsyncTask #3 calls detatch()
,I/SA      ( 4056): [TPMU] getNetworkMcc : 
I/SA      ( 4056): [SCU] saveMccToPreferece Start
I/SA      ( 4056): [SCU] RegionMCC : 260
,I/SA      ( 4056): [SSP] query invoked
,I/SA      ( 4056): [TPMU] GetMccFromDB : null
I/SA      ( 4056): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4056): [SCU] saveMccToPreferece End
I/SA      ( 4056): [RC New] executeRequest [v2liruge] end. 442
I/SA      ( 4056): [RC New] Execute end
I/SA      ( 4056): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4056): [OR] GetMyCountryZoneTask Success
,I/PhenotypeConfigurator( 1221): Scheduling Phenotype for one-off execution 10834 seconds from now (1450361532957)
,D/GetConfigurationSnapshotOperation( 1221): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1221): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1221): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1221): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1221): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1221): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  770): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1221): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1221): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1221): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1221): Thread-110(HTTPLog):isShipBuild true
,I/System.out( 1221): Thread-110(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ConnectivityService(  770): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/dalvikvm( 1221): GC_CONCURRENT freed 1555K, 37% free 11952K/18968K, paused 7ms+9ms, total 85ms
,D/LocationManagerService(  770): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/jxcore-log( 5785): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5785): 
,E/SMD     (  243): DCD ON
,W/WifiP2pStateTracker(  770): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  770): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  770):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  770): updateSourceRoutes : no source routing conditions
,E/WifiStateMachine(  770): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  249): id=25 Removed Uoast (12/13)
,I/SurfaceFlinger(  249): id=25 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  770): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770 (0x0)
,D/PowerManagerService(  770): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=770, ws=WorkSource{1000}) (elapsedTime=3547)
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/dalvikvm( 5785): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5785): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5785): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 5785): Shutting down VM
,W/dalvikvm( 5785): threadid=1: thread exiting with uncaught exception (group=0x417e4da0)
,E/AndroidRuntime( 5785): FATAL EXCEPTION: main
E/AndroidRuntime( 5785): Process: com.test.thalitest, PID: 5785
E/AndroidRuntime( 5785): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 5785): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 5785): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 5785): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 5785): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 5785): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:153)
E/AndroidRuntime( 5785): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 5785): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 5785): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 5785): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 5785): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5785): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5785): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5785): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 5785): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5785): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5785): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 5785): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 5785): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 5785): Sending signal. PID: 5785 SIG: 9
,D/CrashAnrDetector(  770): processName: com.test.thalitest
,D/CrashAnrDetector(  770): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/ActivityManager(  770): Process com.test.thalitest (pid 5785) (adj 1) has died.
,I/WindowState(  770): WIN DEATH: Window{4230d5a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  249): id=20 Removed NainActivit (7/12)
,I/SurfaceFlinger(  249): id=20 Removed NainActivit (-2/12)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,I/SELinux ( 6027): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6027):  
,D/Headlines( 4111): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4111): Breath 4470 latestRequest time : 1450361532494 current time : 1450361536964
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): mConnectivityHandler : connected
,I/SELinux ( 6027): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6027):  
I/SELinux ( 6027):  
,W/PCWCLIENTTRACE_AccountUtil( 5181): [hasSamungAccount] - No Samsung Account
,I/SELinux ( 6027): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6027): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 6027): >>>>> Normal User
,E/dalvikvm( 6027): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5181): [GetString-S]
I/terrier ( 5181): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 5181): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5181): App is not loaded in QSEE
,E/SELinux ( 6027): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/QSEECOMAPI: ( 5181): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5181): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5181): QSEECom_shutdown_app, app_id = 3
E/terrier ( 5181): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5181): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5181): [ensureRegistration] - No Samsung account
,D/TimaKeyStoreProvider( 6027): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6027): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6027): Added TimaKesytore provider
,D/InputDispatcher(  770): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  249): id=26 createSurf (720x1280),2 flag=404, TcreenshotS
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6027, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6027, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,V/WebViewChromium( 6027): Binding Chromium to the background looper Looper (main, tid 1) {42269388}
,I/chromium( 6027): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6027): Initializing chromium process, renderers=0
,W/chromium( 6027): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6027): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6027): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 6027): Build Date: 03/21/14 Fri
I/Adreno-EGL( 6027): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 6027): Remote Branch: 
I/Adreno-EGL( 6027): Local Patches: 
I/Adreno-EGL( 6027): Reconstruct Branch: 
,I/dalvikvm( 6027): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6027): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6027): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6027): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6027): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6027): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 6027): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6027): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6027): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6027): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 6027): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 6027): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6027): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6027): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 6027): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6027): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6027): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 6027): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 6027): CordovaWebView is running on device made by: samsung
,I/SurfaceFlinger(  249): id=27 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 6027): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6027): Enabling debug mode 0
,W/AwContents( 6027): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  249): id=28 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/WindowManager(  770): Screen frozen for +467ms due to Window{44b96330 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  249): id=29 createSurf (720x2560),-1 flag=20004, ClackSurfac
I/SurfaceFlinger(  249): id=30 createSurf (1440x1280),-1 flag=20004, ClackSurfac
I/SurfaceFlinger(  249): id=31 createSurf (720x2560),-1 flag=20004, ClackSurfac
D/InputDispatcher(  770): setInputDispatchMode: enabled=0, frozen=0
,D/JsMessageQueue( 6027): Set native->JS mode to OnlineEventsBridgeMode
,I/SurfaceFlinger(  249): id=26 Removed TcreenshotS (12/17)
I/SurfaceFlinger(  249): id=26 Removed TcreenshotS (-2/17)
,I/SurfaceFlinger(  249): id=28 Removed ClackSurfac (12/16)
I/SurfaceFlinger(  249): id=29 Removed ClackSurfac (12/15)
I/SurfaceFlinger(  249): id=28 Removed ClackSurfac (-2/15)
I/SurfaceFlinger(  249): id=30 Removed ClackSurfac (12/14)
I/SurfaceFlinger(  249): id=29 Removed ClackSurfac (-2/14)
I/SurfaceFlinger(  249): id=31 Removed ClackSurfac (12/13)
,I/SurfaceFlinger(  249): id=30 Removed ClackSurfac (-2/13)
,I/SurfaceFlinger(  249): id=31 Removed ClackSurfac (-2/13)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
V/WindowManager(  770): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/dalvikvm( 6027): Trying to load lib /data/app-lib/com.test.thalitest-57/libjxcore.so 0x425900b0
,D/dalvikvm( 6027): Added shared lib /data/app-lib/com.test.thalitest-57/libjxcore.so 0x425900b0
,D/jxcore_app_log( 6027): JniHelper::setJavaVM(0x416d5528), pthread_self() = 2032668184
,D/JX-Cordova( 6027): jxcore cordova android initializing
,D/SSRMv2:SIOP(  770): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 6027): GC_CONCURRENT freed 4894K, 33% free 12796K/18968K, paused 2ms+3ms, total 38ms
D/dalvikvm( 6027): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 6027): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 6027): GC_FOR_ALLOC freed 4755K, 28% free 15759K/21808K, paused 35ms, total 37ms
,E/SMD     (  243): DCD ON
,D/dalvikvm( 6027): GC_FOR_ALLOC freed 5160K, 32% free 16790K/24536K, paused 39ms, total 40ms
,I/dalvikvm-heap( 6027): Grow heap (frag case) to 22.038MB for 2511452-byte allocation
,D/dalvikvm(  770): GC_EXPLICIT freed 2439K, 58% free 23926K/55984K, paused 8ms+15ms, total 160ms
,D/dalvikvm( 6027): GC_FOR_ALLOC freed 3811K, 36% free 17478K/26992K, paused 38ms, total 38ms
,D/dalvikvm( 6027): GC_FOR_ALLOC freed 1272K, 36% free 17385K/26992K, paused 33ms, total 33ms
,W/jxcore-log( 6027): Initializing JXcore engine
,W/jxcore-log( 6027): JXcore engine is ready
,W/jxcore-log( 6027): Starting JXcore engine
,W/jxcore-log( 6027): Platform android
W/jxcore-log( 6027): 
,W/jxcore-log( 6027): Process ARCH arm
W/jxcore-log( 6027): 
,I/jxcore-log( 6027): JXcore Cordova bridge is ready!
I/jxcore-log( 6027): 
,W/jxcore-log( 6027): JXcore engine is started
,I/chromium( 6027): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6027): Toggling radios to true
I/jxcore-log( 6027): 
,D/BluetoothAdapter( 6027): enable(): BT is already enabled..!
,I/WifiManager( 6027): packageName : com.test.thalitest
I/WifiManager( 6027): setWifiEnabled : true
,I/WifiService(  770): setWifiEnabled: true pid=6027, uid=10179
,W/WifiService(  770): Failed getting userId using ActivityManagerNative
W/WifiService(  770): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6027, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  770): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  770): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  770): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  770): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  770): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  770): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  770): disconnect: pid=6027, uid=10179
,I/wpa_supplicant( 1995): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6027, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/jxcore-log( 6027): Radios toggled
I/jxcore-log( 6027): 
,I/wpa_supplicant( 1995): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1995): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1995): Cmd 35605 not handled
,E/wpa_supplicant( 1995): Cmd 35605 not handled
,I/wpa_supplicant( 1995): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/wpa_supplicant( 1995): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1995): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1995): First Scan Start
,I/wpa_supplicant( 1995): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): InitialState.processMessage what=4
,E/Tethering(  770): No numeric data
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  770): performPollLocked(flags=0x1)
D/Tethering(  770): sendTetherStateChangedBroadcast 0, 0, 0
W/Settings(  770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  770): ignore requestNetworkTransitionWakelock airplane:true
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/WifiP2pService(  770): InactiveState{ what=143375 }
D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/CommandListener(  240): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
D/ConnectivityService(  770): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  770): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  770): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  770): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/ConnectivityService(  770): Attempting to switch to mobile
D/ConnectivityService(  770): Attempting to switch to BLUETOOTH_TETHER
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,V/NetworkStats(  770): performPollLocked() took 70ms
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
I/wpa_supplicant( 1995): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1995): Skip scan - already scanning
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
D/WifiP2pService(  770): InactiveState{ what=143375 }
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
D/CommandListener(  240): Clearing all IP addresses on wlan0
D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
,V/RouteController(  240): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
E/WifiStateMachine(  770): Error! unhandled message{ when=-44ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  770): Error! unhandled message{ when=-44ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  770): Error! unhandled message{ when=-10ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  240): RTNETLINK answers: No such process
V/RouteController(  240): /system/bin/ip -6 rule del table 2 2>&1
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/CaptivePortalTracker(  770): DelayedCaptiveCheckState{ when=-4ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/CaptivePortalTracker(  770): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  770): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  770): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/ConnectivityService(  770): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
V/RouteController(  240): RTNETLINK answers: No such file or directory
W/NetworkManagementService(  770): route cmd failed: 
W/NetworkManagementService(  770): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '87 route del src v6 2' failed with '400 87 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
V/RouteController(  240): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController(  240): RTNETLINK answers: No such process
,V/RouteController(  240): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  770): android_net_utils_resetConnections in env=0x77dcf928 clazz=0xe3e00001 iface=wlan0 mask=0x3
D/ConnectivityService(  770): resetConnections(wlan0, 3)
,V/NativeCrypto( 1320): Read error: ssl=0x7c3eaa60: I/O error during system call, Connection timed out
,V/NativeCrypto( 1320): SSL shutdown failed: ssl=0x7c3eaa60: I/O error during system call, Broken pipe
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/ConnectivityService(  770): handleInetConditionChange: no active default network - ignore
V/NetworkStats(  770): updateIfacesLocked()
V/NetworkStats(  770): performPollLocked(flags=0x1)
,V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 16ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/AmoledAdjustTimer(  770): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/PreloadUpdateManagerStateMachine( 4212): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4212): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4212): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4212): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4212): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 4212): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4212): entry::IDLE
,E/SMD     (  243): DCD ON
,I/ApplicationPolicy(  770): updateDataUsageMap
,D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  770): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  770): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/LocSvc_java(  770): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): noConnectivity : true
,I/KLMS-2.3.201 : ( 5548): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5548): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361542965
,I/KLMS-2.3.201 : ( 5548): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4056): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4056): [BDLM] already registered in spp
,I/SA      ( 4056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4056): [OR] == isSIMCardReady false ==
I/SA      ( 4056): [SCU] == networkStateCheck == false
,I/SA      ( 4056): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5572): Other Intent
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4111): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4111): getCountryCode(): countryCode = PL
D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4111): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4111): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4111): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3365): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4259f1b0
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,I/iu.Environment( 1788): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1788): num queued entries: 0
,I/iu.UploadsManager( 1788): num updated entries: 0
,I/iu.SyncManager( 1788): NEXT; no task
,E/wpa_supplicant( 1995): Cmd 35609 not handled
I/wpa_supplicant( 1995): nl80211: Received scan results (11 BSSes)
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
D/Tethering(  770): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1995): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1995): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1995): Trying to associate with  'G700'
I/wpa_supplicant( 1995): Re-associate with C0.AA.48
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1995): Cmd 35605 not handled
E/wpa_supplicant( 1995): Cmd 35847 not handled
E/wpa_supplicant( 1995): Cmd 35848 not handled
,E/wpa_supplicant( 1995): Cmd 35605 not handled
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1995): Associated with C0.AA.48
I/wpa_supplicant( 1995): freq(2412) increment count 4
,I/wpa_supplicant( 1995): meet head of list.
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  770): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1995): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1995): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/Tethering(  770): No numeric data
,D/Tethering(  770): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiNative(  770): callSECApiVoid - ID [50]
,D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
D/Tethering(  770): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  770): performPollLocked(flags=0x1)
D/Tethering(  770): interfaceStatusChanged wlan0, true
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
D/Tethering(  770): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
V/NetworkStats(  770): performPollLocked() took 37ms
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
D/WifiP2pService(  770): InactiveState{ what=143375 }
D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/dhcpcd  ( 6121): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6121): bssid match
,D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  770): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  770): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  770): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
D/ConnectivityService(  770): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  770): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  770): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  770): mBoosterFLAG : 2
,I/WifiTrafficPoller(  770): current booster mode : BTCoexMode
D/ConnectivityService(  770): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
E/ConnectivityService(  770): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  770): net.tcp.delack.wifi not found in system properties. Using defaults
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,V/RouteController(  240): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  240): /system/bin/ip -4 rule del table 2 2>&1
,D/Toast   ( 1304):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1304): showing allowed
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,V/RouteController(  240): RTNETLINK answers: No such file or directory
,V/RouteController(  240): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/SurfaceFlinger(  249): id=32 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  770): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770
,V/RouteController(  240): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  240): RTNETLINK answers: No such process
,V/RouteController(  240): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): updateIfacesLocked()
V/NetworkStats(  770): performPollLocked(flags=0x1)
V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 19ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  770): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  770): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/LocSvc_java(  770): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.3.201 : ( 5548): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5548): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361545104
,I/KLMS-2.3.201 : ( 5548): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2521): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 2446): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  770): stay LED for fully charged
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,V/KVNProvider( 5732): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5732): getFindoCursor query string : 
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/KVNProvider( 5732): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4056): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4056): [BDLM] already registered in spp
I/SA      ( 4056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4056): [OR] == isSIMCardReady false ==
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
I/SA      ( 4056): [SCU] == networkStateCheck == true
I/SA      ( 4056): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4056): isChinaCountryCode : false
I/SA      ( 4056): [OR] == networkStateCheck true ==
I/SA      ( 4056): [OR] GetMyCountryZoneTask
I/SA      ( 4056): [OR] onReceive END
I/SA      ( 4056): [SRS] prepareGetMyCountryZone
I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4056): [SSP] query invoked
I/SA      ( 4056): [TPMU] GetMccFromDB : null
I/SA      ( 4056): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4056): [TPM] isNoProxy(default) : true
I/SA      ( 4056): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5572): Other Intent
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4111): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4111): getCountryCode(): countryCode = PL
,D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4111): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 4111): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4111): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3365): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4259f1b0
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4212): notifyNetworkActivated
,D/hcjo    ( 4212): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4212): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4212): exit::IDLE
,D/InitializeManagerStateMachine( 4212): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4212): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4212): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4212): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4212): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4212): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4212): entry::SUCCESS
,D/hcjo    ( 4212): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4212): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4212): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4212): exit::SUCCESS
,D/InitializeManagerStateMachine( 4212): entry::IDLE
,I/iu.Environment( 1788): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1788): num queued entries: 0
,I/iu.UploadsManager( 1788): num updated entries: 0
,I/iu.SyncManager( 1788): NEXT; no task
,I/jxcore-log( 6027): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): my name is : samsung-SM-G800H_PT3983
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): attempting to connect to test coordinator
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): check test folder
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): found test : ./testFindPeers.js
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): found test : ./testReConnect.js
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): found test : ./testSendData.js
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): Test app app.js loaded
I/jxcore-log( 6027): 
,I/jxcore-log( 6027): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6027): 
,I/chromium( 6027): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SA      ( 4056): [RC New] [v2liruge] api execute + 434
,I/SA      ( 4056): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4056): AsyncTask #4 calls detatch()
,I/SA      ( 4056): [TPMU] getNetworkMcc : 
,I/SA      ( 4056): [SCU] saveMccToPreferece Start
I/SA      ( 4056): [SCU] RegionMCC : 260
,I/SA      ( 4056): [SSP] query invoked
I/SA      ( 4056): [TPMU] GetMccFromDB : null
,I/SA      ( 4056): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4056): [SCU] saveMccToPreferece End
,I/SA      ( 4056): [RC New] executeRequest [v2liruge] end. 443
I/SA      ( 4056): [RC New] Execute end
I/SA      ( 4056): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4056): [OR] GetMyCountryZoneTask Success
,E/SMD     (  243): DCD ON
,D/ConnectivityService(  770): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/jxcore-log( 6027): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6027): 
,E/WifiStateMachine(  770): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  249): id=32 Removed Uoast (12/13)
,I/SurfaceFlinger(  249): id=32 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  770): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770 (0x0)
,D/PowerManagerService(  770): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=770, ws=WorkSource{1000}) (elapsedTime=3520)
,D/SSRMv2:SIOP(  770): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 6027): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6027): 
,E/SMD     (  243): DCD ON
,W/WifiP2pStateTracker(  770): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  770): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  770):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  770): updateSourceRoutes : no source routing conditions
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5181): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5181): [GetString-S]
,I/terrier ( 5181): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5181): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5181): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5181): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5181): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5181): QSEECom_shutdown_app, app_id = 3
,E/terrier ( 5181): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5181): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5181): [ensureRegistration] - No Samsung account
,I/dalvikvm( 6027): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 6027): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6027): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 6027): Shutting down VM
,W/dalvikvm( 6027): threadid=1: thread exiting with uncaught exception (group=0x417e4da0)
,E/AndroidRuntime( 6027): FATAL EXCEPTION: main
E/AndroidRuntime( 6027): Process: com.test.thalitest, PID: 6027
E/AndroidRuntime( 6027): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 6027): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 6027): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 6027): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 6027): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 6027): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:153)
E/AndroidRuntime( 6027): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 6027): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 6027): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 6027): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 6027): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 6027): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6027): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6027): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 6027): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 6027): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 6027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 6027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 6027): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 6027): Sending signal. PID: 6027 SIG: 9
,D/CrashAnrDetector(  770): processName: com.test.thalitest
,D/CrashAnrDetector(  770): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/ActivityManager(  770): Process com.test.thalitest (pid 6027) (adj 1) has died.
I/WindowState(  770): WIN DEATH: Window{44b96330 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  249): id=27 Removed NainActivit (7/12)
,I/SurfaceFlinger(  249): id=27 Removed NainActivit (-2/12)
,I/SurfaceFlinger(  249): id=27 Removed NainActivit (-2/12)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 6208): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6208):  
,I/SELinux ( 6208): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6208):  
I/SELinux ( 6208):  
,I/SELinux ( 6208): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6208): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6208): >>>>> Normal User
,E/dalvikvm( 6208): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
,E/SELinux ( 6208): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6208): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6208): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6208): Added TimaKesytore provider
,D/InputDispatcher(  770): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  249): id=33 createSurf (720x1280),2 flag=404, TcreenshotS
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6208, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6208, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,V/WebViewChromium( 6208): Binding Chromium to the background looper Looper (main, tid 1) {4226a2f0}
,I/chromium( 6208): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6208): Initializing chromium process, renderers=0
,W/chromium( 6208): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6208): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6208): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 6208): Build Date: 03/21/14 Fri
I/Adreno-EGL( 6208): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 6208): Remote Branch: 
I/Adreno-EGL( 6208): Local Patches: 
I/Adreno-EGL( 6208): Reconstruct Branch: 
,I/dalvikvm( 6208): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 6208): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6208): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6208): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6208): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6208): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 6208): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 6208): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6208): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6208): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 6208): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 6208): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,I/dalvikvm( 6208): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6208): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 6208): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6208): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6208): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 6208): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 6208): CordovaWebView is running on device made by: samsung
,I/SurfaceFlinger(  249): id=34 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 6208): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6208): Enabling debug mode 0
,W/AwContents( 6208): nativeOnDraw failed; clearing to background color.
,E/SMD     (  243): DCD ON
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  249): id=35 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  249): id=36 createSurf (720x2560),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  249): id=37 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  249): id=38 createSurf (720x2560),-1 flag=20004, ClackSurfac
,D/InputDispatcher(  770): setInputDispatchMode: enabled=0, frozen=0
I/WindowManager(  770): Screen frozen for +497ms due to Window{4314f6e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/JsMessageQueue( 6208): Set native->JS mode to OnlineEventsBridgeMode
,I/SurfaceFlinger(  249): id=33 Removed TcreenshotS (12/17)
,I/SurfaceFlinger(  249): id=33 Removed TcreenshotS (-2/17)
I/SurfaceFlinger(  249): id=35 Removed ClackSurfac (12/16)
I/SurfaceFlinger(  249): id=36 Removed ClackSurfac (12/15)
I/SurfaceFlinger(  249): id=35 Removed ClackSurfac (-2/15)
I/SurfaceFlinger(  249): id=36 Removed ClackSurfac (-2/15)
,I/SurfaceFlinger(  249): id=37 Removed ClackSurfac (12/14)
,I/SurfaceFlinger(  249): id=38 Removed ClackSurfac (12/13)
,I/SurfaceFlinger(  249): id=37 Removed ClackSurfac (-2/13)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
V/WindowManager(  770): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/dalvikvm( 6208): Trying to load lib /data/app-lib/com.test.thalitest-57/libjxcore.so 0x42591018
,D/dalvikvm( 6208): Added shared lib /data/app-lib/com.test.thalitest-57/libjxcore.so 0x42591018
D/jxcore_app_log( 6208): JniHelper::setJavaVM(0x416d5528), pthread_self() = 2032674088
,D/JX-Cordova( 6208): jxcore cordova android initializing
,D/AmoledAdjustTimer(  770): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/dalvikvm( 6208): GC_CONCURRENT freed 4896K, 33% free 12794K/18968K, paused 2ms+3ms, total 47ms
,D/dalvikvm( 6208): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 6208): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/dalvikvm( 6208): GC_FOR_ALLOC freed 4761K, 28% free 15760K/21816K, paused 52ms, total 55ms
,D/dalvikvm(  770): GC_EXPLICIT freed 2022K, 58% free 23957K/55984K, paused 8ms+19ms, total 249ms
,D/dalvikvm( 6208): GC_FOR_ALLOC freed 5175K, 32% free 16790K/24544K, paused 56ms, total 56ms
,I/dalvikvm-heap( 6208): Grow heap (frag case) to 22.038MB for 2511452-byte allocation
,E/SMD     (  243): DCD ON
,D/dalvikvm( 6208): GC_FOR_ALLOC freed 3812K, 36% free 17478K/27000K, paused 54ms, total 56ms
,D/CaptivePortalTracker(  770): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  770): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  770): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  770): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  770): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  770): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/dalvikvm( 6208): GC_FOR_ALLOC freed 1283K, 36% free 17386K/27000K, paused 49ms, total 51ms
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/dalvikvm-heap( 6208): Grow heap (frag case) to 23.818MB for 3767174-byte allocation
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/PreloadUpdateManagerStateMachine( 4212): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4212): exit::IDLE
D/PreloadUpdateManagerStateMachine( 4212): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4212): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4212): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 4212): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 4212): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 4212): execute::IDLE:CHECK_TIMER_OVER
,D/dalvikvm( 6208): GC_FOR_ALLOC freed 3174K, 40% free 18556K/30680K, paused 37ms, total 37ms
,W/jxcore-log( 6208): Initializing JXcore engine
,W/jxcore-log( 6208): JXcore engine is ready
,W/jxcore-log( 6208): Starting JXcore engine
,W/jxcore-log( 6208): Platform android
W/jxcore-log( 6208): 
,W/jxcore-log( 6208): Process ARCH arm
W/jxcore-log( 6208): 
,I/jxcore-log( 6208): JXcore Cordova bridge is ready!
I/jxcore-log( 6208): 
,W/jxcore-log( 6208): JXcore engine is started
,I/chromium( 6208): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6208): Toggling radios to true
I/jxcore-log( 6208): 
,D/BluetoothAdapter( 6208): enable(): BT is already enabled..!
,I/WifiManager( 6208): packageName : com.test.thalitest
I/WifiManager( 6208): setWifiEnabled : true
,I/WifiService(  770): setWifiEnabled: true pid=6208, uid=10179
,W/WifiService(  770): Failed getting userId using ActivityManagerNative
W/WifiService(  770): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6208, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  770): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  770): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  770): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  770): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  770): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  770): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  770): disconnect: pid=6208, uid=10179
,I/wpa_supplicant( 1995): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6208, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/jxcore-log( 6208): Radios toggled
I/jxcore-log( 6208): 
,I/wpa_supplicant( 1995): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1995): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1995): Cmd 35605 not handled
,E/wpa_supplicant( 1995): Cmd 35605 not handled
,I/wpa_supplicant( 1995): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): InitialState.processMessage what=4
,E/Tethering(  770): No numeric data
,D/Tethering(  770): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  770): performPollLocked(flags=0x1)
,I/wpa_supplicant( 1995): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1995): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1995): First Scan Start
I/wpa_supplicant( 1995): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings(  770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  770): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  240): Clearing all IP addresses on wlan0
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 57ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
D/ConnectivityService(  770): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  770): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  770): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  770): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  770): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/ConnectivityService(  770): Attempting to switch to mobile
D/ConnectivityService(  770): Attempting to switch to BLUETOOTH_TETHER
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/wpa_supplicant( 1995): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1995): Skip scan - already scanning
D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService(  770): InactiveState{ what=143375 }
,V/RouteController(  240): /system/bin/ip -6 route del default table 2 2>&1
D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  240): RTNETLINK answers: No such process
,V/RouteController(  240): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController(  240): RTNETLINK answers: No such file or directory
,D/CommandListener(  240): Clearing all IP addresses on wlan0
,W/NetworkManagementService(  770): route cmd failed: 
W/NetworkManagementService(  770): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '109 route del src v6 2' failed with '400 109 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,V/RouteController(  240): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
,E/WifiStateMachine(  770): Error! unhandled message{ when=-77ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  770): Error! unhandled message{ when=-80ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
E/WifiStateMachine(  770): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  240): RTNETLINK answers: No such process
,V/RouteController(  240): /system/bin/ip -4 rule del table 2 2>&1
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  770): android_net_utils_resetConnections in env=0x77dcf928 clazz=0x21a00001 iface=wlan0 mask=0x3
D/ConnectivityService(  770): resetConnections(wlan0, 3)
,V/NativeCrypto( 1320): Read error: ssl=0x7a13c540: I/O error during system call, Connection timed out
,V/NativeCrypto( 1320): SSL shutdown failed: ssl=0x7a13c540: I/O error during system call, Broken pipe
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/ConnectivityService(  770): handleInetConditionChange: no active default network - ignore
V/NetworkStats(  770): updateIfacesLocked()
,V/NetworkStats(  770): performPollLocked(flags=0x1)
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,V/NetworkStats(  770): performPollLocked() took 16ms
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,I/ApplicationPolicy(  770): updateDataUsageMap
,D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
D/Tethering(  770): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  770): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/LocSvc_java(  770): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  243): DCD ON
,I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): noConnectivity : true
,I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=false
,D/dalvikvm( 3962): GC_CONCURRENT freed 7765K, 48% free 9925K/18968K, paused 4ms+3ms, total 61ms
,D/dalvikvm( 3962): WAIT_FOR_CONCURRENT_GC blocked 41ms
,I/KLMS-2.3.201 : ( 5548): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/wpa_supplicant( 1995): nl80211: Received scan results (12 BSSes)
I/wpa_supplicant( 1995): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1995): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1995): Trying to associate with  'G700'
I/wpa_supplicant( 1995): Re-associate with C0.AA.48
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1995): Cmd 35609 not handled
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,I/KLMS-2.3.201 : ( 5548): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361557973
,I/KLMS-2.3.201 : ( 5548): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,E/wpa_supplicant( 1995): Cmd 35605 not handled
E/wpa_supplicant( 1995): Cmd 35847 not handled
E/wpa_supplicant( 1995): Cmd 35848 not handled
,E/wpa_supplicant( 1995): Cmd 35605 not handled
I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1995): Associated with C0.AA.48
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1995): freq(2412) increment count 5
,I/wpa_supplicant( 1995): meet head of list.
,D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1995): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1995): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1995): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  770): interfaceLinkStateChanged wlan0, false
,D/Tethering(  770): interfaceStatusChanged wlan0, false
I/SA      ( 4056): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4056): [BDLM] already registered in spp
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
,E/Tethering(  770): No numeric data
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
D/Tethering(  770): interfaceStatusChanged wlan0, true
I/SA      ( 4056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 4056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
D/Tethering(  770): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiNative(  770): callSECApiVoid - ID [50]
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
D/Tethering(  770): interfaceLinkStateChanged wlan0, true
,D/Tethering(  770): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4056): [OR] == isSIMCardReady false ==
,I/SA      ( 4056): [SCU] == networkStateCheck == false
,I/SA      ( 4056): [OR] onReceive END
I/ConnectivityService(  770): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  770): performPollLocked(flags=0x1)
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5572): Other Intent
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 54ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/Headlines( 4111): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4111): getCountryCode(): countryCode = PL
,D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4111): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4111): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4111): requestUpdateNewsWelcomeCard !!! no welcome card
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3365): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4259f1b0
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,I/iu.Environment( 1788): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1788): num queued entries: 0
,I/iu.UploadsManager( 1788): num updated entries: 0
,I/iu.SyncManager( 1788): NEXT; no task
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,I/dhcpcd  ( 6316): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6316): bssid match
D/SSRMv2:SIOP(  770): SIOP:: AP = 310, Delta = 0
,D/WifiP2pService(  770): InactiveState{ what=143375 }
,D/WifiP2pService(  770): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/WifiStateMachine(  770): VerifyingLinkState enter
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  770): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  770): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
D/ConnectivityService(  770): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  770): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  770): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  770): mBoosterFLAG : 2
,I/WifiTrafficPoller(  770): current booster mode : BTCoexMode
D/ConnectivityService(  770): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  770): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  770): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,V/RouteController(  240): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/Toast   ( 1304):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1304): showing allowed
,V/RouteController(  240): /system/bin/ip -4 rule del table 2 2>&1
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,V/RouteController(  240): RTNETLINK answers: No such file or directory
V/RouteController(  240): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/SurfaceFlinger(  249): id=39 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  770): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  240): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  240): RTNETLINK answers: No such process
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
V/RouteController(  240): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  240): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/NetworkStats(  770): updateIfacesLocked()
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked(flags=0x1)
V/NetworkStats(  770): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
V/NetworkStats(  770): performPollLocked() took 17ms
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,D/NtpTrustedTime(  770): currentTimeMillis() cache hit
,I/jxcore-log( 6208): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 6208): 
,I/jxcore-log( 6208): my name is : samsung-SM-G800H_PT6030
I/jxcore-log( 6208): 
E/Watchdog(  770): !@Sync 5
,I/jxcore-log( 6208): attempting to connect to test coordinator
I/jxcore-log( 6208): 
,I/jxcore-log( 6208): check test folder
I/jxcore-log( 6208): 
,I/jxcore-log( 6208): found test : ./testFindPeers.js
I/jxcore-log( 6208): 
,I/jxcore-log( 6208): found test : ./testReConnect.js
I/jxcore-log( 6208): 
,I/jxcore-log( 6208): found test : ./testSendData.js
I/jxcore-log( 6208): 
,I/jxcore-log( 6208): Test app app.js loaded
I/jxcore-log( 6208): 
,I/chromium( 6208): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 6208): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6208): 
,D/Tethering(  770): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  770): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  770): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,E/SMD     (  243): DCD ON
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
,I/NetworkMonitor( 3903): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  770): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  770): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  770): ignore wifi update if we are not in OPENING or CLOSING
,I/KLMS-2.3.201 : ( 5548): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5548): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361560893
,I/KLMS-2.3.201 : ( 5548): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2521): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2521): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5560): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2446): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,V/KVNProvider( 5732): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5732): getFindoCursor query string : 
,V/KVNProvider( 5732): getTagSearchCursor() tagSearchCursor count : 0
,D/dalvikvm( 1207): GC_EXPLICIT freed 396K, 48% free 10047K/18968K, paused 5ms+5ms, total 58ms
,I/SA      ( 4056): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4056): [BDLM] already registered in spp
I/SA      ( 4056): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4056): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4056): [OR] == isSIMCardReady false ==
I/SA      ( 4056): [SCU] == networkStateCheck == true
,I/SA      ( 4056): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4056): isChinaCountryCode : false
I/SA      ( 4056): [OR] == networkStateCheck true ==
,I/SA      ( 4056): [OR] GetMyCountryZoneTask
I/SA      ( 4056): [OR] onReceive END
,I/SA      ( 4056): [SRS] prepareGetMyCountryZone
I/SA      ( 4056): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4056): [SSP] query invoked
I/SA      ( 4056): [TPMU] GetMccFromDB : null
I/SA      ( 4056): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4056): [TPM] isNoProxy(default) : true
,I/SA      ( 4056): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5572): Other Intent
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ClearcutLoggerApiImpl( 1320): disconnect managed GoogleApiClient
D/Headlines( 4111): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4111): getCountryCode(): countryCode = PL
D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4111): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4111): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4111): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4111): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3365): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4259f1b0
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/RCPManagerService(  770): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4212): notifyNetworkActivated
,D/hcjo    ( 4212): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4212): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4212): exit::IDLE
,D/InitializeManagerStateMachine( 4212): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4212): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4212): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4212): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4212): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4212): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4212): entry::SUCCESS
,D/hcjo    ( 4212): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4212): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4212): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4212): exit::SUCCESS
,D/InitializeManagerStateMachine( 4212): entry::IDLE
,I/iu.Environment( 1788): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1788): num queued entries: 0
,I/iu.UploadsManager( 1788): num updated entries: 0
,I/iu.SyncManager( 1788): NEXT; no task
,I/jxcore-log( 6208): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6208): 
,I/SA      ( 4056): [RC New] [v2liruge] api execute + 609
,I/SA      ( 4056): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4056): AsyncTask #5 calls detatch()
,I/SA      ( 4056): [TPMU] getNetworkMcc : 
,I/SA      ( 4056): [SCU] saveMccToPreferece Start
,I/SA      ( 4056): [SCU] RegionMCC : 260
,I/SA      ( 4056): [SSP] query invoked
,I/SA      ( 4056): [TPMU] GetMccFromDB : null
,I/SA      ( 4056): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4056): [SCU] saveMccToPreferece End
,I/SA      ( 4056): [RC New] executeRequest [v2liruge] end. 667
,I/SA      ( 4056): [RC New] Execute end
,I/SA      ( 4056): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4056): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService(  770): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/PowerManagerService(  770): [PWL] Off : 105s ago
,D/AmoledAdjustTimer(  770): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/WifiStateMachine(  770): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  249): id=39 Removed Uoast (12/13)
,I/SurfaceFlinger(  249): id=39 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  770): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=770 (0x0)
,D/PowerManagerService(  770): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=770, ws=WorkSource{1000}) (elapsedTime=3525)
,E/SMD     (  243): DCD ON
,I/jxcore-log( 6208): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6208): 
,I/dalvikvm( 6208): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 6208): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6208): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 6208): Shutting down VM
,W/dalvikvm( 6208): threadid=1: thread exiting with uncaught exception (group=0x417e4da0)
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/AndroidRuntime( 6208): FATAL EXCEPTION: main
E/AndroidRuntime( 6208): Process: com.test.thalitest, PID: 6208
E/AndroidRuntime( 6208): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 6208): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 6208): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 6208): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 6208): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 6208): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:153)
E/AndroidRuntime( 6208): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 6208): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 6208): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 6208): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 6208): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 6208): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6208): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6208): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 6208): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 6208): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 6208): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 6208): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 6208): 	at dalvik.system.NativeStart.main(Native Method)
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,I/Process ( 6208): Sending signal. PID: 6208 SIG: 9
,D/CrashAnrDetector(  770): processName: com.test.thalitest
,D/CrashAnrDetector(  770): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/WifiP2pStateTracker(  770): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5181): mConnectivityHandler : connected
,D/ConnectivityService(  770): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  770):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  770): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  770): updateSourceRoutes : no source routing conditions
,I/ActivityManager(  770): Process com.test.thalitest (pid 6208) (adj 1) has died.
,I/SurfaceFlinger(  249): id=34 Removed NainActivit (7/12)
I/WindowState(  770): WIN DEATH: Window{4314f6e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/ActivityManager(  770): Force removing ActivityRecord{42dd00b8 u0 com.test.thalitest/.MainActivity t3}: app died, no saved state
,I/SurfaceFlinger(  249): id=34 Removed NainActivit (-2/12)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,W/PCWCLIENTTRACE_AccountUtil( 5181): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5181): [GetString-S]
,I/terrier ( 5181): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5181): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5181): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5181): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5181): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5181): QSEECom_shutdown_app, app_id = 3
,E/terrier ( 5181): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5181): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5181): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5181): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5181): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5181): [ensureRegistration] - No Samsung account
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,D/Headlines( 4111): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4111): Breath 5799 latestRequest time : 1450361561038 current time : 1450361566837
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = -10
,E/SMD     (  243): DCD ON
,D/CaptivePortalTracker(  770): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  770): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  770): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  770): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  770): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  770): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  770): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  770): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4212): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4212): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4212): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4212): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4212): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4212): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4212): entry::IDLE
,D/AmoledAdjustTimer(  770): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 297, currTemp = 295, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 6
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 295, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,D/Headlines( 4111): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4111): Breath 35756 latestRequest time : 1450361561038 current time : 1450361596795
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,I/PowerManagerService(  770): [PWL] Off : 140s ago
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 292, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 7
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
V/AlarmManager(  770): waitForAlarm result :8
,D/Headlines( 4111): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4111): Breath 65752 latestRequest time : 1450361561038 current time : 1450361626791
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 180s ago
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 8
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,E/SMD     (  243): DCD ON
,D/Headlines( 4111): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4111): Breath 95759 latestRequest time : 1450361561038 current time : 1450361656799
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 9
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  770): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  770): waitForAlarm result :8
,D/Headlines( 4111): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,E/SMD     (  243): DCD ON
,D/Headlines( 4111): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4111): Breath 125776 latestRequest time : 1450361561038 current time : 1450361686820
,D/Headlines( 4111): stop 
,D/Headlines( 4111): Breath.onDestroy : 
,I/ActivityManager(  770): Killing 4442:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  770): initializing...
,I/TLC_TIMA_PKM_initialize(  770): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  770): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  770): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  770): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  770): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  770): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  770): max_message_size = 524416 = 0x80080,
,D/QSEECOMAPI: (  770): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  770): App is not loaded in QSEE
,D/QSEECOMAPI: (  770): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  770): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  770): Trustlet response is completed
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm(  770): GC_CONCURRENT freed 3438K, 58% free 24030K/55984K, paused 38ms+74ms, total 880ms
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 10
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 275s ago
,V/AlarmManager(  770): waitForAlarm result :4
,V/AlarmManager(  770): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer(  770): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/SELinux ( 6466): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6466):  
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,I/SELinux ( 6466): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6466):  
I/SELinux ( 6466):  
,I/SELinux ( 6466): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6466): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 6466): >>>>> Normal User
,E/dalvikvm( 6466): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 6466): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6466): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6466): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6466): Added TimaKesytore provider
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1254): onRestart, Launcher: 1113819120
,D/Launcher( 1254): onStart, Launcher: 1113819120
,D/Launcher.HomeView( 1254): onStart
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1447): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  249): id=40 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  249): id=41 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6466, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/ActivityManager(  770): Killing 4629:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 11
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,E/SMD     (  243): DCD ON
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 12
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 330s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 13
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 14
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 390s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 15
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 16
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 455s ago
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  770): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 17
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 18
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
E/SMD     (  243): DCD ON
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 19
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 525s ago
,D/AmoledAdjustTimer(  770): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  770): !@Sync 20
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 21
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 600s ago
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  770): waitForAlarm result :4
,D/LightsService(  770): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/SensorManagerA(  770): getReportingMode :: sensor.mType = 5
,D/Sensors (  770): LightSensor setDelay = 200000000
,D/Sensors (  770): LightSensor setSensorDelay = 200000000
,D/Sensors (  770): Light sensor flush: not enabled 0
,D/Sensors (  770): LightSensor enable = 1
,D/Sensors (  770): LightSensor enableSensor = 1
,D/SensorManager(  770): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  770): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/Sensors (  770): LightSensor enable = 0
,D/Sensors (  770): LightSensor enableSensor = 0
,D/SensorManager(  770): unregisterListener ::   
D/LightsService(  770): [SvcLED]  onSensorChanged::light value = 2
D/LightsService(  770): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,I/EventLogService( 1788): Aggregate from 1450360259609 (log), 1450360259609 (data)
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 22
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 23
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  770): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  770): <AppSync3 Whitelist>
,V/AlarmManager(  770): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 24
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 680s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  770): GC_CONCURRENT freed 3549K, 57% free 24031K/55220K, paused 22ms+38ms, total 484ms
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 25
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  243): DCD ON
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 26
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 27
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  770): [PWL] Off : 765s ago
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 28
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 29
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  770): !@Sync 30
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 855s ago
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,E/SMD     (  243): DCD ON
D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 31
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 32
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 33
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 950s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 34
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 35
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :4
,V/AlarmManager(  770): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  770): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 36
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 1050s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 37
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 38
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 39
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 40
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 1155s ago
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/dalvikvm(  770): GC_CONCURRENT freed 3545K, 57% free 24033K/55220K, paused 32ms+44ms, total 484ms
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 41
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  770): waitForAlarm result :8
,D/LightsService(  770): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  770): getReportingMode :: sensor.mType = 5
D/Sensors (  770): LightSensor setDelay = 200000000
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
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 42
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 43
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  770): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  770): <AppSync3 Whitelist>
,V/AlarmManager(  770): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  770): [PWL] Off : 1265s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 44
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 45
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 46
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 47
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 1380s ago
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 48
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 49
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  770): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 50
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 51
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  770): mCoverManager.getCoverState() : true
,E/SMD     (  243): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 1500s ago
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 52
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 53
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 54
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 55
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  770): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  770): [PWL] Off : 1625s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 56
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/dalvikvm(  770): GC_CONCURRENT freed 3521K, 57% free 24047K/55220K, paused 26ms+41ms, total 477ms
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  770): stay LED for fully charged
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 57
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 58
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 59
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/TimaService(  770): TIMA: TimaService scheduler is intialized. 
D/TimaService(  770): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  770): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON,
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  770): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  770): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 60
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  770): [PWL] Off : 1755s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 61
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,I/ActivityManager(  770): Killing 4585:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1803s
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  770): Prepared write state in 135ms
,I/ProcessStatsService(  770): Prepared write state in 111ms
,I/ProcessStatsService(  770): Prepared write state in 56ms
,I/ProcessStatsService(  770): Prepared write state in 39ms
,I/ProcessStatsService(  770): Prepared write state in 43ms
,I/ProcessStatsService(  770): Prepared write state in 33ms
,I/ProcessStatsService(  770): Prepared write state in 37ms
,I/ProcessStatsService(  770): Prepared write state in 33ms
,I/ProcessStatsService(  770): Pruning old procstats: /data/system/procstats/state-2015-12-16-20-31-06.bin
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 62
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  770): stay LED for fully charged
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  770): !@Sync 63
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  770): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  770): mCoverManager.getCoverState() : true
,D/BatteryService(  770): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,E/SMD     (  243): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1947): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  770): prevTemp = 270, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  770): waitForAlarm result :8
,V/AlarmManager(  770): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  770): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  770): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
V/AlarmManager(  770): (AppSync) ### 0 added ###
,I/ActivityManager(  770): Killing 5690:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1803s
,I/ActivityManager(  770): Killing 5395:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1811s
,I/ActivityManager(  770): Killing 5372:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1811s
,I/ActivityManager(  770): Killing 5352:com.samsung.helphub/1000 (adj 15): empty for 1811s
,I/ActivityManager(  770): Killing 5332:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1811s
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager(  770): Killing 5312:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1812s
,I/ActivityManager(  770): Killing 5278:com.google.android.apps.docs/u0a90 (adj 15): empty for 1812s
,I/ActivityManager(  770): Killing 5264:com.sec.android.service.cm/u0a78 (adj 15): empty for 1812s
,I/ActivityManager(  770): Killing 4709:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1812s
,I/ActivityManager(  770): Killing 4363:com.android.mms/u0a48 (adj 15): empty for 1813s
,I/ActivityManager(  770): Killing 5233:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1813s
,I/ActivityManager(  770): Killing 4271:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1813s
,I/ActivityManager(  770): Killing 5195:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1813s
,I/ActivityManager(  770): Killing 5167:com.android.musicfx/u0a24 (adj 15): empty for 1814s
,I/ActivityManager(  770): Killing 5154:com.samsung.groupcast/u0a15 (adj 15): empty for 1814s
,I/ActivityManager(  770): Killing 5138:com.google.android.partnersetup/u0a14 (adj 15): empty for 1814s
,I/ActivityManager(  770): Killing 5121:com.sec.android.inputmethod/1000 (adj 15): empty for 1814s
,I/ActivityManager(  770): Killing 5064:com.android.defcontainer/u0a6 (adj 15): empty for 1815s
,D/CountryDetector(  770): No listener is left
,E/SMD     (  243): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  243): DCD ON
D/BatteryService(  770): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
D/BatteryService(  770): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  770): mCoverManager.getCoverState() : true
D/BatteryService(  770): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1947): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1947): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/SSRMv2:SIOP(  770): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  770): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
E/SMD     (  243): DCD ON
E/Watchdog(  770): !@Sync 64
E/SMD     (  243): DCD ON
D/AndroidRuntime( 6870): 
D/AndroidRuntime( 6870): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6870): CheckJNI is OFF
D/AndroidRuntime( 6870): setted country_code = Poland
D/AndroidRuntime( 6870): setted countryiso_code = PL
D/AndroidRuntime( 6870): setted sales_code = XEO
D/AndroidRuntime( 6870): readGMSProperty: start
D/AndroidRuntime( 6870): readGMSProperty: already setted!!
D/AndroidRuntime( 6870): readGMSProperty: end
D/AndroidRuntime( 6870): addProductProperty: start
D/dalvikvm( 6870): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6870): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6870): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6870): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6870): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6870): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6870): failed to load memtrack module: -2
D/dalvikvm( 6870): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6870): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  770): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  770): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  770): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  770): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  770): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  770): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  770): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  770): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  770): getApplicationUninstallationEnabled
D/ApplicationPolicy(  770): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  770): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  770): START PACKAGE DELETE: observer{1123133400}
D/PackageManager(  770): pkg{<packageName>}
D/PackageManager(  770): user{0}
D/PackageManager(  770): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  770): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  770): !@killApplicatoin: 10179, uninstall pkg
W/PackageSettings(  770): Skipping PackageSetting{42c54800 com.example.hello/10181} due to missing metadata
D/PackageManager(  770): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1788): GC_EXPLICIT freed 1021K, 35% free 12401K/18968K, paused 3ms+12ms, total 108ms
D/dalvikvm( 1408): GC_EXPLICIT freed 4304K, 48% free 10031K/18968K, paused 5ms+8ms, total 70ms
D/PackageManager(  770): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 1088): onReceive: android.intent.action.PACKAGE_REMOVED
D/AdaptiveEventManager( 1069): action=android.intent.action.PACKAGE_REMOVED
I/InputReader(  770): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
D/QuickConnect[1.1][2] ( 3365): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/dalvikvm( 2168): GC_EXPLICIT freed 1019K, 41% free 11238K/18968K, paused 5ms+4ms, total 137ms
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "sms"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6894): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6894):  
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "smsto"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SMD     (  243): DCD ON
I/SELinux ( 6894): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6894):  
I/SELinux ( 6894):  
I/SELinux ( 6894): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6894): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6894): >>>>> Normal User
E/dalvikvm( 6894): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6894): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "mms"
D/dalvikvm(  770): GC_EXPLICIT freed 3124K, 57% free 24138K/55220K, paused 9ms+14ms, total 180ms
D/dalvikvm(  770): WAIT_FOR_CONCURRENT_GC blocked 39ms
D/TimaKeyStoreProvider( 6894): in addTimaSignatureService
D/TimaKeyStoreProvider( 6894): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6894): Added TimaKesytore provider
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "mmsto"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  770): PackageReceiver onReceive()
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "sms"
I/HarmonyEASService(  770): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "smsto"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  770): Package has changed for user 0
D/EnterpriseDeviceManagerService(  770): Admin package name: com.google.android.gms
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6894, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "mms"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "mmsto"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 6894): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6894): ELMEngine.ELMEngine( context ).
D/elm:14132( 6894): MDMBridge.setEnterpriseBridge()
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 6894): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6894): ElmAgentService : onCreate()
D/elm:14132( 6894): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6894): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6894): MDMBridge.getInstance()
D/elm:14132( 6894): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6894): MDMBridge.getAllLicenseInfoFromSDK()
D/dalvikvm(  770): GC_EXPLICIT freed 684K, 57% free 24096K/55220K, paused 7ms+20ms, total 186ms
D/PackageManager(  770): delete sourFile : 
I/SELinux ( 6911): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6911):  
D/elm:14132( 6894): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService(  770): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/elm:14132( 6894): ElmAgentService : onDestroy().
V/BackupManagerService(  770): removePackageParticipantsLocked: uid=10179 #1
D/PackageManager(  770): delete native library directory: 
D/PackageManager(  770): return delete result to caller: 1123133400
D/AndroidRuntime( 6870): Shutting down VM
I/SELinux ( 6911): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6911):  
I/SELinux ( 6911):  
I/SELinux ( 6911): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm( 6870): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
E/SELinux ( 6911): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6911): >>>>> Normal User
E/dalvikvm( 6911): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6911): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager(  770): returnCode: 1
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "sms"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6911): in addTimaSignatureService
D/TimaKeyStoreProvider( 6911): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6911): Added TimaKesytore provider
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "smsto"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "mms"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  770):   Action: "android.intent.action.SENDTO"
I/PackageManager(  770):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  770):   Scheme: "mmsto"
I/PackageManager(  770): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  770): Permission Denial: getCurrentUser() from pid=6911, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 6911): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42594900, skipping init
I/SecureStorage( 6911): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6911): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  316): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6911
I/SecureStorage(  316): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6911): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 6911): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  316): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6911
I/SecureStorage(  316): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  770): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  770): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  770): clearDefaults: com.test.thalitest
D/InputReader(  770): Processing first event
W/ApplicationsProvider( 1408): Could not fetch usage stats
W/ApplicationsProvider( 1408): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1408): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1408): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1408): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1408): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1408): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1408): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1408): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1408): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1408): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1408): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
