#### Test 50650278b44f053_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
D/TimaKeyStoreProvider( 5191): in addTimaSignatureService
D/TimaKeyStoreProvider( 5191): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5191): Added TimaKesytore provider
I/SELinux ( 5217): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5217):  
--------- beginning of /dev/log/system
I/ActivityManager(  723): Killing 3969:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  248): GC_EXPLICIT freed 45K, 51% free 9506K/19128K, paused 2ms+2ms, total 34ms
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19128K, paused 2ms+2ms, total 18ms
I/SELinux ( 5217): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5217):  
I/SELinux ( 5217):  
I/SELinux ( 5217): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5217): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5217): >>>>> Normal User
E/dalvikvm( 5217): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5217): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19128K, paused 1ms+3ms, total 20ms
D/TimaKeyStoreProvider( 5217): in addTimaSignatureService
D/TimaKeyStoreProvider( 5217): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5217): Added TimaKesytore provider
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5217, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5217): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ActivityManager(  723): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5217): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/SA      ( 4045): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4045): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4045): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4340): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2175): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4674): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5242): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5242):  
I/IcingCorporaProvider( 2175): UpdateCorporaTask done [took 73 ms] updated apps [took 73 ms] 
I/SELinux ( 5242): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5242):  
I/SELinux ( 5242):  
I/SELinux ( 5242): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/ActivityManager(  723): Killing 3981:com.samsung.klmsagent/u0a18 (adj 15): empty #43
E/SELinux ( 5242): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5242): >>>>> Normal User
E/dalvikvm( 5242): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5242): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5242): in addTimaSignatureService
D/TimaKeyStoreProvider( 5242): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5242): Added TimaKesytore provider
D/CapabilityManagerService New( 5242): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5242, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5255): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5255):  
I/ActivityManager(  723): Killing 4269:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5255): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5255):  
I/SELinux ( 5255):  
I/SELinux ( 5255): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5255): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5255): >>>>> Normal User
E/dalvikvm( 5255): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5255): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5255): in addTimaSignatureService
D/TimaKeyStoreProvider( 5255): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5255): Added TimaKesytore provider
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5255, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5277): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5277):  
I/SELinux ( 5277): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5277):  
I/SELinux ( 5277):  
I/SELinux ( 5277): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5277): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5277): >>>>> Normal User
E/dalvikvm( 5277): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5277): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager(  723): Killing 3994:com.sec.android.soagent/u0a37 (adj 15): empty #43
W/GAV2    ( 5255): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/AndroidRuntime( 5270): 
D/AndroidRuntime( 5270): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/TimaKeyStoreProvider( 5277): in addTimaSignatureService
D/AndroidRuntime( 5270): CheckJNI is OFF
D/AndroidRuntime( 5270): setted country_code = Poland
D/AndroidRuntime( 5270): setted countryiso_code = PL
D/AndroidRuntime( 5270): setted sales_code = XEO
D/AndroidRuntime( 5270): readGMSProperty: start
D/AndroidRuntime( 5270): readGMSProperty: already setted!!
D/AndroidRuntime( 5270): readGMSProperty: end
D/AndroidRuntime( 5270): addProductProperty: start
D/TimaKeyStoreProvider( 5277): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5277): Added TimaKesytore provider
D/dalvikvm( 5270): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5270): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5270): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5270): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5270): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/PackageIntentReceiver( 5277): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5277): Not GearManger package! 
I/SELinux ( 5307): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5307):  
I/SELinux ( 5307): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5307):  
I/SELinux ( 5307):  
I/SELinux ( 5307): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5307): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5307): >>>>> Normal User
E/dalvikvm( 5307): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5307): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5307): in addTimaSignatureService
D/TimaKeyStoreProvider( 5307): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5307): Added TimaKesytore provider
E/memtrack( 5270): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5270): failed to load memtrack module: -2
D/dalvikvm( 5270): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/MagazineService Version( 5307): Magazine-Channel: 13
D/MagazineService Version( 5307): Magazine-Provider: 13
D/MagazineService Version( 5307): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5307): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5307): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5307, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5307): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5320): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5320):  
D/MagazineService::MagazineService( 5307): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  723): Killing 4374:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
W/GAV2    ( 5255): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/AndroidRuntime( 5270): Calling main entry com.android.commands.am.Am
I/ActivityManager(  723): Killing 1338:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 5320): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5320):  
I/SELinux ( 5320):  
I/SELinux ( 5320): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5320): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5320): >>>>> Normal User
E/dalvikvm( 5320): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5320): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5320): in addTimaSignatureService
D/TimaKeyStoreProvider( 5320): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5320): Added TimaKesytore provider
V/ApplicationPolicy(  723): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  723): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  723): mDVFSHelper.acquire()
I/SELinux ( 5335): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5335):  
D/LockPatternUtils( 1065): isPcwEnable = null
D/AndroidRuntime( 5270): Shutting down VM
D/dalvikvm( 5270): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
I/SELinux ( 5335): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5335):  
I/SELinux ( 5335):  
I/SELinux ( 5335): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5335): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5335): >>>>> Normal User
E/dalvikvm( 5335): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5335): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5335): in addTimaSignatureService
D/TimaKeyStoreProvider( 5335): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5335): Added TimaKesytore provider
D/LockPatternUtils( 1065): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2098): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2098): getDatabaseLocked(b,b,pwd)...
I/SELinux ( 5350): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5350):  
I/SELinux ( 5350): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5350):  
I/SELinux ( 5350):  
I/SELinux ( 5350): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5350): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5350): >>>>> Normal User
E/dalvikvm( 5350): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 5350): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/SurfaceWidgetView( 1241): destroyHardwareResources():1126063752
I/ActivityManager(  723): Killing 4389:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 5350): in addTimaSignatureService
D/TimaKeyStoreProvider( 5350): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5350): Added TimaKesytore provider
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5335, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/SurfaceFlinger(  247): id=9 Removed Mauncher (7/11)
I/SurfaceFlinger(  247): id=9 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5335, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1441): [237392/5] Surface widget visibility changed visibility = false on instance = 1
,D/Launcher( 1241): onTrimMemory. Level: 20
,V/WebViewChromium( 5335): Binding Chromium to the background looper Looper (main, tid 1) {422ba5e8}
,I/chromium( 5335): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5335): Initializing chromium process, renderers=0
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5350, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
W/chromium( 5335): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5335): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5335): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5335): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5335): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5335): Remote Branch: 
I/Adreno-EGL( 5335): Local Patches: 
I/Adreno-EGL( 5335): Reconstruct Branch: 
,D/KidsPlatformStub( 5350): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5374): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5374):  
I/ActivityManager(  723): Killing 4401:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5374): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5374):  
I/SELinux ( 5374):  
,I/SELinux ( 5374): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5374): >>>>> Normal User
,E/dalvikvm( 5374): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5374): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5374): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5374): Added TimaKesytore provider
,I/dalvikvm( 5335): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5335): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5335): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5335): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5335): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5335): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5335): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5335): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5335): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5335): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5335): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5335): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5335): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5335): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 5335): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5335): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5335): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5335): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5335): CordovaWebView is running on device made by: samsung
,I/ActivityManager(  723): Killing 3582:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/dalvikvm( 3675): GC_FOR_ALLOC freed 1779K, 19% free 15926K/19556K, paused 61ms, total 61ms
,I/SurfaceFlinger(  247): id=17 createSurf (1x1),1 flag=404, NainActivit
,D/Finsky  ( 3675): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5335): EGLImpl-HWUI Protected EGL context created
,D/PackageBroadcastService( 1753): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1753): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1753): Loading module APK com.google.android.play.games
I/dalvikvm( 1753): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1753): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1753): VFY: replacing opcode 0x6e at 0x0053
,D/OpenGLRenderer( 5335): Enabling debug mode 0
,W/AwContents( 5335): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  723): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  723): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  723): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  pkgName : ACTIVITY_RESUME_BOOSTER@9
,I/dalvikvm( 1753): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1753): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1753): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1753): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1753): VFY: replacing opcode 0x22 at 0x001a
,D/AmoledAdjustTimer(  723): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
I/dalvikvm( 1753): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1753): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1753): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1753): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1753): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1753): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1753): Submit a task: k
,D/ChimeraCfgMgr( 1753): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1753): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1753): Processing package: com.test.thalitest
,W/BaseAppContext( 1753): Using Auth Proxy for data requests.
,W/BaseAppContext( 1753): Using Auth Proxy for data requests.
,D/GassUtils( 1753): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1753): Found info for package com.test.thalitest in db.
,D/JsMessageQueue( 5335): Set native->JS mode to OnlineEventsBridgeMode
,W/BaseAppContext( 1753): Using Auth Proxy for data requests.
,W/BaseAppContext( 1753): Using Auth Proxy for data requests.
W/BaseAppContext( 1753): Using Auth Proxy for data requests.
,W/BaseAppContext( 1753): Using Auth Proxy for data requests.
,W/BaseAppContext( 1753): Using Auth Proxy for data requests.
,E/SMD     (  241): DCD ON
,D/dalvikvm( 5335): Trying to load lib /data/app-lib/com.test.thalitest-54/libjxcore.so 0x425e1358
,W/dalvikvm( 1753): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1753): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1753): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1753): VFY: replacing opcode 0x6e at 0x000e
D/dalvikvm( 5335): Added shared lib /data/app-lib/com.test.thalitest-54/libjxcore.so 0x425e1358
D/jxcore_app_log( 5335): JniHelper::setJavaVM(0x416f9528), pthread_self() = 2032425104
,D/JX-Cordova( 5335): jxcore cordova android initializing
,W/dalvikvm( 1753): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1753): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1753): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1753): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1753): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1753): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1753): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1753): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1753): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1753): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1753): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1753): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1753): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1753): cleanUpNonGplusAccounts done.
,W/dalvikvm( 1753): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1753): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1753): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5335): GC_CONCURRENT freed 4928K, 34% free 12758K/19128K, paused 3ms+2ms, total 32ms
,D/dalvikvm( 5335): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 5335): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/CustomFrequencyManagerService(  723): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  tag : ACTIVITY_RESUME_BOOSTER@9
,V/AlarmManager(  723): waitForAlarm result :4
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 67285 latestRequest time : 1450287733220 current time : 1450287800505
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): stay LED for fully charged
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  723): mCoverManager.getCoverState() : true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5335): GC_FOR_ALLOC freed 4719K, 29% free 15761K/21940K, paused 34ms, total 38ms
,I/VacuumService( 1216): Vacuum at: now=1450287800710 tag=VacuumService
,D/dalvikvm( 1753): GC_CONCURRENT freed 1898K, 37% free 12187K/19128K, paused 9ms+16ms, total 85ms
,I/Icing   ( 1753): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/FactoryTest( 4740): Not factory mode
D/FactoryTest( 4740): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4740): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4740): still no open session command from host, so toast
,V/ApplicationPolicy(  723): isApplicationStateBlocked userId 0 pkgname com.android.settings
W/ContextImpl( 4740): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4740): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
D/CustomFrequencyManagerService(  723): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  723): mDVFSHelper.acquire()
,D/LockPatternUtils( 1065): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2098): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2098): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1065): isPcwEnable = null
,E/MTPRx   ( 4740): started activity for popup
,E/SettingsReceiverActivity( 4740): PREF_DONT_ASK_AGAIN : false
,I/Icing   ( 1753): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/SettingsReceiverActivity( 4740): dev.kiessupport is : TRUE
,I/SurfaceFlinger(  247): id=18 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4740): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4740): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4740): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4740): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4740): Remote Branch: 
I/Adreno-EGL( 4740): Local Patches: 
I/Adreno-EGL( 4740): Reconstruct Branch: 
,I/HWUI    ( 4740): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4740): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  723): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  723): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  pkgName : ACTIVITY_RESUME_BOOSTER@9
,W/ActivityManager(  723): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/dalvikvm(  723): GC_EXPLICIT freed 2844K, 58% free 23851K/56040K, paused 15ms+16ms, total 192ms
,D/dalvikvm( 5335): GC_FOR_ALLOC freed 5101K, 32% free 16774K/24628K, paused 36ms, total 41ms
,I/dalvikvm-heap( 5335): Grow heap (frag case) to 22.147MB for 2475476-byte allocation
,D/dalvikvm( 1317): GC_EXPLICIT freed 1838K, 44% free 10808K/19128K, paused 5ms+5ms, total 48ms
,I/PhenotypeConfigurator( 1216): Scheduling Phenotype for one-off execution 7590 seconds from now (1450287801812)
,D/GetConfigurationSnapshotOperation( 1216): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1216): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1216): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1216): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1216): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  723): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 5335): GC_FOR_ALLOC freed 3779K, 36% free 17460K/27048K, paused 40ms, total 43ms
,I/dalvikvm( 1216): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1216): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1216): Thread-107(HTTPLog):isShipBuild true
,I/System.out( 1216): Thread-107(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 5335): GC_FOR_ALLOC freed 1242K, 36% free 17363K/27048K, paused 30ms, total 32ms
,D/dalvikvm( 1216): GC_CONCURRENT freed 1498K, 38% free 11934K/19128K, paused 4ms+9ms, total 66ms
,W/jxcore-log( 5335): Initializing JXcore engine
W/jxcore-log( 5335): JXcore engine is ready
W/jxcore-log( 5335): Starting JXcore engine
D/CustomFrequencyManagerService(  723): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  tag : ACTIVITY_RESUME_BOOSTER@9
W/jxcore-log( 5335): Platform android
W/jxcore-log( 5335): 
W/jxcore-log( 5335): Process ARCH arm
W/jxcore-log( 5335): 
E/SMD     (  241): DCD ON
,I/GAV2    ( 5255): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 5335): JXcore Cordova bridge is ready!
I/jxcore-log( 5335): 
,W/jxcore-log( 5335): JXcore engine is started
,I/chromium( 5335): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SSRMv2:SIOP(  723): SIOP:: AP = 320, Delta = 10
,I/jxcore-log( 5335): Toggling radios to true
I/jxcore-log( 5335): 
,D/BluetoothAdapter( 5335): enable(): BT is already enabled..!
,I/WifiManager( 5335): packageName : com.test.thalitest
,I/WifiManager( 5335): setWifiEnabled : true
,I/WifiService(  723): setWifiEnabled: true pid=5335, uid=10179
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5335, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  723): Failed getting userId using ActivityManagerNative
W/WifiService(  723): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5335, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  723): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  723): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  723): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  723): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  723): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  723): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  723): disconnect: pid=5335, uid=10179
,I/jxcore-log( 5335): Radios toggled
I/jxcore-log( 5335): 
,I/wpa_supplicant( 1979): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5335): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5335): 
,I/jxcore-log( 5335): Perf Test app loaded loaded
I/jxcore-log( 5335): 
,I/jxcore-log( 5335): check test folder
I/jxcore-log( 5335): 
,I/jxcore-log( 5335): found test : ./testFindPeers.js
I/jxcore-log( 5335): 
,I/wpa_supplicant( 1979): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1979): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1979): Cmd 35605 not handled
E/wpa_supplicant( 1979): Cmd 35605 not handled
,I/wpa_supplicant( 1979): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/Tethering(  723): InitialState.processMessage what=4
,E/Tethering(  723): No numeric data
D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
I/wpa_supplicant( 1979): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1979): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1979): First Scan Start
,I/wpa_supplicant( 1979): Scan requested (ret=0) - scan timeout 30 seconds
,D/Tethering(  723): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
I/ConnectivityService(  723): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  723): performPollLocked(flags=0x1)
W/Settings(  723): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  723): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService(  723): InactiveState{ what=143375 }
D/WifiP2pService(  723): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,I/jxcore-log( 5335): found test : ./testSendData.js
I/jxcore-log( 5335): 
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,I/WifiTrafficPoller(  723): evaluateTrafficStatsPolling
V/NetworkStats(  723): performPollLocked() took 38ms
D/ConnectivityService(  723): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  723): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  723): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  723): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  723): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  723): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837977 act=2130837934
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
D/ConnectivityService(  723): Attempting to switch to mobile
D/ConnectivityService(  723): Attempting to switch to BLUETOOTH_TETHER
,I/wpa_supplicant( 1979): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1979): Skip scan - already scanning
,I/SELinux ( 5461): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5461):  
D/STATUSBAR-IconMerger( 1065): checkOverflow(336), More:false, Req:false Child:2
,V/RouteController(  238): /system/bin/ip -6 route del default table 2 2>&1
D/WifiP2pService(  723): InactiveState{ what=143375 }
D/WifiP2pService(  723): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5461): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5461):  
I/SELinux ( 5461):  
,I/SELinux ( 5461): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5461): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5461): >>>>> Normal User
,E/dalvikvm( 5461): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5461): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,D/TimaKeyStoreProvider( 5461): in addTimaSignatureService
,W/NetworkManagementService(  723): route cmd failed: 
W/NetworkManagementService(  723): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  723): '
W/NetworkManagementService(  723): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  723): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  723): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  723): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  723): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  723): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  723): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  723): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  723): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  723): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  723): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  723): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  723): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  238): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller(  723): evaluateTrafficStatsPolling
,E/WifiStateMachine(  723): Error! unhandled message{ when=-105ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/TimaKeyStoreProvider( 5461): Cannot add TimaSignature Service, License check Failed
,E/WifiStateMachine(  723): Error! unhandled message{ when=-107ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  238): RTNETLINK answers: No such process
,D/ActivityThread( 5461): Added TimaKesytore provider
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,E/WifiStateMachine(  723): Error! unhandled message{ when=-7ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  723): android_net_utils_resetConnections in env=0x77d35120 clazz=0x6a500001 iface=wlan0 mask=0x3
,I/chromium( 5335): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  723): resetConnections(wlan0, 3)
V/NativeCrypto( 1317): Read error: ssl=0x7bfa7b70: I/O error during system call, Connection timed out
V/NativeCrypto( 1317): SSL shutdown failed: ssl=0x7bfa7b70: I/O error during system call, Broken pipe
,I/System.out( 5461): Inside WakeupProvider
,I/System.out( 5461): Inside onCreate() of WakeupTriggerProvide
,V/NetworkStats(  723): updateIfacesLocked()
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
V/NetworkStats(  723): performPollLocked(flags=0x1)
D/ConnectivityService(  723): handleInetConditionChange: no active default network - ignore
V/NetworkStats(  723): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,I/VlingoApplication( 5461): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5461): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5461): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
V/NetworkStats(  723): performPollLocked() took 15ms
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5461): initQueue()
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  723): Killing 4428:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,I/ApplicationPolicy(  723): updateDataUsageMap
,D/Tethering(  723): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  723): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  723): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  723): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
D/LocSvc_java(  723): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  723): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  723): ignore wifi update if we are not in OPENING or CLOSING
,I/PCWCLIENTTRACE_PushUtil( 5162): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5162): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5162): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5162): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5162): noConnectivity : true
,D/accuweather( 1441): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SELinux ( 5496): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5496):  
,I/SELinux ( 5496): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5496):  
I/SELinux ( 5496):  
,I/SELinux ( 5496): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5496): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5496): >>>>> Normal User
,E/dalvikvm( 5496): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5496): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5496): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5496): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5496): Added TimaKesytore provider
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5496, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  723): Killing 4442:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/SELinux ( 5519): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5519):  
,D/dalvikvm(  248): GC_EXPLICIT freed 43K, 51% free 9506K/19128K, paused 2ms+3ms, total 25ms
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19128K, paused 2ms+3ms, total 18ms
,I/SELinux ( 5519): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5519):  
I/SELinux ( 5519):  
,I/SELinux ( 5519): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5519): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 5519): >>>>> Normal User
,E/dalvikvm( 5519): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5519): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19128K, paused 1ms+2ms, total 20ms
,D/TimaKeyStoreProvider( 5519): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5519): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5519): Added TimaKesytore provider
,I/wpa_supplicant( 1979): nl80211: Received scan results (13 BSSes)
I/wpa_supplicant( 1979): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1979): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1979): Trying to associate with  'G700'
I/wpa_supplicant( 1979): Re-associate with C0.AA.48
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
,E/wpa_supplicant( 1979): Cmd 35609 not handled
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5519, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,E/wpa_supplicant( 1979): Cmd 35605 not handled
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1979): Associated with C0.AA.48
I/wpa_supplicant( 1979): freq(2412) increment count 2
I/wpa_supplicant( 1979): meet head of list.
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1979): Cmd 35847 not handled
D/Tethering(  723): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1979): Cmd 35848 not handled
,E/wpa_supplicant( 1979): Cmd 35605 not handled
,D/Tethering(  723): interfaceStatusChanged wlan0, false
,D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
D/Tethering(  723): interfaceLinkStateChanged wlan0, true
,D/Tethering(  723): interfaceStatusChanged wlan0, true
D/Tethering(  723): interfaceLinkStateChanged wlan0, true
,D/Tethering(  723): interfaceStatusChanged wlan0, true
E/Tethering(  723): No numeric data
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  723): sendTetherStateChangedBroadcast 1, 0, 0
I/wpa_supplicant( 1979): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1979): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
D/Tethering(  723): interfaceLinkStateChanged wlan0, true
,D/Tethering(  723): interfaceStatusChanged wlan0, true
,D/WifiNative(  723): callSECApiVoid - ID [50]
I/ConnectivityService(  723): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  723): performPollLocked(flags=0x1)
D/Tethering(  723): interfaceLinkStateChanged wlan0, true
,D/Tethering(  723): interfaceStatusChanged wlan0, true
I/ActivityManager(  723): Killing 4466:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/Tethering(  723): interfaceLinkStateChanged wlan0, true
,D/Tethering(  723): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
V/NetworkStats(  723): performPollLocked() took 25ms
,I/SELinux ( 5533): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5533):  
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
D/WifiP2pService(  723): InactiveState{ what=143375 }
D/WifiP2pService(  723): P2pEnabledState{ what=143375 }
,I/SELinux ( 5533): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5533):  
I/SELinux ( 5533):  
,I/SELinux ( 5533): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5533): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5533): >>>>> Normal User
,E/dalvikvm( 5533): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5533): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5533): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5533): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5533): Added TimaKesytore provider
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5533, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5533): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5533): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450287806758
,I/KLMS-2.3.201 : ( 5533): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager(  723): Killing 4485:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5545): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5545):  
,I/SELinux ( 5545): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5545):  
I/SELinux ( 5545):  
,I/SELinux ( 5545): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5545): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5545): >>>>> Normal User
,E/dalvikvm( 5545): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5545): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5545): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5545): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5545): Added TimaKesytore provider
,D/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5545, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/dhcpcd  ( 5549): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5549): bssid match
,I/SA      ( 4045): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4045): [BDLM] already registered in spp
,I/SA      ( 4045): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4045): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4045): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4045): [OR] == isSIMCardReady false ==
I/SA      ( 4045): [SCU] == networkStateCheck == false
,I/SA      ( 4045): [OR] onReceive END
I/ActivityManager(  723): Killing 4610:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): Phone number locator feature is dsiabled
,I/SELinux ( 5564): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5564):  
,I/SELinux ( 5564): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5564):  
I/SELinux ( 5564):  
,I/SELinux ( 5564): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5564): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5564): >>>>> Normal User
,E/dalvikvm( 5564): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5564): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5564): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5564): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5564): Added TimaKesytore provider
,I/sCloudBackupApp( 5564): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5564): Other Intent
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/ActivityManager(  723): Killing 4625:com.sec.android.app.voicenote/1000 (adj 15): empty #43
D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5577): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5577):  
,I/SELinux ( 5577): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5577):  
I/SELinux ( 5577):  
,I/SELinux ( 5577): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5577): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5577): >>>>> Normal User
,E/dalvikvm( 5577): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5577): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5577): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5577): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5577): Added TimaKesytore provider
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5577, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  723): Killing 4638:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/Headlines( 4096): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4096): getCountryCode(): countryCode = PL
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4096): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 4096): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4096): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5593): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5593):  
,I/SELinux ( 5593): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5593):  
I/SELinux ( 5593):  
,I/SELinux ( 5593): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5593): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5593): >>>>> Normal User
,E/dalvikvm( 5593): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5593): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5593): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5593): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5593): Added TimaKesytore provider
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5593): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5593): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 5593): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    (  228): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5593): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5593): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 5593): Binding Chromium to the main looper Looper (main, tid 1) {422b8f58}
,I/chromium( 5593): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5593): Initializing chromium process, renderers=0
,I/Adreno-EGL( 5593): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5593): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5593): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5593): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5593): Remote Branch: 
I/Adreno-EGL( 5593): Local Patches: 
I/Adreno-EGL( 5593): Reconstruct Branch: 
,W/chromium( 5593): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/NSApplication( 5593): Starting up...
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5593, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  723): Killing 4693:com.google.android.talk/u0a105 (adj 15): empty #43
D/QuickConnect[1.1][2] ( 3354): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3354): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3354): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425eb2a8
,I/SELinux ( 5633): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5633):  
,I/SELinux ( 5633): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5633):  
I/SELinux ( 5633):  
,I/SELinux ( 5633): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5633): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5633): >>>>> Normal User
,E/dalvikvm( 5633): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5633): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5633): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5633): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5633): Added TimaKesytore provider
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
,I/SELinux ( 5652): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5652):  
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
W/ActivityManager(  723): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager(  723): Killing 3024:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,I/SELinux ( 5656): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5656):  
,I/SELinux ( 5652): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5652):  
I/SELinux ( 5652):  
,I/SELinux ( 5652): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5652): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5652): >>>>> Normal User
,E/dalvikvm( 5652): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5652): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5652): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5652): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5652): Added TimaKesytore provider
I/SELinux ( 5656): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5656):  
I/SELinux ( 5656):  
,I/SELinux ( 5656): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5656): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5656): >>>>> Normal User
,E/dalvikvm( 5656): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5656): [DEBUG] seapp_context_lookup: seinfoCategory = shared
I/ActivityManager(  723): Killing 4774:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5656): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5656): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5656): Added TimaKesytore provider
,D/BadgeProvider( 5652): onCreate
,D/BadgeProvider( 5652): DatabaseHelper
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5652, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5652): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5652): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5652): sendNotify, [notify] : null
,D/Launcher.Model( 1241): reloadBadges entered.
D/BadgeProvider( 5652): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5652): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5652): update, [UpdateCount] : 1
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5656, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  723): Killing 4795:com.wssyncmldm/1000 (adj 15): empty #43
,I/iu.Environment( 1753): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1753): num queued entries: 0
,I/iu.UploadsManager( 1753): num updated entries: 0
,I/iu.SyncManager( 1753): NEXT; no task
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService(  723): InactiveState{ what=143375 }
,D/WifiP2pService(  723): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  723): VerifyingLinkState enter
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
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  723): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  723): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  723): evaluateTrafficStatsPolling
,D/WifiStateMachine(  723): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  723): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  723): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  723): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  723): mBoosterFLAG : 2
,I/WifiTrafficPoller(  723): current booster mode : BTCoexMode
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService(  723): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  723): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  723): net.tcp.delack.wifi not found in system properties. Using defaults
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1065): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  723): handleConnectivityChange: setting default proxy info 
,V/RouteController(  238): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,D/Toast   ( 1302):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1302): showing allowed
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,V/RouteController(  238): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,I/SurfaceFlinger(  247): id=19 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,V/RouteController(  238): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/PowerManagerService(  723): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=723
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
V/RouteController(  238): RTNETLINK answers: No such process
V/RouteController(  238): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,V/NetworkStats(  723): updateIfacesLocked()
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
V/NetworkStats(  723): performPollLocked(flags=0x1)
,V/NetworkStats(  723): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
V/NetworkStats(  723): performPollLocked() took 18ms
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,E/SMD     (  241): DCD ON
,D/Tethering(  723): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  723): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  723): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/LocSvc_java(  723): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  723): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  723): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1441): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=true
I/PCWCLIENTTRACE_PushUtil( 5162): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5162): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5162): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5162): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.3.201 : ( 5533): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5533): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450287809377
,I/KLMS-2.3.201 : ( 5533): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2560): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2560): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2560): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2560): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2340): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5740): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5740):  
,I/SELinux ( 5740): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5740):  
I/SELinux ( 5740):  
I/SELinux ( 5740): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5740): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5740): >>>>> Normal User
,E/dalvikvm( 5740): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
I/SELinux ( 5744): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5744):  
,E/SELinux ( 5740): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/AmoledAdjustTimer(  723): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaKeyStoreProvider( 5740): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5740): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5740): Added TimaKesytore provider
,I/SA      ( 4045): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4045): [BDLM] already registered in spp
,I/SA      ( 4045): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4045): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4045): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4045): [OR] == isSIMCardReady false ==
,I/SA      ( 4045): [SCU] == networkStateCheck == true
I/SA      ( 4045): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4045): isChinaCountryCode : false
I/SA      ( 4045): [OR] == networkStateCheck true ==
,I/SA      ( 4045): [OR] GetMyCountryZoneTask
,I/SA      ( 4045): [OR] onReceive END
,I/SELinux ( 5744): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5744):  
I/SELinux ( 5744):  
,I/SELinux ( 5744): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5744): >>>>> Normal User
,E/dalvikvm( 5744): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): Phone number locator feature is dsiabled
,I/SA      ( 4045): [SRS] prepareGetMyCountryZone
,I/SCloudBackupReceiver( 5564): Other Intent
,D/TimaKeyStoreProvider( 5744): in addTimaSignatureService
,I/SA      ( 4045): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/TimaKeyStoreProvider( 5744): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5744): Added TimaKesytore provider
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      ( 4045): [SSP] query invoked
,I/SA      ( 4045): [TPMU] GetMccFromDB : null
I/SA      ( 4045): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4045): [TPM] isNoProxy(default) : true
,I/SA      ( 4045): [RC New] Execute method=[GET] start
,D/Headlines( 4096): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4096): getCountryCode(): countryCode = PL
,D/dalvikvm(  723): GC_EXPLICIT freed 2654K, 58% free 23750K/56040K, paused 7ms+13ms, total 147ms
,V/KVNProvider( 5744): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5744): getFindoCursor query string : 
D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4096): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 4096): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4096): requestUpdateNewsWelcomeCard !!! no welcome card
,V/KVNProvider( 5744): getTagSearchCursor() tagSearchCursor count : 0
,D/QuickConnect[1.1][2] ( 3354): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3354): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3354): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425eb2a8
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
I/ActivityManager(  723): Killing 4650:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/WaitQueueForNetworkActivate( 4192): notifyNetworkActivated
,D/hcjo    ( 4192): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4192): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4192): exit::IDLE
,D/InitializeManagerStateMachine( 4192): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4192): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4192): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4192): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4192): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4192): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4192): entry::SUCCESS
,D/hcjo    ( 4192): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4192): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4192): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4192): exit::SUCCESS
,D/InitializeManagerStateMachine( 4192): entry::IDLE
,I/HarmonyEASService(  723): Updating for all 1
,I/iu.Environment( 1753): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1753): num queued entries: 0
,I/iu.UploadsManager( 1753): num updated entries: 0
,I/iu.SyncManager( 1753): NEXT; no task
,W/WifiP2pStateTracker(  723): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  723): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  723):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
D/ConnectivityService(  723): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  723): updateSourceRoutes : no source routing conditions
,I/SA      ( 4045): [RC New] [v2liruge] api execute + 641
,I/SA      ( 4045): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4045): AsyncTask #2 calls detatch()
,I/SA      ( 4045): [TPMU] getNetworkMcc : 
,I/SA      ( 4045): [SCU] saveMccToPreferece Start
,I/SA      ( 4045): [SCU] RegionMCC : 260
,I/SA      ( 4045): [SSP] query invoked
,I/SA      ( 4045): [TPMU] GetMccFromDB : null
I/SA      ( 4045): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4045): [SCU] saveMccToPreferece End
,I/SA      ( 4045): [RC New] executeRequest [v2liruge] end. 660
I/SA      ( 4045): [RC New] Execute end
,I/SA      ( 4045): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4045): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 5335): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5335): 
,D/ConnectivityService(  723): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  241): DCD ON
,E/WifiStateMachine(  723): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  247): id=19 Removed Uoast (12/13)
,I/SurfaceFlinger(  247): id=19 Removed Uoast (-2/13)
I/ActivityManager(  723): Killing 4214:com.android.calendar/u0a142 (adj 15): empty #43
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  723): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=723 (0x0)
,D/PowerManagerService(  723): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=723, ws=WorkSource{1000}) (elapsedTime=3527)
,I/GAV2    ( 5593): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5162): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5162): [hasSamungAccount] - No Samsung Account
,V/AlarmManager(  723): waitForAlarm result :4
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/linker  ( 5162): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/SSRMv2:SIOP(  723): SIOP:: AP = 310, Delta = -10
,I/CSTORAGE( 5162): ================================================
,I/CSTORAGE( 5162):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5162): ================================================
D/dalvikvm( 5162): No JNI_OnLoad found in /system/lib/libterrier.so 0x425e52e0, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5162): [GetString-S]
I/terrier ( 5162): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 5162): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5162): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5162): Loaded image: APP id = 4
,D/QSEECOMAPI: ( 5162): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5162): QSEECom_shutdown_app, app_id = 4
,E/terrier ( 5162): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5162): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5162): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5162): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5162): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5162): [ensureRegistration] - No Samsung account
,D/Finsky  ( 3675): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3675): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/Watchdog(  723): !@Sync 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 75s ago
,D/CaptivePortalTracker(  723): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  723): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  723): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  723): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  723): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  723): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  723): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  723): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AmoledAdjustTimer(  723): prevTemp = 289, currTemp = 294, prevStep = 4, currStep = 4
,D/PreloadUpdateManagerStateMachine( 4192): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4192): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4192): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4192): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4192): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4192): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4192): entry::IDLE
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 13517 latestRequest time : 1450287809749 current time : 1450287823266
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = -10
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 294, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 292, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 5
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 105s ago
,D/AmoledAdjustTimer(  723): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  723): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 43511 latestRequest time : 1450287809749 current time : 1450287853260
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 6
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 73510 latestRequest time : 1450287809749 current time : 1450287883260
,I/PowerManagerService(  723): [PWL] Off : 140s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 7
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  723): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 103527 latestRequest time : 1450287809749 current time : 1450287913277
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 180s ago
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 8
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 133510 latestRequest time : 1450287809749 current time : 1450287943259
,D/Headlines( 4096): stop 
,D/Headlines( 4096): Breath.onDestroy : 
,I/ActivityManager(  723): Killing 4416:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  723): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 9
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  723): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  723): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/TimaService(  723): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  723): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  723): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  723): initializing...
,I/TLC_TIMA_PKM_initialize(  723): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  723): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  723): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  723): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  723): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  723): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  723): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  723): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  723): App is not loaded in QSEE
,D/QSEECOMAPI: (  723): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  723): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  723): Trustlet response is completed
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 5335): Connected to the server!
I/jxcore-log( 5335): 
,I/chromium( 5335): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  723): stay LED for fully charged
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 10
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 275s ago
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :4
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,I/SELinux ( 5863): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5863):  
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/dalvikvm(  248): GC_EXPLICIT freed 43K, 51% free 9506K/19128K, paused 29ms+27ms, total 287ms
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19128K, paused 19ms+40ms, total 225ms
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,I/SELinux ( 5863): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5863):  
I/SELinux ( 5863):  
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 5863): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5863): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5863): >>>>> Normal User
,E/dalvikvm( 5863): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5863): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 51% free 9506K/19128K, paused 34ms+27ms, total 233ms
,D/TimaKeyStoreProvider( 5863): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5863): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5863): Added TimaKesytore provider
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5863, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  723): Killing 4598:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 11
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/jxcore-log( 5335): --- start :testFindPeers.js---
I/jxcore-log( 5335): 
,E/SMD     (  241): DCD ON
,I/jxcore-log( 5335): testFindPeers created [object Object]
I/jxcore-log( 5335): 
,I/jxcore-log( 5335): serverPort is 8876
I/jxcore-log( 5335): 
,I/dalvikvm( 5335): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5335): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5335): VFY: replacing opcode 0x6e at 0x0019
I/dalvikvm( 5335): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5335): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5335): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 5335): Shutting down VM
,W/dalvikvm( 5335): threadid=1: thread exiting with uncaught exception (group=0x41808da0)
,E/AndroidRuntime( 5335): FATAL EXCEPTION: main
E/AndroidRuntime( 5335): Process: com.test.thalitest, PID: 5335
E/AndroidRuntime( 5335): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 5335): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 5335): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 5335): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 5335): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 5335): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 5335): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 5335): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 5335): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 5335): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 5335): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5335): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5335): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5335): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 5335): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5335): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 5335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 5335): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 5335): Sending signal. PID: 5335 SIG: 9
,D/CrashAnrDetector(  723): processName: com.test.thalitest
,D/CrashAnrDetector(  723): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 ,
,I/ActivityManager(  723): Process com.test.thalitest (pid 5335) (adj 1) has died.
,I/WindowState(  723): WIN DEATH: Window{44296148 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  247): id=17 Removed NainActivit (7/12)
,I/SurfaceFlinger(  247): id=17 Removed NainActivit (-2/12)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 5906): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5906):  
,I/SELinux ( 5906): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5906):  
I/SELinux ( 5906):  
,I/SELinux ( 5906): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5906): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5906): >>>>> Normal User
,E/dalvikvm( 5906): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
,E/SELinux ( 5906): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5906): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5906): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5906): Added TimaKesytore provider
,D/InputDispatcher(  723): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  247): id=20 createSurf (720x1280),2 flag=404, TcreenshotS
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (239 us)
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5906, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5906, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,V/WebViewChromium( 5906): Binding Chromium to the background looper Looper (main, tid 1) {422b5388}
,I/chromium( 5906): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5906): Initializing chromium process, renderers=0
,W/chromium( 5906): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5906): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5906): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5906): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5906): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5906): Remote Branch: 
I/Adreno-EGL( 5906): Local Patches: 
I/Adreno-EGL( 5906): Reconstruct Branch: 
,I/dalvikvm( 5906): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 5906): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5906): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5906): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5906): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5906): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5906): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 5906): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5906): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5906): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5906): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5906): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,I/dalvikvm( 5906): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5906): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 5906): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5906): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5906): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5906): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5906): CordovaWebView is running on device made by: samsung
,I/SurfaceFlinger(  247): id=21 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5906): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 5906): Enabling debug mode 0
,W/AwContents( 5906): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/WindowManager(  723): Screen frozen for +482ms due to Window{430b6b70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  247): id=22 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  247): id=23 createSurf (720x2560),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  247): id=24 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  247): id=25 createSurf (720x2560),-1 flag=20004, ClackSurfac
,D/InputDispatcher(  723): setInputDispatchMode: enabled=0, frozen=0
,I/SurfaceFlinger(  247): id=20 Removed TcreenshotS (12/17)
,I/SurfaceFlinger(  247): id=20 Removed TcreenshotS (-2/17)
I/SurfaceFlinger(  247): id=22 Removed ClackSurfac (12/16)
I/SurfaceFlinger(  247): id=22 Removed ClackSurfac (-2/16)
,I/SurfaceFlinger(  247): id=23 Removed ClackSurfac (12/15)
,I/SurfaceFlinger(  247): id=23 Removed ClackSurfac (-2/15)
I/SurfaceFlinger(  247): id=24 Removed ClackSurfac (12/14)
I/SurfaceFlinger(  247): id=24 Removed ClackSurfac (-2/14)
I/SurfaceFlinger(  247): id=25 Removed ClackSurfac (12/13)
,I/SurfaceFlinger(  247): id=25 Removed ClackSurfac (-2/13)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,V/WindowManager(  723): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/JsMessageQueue( 5906): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 5906): Trying to load lib /data/app-lib/com.test.thalitest-54/libjxcore.so 0x425dc120
,D/dalvikvm( 5906): Added shared lib /data/app-lib/com.test.thalitest-54/libjxcore.so 0x425dc120
,D/jxcore_app_log( 5906): JniHelper::setJavaVM(0x416f9528), pthread_self() = 2032932088
,D/JX-Cordova( 5906): jxcore cordova android initializing
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 5906): GC_CONCURRENT freed 4896K, 34% free 12790K/19128K, paused 4ms+4ms, total 47ms
,D/dalvikvm( 5906): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 5906): WAIT_FOR_CONCURRENT_GC blocked 24ms
,E/SMD     (  241): DCD ON
,D/dalvikvm( 5906): GC_FOR_ALLOC freed 4717K, 29% free 15761K/21936K, paused 41ms, total 42ms
,D/dalvikvm(  723): GC_EXPLICIT freed 2867K, 58% free 23698K/56040K, paused 7ms+17ms, total 171ms
,D/dalvikvm( 5906): GC_FOR_ALLOC freed 4868K, 31% free 16995K/24624K, paused 46ms, total 51ms
,I/dalvikvm-heap( 5906): Grow heap (frag case) to 22.363MB for 2475476-byte allocation
,D/dalvikvm( 5906): GC_FOR_ALLOC freed 3441K, 34% free 18019K/27044K, paused 37ms, total 41ms
,D/dalvikvm( 5906): GC_FOR_ALLOC freed 1425K, 35% free 17740K/27044K, paused 37ms, total 37ms
,W/jxcore-log( 5906): Initializing JXcore engine
,W/jxcore-log( 5906): JXcore engine is ready
,W/jxcore-log( 5906): Starting JXcore engine
,W/jxcore-log( 5906): Platform android
W/jxcore-log( 5906): 
,W/jxcore-log( 5906): Process ARCH arm
W/jxcore-log( 5906): 
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 5906): JXcore Cordova bridge is ready!
I/jxcore-log( 5906): 
,W/jxcore-log( 5906): JXcore engine is started
,I/chromium( 5906): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  241): DCD ON
,I/jxcore-log( 5906): Toggling radios to true
I/jxcore-log( 5906): 
,D/BluetoothAdapter( 5906): enable(): BT is already enabled..!
,I/WifiManager( 5906): packageName : com.test.thalitest
,I/WifiManager( 5906): setWifiEnabled : true
I/WifiService(  723): setWifiEnabled: true pid=5906, uid=10179
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5906, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  723): Failed getting userId using ActivityManagerNative
W/WifiService(  723): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5906, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  723): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  723): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  723): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  723): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  723): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  723): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService(  723): disconnect: pid=5906, uid=10179
I/wpa_supplicant( 1979): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 5906): Radios toggled
I/jxcore-log( 5906): 
I/jxcore-log( 5906): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5906): 
I/jxcore-log( 5906): Perf Test app loaded loaded
I/jxcore-log( 5906): 
,I/jxcore-log( 5906): check test folder
I/jxcore-log( 5906): 
,I/jxcore-log( 5906): found test : ./testFindPeers.js
I/jxcore-log( 5906): 
,I/wpa_supplicant( 1979): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1979): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/jxcore-log( 5906): found test : ./testSendData.js
I/jxcore-log( 5906): 
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1979): Cmd 35605 not handled
,E/wpa_supplicant( 1979): Cmd 35605 not handled
,I/wpa_supplicant( 1979): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 1979): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1979): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1979): First Scan Start
,I/wpa_supplicant( 1979): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
W/Settings(  723): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  723): ignore requestNetworkTransitionWakelock airplane:true
,D/Tethering(  723): InitialState.processMessage what=4
E/Tethering(  723): No numeric data
,D/Tethering(  723): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
I/ConnectivityService(  723): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  723): performPollLocked(flags=0x1)
D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
D/WifiP2pService(  723): InactiveState{ what=143375 }
D/WifiP2pService(  723): P2pEnabledState{ what=143375 }
,D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  238): Clearing all IP addresses on wlan0
D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
V/NetworkStats(  723): performPollLocked() took 32ms
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,I/WifiTrafficPoller(  723): evaluateTrafficStatsPolling
D/ConnectivityService(  723): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  723): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  723): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  723): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  723): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  723): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837977 act=2130837934
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
D/ConnectivityService(  723): Attempting to switch to mobile
D/ConnectivityService(  723): Attempting to switch to BLUETOOTH_TETHER
,I/wpa_supplicant( 1979): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1979): Skip scan - already scanning
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
D/STATUSBAR-IconMerger( 1065): checkOverflow(336), More:false, Req:false Child:2
,D/CommandListener(  238): Clearing all IP addresses on wlan0
D/WifiP2pService(  723): InactiveState{ what=143375 }
D/WifiP2pService(  723): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  723): Error! unhandled message{ when=-41ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller(  723): evaluateTrafficStatsPolling
,E/WifiStateMachine(  723): Error! unhandled message{ when=-40ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  238): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  238): RTNETLINK answers: No such process
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
E/WifiStateMachine(  723): Error! unhandled message{ when=-14ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController(  238): /system/bin/ip -6 rule del table 2 2>&1
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,W/NetworkManagementService(  723): route cmd failed: 
W/NetworkManagementService(  723): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '63 route del src v6 2' failed with '400 63 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  723): '
W/NetworkManagementService(  723): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  723): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  723): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  723): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  723): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  723): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  723): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  723): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  723): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  723): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  723): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  723): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  723): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  238): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  723): android_net_utils_resetConnections in env=0x77d35120 clazz=0xa7e00001 iface=wlan0 mask=0x3
D/ConnectivityService(  723): resetConnections(wlan0, 3)
,V/NativeCrypto( 1317): Read error: ssl=0x7bfcc8f8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1317): SSL shutdown failed: ssl=0x7bfcc8f8: I/O error during system call, Broken pipe
,I/chromium( 5906): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  723): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
V/NetworkStats(  723): updateIfacesLocked()
V/NetworkStats(  723): performPollLocked(flags=0x1)
V/NetworkStats(  723): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,V/NetworkStats(  723): performPollLocked() took 15ms
D/NtpTrustedTime(  723): currentTimeMillis() cache hit
D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,I/ApplicationPolicy(  723): updateDataUsageMap
,D/Tethering(  723): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  723): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  723): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  723): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1441): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5162): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5162): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5162): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5162): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5162): noConnectivity : true
,D/LocSvc_java(  723): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  723): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  723): ignore wifi update if we are not in OPENING or CLOSING
,I/wpa_supplicant( 1979): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 1979): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1979): wlan0: CTRL-EVENT-NO-CONNECTION
I/wpa_supplicant( 1979): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1979): Cmd 35609 not handled
,D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
D/WifiP2pService(  723): InactiveState{ what=147461 }
D/WifiP2pService(  723): P2pEnabledState{ what=147461 }
D/WifiP2pService(  723): DefaultState{ what=147461 }
D/WifiP2pService(  723): InactiveState{ what=147462 }
D/WifiP2pService(  723): P2pEnabledState{ what=147462 }
D/WifiP2pService(  723): DefaultState{ what=147462 }
,I/KLMS-2.3.201 : ( 5533): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5533): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450288039386
,I/KLMS-2.3.201 : ( 5533): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4045): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4045): [BDLM] already registered in spp
I/SA      ( 4045): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4045): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4045): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4045): [OR] == isSIMCardReady false ==
I/SA      ( 4045): [SCU] == networkStateCheck == false
,I/SA      ( 4045): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5564): Other Intent
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4096): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4096): getCountryCode(): countryCode = PL
,D/Headlines( 4096): Breath.onCreate
,D/Headlines( 4096): Breath timer started. interval : 30000
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  723): stay LED for fully charged
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4096): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4096): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4096): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager(  723): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  723): mCoverManager.getCoverState() : true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/QuickConnect[1.1][2] ( 3354): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/QuickConnect[1.1][2] ( 3354): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3354): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425eb2a8
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
D/STATUSBAR-IconMerger( 1065): checkOverflow(336), More:false, Req:false Child:2
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
,I/iu.Environment( 1753): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/AmoledAdjustTimer(  723): prevTemp = 280, currTemp = 281, prevStep = 4, currStep = 4
,I/iu.UploadsManager( 1753): num queued entries: 0
,I/iu.UploadsManager( 1753): num updated entries: 0
,I/iu.SyncManager( 1753): NEXT; no task
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 134 latestRequest time : 1450288039531 current time : 1450288039665
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/jxcore-log( 5906): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5906): 
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/wpa_supplicant( 1979): Scan requested (ret=0) - scan timeout 30 seconds
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  723): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(336), More:false, Req:false Child:2
,I/wpa_supplicant( 1979): nl80211: Received scan results (14 BSSes)
,I/wpa_supplicant( 1979): wlan0: Setting scan request: 16 sec 0 usec
,I/wpa_supplicant( 1979): Trying to associate with SSID '4E47373030'
,I/wpa_supplicant( 1979): Trying to associate with  'G700'
,I/wpa_supplicant( 1979): Re-associate with C0.AA.48
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1979): Cmd 35609 not handled
,D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
,E/wpa_supplicant( 1979): Cmd 35605 not handled
I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1979): Associated with C0.AA.48
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1979): freq(2412) increment count 3
,I/wpa_supplicant( 1979): meet head of list.
,E/wpa_supplicant( 1979): Cmd 35847 not handled
,E/wpa_supplicant( 1979): Cmd 35848 not handled
,E/wpa_supplicant( 1979): Cmd 35605 not handled
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1979): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1979): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1979): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative(  723): callSECApiVoid - ID [50]
,D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
,D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
,D/Tethering(  723): interfaceLinkStateChanged wlan0, false
,D/Tethering(  723): interfaceStatusChanged wlan0, false
,D/Tethering(  723): interfaceLinkStateChanged wlan0, true
,D/Tethering(  723): interfaceStatusChanged wlan0, true
,E/Tethering(  723): No numeric data
I/ConnectivityService(  723): defaultVal : 1, tetherEnabledInSettings : true
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
D/Tethering(  723): interfaceLinkStateChanged wlan0, true
D/Tethering(  723): interfaceStatusChanged wlan0, true
,D/Tethering(  723): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
V/NetworkStats(  723): performPollLocked(flags=0x1)
,D/Tethering(  723): interfaceLinkStateChanged wlan0, true
,D/Tethering(  723): interfaceStatusChanged wlan0, true
,D/Tethering(  723): interfaceLinkStateChanged wlan0, true
,D/Tethering(  723): interfaceStatusChanged wlan0, true
,D/Tethering(  723): interfaceLinkStateChanged wlan0, true
,D/Tethering(  723): interfaceStatusChanged wlan0, true
,D/WifiP2pService(  723): InactiveState{ what=143375 }
,D/WifiP2pService(  723): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
V/NetworkStats(  723): performPollLocked() took 346ms
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,I/dhcpcd  ( 6012): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6012): bssid match
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/WifiP2pService(  723): InactiveState{ what=143375 }
,D/WifiP2pService(  723): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
D/WifiStateMachine(  723): VerifyingLinkState enter
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  723): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  723): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  723): evaluateTrafficStatsPolling
D/ConnectivityService(  723): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  723): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  723): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1065): refreshSignalCluster - setNWBoosterIndicators(false)
,D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837977 act=2130837934
,D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/WifiTrafficPoller(  723): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  723): mBoosterFLAG : 2
,I/WifiTrafficPoller(  723): current booster mode : BTCoexMode
D/ConnectivityService(  723): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  723): net.tcp.usercfg.wifi not found in system properties. Using defaults
,E/ConnectivityService(  723): net.tcp.delack.wifi not found in system properties. Using defaults
D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  723): handleConnectivityChange: setting default proxy info 
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,V/RouteController(  238): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1302):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1302): showing allowed
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,V/RouteController(  238): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/SurfaceFlinger(  247): id=26 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  723): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=723
V/RouteController(  238): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,V/NetworkStats(  723): updateIfacesLocked()
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
V/NetworkStats(  723): performPollLocked(flags=0x1)
V/NetworkStats(  723): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
V/NetworkStats(  723): performPollLocked() took 20ms
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,D/NtpTrustedTime(  723): currentTimeMillis() cache hit
,I/ActivityManager(  723): Waited long enough for: ServiceRecord{445afe98 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/Tethering(  723): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  723): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  723): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1441): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5162): SPPPushClient is installed : true
,I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5162): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5162): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5162): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  723): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  723): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  723): ignore wifi update if we are not in OPENING or CLOSING
,E/SMD     (  241): DCD ON
,I/KLMS-2.3.201 : ( 5533): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5533): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450288055535
,I/KLMS-2.3.201 : ( 5533): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/LocationTagReadyService( 2560): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2560): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2560): [Slink platform] The state of Slink geocode service is true
,D/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,D/GalaxyFinderApplication( 2560): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2340): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,V/KVNProvider( 5744): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5744): getFindoCursor query string : 
,V/KVNProvider( 5744): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4045): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4045): [BDLM] already registered in spp
I/SA      ( 4045): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4045): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4045): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4045): [OR] == isSIMCardReady false ==
I/SA      ( 4045): [SCU] == networkStateCheck == true
I/SA      ( 4045): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4045): isChinaCountryCode : false
I/SA      ( 4045): [OR] == networkStateCheck true ==
,I/SA      ( 4045): [OR] GetMyCountryZoneTask
I/SA      ( 4045): [OR] onReceive END
,I/SA      ( 4045): [SRS] prepareGetMyCountryZone
,I/SA      ( 4045): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4045): [SSP] query invoked
,I/jxcore-log( 5906): Connected to the server!
I/jxcore-log( 5906): 
I/SA      ( 4045): [TPMU] GetMccFromDB : null
I/SA      ( 4045): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4045): [TPM] isNoProxy(default) : true
,I/SA      ( 4045): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 1237): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5564): Other Intent
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/chromium( 5906): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Headlines( 4096): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4096): getCountryCode(): countryCode = PL
D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4096): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4096): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4096): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4096): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3354): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3354): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3354): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425eb2a8
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
,D/RCPManagerService(  723): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4192): notifyNetworkActivated
,D/hcjo    ( 4192): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4192): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4192): exit::IDLE
,D/InitializeManagerStateMachine( 4192): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4192): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4192): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4192): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4192): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4192): exit::CHECK_COUNTRY_INFO
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
D/InitializeManagerStateMachine( 4192): entry::SUCCESS
D/hcjo    ( 4192): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4192): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4192): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4192): exit::SUCCESS
D/InitializeManagerStateMachine( 4192): entry::IDLE
,I/iu.Environment( 1753): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1753): num queued entries: 0
,I/iu.UploadsManager( 1753): num updated entries: 0
,I/iu.SyncManager( 1753): NEXT; no task
,D/ConnectivityService(  723): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  723): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/Watchdog(  723): !@Sync 12
,I/SA      ( 4045): [RC New] [v2liruge] api execute + 1630
,I/SA      ( 4045): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4045): AsyncTask #3 calls detatch()
,I/SA      ( 4045): [TPMU] getNetworkMcc : 
,I/SurfaceFlinger(  247): id=26 Removed Uoast (12/13)
,I/SurfaceFlinger(  247): id=26 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  723): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=723 (0x0)
,D/PowerManagerService(  723): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=723, ws=WorkSource{1000}) (elapsedTime=3508)
,I/SA      ( 4045): [SCU] saveMccToPreferece Start
,I/SA      ( 4045): [SCU] RegionMCC : 260
,I/SA      ( 4045): [SSP] query invoked
,I/SA      ( 4045): [TPMU] GetMccFromDB : null
,I/SA      ( 4045): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4045): [SCU] saveMccToPreferece End
,I/SA      ( 4045): [RC New] executeRequest [v2liruge] end. 1748
,I/SA      ( 4045): [RC New] Execute end
,I/SA      ( 4045): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4045): [OR] GetMyCountryZoneTask Success
,E/SMD     (  241): DCD ON
,W/WifiP2pStateTracker(  723): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  723): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  723):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  723): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  723): updateSourceRoutes : no source routing conditions
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/AmoledAdjustTimer(  723): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5162): mConnectivityHandler : connected
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/PCWCLIENTTRACE_AccountUtil( 5162): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5162): [GetString-S]
,I/terrier ( 5162): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5162): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5162): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5162): Loaded image: APP id = 6
,D/QSEECOMAPI: ( 5162): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5162): QSEECom_shutdown_app, app_id = 6
,E/terrier ( 5162): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5162): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5162): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5162): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5162): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5162): [ensureRegistration] - No Samsung account
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/CaptivePortalTracker(  723): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  723): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  723): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  723): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  723): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  723): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  723): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  723): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4192): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4192): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4192): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4192): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4192): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4192): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4192): entry::IDLE
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 13769 latestRequest time : 1450288055804 current time : 1450288069574
,D/AmoledAdjustTimer(  723): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 330s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 13
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 43799 latestRequest time : 1450288055804 current time : 1450288099603
,D/AmoledAdjustTimer(  723): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): stay LED for fully charged
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  723): mCoverManager.getCoverState() : true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 14
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 73765 latestRequest time : 1450288055804 current time : 1450288129569
,D/AmoledAdjustTimer(  723): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 390s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 15
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 103780 latestRequest time : 1450288055804 current time : 1450288159584
,D/AmoledAdjustTimer(  723): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 16
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,D/Headlines( 4096): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4096): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4096): Breath 133770 latestRequest time : 1450288055804 current time : 1450288189580
,D/Headlines( 4096): stop 
,D/Headlines( 4096): Breath.onDestroy : 
,D/AmoledAdjustTimer(  723): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,W/ProcessCpuTracker(  723): Skipping unknown process pid 6174
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  723): [PWL] Off : 455s ago
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm(  723): GC_CONCURRENT freed 3359K, 58% free 23823K/56040K, paused 23ms+61ms, total 696ms
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 17
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 18
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 19
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 525s ago
,D/AmoledAdjustTimer(  723): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  723): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  723): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  723): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 20
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 21
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 600s ago
,V/AlarmManager(  723): waitForAlarm result :8
,I/SensorManagerA(  723): getReportingMode :: sensor.mType = 5
,D/LightsService(  723): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  723): LightSensor setDelay = 200000000
D/Sensors (  723): LightSensor setSensorDelay = 200000000
D/Sensors (  723): Light sensor flush: not enabled 0
D/Sensors (  723): LightSensor enable = 1
D/Sensors (  723): LightSensor enableSensor = 1
D/SensorManager(  723): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  723): LightSensor enable = 0
D/LightsService(  723): [SvcLED]  onSensorChanged::light value = 0
,D/Sensors (  723): LightSensor enableSensor = 0
,D/SensorManager(  723): unregisterListener ::   
D/LightsService(  723): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 22
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  723): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  723): <AppSync3 Whitelist>
,V/AlarmManager(  723): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 23
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  723): !@Sync 24
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,I/PowerManagerService(  723): [PWL] Off : 680s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 25
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 26
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 27
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 765s ago
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  723): stay LED for fully charged
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 28
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 29
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService(  723): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  723): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  723): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  723): !@Sync 30
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 855s ago
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 31
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 32
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 33
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/dalvikvm(  723): GC_CONCURRENT freed 3499K, 58% free 23816K/55428K, paused 26ms+42ms, total 544ms
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
I/PowerManagerService(  723): [PWL] Off : 950s ago
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 34
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 35
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 36
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 1050s ago
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 37
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 38
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  723): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 39
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService(  723): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  723): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  723): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  723): !@Sync 40
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 41
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :4
,I/SensorManagerA(  723): getReportingMode :: sensor.mType = 5
,D/LightsService(  723): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  723): LightSensor setDelay = 200000000
D/Sensors (  723): LightSensor setSensorDelay = 200000000
D/Sensors (  723): Light sensor flush: not enabled 0
D/Sensors (  723): LightSensor enable = 1
D/Sensors (  723): LightSensor enableSensor = 1
,D/SensorManager(  723): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors (  723): LightSensor enable = 0
,D/LightsService(  723): [SvcLED]  onSensorChanged::light value = 0
D/Sensors (  723): LightSensor enableSensor = 0
,D/SensorManager(  723): unregisterListener ::   
D/LightsService(  723): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ConnectivityService(  723): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,E/Watchdog(  723): !@Sync 42
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  723): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  723): <AppSync3 Whitelist>
,V/AlarmManager(  723): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 43
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,I/PowerManagerService(  723): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 44
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 45
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 46
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 47
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 1380s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 48
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  723): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 49
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,E/SMD     (  241): DCD ON
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/dalvikvm(  723): GC_CONCURRENT freed 3497K, 57% free 23834K/55428K, paused 25ms+18ms, total 523ms
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  723): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  723): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  723): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 50
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 51
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 1500s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 52
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 53
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 54
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 55
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  723): [PWL] Off : 1625s ago
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 56
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,E/SMD     (  241): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 57
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 58
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 59
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  723): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  723): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  723): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 60
,I/PowerManagerService(  723): [PWL] Off : 1755s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  723): Prepared write state in 141ms
,I/ProcessStatsService(  723): Prepared write state in 127ms
,I/ProcessStatsService(  723): Pruning old procstats: /data/system/procstats/state-2015-12-16-04-02-17.bin
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  723): stay LED for fully charged
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 61
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 62
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  723): waitForAlarm result :8
,E/SMD     (  241): DCD ON
V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  723): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  723): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  723): (AppSync) ### 0 added ###
,I/ActivityManager(  723): Killing 4550:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1838s
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  723): stay LED for fully charged
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  723): !@Sync 63
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1941): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  241): DCD ON
E/Watchdog(  723): !@Sync 64
E/SMD     (  241): DCD ON
D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  723): mCoverManager.getCoverState() : true
D/BatteryService(  723): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1941): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
E/SMD     (  241): DCD ON
D/dalvikvm(  723): GC_CONCURRENT freed 3500K, 57% free 23849K/55428K, paused 23ms+37ms, total 529ms
E/SMD     (  241): DCD ON
E/SMD     (  241): DCD ON
D/AndroidRuntime( 6479): 
D/AndroidRuntime( 6479): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6479): CheckJNI is OFF
D/AndroidRuntime( 6479): setted country_code = Poland
D/AndroidRuntime( 6479): setted countryiso_code = PL
D/AndroidRuntime( 6479): setted sales_code = XEO
D/AndroidRuntime( 6479): readGMSProperty: start
D/AndroidRuntime( 6479): readGMSProperty: already setted!!
D/AndroidRuntime( 6479): readGMSProperty: end
D/AndroidRuntime( 6479): addProductProperty: start
D/dalvikvm( 6479): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6479): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6479): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6479): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6479): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6479): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6479): failed to load memtrack module: -2
D/dalvikvm( 6479): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6479): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  723): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  723): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  723): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  723): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  723): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  723): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  723): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  723): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  723): getApplicationUninstallationEnabled
D/ApplicationPolicy(  723): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  723): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  723): START PACKAGE DELETE: observer{1151979712}
D/PackageManager(  723): pkg{<packageName>}
D/PackageManager(  723): user{0}
D/PackageManager(  723): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  723): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  723): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  723): Killing 5906:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/ActivityManager(  723): Killing 5652:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1822s
I/ActivityManager(  723): Killing 5374:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1831s
I/ActivityManager(  723): Killing 5350:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1831s
I/ActivityManager(  723): Killing 5320:com.samsung.helphub/1000 (adj 15): empty for 1832s
I/ActivityManager(  723): Killing 5307:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1832s
I/ActivityManager(  723): Killing 5277:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1832s
I/ActivityManager(  723): Killing 5255:com.google.android.apps.docs/u0a90 (adj 15): empty for 1832s
I/ActivityManager(  723): Killing 5242:com.sec.android.service.cm/u0a78 (adj 15): empty for 1833s
I/ActivityManager(  723): Killing 4674:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1833s
I/ActivityManager(  723): Killing 4340:com.android.mms/u0a48 (adj 15): empty for 1833s
I/ActivityManager(  723): Killing 5217:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1833s
I/ActivityManager(  723): Killing 4238:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1833s
I/ActivityManager(  723): Killing 5174:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1834s
I/ActivityManager(  723): Killing 5146:com.android.musicfx/u0a24 (adj 15): empty for 1834s
I/ActivityManager(  723): Killing 5134:com.samsung.groupcast/u0a15 (adj 15): empty for 1834s
I/ActivityManager(  723): Killing 5119:com.google.android.partnersetup/u0a14 (adj 15): empty for 1834s
I/ActivityManager(  723): Killing 5101:com.sec.android.inputmethod/1000 (adj 15): empty for 1835s
I/ActivityManager(  723): Killing 5054:com.android.defcontainer/u0a6 (adj 15): empty for 1835s
I/SurfaceFlinger(  247): id=21 Removed NainActivit (7/12)
I/SurfaceFlinger(  247): id=21 Removed NainActivit (-2/12)
I/WindowState(  723): WIN DEATH: Window{430b6b70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  247): id=21 Removed NainActivit (-2/12)
E/SMD     (  241): DCD ON
D/CountryDetector(  723): No listener is left
W/PackageSettings(  723): Skipping PackageSetting{42606020 com.example.hello/10181} due to missing metadata
D/PackageManager(  723): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 2175): GC_EXPLICIT freed 1008K, 42% free 11224K/19128K, paused 2ms+3ms, total 54ms
D/dalvikvm( 1753): GC_EXPLICIT freed 871K, 37% free 12181K/19128K, paused 8ms+6ms, total 64ms
D/PackageManager(  723): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1065): action=android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 1403): GC_EXPLICIT freed 4301K, 48% free 10025K/19128K, paused 3ms+4ms, total 55ms
I/FPMS_FingerprintManagerService( 1084): onReceive: android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3354): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 1216): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "sms"
I/SELinux ( 6506): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6506):  
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/InputReader(  723): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "smsto"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  723): stay LED for fully charged
I/SELinux ( 6506): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6506):  
I/SELinux ( 6506):  
I/SELinux ( 6506): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6506): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6506): >>>>> Normal User
E/dalvikvm( 6506): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6506): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mms"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  723): GC_EXPLICIT freed 1231K, 58% free 23807K/55428K, paused 8ms+16ms, total 166ms
D/TimaKeyStoreProvider( 6506): in addTimaSignatureService
D/dalvikvm(  723): WAIT_FOR_CONCURRENT_GC blocked 50ms
D/TimaKeyStoreProvider( 6506): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6506): Added TimaKesytore provider
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mmsto"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "sms"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/RCPManagerService(  723): PackageReceiver onReceive()
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "smsto"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mms"
I/HarmonyEASService(  723): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  723): Package has changed for user 0
D/EnterpriseDeviceManagerService(  723): Admin package name: com.google.android.gms
I/SurfaceFlinger(  247): id=27 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mmsto"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=6506, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 6506): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6506): ELMEngine.ELMEngine( context ).
D/elm:14132( 6506): MDMBridge.setEnterpriseBridge()
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6506): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6506): ElmAgentService : onCreate()
D/elm:14132( 6506): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6506): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6506): MDMBridge.getInstance()
D/elm:14132( 6506): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6506): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6520): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6520):  
D/elm:14132( 6506): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 6506): ElmAgentService : onDestroy().
I/SELinux ( 6520): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6520):  
I/SELinux ( 6520):  
I/SELinux ( 6520): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6520): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6520): >>>>> Normal User
E/dalvikvm( 6520): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6520): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(  723): GC_EXPLICIT freed 762K, 57% free 23905K/55428K, paused 9ms+21ms, total 224ms
D/TimaKeyStoreProvider( 6520): in addTimaSignatureService
D/PackageManager(  723): delete sourFile : 
D/TimaKeyStoreProvider( 6520): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6520): Added TimaKesytore provider
D/PackageManager(  723): delete native library directory: 
D/PackageManager(  723): return delete result to caller: 1151979712
D/AndroidRuntime( 6479): Shutting down VM
D/PackageManager(  723): returnCode: 1
D/dalvikvm( 6479): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "sms"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BackupManagerService(  723): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  723): removePackageParticipantsLocked: uid=10179 #1
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
V/HeadsetService( 1941): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1941): Disconnected process message: 10
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "smsto"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mms"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/UiModeManager(  723): mCoverManager.getCoverState() : true
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mmsto"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=6520, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 6520): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425deb90, skipping init
I/SecureStorage( 6520): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6520): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  306): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6520
D/Launcher( 1241): onRestart, Launcher: 1114130584
I/SecureStorage(  306): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
D/Launcher( 1241): onStart, Launcher: 1114130584
D/Launcher.HomeView( 1241): onStart
I/SecureStorage( 6520): [INFO]: SPID(0x00000000)SS Daemon is running
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1441): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1441): [237392/5] SurfaceWidget drawing first frame
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 6520): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  306): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6520
I/SecureStorage(  306): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SurfaceFlinger(  247): id=28 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  723): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  723): clearDefaults: com.test.thalitest
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/InputReader(  723): Processing first event
W/ApplicationsProvider( 1403): Could not fetch usage stats
W/ApplicationsProvider( 1403): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1403): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1403): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1403): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1403): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1403): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
