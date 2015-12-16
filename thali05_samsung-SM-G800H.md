#### Test 50650278cd699a4_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5123): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5123):  
,--------- beginning of /dev/log/system
I/ActivityManager(  799): Killing 3961:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
I/SELinux ( 5123): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5123):  
I/SELinux ( 5123):  
I/SELinux ( 5123): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5123): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5123): >>>>> Normal User
E/dalvikvm( 5123): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5123): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  246): GC_EXPLICIT freed 45K, 50% free 9508K/18920K, paused 2ms+3ms, total 42ms
D/TimaKeyStoreProvider( 5123): in addTimaSignatureService
D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9508K/18920K, paused 1ms+3ms, total 18ms
D/TimaKeyStoreProvider( 5123): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5123): Added TimaKesytore provider
D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9508K/18920K, paused 1ms+2ms, total 18ms
W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5123, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5123): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
W/ActivityManager(  799): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5123): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
D/AndroidRuntime( 5139): 
D/AndroidRuntime( 5139): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5139): CheckJNI is OFF
D/AndroidRuntime( 5139): setted country_code = Poland
D/AndroidRuntime( 5139): setted countryiso_code = PL
D/AndroidRuntime( 5139): setted sales_code = XEO
D/AndroidRuntime( 5139): readGMSProperty: start
D/AndroidRuntime( 5139): readGMSProperty: already setted!!
D/AndroidRuntime( 5139): readGMSProperty: end
D/AndroidRuntime( 5139): addProductProperty: start
I/SA      ( 4036): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4036): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4036): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/dalvikvm( 5139): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5139): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5139): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5139): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5139): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/Mms/PackageInstallReceiver( 4303): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2195): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5161): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5161):  
D/dalvikvm( 2195): GC_CONCURRENT freed 6488K, 41% free 11200K/18920K, paused 4ms+6ms, total 73ms
D/dalvikvm( 2195): WAIT_FOR_CONCURRENT_GC blocked 31ms
I/SELinux ( 5161): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5161):  
I/SELinux ( 5161):  
I/SELinux ( 5161): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5161): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5161): >>>>> Normal User
E/dalvikvm( 5161): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/memtrack( 5139): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5139): failed to load memtrack module: -2
E/SELinux ( 5161): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5161): in addTimaSignatureService
D/TimaKeyStoreProvider( 5161): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5161): Added TimaKesytore provider
D/dalvikvm( 5139): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/ActivityManager(  799): Killing 3973:com.samsung.klmsagent/u0a18 (adj 15): empty #43
W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5161, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 5161): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/IcingCorporaProvider( 2195): UpdateCorporaTask done [took 196 ms] updated apps [took 196 ms] 
D/AndroidRuntime( 5139): Calling main entry com.android.commands.am.Am
I/SELinux ( 5176): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5176):  
I/ActivityManager(  799): Killing 4230:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5176): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5176):  
I/SELinux ( 5176):  
I/SELinux ( 5176): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5176): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5176): >>>>> Normal User
E/dalvikvm( 5176): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5176): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5176): in addTimaSignatureService
V/ApplicationPolicy(  799): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TimaKeyStoreProvider( 5176): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5176): Added TimaKesytore provider
D/CustomFrequencyManagerService(  799): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 799  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  799): mDVFSHelper.acquire()
I/SELinux ( 5189): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5189):  
D/LockPatternUtils( 1068): isPcwEnable = null
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1448): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/AndroidRuntime( 5139): Shutting down VM
D/dalvikvm( 5139): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
D/SurfaceWidgetView( 1251): destroyHardwareResources():1126031024
I/SurfaceFlinger(  245): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  245): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SELinux ( 5189): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5189):  
I/SELinux ( 5189):  
I/SELinux ( 5189): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5189): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5189): >>>>> Normal User
E/dalvikvm( 5189): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5189): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/SurfaceFlinger(  245): id=9 Removed Mauncher (7/11)
D/TimaKeyStoreProvider( 5189): in addTimaSignatureService
I/SurfaceFlinger(  245): id=9 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 5189): Cannot add TimaSignature Service, License check Failed
D/Launcher( 1251): onTrimMemory. Level: 20
D/ActivityThread( 5189): Added TimaKesytore provider
D/LockPatternUtils( 1068): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2115): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2115): getDatabaseLocked(b,b,pwd)...
W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5189, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5189, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5189): Binding Chromium to the background looper Looper (main, tid 1) {422b0198}
I/chromium( 5189): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5189): Initializing chromium process, renderers=0
W/chromium( 5189): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5189): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5189): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5189): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5189): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5189): Remote Branch: 
I/Adreno-EGL( 5189): Local Patches: 
I/Adreno-EGL( 5189): Reconstruct Branch: 
,W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5176, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,I/dalvikvm( 5189): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5189): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5189): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5189): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5189): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5189): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5189): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5189): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5189): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5189): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5189): VFY: replacing opcode 0x6f at 0x001a
E/SMD     (  239): DCD ON
W/dalvikvm( 5189): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5189): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5189): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5189): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5189): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5189): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5189): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5189): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger(  245): id=18 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5189): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 5189): Enabling debug mode 0
W/AwContents( 5189): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  799): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 799  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  799): mDVFSHelper.release()
D/CustomFrequencyManagerService(  799): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 799  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/GAV2    ( 5176): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5235): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5235):  
I/SELinux ( 5235): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5235):  
I/SELinux ( 5235):  
I/SELinux ( 5235): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5235): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5235): >>>>> Normal User
E/dalvikvm( 5235): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5235): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/JsMessageQueue( 5189): Set native->JS mode to OnlineEventsBridgeMode
D/TimaKeyStoreProvider( 5235): in addTimaSignatureService
D/TimaKeyStoreProvider( 5235): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5235): Added TimaKesytore provider
D/PackageIntentReceiver( 5235): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5235): Not GearManger package! 
I/SELinux ( 5253): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5253):  
I/ActivityManager(  799): Killing 3986:com.sec.android.soagent/u0a37 (adj 15): empty #43
D/dalvikvm( 5189): Trying to load lib /data/app-lib/com.test.thalitest-52/libjxcore.so 0x425d6f40
D/dalvikvm( 5189): Added shared lib /data/app-lib/com.test.thalitest-52/libjxcore.so 0x425d6f40
D/jxcore_app_log( 5189): JniHelper::setJavaVM(0x41726528), pthread_self() = 2032983832
D/JX-Cordova( 5189): jxcore cordova android initializing
I/SELinux ( 5253): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5253):  
I/SELinux ( 5253):  
I/SELinux ( 5253): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5253): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5253): >>>>> Normal User
E/dalvikvm( 5253): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5253): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5253): in addTimaSignatureService
D/TimaKeyStoreProvider( 5253): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5253): Added TimaKesytore provider
D/MagazineService Version( 5253): Magazine-Channel: 13
D/MagazineService Version( 5253): Magazine-Provider: 13
D/MagazineService Version( 5253): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5253): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5253): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5253, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5253): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5266): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5266):  
D/MagazineService::MagazineService( 5253): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  799): Killing 1346:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 5266): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5266):  
I/SELinux ( 5266):  
I/SELinux ( 5266): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5266): >>>>> Normal User
E/dalvikvm( 5266): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5266): in addTimaSignatureService
D/TimaKeyStoreProvider( 5266): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5266): Added TimaKesytore provider
W/GAV2    ( 5176): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  799): Killing 4337:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
,D/dalvikvm( 5189): GC_CONCURRENT freed 4909K, 33% free 12779K/18920K, paused 1ms+2ms, total 29ms
,D/dalvikvm( 5189): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/SELinux ( 5280): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5280):  
,I/ActivityManager(  799): Killing 4353:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,I/SELinux ( 5280): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5280):  
I/SELinux ( 5280):  
,I/SELinux ( 5280): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5280): >>>>> Normal User
,E/dalvikvm( 5280): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5280): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5280): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5280): Added TimaKesytore provider
,W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5280, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5280): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5292): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5292):  
I/ActivityManager(  799): Killing 4365:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5292): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5292):  
I/SELinux ( 5292):  
,I/SELinux ( 5292): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5292): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5292): >>>>> Normal User
,E/dalvikvm( 5292): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5292): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5292): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5292): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5292): Added TimaKesytore provider
,I/ActivityManager(  799): Killing 3563:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/CustomFrequencyManagerService(  799): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 799  tag : ACTIVITY_RESUME_BOOSTER@9
,D/Finsky  ( 3660): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 1759): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1759): Loading module APK com.google.android.play.games
I/dalvikvm( 1759): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1759): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0053
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/dalvikvm( 1759): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1759): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1759): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1759): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1759): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1759): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1759): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1759): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1759): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5189): GC_FOR_ALLOC freed 4683K, 28% free 15762K/21696K, paused 34ms, total 34ms
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1759): Submit a task: k
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1759): Processing package: com.test.thalitest
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
D/GassUtils( 1759): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1759): Found info for package com.test.thalitest in db.
,D/dalvikvm( 1759): GC_CONCURRENT freed 1890K, 37% free 11947K/18920K, paused 6ms+6ms, total 152ms
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/BaseAppContext( 1759): Using Auth Proxy for data requests.
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1759): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1759): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x000e
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1759): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1759): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1759): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
,W/dalvikvm( 1759): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1759): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1759): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1759): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1759): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1759): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1759): cleanUpNonGplusAccounts done.
,D/dalvikvm( 5189): GC_FOR_ALLOC freed 4843K, 31% free 16989K/24384K, paused 37ms, total 37ms
,I/dalvikvm-heap( 5189): Grow heap (frag case) to 22.153MB for 2475476-byte allocation
,W/dalvikvm( 1759): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1759): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1759): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5189): GC_FOR_ALLOC freed 3438K, 33% free 18016K/26804K, paused 34ms, total 34ms
,D/dalvikvm( 5189): GC_FOR_ALLOC freed 1000K, 33% free 18136K/26804K, paused 34ms, total 36ms
,W/jxcore-log( 5189): Initializing JXcore engine
,W/jxcore-log( 5189): JXcore engine is ready
,W/jxcore-log( 5189): Starting JXcore engine
,I/Icing   ( 1759): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 1759): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,W/jxcore-log( 5189): Platform android
W/jxcore-log( 5189): 
,W/jxcore-log( 5189): Process ARCH arm
W/jxcore-log( 5189): 
,E/SMD     (  239): DCD ON
,I/jxcore-log( 5189): JXcore Cordova bridge is ready!
I/jxcore-log( 5189): 
,W/jxcore-log( 5189): JXcore engine is started
,I/chromium( 5189): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/PowerManagerService(  799): [PWL] Off : 50s ago
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  799): stay LED for fully charged
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  799): mCoverManager.getCoverState() : true
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/SSRMv2:SIOP(  799): SIOP:: AP = 330, Delta = 20
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 5189): Toggling radios to true
I/jxcore-log( 5189): 
,D/BluetoothAdapter( 5189): enable(): BT is already enabled..!
,I/WifiManager( 5189): packageName : com.test.thalitest
,I/WifiManager( 5189): setWifiEnabled : true
,I/WifiService(  799): setWifiEnabled: true pid=5189, uid=10179
W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5189, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  799): Failed getting userId using ActivityManagerNative
W/WifiService(  799): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5189, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  799): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  799): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  799): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  799): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  799): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  799): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  799): disconnect: pid=5189, uid=10179
,I/jxcore-log( 5189): Radios toggled
I/jxcore-log( 5189): 
,I/wpa_supplicant( 1974): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5189): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5189): 
,I/jxcore-log( 5189): Perf Test app loaded loaded
I/jxcore-log( 5189): 
,I/jxcore-log( 5189): check test folder
I/jxcore-log( 5189): 
,I/jxcore-log( 5189): found test : ./testFindPeers.js
I/jxcore-log( 5189): 
,I/wpa_supplicant( 1974): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1974): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
D/Tethering(  799): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1974): Cmd 35605 not handled
,E/wpa_supplicant( 1974): Cmd 35605 not handled
,I/wpa_supplicant( 1974): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/Tethering(  799): InitialState.processMessage what=4
,E/Tethering(  799): No numeric data
I/wpa_supplicant( 1974): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1974): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1974): First Scan Start
I/wpa_supplicant( 1974): Scan requested (ret=0) - scan timeout 30 seconds
,D/Tethering(  799): sendTetherStateChangedBroadcast 0, 0, 0
I/ConnectivityService(  799): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
V/NetworkStats(  799): performPollLocked(flags=0x1)
,W/Settings(  799): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GAV2    ( 5176): Thread[GAThread,5,main]: No campaign data found.
,I/WifiStateMachine(  799): ignore requestNetworkTransitionWakelock airplane:true
,D/Tethering(  799): interfaceLinkStateChanged wlan0, false
,D/Tethering(  799): interfaceStatusChanged wlan0, false
D/WifiP2pService(  799): InactiveState{ what=143375 }
D/WifiP2pService(  799): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  236): Clearing all IP addresses on wlan0
,D/Tethering(  799): interfaceLinkStateChanged wlan0, false
,D/Tethering(  799): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,I/jxcore-log( 5189): found test : ./testSendData.js
I/jxcore-log( 5189): 
,V/NetworkStats(  799): performPollLocked() took 45ms
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
I/WifiTrafficPoller(  799): evaluateTrafficStatsPolling
I/wpa_supplicant( 1974): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1974): Skip scan - already scanning
D/ConnectivityService(  799): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  799): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  799): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  799): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  799): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  799): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/WifiP2pService(  799): InactiveState{ what=143375 }
D/WifiP2pService(  799): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  799): Attempting to switch to mobile
D/ConnectivityService(  799): Attempting to switch to BLUETOOTH_TETHER
,V/RouteController(  236): /system/bin/ip -6 route del default table 2 2>&1
,I/SELinux ( 5353): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5353):  
D/STATUSBAR-IconMerger( 1068): checkOverflow(336), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  236): RTNETLINK answers: No such process
,V/RouteController(  236): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController(  236): RTNETLINK answers: No such file or directory
,D/CommandListener(  236): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  799): evaluateTrafficStatsPolling
,E/WifiStateMachine(  799): Error! unhandled message{ when=-57ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  799): Error! unhandled message{ when=-51ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,W/NetworkManagementService(  799): route cmd failed: 
W/NetworkManagementService(  799): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  799): '
W/NetworkManagementService(  799): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  799): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  799): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  799): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  799): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  799): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  799): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  799): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  799): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  799): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  799): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  799): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  799): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  236): /system/bin/ip -4 route del default table 2 2>&1
I/SELinux ( 5353): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5353):  
I/SELinux ( 5353):  
,I/SELinux ( 5353): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5353): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5353): >>>>> Normal User
,E/dalvikvm( 5353): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
E/WifiStateMachine(  799): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/SELinux ( 5353): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController(  236): RTNETLINK answers: No such process
,V/RouteController(  236): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  236): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 5353): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5353): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5353): Added TimaKesytore provider
,D/NetUtils(  799): android_net_utils_resetConnections in env=0x77df6940 clazz=0x69f00001 iface=wlan0 mask=0x3
D/ConnectivityService(  799): resetConnections(wlan0, 3)
,V/NativeCrypto( 1308): Read error: ssl=0x7c2e3a10: I/O error during system call, Connection timed out
,V/NativeCrypto( 1308): SSL shutdown failed: ssl=0x7c2e3a10: I/O error during system call, Broken pipe
,I/Choreographer( 5189): Skipped 117 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5189): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/NetworkStats(  799): updateIfacesLocked()
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
V/NetworkStats(  799): performPollLocked(flags=0x1)
D/ConnectivityService(  799): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
V/NetworkStats(  799): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
V/NetworkStats(  799): performPollLocked() took 19ms
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,I/System.out( 5353): Inside WakeupProvider
,I/System.out( 5353): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 5353): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5353): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5353): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/dalvikvm(  799): GC_EXPLICIT freed 2558K, 58% free 23818K/55796K, paused 6ms+14ms, total 139ms
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5353): initQueue()
D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  799): Killing 4393:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,E/SMD     (  239): DCD ON
,D/Tethering(  799): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy(  799): updateDataUsageMap
,D/Tethering(  799): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  799): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/ConnectivityService(  799): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1448): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3879): type=WIFI subType= reason=null isConnected=false
I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): noConnectivity : true
,D/LocSvc_java(  799): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  799): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  799): ignore wifi update if we are not in OPENING or CLOSING
,I/SELinux ( 5386): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5386):  
,I/SELinux ( 5386): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5386):  
I/SELinux ( 5386):  
,I/SELinux ( 5386): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5386): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5386): >>>>> Normal User
,E/dalvikvm( 5386): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5386): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5386): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5386): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5386): Added TimaKesytore provider
,W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5386, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  799): Killing 4408:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,E/wpa_supplicant( 1974): Cmd 35609 not handled
I/wpa_supplicant( 1974): nl80211: Received scan results (7 BSSes)
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
D/Tethering(  799): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1974): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1974): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1974): Trying to associate with  'G700'
I/wpa_supplicant( 1974): Re-associate with C0.AA.48
,I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/SELinux ( 5400): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5400):  
,D/dalvikvm(  246): GC_EXPLICIT freed 43K, 50% free 9508K/18920K, paused 2ms+2ms, total 27ms
,I/SELinux ( 5400): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5400):  
I/SELinux ( 5400):  
,I/SELinux ( 5400): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9508K/18920K, paused 1ms+3ms, total 18ms
E/SELinux ( 5400): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5400): >>>>> Normal User
,E/dalvikvm( 5400): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5400): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5400): in addTimaSignatureService
,D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9508K/18920K, paused 2ms+3ms, total 19ms
,D/TimaKeyStoreProvider( 5400): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5400): Added TimaKesytore provider
,E/wpa_supplicant( 1974): Cmd 35605 not handled
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1974): Associated with C0.AA.48
I/wpa_supplicant( 1974): freq(2412) increment count 2
I/wpa_supplicant( 1974): meet head of list.
E/wpa_supplicant( 1974): Cmd 35847 not handled
E/wpa_supplicant( 1974): Cmd 35848 not handled
E/wpa_supplicant( 1974): Cmd 35605 not handled
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
D/Tethering(  799): interfaceStatusChanged wlan0, false
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
,D/Tethering(  799): interfaceStatusChanged wlan0, false
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
,D/Tethering(  799): interfaceStatusChanged wlan0, false
,D/Tethering(  799): interfaceLinkStateChanged wlan0, true
,D/Tethering(  799): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1974): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1974): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering(  799): interfaceLinkStateChanged wlan0, true
D/Tethering(  799): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/Tethering(  799): No numeric data
D/Tethering(  799): interfaceLinkStateChanged wlan0, true
,D/Tethering(  799): interfaceStatusChanged wlan0, true
D/Tethering(  799): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  799): interfaceLinkStateChanged wlan0, true
,D/Tethering(  799): interfaceStatusChanged wlan0, true
,I/ConnectivityService(  799): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  799): interfaceLinkStateChanged wlan0, true
D/Tethering(  799): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/WifiNative(  799): callSECApiVoid - ID [50]
V/NetworkStats(  799): performPollLocked(flags=0x1)
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5400, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
V/NetworkStats(  799): performPollLocked() took 32ms
D/WifiP2pService(  799): InactiveState{ what=143375 }
D/WifiP2pService(  799): P2pEnabledState{ what=143375 }
,I/ActivityManager(  799): Killing 4433:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5417): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5417):  
,I/SELinux ( 5417): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5417):  
I/SELinux ( 5417):  
,I/SELinux ( 5417): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5417): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5417): >>>>> Normal User
,E/dalvikvm( 5417): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5417): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5417): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5417): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5417): Added TimaKesytore provider
,W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5417, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5417): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5417): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450240711298
,I/KLMS-2.3.201 : ( 5417): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager(  799): Killing 4449:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5436): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5436):  
,I/dhcpcd  ( 5430): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5430): bssid match
,I/SELinux ( 5436): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5436):  
I/SELinux ( 5436):  
,I/SELinux ( 5436): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5436): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5436): >>>>> Normal User
,E/dalvikvm( 5436): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5436): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5436): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5436): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5436): Added TimaKesytore provider
,D/SO_AGENT( 5436): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5436): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5436, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/SA      ( 4036): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4036): [BDLM] already registered in spp
I/SA      ( 4036): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4036): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4036): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4036): [OR] == isSIMCardReady false ==
I/SA      ( 4036): [SCU] == networkStateCheck == false
,I/SA      ( 4036): [OR] onReceive END
I/ActivityManager(  799): Killing 4588:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SELinux ( 5449): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5449):  
,I/SELinux ( 5449): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5449):  
I/SELinux ( 5449):  
,I/SELinux ( 5449): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5449): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5449): >>>>> Normal User
,E/dalvikvm( 5449): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5449): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5449): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5449): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5449): Added TimaKesytore provider
,I/sCloudBackupApp( 5449): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5449): Other Intent
,I/ActivityManager(  799): Killing 4631:com.sec.android.app.voicenote/1000 (adj 15): empty #43
D/com.samsung.app( 1448): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1448): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5484): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5484):  
,I/SELinux ( 5484): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5484):  
I/SELinux ( 5484):  
,I/SELinux ( 5484): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5484): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5484): >>>>> Normal User
,E/dalvikvm( 5484): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5484): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5484): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5484): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5484): Added TimaKesytore provider
,W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5484, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  799): Killing 4675:com.google.android.talk/u0a105 (adj 15): empty #43
,D/WifiP2pService(  799): InactiveState{ what=143375 }
,D/WifiP2pService(  799): P2pEnabledState{ what=143375 }
D/Headlines( 4087): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 4087): getCountryCode(): countryCode = PL
D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4087): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4087): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 4087): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5504): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5504):  
,D/WifiStateMachine(  799): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  799): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  799): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  799): evaluateTrafficStatsPolling
,D/WifiStateMachine(  799): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/SELinux ( 5504): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5504):  
I/SELinux ( 5504):  
,I/SELinux ( 5504): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/ConnectivityService(  799): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  799): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,E/SELinux ( 5504): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5504): >>>>> Normal User
,E/dalvikvm( 5504): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5504): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  799): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  799): mBoosterFLAG : 2
,I/WifiTrafficPoller(  799): current booster mode : BTCoexMode
D/ConnectivityService(  799): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService(  799): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  799): net.tcp.delack.wifi not found in system properties. Using defaults
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  799): handleConnectivityChange: setting default proxy info 
,V/RouteController(  236): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/RouteController(  236): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 5504): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5504): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5504): Added TimaKesytore provider
,V/RouteController(  236): RTNETLINK answers: No such file or directory
,V/RouteController(  236): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,V/RouteController(  236): /system/bin/ip route flush cached 2>&1
,V/RouteController(  236): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  236): RTNETLINK answers: No such process
,V/RouteController(  236): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  236): /system/bin/ip route flush cached 2>&1
,V/NetworkStats(  799): updateIfacesLocked()
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,V/NetworkStats(  799): performPollLocked(flags=0x1)
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
V/NetworkStats(  799): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,V/NetworkStats(  799): performPollLocked() took 19ms
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5504): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5504): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5504): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/GAV2    ( 5504): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5504): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 5504): Binding Chromium to the main looper Looper (main, tid 1) {422b1f58}
,I/chromium( 5504): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5504): Initializing chromium process, renderers=0
,W/chromium( 5504): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5504): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5504): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5504): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5504): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5504): Remote Branch: 
I/Adreno-EGL( 5504): Local Patches: 
I/Adreno-EGL( 5504): Reconstruct Branch: 
,I/NSApplication( 5504): Starting up...
,W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5504, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3338): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3338): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3338): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425e4330
I/ActivityManager(  799): Killing 3018:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,I/SELinux ( 5553): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5553):  
,I/SELinux ( 5553): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5553):  
I/SELinux ( 5553):  
,I/SELinux ( 5553): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5553): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5553): >>>>> Normal User
,E/dalvikvm( 5553): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5553): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5553): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5553): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5553): Added TimaKesytore provider
,D/RCPManagerService(  799): exchangeData() failure , invalid userId
,D/RCPManagerService(  799): exchangeData() failure , invalid userId
,D/RCPManagerService(  799): exchangeData() failure , invalid userId
,D/AmoledAdjustTimer(  799): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,D/RCPManagerService(  799): exchangeData() failure , invalid userId
,D/Tethering(  799): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  799): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  799): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/LocSvc_java(  799): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  799): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  799): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1448): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/RCPManagerService(  799): exchangeData() failure , invalid userId
D/RCPManagerService(  799): exchangeData() failure , invalid userId
,I/NetworkMonitor( 3879): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  799): Killing 4760:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 5574): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5574):  
,I/SELinux ( 5578): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5578):  
W/ActivityManager(  799): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5574): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5574):  
I/SELinux ( 5574):  
,I/SELinux ( 5574): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5574): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5574): >>>>> Normal User
,E/dalvikvm( 5574): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5574): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 5578): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5578):  
I/SELinux ( 5578):  
,I/SELinux ( 5578): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5578): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5578): >>>>> Normal User
,E/dalvikvm( 5578): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
D/TimaKeyStoreProvider( 5574): in addTimaSignatureService
,E/SELinux ( 5578): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5574): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5574): Added TimaKesytore provider
,I/ActivityManager(  799): Killing 4780:com.wssyncmldm/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5578): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5578): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5578): Added TimaKesytore provider
,D/BadgeProvider( 5574): onCreate
,D/BadgeProvider( 5574): DatabaseHelper
W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5574, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5574): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5578, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5574): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5574): sendNotify, [notify] : null
D/BadgeProvider( 5574): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5574): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5574): update, [UpdateCount] : 1
,D/Launcher.Model( 1251): reloadBadges entered.
,D/hcjo    ( 4170): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4170): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4170): exit::IDLE
,D/InitializeManagerStateMachine( 4170): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4170): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4170): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4170): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4170): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4170): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4170): entry::SUCCESS
,D/hcjo    ( 4170): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4170): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4170): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4170): exit::SUCCESS
,D/InitializeManagerStateMachine( 4170): entry::IDLE
I/ActivityManager(  799): Killing 4617:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1318):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1318): showing allowed
,I/SurfaceFlinger(  245): id=19 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  799): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=799
D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/KLMS-2.3.201 : ( 5417): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5417): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450240713097
,I/KLMS-2.3.201 : ( 5417): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5436): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2563): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2563): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2563): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2563): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5436): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2439): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5602): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5602):  
,I/SELinux ( 5606): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5606):  
,I/SELinux ( 5602): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5602):  
I/SELinux ( 5602):  
I/SELinux ( 5602): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5602): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5602): >>>>> Normal User
E/dalvikvm( 5602): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5602): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5602): in addTimaSignatureService
I/SELinux ( 5606): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5606):  
I/SELinux ( 5606):  
,I/SELinux ( 5606): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5606): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5606): >>>>> Normal User
,E/dalvikvm( 5606): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,D/TimaKeyStoreProvider( 5602): Cannot add TimaSignature Service, License check Failed
,E/SELinux ( 5606): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/ActivityThread( 5602): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5606): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5606): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5606): Added TimaKesytore provider
,I/SA      ( 4036): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4036): [BDLM] already registered in spp
I/SA      ( 4036): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4036): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4036): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4036): [OR] == isSIMCardReady false ==
,I/SA      ( 4036): [SCU] == networkStateCheck == true
I/SA      ( 4036): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4036): isChinaCountryCode : false
,I/SA      ( 4036): [OR] == networkStateCheck true ==
I/SA      ( 4036): [OR] GetMyCountryZoneTask
,I/SA      ( 4036): [OR] onReceive END
,I/SA      ( 4036): [SRS] prepareGetMyCountryZone
I/SA      ( 4036): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4036): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5449): Other Intent
,D/com.samsung.app( 1448): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1448): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      ( 4036): [TPMU] GetMccFromDB : null
I/SA      ( 4036): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4036): [TPM] isNoProxy(default) : true
,I/SA      ( 4036): [RC New] Execute method=[GET] start
,V/KVNProvider( 5606): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5606): getFindoCursor query string : 
,D/Headlines( 4087): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4087): getCountryCode(): countryCode = PL
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4087): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 4087): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4087): requestUpdateNewsWelcomeCard !!! no welcome card
,V/KVNProvider( 5606): getTagSearchCursor() tagSearchCursor count : 0
,D/QuickConnect[1.1][2] ( 3338): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3338): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3338): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425e4330
I/ActivityManager(  799): Killing 4188:com.android.calendar/u0a142 (adj 15): empty #43
,D/RCPManagerService(  799): exchangeData() failure , invalid userId
,D/RCPManagerService(  799): exchangeData() failure , invalid userId
,D/hcjo    ( 4170): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4170): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4170): exit::IDLE
,D/InitializeManagerStateMachine( 4170): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4170): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4170): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4170): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4170): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4170): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4170): entry::SUCCESS
,D/hcjo    ( 4170): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4170): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4170): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4170): exit::SUCCESS
,D/InitializeManagerStateMachine( 4170): entry::IDLE
,E/SMD     (  239): DCD ON
,I/SA      ( 4036): [RC New] [v2liruge] api execute + 654
,I/SA      ( 4036): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4036): AsyncTask #2 calls detatch()
,I/SA      ( 4036): [TPMU] getNetworkMcc : 
,I/SA      ( 4036): [SCU] saveMccToPreferece Start
,I/SA      ( 4036): [SCU] RegionMCC : 260
,I/SA      ( 4036): [SSP] query invoked
,I/SA      ( 4036): [TPMU] GetMccFromDB : null
I/SA      ( 4036): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4036): [SCU] saveMccToPreferece End
,I/SA      ( 4036): [RC New] executeRequest [v2liruge] end. 674
I/SA      ( 4036): [RC New] Execute end
I/SA      ( 4036): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4036): [OR] GetMyCountryZoneTask Success
,W/WifiP2pStateTracker(  799): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  799): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  799):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  799): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  799): updateSourceRoutes : no source routing conditions
,I/jxcore-log( 5189): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5189): 
,V/AlarmManager(  799): waitForAlarm result :4
,V/AlarmManager(  799): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 1897 latestRequest time : 1450240713332 current time : 1450240715229
,E/WifiStateMachine(  799): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/VacuumService( 1211): Vacuum at: now=1450240715409 tag=VacuumService
,D/FactoryTest( 4726): Not factory mode
,D/FactoryTest( 4726): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4726): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4726): still no open session command from host, so toast
W/ContextImpl( 4726): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4726): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
V/ApplicationPolicy(  799): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  799): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 799  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  799): mDVFSHelper.acquire()
,I/SQLiteSecureOpenHelper( 2115): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2115): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/LockPatternUtils( 1068): isPcwEnable = null
,E/MTPRx   ( 4726): started activity for popup
,E/SettingsReceiverActivity( 4726): PREF_DONT_ASK_AGAIN : false
,D/SettingsReceiverActivity( 4726): dev.kiessupport is : TRUE
D/dalvikvm(  799): GC_EXPLICIT freed 2715K, 58% free 23751K/55796K, paused 6ms+14ms, total 134ms
D/dalvikvm( 1308): GC_EXPLICIT freed 1750K, 43% free 10791K/18920K, paused 5ms+5ms, total 50ms
I/PhenotypeConfigurator( 1211): Scheduling Phenotype for one-off execution 14072 seconds from now (1450240715860)
I/SurfaceFlinger(  245): id=20 createSurf (1x1),1 flag=4, TettingsRec
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/Adreno-EGL( 4726): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4726): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4726): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4726): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4726): Remote Branch: 
I/Adreno-EGL( 4726): Local Patches: 
I/Adreno-EGL( 4726): Reconstruct Branch: 
D/GetConfigurationSnapshotOperation( 1211): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/HWUI    ( 4726): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 4726): Enabling debug mode 0
I/PhenotypeFlagCommitter( 1211): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
W/dalvikvm( 1211): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1211): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1211): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1211): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1211): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1211): VFY: replacing opcode 0x6e at 0x00bb
I/GoogleURLConnFactory( 1211): Using platform SSLCertificateSocketFactory
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/HarmonyEASService(  799): Updating for all 1
D/CustomFrequencyManagerService(  799): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 799  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/CustomFrequencyManagerService(  799): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 799  tag : ACTIVITY_RESUME_BOOSTER@5
D/CustomFrequencyManagerService(  799): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
D/LocationManagerService(  799): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  799): mDVFSHelper.release()
I/dalvikvm( 1211): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1211): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1211): VFY: replacing opcode 0x6e at 0x003d
I/System.out( 1211): Thread-107(HTTPLog):isShipBuild true
I/System.out( 1211): Thread-107(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1211): GC_CONCURRENT freed 1629K, 38% free 11869K/18920K, paused 5ms+5ms, total 54ms
,D/dalvikvm( 1211): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/ActivityManager(  799): Killing 4601:com.android.providers.calendar/u0a44 (adj 15): empty #43
I/SurfaceFlinger(  245): id=19 Removed Uoast (12/13)
I/SurfaceFlinger(  245): id=19 Removed Uoast (-2/13)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  799): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=799 (0x0)
D/PowerManagerService(  799): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=799, ws=WorkSource{1000}) (elapsedTime=3473)
,D/LocationManagerService(  799): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  239): DCD ON
,D/LocationManagerService(  799): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/CustomFrequencyManagerService(  799): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 799  tag : ACTIVITY_RESUME_BOOSTER@9
,I/GAV2    ( 5504): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5070): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5070): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5070): ================================================
,I/CSTORAGE( 5070):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5070): ================================================
,D/dalvikvm( 5070): No JNI_OnLoad found in /system/lib/libterrier.so 0x425de2f0, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5070): [GetString-S]
,I/terrier ( 5070): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5070): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5070): App is not loaded in QSEE
,D/SSRMv2:SIOP(  799): SIOP:: AP = 330, Delta = 0
,D/QSEECOMAPI: ( 5070): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5070): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5070): QSEECom_shutdown_app, app_id = 3
,E/terrier ( 5070): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5070): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5070): [ensureRegistration] - No Samsung account
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :4
,V/AlarmManager(  799): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3660): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3660): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 296, currTemp = 299, prevStep = 4, currStep = 4
,D/CaptivePortalTracker(  799): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  799): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  799): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  799): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  799): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  799): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  799): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  799): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4170): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4170): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4170): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4170): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4170): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4170): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4170): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 4170): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4170): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4170): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4170): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4170): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4170): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4170): entry::IDLE
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 310, Delta = -20
,E/Watchdog(  799): !@Sync 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 299, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService(  799): [PWL] Off : 75s ago
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 24288 latestRequest time : 1450240713332 current time : 1450240737620
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = -10
,V/AlarmManager(  799): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  799): prevTemp = 297, currTemp = 295, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 5
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1963): Disconnected process message: 10
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService(  799): [PWL] Off : 105s ago
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 54277 latestRequest time : 1450240713332 current time : 1450240767610
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  799): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 6
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 84268 latestRequest time : 1450240713332 current time : 1450240797601
,I/PowerManagerService(  799): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  799): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 7
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  799): waitForAlarm result :8
,E/SMD     (  239): DCD ON
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 114273 latestRequest time : 1450240713332 current time : 1450240827606
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  799): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  799): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 8
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,E/SMD     (  239): DCD ON
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 144280 latestRequest time : 1450240713332 current time : 1450240857613
,D/Headlines( 4087): stop 
,D/Headlines( 4087): Breath.onDestroy : 
,I/ActivityManager(  799): Killing 4380:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  799): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 9
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  799): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService(  799): [PWL] Off : 225s ago
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/AmoledAdjustTimer(  799): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 5189): Connected to the server!
I/jxcore-log( 5189): 
,I/chromium( 5189): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  239): DCD ON
,I/jxcore-log( 5189): --- start :testFindPeers.js---
I/jxcore-log( 5189): 
,I/jxcore-log( 5189): testFindPeers created [object Object]
I/jxcore-log( 5189): 
,I/jxcore-log( 5189): serverPort is 8876
I/jxcore-log( 5189): 
,I/dalvikvm( 5189): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5189): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5189): VFY: replacing opcode 0x6e at 0x0019
I/dalvikvm( 5189): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5189): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5189): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 5189): Shutting down VM
,W/dalvikvm( 5189): threadid=1: thread exiting with uncaught exception (group=0x41835da0)
,E/AndroidRuntime( 5189): FATAL EXCEPTION: main
E/AndroidRuntime( 5189): Process: com.test.thalitest, PID: 5189
E/AndroidRuntime( 5189): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 5189): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 5189): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 5189): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 5189): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 5189): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 5189): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 5189): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 5189): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 5189): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 5189): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5189): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5189): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5189): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 5189): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5189): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5189): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 5189): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 5189): 	at dalvik.system.NativeStart.main(Native Method)
,D/CrashAnrDetector(  799): processName: com.test.thalitest
,D/CrashAnrDetector(  799): broadcastEvent : com.test.thalitest data_app_crash
,I/Process ( 5189): Sending signal. PID: 5189 SIG: 9
W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/ActivityManager(  799): Process com.test.thalitest (pid 5189) (adj 1) has died.
,I/WindowState(  799): WIN DEATH: Window{44692428 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  245): id=18 Removed NainActivit (7/12)
,I/SurfaceFlinger(  245): id=18 Removed NainActivit (-2/12)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 5740): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5740):  
,D/dalvikvm(  246): GC_EXPLICIT freed 43K, 50% free 9508K/18920K, paused 22ms+20ms, total 208ms
,D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9508K/18920K, paused 3ms+4ms, total 71ms
,I/SELinux ( 5740): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5740):  
I/SELinux ( 5740):  
,I/SELinux ( 5740): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5740): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5740): >>>>> Normal User
,E/dalvikvm( 5740): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
,D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9508K/18920K, paused 3ms+5ms, total 30ms
,E/SELinux ( 5740): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5740): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5740): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5740): Added TimaKesytore provider
,D/InputDispatcher(  799): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  245): id=21 createSurf (720x1280),2 flag=404, TcreenshotS
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (366 us)
,W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5740, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5740, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,V/WebViewChromium( 5740): Binding Chromium to the background looper Looper (main, tid 1) {422b7fd0}
,I/chromium( 5740): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5740): Initializing chromium process, renderers=0
,W/chromium( 5740): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5740): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5740): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5740): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5740): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5740): Remote Branch: 
I/Adreno-EGL( 5740): Local Patches: 
I/Adreno-EGL( 5740): Reconstruct Branch: 
,I/dalvikvm( 5740): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5740): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5740): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5740): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5740): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5740): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5740): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5740): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5740): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5740): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5740): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5740): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5740): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5740): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 5740): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5740): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5740): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5740): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5740): CordovaWebView is running on device made by: samsung
,I/SurfaceFlinger(  245): id=22 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5740): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 5740): Enabling debug mode 0
,W/AwContents( 5740): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/WindowManager(  799): Screen frozen for +490ms due to Window{436689b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  245): id=23 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  245): id=24 createSurf (720x2560),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  245): id=25 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  245): id=26 createSurf (720x2560),-1 flag=20004, ClackSurfac
,D/InputDispatcher(  799): setInputDispatchMode: enabled=0, frozen=0
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/SurfaceFlinger(  245): id=21 Removed TcreenshotS (12/17)
,I/SurfaceFlinger(  245): id=23 Removed ClackSurfac (12/16)
I/SurfaceFlinger(  245): id=21 Removed TcreenshotS (-2/16)
,I/SurfaceFlinger(  245): id=24 Removed ClackSurfac (12/15)
,I/SurfaceFlinger(  245): id=25 Removed ClackSurfac (12/14)
,I/SurfaceFlinger(  245): id=25 Removed ClackSurfac (-2/14)
I/SurfaceFlinger(  245): id=26 Removed ClackSurfac (12/13)
,I/SurfaceFlinger(  245): id=26 Removed ClackSurfac (-2/13)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
V/WindowManager(  799): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/JsMessageQueue( 5740): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 5740): Trying to load lib /data/app-lib/com.test.thalitest-52/libjxcore.so 0x425deda0
,D/dalvikvm( 5740): Added shared lib /data/app-lib/com.test.thalitest-52/libjxcore.so 0x425deda0
,D/jxcore_app_log( 5740): JniHelper::setJavaVM(0x41726528), pthread_self() = 2032987440
,D/JX-Cordova( 5740): jxcore cordova android initializing
,E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  799): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 5740): GC_CONCURRENT freed 4928K, 33% free 12760K/18920K, paused 4ms+6ms, total 63ms
,D/dalvikvm( 5740): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 5740): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/dalvikvm(  799): GC_EXPLICIT freed 2472K, 58% free 23744K/55796K, paused 10ms+18ms, total 233ms
,D/dalvikvm( 5740): GC_FOR_ALLOC freed 4744K, 28% free 15763K/21756K, paused 54ms, total 55ms
,D/TimaService(  799): TIMA: TimaService scheduler is intialized. 
D/TimaService(  799): TimaServiceHandler.handleMessage what =1
,D/TimaService(  799): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  799): initializing...
I/TLC_TIMA_PKM_initialize(  799): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  799): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  799): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  799): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  799): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  799): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  799): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  799): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  799): App is not loaded in QSEE
,D/QSEECOMAPI: (  799): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  799): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  799): Trustlet response is completed
,D/dalvikvm( 5740): GC_FOR_ALLOC freed 5103K, 32% free 16776K/24444K, paused 58ms, total 60ms
,I/dalvikvm-heap( 5740): Grow heap (frag case) to 21.944MB for 2475476-byte allocation
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5740): GC_FOR_ALLOC freed 3781K, 36% free 17460K/26864K, paused 55ms, total 58ms
,D/dalvikvm( 5740): GC_FOR_ALLOC freed 1253K, 36% free 17366K/26864K, paused 41ms, total 41ms
,I/dalvikvm-heap( 5740): Grow heap (frag case) to 23.701MB for 3713210-byte allocation
,D/dalvikvm( 5740): GC_FOR_ALLOC freed 3282K, 40% free 18533K/30492K, paused 38ms, total 39ms
,W/jxcore-log( 5740): Initializing JXcore engine
,W/jxcore-log( 5740): JXcore engine is ready
,W/jxcore-log( 5740): Starting JXcore engine
,W/jxcore-log( 5740): Platform android
W/jxcore-log( 5740): 
,W/jxcore-log( 5740): Process ARCH arm
W/jxcore-log( 5740): 
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/jxcore-log( 5740): JXcore Cordova bridge is ready!
I/jxcore-log( 5740): 
,W/jxcore-log( 5740): JXcore engine is started
,I/chromium( 5740): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 5740): Toggling radios to true
I/jxcore-log( 5740): 
,D/BluetoothAdapter( 5740): enable(): BT is already enabled..!
,I/WifiManager( 5740): packageName : com.test.thalitest
I/WifiManager( 5740): setWifiEnabled : true
I/WifiService(  799): setWifiEnabled: true pid=5740, uid=10179
,W/WifiService(  799): Failed getting userId using ActivityManagerNative
W/WifiService(  799): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5740, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  799): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  799): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  799): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  799): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  799): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  799): 	at dalvik.system.NativeStart.run(Native Method)
,W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5740, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/WifiService(  799): disconnect: pid=5740, uid=10179
I/wpa_supplicant( 1974): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 5740): Radios toggled
I/jxcore-log( 5740): 
I/jxcore-log( 5740): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5740): 
I/jxcore-log( 5740): Perf Test app loaded loaded
I/jxcore-log( 5740): 
I/jxcore-log( 5740): check test folder
I/jxcore-log( 5740): 
I/jxcore-log( 5740): found test : ./testFindPeers.js
I/jxcore-log( 5740): 
,I/wpa_supplicant( 1974): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1974): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,E/wpa_supplicant( 1974): Cmd 35605 not handled
E/wpa_supplicant( 1974): Cmd 35605 not handled
,I/wpa_supplicant( 1974): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 1974): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1974): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1974): First Scan Start
,I/wpa_supplicant( 1974): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings(  799): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Tethering(  799): interfaceLinkStateChanged wlan0, false
I/WifiStateMachine(  799): ignore requestNetworkTransitionWakelock airplane:true
,D/Tethering(  799): interfaceStatusChanged wlan0, false
,D/Tethering(  799): InitialState.processMessage what=4
,E/Tethering(  799): No numeric data
,D/Tethering(  799): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiP2pService(  799): InactiveState{ what=143375 }
D/WifiP2pService(  799): P2pEnabledState{ what=143375 }
I/ConnectivityService(  799): defaultVal : 1, tetherEnabledInSettings : true
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,I/jxcore-log( 5740): found test : ./testSendData.js
I/jxcore-log( 5740): 
,D/CommandListener(  236): Clearing all IP addresses on wlan0
,V/NetworkStats(  799): performPollLocked(flags=0x1)
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
D/Tethering(  799): interfaceStatusChanged wlan0, false
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
D/Tethering(  799): interfaceStatusChanged wlan0, false
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
D/Tethering(  799): interfaceStatusChanged wlan0, false
,I/WifiTrafficPoller(  799): evaluateTrafficStatsPolling
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
D/ConnectivityService(  799): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  799): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
E/ConnectivityService(  799): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  799): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  799): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  799): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/ConnectivityService(  799): Attempting to switch to mobile
D/ConnectivityService(  799): Attempting to switch to BLUETOOTH_TETHER
V/NetworkStats(  799): performPollLocked() took 36ms
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
I/wpa_supplicant( 1974): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1974): Skip scan - already scanning
D/STATUSBAR-IconMerger( 1068): checkOverflow(336), More:false, Req:false Child:2
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService(  799): InactiveState{ what=143375 }
,D/WifiP2pService(  799): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
V/RouteController(  236): /system/bin/ip -6 route del default table 2 2>&1
,V/RouteController(  236): RTNETLINK answers: No such process
,V/RouteController(  236): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController(  236): RTNETLINK answers: No such file or directory
,D/CommandListener(  236): Clearing all IP addresses on wlan0
,W/NetworkManagementService(  799): route cmd failed: 
W/NetworkManagementService(  799): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '61 route del src v6 2' failed with '400 61 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  799): '
W/NetworkManagementService(  799): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  799): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  799): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  799): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  799): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  799): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  799): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  799): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  799): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  799): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  799): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  799): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  799): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  236): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController(  236): RTNETLINK answers: No such process
,V/RouteController(  236): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  236): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  799): android_net_utils_resetConnections in env=0x77df6940 clazz=0xa4500001 iface=wlan0 mask=0x3
,D/ConnectivityService(  799): resetConnections(wlan0, 3)
,I/WifiTrafficPoller(  799): evaluateTrafficStatsPolling
E/WifiStateMachine(  799): Error! unhandled message{ when=-153ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  799): Error! unhandled message{ when=-153ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  799): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
I/chromium( 5740): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
,V/NetworkStats(  799): updateIfacesLocked()
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
V/NetworkStats(  799): performPollLocked(flags=0x1)
V/NetworkStats(  799): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,V/NetworkStats(  799): performPollLocked() took 15ms
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,E/Watchdog(  799): !@Sync 10
,I/ApplicationPolicy(  799): updateDataUsageMap
,D/Tethering(  799): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  799): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  799): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  799): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1448): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3879): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): noConnectivity : true
,D/LocSvc_java(  799): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  799): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  799): ignore wifi update if we are not in OPENING or CLOSING
,I/KLMS-2.3.201 : ( 5417): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5417): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450240911073
,I/KLMS-2.3.201 : ( 5417): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5436): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5436): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/wpa_supplicant( 1974): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 1974): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1974): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1974): Trying to associate with  'G700'
I/wpa_supplicant( 1974): Re-associate with C0.AA.48
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
D/Tethering(  799): interfaceStatusChanged wlan0, false
,E/wpa_supplicant( 1974): Cmd 35609 not handled
I/SA      ( 4036): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4036): [BDLM] already registered in spp
I/SA      ( 4036): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4036): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4036): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4036): [OR] == isSIMCardReady false ==
,I/SA      ( 4036): [SCU] == networkStateCheck == false
,I/SA      ( 4036): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5449): Other Intent
,D/com.samsung.app( 1448): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1448): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4087): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4087): getCountryCode(): countryCode = PL
,D/Headlines( 4087): Breath.onCreate
,D/Headlines( 4087): Breath timer started. interval : 30000
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4087): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4087): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4087): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3338): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3338): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3338): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425e4330
,D/RCPManagerService(  799): exchangeData() failure , invalid userId
,D/RCPManagerService(  799): exchangeData() failure , invalid userId
,E/wpa_supplicant( 1974): Cmd 35605 not handled
E/wpa_supplicant( 1974): Cmd 35847 not handled
E/wpa_supplicant( 1974): Cmd 35848 not handled
E/wpa_supplicant( 1974): Cmd 35605 not handled
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1974): Associated with C0.AA.48
I/wpa_supplicant( 1974): freq(2412) increment count 3
,I/wpa_supplicant( 1974): meet head of list.
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
,D/Tethering(  799): interfaceStatusChanged wlan0, false
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
,D/Tethering(  799): interfaceStatusChanged wlan0, false
D/Tethering(  799): interfaceLinkStateChanged wlan0, false
,D/Tethering(  799): interfaceStatusChanged wlan0, false
D/Tethering(  799): interfaceLinkStateChanged wlan0, true
,D/Tethering(  799): interfaceStatusChanged wlan0, true
,E/Tethering(  799): No numeric data
D/Tethering(  799): interfaceLinkStateChanged wlan0, true
,D/Tethering(  799): interfaceStatusChanged wlan0, true
D/Tethering(  799): interfaceLinkStateChanged wlan0, true
,D/Tethering(  799): interfaceStatusChanged wlan0, true
D/Tethering(  799): interfaceLinkStateChanged wlan0, true
,D/Tethering(  799): interfaceStatusChanged wlan0, true
,D/Tethering(  799): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
I/ConnectivityService(  799): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  799): performPollLocked(flags=0x1)
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,V/NetworkStats(  799): performPollLocked() took 20ms
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
I/iu.Environment( 1759): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 1759): num queued entries: 0
I/iu.UploadsManager( 1759): num updated entries: 0
I/iu.SyncManager( 1759): NEXT; no task
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1974): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1974): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  799): interfaceLinkStateChanged wlan0, true
D/Tethering(  799): interfaceStatusChanged wlan0, true
D/WifiNative(  799): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/WifiP2pService(  799): InactiveState{ what=143375 }
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
D/WifiP2pService(  799): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/dhcpcd  ( 5864): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5864): bssid match
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): stay LED for fully charged
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(336), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  799): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/WifiP2pService(  799): InactiveState{ what=143375 }
,D/WifiP2pService(  799): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/WifiStateMachine(  799): VerifyingLinkState enter
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  799): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  799): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  799): evaluateTrafficStatsPolling
D/ConnectivityService(  799): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  799): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/WifiStateMachine(  799): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
,D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,I/WifiTrafficPoller(  799): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  799): mBoosterFLAG : 2
,I/WifiTrafficPoller(  799): current booster mode : BTCoexMode
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  799): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  799): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  799): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  799): handleConnectivityChange: setting default proxy info 
,V/RouteController(  236): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
D/Toast   ( 1318):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1318): showing allowed
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,V/RouteController(  236): /system/bin/ip -4 rule del table 2 2>&1
,I/SurfaceFlinger(  245): id=27 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,V/RouteController(  236): RTNETLINK answers: No such file or directory
,D/PowerManagerService(  799): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=799
V/RouteController(  236): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,V/RouteController(  236): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,V/RouteController(  236): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,V/RouteController(  236): RTNETLINK answers: No such process
,V/RouteController(  236): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  236): /system/bin/ip route flush cached 2>&1
,V/NetworkStats(  799): updateIfacesLocked()
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,V/NetworkStats(  799): performPollLocked(flags=0x1)
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
V/NetworkStats(  799): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
V/NetworkStats(  799): performPollLocked() took 26ms
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,D/NtpTrustedTime(  799): currentTimeMillis() cache hit
,I/jxcore-log( 5740): Connected to the server!
I/jxcore-log( 5740): 
,I/chromium( 5740): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  799): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  799): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  799): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  239): DCD ON
,D/accuweather( 1448): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 3879): type=WIFI subType= reason=null isConnected=true
,D/LocSvc_java(  799): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  799): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  799): ignore wifi update if we are not in OPENING or CLOSING
,I/KLMS-2.3.201 : ( 5417): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5417): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450240914905
,I/KLMS-2.3.201 : ( 5417): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5436): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5436): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/LocationTagReadyService( 2563): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 2563): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2563): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2563): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 2439): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,V/KVNProvider( 5606): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5606): getFindoCursor query string : 
,V/KVNProvider( 5606): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4036): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4036): [BDLM] already registered in spp
I/SA      ( 4036): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4036): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4036): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4036): [OR] == isSIMCardReady false ==
I/SA      ( 4036): [SCU] == networkStateCheck == true
I/SA      ( 4036): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4036): isChinaCountryCode : false
I/SA      ( 4036): [OR] == networkStateCheck true ==
,I/SA      ( 4036): [OR] GetMyCountryZoneTask
,I/SA      ( 4036): [OR] onReceive END
,I/SA      ( 4036): [SRS] prepareGetMyCountryZone
,I/SA      ( 4036): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4036): [SSP] query invoked
I/SA      ( 4036): [TPMU] GetMccFromDB : null
I/SA      ( 4036): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4036): [TPM] isNoProxy(default) : true
,I/SA      ( 4036): [RC New] Execute method=[GET] start
,I/jxcore-log( 5740): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5740): 
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5449): Other Intent
,D/com.samsung.app( 1448): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1448): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4087): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4087): getCountryCode(): countryCode = PL
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4087): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4087): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 4087): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4087): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3338): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3338): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3338): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425e4330
,D/RCPManagerService(  799): exchangeData() failure , invalid userId
,D/RCPManagerService(  799): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4170): notifyNetworkActivated
,D/hcjo    ( 4170): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4170): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4170): exit::IDLE
,D/InitializeManagerStateMachine( 4170): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4170): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4170): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4170): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4170): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4170): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4170): entry::SUCCESS
,D/hcjo    ( 4170): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4170): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4170): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4170): exit::SUCCESS
,D/InitializeManagerStateMachine( 4170): entry::IDLE
,I/iu.Environment( 1759): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1759): num queued entries: 0
,I/iu.UploadsManager( 1759): num updated entries: 0
,I/iu.SyncManager( 1759): NEXT; no task
,D/dalvikvm( 1759): GC_CONCURRENT freed 1661K, 36% free 12215K/18920K, paused 5ms+6ms, total 58ms
,I/SA      ( 4036): [RC New] [v2liruge] api execute + 682
,I/SA      ( 4036): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4036): AsyncTask #3 calls detatch()
,I/SA      ( 4036): [TPMU] getNetworkMcc : 
,I/SA      ( 4036): [SCU] saveMccToPreferece Start
I/SA      ( 4036): [SCU] RegionMCC : 260
,I/SA      ( 4036): [SSP] query invoked
,I/SA      ( 4036): [TPMU] GetMccFromDB : null
,I/SA      ( 4036): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4036): [SCU] saveMccToPreferece End
,I/SA      ( 4036): [RC New] executeRequest [v2liruge] end. 708
,I/SA      ( 4036): [RC New] Execute end
,I/SA      ( 4036): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4036): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService(  799): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,W/WifiP2pStateTracker(  799): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  799): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  799):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  799): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  799): updateSourceRoutes : no source routing conditions
,E/WifiStateMachine(  799): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  245): id=27 Removed Uoast (12/13)
,I/SurfaceFlinger(  245): id=27 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  799): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=799 (0x0)
,D/PowerManagerService(  799): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=799, ws=WorkSource{1000}) (elapsedTime=3509)
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5070): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5070): [GetString-S]
,I/terrier ( 5070): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5070): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5070): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5070): Loaded image: APP id = 6
,D/QSEECOMAPI: ( 5070): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5070): QSEECom_shutdown_app, app_id = 6
,E/terrier ( 5070): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5070): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5070): [ensureRegistration] - No Samsung account
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/AmoledAdjustTimer(  799): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/CaptivePortalTracker(  799): DelayedCaptiveCheckState{ when=0 what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  799): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  799): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  799): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  799): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  799): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  799): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  799): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4170): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4170): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4170): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4170): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4170): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4170): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4170): entry::IDLE
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  799): Waited long enough for: ServiceRecord{44254f70 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  799): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager(  799): waitForAlarm result :4
,V/AlarmManager(  799): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PowerManagerService(  799): [PWL] Off : 275s ago
,I/PowerManagerService(  799): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  799): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  799): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=799, ws=WorkSource{10075}) (elapsedTime=67)
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,I/SELinux ( 5982): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5982):  
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,I/SELinux ( 5982): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5982):  
I/SELinux ( 5982):  
,I/SELinux ( 5982): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5982): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5982): >>>>> Normal User
,E/dalvikvm( 5982): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5982): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5982): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5982): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5982): Added TimaKesytore provider
,W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=5982, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 18761 latestRequest time : 1450240915107 current time : 1450240933868
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 11
,V/AlarmManager(  799): waitForAlarm result :8
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 26110 latestRequest time : 1450240915107 current time : 1450240941217
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  799): mCoverManager.getCoverState() : true
D/BatteryService(  799): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 12
,V/AlarmManager(  799): waitForAlarm result :8
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 56106 latestRequest time : 1450240915107 current time : 1450240971214
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  799): [PWL] Off : 330s ago
,E/SMD     (  239): DCD ON
D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 13
,V/AlarmManager(  799): waitForAlarm result :8
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 86103 latestRequest time : 1450240915107 current time : 1450241001210
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  799): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  239): DCD ON
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  799): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 14
,V/AlarmManager(  799): waitForAlarm result :8
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 116105 latestRequest time : 1450240915107 current time : 1450241031212
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  799): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  799): [PWL] Off : 390s ago
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 15
,V/AlarmManager(  799): waitForAlarm result :8
,D/Headlines( 4087): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4087): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4087): Breath 146102 latestRequest time : 1450240915107 current time : 1450241061209
,D/Headlines( 4087): stop 
,D/Headlines( 4087): Breath.onDestroy : 
,I/ActivityManager(  799): Killing 4572:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/dalvikvm(  799): GC_CONCURRENT freed 3363K, 58% free 23846K/55796K, paused 24ms+53ms, total 553ms
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 16
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService(  799): [PWL] Off : 455s ago
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 17
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 18
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 19
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService(  799): [PWL] Off : 525s ago
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService(  799): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  799): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  799): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,E/SMD     (  239): DCD ON
W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  799): !@Sync 20
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  799): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 21
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,I/SensorManagerA(  799): getReportingMode :: sensor.mType = 5
,D/Sensors (  799): LightSensor setDelay = 200000000
,D/Sensors (  799): LightSensor setSensorDelay = 200000000
,D/LightsService(  799): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  799): Light sensor flush: not enabled 0
D/Sensors (  799): LightSensor enable = 1
D/Sensors (  799): LightSensor enableSensor = 1
D/SensorManager(  799): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService(  799): [PWL] Off : 600s ago
,D/LightsService(  799): [SvcLED]  onSensorChanged::light value = 0
D/Sensors (  799): LightSensor enable = 0
D/Sensors (  799): LightSensor enableSensor = 0
,D/SensorManager(  799): unregisterListener ::   
D/LightsService(  799): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 22
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  799): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  799): <AppSync3 Whitelist>
,V/AlarmManager(  799): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 23
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 24
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  799): [PWL] Off : 680s ago
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 25
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 26
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  799): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  239): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 27
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  799): [PWL] Off : 765s ago
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  799): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 28
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  799): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 29
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService(  799): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  799): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  799): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 30
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService(  799): [PWL] Off : 855s ago
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 31
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/dalvikvm(  799): GC_CONCURRENT freed 3571K, 57% free 23767K/55016K, paused 48ms+50ms, total 622ms
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 32
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  799): mCoverManager.getCoverState() : true
D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 33
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  799): [PWL] Off : 950s ago
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 34
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 35
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 36
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  799): [PWL] Off : 1050s ago
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 37
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 38
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 39
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/TimaService(  799): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  799): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  799): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 40
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService(  799): [PWL] Off : 1155s ago
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :4
,V/AlarmManager(  799): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  799): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 41
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  799): mCoverManager.getCoverState() : true
D/BatteryService(  799): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,I/SensorManagerA(  799): getReportingMode :: sensor.mType = 5
,D/LightsService(  799): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  799): LightSensor setDelay = 200000000
,D/Sensors (  799): LightSensor setSensorDelay = 200000000
,D/Sensors (  799): Light sensor flush: not enabled 0
,D/Sensors (  799): LightSensor enable = 1
,D/Sensors (  799): LightSensor enableSensor = 1
,D/SensorManager(  799): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/LightsService(  799): [SvcLED]  onSensorChanged::light value = 0
D/Sensors (  799): LightSensor enable = 0
D/Sensors (  799): LightSensor enableSensor = 0
,D/SensorManager(  799): unregisterListener ::   
D/LightsService(  799): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 42
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  799): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  799): <AppSync3 Whitelist>
,V/AlarmManager(  799): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 43
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  799): [PWL] Off : 1265s ago
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 44
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,E/SMD     (  239): DCD ON
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 45
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 46
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 47
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  799): [PWL] Off : 1380s ago
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,D/dalvikvm(  799): GC_CONCURRENT freed 3468K, 57% free 23807K/55016K, paused 22ms+50ms, total 545ms
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 48
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 49
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/TimaService(  799): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  799): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  799): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 50
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 51
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,E/SMD     (  239): DCD ON
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  799): [PWL] Off : 1500s ago
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 52
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 53
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  799): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 54
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 55
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  799): [PWL] Off : 1625s ago
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 56
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 57
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 58
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  239): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 59
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/TimaService(  799): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  799): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  799): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  799): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  799): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 60
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  799): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): stay LED for fully charged
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,I/ProcessStatsService(  799): Prepared write state in 151ms
,I/ProcessStatsService(  799): Prepared write state in 127ms
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,I/ProcessStatsService(  799): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-46-39.bin
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  799): !@Sync 61
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  799): !@Sync 62
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  799): waitForAlarm result :8
,V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  799): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  799): <AppSync3 Whitelist>
,V/AlarmManager(  799): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,I/ActivityManager(  799): Killing 4528:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1823s
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  799): stay LED for fully charged
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/dalvikvm(  799): GC_CONCURRENT freed 3495K, 57% free 23813K/55016K, paused 25ms+25ms, total 536ms
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  799): !@Sync 63
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  799): mCoverManager.getCoverState() : true
,D/BatteryService(  799): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  239): DCD ON
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  239): DCD ON
E/SMD     (  239): DCD ON
E/Watchdog(  799): !@Sync 64
D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  799): stay LED for fully charged
D/UiModeManager(  799): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1963): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  239): DCD ON
E/SMD     (  239): DCD ON
D/SSRMv2:SIOP(  799): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  799): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
E/SMD     (  239): DCD ON
D/AndroidRuntime( 6351): 
D/AndroidRuntime( 6351): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6351): CheckJNI is OFF
D/AndroidRuntime( 6351): setted country_code = Poland
D/AndroidRuntime( 6351): setted countryiso_code = PL
D/AndroidRuntime( 6351): setted sales_code = XEO
D/AndroidRuntime( 6351): readGMSProperty: start
D/AndroidRuntime( 6351): readGMSProperty: already setted!!
D/AndroidRuntime( 6351): readGMSProperty: end
D/AndroidRuntime( 6351): addProductProperty: start
D/dalvikvm( 6351): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6351): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6351): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6351): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6351): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6351): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6351): failed to load memtrack module: -2
D/dalvikvm( 6351): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6351): Calling main entry com.android.commands.pm.Pm
V/AlarmManager(  799): waitForAlarm result :8
V/AlarmManager(  799): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
I/ActivityManager(  799): Killing 5574:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1827s
I/ActivityManager(  799): Killing 5292:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1834s
I/ActivityManager(  799): Killing 5280:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1834s
I/ActivityManager(  799): Killing 5266:com.samsung.helphub/1000 (adj 15): empty for 1834s
I/ActivityManager(  799): Killing 5253:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1834s
I/ActivityManager(  799): Killing 5235:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1835s
I/ActivityManager(  799): Killing 5176:com.google.android.apps.docs/u0a90 (adj 15): empty for 1835s
I/ActivityManager(  799): Killing 5161:com.sec.android.service.cm/u0a78 (adj 15): empty for 1835s
I/ActivityManager(  799): Killing 4655:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1836s
I/ActivityManager(  799): Killing 4303:com.android.mms/u0a48 (adj 15): empty for 1836s
I/ActivityManager(  799): Killing 5123:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1836s
I/ActivityManager(  799): Killing 4203:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1836s
I/ActivityManager(  799): Killing 5083:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1837s
I/ActivityManager(  799): Killing 5054:com.android.musicfx/u0a24 (adj 15): empty for 1837s
I/ActivityManager(  799): Killing 5042:com.samsung.groupcast/u0a15 (adj 15): empty for 1837s
I/ActivityManager(  799): Killing 5027:com.google.android.partnersetup/u0a14 (adj 15): empty for 1837s
I/ActivityManager(  799): Killing 5015:com.sec.android.inputmethod/1000 (adj 15): empty for 1838s
I/ActivityManager(  799): Killing 4960:com.android.defcontainer/u0a6 (adj 15): empty for 1838s
D/PackageManagerService(  799): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  799): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  799): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  799): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  799): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  799): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  799): START PACKAGE DELETE: observer{1125340992}
D/PackageManager(  799): pkg{<packageName>}
D/PackageManager(  799): user{0}
D/PackageManager(  799): deletePackageAsUser : uid = 2000 userId = 0
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/PackageManager(  799): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  799): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  799): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  799): getApplicationUninstallationEnabled
D/ApplicationPolicy(  799): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  799): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  799): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  799): Killing 5740:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/SurfaceFlinger(  245): id=22 Removed NainActivit (7/12)
I/SurfaceFlinger(  245): id=22 Removed NainActivit (-2/12)
I/SurfaceFlinger(  245): id=22 Removed NainActivit (-2/12)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/WindowState(  799): WIN DEATH: Window{436689b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/CountryDetector(  799): No listener is left
W/PackageSettings(  799): Skipping PackageSetting{42693a28 com.example.hello/10181} due to missing metadata
D/PackageManager(  799): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager(  799): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 2195): GC_EXPLICIT freed 538K, 43% free 10954K/18920K, paused 4ms+3ms, total 46ms
I/FPMS_FingerprintManagerService( 1087): onReceive: android.intent.action.PACKAGE_REMOVED
I/InputReader(  799): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 1759): GC_EXPLICIT freed 119K, 37% free 12097K/18920K, paused 12ms+15ms, total 61ms
D/AdaptiveEventManager( 1068): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3338): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 1211): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "sms"
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 1406): GC_EXPLICIT freed 4305K, 47% free 10029K/18920K, paused 4ms+8ms, total 85ms
I/SELinux ( 6377): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6377):  
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "smsto"
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "mms"
I/SELinux ( 6377): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6377):  
I/SELinux ( 6377):  
I/SELinux ( 6377): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6377): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6377): >>>>> Normal User
E/dalvikvm( 6377): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6377): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6377): in addTimaSignatureService
D/TimaKeyStoreProvider( 6377): Cannot add TimaSignature Service, License check Failed
D/dalvikvm(  799): GC_EXPLICIT freed 1488K, 57% free 23814K/55016K, paused 8ms+18ms, total 167ms
D/dalvikvm(  799): WAIT_FOR_CONCURRENT_GC blocked 32ms
D/ActivityThread( 6377): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "mmsto"
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/RCPManagerService(  799): PackageReceiver onReceive()
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "sms"
I/HarmonyEASService(  799): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SurfaceFlinger(  245): id=28 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "smsto"
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "mms"
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=6377, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "mmsto"
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6377): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6377): ELMEngine.ELMEngine( context ).
D/elm:14132( 6377): MDMBridge.setEnterpriseBridge()
D/elm:14132( 6377): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6377): ElmAgentService : onCreate()
D/elm:14132( 6377): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6377): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6377): MDMBridge.getInstance()
D/elm:14132( 6377): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 6392): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6392):  
D/elm:14132( 6377): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6377): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 6377): ElmAgentService : onDestroy().
I/SELinux ( 6392): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6392):  
I/SELinux ( 6392):  
I/SELinux ( 6392): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6392): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6392): >>>>> Normal User
E/dalvikvm( 6392): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6392): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/BatteryService(  799): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
D/TimaKeyStoreProvider( 6392): in addTimaSignatureService
D/BatteryService(  799): stay LED for fully charged
D/TimaKeyStoreProvider( 6392): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6392): Added TimaKesytore provider
D/dalvikvm(  799): GC_EXPLICIT freed 714K, 57% free 23870K/55016K, paused 8ms+25ms, total 255ms
D/PackageManager(  799): delete sourFile : 
D/BackupManagerService(  799): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  799): removePackageParticipantsLocked: uid=10179 #1
D/PackageManager(  799): delete native library directory: 
D/PackageManager(  799): return delete result to caller: 1125340992
D/AndroidRuntime( 6351): Shutting down VM
D/dalvikvm( 6351): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+1ms, total 3ms
D/PackageManager(  799): returnCode: 1
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "sms"
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BatteryService(  799): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "smsto"
D/UiModeManager(  799): mCoverManager.getCoverState() : true
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
V/HeadsetService( 1963): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1963): Disconnected process message: 10
W/ActivityManager(  799): Permission Denial: getCurrentUser() from pid=6392, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "mms"
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
I/PackageManager(  799):   Action: "android.intent.action.SENDTO"
I/PackageManager(  799):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  799):   Scheme: "mmsto"
I/PackageManager(  799): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 6392): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425d7ad0, skipping init
I/SecureStorage( 6392): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6392): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  299): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6392
I/SecureStorage(  299): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6392): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 6392): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  299): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6392
I/SecureStorage(  299): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
D/Launcher( 1251): onRestart, Launcher: 1114101592
D/Launcher( 1251): onStart, Launcher: 1114101592
D/Launcher.HomeView( 1251): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1448): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1448): [237392/5] SurfaceWidget drawing first frame
I/SurfaceFlinger(  245): id=29 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/EnterpriseDeviceManagerService(  799): Package has changed for user 0
D/EnterpriseDeviceManagerService(  799): Admin package name: com.google.android.gms
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  799): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  799): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  799): clearDefaults: com.test.thalitest
W/AtomicFile(  799): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  799): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/InputReader(  799): Processing first event
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

```
