#### Test 506502789b39735_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5134, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
--------- beginning of /dev/log/main
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5134): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5134): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  758): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
I/SA      ( 4017): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4017): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4017): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4309): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2175): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4647): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5168): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5168):  
I/ActivityManager(  758): Killing 3954:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/SELinux ( 5168): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5168):  
I/SELinux ( 5168):  
I/SELinux ( 5168): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5168): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5168): >>>>> Normal User
E/dalvikvm( 5168): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5168): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/IcingCorporaProvider( 2175): UpdateCorporaTask done [took 97 ms] updated apps [took 97 ms] 
D/TimaKeyStoreProvider( 5168): in addTimaSignatureService
D/TimaKeyStoreProvider( 5168): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5168): Added TimaKesytore provider
D/CapabilityManagerService New( 5168): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5168, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5182): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5182):  
I/ActivityManager(  758): Killing 4220:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5182): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5182):  
I/SELinux ( 5182):  
I/SELinux ( 5182): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5182): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5182): >>>>> Normal User
E/dalvikvm( 5182): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5182): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5182): in addTimaSignatureService
D/TimaKeyStoreProvider( 5182): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5182): Added TimaKesytore provider
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5182, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5203): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5203):  
I/ActivityManager(  758): Killing 3967:com.sec.android.soagent/u0a37 (adj 15): empty #43
W/GAV2    ( 5182): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5203): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5203):  
I/SELinux ( 5203):  
I/SELinux ( 5203): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5203): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5203): >>>>> Normal User
E/dalvikvm( 5203): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5203): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5203): in addTimaSignatureService
D/TimaKeyStoreProvider( 5203): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5203): Added TimaKesytore provider
D/AndroidRuntime( 5197): 
D/AndroidRuntime( 5197): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/PackageIntentReceiver( 5203): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5203): Not GearManger package! 
D/AndroidRuntime( 5197): CheckJNI is OFF
D/AndroidRuntime( 5197): setted country_code = Poland
D/AndroidRuntime( 5197): setted countryiso_code = PL
D/AndroidRuntime( 5197): setted sales_code = XEO
D/AndroidRuntime( 5197): readGMSProperty: start
D/AndroidRuntime( 5197): readGMSProperty: already setted!!
D/AndroidRuntime( 5197): readGMSProperty: end
D/AndroidRuntime( 5197): addProductProperty: start
I/SELinux ( 5226): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5226):  
D/dalvikvm( 5197): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5197): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5197): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5197): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5197): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 5226): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5226):  
I/SELinux ( 5226):  
I/SELinux ( 5226): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5226): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5226): >>>>> Normal User
E/dalvikvm( 5226): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5226): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5226): in addTimaSignatureService
D/TimaKeyStoreProvider( 5226): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5226): Added TimaKesytore provider
D/MagazineService Version( 5226): Magazine-Channel: 13
D/MagazineService Version( 5226): Magazine-Provider: 13
D/MagazineService Version( 5226): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5226): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5226): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5226, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5226): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5246): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5246):  
D/MagazineService::MagazineService( 5226): [onHandleIntent] Send broadcast to (com.test.thalitest).
E/memtrack( 5197): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5197): failed to load memtrack module: -2
I/ActivityManager(  758): Killing 4336:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
D/dalvikvm( 5197): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 5246): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5246):  
I/SELinux ( 5246):  
I/SELinux ( 5246): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5246): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5246): >>>>> Normal User
E/dalvikvm( 5246): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5246): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5246): in addTimaSignatureService
D/TimaKeyStoreProvider( 5246): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5246): Added TimaKesytore provider
D/AndroidRuntime( 5197): Calling main entry com.android.commands.am.Am
E/SMD     (  240): DCD ON
V/ApplicationPolicy(  758): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  758): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 758  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  758): mDVFSHelper.acquire()
I/SELinux ( 5261): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5261):  
D/LockPatternUtils( 1065): isPcwEnable = null
D/AndroidRuntime( 5197): Shutting down VM
D/dalvikvm( 5197): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 5261): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5261):  
I/SELinux ( 5261):  
I/SELinux ( 5261): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5261): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5261): >>>>> Normal User
E/dalvikvm( 5261): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5261): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5261): in addTimaSignatureService
D/TimaKeyStoreProvider( 5261): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5261): Added TimaKesytore provider
D/LockPatternUtils( 1065): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2094): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2094): getDatabaseLocked(b,b,pwd)...
D/SurfaceWidgetView( 1249): destroyHardwareResources():1125865792
I/SELinux ( 5276): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5276):  
I/ActivityManager(  758): Killing 1335:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SurfaceFlinger(  246): id=7 Removed Mauncher (7/12)
I/SurfaceFlinger(  246): id=7 Removed Mauncher (-2/12)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1442): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1249): onTrimMemory. Level: 20
I/SELinux ( 5276): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5276):  
I/SELinux ( 5276):  
I/SELinux ( 5276): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
W/GAV2    ( 5182): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/SELinux ( 5276): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5276): >>>>> Normal User
E/dalvikvm( 5276): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 5276): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SurfaceFlinger(  246): id=13 Removed CatteryCove (7/11)
I/SurfaceFlinger(  246): id=13 Removed CatteryCove (-2/11)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  758): Killing 4351:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5261, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
D/TimaKeyStoreProvider( 5276): in addTimaSignatureService
D/TimaKeyStoreProvider( 5276): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5276): Added TimaKesytore provider
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5261, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5261): Binding Chromium to the background looper Looper (main, tid 1) {422893e0}
I/chromium( 5261): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5261): Initializing chromium process, renderers=0
,W/chromium( 5261): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5261): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5261): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5261): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5261): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5261): Remote Branch: 
I/Adreno-EGL( 5261): Local Patches: 
I/Adreno-EGL( 5261): Reconstruct Branch: 
,W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5276, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5276): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5300): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5300):  
I/ActivityManager(  758): Killing 4364:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5300): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5300):  
I/SELinux ( 5300):  
,I/SELinux ( 5300): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5300): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5300): >>>>> Normal User
,E/dalvikvm( 5300): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5300): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5300): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5300): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5300): Added TimaKesytore provider
,I/dalvikvm( 5261): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5261): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5261): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5261): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5261): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5261): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5261): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5261): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5261): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5261): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5261): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5261): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5261): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5261): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5261): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5261): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5261): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5261): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5261): CordovaWebView is running on device made by: samsung
,I/ActivityManager(  758): Killing 3551:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/Finsky  ( 3655): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 1756): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Loading module APK com.google.android.play.games
,I/dalvikvm( 1756): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1756): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0053
,I/SurfaceFlinger(  246): id=17 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5261): EGLImpl-HWUI Protected EGL context created
,I/dalvikvm( 1756): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1756): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 1756): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1756): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1756): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1756): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1756): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1756): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
D/OpenGLRenderer( 5261): Enabling debug mode 0
,W/AwContents( 5261): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  758): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 758  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  758): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 758  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  758): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  758): mDVFSHelper.release()
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1756): Submit a task: k
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.gass from APK com.google.android.gms
W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,D/k       ( 1756): Processing package: com.test.thalitest
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/GassUtils( 1756): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1756): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
I/PowerManagerService(  758): [PWL] Off : 50s ago
I/PowerManagerService(  758): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  758): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  758): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=1756, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=31)
,D/dalvikvm( 1756): GC_CONCURRENT freed 1885K, 37% free 11934K/18872K, paused 6ms+6ms, total 137ms
,D/JsMessageQueue( 5261): Set native->JS mode to OnlineEventsBridgeMode
,W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1756): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1756): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1756): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1756): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1756): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1756): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 1756): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1756): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1756): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1756): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1756): cleanUpNonGplusAccounts done.
,D/dalvikvm( 5261): Trying to load lib /data/app-lib/com.test.thalitest-49/libjxcore.so 0x425b0118
,D/dalvikvm( 5261): Added shared lib /data/app-lib/com.test.thalitest-49/libjxcore.so 0x425b0118
,D/jxcore_app_log( 5261): JniHelper::setJavaVM(0x41708528), pthread_self() = 1943287224
,D/JX-Cordova( 5261): jxcore cordova android initializing
,D/SSRMv2:SIOP(  758): SIOP:: AP = 310, Delta = 0
,W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5261): GC_CONCURRENT freed 4927K, 33% free 12766K/18872K, paused 2ms+2ms, total 35ms
,D/dalvikvm( 5261): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 5261): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/CustomFrequencyManagerService(  758): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 758  tag : ACTIVITY_RESUME_BOOSTER@9
,D/dalvikvm( 5261): GC_FOR_ALLOC freed 4716K, 28% free 15767K/21680K, paused 32ms, total 32ms
,I/Icing   ( 1756): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 1756): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/dalvikvm( 5261): GC_FOR_ALLOC freed 5083K, 32% free 16780K/24368K, paused 34ms, total 34ms
,I/dalvikvm-heap( 5261): Grow heap (frag case) to 21.897MB for 2475476-byte allocation
,D/dalvikvm( 5261): GC_FOR_ALLOC freed 3780K, 35% free 17465K/26788K, paused 31ms, total 32ms
,D/dalvikvm( 5261): GC_FOR_ALLOC freed 1241K, 36% free 17369K/26788K, paused 28ms, total 28ms
,E/SMD     (  240): DCD ON
,W/jxcore-log( 5261): Initializing JXcore engine
,W/jxcore-log( 5261): JXcore engine is ready
,W/jxcore-log( 5261): Starting JXcore engine
,W/jxcore-log( 5261): Platform android
W/jxcore-log( 5261): 
,W/jxcore-log( 5261): Process ARCH arm
W/jxcore-log( 5261): 
,I/jxcore-log( 5261): JXcore Cordova bridge is ready!
I/jxcore-log( 5261): 
,W/jxcore-log( 5261): JXcore engine is started
,I/chromium( 5261): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GAV2    ( 5182): Thread[GAThread,5,main]: No campaign data found.
,D/AmoledAdjustTimer(  758): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 5261): Toggling radios to true
I/jxcore-log( 5261): 
,D/BluetoothAdapter( 5261): enable(): BT is already enabled..!
,I/WifiManager( 5261): packageName : com.test.thalitest
I/WifiManager( 5261): setWifiEnabled : true
,I/WifiService(  758): setWifiEnabled: true pid=5261, uid=10179
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5261, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  758): Failed getting userId using ActivityManagerNative
W/WifiService(  758): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5261, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  758): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  758): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  758): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  758): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  758): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  758): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  758): disconnect: pid=5261, uid=10179
,I/wpa_supplicant( 1983): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5261): Radios toggled
I/jxcore-log( 5261): 
,I/jxcore-log( 5261): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5261): 
,I/jxcore-log( 5261): Perf Test app loaded loaded
I/jxcore-log( 5261): 
,I/jxcore-log( 5261): check test folder
I/jxcore-log( 5261): 
,I/jxcore-log( 5261): found test : ./testFindPeers.js
I/jxcore-log( 5261): 
,E/SMD     (  240): DCD ON
,I/wpa_supplicant( 1983): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1983): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering(  758): interfaceLinkStateChanged wlan0, false
,D/Tethering(  758): interfaceStatusChanged wlan0, false
D/Tethering(  758): InitialState.processMessage what=4
,I/wpa_supplicant( 1983): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1983): Cmd 35605 not handled
,E/wpa_supplicant( 1983): Cmd 35605 not handled
,I/wpa_supplicant( 1983): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,E/Tethering(  758): No numeric data
,D/Tethering(  758): sendTetherStateChangedBroadcast 0, 0, 0
I/ConnectivityService(  758): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
V/NetworkStats(  758): performPollLocked(flags=0x1)
,I/wpa_supplicant( 1983): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1983): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1983): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1983): First Scan Start
,I/wpa_supplicant( 1983): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering(  758): interfaceLinkStateChanged wlan0, false
,D/Tethering(  758): interfaceStatusChanged wlan0, false
W/Settings(  758): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  758): ignore requestNetworkTransitionWakelock airplane:true
,D/Tethering(  758): interfaceLinkStateChanged wlan0, false
,D/Tethering(  758): interfaceStatusChanged wlan0, false
,I/jxcore-log( 5261): found test : ./testSendData.js
I/jxcore-log( 5261): 
D/WifiP2pService(  758): InactiveState{ what=143375 }
D/WifiP2pService(  758): P2pEnabledState{ what=143375 }
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
V/NetworkStats(  758): performPollLocked() took 62ms
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  237): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  758): evaluateTrafficStatsPolling
I/wpa_supplicant( 1983): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1983): Skip scan - already scanning
D/ConnectivityService(  758): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  758): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  758): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  758): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  758): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  758): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
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
D/WifiP2pService(  758): InactiveState{ what=143375 }
D/WifiP2pService(  758): P2pEnabledState{ what=143375 }
D/ConnectivityService(  758): Attempting to switch to mobile
D/ConnectivityService(  758): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 5364): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5364):  
D/STATUSBAR-IconMerger( 1065): checkOverflow(336), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/CommandListener(  237): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
V/RouteController(  237): /system/bin/ip -6 route del default table 2 2>&1
,I/WifiTrafficPoller(  758): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  758): Error! unhandled message{ when=-46ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  758): Error! unhandled message{ when=-42ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  758): Error! unhandled message{ when=-5ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  237): RTNETLINK answers: No such process
V/RouteController(  237): /system/bin/ip -6 rule del table 2 2>&1
,I/SELinux ( 5364): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5364):  
I/SELinux ( 5364):  
,I/SELinux ( 5364): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/RouteController(  237): RTNETLINK answers: No such file or directory
,E/SELinux ( 5364): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5364): >>>>> Normal User
,E/dalvikvm( 5364): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5364): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService(  758): route cmd failed: 
W/NetworkManagementService(  758): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 route del src v6 2' failed with '400 39 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  758): '
W/NetworkManagementService(  758): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  758): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  758): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  758): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  758): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  758): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  758): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  758): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  758): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  758): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  758): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  237): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 5364): in addTimaSignatureService
,V/RouteController(  237): RTNETLINK answers: No such process
,V/RouteController(  237): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 5364): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5364): Added TimaKesytore provider
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,I/chromium( 5261): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/NetUtils(  758): android_net_utils_resetConnections in env=0x77e92208 clazz=0x6ac00001 iface=wlan0 mask=0x3
D/ConnectivityService(  758): resetConnections(wlan0, 3)
,V/NativeCrypto( 1310): Read error: ssl=0x7bdb2df8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1310): SSL shutdown failed: ssl=0x7bdb2df8: I/O error during system call, Broken pipe
,V/NetworkStats(  758): updateIfacesLocked()
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
V/NetworkStats(  758): performPollLocked(flags=0x1)
D/ConnectivityService(  758): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
V/NetworkStats(  758): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/System.out( 5364): Inside WakeupProvider
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,I/System.out( 5364): Inside onCreate() of WakeupTriggerProvide
V/NetworkStats(  758): performPollLocked() took 16ms
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,I/VlingoApplication( 5364): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5364): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5364): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5364): initQueue()
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  758): Killing 4391:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,I/ApplicationPolicy(  758): updateDataUsageMap
,D/Tethering(  758): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  758): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  758): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  758): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/accuweather( 1442): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LocSvc_java(  758): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  758): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  758): ignore wifi update if we are not in OPENING or CLOSING
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,I/NetworkMonitor( 3877): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5085): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5085): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5085): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5085): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5085): noConnectivity : true
,I/SELinux ( 5398): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5398):  
,I/SELinux ( 5398): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5398):  
I/SELinux ( 5398):  
,I/SELinux ( 5398): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5398): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 5398): >>>>> Normal User
,E/dalvikvm( 5398): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5398): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5398): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5398): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5398): Added TimaKesytore provider
,W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5398, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 1983): nl80211: Received scan results (11 BSSes)
,I/wpa_supplicant( 1983): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1983): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1983): Trying to associate with  'G700'
I/wpa_supplicant( 1983): Re-associate with C0.AA.48
,I/wpa_supplicant( 1983): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1983): Cmd 35609 not handled
,D/Tethering(  758): interfaceLinkStateChanged wlan0, false
,D/Tethering(  758): interfaceStatusChanged wlan0, false
,D/dalvikvm(  758): GC_EXPLICIT freed 2661K, 58% free 23929K/55664K, paused 7ms+13ms, total 143ms
,I/ActivityManager(  758): Killing 4406:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,E/wpa_supplicant( 1983): Cmd 35605 not handled
E/wpa_supplicant( 1983): Cmd 35847 not handled
E/wpa_supplicant( 1983): Cmd 35848 not handled
,E/wpa_supplicant( 1983): Cmd 35605 not handled
I/wpa_supplicant( 1983): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1983): Associated with C0.AA.48
I/wpa_supplicant( 1983): freq(2412) increment count 2
,I/wpa_supplicant( 1983): meet head of list.
,I/wpa_supplicant( 1983): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  758): interfaceLinkStateChanged wlan0, false
,D/Tethering(  758): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1983): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1983): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1983): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1983): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  758): interfaceLinkStateChanged wlan0, false
,D/Tethering(  758): interfaceStatusChanged wlan0, false
,D/Tethering(  758): interfaceLinkStateChanged wlan0, false
,D/Tethering(  758): interfaceStatusChanged wlan0, false
,D/Tethering(  758): interfaceLinkStateChanged wlan0, true
,D/Tethering(  758): interfaceStatusChanged wlan0, true
,D/WifiNative(  758): callSECApiVoid - ID [50]
,E/Tethering(  758): No numeric data
,D/Tethering(  758): sendTetherStateChangedBroadcast 1, 0, 0
I/ConnectivityService(  758): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
V/NetworkStats(  758): performPollLocked(flags=0x1)
,D/Tethering(  758): interfaceLinkStateChanged wlan0, true
,D/Tethering(  758): interfaceStatusChanged wlan0, true
,I/SELinux ( 5422): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5422):  
,D/Tethering(  758): interfaceLinkStateChanged wlan0, true
,D/Tethering(  758): interfaceStatusChanged wlan0, true
,D/Tethering(  758): interfaceLinkStateChanged wlan0, true
,D/Tethering(  758): interfaceStatusChanged wlan0, true
,D/Tethering(  758): interfaceLinkStateChanged wlan0, true
,D/Tethering(  758): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
V/NetworkStats(  758): performPollLocked() took 38ms
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/dalvikvm(  247): GC_EXPLICIT freed 43K, 50% free 9513K/18872K, paused 2ms+2ms, total 26ms
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/WifiP2pService(  758): InactiveState{ what=143375 }
I/SELinux ( 5422): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5422):  
I/SELinux ( 5422):  
,I/SELinux ( 5422): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5422): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5422): >>>>> Normal User
,E/dalvikvm( 5422): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,D/WifiP2pService(  758): P2pEnabledState{ what=143375 }
E/SELinux ( 5422): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9513K/18872K, paused 2ms+3ms, total 19ms
,D/TimaKeyStoreProvider( 5422): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5422): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5422): Added TimaKesytore provider
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9513K/18872K, paused 1ms+3ms, total 18ms
,W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5422, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  758): Killing 4439:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5435): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5435):  
,I/SELinux ( 5435): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5435):  
I/SELinux ( 5435):  
,I/SELinux ( 5435): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5435): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5435): >>>>> Normal User
,E/dalvikvm( 5435): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5435): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5435): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5435): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5435): Added TimaKesytore provider
,W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5435, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5435): KLMSValidator() : checkQATesting()
,I/dhcpcd  ( 5443): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5443): bssid match
,I/KLMS-2.3.201 : ( 5435): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450229686015
,I/KLMS-2.3.201 : ( 5435): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager(  758): Killing 4461:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5454): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5454):  
,I/SELinux ( 5454): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5454):  
I/SELinux ( 5454):  
,I/SELinux ( 5454): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5454): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5454): >>>>> Normal User
,E/dalvikvm( 5454): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5454): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5454): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5454): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5454): Added TimaKesytore provider
,W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5454, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,D/SO_AGENT( 5454): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5454): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4017): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4017): [BDLM] already registered in spp
,I/SA      ( 4017): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4017): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4017): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4017): [OR] == isSIMCardReady false ==
I/SA      ( 4017): [SCU] == networkStateCheck == false
,I/SA      ( 4017): [OR] onReceive END
I/ActivityManager(  758): Killing 4588:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): Phone number locator feature is dsiabled
,I/SELinux ( 5473): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5473):  
,I/SELinux ( 5473): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5473):  
I/SELinux ( 5473):  
,I/SELinux ( 5473): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5473): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5473): >>>>> Normal User
,E/dalvikvm( 5473): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5473): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5473): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5473): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5473): Added TimaKesytore provider
,I/sCloudBackupApp( 5473): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5473): Other Intent
,D/com.samsung.app( 1442): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1442): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ActivityManager(  758): Killing 4614:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 5500): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5500):  
,I/SELinux ( 5500): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5500):  
I/SELinux ( 5500):  
I/SELinux ( 5500): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5500): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5500): >>>>> Normal User
E/dalvikvm( 5500): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
E/SELinux ( 5500): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
D/TimaKeyStoreProvider( 5500): in addTimaSignatureService
D/TimaKeyStoreProvider( 5500): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5500): Added TimaKesytore provider
D/WifiP2pService(  758): InactiveState{ what=143375 }
D/WifiP2pService(  758): P2pEnabledState{ what=143375 }
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5500, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  758): Killing 4606:com.android.providers.calendar/u0a44 (adj 15): empty #43
D/Headlines( 4068): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 4068): getCountryCode(): countryCode = PL
D/Headlines( 4068): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4068): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4068): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4068): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4068): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4068): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 4068): requestUpdateNewsWelcomeCard !!! no welcome card
I/SELinux ( 5513): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5513):  
D/WifiStateMachine(  758): VerifyingLinkState enter
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
D/WifiStateMachine(  758): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  758): CaptivePortalCheckState enter
I/WifiTrafficPoller(  758): evaluateTrafficStatsPolling
D/WifiStateMachine(  758): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  758): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  758): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
I/WifiTrafficPoller(  758): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  758): mBoosterFLAG : 2
I/WifiTrafficPoller(  758): current booster mode : BTCoexMode
V/AlarmManager(  758): waitForAlarm result :4
D/ConnectivityService(  758): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  758): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  758): net.tcp.delack.wifi not found in system properties. Using defaults
I/SELinux ( 5513): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5513):  
I/SELinux ( 5513):  
I/SELinux ( 5513): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5513): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5513): >>>>> Normal User
E/dalvikvm( 5513): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
E/SELinux ( 5513): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
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
V/AlarmManager(  758): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/ConnectivityService(  758): handleConnectivityChange: setting default proxy info 
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
D/TimaKeyStoreProvider( 5513): in addTimaSignatureService
V/RouteController(  237): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
D/TimaKeyStoreProvider( 5513): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5513): Added TimaKesytore provider
V/RouteController(  237): /system/bin/ip -4 rule del table 2 2>&1
V/RouteController(  237): RTNETLINK answers: No such file or directory
V/RouteController(  237): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
D/BatteryService(  758): stay LED for fully charged
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  758): mCoverManager.getCoverState() : true
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
V/RouteController(  237): /system/bin/ip route flush cached 2>&1
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/RouteController(  237): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
V/RouteController(  237): RTNETLINK answers: No such process
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
V/RouteController(  237): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
V/RouteController(  237): /system/bin/ip route flush cached 2>&1
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5513): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5513): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
V/NetworkStats(  758): updateIfacesLocked()
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
W/GAV2    ( 5513): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/NetworkStats(  758): performPollLocked(flags=0x1)
V/NetworkStats(  758): advisePersistThreshold() given 9223372036854775, clamped to 2097152
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5513): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5513): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
V/NetworkStats(  758): performPollLocked() took 17ms
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
D/NtpTrustedTime(  758): currentTimeMillis() cache hit
V/WebViewChromium( 5513): Binding Chromium to the main looper Looper (main, tid 1) {42287f50}
I/chromium( 5513): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5513): Initializing chromium process, renderers=0
W/chromium( 5513): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5513): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5513): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5513): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5513): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5513): Remote Branch: 
I/Adreno-EGL( 5513): Local Patches: 
I/Adreno-EGL( 5513): Reconstruct Branch: 
D/FactoryTest( 4715): Not factory mode
D/FactoryTest( 4715): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4715): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4715): still no open session command from host, so toast
W/ContextImpl( 4715): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4715): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
I/NSApplication( 5513): Starting up...
V/ApplicationPolicy(  758): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/CustomFrequencyManagerService(  758): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 758  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  758): mDVFSHelper.acquire()
D/LockPatternUtils( 1065): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2094): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2094): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtils( 1065): isPcwEnable = null
E/MTPRx   ( 4715): started activity for popup
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5513, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
D/QuickConnect[1.1][2] ( 3320): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3320): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3320): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ba230
I/ActivityManager(  758): Killing 4668:com.google.android.talk/u0a105 (adj 15): empty #43
I/SELinux ( 5565): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5565):  
E/SettingsReceiverActivity( 4715): PREF_DONT_ASK_AGAIN : false
I/SELinux ( 5565): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5565):  
I/SELinux ( 5565):  
I/SELinux ( 5565): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5565): >>>>> Normal User
E/dalvikvm( 5565): >>>>> com.android.email [ userId:0 | appId:10155 ]
E/SELinux ( 5565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5565): in addTimaSignatureService
D/SettingsReceiverActivity( 4715): dev.kiessupport is : TRUE
D/TimaKeyStoreProvider( 5565): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5565): Added TimaKesytore provider
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,I/SurfaceFlinger(  246): id=18 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4715): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4715): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4715): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4715): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4715): Remote Branch: 
I/Adreno-EGL( 4715): Local Patches: 
I/Adreno-EGL( 4715): Reconstruct Branch: 
,I/HWUI    ( 4715): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4715): Enabling debug mode 0
,D/Tethering(  758): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  758): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  758): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/LocSvc_java(  758): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  758): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  758): ignore wifi update if we are not in OPENING or CLOSING
,E/SMD     (  240): DCD ON
,D/accuweather( 1442): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3877): type=WIFI subType= reason=null isConnected=true
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 5591): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5591):  
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  758): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 758  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  758): mDVFSHelper.release()
D/CustomFrequencyManagerService(  758): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 758  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
I/ActivityManager(  758): Killing 3007:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,I/SELinux ( 5591): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5591):  
I/SELinux ( 5591):  
,I/SELinux ( 5591): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5591): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5591): >>>>> Normal User
,E/dalvikvm( 5591): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5591): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 5602): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5602):  
D/TimaKeyStoreProvider( 5591): in addTimaSignatureService
D/TimaKeyStoreProvider( 5591): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5591): Added TimaKesytore provider
,I/ActivityManager(  758): Killing 4752:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 5602): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5602):  
I/SELinux ( 5602):  
,I/SELinux ( 5602): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5602): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5602): >>>>> Normal User
,E/dalvikvm( 5602): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5602): [DEBUG] seapp_context_lookup: seinfoCategory = shared
W/ActivityManager(  758): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider( 5591): onCreate
,D/BadgeProvider( 5591): DatabaseHelper
,W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5591, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
D/TimaKeyStoreProvider( 5602): in addTimaSignatureService
D/TimaKeyStoreProvider( 5602): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5602): Added TimaKesytore provider
D/BadgeProvider( 5591): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5591): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1249): reloadBadges entered.
D/BadgeProvider( 5591): sendNotify, [notify] : null
D/BadgeProvider( 5591): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5591): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5591): update, [UpdateCount] : 1
,W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5602, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/hcjo    ( 4166): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4166): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4166): exit::IDLE
,D/InitializeManagerStateMachine( 4166): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4166): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4166): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4166): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4166): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4166): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4166): entry::SUCCESS
,D/hcjo    ( 4166): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4166): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4166): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4166): exit::SUCCESS
,D/InitializeManagerStateMachine( 4166): entry::IDLE
,I/ActivityManager(  758): Killing 4769:com.wssyncmldm/1000 (adj 15): empty #43
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1302):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1302): showing allowed
,I/SurfaceFlinger(  246): id=19 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  758): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=758
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/Headlines( 4068): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4068): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4068): Breath 1197 latestRequest time : 1450229686561 current time : 1450229687758
I/PCWCLIENTTRACE_PushUtil( 5085): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5085): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5085): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5085): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/VacuumService( 1217): Vacuum at: now=1450229687915 tag=VacuumService
,I/KLMS-2.3.201 : ( 5435): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5435): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450229687963
,I/KLMS-2.3.201 : ( 5435): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5454): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2556): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2556): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2556): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2556): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5454): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2338): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5622): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5622):  
,I/SELinux ( 5622): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5622):  
I/SELinux ( 5622):  
,I/SELinux ( 5622): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/SELinux ( 5626): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5626):  
E/SELinux ( 5622): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5622): >>>>> Normal User
,E/dalvikvm( 5622): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5622): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5622): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5622): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5622): Added TimaKesytore provider
,I/SA      ( 4017): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4017): [BDLM] already registered in spp
,I/SA      ( 4017): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4017): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4017): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4017): [OR] == isSIMCardReady false ==
,I/SA      ( 4017): [SCU] == networkStateCheck == true
,I/SA      ( 4017): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4017): isChinaCountryCode : false
,I/SA      ( 4017): [OR] == networkStateCheck true ==
,I/SA      ( 4017): [OR] GetMyCountryZoneTask
,I/SA      ( 4017): [OR] onReceive END
,I/SELinux ( 5626): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5626):  
I/SELinux ( 5626):  
,I/SELinux ( 5626): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5626): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5626): >>>>> Normal User
E/dalvikvm( 5626): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
I/SA      ( 4017): [SRS] prepareGetMyCountryZone
I/SA      ( 4017): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4017): [SSP] query invoked
,E/SELinux ( 5626): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PhoneNumberLocatorBootCompletedReceiver( 1237): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): Phone number locator feature is dsiabled
I/SA      ( 4017): [TPMU] GetMccFromDB : null
I/SA      ( 4017): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4017): [TPM] isNoProxy(default) : true
I/SA      ( 4017): [RC New] Execute method=[GET] start
,I/SCloudBackupReceiver( 5473): Other Intent
,D/TimaKeyStoreProvider( 5626): in addTimaSignatureService
,D/com.samsung.app( 1442): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 5626): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5626): Added TimaKesytore provider
,D/com.samsung.app( 1442): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4068): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4068): getCountryCode(): countryCode = PL
,D/Headlines( 4068): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4068): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4068): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4068): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4068): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 4068): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4068): requestUpdateNewsWelcomeCard !!! no welcome card
,V/KVNProvider( 5626): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5626): getFindoCursor query string : 
,D/QuickConnect[1.1][2] ( 3320): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3320): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3320): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ba230
,V/KVNProvider( 5626): getTagSearchCursor() tagSearchCursor count : 0
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,D/RCPManagerService(  758): exchangeData() failure , invalid userId
,D/hcjo    ( 4166): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4166): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4166): exit::IDLE
,D/InitializeManagerStateMachine( 4166): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4166): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4166): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4166): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4166): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4166): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4166): entry::SUCCESS
,D/hcjo    ( 4166): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4166): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4166): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4166): exit::SUCCESS
,D/InitializeManagerStateMachine( 4166): entry::IDLE
I/ActivityManager(  758): Killing 4610:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/CustomFrequencyManagerService(  758): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 758  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SA      ( 4017): [RC New] [v2liruge] api execute + 654
,I/SA      ( 4017): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4017): AsyncTask #2 calls detatch()
,I/SA      ( 4017): [TPMU] getNetworkMcc : 
,I/SA      ( 4017): [SCU] saveMccToPreferece Start
,I/SA      ( 4017): [SCU] RegionMCC : 260
,I/SA      ( 4017): [SSP] query invoked
,I/SA      ( 4017): [TPMU] GetMccFromDB : null
I/SA      ( 4017): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4017): [SCU] saveMccToPreferece End
,I/SA      ( 4017): [RC New] executeRequest [v2liruge] end. 674
,I/SA      ( 4017): [RC New] Execute end
,I/SA      ( 4017): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4017): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 5261): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5261): 
,I/HarmonyEASService(  758): Updating for all 1
,D/SSRMv2:SIOP(  758): SIOP:: AP = 320, Delta = 10
,E/WifiStateMachine(  758): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SMD     (  240): DCD ON
,W/WifiP2pStateTracker(  758): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  758): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  758):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  758): handleConnectivityChange: setting default proxy info 
,I/SurfaceFlinger(  246): id=19 Removed Uoast (12/13)
,I/SurfaceFlinger(  246): id=19 Removed Uoast (-2/13)
D/ConnectivityService(  758): updateSourceRoutes : no source routing conditions
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/ActivityManager(  758): Killing 4187:com.android.calendar/u0a142 (adj 15): empty #43
,D/PowerManagerService(  758): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=758 (0x0)
,D/PowerManagerService(  758): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=758, ws=WorkSource{1000}) (elapsedTime=3553)
,I/GAV2    ( 5513): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5085): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5085): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5085): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5085): ================================================
,I/CSTORAGE( 5085):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5085): ================================================
,D/dalvikvm( 5085): No JNI_OnLoad found in /system/lib/libterrier.so 0x425b4388, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5085): [GetString-S]
,I/terrier ( 5085): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5085): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5085): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5085): Loaded image: APP id = 5
,D/QSEECOMAPI: ( 5085): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5085): QSEECom_shutdown_app, app_id = 5
,E/terrier ( 5085): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5085): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5085): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5085): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5085): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5085): [ensureRegistration] - No Samsung account
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 289, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager(  758): waitForAlarm result :4
,V/AlarmManager(  758): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Finsky  ( 3655): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3655): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/CaptivePortalTracker(  758): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  758): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  758): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  758): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  758): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  758): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  758): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  758): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4166): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4166): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4166): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4166): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4166): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4166): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4166): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 4166): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4166): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4166): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4166): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4166): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4166): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4166): entry::IDLE
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = -20
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 4
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService(  758): [PWL] Off : 75s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,D/Headlines( 4068): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4068): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4068): Breath 20809 latestRequest time : 1450229688192 current time : 1450229709001
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 293, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 5
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 290, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService(  758): [PWL] Off : 105s ago
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :4
,V/AlarmManager(  758): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 4068): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4068): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4068): Breath 58644 latestRequest time : 1450229688192 current time : 1450229746836
,E/SMD     (  240): DCD ON
,D/dalvikvm(  758): GC_EXPLICIT freed 3435K, 58% free 23879K/55664K, paused 26ms+22ms, total 530ms
,D/dalvikvm( 1310): GC_EXPLICIT freed 1688K, 43% free 10802K/18872K, paused 8ms+8ms, total 71ms
,I/PhenotypeConfigurator( 1217): Scheduling Phenotype for one-off execution 3452 seconds from now (1450229747950)
,D/GetConfigurationSnapshotOperation( 1217): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1217): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1217): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1217): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1217): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1217): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  758): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1217): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1217): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1217): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1217): Thread-107(HTTPLog):isShipBuild true
,I/System.out( 1217): Thread-107(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1217): GC_CONCURRENT freed 1518K, 37% free 11921K/18872K, paused 7ms+8ms, total 90ms
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 288, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 6
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,D/Headlines( 4068): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4068): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4068): Breath 80779 latestRequest time : 1450229688192 current time : 1450229768971
,I/PowerManagerService(  758): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 7
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,D/Headlines( 4068): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4068): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4068): Breath 110780 latestRequest time : 1450229688192 current time : 1450229798972
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 8
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,D/Headlines( 4068): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4068): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4068): Breath 140774 latestRequest time : 1450229688192 current time : 1450229828967
,D/Headlines( 4068): stop 
,D/Headlines( 4068): Breath.onDestroy : 
,I/ActivityManager(  758): Killing 4379:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 9
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService(  758): [PWL] Off : 225s ago
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5261): Connected to the server!
I/jxcore-log( 5261): 
,I/chromium( 5261): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  240): DCD ON
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  758): initializing...
,I/TLC_TIMA_PKM_initialize(  758): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  758): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  758): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  758): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  758): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  758): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  758): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  758): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  758): App is not loaded in QSEE
,D/QSEECOMAPI: (  758): Loaded image: APP id = 5
,I/TZ: qc_tlc_communication(  758): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_initialize(  758): Trustlet response is completed
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  758): !@Sync 10
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService(  758): [PWL] Off : 275s ago
,V/AlarmManager(  758): waitForAlarm result :4
,V/AlarmManager(  758): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5755): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5755):  
D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/dalvikvm(  247): GC_EXPLICIT freed 43K, 50% free 9513K/18872K, paused 25ms+28ms, total 284ms
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9513K/18872K, paused 19ms+24ms, total 187ms
,I/SELinux ( 5755): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5755):  
I/SELinux ( 5755):  
,I/SELinux ( 5755): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5755): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5755): >>>>> Normal User
,E/dalvikvm( 5755): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5755): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9513K/18872K, paused 19ms+21ms, total 192ms
,D/TimaKeyStoreProvider( 5755): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5755): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5755): Added TimaKesytore provider
,W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=5755, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  758): Killing 4564:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 11
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 12
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 330s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 13
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 14
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 390s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 15
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 16
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService(  758): [PWL] Off : 455s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 17
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 18
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  758): !@Sync 19
,D/dalvikvm(  758): GC_CONCURRENT freed 3508K, 58% free 23868K/55664K, paused 24ms+49ms, total 544ms
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  758): [PWL] Off : 525s ago
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  758): !@Sync 20
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  758): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 21
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,I/SensorManagerA(  758): getReportingMode :: sensor.mType = 5
,D/LightsService(  758): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  758): LightSensor setDelay = 200000000
D/Sensors (  758): LightSensor setSensorDelay = 200000000
D/Sensors (  758): Light sensor flush: not enabled 0
D/Sensors (  758): LightSensor enable = 1
D/Sensors (  758): LightSensor enableSensor = 1
D/SensorManager(  758): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService(  758): [PWL] Off : 600s ago
,D/Sensors (  758): LightSensor enable = 0
,D/Sensors (  758): LightSensor enableSensor = 0
,D/SensorManager(  758): unregisterListener ::   
D/LightsService(  758): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  758): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  758): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  758): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  758): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 22
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 23
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  240): DCD ON
D/BatteryService(  758): stay LED for fully charged
D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 24
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 680s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 25
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 26
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 27
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService(  758): [PWL] Off : 765s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 28
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 29
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  758): !@Sync 30
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService(  758): [PWL] Off : 855s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,E/SMD     (  240): DCD ON
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 31
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 32
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 33
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 950s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 34
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 35
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/dalvikvm(  758): GC_CONCURRENT freed 3540K, 57% free 23838K/55156K, paused 26ms+48ms, total 520ms
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 36
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 1050s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 37
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,E/SMD     (  240): DCD ON
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 38
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 39
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  758): stay LED for fully charged
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  758): mCoverManager.getCoverState() : true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 40
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  758): [PWL] Off : 1155s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 41
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,I/SensorManagerA(  758): getReportingMode :: sensor.mType = 5
,D/Sensors (  758): LightSensor setDelay = 200000000
,D/Sensors (  758): LightSensor setSensorDelay = 200000000
,D/Sensors (  758): Light sensor flush: not enabled 0
,D/Sensors (  758): LightSensor enable = 1
,D/LightsService(  758): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  758): LightSensor enableSensor = 1
D/SensorManager(  758): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  758): LightSensor enable = 0
,D/Sensors (  758): LightSensor enableSensor = 0
,D/LightsService(  758): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  758): unregisterListener ::   
D/LightsService(  758): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  758): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  758): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  758): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 42
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  758): !@Sync 43
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 44
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
E/Watchdog(  758): !@Sync 45
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 46
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 47
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 1380s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 48
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 49
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  758): !@Sync 50
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 51
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 1500s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 52
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  758): mCoverManager.getCoverState() : true
D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/dalvikvm(  758): GC_CONCURRENT freed 3510K, 57% free 23854K/54884K, paused 25ms+46ms, total 549ms
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 53
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  758): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 54
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 55
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  758): [PWL] Off : 1625s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 56
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  758): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 57
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 58
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 59
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/TimaService(  758): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  758): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  758): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  758): Prepared write state in 247ms
,E/SMD     (  240): DCD ON
,I/ProcessStatsService(  758): Prepared write state in 223ms
,I/ProcessStatsService(  758): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-43-53.bin
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  758): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  758): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  758): !@Sync 60
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  758): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 61
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :4
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
V/NetworkStats(  758): performPollLocked(flags=0x3)
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,V/AlarmManager(  758): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
V/NetworkStats(  758): performPollLocked() took 216ms
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,D/NtpTrustedTime(  758): currentTimeMillis() cache hit
,I/ActivityManager(  758): Killing 4523:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1801s
,I/SensorManagerA(  758): getReportingMode :: sensor.mType = 5
,D/Sensors (  758): LightSensor setDelay = 200000000
,D/Sensors (  758): LightSensor setSensorDelay = 200000000
,D/LightsService(  758): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  758): Light sensor flush: not enabled 0
D/Sensors (  758): LightSensor enable = 1
D/Sensors (  758): LightSensor enableSensor = 1
D/SensorManager(  758): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  758): LightSensor enable = 0
,D/Sensors (  758): LightSensor enableSensor = 0
,D/LightsService(  758): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  758): unregisterListener ::   
D/LightsService(  758): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1310): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1756): Aggregate from 1450229212762 (log), 1450229212762 (data)
,D/dalvikvm( 1756): GC_CONCURRENT freed 1645K, 35% free 12284K/18872K, paused 6ms+7ms, total 61ms
,E/SMD     (  240): DCD ON,
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  758): waitForAlarm result :8
,V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  758): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  758): <AppSync3 Whitelist>
,V/AlarmManager(  758): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 62
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  758): stay LED for fully charged
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  758): !@Sync 63
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  758): mCoverManager.getCoverState() : true
,D/BatteryService(  758): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  240): DCD ON
V/AlarmManager(  758): waitForAlarm result :8
V/AlarmManager(  758): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
I/ActivityManager(  758): Killing 5364:com.vlingo.midas/u0a33 (adj 15): empty for 1812s
I/ActivityManager(  758): Killing 5435:com.samsung.klmsagent/u0a18 (adj 15): empty for 1812s
I/ActivityManager(  758): Killing 5422:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1812s
I/ActivityManager(  758): Killing 3926:com.sec.android.diagmonagent/1000 (adj 15): empty for 1812s
I/ActivityManager(  758): Killing 5398:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1812s
I/ActivityManager(  758): Killing 3877:com.google.android.music:main/u0a122 (adj 15): empty for 1812s
I/ActivityManager(  758): Killing 5085:com.sec.pcw.device/1000 (adj 15): empty for 1812s
I/ActivityManager(  758): Killing 1302:com.android.settings/1000 (adj 15): empty for 1812s
I/ActivityManager(  758): Killing 5591:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1812s
I/ActivityManager(  758): Killing 5300:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1821s
I/ActivityManager(  758): Killing 5276:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1821s
I/ActivityManager(  758): Killing 5246:com.samsung.helphub/1000 (adj 15): empty for 1821s
I/ActivityManager(  758): Killing 5226:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1821s
I/ActivityManager(  758): Killing 5203:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1822s
I/ActivityManager(  758): Killing 5182:com.google.android.apps.docs/u0a90 (adj 15): empty for 1822s
I/ActivityManager(  758): Killing 5168:com.sec.android.service.cm/u0a78 (adj 15): empty for 1822s
I/ActivityManager(  758): Killing 4647:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1822s
I/ActivityManager(  758): Killing 4309:com.android.mms/u0a48 (adj 15): empty for 1822s
I/ActivityManager(  758): Killing 5134:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1822s
I/ActivityManager(  758): Killing 4202:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1823s
I/ActivityManager(  758): Killing 5099:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1823s
I/ActivityManager(  758): Killing 5070:com.android.musicfx/u0a24 (adj 15): empty for 1824s
I/ActivityManager(  758): Killing 5057:com.samsung.groupcast/u0a15 (adj 15): empty for 1824s
I/ActivityManager(  758): Killing 5041:com.google.android.partnersetup/u0a14 (adj 15): empty for 1824s
I/ActivityManager(  758): Killing 5025:com.sec.android.inputmethod/1000 (adj 15): empty for 1824s
I/ActivityManager(  758): Killing 4965:com.android.defcontainer/u0a6 (adj 15): empty for 1824s
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  240): DCD ON
D/CountryDetector(  758): No listener is left
E/Watchdog(  758): !@Sync 64
E/SMD     (  240): DCD ON
E/SMD     (  240): DCD ON
D/SSRMv2:SIOP(  758): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  758): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
E/SMD     (  240): DCD ON
D/AndroidRuntime( 6172): 
D/AndroidRuntime( 6172): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6172): CheckJNI is OFF
D/AndroidRuntime( 6172): setted country_code = Poland
D/AndroidRuntime( 6172): setted countryiso_code = PL
D/AndroidRuntime( 6172): setted sales_code = XEO
D/AndroidRuntime( 6172): readGMSProperty: start
D/AndroidRuntime( 6172): readGMSProperty: already setted!!
D/AndroidRuntime( 6172): readGMSProperty: end
D/AndroidRuntime( 6172): addProductProperty: start
D/dalvikvm( 6172): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6172): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6172): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6172): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6172): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/BatteryService(  758): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
D/BatteryService(  758): stay LED for fully charged
D/BatteryService(  758): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  758): mCoverManager.getCoverState() : true
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
E/memtrack( 6172): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6172): failed to load memtrack module: -2
D/dalvikvm( 6172): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6172): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  758): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  758): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  758): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  758): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  758): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  758): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  758): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  758): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  758): getApplicationUninstallationEnabled
D/ApplicationPolicy(  758): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  758): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  758): START PACKAGE DELETE: observer{1125192984}
D/PackageManager(  758): pkg{<packageName>}
D/PackageManager(  758): user{0}
D/PackageManager(  758): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  758): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  758): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  758): Killing 5261:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/SurfaceFlinger(  246): id=17 Removed NainActivit (7/12)
I/SurfaceFlinger(  246): id=17 Removed NainActivit (-2/12)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/WindowState(  758): WIN DEATH: Window{44780658 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  246): id=17 Removed NainActivit (-2/12)
D/dalvikvm(  758): GC_CONCURRENT freed 3617K, 57% free 23847K/54884K, paused 5ms+11ms, total 117ms
D/dalvikvm(  758): WAIT_FOR_CONCURRENT_GC blocked 103ms
W/PackageSettings(  758): Skipping PackageSetting{42c70010 com.example.hello/10181} due to missing metadata
D/PackageManager(  758): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 1084): onReceive: android.intent.action.PACKAGE_REMOVED
D/AdaptiveEventManager( 1065): action=android.intent.action.PACKAGE_REMOVED
D/PackageManager(  758): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
D/QuickConnect[1.1][2] ( 3320): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/RCPManagerService(  758): PackageReceiver onReceive()
I/HarmonyEASService(  758): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "sms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6197): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6197):  
D/dalvikvm( 1399): GC_EXPLICIT freed 4301K, 47% free 10032K/18872K, paused 6ms+8ms, total 77ms
W/GeofencerStateMachine( 1217): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1756): GC_EXPLICIT freed 209K, 36% free 12257K/18872K, paused 5ms+30ms, total 109ms
D/dalvikvm( 2175): GC_EXPLICIT freed 990K, 42% free 11001K/18872K, paused 5ms+4ms, total 109ms
I/SELinux ( 6197): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6197):  
I/SELinux ( 6197):  
I/SELinux ( 6197): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6197): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6197): >>>>> Normal User
E/dalvikvm( 6197): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6197): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "smsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6197): in addTimaSignatureService
D/TimaKeyStoreProvider( 6197): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6197): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "mms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "mmsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "sms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SurfaceFlinger(  246): id=20 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "smsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "mms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
V/BackupManagerService(  758): removePackageParticipantsLocked: uid=10179 #1
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "mmsto"
D/EnterpriseDeviceManagerService(  758): Package has changed for user 0
D/EnterpriseDeviceManagerService(  758): Admin package name: com.google.android.gms
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=6197, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 6197): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6197): ELMEngine.ELMEngine( context ).
D/elm:14132( 6197): MDMBridge.setEnterpriseBridge()
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 6197): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6197): ElmAgentService : onCreate()
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 6197): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6197): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6197): MDMBridge.getInstance()
D/elm:14132( 6197): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6197): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 6213): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6213):  
D/elm:14132( 6197): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 6197): ElmAgentService : onDestroy().
I/ActivityManager(  758): Killing 5454:com.sec.android.soagent/u0a37 (adj 15): empty for 1823s
D/dalvikvm(  758): GC_EXPLICIT freed 1639K, 57% free 23749K/54884K, paused 8ms+16ms, total 248ms
I/SELinux ( 6213): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6213):  
I/SELinux ( 6213):  
I/SELinux ( 6213): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6213): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/dalvikvm( 6213): >>>>> Normal User
E/dalvikvm( 6213): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6213): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager(  758): delete sourFile : 
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 6213): in addTimaSignatureService
D/TimaKeyStoreProvider( 6213): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6213): Added TimaKesytore provider
D/AndroidRuntime( 6172): Shutting down VM
D/PackageManager(  758): delete native library directory: 
D/PackageManager(  758): return delete result to caller: 1125192984
D/PackageManager(  758): returnCode: 1
D/dalvikvm( 6172): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "sms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  758):   Scheme: "smsto"
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "mms"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  758):   Action: "android.intent.action.SENDTO"
I/PackageManager(  758):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  758):   Scheme: "mmsto"
I/PackageManager(  758): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  758): Permission Denial: getCurrentUser() from pid=6213, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 6213): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425acb58, skipping init
I/SecureStorage( 6213): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6213): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6213
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6213): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 6213): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6213
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
D/Launcher( 1249): onRestart, Launcher: 1113929896
D/Launcher( 1249): onStart, Launcher: 1113929896
D/Launcher.HomeView( 1249): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1442): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1442): [237392/5] SurfaceWidget drawing first frame
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SurfaceFlinger(  246): id=21 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  758): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  758): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  758): clearDefaults: com.test.thalitest
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/InputReader(  758): Processing first event

```
