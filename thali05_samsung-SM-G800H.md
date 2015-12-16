#### Test 506502783fcf234_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
D/TimaKeyStoreProvider( 5203): in addTimaSignatureService
D/TimaKeyStoreProvider( 5203): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5203): Added TimaKesytore provider
I/SELinux ( 5229): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5229):  
--------- beginning of /dev/log/system
I/ActivityManager(  751): Killing 4004:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  248): GC_EXPLICIT freed 46K, 50% free 9507K/18696K, paused 2ms+3ms, total 34ms
I/SELinux ( 5229): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5229):  
I/SELinux ( 5229):  
I/SELinux ( 5229): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5229): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5229): >>>>> Normal User
E/dalvikvm( 5229): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5229): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9507K/18696K, paused 2ms+3ms, total 21ms
D/TimaKeyStoreProvider( 5229): in addTimaSignatureService
D/TimaKeyStoreProvider( 5229): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5229): Added TimaKesytore provider
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9507K/18696K, paused 2ms+2ms, total 20ms
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5229, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5229): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
W/ActivityManager(  751): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5229): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
I/SA      ( 4082): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4082): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4082): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4362): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2172): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4710): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5261): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5261):  
I/SELinux ( 5261): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5261):  
I/SELinux ( 5261):  
I/SELinux ( 5261): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/ActivityManager(  751): Killing 4020:com.samsung.klmsagent/u0a18 (adj 15): empty #43
E/SELinux ( 5261): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5261): >>>>> Normal User
E/dalvikvm( 5261): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
I/IcingCorporaProvider( 2172): UpdateCorporaTask done [took 99 ms] updated apps [took 99 ms] 
E/SELinux ( 5261): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5261): in addTimaSignatureService
D/TimaKeyStoreProvider( 5261): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5261): Added TimaKesytore provider
D/CapabilityManagerService New( 5261): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5261, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5276): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5276):  
I/ActivityManager(  751): Killing 4280:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5276): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5276):  
I/SELinux ( 5276):  
I/SELinux ( 5276): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5276): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5276): >>>>> Normal User
E/dalvikvm( 5276): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5276): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5276): in addTimaSignatureService
D/TimaKeyStoreProvider( 5276): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5276): Added TimaKesytore provider
,W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5276, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
W/GAV2    ( 5276): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/AndroidRuntime( 5288): 
D/AndroidRuntime( 5288): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5288): CheckJNI is OFF
D/AndroidRuntime( 5288): setted country_code = Poland
D/AndroidRuntime( 5288): setted countryiso_code = PL
D/AndroidRuntime( 5288): setted sales_code = XEO
D/AndroidRuntime( 5288): readGMSProperty: start
D/AndroidRuntime( 5288): readGMSProperty: already setted!!
D/AndroidRuntime( 5288): readGMSProperty: end
D/AndroidRuntime( 5288): addProductProperty: start
I/SELinux ( 5307): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5307):  
D/dalvikvm( 5288): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5288): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5288): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5288): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5288): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 5307): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5307):  
I/SELinux ( 5307):  
I/SELinux ( 5307): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5307): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5307): >>>>> Normal User
E/dalvikvm( 5307): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5307): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5307): in addTimaSignatureService
D/TimaKeyStoreProvider( 5307): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5307): Added TimaKesytore provider
D/PackageIntentReceiver( 5307): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5307): Not GearManger package! 
I/SELinux ( 5328): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5328):  
I/ActivityManager(  751): Killing 4033:com.sec.android.soagent/u0a37 (adj 15): empty #43
E/memtrack( 5288): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5288): failed to load memtrack module: -2
I/SELinux ( 5328): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5328):  
I/SELinux ( 5328):  
I/SELinux ( 5328): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5328): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5328): >>>>> Normal User
E/dalvikvm( 5328): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5328): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm( 5288): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/TimaKeyStoreProvider( 5328): in addTimaSignatureService
D/TimaKeyStoreProvider( 5328): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5328): Added TimaKesytore provider
D/MagazineService Version( 5328): Magazine-Channel: 13
D/MagazineService Version( 5328): Magazine-Provider: 13
D/MagazineService Version( 5328): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5328): [onCreate]
D/AndroidRuntime( 5288): Calling main entry com.android.commands.am.Am
D/MagazineService::MagazineBroadcastReceiver( 5328): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5328, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5328): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5343): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5343):  
D/MagazineService::MagazineService( 5328): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  751): Killing 1322:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 5343): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5343):  
I/SELinux ( 5343):  
I/SELinux ( 5343): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/ApplicationPolicy(  751): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5343): >>>>> Normal User
E/dalvikvm( 5343): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5343): in addTimaSignatureService
D/TimaKeyStoreProvider( 5343): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5343): Added TimaKesytore provider
D/CustomFrequencyManagerService(  751): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 751  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  751): mDVFSHelper.acquire()
I/SELinux ( 5355): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5355):  
D/LockPatternUtils( 1066): isPcwEnable = null
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1443): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/AndroidRuntime( 5288): Shutting down VM
W/GAV2    ( 5276): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/dalvikvm( 5288): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
I/ActivityManager(  751): Killing 4395:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
I/SurfaceFlinger(  245): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  245): id=14 Removed CatteryCove (-2/12)
D/SurfaceWidgetView( 1249): destroyHardwareResources():1125555464
I/SELinux ( 5355): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5355):  
I/SELinux ( 5355):  
I/SELinux ( 5355): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
E/SELinux ( 5355): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5355): >>>>> Normal User
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
E/dalvikvm( 5355): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5355): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5355): in addTimaSignatureService
D/TimaKeyStoreProvider( 5355): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5355): Added TimaKesytore provider
I/SurfaceFlinger(  245): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  245): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/Launcher( 1249): onTrimMemory. Level: 20
D/LockPatternUtils( 1066): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2100): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2100): getDatabaseLocked(b,b,pwd)...
E/SMD     (  239): DCD ON
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5355, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5355, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5355): Binding Chromium to the background looper Looper (main, tid 1) {4223d428}
I/chromium( 5355): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5355): Initializing chromium process, renderers=0
W/chromium( 5355): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5355): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5355): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5355): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5355): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5355): Remote Branch: 
I/Adreno-EGL( 5355): Local Patches: 
I/Adreno-EGL( 5355): Reconstruct Branch: 
,I/SELinux ( 5381): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5381):  
I/ActivityManager(  751): Killing 4410:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,I/dalvikvm( 5355): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5355): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5355): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5355): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5355): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5355): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5355): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5355): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5355): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5355): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5355): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5355): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5355): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5355): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5355): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5355): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5355): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5355): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5355): CordovaWebView is running on device made by: samsung
,I/SELinux ( 5381): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5381):  
I/SELinux ( 5381):  
,I/SELinux ( 5381): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5381): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5381): >>>>> Normal User
,E/dalvikvm( 5381): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5381): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5381): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5381): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5381): Added TimaKesytore provider
,W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5381, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5381): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5400): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5400):  
,I/SurfaceFlinger(  245): id=18 createSurf (1x1),1 flag=404, NainActivit
,I/ActivityManager(  751): Killing 4422:com.sec.esdk.elm/u0a94 (adj 15): empty #43
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5355): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 5355): Enabling debug mode 0
I/SELinux ( 5400): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5400):  
I/SELinux ( 5400):  
,I/SELinux ( 5400): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5400): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5400): >>>>> Normal User
,E/dalvikvm( 5400): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5400): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/AwContents( 5355): nativeOnDraw failed; clearing to background color.
,D/TimaKeyStoreProvider( 5400): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5400): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5400): Added TimaKesytore provider
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  751): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 751  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  751): mDVFSHelper.release()
D/CustomFrequencyManagerService(  751): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 751  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/ActivityManager(  751): Killing 3604:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/Finsky  ( 3710): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/PackageBroadcastService( 1782): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraModuleLdr( 1782): Loading module APK com.google.android.play.games
,I/dalvikvm( 1782): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
,W/dalvikvm( 1782): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1782): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1782): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1782): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1782): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1782): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1782): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1782): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1782): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/JsMessageQueue( 5355): Set native->JS mode to OnlineEventsBridgeMode
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1782): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1782): Submit a task: k
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/dalvikvm( 5355): Trying to load lib /data/app-lib/com.test.thalitest-51/libjxcore.so 0x42564198
,D/dalvikvm( 5355): Added shared lib /data/app-lib/com.test.thalitest-51/libjxcore.so 0x42564198
D/jxcore_app_log( 5355): JniHelper::setJavaVM(0x416e8528), pthread_self() = 2032723552
,D/JX-Cordova( 5355): jxcore cordova android initializing
,D/k       ( 1782): Processing package: com.test.thalitest
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/dalvikvm( 1782): GC_CONCURRENT freed 1983K, 37% free 11856K/18696K, paused 10ms+7ms, total 141ms
,D/dalvikvm( 1782): WAIT_FOR_CONCURRENT_GC blocked 31ms
D/dalvikvm( 1782): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 1782): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 1782): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/GassUtils( 1782): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1782): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1782): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1782): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1782): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1782): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1782): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1782): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1782): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1782): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1782): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1782): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1782): VFY: replacing opcode 0x6e at 0x0006
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1782): cleanUpNonGplusAccounts done.
,D/dalvikvm( 5355): GC_CONCURRENT freed 4918K, 32% free 12770K/18696K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 5355): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/dalvikvm( 1782): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1782): Module APK com.google.android.play.games already loaded
,D/CustomFrequencyManagerService(  751): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 751  tag : ACTIVITY_RESUME_BOOSTER@9
,D/dalvikvm( 5355): GC_FOR_ALLOC freed 4687K, 27% free 15762K/21480K, paused 31ms, total 32ms
,D/AmoledAdjustTimer(  751): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/Icing   ( 1782): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 5355): GC_FOR_ALLOC freed 5057K, 31% free 16775K/24168K, paused 35ms, total 41ms
,I/dalvikvm-heap( 5355): Grow heap (frag case) to 21.725MB for 2475476-byte allocation
,I/Icing   ( 1782): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/dalvikvm( 5355): GC_FOR_ALLOC freed 3778K, 35% free 17462K/26588K, paused 32ms, total 32ms
,D/dalvikvm( 5355): GC_FOR_ALLOC freed 1220K, 35% free 17362K/26588K, paused 29ms, total 29ms
,W/jxcore-log( 5355): Initializing JXcore engine
,W/jxcore-log( 5355): JXcore engine is ready
,W/jxcore-log( 5355): Starting JXcore engine
,W/jxcore-log( 5355): Platform android
W/jxcore-log( 5355): 
,W/jxcore-log( 5355): Process ARCH arm
W/jxcore-log( 5355): 
,E/SMD     (  239): DCD ON
,I/jxcore-log( 5355): JXcore Cordova bridge is ready!
I/jxcore-log( 5355): 
,W/jxcore-log( 5355): JXcore engine is started
,I/chromium( 5355): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GAV2    ( 5276): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  751): waitForAlarm result :4
V/AlarmManager(  751): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/Headlines( 4130): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 4130): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 4130): Breath 67619 latestRequest time : 1450238249550 current time : 1450238317169
D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService(  751): stay LED for fully charged
D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  751): mCoverManager.getCoverState() : true
V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
I/VacuumService( 1217): Vacuum at: now=1450238317387 tag=VacuumService
D/dalvikvm( 1327): GC_EXPLICIT freed 1376K, 43% free 10793K/18696K, paused 7ms+10ms, total 76ms
D/FactoryTest( 4780): Not factory mode
D/FactoryTest( 4780): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4780): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4780): still no open session command from host, so toast
W/ContextImpl( 4780): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4780): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
V/ApplicationPolicy(  751): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/CustomFrequencyManagerService(  751): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 751  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  751): mDVFSHelper.acquire()
D/LockPatternUtils( 1066): isPcwEnable = null
D/LockPatternUtils( 1066): isPcwEnable = null
E/MTPRx   ( 4780): started activity for popup
I/SQLiteSecureOpenHelper( 2100): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2100): getDatabaseLocked(b,b,pwd)...
E/SettingsReceiverActivity( 4780): PREF_DONT_ASK_AGAIN : false
D/SettingsReceiverActivity( 4780): dev.kiessupport is : TRUE
D/dalvikvm(  751): GC_EXPLICIT freed 2819K, 58% free 23890K/55724K, paused 8ms+14ms, total 194ms
,I/SurfaceFlinger(  245): id=19 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4780): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4780): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4780): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4780): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4780): Remote Branch: 
I/Adreno-EGL( 4780): Local Patches: 
I/Adreno-EGL( 4780): Reconstruct Branch: 
,I/HWUI    ( 4780): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4780): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/jxcore-log( 5355): Toggling radios to true
I/jxcore-log( 5355): 
,D/CustomFrequencyManagerService(  751): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 751  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  751): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  751): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 751  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/BluetoothAdapter( 5355): enable(): BT is already enabled..!
,I/WifiManager( 5355): packageName : com.test.thalitest
,I/WifiManager( 5355): setWifiEnabled : true
,I/WifiService(  751): setWifiEnabled: true pid=5355, uid=10179
,I/PhenotypeConfigurator( 1217): Scheduling Phenotype for one-off execution 6299 seconds from now (1450238318091)
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5355, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  751): Failed getting userId using ActivityManagerNative
W/WifiService(  751): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5355, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  751): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  751): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  751): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  751): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  751): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  751): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  751): disconnect: pid=5355, uid=10179
,I/jxcore-log( 5355): Radios toggled
I/jxcore-log( 5355): 
,I/wpa_supplicant( 1974): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5355): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5355): 
,I/jxcore-log( 5355): Perf Test app loaded loaded
I/jxcore-log( 5355): 
,I/jxcore-log( 5355): check test folder
I/jxcore-log( 5355): 
,I/jxcore-log( 5355): found test : ./testFindPeers.js
I/jxcore-log( 5355): 
,D/GetConfigurationSnapshotOperation( 1217): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/wpa_supplicant( 1974): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1974): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering(  751): interfaceLinkStateChanged wlan0, false
,D/Tethering(  751): interfaceStatusChanged wlan0, false
,D/Tethering(  751): InitialState.processMessage what=4
,E/Tethering(  751): No numeric data
,D/Tethering(  751): sendTetherStateChangedBroadcast 0, 0, 0
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1974): Cmd 35605 not handled
E/wpa_supplicant( 1974): Cmd 35605 not handled
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,I/wpa_supplicant( 1974): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/ConnectivityService(  751): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  751): performPollLocked(flags=0x1)
I/wpa_supplicant( 1974): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1974): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1974): First Scan Start
I/wpa_supplicant( 1974): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings(  751): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  751): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService(  751): InactiveState{ what=143375 }
D/WifiP2pService(  751): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/Tethering(  751): interfaceLinkStateChanged wlan0, false
D/Tethering(  751): interfaceStatusChanged wlan0, false
D/CommandListener(  236): Clearing all IP addresses on wlan0
D/Tethering(  751): interfaceLinkStateChanged wlan0, false
D/Tethering(  751): interfaceStatusChanged wlan0, false
,I/jxcore-log( 5355): found test : ./testSendData.js
I/jxcore-log( 5355): 
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
V/NetworkStats(  751): performPollLocked() took 50ms
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,I/WifiTrafficPoller(  751): evaluateTrafficStatsPolling
D/ConnectivityService(  751): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  751): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  751): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  751): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  751): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  751): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  751): Attempting to switch to mobile
D/ConnectivityService(  751): Attempting to switch to BLUETOOTH_TETHER
,I/wpa_supplicant( 1974): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1974): Skip scan - already scanning
D/STATUSBAR-IconMerger( 1066): checkOverflow(336), More:false, Req:false Child:2
,I/SELinux ( 5484): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5484):  
,V/RouteController(  236): /system/bin/ip -6 route del default table 2 2>&1
,D/WifiP2pService(  751): InactiveState{ what=143375 }
,D/WifiP2pService(  751): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  236): RTNETLINK answers: No such process
,V/RouteController(  236): /system/bin/ip -6 rule del table 2 2>&1
,I/SELinux ( 5484): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5484):  
I/SELinux ( 5484):  
I/SELinux ( 5484): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,V/RouteController(  236): RTNETLINK answers: No such file or directory
,E/SELinux ( 5484): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/CommandListener(  236): Clearing all IP addresses on wlan0
E/dalvikvm( 5484): >>>>> Normal User
,E/dalvikvm( 5484): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5484): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/WifiStateMachine(  751): Error! unhandled message{ when=-81ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  751): Error! unhandled message{ when=-80ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller(  751): evaluateTrafficStatsPolling
,W/NetworkManagementService(  751): route cmd failed: 
W/NetworkManagementService(  751): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  751): '
W/NetworkManagementService(  751): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  751): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  751): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  751): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  751): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  751): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  751): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  751): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  751): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  751): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  751): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  751): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  751): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  236): /system/bin/ip -4 route del default table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  236): RTNETLINK answers: No such process
,E/WifiStateMachine(  751): Error! unhandled message{ when=-10ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  236): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 5484): in addTimaSignatureService
,V/RouteController(  236): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 5484): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5484): Added TimaKesytore provider
,D/NetUtils(  751): android_net_utils_resetConnections in env=0x77f6bfb8 clazz=0x6aa00001 iface=wlan0 mask=0x3
D/ConnectivityService(  751): resetConnections(wlan0, 3)
,I/PhenotypeFlagCommitter( 1217): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,V/NativeCrypto( 1327): Read error: ssl=0x7bbf5e60: I/O error during system call, Connection timed out
,V/NativeCrypto( 1327): SSL shutdown failed: ssl=0x7bbf5e60: I/O error during system call, Broken pipe
,E/SMD     (  239): DCD ON
,I/chromium( 5355): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/ConnectivityService(  751): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
V/NetworkStats(  751): updateIfacesLocked()
V/NetworkStats(  751): performPollLocked(flags=0x1)
V/NetworkStats(  751): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1217): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1217): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1217): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1217): Using platform SSLCertificateSocketFactory
V/NetworkStats(  751): performPollLocked() took 19ms
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,I/System.out( 5484): Inside WakeupProvider
,I/System.out( 5484): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 5484): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5484): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5484): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/LocationManagerService(  751): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1217): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1217): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1217): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1217): Thread-105(HTTPLog):isShipBuild true
,I/System.out( 1217): Thread-105(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Uploader( 1217): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5484): initQueue()
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  751): Killing 4452:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/LocationManagerService(  751): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Uploader( 1217): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/ApplicationPolicy(  751): updateDataUsageMap
,D/Tethering(  751): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  751): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  751): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  751): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  751): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/LocSvc_java(  751): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  751): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1443): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,I/NetworkMonitor( 3928): type=WIFI subType= reason=null isConnected=false
I/PCWCLIENTTRACE_PushUtil( 5174): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5174): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5174): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5174): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5174): noConnectivity : true
,I/SELinux ( 5517): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5517):  
,I/SELinux ( 5517): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5517):  
I/SELinux ( 5517):  
,I/SELinux ( 5517): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5517): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5517): >>>>> Normal User
,E/dalvikvm( 5517): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5517): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5517): in addTimaSignatureService
,D/CustomFrequencyManagerService(  751): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 751  tag : ACTIVITY_RESUME_BOOSTER@9
D/TimaKeyStoreProvider( 5517): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5517): Added TimaKesytore provider
,W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5517, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  751): Killing 4467:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/SELinux ( 5534): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5534):  
,I/wpa_supplicant( 1974): nl80211: Received scan results (9 BSSes)
,I/wpa_supplicant( 1974): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1974): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1974): Trying to associate with  'G700'
I/wpa_supplicant( 1974): Re-associate with C0.AA.48
,I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1974): Cmd 35609 not handled
,D/dalvikvm(  248): GC_EXPLICIT freed 43K, 50% free 9507K/18696K, paused 5ms+6ms, total 32ms
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9507K/18696K, paused 2ms+3ms, total 22ms
I/SELinux ( 5534): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5534):  
I/SELinux ( 5534):  
,I/SELinux ( 5534): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5534): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5534): >>>>> Normal User
,E/dalvikvm( 5534): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5534): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/Tethering(  751): interfaceLinkStateChanged wlan0, false
,D/Tethering(  751): interfaceStatusChanged wlan0, false
,D/TimaKeyStoreProvider( 5534): in addTimaSignatureService
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9507K/18696K, paused 2ms+3ms, total 22ms
,D/TimaKeyStoreProvider( 5534): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5534): Added TimaKesytore provider
,E/wpa_supplicant( 1974): Cmd 35605 not handled
E/wpa_supplicant( 1974): Cmd 35847 not handled
E/wpa_supplicant( 1974): Cmd 35848 not handled
,E/wpa_supplicant( 1974): Cmd 35605 not handled
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1974): Associated with C0.AA.48
,I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1974): freq(2412) increment count 2
,I/wpa_supplicant( 1974): meet head of list.
D/Tethering(  751): interfaceLinkStateChanged wlan0, false
,D/Tethering(  751): interfaceStatusChanged wlan0, false
D/Tethering(  751): interfaceLinkStateChanged wlan0, false
,D/Tethering(  751): interfaceStatusChanged wlan0, false
D/Tethering(  751): interfaceLinkStateChanged wlan0, false
,D/Tethering(  751): interfaceStatusChanged wlan0, false
D/Tethering(  751): interfaceLinkStateChanged wlan0, true
,D/Tethering(  751): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1974): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1974): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1974): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/Tethering(  751): No numeric data
,D/Tethering(  751): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/WifiNative(  751): callSECApiVoid - ID [50]
,D/Tethering(  751): interfaceLinkStateChanged wlan0, true
,D/Tethering(  751): interfaceStatusChanged wlan0, true
D/Tethering(  751): interfaceLinkStateChanged wlan0, true
I/ConnectivityService(  751): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  751): performPollLocked(flags=0x1)
D/Tethering(  751): interfaceStatusChanged wlan0, true
D/Tethering(  751): interfaceLinkStateChanged wlan0, true
D/Tethering(  751): interfaceStatusChanged wlan0, true
D/Tethering(  751): interfaceLinkStateChanged wlan0, true
D/Tethering(  751): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,V/NetworkStats(  751): performPollLocked() took 30ms
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5534, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
D/WifiP2pService(  751): InactiveState{ what=143375 }
D/WifiP2pService(  751): P2pEnabledState{ what=143375 }
,I/ActivityManager(  751): Killing 4496:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5552): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5552):  
,I/SELinux ( 5552): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5552):  
I/SELinux ( 5552):  
,I/SELinux ( 5552): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5552): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5552): >>>>> Normal User
,E/dalvikvm( 5552): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5552): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5552): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5552): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5552): Added TimaKesytore provider
,W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5552, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5552): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5552): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450238319662
,I/KLMS-2.3.201 : ( 5552): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager(  751): Killing 4512:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5570): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5570):  
,I/dhcpcd  ( 5565): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5565): bssid match
,I/SELinux ( 5570): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5570):  
I/SELinux ( 5570):  
,I/SELinux ( 5570): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5570): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5570): >>>>> Normal User
E/dalvikvm( 5570): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5570): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5570): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5570): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5570): Added TimaKesytore provider
,D/SO_AGENT( 5570): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5570): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5570, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/SA      ( 4082): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4082): [BDLM] already registered in spp
I/SA      ( 4082): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4082): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4082): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4082): [OR] == isSIMCardReady false ==
,I/SA      ( 4082): [SCU] == networkStateCheck == false
,I/SA      ( 4082): [OR] onReceive END
I/ActivityManager(  751): Killing 4640:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SELinux ( 5586): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5586):  
,I/SELinux ( 5586): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5586):  
I/SELinux ( 5586):  
,I/SELinux ( 5586): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5586): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5586): >>>>> Normal User
,E/dalvikvm( 5586): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5586): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5586): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5586): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5586): Added TimaKesytore provider
,I/sCloudBackupApp( 5586): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5586): Other Intent
,I/ActivityManager(  751): Killing 4654:com.sec.android.app.voicenote/1000 (adj 15): empty #43
D/com.samsung.app( 1443): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1443): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5614): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5614):  
,I/SELinux ( 5614): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5614):  
I/SELinux ( 5614):  
,I/SELinux ( 5614): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5614): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5614): >>>>> Normal User
,E/dalvikvm( 5614): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5614): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5614): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5614): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5614): Added TimaKesytore provider
,W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5614, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  751): Killing 4678:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/Headlines( 4130): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4130): getCountryCode(): countryCode = PL
D/Headlines( 4130): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4130): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4130): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4130): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4130): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4130): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4130): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5632): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5632):  
,D/WifiP2pService(  751): InactiveState{ what=143375 }
,D/WifiP2pService(  751): P2pEnabledState{ what=143375 }
,I/SELinux ( 5632): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5632):  
I/SELinux ( 5632):  
,I/SELinux ( 5632): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5632): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5632): >>>>> Normal User
,E/dalvikvm( 5632): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5632): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5632): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5632): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5632): Added TimaKesytore provider
,D/WifiStateMachine(  751): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  751): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  751): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  751): evaluateTrafficStatsPolling
,D/WifiStateMachine(  751): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  751): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  751): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  751): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  751): mBoosterFLAG : 2
,I/WifiTrafficPoller(  751): current booster mode : BTCoexMode
D/ConnectivityService(  751): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  751): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  751): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  751): handleConnectivityChange: setting default proxy info 
,V/RouteController(  236): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  236): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  236): RTNETLINK answers: No such file or directory
,V/RouteController(  236): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,V/RouteController(  236): /system/bin/ip route flush cached 2>&1
,W/ContextImpl( 5632): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5632): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
,V/RouteController(  236): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/GAV2    ( 5632): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 5632): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,V/RouteController(  236): RTNETLINK answers: No such process
,V/RouteController(  236): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,W/ContextImpl( 5632): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
,V/RouteController(  236): /system/bin/ip route flush cached 2>&1
,D/SSRMv2:SIOP(  751): SIOP:: AP = 320, Delta = 10
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
V/NetworkStats(  751): updateIfacesLocked()
V/NetworkStats(  751): performPollLocked(flags=0x1)
V/NetworkStats(  751): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
V/NetworkStats(  751): performPollLocked() took 18ms
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,V/WebViewChromium( 5632): Binding Chromium to the main looper Looper (main, tid 1) {4223bf50}
,I/chromium( 5632): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5632): Initializing chromium process, renderers=0
,W/chromium( 5632): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5632): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5632): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5632): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5632): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5632): Remote Branch: 
I/Adreno-EGL( 5632): Local Patches: 
I/Adreno-EGL( 5632): Reconstruct Branch: 
,I/NSApplication( 5632): Starting up...
,W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5632, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  751): Killing 4731:com.google.android.talk/u0a105 (adj 15): empty #43
D/QuickConnect[1.1][2] ( 3374): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3374): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3374): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4256e2a8
,I/SELinux ( 5681): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5681):  
,I/SELinux ( 5681): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5681):  
I/SELinux ( 5681):  
,I/SELinux ( 5681): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5681): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5681): >>>>> Normal User
,E/dalvikvm( 5681): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5681): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5681): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5681): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5681): Added TimaKesytore provider
,D/RCPManagerService(  751): exchangeData() failure , invalid userId
,D/RCPManagerService(  751): exchangeData() failure , invalid userId
,D/RCPManagerService(  751): exchangeData() failure , invalid userId
,D/RCPManagerService(  751): exchangeData() failure , invalid userId
,D/RCPManagerService(  751): exchangeData() failure , invalid userId
,D/RCPManagerService(  751): exchangeData() failure , invalid userId
,I/SELinux ( 5700): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5700):  
I/ActivityManager(  751): Killing 3062:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
W/ActivityManager(  751): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5704): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5704):  
,I/SELinux ( 5700): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5700):  
I/SELinux ( 5700):  
,I/SELinux ( 5700): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5700): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5700): >>>>> Normal User
,E/dalvikvm( 5700): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
D/Tethering(  751): Tethering got CONNECTIVITY_ACTION
,E/SELinux ( 5700): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/Tethering(  751): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  751): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/LocSvc_java(  751): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  751): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  751): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1443): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5704): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5704):  
I/SELinux ( 5704):  
,I/SELinux ( 5704): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5704): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5704): >>>>> Normal User
,E/dalvikvm( 5704): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5704): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5700): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5704): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5700): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5700): Added TimaKesytore provider
,I/NetworkMonitor( 3928): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  751): Killing 4816:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5704): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5704): Added TimaKesytore provider
,W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5704, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
D/BadgeProvider( 5700): onCreate
,D/BadgeProvider( 5700): DatabaseHelper
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5700, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5700): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5700): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5700): sendNotify, [notify] : null
D/BadgeProvider( 5700): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5700): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5700): update, [UpdateCount] : 1
,D/Launcher.Model( 1249): reloadBadges entered.
,D/hcjo    ( 4216): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4216): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4216): exit::IDLE
,D/InitializeManagerStateMachine( 4216): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4216): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 4216): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4216): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4216): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4216): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4216): entry::SUCCESS
,D/hcjo    ( 4216): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4216): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4216): exit::SUCCESS
,D/InitializeManagerStateMachine( 4216): entry::IDLE
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1304):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1304): showing allowed
,I/SurfaceFlinger(  245): id=20 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  751): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=751
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
I/PCWCLIENTTRACE_PushUtil( 5174): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5174): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5174): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5174): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/KLMS-2.3.201 : ( 5552): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5552): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450238321368
,I/KLMS-2.3.201 : ( 5552): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5570): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2564): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 2564): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2564): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2564): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5570): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,E/SMD     (  239): DCD ON
,I/GallerySearchProvider( 2419): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5728): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5728):  
,I/SELinux ( 5732): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5732):  
I/SELinux ( 5728): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5728):  
I/SELinux ( 5728):  
I/SELinux ( 5728): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5728): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5728): >>>>> Normal User
E/dalvikvm( 5728): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5728): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5728): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5728): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5728): Added TimaKesytore provider
,I/SELinux ( 5732): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5732):  
I/SELinux ( 5732):  
,I/SELinux ( 5732): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5732): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5732): >>>>> Normal User
,E/dalvikvm( 5732): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5732): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5732): in addTimaSignatureService
,I/SA      ( 4082): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4082): [BDLM] already registered in spp
,D/TimaKeyStoreProvider( 5732): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5732): Added TimaKesytore provider
,I/SA      ( 4082): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4082): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4082): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4082): [OR] == isSIMCardReady false ==
,I/SA      ( 4082): [SCU] == networkStateCheck == true
,I/SA      ( 4082): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4082): isChinaCountryCode : false
,I/SA      ( 4082): [OR] == networkStateCheck true ==
,I/SA      ( 4082): [OR] GetMyCountryZoneTask
,I/SA      ( 4082): [OR] onReceive END
,I/SA      ( 4082): [SRS] prepareGetMyCountryZone
,I/SA      ( 4082): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4082): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5586): Other Intent
,I/ActivityManager(  751): Killing 4833:com.wssyncmldm/1000 (adj 15): empty #43
,V/KVNProvider( 5732): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5732): getFindoCursor query string : 
,D/com.samsung.app( 1443): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1443): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4130): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4130): getCountryCode(): countryCode = PL
,D/QuickConnect[1.1][2] ( 3374): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3374): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3374): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4256e2a8
,D/RCPManagerService(  751): exchangeData() failure , invalid userId
,D/Headlines( 4130): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4130): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4130): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/RCPManagerService(  751): exchangeData() failure , invalid userId
,D/Headlines( 4130): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4130): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 4130): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4130): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm(  751): GC_EXPLICIT freed 2623K, 58% free 23832K/55724K, paused 7ms+13ms, total 147ms
,V/KVNProvider( 5732): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4082): [TPMU] GetMccFromDB : null
,I/SA      ( 4082): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4082): [TPM] isNoProxy(default) : true
,I/SA      ( 4082): [RC New] Execute method=[GET] start
,D/hcjo    ( 4216): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4216): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4216): exit::IDLE
,D/InitializeManagerStateMachine( 4216): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4216): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4216): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4216): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4216): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4216): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4216): entry::SUCCESS
,D/hcjo    ( 4216): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4216): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4216): exit::SUCCESS
,D/InitializeManagerStateMachine( 4216): entry::IDLE
,I/ActivityManager(  751): Killing 4692:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,W/ProcessCpuTracker(  751): Skipping unknown process pid 5547
,W/ProcessCpuTracker(  751): Skipping unknown process pid 5548
,W/ProcessCpuTracker(  751): Skipping unknown process pid 5550
,W/ProcessCpuTracker(  751): Skipping unknown process pid 5574
,W/ProcessCpuTracker(  751): Skipping unknown process pid 5756
,I/SA      ( 4082): [RC New] [v2liruge] api execute + 686
,I/SA      ( 4082): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4082): AsyncTask #2 calls detatch()
,I/SA      ( 4082): [TPMU] getNetworkMcc : 
,I/SA      ( 4082): [SCU] saveMccToPreferece Start
,I/SA      ( 4082): [SCU] RegionMCC : 260
,I/SA      ( 4082): [SSP] query invoked
,I/SA      ( 4082): [TPMU] GetMccFromDB : null
I/SA      ( 4082): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4082): [SCU] saveMccToPreferece End
,I/SA      ( 4082): [RC New] executeRequest [v2liruge] end. 706
I/SA      ( 4082): [RC New] Execute end
,I/SA      ( 4082): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4082): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 5355): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5355): 
,I/HarmonyEASService(  751): Updating for all 1
,E/WifiStateMachine(  751): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/WifiP2pStateTracker(  751): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  751): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  751):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  751): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  751): updateSourceRoutes : no source routing conditions
,D/AmoledAdjustTimer(  751): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,I/ActivityManager(  751): Killing 4237:com.android.calendar/u0a142 (adj 15): empty #43
,I/SurfaceFlinger(  245): id=20 Removed Uoast (12/13)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  751): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=751 (0x0)
,D/PowerManagerService(  751): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=751, ws=WorkSource{1000}) (elapsedTime=3544)
,I/GAV2    ( 5632): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5174): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5174): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5174): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5174): ================================================
,I/CSTORAGE( 5174):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5174): ================================================
,D/dalvikvm( 5174): No JNI_OnLoad found in /system/lib/libterrier.so 0x425682e0, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5174): [GetString-S]
,I/terrier ( 5174): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5174): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5174): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5174): Loaded image: APP id = 4
,D/QSEECOMAPI: ( 5174): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5174): QSEECom_shutdown_app, app_id = 4
,E/terrier ( 5174): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5174): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5174): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5174): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5174): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5174): [ensureRegistration] - No Samsung account
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :4
,V/AlarmManager(  751): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/BatteryService(  751): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3710): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3710): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 310, Delta = -10
,D/CaptivePortalTracker(  751): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  751): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  751): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  751): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  751): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  751): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  751): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  751): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4216): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4216): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4216): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4216): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4216): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4216): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 4216): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4216): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4216): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4216): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4216): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4216): entry::IDLE
,E/Watchdog(  751): !@Sync 4
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 288, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService(  751): [PWL] Off : 75s ago
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,D/Headlines( 4130): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4130): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4130): Breath 17880 latestRequest time : 1450238321727 current time : 1450238339607
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = -10
,E/SMD     (  239): DCD ON
,D/dalvikvm( 1782): GC_CONCURRENT freed 1609K, 35% free 12171K/18696K, paused 17ms+19ms, total 182ms
,D/AmoledAdjustTimer(  751): prevTemp = 292, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 290, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 5
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService(  751): [PWL] Off : 105s ago
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,D/Headlines( 4130): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4130): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4130): Breath 47869 latestRequest time : 1450238321727 current time : 1450238369596
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 6
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,D/Headlines( 4130): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4130): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4130): Breath 77869 latestRequest time : 1450238321727 current time : 1450238399599
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1935): Disconnected process message: 10
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  751): [PWL] Off : 140s ago
,I/PowerManagerService(  751): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  751): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  751): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=751, ws=WorkSource{1000}) (elapsedTime=106)
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 7
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,D/Headlines( 4130): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4130): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4130): Breath 107863 latestRequest time : 1450238321727 current time : 1450238429591
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  751): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 8
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,D/Headlines( 4130): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4130): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4130): Breath 137861 latestRequest time : 1450238321727 current time : 1450238459588
,D/Headlines( 4130): stop 
,D/Headlines( 4130): Breath.onDestroy : 
,I/ActivityManager(  751): Killing 4440:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): stay LED for fully charged
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  751): mCoverManager.getCoverState() : true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,I/jxcore-log( 5355): Connected to the server!
I/jxcore-log( 5355): 
,I/chromium( 5355): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 9
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService(  751): [PWL] Off : 225s ago
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/TimaService(  751): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  751): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  751): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  751): initializing...
,I/TLC_TIMA_PKM_initialize(  751): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  751): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  751): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  751): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  751): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  751): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  751): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  751): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  751): App is not loaded in QSEE
,D/QSEECOMAPI: (  751): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  751): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  751): Trustlet response is completed
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  751): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  751): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  751): !@Sync 10
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  751): [PWL] Off : 275s ago
,V/AlarmManager(  751): waitForAlarm result :4
,V/AlarmManager(  751): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,I/SELinux ( 5847): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5847):  
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/dalvikvm(  248): GC_EXPLICIT freed 43K, 50% free 9507K/18696K, paused 13ms+19ms, total 290ms
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9507K/18696K, paused 19ms+26ms, total 186ms
,I/SELinux ( 5847): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5847):  
I/SELinux ( 5847):  
,I/SELinux ( 5847): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5847): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5847): >>>>> Normal User
,E/dalvikvm( 5847): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5847): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9507K/18696K, paused 19ms+30ms, total 194ms
,D/TimaKeyStoreProvider( 5847): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5847): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5847): Added TimaKesytore provider
,W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=5847, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  751): Killing 4632:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 11
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 12
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  751): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 13
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 14
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  751): [PWL] Off : 390s ago
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  751): GC_CONCURRENT freed 3481K, 58% free 23854K/55724K, paused 23ms+51ms, total 544ms
,E/Watchdog(  751): !@Sync 15
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,E/SMD     (  239): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 16
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  751): [PWL] Off : 455s ago
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 17
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 18
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 19
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService(  751): [PWL] Off : 525s ago
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/TimaService(  751): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  751): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  751): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  751): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  751): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 20
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 21
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,I/SensorManagerA(  751): getReportingMode :: sensor.mType = 5
,D/LightsService(  751): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  751): LightSensor setDelay = 200000000
D/Sensors (  751): LightSensor setSensorDelay = 200000000
D/Sensors (  751): Light sensor flush: not enabled 0
D/Sensors (  751): LightSensor enable = 1
D/Sensors (  751): LightSensor enableSensor = 1
D/SensorManager(  751): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService(  751): [PWL] Off : 600s ago
,D/Sensors (  751): LightSensor enable = 0
,D/Sensors (  751): LightSensor enableSensor = 0
,D/SensorManager(  751): unregisterListener ::   
D/LightsService(  751): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  751): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/SMD     (  239): DCD ON
V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  751): !@Sync 22
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  751): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  751): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
V/AlarmManager(  751): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 23
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 24
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  751): [PWL] Off : 680s ago
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 25
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 26
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,W/ProcessCpuTracker(  751): Skipping unknown process pid 5966
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 27
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService(  751): [PWL] Off : 765s ago
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 28
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 29
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/TimaService(  751): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  751): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  751): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  751): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  751): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  751): !@Sync 30
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,I/PowerManagerService(  751): [PWL] Off : 855s ago
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  751): GC_CONCURRENT freed 3530K, 57% free 23826K/55176K, paused 24ms+43ms, total 518ms
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 31
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 32
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
V/AlarmManager(  751): waitForAlarm result :8
V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-13, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 33
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  751): [PWL] Off : 950s ago
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  751): !@Sync 34
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,E/SMD     (  239): DCD ON
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  751): mCoverManager.getCoverState() : true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  751): !@Sync 35
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  751): !@Sync 36
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  751): [PWL] Off : 1050s ago
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  751): !@Sync 37
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  751): !@Sync 38
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  751): !@Sync 39
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/TimaService(  751): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  751): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  751): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/SMD     (  239): DCD ON
D/TimaService(  751): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  751): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  751): !@Sync 40
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  751): [PWL] Off : 1155s ago
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  751): !@Sync 41
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,I/SensorManagerA(  751): getReportingMode :: sensor.mType = 5
,D/Sensors (  751): LightSensor setDelay = 200000000
,D/Sensors (  751): LightSensor setSensorDelay = 200000000
,D/Sensors (  751): Light sensor flush: not enabled 0
,D/Sensors (  751): LightSensor enable = 1
,D/LightsService(  751): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  751): LightSensor enableSensor = 1
D/SensorManager(  751): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  751): LightSensor enable = 0
,D/Sensors (  751): LightSensor enableSensor = 0
,D/LightsService(  751): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  751): unregisterListener ::   
D/LightsService(  751): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  751): !@Sync 42
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  751): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  751): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
V/AlarmManager(  751): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
E/Watchdog(  751): !@Sync 43
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  751): [PWL] Off : 1265s ago
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 44
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 45
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 46
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/dalvikvm(  751): GC_CONCURRENT freed 3506K, 57% free 23819K/54952K, paused 28ms+50ms, total 584ms
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 47
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,E/SMD     (  239): DCD ON
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  751): [PWL] Off : 1380s ago
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 48
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 49
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  751): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  751): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  751): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  751): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  751): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 50
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 51
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  751): [PWL] Off : 1500s ago
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 52
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 53
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 54
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,E/SMD     (  239): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 55
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/BatteryService(  751): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  751): [PWL] Off : 1625s ago
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 56
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 57
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 58
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 59
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/TimaService(  751): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  751): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  751): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  751): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  751): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  751): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 60
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  751): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  751): Prepared write state in 143ms
,I/ProcessStatsService(  751): Prepared write state in 131ms
,I/ProcessStatsService(  751): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-04-09.bin
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/dalvikvm(  751): GC_CONCURRENT freed 3473K, 57% free 23856K/54952K, paused 22ms+47ms, total 551ms
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,E/SMD     (  239): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 61
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,I/SensorManagerA(  751): getReportingMode :: sensor.mType = 5
,D/Sensors (  751): LightSensor setDelay = 200000000
,D/LightsService(  751): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  751): LightSensor setSensorDelay = 200000000
D/Sensors (  751): Light sensor flush: not enabled 0
D/Sensors (  751): LightSensor enable = 1
D/Sensors (  751): LightSensor enableSensor = 1
D/SensorManager(  751): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/ActivityManager(  751): Killing 4581:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1801s
,D/Sensors (  751): LightSensor enable = 0
,D/Sensors (  751): LightSensor enableSensor = 0
,D/LightsService(  751): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  751): unregisterListener ::   
D/LightsService(  751): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 62
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/BatteryService(  751): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  751): waitForAlarm result :8
,V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  751): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  751): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
V/AlarmManager(  751): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  751): !@Sync 63
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  751): stay LED for fully charged
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  751): mCoverManager.getCoverState() : true
,D/BatteryService(  751): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1935): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1935): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  239): DCD ON
E/SMD     (  239): DCD ON
E/Watchdog(  751): !@Sync 64
E/SMD     (  239): DCD ON
D/SSRMv2:SIOP(  751): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  751): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
E/SMD     (  239): DCD ON
V/AlarmManager(  751): waitForAlarm result :8
V/AlarmManager(  751): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
I/ActivityManager(  751): Killing 5484:com.vlingo.midas/u0a33 (adj 15): empty for 1818s
I/ActivityManager(  751): Killing 5552:com.samsung.klmsagent/u0a18 (adj 15): empty for 1818s
I/ActivityManager(  751): Killing 5534:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1818s
I/ActivityManager(  751): Killing 3981:com.sec.android.diagmonagent/1000 (adj 15): empty for 1818s
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
I/ActivityManager(  751): Killing 5517:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1818s
I/ActivityManager(  751): Killing 3928:com.google.android.music:main/u0a122 (adj 15): empty for 1818s
I/ActivityManager(  751): Killing 5174:com.sec.pcw.device/1000 (adj 15): empty for 1818s
I/ActivityManager(  751): Killing 1304:com.android.settings/1000 (adj 15): empty for 1818s
I/ActivityManager(  751): Killing 5700:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1818s
I/ActivityManager(  751): Killing 5400:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1827s
I/ActivityManager(  751): Killing 5381:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1827s
I/ActivityManager(  751): Killing 5343:com.samsung.helphub/1000 (adj 15): empty for 1827s
I/ActivityManager(  751): Killing 5328:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1827s
I/ActivityManager(  751): Killing 5307:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1828s
I/ActivityManager(  751): Killing 5276:com.google.android.apps.docs/u0a90 (adj 15): empty for 1828s
I/ActivityManager(  751): Killing 5261:com.sec.android.service.cm/u0a78 (adj 15): empty for 1828s
I/ActivityManager(  751): Killing 4710:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1828s
I/ActivityManager(  751): Killing 4362:com.android.mms/u0a48 (adj 15): empty for 1828s
I/ActivityManager(  751): Killing 5229:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1828s
I/ActivityManager(  751): Killing 4261:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1829s
I/ActivityManager(  751): Killing 5186:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1829s
I/ActivityManager(  751): Killing 5156:com.android.musicfx/u0a24 (adj 15): empty for 1829s
I/ActivityManager(  751): Killing 5143:com.samsung.groupcast/u0a15 (adj 15): empty for 1830s
I/ActivityManager(  751): Killing 5128:com.google.android.partnersetup/u0a14 (adj 15): empty for 1830s
I/ActivityManager(  751): Killing 5112:com.sec.android.inputmethod/1000 (adj 15): empty for 1830s
I/ActivityManager(  751): Killing 5070:com.android.defcontainer/u0a6 (adj 15): empty for 1830s
D/CountryDetector(  751): No listener is left
D/AndroidRuntime( 6207): 
D/AndroidRuntime( 6207): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6207): CheckJNI is OFF
D/AndroidRuntime( 6207): setted country_code = Poland
D/AndroidRuntime( 6207): setted countryiso_code = PL
D/AndroidRuntime( 6207): setted sales_code = XEO
D/AndroidRuntime( 6207): readGMSProperty: start
D/AndroidRuntime( 6207): readGMSProperty: already setted!!
D/AndroidRuntime( 6207): readGMSProperty: end
D/AndroidRuntime( 6207): addProductProperty: start
D/dalvikvm( 6207): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6207): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6207): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6207): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6207): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/SMD     (  239): DCD ON
E/memtrack( 6207): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6207): failed to load memtrack module: -2
D/dalvikvm( 6207): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6207): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  751): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  751): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  751): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  751): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  751): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  751): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  751): START PACKAGE DELETE: observer{1110240256}
D/PackageManager(  751): pkg{<packageName>}
D/PackageManager(  751): user{0}
D/PackageManager(  751): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManagerService(  751): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  751): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  751): getApplicationUninstallationEnabled
D/ApplicationPolicy(  751): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  751): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  751): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  751): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  751): Killing 5355:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/SurfaceFlinger(  245): id=18 Removed NainActivit (7/12)
I/SurfaceFlinger(  245): id=18 Removed NainActivit (-2/12)
I/SurfaceFlinger(  245): id=18 Removed NainActivit (-2/12)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/WindowState(  751): WIN DEATH: Window{42ec6878 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  751): Skipping PackageSetting{42c2ba30 com.example.hello/10181} due to missing metadata
D/PackageManager(  751): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1400): GC_EXPLICIT freed 4301K, 47% free 10025K/18696K, paused 6ms+4ms, total 73ms
D/AdaptiveEventManager( 1066): action=android.intent.action.PACKAGE_REMOVED
D/PackageManager(  751): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 1085): onReceive: android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3374): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/dalvikvm(  751): GC_EXPLICIT freed 1856K, 57% free 23793K/54952K, paused 7ms+15ms, total 152ms
I/SELinux ( 6254): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6254):  
I/InputReader(  751): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1217): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1782): GC_EXPLICIT freed 91K, 36% free 12105K/18696K, paused 3ms+5ms, total 183ms
D/dalvikvm( 2172): GC_EXPLICIT freed 1579K, 40% free 11222K/18696K, paused 4ms+4ms, total 134ms
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "sms"
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  751): PackageReceiver onReceive()
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "smsto"
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService(  751): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux ( 6254): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6254):  
I/SELinux ( 6254):  
I/SELinux ( 6254): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6254): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6254): >>>>> Normal User
E/dalvikvm( 6254): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6254): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6254): in addTimaSignatureService
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "mms"
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6254): Cannot add TimaSignature Service, License check Failed
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "mmsto"
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/ActivityThread( 6254): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "sms"
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "smsto"
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "mms"
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SurfaceFlinger(  245): id=21 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "mmsto"
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=6254, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 6254): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6254): ELMEngine.ELMEngine( context ).
D/elm:14132( 6254): MDMBridge.setEnterpriseBridge()
D/elm:14132( 6254): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6254): ElmAgentService : onCreate()
D/elm:14132( 6254): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6254): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6254): MDMBridge.getInstance()
D/EnterpriseDeviceManagerService(  751): Package has changed for user 0
D/EnterpriseDeviceManagerService(  751): Admin package name: com.google.android.gms
D/elm:14132( 6254): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6254): MDMBridge.getAllLicenseInfoFromSDK()
D/BackupManagerService(  751): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  751): removePackageParticipantsLocked: uid=10179 #1
I/SELinux ( 6270): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6270):  
D/elm:14132( 6254): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 6254): ElmAgentService : onDestroy().
I/ActivityManager(  751): Killing 5570:com.sec.android.soagent/u0a37 (adj 15): empty for 1820s
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6270): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6270):  
I/SELinux ( 6270):  
I/SELinux ( 6270): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6270): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6270): >>>>> Normal User
E/dalvikvm( 6270): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 6270): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  751): GC_EXPLICIT freed 1212K, 57% free 23851K/54952K, paused 7ms+20ms, total 280ms
D/PackageManager(  751): delete sourFile : 
D/TimaKeyStoreProvider( 6270): in addTimaSignatureService
D/TimaKeyStoreProvider( 6270): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6270): Added TimaKesytore provider
D/PackageManager(  751): delete native library directory: 
D/PackageManager(  751): return delete result to caller: 1110240256
D/AndroidRuntime( 6207): Shutting down VM
D/dalvikvm( 6207): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+1ms, total 3ms
D/PackageManager(  751): returnCode: 1
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "sms"
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "smsto"
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "mms"
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  751):   Action: "android.intent.action.SENDTO"
I/PackageManager(  751):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  751):   Scheme: "mmsto"
I/PackageManager(  751): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  751): Permission Denial: getCurrentUser() from pid=6270, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 6270): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42560c78, skipping init
I/SecureStorage( 6270): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6270): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  307): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6270
I/SecureStorage(  307): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6270): [INFO]: SPID(0x00000000)SS Daemon is running
D/Launcher( 1249): onRestart, Launcher: 1113618432
D/Launcher( 1249): onStart, Launcher: 1113618432
D/Launcher.HomeView( 1249): onStart
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 6270): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  307): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6270
I/SecureStorage(  307): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1443): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1443): [237392/5] SurfaceWidget drawing first frame
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SurfaceFlinger(  245): id=22 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  751): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  751): clearDefaults: com.test.thalitest
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/InputReader(  751): Processing first event
W/ApplicationsProvider( 1400): Could not fetch usage stats
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
