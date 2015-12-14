#### Test 5357450766a890e_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
D/TimaKeyStoreProvider( 5185): in addTimaSignatureService
D/TimaKeyStoreProvider( 5185): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5185): Added TimaKesytore provider
D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9507K/18980K, paused 2ms+2ms, total 21ms
,--------- beginning of /dev/log/system
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5185, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  231): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5185): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  231): Returning OperationFailed - no handler for errno 30
E/cutils  (  231): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5185): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  729): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  231): Returning OperationFailed - no handler for errno 30
I/SA      ( 4034): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4034): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4034): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4324): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2191): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5216): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5216):  
I/SELinux ( 5216): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5216):  
I/SELinux ( 5216):  
I/SELinux ( 5216): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5216): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5216): >>>>> Normal User
E/dalvikvm( 5216): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5216): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/AndroidRuntime( 5203): 
D/AndroidRuntime( 5203): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5203): CheckJNI is OFF
D/AndroidRuntime( 5203): setted country_code = Poland
D/AndroidRuntime( 5203): setted countryiso_code = PL
D/AndroidRuntime( 5203): setted sales_code = XEO
D/AndroidRuntime( 5203): readGMSProperty: start
D/AndroidRuntime( 5203): readGMSProperty: already setted!!
D/AndroidRuntime( 5203): readGMSProperty: end
D/AndroidRuntime( 5203): addProductProperty: start
D/TimaKeyStoreProvider( 5216): in addTimaSignatureService
D/dalvikvm( 5203): Trying to load lib libjavacore.so 0x0
D/TimaKeyStoreProvider( 5216): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5216): Added TimaKesytore provider
D/dalvikvm( 5203): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5203): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5203): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5203): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2191): GC_CONCURRENT freed 6483K, 41% free 11204K/18980K, paused 8ms+3ms, total 142ms
D/dalvikvm( 2191): WAIT_FOR_CONCURRENT_GC blocked 61ms
D/CapabilityManagerService New( 5216): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5216, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5237): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5237):  
I/ActivityManager(  729): Killing 3972:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/ActivityManager(  729): Killing 4246:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5237): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5237):  
I/SELinux ( 5237):  
I/SELinux ( 5237): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5237): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5237): >>>>> Normal User
E/dalvikvm( 5237): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5237): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5237): in addTimaSignatureService
D/TimaKeyStoreProvider( 5237): Cannot add TimaSignature Service, License check Failed
E/SMD     (  244): DCD ON
D/ActivityThread( 5237): Added TimaKesytore provider
E/memtrack( 5203): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5203): failed to load memtrack module: -2
I/IcingCorporaProvider( 2191): UpdateCorporaTask done [took 295 ms] updated apps [took 295 ms] 
D/dalvikvm( 5203): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5203): Calling main entry com.android.commands.am.Am
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5237, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
V/ApplicationPolicy(  729): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  729): mDVFSHelper.acquire()
I/SELinux ( 5251): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5251):  
D/LockPatternUtils( 1069): isPcwEnable = null
D/AndroidRuntime( 5203): Shutting down VM
D/dalvikvm( 5203): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
I/SELinux ( 5251): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5251):  
I/SELinux ( 5251):  
I/SELinux ( 5251): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5251): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5251): >>>>> Normal User
E/dalvikvm( 5251): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5251): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5251): in addTimaSignatureService
D/TimaKeyStoreProvider( 5251): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5251): Added TimaKesytore provider
D/LockPatternUtils( 1069): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2108): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2108): getDatabaseLocked(b,b,pwd)...
D/SurfaceWidgetView( 1246): destroyHardwareResources():1125911120
I/SurfaceFlinger(  250): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  250): id=13 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  250): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  250): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1462): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1246): onTrimMemory. Level: 20
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5251, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5251, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5251): Binding Chromium to the background looper Looper (main, tid 1) {422911d8}
I/chromium( 5251): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5251): Initializing chromium process, renderers=0
W/chromium( 5251): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5251): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5251): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5251): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5251): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5251): Remote Branch: 
I/Adreno-EGL( 5251): Local Patches: 
I/Adreno-EGL( 5251): Reconstruct Branch: 
,I/dalvikvm( 5251): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5251): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5251): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5251): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5251): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5251): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5251): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5251): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5251): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5251): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5251): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5251): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5251): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5251): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5251): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5251): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5251): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5251): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5251): CordovaWebView is running on device made by: samsung
,I/SELinux ( 5286): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5286):  
I/ActivityManager(  729): Killing 3985:com.sec.android.soagent/u0a37 (adj 15): empty #43
,W/GAV2    ( 5237): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 5286): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5286):  
I/SELinux ( 5286):  
,I/SELinux ( 5286): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5286): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5286): >>>>> Normal User
,E/dalvikvm( 5286): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 5286): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5286): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5286): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5286): Added TimaKesytore provider
,I/SurfaceFlinger(  250): id=16 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5251): EGLImpl-HWUI Protected EGL context created
,D/PackageIntentReceiver( 5286): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 5286): Not GearManger package! 
,D/OpenGLRenderer( 5251): Enabling debug mode 0
,I/SELinux ( 5313): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5313):  
,W/AwContents( 5251): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  729): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SELinux ( 5313): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5313):  
I/SELinux ( 5313):  
I/SELinux ( 5313): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5313): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5313): >>>>> Normal User
E/dalvikvm( 5313): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5313): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5313): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5313): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5313): Added TimaKesytore provider
,D/MagazineService Version( 5313): Magazine-Channel: 13
,D/MagazineService Version( 5313): Magazine-Provider: 13
,D/MagazineService Version( 5313): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 5313): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 5313): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5313, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,I/MagazineService::MagazineService( 5313): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5327): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5327):  
D/MagazineService::MagazineService( 5313): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/ActivityManager(  729): Killing 4362:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
,I/SELinux ( 5327): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5327):  
I/SELinux ( 5327):  
,I/SELinux ( 5327): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
W/GAV2    ( 5237): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,E/SELinux ( 5327): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5327): >>>>> Normal User
,E/dalvikvm( 5327): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 5327): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager(  729): Killing 4377:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5327): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5327): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5327): Added TimaKesytore provider
,D/JsMessageQueue( 5251): Set native->JS mode to OnlineEventsBridgeMode
,I/SELinux ( 5343): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5343):  
I/ActivityManager(  729): Killing 4389:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5343): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5343):  
I/SELinux ( 5343):  
,I/SELinux ( 5343): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5343): >>>>> Normal User
,E/dalvikvm( 5343): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5343): in addTimaSignatureService
D/TimaKeyStoreProvider( 5343): Cannot add TimaSignature Service, License check Failed
D/dalvikvm( 5251): Trying to load lib /data/app-lib/com.test.thalitest-38/libjxcore.so 0x425b7f10
D/ActivityThread( 5343): Added TimaKesytore provider
D/dalvikvm( 5251): Added shared lib /data/app-lib/com.test.thalitest-38/libjxcore.so 0x425b7f10
D/jxcore_app_log( 5251): JniHelper::setJavaVM(0x416f8528), pthread_self() = 2032777416
D/JX-Cordova( 5251): jxcore cordova android initializing
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5343, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 5343): Package not found : com.sec.android.app.kidshome
I/SELinux ( 5355): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5355):  
I/ActivityManager(  729): Killing 3565:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
I/SELinux ( 5355): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5355):  
I/SELinux ( 5355):  
I/SELinux ( 5355): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5355): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5355): >>>>> Normal User
E/dalvikvm( 5355): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
E/SELinux ( 5355): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5355): in addTimaSignatureService
D/TimaKeyStoreProvider( 5355): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5355): Added TimaKesytore provider
I/ActivityManager(  729): Killing 4416:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
D/Finsky  ( 3666): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/PackageBroadcastService( 1759): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1759): Loading module APK com.google.android.play.games
I/dalvikvm( 1759): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1759): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0053
I/dalvikvm( 1759): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1759): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1759): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1759): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1759): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1759): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1759): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1759): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
D/dalvikvm( 5251): GC_CONCURRENT freed 4920K, 33% free 12767K/18980K, paused 3ms+2ms, total 35ms
D/dalvikvm( 5251): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/dalvikvm( 5251): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1759): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1759): GC_CONCURRENT freed 1898K, 38% free 11880K/18980K, paused 8ms+5ms, total 90ms
D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1759): Submit a task: k
D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.vision from APK com.google.android.gms
W/BaseAppContext( 1759): Using Auth Proxy for data requests.
W/BaseAppContext( 1759): Using Auth Proxy for data requests.
D/k       ( 1759): Processing package: com.test.thalitest
D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@9
D/GassUtils( 1759): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
D/k       ( 1759): Found info for package com.test.thalitest in db.
W/BaseAppContext( 1759): Using Auth Proxy for data requests.
W/BaseAppContext( 1759): Using Auth Proxy for data requests.
W/BaseAppContext( 1759): Using Auth Proxy for data requests.
W/BaseAppContext( 1759): Using Auth Proxy for data requests.
W/BaseAppContext( 1759): Using Auth Proxy for data requests.
W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1759): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1759): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1759): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1759): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1759): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1759): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1759): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1759): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1759): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1759): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0006
I/PeopleDatabaseHelper( 1759): cleanUpNonGplusAccounts done.
,D/dalvikvm( 5251): GC_FOR_ALLOC freed 4775K, 28% free 15780K/21868K, paused 35ms, total 35ms
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1759): Module APK com.google.android.play.games already loaded
,D/AmoledAdjustTimer(  729): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/dalvikvm( 5251): GC_FOR_ALLOC freed 5160K, 32% free 16809K/24596K, paused 38ms, total 39ms
,I/dalvikvm-heap( 5251): Grow heap (frag case) to 22.071MB for 2511452-byte allocation
,I/Icing   ( 1759): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,E/SMD     (  244): DCD ON
,I/Icing   ( 1759): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/dalvikvm( 5251): GC_FOR_ALLOC freed 3810K, 36% free 17498K/27052K, paused 37ms, total 38ms
,D/dalvikvm( 5251): GC_FOR_ALLOC freed 1274K, 36% free 17405K/27052K, paused 31ms, total 33ms
,W/jxcore-log( 5251): Initializing JXcore engine
,W/jxcore-log( 5251): JXcore engine is ready
,W/jxcore-log( 5251): Starting JXcore engine
,W/jxcore-log( 5251): Platform android
W/jxcore-log( 5251): 
,W/jxcore-log( 5251): Process ARCH arm
W/jxcore-log( 5251): 
,D/SSRMv2:SIOP(  729): SIOP:: AP = 330, Delta = 20
,I/jxcore-log( 5251): JXcore Cordova bridge is ready!
I/jxcore-log( 5251): 
W/jxcore-log( 5251): JXcore engine is started
I/chromium( 5251): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 5251): Toggling radios to true
I/jxcore-log( 5251): 
D/BluetoothAdapter( 5251): enable(): BT is already enabled..!
I/WifiManager( 5251): packageName : com.test.thalitest
I/WifiManager( 5251): setWifiEnabled : true
I/WifiService(  729): setWifiEnabled: true pid=5251, uid=10179
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5251, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  729): Failed getting userId using ActivityManagerNative
W/WifiService(  729): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5251, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  729): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  729): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  729): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  729): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  729): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  729): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService(  729): disconnect: pid=5251, uid=10179
I/wpa_supplicant( 1979): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 5251): Radios toggled
I/jxcore-log( 5251): 
I/wpa_supplicant( 1979): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1979): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1979): Cmd 35605 not handled
E/wpa_supplicant( 1979): Cmd 35605 not handled
I/wpa_supplicant( 1979): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
D/Tethering(  729): interfaceStatusChanged wlan0, false
D/Tethering(  729): InitialState.processMessage what=4
E/Tethering(  729): No numeric data
D/Tethering(  729): sendTetherStateChangedBroadcast 0, 0, 0
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  729): performPollLocked(flags=0x1)
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
D/Tethering(  729): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1979): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1979): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1979): First Scan Start
I/wpa_supplicant( 1979): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings(  729): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
D/Tethering(  729): interfaceStatusChanged wlan0, false
I/WifiStateMachine(  729): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService(  729): InactiveState{ what=143375 }
D/WifiP2pService(  729): P2pEnabledState{ what=143375 }
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked() took 50ms
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/CommandListener(  241): Clearing all IP addresses on wlan0
I/WifiTrafficPoller(  729): evaluateTrafficStatsPolling
D/ConnectivityService(  729): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  729): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  729): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  729): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  729): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  729): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
I/wpa_supplicant( 1979): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1979): Skip scan - already scanning
D/ConnectivityService(  729): Attempting to switch to mobile
D/ConnectivityService(  729): Attempting to switch to BLUETOOTH_TETHER
D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
I/SELinux ( 5391): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5391):  
D/WifiP2pService(  729): InactiveState{ what=143375 }
D/WifiP2pService(  729): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/CommandListener(  241): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
I/WifiTrafficPoller(  729): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
E/WifiStateMachine(  729): Error! unhandled message{ when=-60ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  729): Error! unhandled message{ when=-60ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController(  241): /system/bin/ip -6 route del default table 2 2>&1
E/WifiStateMachine(  729): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/SELinux ( 5391): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5391):  
I/SELinux ( 5391):  
I/SELinux ( 5391): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5391): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5391): >>>>> Normal User
,E/dalvikvm( 5391): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5391): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController(  241): RTNETLINK answers: No such process
,V/RouteController(  241): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController(  241): RTNETLINK answers: No such file or directory
,D/TimaKeyStoreProvider( 5391): in addTimaSignatureService
,W/NetworkManagementService(  729): route cmd failed: 
W/NetworkManagementService(  729): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 route del src v6 2' failed with '400 38 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  729): '
W/NetworkManagementService(  729): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  729): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  729): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  729): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  729): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  729): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  729): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  729): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  729): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  729): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  729): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  729): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  729): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/RouteController(  241): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 5391): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5391): Added TimaKesytore provider
,V/RouteController(  241): RTNETLINK answers: No such process
,V/RouteController(  241): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  241): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  729): android_net_utils_resetConnections in env=0x79e36450 clazz=0x6b500001 iface=wlan0 mask=0x3
D/ConnectivityService(  729): resetConnections(wlan0, 3)
,V/NativeCrypto( 1309): Read error: ssl=0x7bfbb570: I/O error during system call, Connection timed out
,V/NetworkStats(  729): updateIfacesLocked()
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked(flags=0x1)
V/NetworkStats(  729): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/System.out( 5391): Inside WakeupProvider
,I/System.out( 5391): Inside onCreate() of WakeupTriggerProvide
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked() took 18ms
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/dalvikvm( 1309): GC_EXPLICIT freed 862K, 44% free 10776K/18980K, paused 3ms+12ms, total 83ms
,V/NativeCrypto( 1309): SSL shutdown failed: ssl=0x7bfbb570: I/O error during system call, Broken pipe
,D/ConnectivityService(  729): handleInetConditionChange: no active default network - ignore
,I/VlingoApplication( 5391): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5391): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5391): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1364): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1364): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1364): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5391): initQueue()
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1364): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1364): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1364): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  729): Killing 4431:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/GAV2    ( 5237): Thread[GAThread,5,main]: No campaign data found.
,I/ApplicationPolicy(  729): updateDataUsageMap
,D/Tethering(  729): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  729): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  729): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  729): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1462): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5140): SPPPushClient is installed : true
,I/NetworkMonitor( 3886): type=WIFI subType= reason=null isConnected=false
I/PCWCLIENTTRACE_PushUtil( 5140): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5140): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5140): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5140): noConnectivity : true
,D/LocSvc_java(  729): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  729): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  729): ignore wifi update if we are not in OPENING or CLOSING
,I/SELinux ( 5424): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5424):  
,I/SELinux ( 5424): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5424):  
I/SELinux ( 5424):  
,I/SELinux ( 5424): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5424): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5424): >>>>> Normal User
,E/dalvikvm( 5424): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5424): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5424): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5424): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5424): Added TimaKesytore provider
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5424, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,V/AlarmManager(  729): waitForAlarm result :4
,V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/wpa_supplicant( 1979): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 1979): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1979): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1979): Trying to associate with  'G700'
I/wpa_supplicant( 1979): Re-associate with C0.AA.48
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
,E/wpa_supplicant( 1979): Cmd 35609 not handled
,E/wpa_supplicant( 1979): Cmd 35605 not handled
E/wpa_supplicant( 1979): Cmd 35847 not handled
E/wpa_supplicant( 1979): Cmd 35848 not handled
,E/wpa_supplicant( 1979): Cmd 35605 not handled
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1979): Associated with C0.AA.48
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1979): freq(2412) increment count 2
,I/wpa_supplicant( 1979): meet head of list.
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1979): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1979): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
D/Tethering(  729): interfaceLinkStateChanged wlan0, true
,D/Tethering(  729): interfaceStatusChanged wlan0, true
D/Tethering(  729): interfaceLinkStateChanged wlan0, true
,D/Tethering(  729): interfaceStatusChanged wlan0, true
,I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
D/dalvikvm(  729): GC_EXPLICIT freed 2688K, 60% free 23889K/58744K, paused 7ms+22ms, total 176ms
E/Tethering(  729): No numeric data
D/Tethering(  729): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/Tethering(  729): interfaceLinkStateChanged wlan0, true
,D/Tethering(  729): interfaceStatusChanged wlan0, true
,D/Tethering(  729): interfaceLinkStateChanged wlan0, true
D/Tethering(  729): interfaceStatusChanged wlan0, true
,D/WifiNative(  729): callSECApiVoid - ID [50]
D/Tethering(  729): interfaceLinkStateChanged wlan0, true
,D/Tethering(  729): interfaceStatusChanged wlan0, true
V/NetworkStats(  729): performPollLocked(flags=0x1)
I/ActivityManager(  729): Killing 4456:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked() took 28ms
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  244): DCD ON
,D/WifiP2pService(  729): InactiveState{ what=143375 }
,D/WifiP2pService(  729): P2pEnabledState{ what=143375 }
,I/SELinux ( 5446): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5446):  
,D/dalvikvm(  251): GC_EXPLICIT freed 43K, 50% free 9506K/18980K, paused 2ms+2ms, total 25ms
,D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9506K/18980K, paused 2ms+3ms, total 19ms
,I/SELinux ( 5446): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5446):  
I/SELinux ( 5446):  
,I/SELinux ( 5446): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5446): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5446): >>>>> Normal User
,E/dalvikvm( 5446): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
E/SELinux ( 5446): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9506K/18980K, paused 2ms+3ms, total 19ms
D/TimaKeyStoreProvider( 5446): in addTimaSignatureService
D/TimaKeyStoreProvider( 5446): Cannot add TimaSignature Service, License check Failed
D/FactoryTest( 4741): Not factory mode
D/FactoryTest( 4741): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4741): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4741): still no open session command from host, so toast
D/ActivityThread( 5446): Added TimaKesytore provider
W/ContextImpl( 4741): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4741): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  729): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  729): mDVFSHelper.acquire()
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/LockPatternUtils( 1069): isPcwEnable = null
,E/MTPRx   ( 4741): started activity for popup
,I/SQLiteSecureOpenHelper( 2108): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2108): getDatabaseLocked(b,b,pwd)...
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5446, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,E/SettingsReceiverActivity( 4741): PREF_DONT_ASK_AGAIN : false
,I/dhcpcd  ( 5458): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5458): bssid match
,D/SettingsReceiverActivity( 4741): dev.kiessupport is : TRUE
,I/ActivityManager(  729): Killing 4476:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5470): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5470):  
,I/SurfaceFlinger(  250): id=17 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4741): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4741): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4741): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4741): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4741): Remote Branch: 
I/Adreno-EGL( 4741): Local Patches: 
I/Adreno-EGL( 4741): Reconstruct Branch: 
,I/SELinux ( 5470): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5470):  
I/SELinux ( 5470):  
,I/SELinux ( 5470): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5470): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5470): >>>>> Normal User
,E/dalvikvm( 5470): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5470): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/HWUI    ( 4741): EGLImpl-HWUI Protected EGL context created
,D/TimaKeyStoreProvider( 5470): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5470): Cannot add TimaSignature Service, License check Failed
,D/OpenGLRenderer( 4741): Enabling debug mode 0
,D/ActivityThread( 5470): Added TimaKesytore provider
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5470, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5470): KLMSValidator() : checkQATesting()
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  729): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/KLMS-2.3.201 : ( 5470): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450106385325
I/KLMS-2.3.201 : ( 5470): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager(  729): Killing 1331:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 5484): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5484):  
,I/SELinux ( 5484): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5484):  
I/SELinux ( 5484):  
,I/SELinux ( 5484): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5484): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5484): >>>>> Normal User
,E/dalvikvm( 5484): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5484): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5484): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5484): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5484): Added TimaKesytore provider
,D/SO_AGENT( 5484): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5484): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5484, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/SA      ( 4034): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4034): [BDLM] already registered in spp
I/SA      ( 4034): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4034): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4034): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4034): [OR] == isSIMCardReady false ==
I/SA      ( 4034): [SCU] == networkStateCheck == false
,I/SA      ( 4034): [OR] onReceive END
I/ActivityManager(  729): Killing 4603:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,I/SELinux ( 5496): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5496):  
,I/SELinux ( 5496): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5496):  
I/SELinux ( 5496):  
,I/SELinux ( 5496): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5496): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5496): >>>>> Normal User
,E/dalvikvm( 5496): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5496): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5496): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5496): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5496): Added TimaKesytore provider
,I/sCloudBackupApp( 5496): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5496): Other Intent
I/ActivityManager(  729): Killing 4631:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/com.samsung.app( 1462): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1462): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5509): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5509):  
,I/SELinux ( 5509): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5509):  
I/SELinux ( 5509):  
,I/SELinux ( 5509): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5509): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5509): >>>>> Normal User
,E/dalvikvm( 5509): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5509): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5509): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5509): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5509): Added TimaKesytore provider
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5509, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  729): Killing 4644:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/Headlines( 4085): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4085): getCountryCode(): countryCode = PL
,D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4085): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4085): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4085): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5522): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5522):  
,I/SELinux ( 5522): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5522):  
I/SELinux ( 5522):  
,I/SELinux ( 5522): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5522): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5522): >>>>> Normal User
,E/dalvikvm( 5522): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5522): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5522): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5522): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5522): Added TimaKesytore provider
,E/cutils  (  231): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    (  231): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5522): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  231): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5522): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  231): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 5522): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  231): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5522): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  231): Returning OperationFailed - no handler for errno 30
,E/cutils  (  231): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5522): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  231): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 5522): Binding Chromium to the main looper Looper (main, tid 1) {42293100}
,I/chromium( 5522): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5522): Initializing chromium process, renderers=0
,I/Adreno-EGL( 5522): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5522): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5522): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5522): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5522): Remote Branch: 
I/Adreno-EGL( 5522): Local Patches: 
I/Adreno-EGL( 5522): Reconstruct Branch: 
,W/chromium( 5522): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/NSApplication( 5522): Starting up...
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5522, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  729): Killing 4695:com.google.android.talk/u0a105 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 3342): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3342): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3342): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425c5330
,D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 5560): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5560):  
,I/SELinux ( 5560): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5560):  
I/SELinux ( 5560):  
,I/SELinux ( 5560): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5560): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5560): >>>>> Normal User
E/dalvikvm( 5560): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5560): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5560): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5560): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5560): Added TimaKesytore provider
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
I/ActivityManager(  729): Killing 3021:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,I/SELinux ( 5598): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5598):  
,I/SELinux ( 5602): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5602):  
,D/WifiP2pService(  729): InactiveState{ what=143375 }
,D/WifiP2pService(  729): P2pEnabledState{ what=143375 }
,I/SELinux ( 5598): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5598):  
I/SELinux ( 5598):  
,I/SELinux ( 5598): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5598): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5598): >>>>> Normal User
,E/dalvikvm( 5598): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5598): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/SELinux ( 5602): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5602):  
I/SELinux ( 5602):  
,I/SELinux ( 5602): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5602): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5602): >>>>> Normal User
,E/dalvikvm( 5602): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,D/WifiStateMachine(  729): VerifyingLinkState enter
,E/SELinux ( 5602): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5598): in addTimaSignatureService
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/TimaKeyStoreProvider( 5598): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5598): Added TimaKesytore provider
,D/WifiStateMachine(  729): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  729): CaptivePortalCheckState enter
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,W/ActivityManager(  729): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/WifiTrafficPoller(  729): evaluateTrafficStatsPolling
,D/WifiStateMachine(  729): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  729): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  729): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/TimaKeyStoreProvider( 5602): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5602): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5602): Added TimaKesytore provider
,I/WifiTrafficPoller(  729): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  729): mBoosterFLAG : 2
,I/WifiTrafficPoller(  729): current booster mode : BTCoexMode
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  729): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  729): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  729): net.tcp.delack.wifi not found in system properties. Using defaults
,I/ActivityManager(  729): Killing 4790:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  729): handleConnectivityChange: setting default proxy info 
,V/RouteController(  241): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  241): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  241): RTNETLINK answers: No such file or directory
,V/RouteController(  241): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
D/BadgeProvider( 5602): onCreate
,D/BadgeProvider( 5602): DatabaseHelper
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5602, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,V/RouteController(  241): /system/bin/ip route flush cached 2>&1
,V/RouteController(  241): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/BadgeProvider( 5602): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/RouteController(  241): RTNETLINK answers: No such process
,V/RouteController(  241): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/Launcher.Model( 1246): reloadBadges entered.
,D/BadgeProvider( 5602): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5602): sendNotify, [notify] : null
D/BadgeProvider( 5602): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5602): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5602): update, [UpdateCount] : 1
,V/RouteController(  241): /system/bin/ip route flush cached 2>&1
,V/NetworkStats(  729): updateIfacesLocked()
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked() took 18ms
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5598, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/hcjo    ( 4172): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4172): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4172): exit::IDLE
,D/InitializeManagerStateMachine( 4172): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4172): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4172): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4172): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4172): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4172): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4172): entry::SUCCESS
,D/hcjo    ( 4172): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4172): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4172): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4172): exit::SUCCESS
,D/InitializeManagerStateMachine( 4172): entry::IDLE
I/ActivityManager(  729): Killing 4809:com.wssyncmldm/1000 (adj 15): empty #43
,D/Headlines( 4085): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4085): Breath 1149 latestRequest time : 1450106385907 current time : 1450106387056
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1364): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1364): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1364): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1364): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1364): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1364):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1364): showing allowed
,I/SurfaceFlinger(  250): id=18 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  729): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=729
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1364): MountReceiver.onReceive - Keep current state
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/VacuumService( 1219): Vacuum at: now=1450106387291 tag=VacuumService
,I/jxcore-log( 5251): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5251): 
,I/jxcore-log( 5251): my name is : samsung-SM-G800H_PT8286
I/jxcore-log( 5251): 
,D/dalvikvm( 1759): GC_CONCURRENT freed 1603K, 36% free 12227K/18980K, paused 5ms+5ms, total 49ms
,I/jxcore-log( 5251): attempting to connect to test coordinator
I/jxcore-log( 5251): 
,I/jxcore-log( 5251): check test folder
I/jxcore-log( 5251): 
,I/jxcore-log( 5251): found test : ./testFindPeers.js
I/jxcore-log( 5251): 
,I/jxcore-log( 5251): found test : ./testReConnect.js
I/jxcore-log( 5251): 
,I/jxcore-log( 5251): found test : ./testSendData.js
I/jxcore-log( 5251): 
,D/Tethering(  729): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  729): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  729): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/LocSvc_java(  729): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  729): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  729): ignore wifi update if we are not in OPENING or CLOSING
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1462): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3886): type=WIFI subType= reason=null isConnected=true
I/PCWCLIENTTRACE_PushUtil( 5140): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5140): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5140): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5140): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/jxcore-log( 5251): Test app app.js loaded
I/jxcore-log( 5251): 
,I/chromium( 5251): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,I/KLMS-2.3.201 : ( 5470): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/SMD     (  244): DCD ON
,I/KLMS-2.3.201 : ( 5470): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450106387668
,I/KLMS-2.3.201 : ( 5470): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5484): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2577): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2577): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2577): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2577): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5484): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2426): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5649): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5649):  
,I/SELinux ( 5649): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5649):  
I/SELinux ( 5649):  
,I/SELinux ( 5649): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5649): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 5653): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5653):  
E/dalvikvm( 5649): >>>>> Normal User
,E/dalvikvm( 5649): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5649): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5649): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5649): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5649): Added TimaKesytore provider
,I/SELinux ( 5653): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5653):  
I/SELinux ( 5653):  
,I/SELinux ( 5653): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5653): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5653): >>>>> Normal User
,E/dalvikvm( 5653): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5653): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 4034): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4034): [BDLM] already registered in spp
,I/SA      ( 4034): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4034): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4034): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4034): [OR] == isSIMCardReady false ==
,D/TimaKeyStoreProvider( 5653): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5653): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5653): Added TimaKesytore provider
,I/SA      ( 4034): [SCU] == networkStateCheck == true
I/SA      ( 4034): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4034): isChinaCountryCode : false
,I/SA      ( 4034): [OR] == networkStateCheck true ==
,I/SA      ( 4034): [OR] GetMyCountryZoneTask
,I/SA      ( 4034): [OR] onReceive END
,I/SA      ( 4034): [SRS] prepareGetMyCountryZone
,V/KVNProvider( 5653): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5653): getFindoCursor query string : 
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,I/SA      ( 4034): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4034): [SSP] query invoked
,I/SCloudBackupReceiver( 5496): Other Intent
I/SA      ( 4034): [TPMU] GetMccFromDB : null
I/SA      ( 4034): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4034): [TPM] isNoProxy(default) : true
,I/SA      ( 4034): [RC New] Execute method=[GET] start
,D/com.samsung.app( 1462): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1462): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,V/KVNProvider( 5653): getTagSearchCursor() tagSearchCursor count : 0
,D/Headlines( 4085): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4085): getCountryCode(): countryCode = PL
D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4085): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4085): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4085): requestUpdateNewsWelcomeCard !!! no welcome card
I/ActivityManager(  729): Killing 4650:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 3342): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3342): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3342): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425c5330
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/hcjo    ( 4172): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4172): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4172): exit::IDLE
,D/InitializeManagerStateMachine( 4172): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4172): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4172): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4172): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4172): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4172): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4172): entry::SUCCESS
,D/hcjo    ( 4172): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4172): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4172): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4172): exit::SUCCESS
,D/InitializeManagerStateMachine( 4172): entry::IDLE
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,I/SA      ( 4034): [RC New] [v2liruge] api execute + 643
,I/SA      ( 4034): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4034): AsyncTask #2 calls detatch()
,I/SA      ( 4034): [TPMU] getNetworkMcc : 
,I/SA      ( 4034): [SCU] saveMccToPreferece Start
,I/SA      ( 4034): [SCU] RegionMCC : 260
,I/SA      ( 4034): [SSP] query invoked
,I/SA      ( 4034): [TPMU] GetMccFromDB : null
I/SA      ( 4034): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4034): [SCU] saveMccToPreferece End
,I/SA      ( 4034): [RC New] executeRequest [v2liruge] end. 663
,I/SA      ( 4034): [RC New] Execute end
,I/SA      ( 4034): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4034): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine(  729): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/WifiP2pStateTracker(  729): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  729): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  729):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  729): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  729): updateSourceRoutes : no source routing conditions
,E/SMD     (  244): DCD ON
,I/HarmonyEASService(  729): Updating for all 1
,I/SurfaceFlinger(  250): id=18 Removed Uoast (12/13)
,I/SurfaceFlinger(  250): id=18 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  729): Killing 4203:com.android.calendar/u0a142 (adj 15): empty #43
D/PowerManagerService(  729): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=729 (0x0)
D/PowerManagerService(  729): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=729, ws=WorkSource{1000}) (elapsedTime=3480)
,D/AmoledAdjustTimer(  729): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,I/GAV2    ( 5522): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 5251): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5251): 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5140): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5140): [hasSamungAccount] - No Samsung Account
,D/SSRMv2:SIOP(  729): SIOP:: AP = 330, Delta = 0
,W/linker  ( 5140): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5140): ================================================
,I/CSTORAGE( 5140):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5140): ================================================
,D/dalvikvm( 5140): No JNI_OnLoad found in /system/lib/libterrier.so 0x425bf380, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5140): [GetString-S]
,I/terrier ( 5140): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5140): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5140): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5140): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5140): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5140): QSEECom_shutdown_app, app_id = 3
,E/terrier ( 5140): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5140): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5140): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5140): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5140): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5140): [ensureRegistration] - No Samsung account
,E/SMD     (  244): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,V/AlarmManager(  729): waitForAlarm result :4
,V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,D/Finsky  ( 3666): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3666): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  244): DCD ON
,D/PreloadUpdateManagerStateMachine( 4172): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4172): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4172): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4172): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4172): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4172): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4172): entry::IDLE
,D/CaptivePortalTracker(  729): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  729): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  729): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  729): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  729): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  729): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  729): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  729): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm(  729): GC_EXPLICIT freed 3126K, 60% free 23737K/58744K, paused 32ms+24ms, total 591ms
,D/PreloadUpdateManagerStateMachine( 4172): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4172): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4172): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4172): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4172): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4172): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4172): entry::IDLE
,E/Watchdog(  729): !@Sync 4
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  729): prevTemp = 298, currTemp = 302, prevStep = 4, currStep = 5
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 310, Delta = -20
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,D/Headlines( 4085): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4085): Breath 18368 latestRequest time : 1450106387973 current time : 1450106406341
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1953): Disconnected process message: 10
,I/PowerManagerService(  729): [PWL] Off : 105s ago
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,D/AmoledAdjustTimer(  729): prevTemp = 302, currTemp = 300, prevStep = 5, currStep = 5
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = -10
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 300, currTemp = 298, prevStep = 5, currStep = 4
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  244): DCD ON
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  729): !@Sync 5
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,D/AmoledAdjustTimer(  729): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,D/Headlines( 4085): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4085): Breath 48368 latestRequest time : 1450106387973 current time : 1450106436343
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,D/AmoledAdjustTimer(  729): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  729): !@Sync 6
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  729): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,D/Headlines( 4085): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4085): Breath 78362 latestRequest time : 1450106387973 current time : 1450106466336
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1953): Disconnected process message: 10
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,D/AmoledAdjustTimer(  729): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService(  729): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  729): !@Sync 7
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,D/AmoledAdjustTimer(  729): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,D/Headlines( 4085): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4085): Breath 108358 latestRequest time : 1450106387973 current time : 1450106496331
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,D/AmoledAdjustTimer(  729): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1953): Disconnected process message: 10
,E/Watchdog(  729): !@Sync 8
,E/SMD     (  244): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,D/AmoledAdjustTimer(  729): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5251): 
,E/SMD     (  244): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,D/Headlines( 4085): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4085): Breath 138359 latestRequest time : 1450106387973 current time : 1450106526333
,D/Headlines( 4085): stop 
,D/Headlines( 4085): Breath.onDestroy : 
,I/ActivityManager(  729): Killing 4404:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,I/PowerManagerService(  729): [PWL] Off : 225s ago
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5251): DBG, CoordinatorConnector connect called
I/jxcore-log( 5251): 
,I/jxcore-log( 5251): Coordinator is now connected to the server!
I/jxcore-log( 5251): 
,I/chromium( 5251): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer(  729): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,E/SMD     (  244): DCD ON
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  729): !@Sync 9
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  729): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1953): Disconnected process message: 10
,E/SMD     (  244): DCD ON
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService(  729): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  729): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  729): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  729): initializing...
,I/TLC_TIMA_PKM_initialize(  729): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  729): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  729): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  729): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  729): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  729): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  729): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  729): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  729): App is not loaded in QSEE
,D/QSEECOMAPI: (  729): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  729): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  729): Trustlet response is completed
,E/SMD     (  244): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  729): [PWL] Off : 275s ago
,I/PowerManagerService(  729): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  729): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  729): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=729, ws=null) (elapsedTime=3192)
,E/SMD     (  244): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  729): !@Sync 10
,E/SMD     (  244): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  729): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  244): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,E/SMD     (  244): DCD ON
,E/SMD     (  244): DCD ON
,V/AlarmManager(  729): waitForAlarm result :4
,V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer(  729): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,I/SELinux ( 5754): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5754):  
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/dalvikvm(  251): GC_EXPLICIT freed 43K, 50% free 9506K/18980K, paused 24ms+37ms, total 314ms
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9506K/18980K, paused 20ms+25ms, total 211ms
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 5754): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5754):  
I/SELinux ( 5754):  
,I/SELinux ( 5754): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5754): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5754): >>>>> Normal User
,E/dalvikvm( 5754): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9506K/18980K, paused 22ms+31ms, total 206ms
,E/SELinux ( 5754): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5754): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5754): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5754): Added TimaKesytore provider
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5754, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  729): Killing 4592:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,E/Watchdog(  729): !@Sync 11
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  244): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  244): DCD ON
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
I/PowerManagerService(  729): [PWL] Off : 330s ago
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  244): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,E/Watchdog(  729): !@Sync 12
,E/SMD     (  244): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  729): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  244): DCD ON
,E/SMD     (  244): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,E/SMD     (  244): DCD ON
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1953): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 5251): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 5251): 
,I/jxcore-log( 5251): DBG, CoordinatorConnector command called
I/jxcore-log( 5251): 
,I/jxcore-log( 5251): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"34:FC:EF:9D:93
,I/jxcore-log( 5251): Start now : testSendData.js
I/jxcore-log( 5251): 
,I/jxcore-log( 5251): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 5251): 
,I/jxcore-log( 5251): check server
I/jxcore-log( 5251): 
,I/jxcore-log( 5251): serverPort is 37381
I/jxcore-log( 5251): 
,I/dalvikvm( 5251): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5251): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5251): VFY: replacing opcode 0x6e at 0x0019
,I/dalvikvm( 5251): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 5251): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5251): VFY: replacing opcode 0x6e at 0x0020
,I/jxcore-log( 5251): 2015-12-14T15:24:12.593Z SendDataTCPServer.js: TCP/IP server is bound to port: 37381
I/jxcore-log( 5251): 
,D/AndroidRuntime( 5251): Shutting down VM
,W/dalvikvm( 5251): threadid=1: thread exiting with uncaught exception (group=0x41807da0)
,E/AndroidRuntime( 5251): FATAL EXCEPTION: main
E/AndroidRuntime( 5251): Process: com.test.thalitest, PID: 5251
E/AndroidRuntime( 5251): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 5251): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 5251): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 5251): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 5251): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 5251): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 5251): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 5251): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 5251): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 5251): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 5251): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5251): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5251): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5251): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 5251): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5251): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5251): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 5251): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 5251): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 5251): Sending signal. PID: 5251 SIG: 9
,D/CrashAnrDetector(  729): processName: com.test.thalitest
,D/CrashAnrDetector(  729): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/WindowState(  729): WIN DEATH: Window{4248f360 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  250): id=16 Removed NainActivit (7/12)
,I/SurfaceFlinger(  250): id=16 Removed NainActivit (-2/12)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,I/ActivityManager(  729): Process com.test.thalitest (pid 5251) (adj 1) has died.
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 5780): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5780):  
,I/SELinux ( 5780): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5780):  
I/SELinux ( 5780):  
,I/SELinux ( 5780): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5780): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5780): >>>>> Normal User
,E/dalvikvm( 5780): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
,E/SELinux ( 5780): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5780): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5780): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5780): Added TimaKesytore provider
,D/InputDispatcher(  729): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  250): id=19 createSurf (720x1280),2 flag=404, TcreenshotS
,D/PermissionCache(  250): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (394 us)
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5780, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5780, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,V/WebViewChromium( 5780): Binding Chromium to the background looper Looper (main, tid 1) {4228f378}
,I/chromium( 5780): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5780): Initializing chromium process, renderers=0
,W/chromium( 5780): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5780): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5780): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5780): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5780): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5780): Remote Branch: 
I/Adreno-EGL( 5780): Local Patches: 
I/Adreno-EGL( 5780): Reconstruct Branch: 
,I/dalvikvm( 5780): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 5780): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5780): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5780): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5780): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5780): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5780): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 5780): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5780): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5780): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5780): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5780): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,I/dalvikvm( 5780): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5780): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 5780): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5780): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
,W/dalvikvm( 5780): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5780): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5780): CordovaWebView is running on device made by: samsung
,I/SurfaceFlinger(  250): id=20 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5780): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 5780): Enabling debug mode 0
,W/AwContents( 5780): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/WindowManager(  729): Screen frozen for +485ms due to Window{4374b3e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  250): id=21 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  250): id=22 createSurf (720x2560),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  250): id=23 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  250): id=24 createSurf (720x2560),-1 flag=20004, ClackSurfac
,D/InputDispatcher(  729): setInputDispatchMode: enabled=0, frozen=0
,I/SurfaceFlinger(  250): id=19 Removed TcreenshotS (12/17)
I/SurfaceFlinger(  250): id=21 Removed ClackSurfac (12/16)
,I/SurfaceFlinger(  250): id=19 Removed TcreenshotS (-2/16)
I/SurfaceFlinger(  250): id=22 Removed ClackSurfac (12/15)
I/SurfaceFlinger(  250): id=21 Removed ClackSurfac (-2/15)
I/SurfaceFlinger(  250): id=23 Removed ClackSurfac (12/14)
I/SurfaceFlinger(  250): id=22 Removed ClackSurfac (-2/14)
,I/SurfaceFlinger(  250): id=24 Removed ClackSurfac (12/13)
,I/SurfaceFlinger(  250): id=23 Removed ClackSurfac (-2/13)
,I/SurfaceFlinger(  250): id=24 Removed ClackSurfac (-2/13)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
V/WindowManager(  729): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/JsMessageQueue( 5780): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 5780): Trying to load lib /data/app-lib/com.test.thalitest-38/libjxcore.so 0x425b60d8
,D/dalvikvm( 5780): Added shared lib /data/app-lib/com.test.thalitest-38/libjxcore.so 0x425b60d8
,D/jxcore_app_log( 5780): JniHelper::setJavaVM(0x416f8528), pthread_self() = 2032781576
,D/JX-Cordova( 5780): jxcore cordova android initializing
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5780): GC_CONCURRENT freed 4898K, 33% free 12789K/18980K, paused 5ms+4ms, total 64ms
,D/dalvikvm( 5780): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 5780): WAIT_FOR_CONCURRENT_GC blocked 29ms
,E/SMD     (  244): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/dalvikvm( 5780): GC_FOR_ALLOC freed 4770K, 28% free 15779K/21860K, paused 35ms, total 37ms
,D/dalvikvm(  729): GC_EXPLICIT freed 2351K, 60% free 23659K/58744K, paused 5ms+13ms, total 141ms
,D/dalvikvm( 5780): GC_FOR_ALLOC freed 5159K, 32% free 16808K/24588K, paused 37ms, total 38ms
,I/dalvikvm-heap( 5780): Grow heap (frag case) to 22.071MB for 2511452-byte allocation
,D/dalvikvm( 5780): GC_FOR_ALLOC freed 3809K, 36% free 17499K/27044K, paused 32ms, total 33ms
,D/dalvikvm( 5780): GC_FOR_ALLOC freed 1274K, 36% free 17405K/27044K, paused 29ms, total 29ms
,W/jxcore-log( 5780): Initializing JXcore engine
,W/jxcore-log( 5780): JXcore engine is ready
,W/jxcore-log( 5780): Starting JXcore engine
,W/jxcore-log( 5780): Platform android
W/jxcore-log( 5780): 
,W/jxcore-log( 5780): Process ARCH arm
W/jxcore-log( 5780): 
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5780): JXcore Cordova bridge is ready!
I/jxcore-log( 5780): 
,W/jxcore-log( 5780): JXcore engine is started
,I/chromium( 5780): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5780): Toggling radios to true
I/jxcore-log( 5780): 
,D/BluetoothAdapter( 5780): enable(): BT is already enabled..!
,I/WifiManager( 5780): packageName : com.test.thalitest
,I/WifiManager( 5780): setWifiEnabled : true
,I/WifiService(  729): setWifiEnabled: true pid=5780, uid=10179
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5780, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  729): Failed getting userId using ActivityManagerNative
W/WifiService(  729): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5780, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  729): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  729): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  729): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  729): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  729): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  729): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService(  729): disconnect: pid=5780, uid=10179
I/wpa_supplicant( 1979): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 5780): Radios toggled
I/jxcore-log( 5780): 
,I/wpa_supplicant( 1979): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1979): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1979): Cmd 35605 not handled
,E/wpa_supplicant( 1979): Cmd 35605 not handled
,I/wpa_supplicant( 1979): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/wpa_supplicant( 1979): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1979): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1979): First Scan Start
,I/wpa_supplicant( 1979): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings(  729): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  729): ignore requestNetworkTransitionWakelock airplane:true
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
D/Tethering(  729): interfaceStatusChanged wlan0, false
,D/Tethering(  729): InitialState.processMessage what=4
,E/Tethering(  729): No numeric data
,D/Tethering(  729): sendTetherStateChangedBroadcast 0, 0, 0
I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
,D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
,D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
D/WifiP2pService(  729): InactiveState{ what=143375 }
D/WifiP2pService(  729): P2pEnabledState{ what=143375 }
,D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
,D/CommandListener(  241): Clearing all IP addresses on wlan0
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked(flags=0x1)
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller(  729): evaluateTrafficStatsPolling
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  729): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  729): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  729): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  729): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  729): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  729): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/ConnectivityService(  729): Attempting to switch to mobile
D/ConnectivityService(  729): Attempting to switch to BLUETOOTH_TETHER
I/wpa_supplicant( 1979): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1979): Skip scan - already scanning
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/WifiP2pService(  729): InactiveState{ what=143375 }
,D/WifiP2pService(  729): P2pEnabledState{ what=143375 }
,D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/CommandListener(  241): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  729): evaluateTrafficStatsPolling
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,E/WifiStateMachine(  729): Error! unhandled message{ when=-34ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  729): Error! unhandled message{ when=-35ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NearbySettings( 1364): DMSUtil.isNetworkConnected - flag-null, state-null
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/NetworkStats(  729): performPollLocked() took 53ms
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
V/RouteController(  241): /system/bin/ip -6 route del default table 2 2>&1
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1364): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1364): MountReceiver.mPrefHandler - 7002
E/WifiStateMachine(  729): Error! unhandled message{ when=-8ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  241): RTNETLINK answers: No such process
,V/RouteController(  241): /system/bin/ip -6 rule del table 2 2>&1
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1364): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1364): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1364): MountReceiver.mPrefHandler - 7002
,V/RouteController(  241): RTNETLINK answers: No such file or directory
,W/NetworkManagementService(  729): route cmd failed: 
W/NetworkManagementService(  729): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '63 route del src v6 2' failed with '400 63 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  729): '
W/NetworkManagementService(  729): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  729): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  729): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  729): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  729): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  729): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  729): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  729): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  729): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  729): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  729): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  729): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  729): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  241): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController(  241): RTNETLINK answers: No such process
,V/RouteController(  241): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  241): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  729): android_net_utils_resetConnections in env=0x79e36450 clazz=0xa6d00001 iface=wlan0 mask=0x3
D/ConnectivityService(  729): resetConnections(wlan0, 3)
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): updateIfacesLocked()
,V/NetworkStats(  729): performPollLocked(flags=0x1)
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked() took 19ms
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,I/ApplicationPolicy(  729): updateDataUsageMap
,D/Tethering(  729): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  729): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  729): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  729): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  729): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  729): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  729): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/NetworkMonitor( 3886): type=WIFI subType= reason=null isConnected=false
I/PCWCLIENTTRACE_PushUtil( 5140): SPPPushClient is installed : true
D/accuweather( 1462): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_PushUtil( 5140): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5140): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5140): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5140): noConnectivity : true
,I/wpa_supplicant( 1979): nl80211: Received scan results (2 BSSes)
,I/wpa_supplicant( 1979): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1979): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1979): Trying to associate with  'G700'
I/wpa_supplicant( 1979): Re-associate with C0.AA.48
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1979): Cmd 35609 not handled
,D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
,I/KLMS-2.3.201 : ( 5470): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/wpa_supplicant( 1979): Cmd 35605 not handled
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1979): Associated with C0.AA.48
I/wpa_supplicant( 1979): freq(2412) increment count 3
I/wpa_supplicant( 1979): meet head of list.
,E/wpa_supplicant( 1979): Cmd 35847 not handled
E/wpa_supplicant( 1979): Cmd 35848 not handled
E/wpa_supplicant( 1979): Cmd 35605 not handled
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
D/Tethering(  729): interfaceLinkStateChanged wlan0, true
,D/Tethering(  729): interfaceStatusChanged wlan0, true
,E/Tethering(  729): No numeric data
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  729): sendTetherStateChangedBroadcast 1, 0, 0
I/wpa_supplicant( 1979): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
I/wpa_supplicant( 1979): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  729): interfaceLinkStateChanged wlan0, true
D/WifiNative(  729): callSECApiVoid - ID [50]
D/Tethering(  729): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked(flags=0x1)
,I/KLMS-2.3.201 : ( 5470): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450106659049
,I/KLMS-2.3.201 : ( 5470): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
D/Tethering(  729): interfaceLinkStateChanged wlan0, true
,D/Tethering(  729): interfaceStatusChanged wlan0, true
D/Tethering(  729): interfaceLinkStateChanged wlan0, true
,D/Tethering(  729): interfaceStatusChanged wlan0, true
,D/Tethering(  729): interfaceLinkStateChanged wlan0, true
,D/Tethering(  729): interfaceStatusChanged wlan0, true
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/SO_AGENT( 5484): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5484): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked() took 29ms
D/WifiP2pService(  729): InactiveState{ what=143375 }
D/WifiP2pService(  729): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/SA      ( 4034): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4034): [BDLM] already registered in spp
,I/SA      ( 4034): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4034): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4034): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4034): [OR] == isSIMCardReady false ==
I/SA      ( 4034): [SCU] == networkStateCheck == false
,I/SA      ( 4034): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5496): Other Intent
,D/com.samsung.app( 1462): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1462): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4085): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4085): getCountryCode(): countryCode = PL
,D/Headlines( 4085): Breath.onCreate
,D/Headlines( 4085): Breath timer started. interval : 30000
D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4085): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4085): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4085): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager(  729): waitForAlarm result :8
,D/QuickConnect[1.1][2] ( 3342): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3342): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3342): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425c5330
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,I/iu.Environment( 1759): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1759): num queued entries: 0
,I/iu.UploadsManager( 1759): num updated entries: 0
,I/iu.SyncManager( 1759): NEXT; no task
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1364): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1364): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1364): MountReceiver.mPrefHandler - 7002
,D/Headlines( 4085): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4085): Breath 70 latestRequest time : 1450106659153 current time : 1450106659223
,I/dhcpcd  ( 5882): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5882): bssid match
,E/SMD     (  244): DCD ON
,I/jxcore-log( 5780): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): my name is : samsung-SM-G800H_PT8367
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): attempting to connect to test coordinator
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): check test folder
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): found test : ./testFindPeers.js
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): found test : ./testReConnect.js
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): found test : ./testSendData.js
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): Test app app.js loaded
I/jxcore-log( 5780): 
,I/chromium( 5780): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/AmoledAdjustTimer(  729): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/WifiP2pService(  729): InactiveState{ what=143375 }
,D/WifiP2pService(  729): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/WifiStateMachine(  729): VerifyingLinkState enter
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  729): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  729): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  729): evaluateTrafficStatsPolling
,D/WifiStateMachine(  729): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  729): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  729): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/jxcore-log( 5780): DBG, CoordinatorConnector connect called
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): Coordinator is now connected to the server!
I/jxcore-log( 5780): 
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,I/WifiTrafficPoller(  729): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  729): mBoosterFLAG : 2
,I/WifiTrafficPoller(  729): current booster mode : BTCoexMode
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  729): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/chromium( 5780): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
E/ConnectivityService(  729): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  729): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1364): MountReceiver.onReceive - Keep current state
D/ConnectivityService(  729): handleConnectivityChange: setting default proxy info 
,V/RouteController(  241): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1364): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1364): MountReceiver.onReceive - Keep current state
,I/jxcore-log( 5780): DBG, CoordinatorConnector too_late called
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): got too_late message
I/jxcore-log( 5780): 
,V/RouteController(  241): /system/bin/ip -4 rule del table 2 2>&1
,I/jxcore-log( 5780): stop tests now !
I/jxcore-log( 5780): 
I/jxcore-log( 5780): CoordinatorConnector close called
I/jxcore-log( 5780): 
D/Toast   ( 1364):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1364): showing allowed
,I/jxcore-log( 5780): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 5780): 
I/jxcore-log( 5780): The Coordinator has disconnected!
I/jxcore-log( 5780): 
I/jxcore-log( 5780): The Coordinator has closed!
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): stop tests now !
I/jxcore-log( 5780): 
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1364): MountReceiver.onReceive - Keep current state
,I/jxcore-log( 5780): turning Radios off
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): Toggling radios to false
I/jxcore-log( 5780): 
,V/RouteController(  241): RTNETLINK answers: No such file or directory
,V/RouteController(  241): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  729): stay LED for fully charged
D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
I/WifiManager( 5780): packageName : com.test.thalitest
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
V/HeadsetService( 1953): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1953): Disconnected process message: 10
,I/WifiManager( 5780): setWifiEnabled : false
,I/WifiService(  729): setWifiEnabled: false pid=5780, uid=10179
,I/SurfaceFlinger(  250): id=25 createSurf (1x1),1 flag=4, Uoast
,D/BluetoothAdapterService(1113373544)( 1953): unRegister RemoteMessageListener
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetService( 1953): registerMessageListener
D/HeadsetStateMachine( 1953): Disconnected process message: 80
V/RouteController(  241): /system/bin/ip route flush cached 2>&1
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/BluetoothAdapterState( 1953): CURRENT_STATE=ON, MSG = USER_TURN_OFF
I/BluetoothAdapterState( 1953): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1953): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 1953): updateAdapterState state is 13
D/HeadsetStateMachine( 1953): processUnRegisterMessageListener : 2
D/BluetoothAdapterService( 1953): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 1953): Autoconnection is available 
D/BluetoothAdapterService( 1953): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 1953): terminating service from this receiver
I/BluetoothPbapService( 1953): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,W/ContextImpl( 1953): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,E/bt-btif ( 1953): bta_jv_rfcomm_stop_server
,I/BluetoothAdapterState( 1953): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BluetoothAdapterState( 1953): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/RouteController(  241): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
D/GKI_LINUX( 1953): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
I/wpa_supplicant( 1979): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1979): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1979): Scan requested (ret=0) - scan timeout 30 seconds
I/jxcore-log( 5780): Radios toggled
I/jxcore-log( 5780): 
I/jxcore-log( 5780): ****TEST TOOK:  ms ****
I/jxcore-log( 5780): 
,I/jxcore-log( 5780): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 5780): 
,I/chromium( 5780): [INFO:CONSOLE(63)] "logCallback got too_late message", source: file:///android_asset/www/js/thali_main.js (63)
D/PowerManagerService(  729): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=729
E/bt-btif ( 1953): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
I/chromium( 5780): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
E/bt-btif ( 1953): bta_jv_rfcomm_stop_server
E/BtOppRfcommListener( 1953): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 1953): bta_jv_rfcomm_stop_server
E/bt-btif ( 1953): cmd socket is not created
W/Settings(  729): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  729): ignore requestNetworkTransitionWakelock airplane:true
D/btif_config_util( 1953): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/WifiP2pService(  729): InactiveState{ what=143375 }
D/WifiP2pService(  729): P2pEnabledState{ what=143375 }
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
V/RouteController(  241): RTNETLINK answers: No such process
V/RouteController(  241): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/BluetoothPbap( 1364): Proxy object disconnected
D/PbapServerProfile( 1364): Bluetooth service disconnected
D/IOP_DB_BT( 1953): db_close: nbr users 0
,D/IOP_DB_BT( 1953): db_close: free database
W/InputMethodManagerService(  729): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  729): [BT Setting State] State =13
,D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,V/RouteController(  241): /system/bin/ip route flush cached 2>&1
,I/QuickConnect[1.1][2] ( 3342): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
I/BtOppRfcommListener( 1953): stopping Accept Thread
,I/BtOppRfcommListener( 1953): BluetoothSocket listen thread finished
,D/CommandListener(  241): Clearing all IP addresses on wlan0
D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
V/NetworkStats(  729): updateIfacesLocked()
,V/NetworkStats(  729): performPollLocked(flags=0x1)
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,I/WifiTrafficPoller(  729): evaluateTrafficStatsPolling
,V/BluetoothEventManager( 1364): Received android.bluetooth.adapter.action.STATE_CHANGED
V/NetworkStats(  729): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/ConnectivityService(  729): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  729): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  729): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
E/ConnectivityService(  729): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  729): net.tcp.delack.default not found in system default properties
E/WifiStateMachine(  729): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  729): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
E/ConnectivityService(  729): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/WifiP2pService(  729): InactiveState{ what=131204 }
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/WifiP2pService(  729): P2pEnabledState{ what=131204 }
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  729): Attempting to switch to mobile
D/ConnectivityService(  729): Attempting to switch to BLUETOOTH_TETHER
,W/ContextImpl( 1364): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiP2pService(  729): sending p2p connection changed broadcast: FAILED
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked() took 35ms
W/WifiP2pStateTracker(  729): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/QuickConnect[1.1][2] ( 3342): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 3342): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  241): /system/bin/ip -4 route del default table 2 2>&1
D/WifiDisplayController(  729): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter(  729): onP2pDisconnected
D/IpRemoteDisplayController(  729): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  729): WfdBridgeServer is already null
,D/DockEventReceiver( 1364): finishStartingService: stopping service
,E/WifiStateMachine(  729): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/QuickConnect[1.1][2] ( 3342): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
,D/BluetoothNotiBroadcastReceiver( 1364): onReceive
,D/QuickConnect[1.1][2] ( 3342): P2pHelper.cancelConnectPeer -  mTargetList clear all 
,D/QuickConnect[1.1][2] ( 3342): P2pHelper.removeP2pConfirm - skip: false
D/WifiP2pService(  729): sending p2p connection changed broadcast: DISCONNECTED
D/WifiDisplayController(  729): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  729): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  729): disconnect
D/WifiDisplayController(  729): updateConnection
D/WifiDisplayController(  729): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  729): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService(  729): P2pDisablingState
,D/QuickConnect[1.1][2] ( 3342): CentralActionManager.removeHoldingIntentAll - all request done.
,V/RouteController(  241): RTNETLINK answers: No such process
,V/RouteController(  241): /system/bin/ip -4 rule del table 2 2>&1
D/QuickConnect[1.1][2] ( 3342): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,D/QuickConnect[1.1][2] ( 3342): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService(  729): P2pDisablingState{ what=147458 }
D/WifiP2pService(  729): p2p socket connection lost
D/WifiDisplayAdapter(  729): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService(  729): P2pDisabledState
D/WifiP2pService(  729): P2pDisabledState{ what=139287 }
W/WifiP2pStateTracker(  729): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiP2pService(  729): DefaultState{ what=139287 }
D/WifiDisplayController(  729): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter(  729): onP2pDisconnected
D/IpRemoteDisplayController(  729): disconnectWfdBridgeServer
D/WifiP2pService(  729): P2pDisabledState{ what=139376 }
D/IpRemoteDisplayController(  729): WfdBridgeServer is already null
D/WifiP2pService(  729): DefaultState{ what=139376 }
,E/WifiP2pService(  729): Unhandled message { what=139376 }
D/QuickConnect[1.1][2] ( 3342): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 3342): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/QuickConnect[1.1][2] ( 3342): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService(  729): P2pDisabledState{ what=139287 }
D/WifiP2pService(  729): DefaultState{ what=139287 }
,D/AuthorizationBluetoothService( 1309): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/RouteController(  241): /system/bin/ip route flush cached 2>&1
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1364): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1364): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1364): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  241): Clearing all IP addresses on wlan0
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NetUtils(  729): android_net_utils_resetConnections in env=0x79e36450 clazz=0xcd800001 iface=wlan0 mask=0x3
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/WifiNative(  729): callSECApiBoolean - ID [13]
,I/WifiTrafficPoller(  729): evaluateTrafficStatsPolling
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,I/wpa_supplicant( 1979): USE_NETWORK : USE_NETWORK OFF
D/ConnectivityService(  729): resetConnections(wlan0, 3)
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
V/NearbySettings( 1364): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1364): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1364): MountReceiver.mPrefHandler - 7002
,D/BluetoothAdapterState( 1953): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BtConfig.SecureMode( 1953): isSecureModeOn:false
W/BluetoothAdapterService( 1953): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,I/SELinux ( 5974): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5974):  
W/BluetoothAdapterService( 1953): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 1953): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 1953): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 1953): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: GONE sig=0 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1069): wifi: GONE sig=0 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=0 act=2130837946
,D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=0 act=2130837946
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
E/WifiStateMachine(  729): Error! unhandled message{ when=-54ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  729): Error! unhandled message{ when=-54ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,W/BluetoothAdapterService( 1953): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 1953): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 1953): Received stop request...Stopping profile...
,D/QuickConnect[1.1][2] ( 3342): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
,D/HeadsetProfile( 1364): Bluetooth service disconnected
,W/BluetoothAdapterService( 1953): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 1953): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 1953): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 1953): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 1953): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 1953): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 1953): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 1953): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1953): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 1953): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 1953): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 1953): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,E/WifiStateMachine(  729): Error! unhandled message{ when=-21ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
W/BluetoothAdapterService( 1953): Not skipping com.android.bluetooth.map.BluetoothMapService
,E/WifiStateMachine(  729): Error! unhandled message{ when=-21ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothAdapterState( 1953): Stopping profile services that were post enabled
I/SELinux ( 5974): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5974):  
I/SELinux ( 5974):  
,I/SELinux ( 5974): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5974): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5974): >>>>> Normal User
,E/dalvikvm( 5974): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
D/BtSettings.ProfileConfig( 1953): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 1953): Profile still running: com.android.bluetooth.hdp.HealthService
,E/SELinux ( 5974): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/BluetoothHeadsetServiceJni( 1953): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1953): Cleaning up Bluetooth Handsfree callback object
,D/A2dpService( 1953): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1953): Exit Disconnected: -1
D/Avrcp   ( 1953): Unregistering previous receiver
,D/MediaFocusControl(  729): <<< unregisterRemoteControlDisplay
,D/BluetoothA2dp(  729): Proxy object disconnected
,D/BluetoothA2dp( 3342): Proxy object disconnected
D/QuickConnect[1.1][2] ( 3342): A2dpProfile.onServiceConnected - Bluetooth service disconnected
D/BluetoothA2dp( 1364): Proxy object disconnected
,D/A2dpProfile( 1364): Bluetooth service disconnected
,D/HidService( 1953): Received stop request...Stopping profile...
,D/HidService( 1953): Stopping Bluetooth HidService
D/BluetoothInputDevice( 1364): Proxy object disconnected
,D/HidProfile( 1364): Bluetooth service disconnected
,D/BluetoothInputDevice( 3342): Proxy object disconnected
D/BluetoothA2dp( 2108): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 3342): HidProfile.onServiceDisconnected - Bluetooth service disconnected
,D/HealthService( 1953): Received stop request...Stopping profile...
,D/PanService( 1953): Received stop request...Stopping profile...
,D/TimaKeyStoreProvider( 5974): in addTimaSignatureService
D/BluetoothPan( 1364): BluetoothPAN Proxy object disconnected
D/PanProfile( 1364): Bluetooth service disconnected
,D/BluetoothPan(  729): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService( 1953): Received stop request...Stopping profile...
,D/TimaKeyStoreProvider( 5974): Cannot add TimaSignature Service, License check Failed
D/BluetoothMap( 1364): Proxy object disconnected
,D/MapProfile( 1364): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 1953): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/ActivityThread( 5974): Added TimaKesytore provider
,D/BluetoothAdapterService( 1953): Profile still running: com.android.bluetooth.hdp.HealthService
,I/GKI_LINUX( 1953): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1953): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 1953): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BtSettings.ProfileConfig( 1953): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1953): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1953): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 1953): Cleaning up Bluetooth GID callback object
D/BtSettings.ProfileConfig( 1953): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1953): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 1953): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1953): Cleaning up Bluetooth Health object
D/BtSettings.ProfileConfig( 1953): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1953): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1953): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1953): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterService( 1953): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
D/BluetoothAdapterState( 1953): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 1953): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1953): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 1953): updateAdapterState state is 10
,D/BluetoothAdapterService( 1953): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 1953): Autoconnection is available 
D/BluetoothAdapterService( 1953): updateAdapterState prevState = 13newState = 10
,I/BluetoothAdapterState( 1953): Entering OffState
D/Bluetoothsap( 1364): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1364): Unbinding service...
D/Bluetoothsap( 1364): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1364): Unbinding service...
,D/BluetoothPbap( 1364): onBluetoothStateChange: up=false
,D/BluetoothMap( 1364): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1364): onBluetoothStateChange: up=false
,D/GKI_LINUX( 1953): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/BluetoothA2dp( 2108): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 1364): onBluetoothStateChange: up=false
,D/BluetoothTethering(  729): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  729): attempted to stop reverse tether with nothing tethered
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/BluetoothA2dp(  729): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3342): onBluetoothStateChange: up=false
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/BluetoothInputDevice( 3342): onBluetoothStateChange: up=false
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): updateIfacesLocked()
V/NetworkStats(  729): performPollLocked(flags=0x1)
V/NetworkStats(  729): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/WifiTrafficPoller(  729): mBoosterFLAG : 0
,I/WifiTrafficPoller(  729): current booster mode : FullMode
W/InputMethodManagerService(  729): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  729): [BT Setting State] State =10
I/InputMethodManagerService(  729): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
,I/QuickConnect[1.1][2] ( 3342): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
,V/BluetoothEventManager( 1364): Received android.bluetooth.adapter.action.STATE_CHANGED
V/NetworkStats(  729): performPollLocked() took 18ms
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/FileShare-Server( 5974): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 5974): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
,D/NearbySettings( 1364): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1364): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1364): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1364): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1364): MountReceiver.mPrefHandler - 7002
D/Tethering(  729): interfaceLinkStateChanged p2p0, false
,D/Tethering(  729): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 1979): p2p0: CTRL-EVENT-TERMINATING 
,I/knox    ( 3280): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/Tethering(  729): interfaceLinkStateChanged wlan0, true
,D/Tethering(  729): interfaceStatusChanged wlan0, true
,I/knox    ( 3280): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3280): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3280): KNOXAgentService : onCreate()
D/knox    ( 3280): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3280): KNOXAgentService. startJobThread() start
D/knox    ( 3280): KNOXAgentService. JobThread()
D/knox    ( 3280): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3280): KNOXAgentService. startJobThread() wait
D/knox    ( 3280): KNOXAgentService : onDestroy().
,D/knox    ( 3280): ModuleBase.cancelAllAlarmManageModule()
W/ContextImpl( 1364): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 1364): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1364): onReceive
,I/wpa_supplicant( 1979): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1979): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
,D/Tethering(  729): InitialState.processMessage what=4
,E/Tethering(  729): No numeric data
,D/Tethering(  729): interfaceLinkStateChanged wlan0, false
,D/Tethering(  729): interfaceStatusChanged wlan0, false
,D/Tethering(  729): interfaceLinkStateChanged wlan0, false
D/Tethering(  729): interfaceStatusChanged wlan0, false
,D/AuthorizationBluetoothService( 1309): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ConnectivityService(  729): defaultVal : 1, tetherEnabledInSettings : true
,D/Tethering(  729): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked() took 17ms
,D/Tethering(  729): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  729): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  729): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/LocSvc_java(  729): updateNetworkState available info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  729): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  729): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1462): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3886): type=WIFI subType= reason=null isConnected=false
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/AndroidRuntime( 5964): 
D/AndroidRuntime( 5964): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/PCWCLIENTTRACE_PushUtil( 5140): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5140): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5140): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5140): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/AndroidRuntime( 5964): CheckJNI is OFF
,D/AndroidRuntime( 5964): setted country_code = Poland
,D/AndroidRuntime( 5964): setted countryiso_code = PL
D/AndroidRuntime( 5964): setted sales_code = XEO
D/AndroidRuntime( 5964): readGMSProperty: start
,D/AndroidRuntime( 5964): readGMSProperty: already setted!!
D/AndroidRuntime( 5964): readGMSProperty: end
,D/AndroidRuntime( 5964): addProductProperty: start
,D/dalvikvm( 5964): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5964): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5964): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5964): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5964): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/Tethering(  729): interfaceLinkStateChanged wlan0, false
D/Tethering(  729): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1979): wlan0: CTRL-EVENT-TERMINATING 
,I/KLMS-2.3.201 : ( 5470): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/WifiStateMachine(  729): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
I/KLMS-2.3.201 : ( 5470): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450106662597
W/Settings( 1219): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/KLMS-2.3.201 : ( 5470): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5484): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2577): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2577): [Slink platform] The state of Slink geocode service is true
I/SO_AGENT( 5484): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 2577): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2577): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 2426): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,E/memtrack( 5964): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5964): failed to load memtrack module: -2
,I/SA      ( 4034): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4034): [BDLM] already registered in spp
,I/SA      ( 4034): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4034): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4034): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4034): [OR] == isSIMCardReady false ==
,D/dalvikvm( 5964): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,I/SA      ( 4034): [SCU] == networkStateCheck == false
,I/SA      ( 4034): [OR] onReceive END
,I/ApplicationPolicy(  729): updateDataUsageMap
,D/Tethering(  729): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  729): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  729): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/LocSvc_java(  729): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  729): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  729): ignore wifi update if we are not in OPENING or CLOSING
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/accuweather( 1462): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3886): type=WIFI subType= reason=null isConnected=false
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,V/KVNProvider( 5653): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5653): getFindoCursor query string : 
,I/SCloudBackupReceiver( 5496): Other Intent
,V/KVNProvider( 5653): getTagSearchCursor() tagSearchCursor count : 0
,D/AndroidRuntime( 5964): Calling main entry com.android.commands.pm.Pm
,D/com.samsung.app( 1462): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1462): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4085): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4085): getCountryCode(): countryCode = PL
D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4085): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4085): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4085): requestUpdateNewsWelcomeCard !!! no welcome card
,D/PackageManagerService(  729): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  729): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  729): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  729): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager(  729): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  729): START PACKAGE DELETE: observer{1111279592}
D/PackageManager(  729): pkg{<packageName>}
D/PackageManager(  729): user{0}
,D/PackageManager(  729): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/QuickConnect[1.1][2] ( 3342): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/PackageManagerService(  729): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  729): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  729): getApplicationUninstallationEnabled
I/QuickConnect[1.1][2] ( 3342): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3342): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425c5330
D/ApplicationPolicy(  729): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService(  729): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  729): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  729): [MSG] DELETE_PACKAGE_AS_USER
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/PackageManager(  729): !@killApplicatoin: 10179, uninstall pkg
,I/ActivityManager(  729): Killing 5780:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
,I/SurfaceFlinger(  250): id=20 Removed NainActivit (7/13)
,I/SurfaceFlinger(  250): id=20 Removed NainActivit (-2/13)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,I/WindowState(  729): WIN DEATH: Window{4374b3e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  250): id=20 Removed NainActivit (-2/13)
,W/PackageSettings(  729): Skipping PackageSetting{426763a0 com.example.hello/10180} due to missing metadata
,D/PackageManager(  729): checkUidPermission - Execution time: 123 ms
D/PackageManager(  729): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/AdaptiveEventManager( 1069): action=android.intent.action.PACKAGE_REMOVED
,D/QuickConnect[1.1][2] ( 3342): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/FPMS_FingerprintManagerService( 1088): onReceive: android.intent.action.PACKAGE_REMOVED
,D/PackageManager(  729): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,W/Netd    (  241): No subsystem found in netlink event
D/NetlinkEvent(  241): Unexpected netlink message. type=0x11
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "sms"
,I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
D/Vpn     (  729): Interface removed : wlan0
D/Tethering(  729): interfaceRemoved wlan0
E/Tethering(  729): attempting to remove unknown iface (wlan0), ignoring
,I/InputReader(  729): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 2191): GC_EXPLICIT freed 541K, 43% free 10954K/18980K, paused 2ms+41ms, total 89ms
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "smsto"
,I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 1759): GC_EXPLICIT freed 253K, 37% free 12132K/18980K, paused 11ms+8ms, total 112ms
,D/dalvikvm( 1400): GC_EXPLICIT freed 4306K, 48% free 10028K/18980K, paused 14ms+5ms, total 108ms
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "mms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "mmsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "sms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Netd    (  241): No subsystem found in netlink event
D/NetlinkEvent(  241): Unexpected netlink message. type=0x11
,D/Vpn     (  729): Interface removed : p2p0
,D/Tethering(  729): interfaceRemoved p2p0
,E/Tethering(  729): attempting to remove unknown iface (p2p0), ignoring
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "smsto"
D/dalvikvm(  729): GC_EXPLICIT freed 3158K, 60% free 23952K/58744K, paused 9ms+15ms, total 194ms
,D/dalvikvm(  729): WAIT_FOR_CONCURRENT_GC blocked 48ms
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "mms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "mmsto"
,I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  729): PackageReceiver onReceive()
,I/HarmonyEASService(  729): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/knox    ( 3280): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/EnterpriseDeviceManagerService(  729): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  729): Admin package name: com.google.android.gms
W/ContextImpl( 3280): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3280): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3280): KNOXAgentService : onCreate()
,D/knox    ( 3280): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 3280): KNOXAgentService. startJobThread() start
D/knox    ( 3280): KNOXAgentService. JobThread()
D/knox    ( 3280): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3280): KNOXAgentService. startJobThread() wait
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/knox    ( 3280): KNOXAgentService : onDestroy().
,D/knox    ( 3280): ModuleBase.cancelAllAlarmManageModule()
I/PCWCLIENTTRACE_PushUtil( 5140): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5140): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5140): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5140): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5140): noConnectivity : true
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm(  729): GC_EXPLICIT freed 753K, 60% free 23832K/58744K, paused 6ms+23ms, total 198ms
D/PackageManager(  729): delete sourFile : 
,D/BackupManagerService(  729): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService(  729): removePackageParticipantsLocked: uid=10179 #1
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 5964): Shutting down VM
,D/dalvikvm( 5964): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 2ms
D/PackageManager(  729): delete native library directory: 
D/PackageManager(  729): return delete result to caller: 1111279592
D/PackageManager(  729): returnCode: 1
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "sms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "smsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "mms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  729):   Scheme: "mmsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/KLMS-2.3.201 : ( 5470): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector(  729): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  729): clearDefaults: com.test.thalitest
,I/KLMS-2.3.201 : ( 5470): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450106663607
,I/KLMS-2.3.201 : ( 5470): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5484): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5484): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4034): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4034): [BDLM] already registered in spp
I/SA      ( 4034): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4034): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4034): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4034): [OR] == isSIMCardReady false ==
I/SA      ( 4034): [SCU] == networkStateCheck == false
,I/SA      ( 4034): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5496): Other Intent
,D/com.samsung.app( 1462): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1462): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4085): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4085): getCountryCode(): countryCode = PL
D/Headlines( 4085): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4085): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4085): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4085): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4085): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3342): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3342): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3342): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425c5330
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,D/RCPManagerService(  729): exchangeData() failure , invalid userId
,I/SELinux ( 6006): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6006):  
,D/WifiStateMachine(  729): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,I/SELinux ( 6006): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6006):  
I/SELinux ( 6006):  
,I/SELinux ( 6006): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6006): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6006): >>>>> Normal User
,E/dalvikvm( 6006): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 6006): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6006): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6006): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6006): Added TimaKesytore provider
,D/InputReader(  729): Processing first event
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,E/SMD     (  244): DCD ON
,D/SurfaceWidgetView( 1246): destroyHardwareResources():1125911120
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1246): onRestart, Launcher: 1113974600
D/Launcher( 1246): onStart, Launcher: 1113974600
,D/Launcher.HomeView( 1246): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1462): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1462): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  250): id=26 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  250): id=27 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,W/ApplicationsProvider( 1400): Could not fetch usage stats
W/ApplicationsProvider( 1400): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1400): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1400): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1400): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1400): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1400): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1400): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1400): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1400): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1400): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1400): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
