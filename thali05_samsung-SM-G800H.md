#### Test 5065027881383b1_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5173, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
,--------- beginning of /dev/log/main
E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5173): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/ActivityManager(  732): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5173): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
I/SA      ( 4026): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4026): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4026): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4320): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2184): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4665): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5206): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5206):  
I/SELinux ( 5206): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5206):  
I/SELinux ( 5206):  
I/SELinux ( 5206): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5206): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5206): >>>>> Normal User
E/dalvikvm( 5206): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5206): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5206): in addTimaSignatureService
D/TimaKeyStoreProvider( 5206): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5206): Added TimaKesytore provider
I/IcingCorporaProvider( 2184): UpdateCorporaTask done [took 137 ms] updated apps [took 136 ms] 
I/ActivityManager(  732): Killing 3969:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/CapabilityManagerService New( 5206): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5206, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5219): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5219):  
I/ActivityManager(  732): Killing 4244:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5219): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5219):  
I/SELinux ( 5219):  
I/SELinux ( 5219): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5219): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5219): >>>>> Normal User
E/dalvikvm( 5219): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5219): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/AndroidRuntime( 5200): 
D/AndroidRuntime( 5200): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/TimaKeyStoreProvider( 5219): in addTimaSignatureService
D/AndroidRuntime( 5200): CheckJNI is OFF
D/AndroidRuntime( 5200): setted country_code = Poland
D/AndroidRuntime( 5200): setted countryiso_code = PL
D/AndroidRuntime( 5200): setted sales_code = XEO
D/AndroidRuntime( 5200): readGMSProperty: start
D/AndroidRuntime( 5200): readGMSProperty: already setted!!
D/AndroidRuntime( 5200): readGMSProperty: end
D/AndroidRuntime( 5200): addProductProperty: start
D/TimaKeyStoreProvider( 5219): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5219): Added TimaKesytore provider
D/SSRMv2:SIOP(  732): SIOP:: AP = 320, Delta = 10
D/dalvikvm( 5200): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5200): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5200): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5200): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5200): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5219, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
E/memtrack( 5200): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5200): failed to load memtrack module: -2
D/dalvikvm( 5200): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5200): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy(  732): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  732): mDVFSHelper.acquire()
I/SELinux ( 5240): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5240):  
D/LockPatternUtils( 1070): isPcwEnable = null
D/AndroidRuntime( 5200): Shutting down VM
D/dalvikvm( 5200): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 4ms
I/SELinux ( 5240): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5240):  
I/SELinux ( 5240):  
I/SELinux ( 5240): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5240): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5240): >>>>> Normal User
E/dalvikvm( 5240): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5240): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5240): in addTimaSignatureService
D/TimaKeyStoreProvider( 5240): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5240): Added TimaKesytore provider
D/LockPatternUtils( 1070): isPcwEnable = null
I/SurfaceFlinger(  239): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  239): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1265): destroyHardwareResources():1126171592
I/SQLiteSecureOpenHelper( 2094): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2094): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  239): id=9 Removed Mauncher (7/11)
I/SurfaceFlinger(  239): id=9 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1265): onTrimMemory. Level: 20
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5240, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/GAV2    ( 5219): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5259): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5259):  
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5240, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5240): Binding Chromium to the background looper Looper (main, tid 1) {422d1198}
I/chromium( 5240): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5240): Initializing chromium process, renderers=0
I/SELinux ( 5259): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5259):  
I/SELinux ( 5259):  
I/SELinux ( 5259): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5259): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5259): >>>>> Normal User
E/dalvikvm( 5259): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5259): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/chromium( 5240): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5240): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5240): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5240): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5240): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5240): Remote Branch: 
I/Adreno-EGL( 5240): Local Patches: 
I/Adreno-EGL( 5240): Reconstruct Branch: 
D/TimaKeyStoreProvider( 5259): in addTimaSignatureService
D/TimaKeyStoreProvider( 5259): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5259): Added TimaKesytore provider
D/PackageIntentReceiver( 5259): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5259): Not GearManger package! 
I/SELinux ( 5287): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5287):  
I/ActivityManager(  732): Killing 3982:com.sec.android.soagent/u0a37 (adj 15): empty #43
I/dalvikvm( 5240): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5240): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5240): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5240): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5240): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5240): VFY: replacing opcode 0x6e at 0x0008
I/SELinux ( 5287): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5287):  
I/SELinux ( 5287):  
I/SELinux ( 5287): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5287): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5287): >>>>> Normal User
E/dalvikvm( 5287): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
W/dalvikvm( 5240): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5240): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5240): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5240): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5240): VFY: replacing opcode 0x6f at 0x001a
E/SELinux ( 5287): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/dalvikvm( 5240): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5240): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5240): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5240): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5240): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5240): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5240): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5240): CordovaWebView is running on device made by: samsung
D/TimaKeyStoreProvider( 5287): in addTimaSignatureService
D/TimaKeyStoreProvider( 5287): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5287): Added TimaKesytore provider
D/MagazineService Version( 5287): Magazine-Channel: 13
D/MagazineService Version( 5287): Magazine-Provider: 13
D/MagazineService Version( 5287): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5287): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5287): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5287, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5287): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5306): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5306):  
D/MagazineService::MagazineService( 5287): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/SurfaceFlinger(  239): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
W/GAV2    ( 5219): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  732): Killing 4357:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
I/ActivityManager(  732): Killing 4370:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
I/HWUI    ( 5240): EGLImpl-HWUI Protected EGL context created
I/SELinux ( 5306): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5306):  
I/SELinux ( 5306):  
I/SELinux ( 5306): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5306): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5306): >>>>> Normal User
E/dalvikvm( 5306): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5306): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/OpenGLRenderer( 5240): Enabling debug mode 0
W/AwContents( 5240): nativeOnDraw failed; clearing to background color.
D/TimaKeyStoreProvider( 5306): in addTimaSignatureService
D/TimaKeyStoreProvider( 5306): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5306): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  732): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 5327): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5327):  
I/ActivityManager(  732): Killing 4382:com.sec.esdk.elm/u0a94 (adj 15): empty #43
I/SELinux ( 5327): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5327):  
I/SELinux ( 5327):  
I/SELinux ( 5327): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5327): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5327): >>>>> Normal User
E/dalvikvm( 5327): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 5327): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5327): in addTimaSignatureService
D/TimaKeyStoreProvider( 5327): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5327): Added TimaKesytore provider
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5327, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 5327): Package not found : com.sec.android.app.kidshome
D/JsMessageQueue( 5240): Set native->JS mode to OnlineEventsBridgeMode
I/SELinux ( 5342): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5342):  
I/ActivityManager(  732): Killing 3570:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
I/SELinux ( 5342): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5342):  
I/SELinux ( 5342):  
I/SELinux ( 5342): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5342): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5342): >>>>> Normal User
E/dalvikvm( 5342): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
E/SELinux ( 5342): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5342): in addTimaSignatureService
D/TimaKeyStoreProvider( 5342): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5342): Added TimaKesytore provider
D/dalvikvm( 5240): Trying to load lib /data/app-lib/com.test.thalitest-29/libjxcore.so 0x425f7f08
D/dalvikvm( 5240): Added shared lib /data/app-lib/com.test.thalitest-29/libjxcore.so 0x425f7f08
D/jxcore_app_log( 5240): JniHelper::setJavaVM(0x41735528), pthread_self() = 2026088240
D/JX-Cordova( 5240): jxcore cordova android initializing
I/dalvikvm( 5240): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 5240): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5240): VFY: replacing opcode 0x6e at 0x0045
I/ActivityManager(  732): Killing 4410:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/Finsky  ( 3668): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1805): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1805): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/dalvikvm( 1805): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1805): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1805): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1805): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1805): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1805): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1805): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1805): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1805): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1805): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1805): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,E/SMD     (  233): DCD ON
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1805): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1805): Submit a task: k
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/dalvikvm( 5240): GC_CONCURRENT freed 4925K, 33% free 12767K/18992K, paused 2ms+3ms, total 32ms
,D/dalvikvm( 5240): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 5240): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/k       ( 1805): Processing package: com.test.thalitest
,W/BaseAppContext( 1805): Using Auth Proxy for data requests.
,W/BaseAppContext( 1805): Using Auth Proxy for data requests.
,D/GassUtils( 1805): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1805): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1805): Using Auth Proxy for data requests.
,W/BaseAppContext( 1805): Using Auth Proxy for data requests.
,W/BaseAppContext( 1805): Using Auth Proxy for data requests.
,W/BaseAppContext( 1805): Using Auth Proxy for data requests.
,W/dalvikvm( 1805): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1805): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1805): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1805): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1805): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1805): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1805): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1805): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1805): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
,W/dalvikvm( 1805): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1805): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 1805): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1805): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1805): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1805): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1805): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1805): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1805): cleanUpNonGplusAccounts done.
,D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@9
,D/ChimeraCfgMgr( 1805): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1805): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5240): GC_FOR_ALLOC freed 4722K, 28% free 15776K/21820K, paused 32ms, total 33ms
,D/dalvikvm( 5240): GC_FOR_ALLOC freed 5080K, 32% free 16788K/24508K, paused 35ms, total 36ms
,I/dalvikvm-heap( 5240): Grow heap (frag case) to 22.024MB for 2475476-byte allocation
,I/Icing   ( 1805): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1805): GC_CONCURRENT freed 1377K, 35% free 12482K/18992K, paused 5ms+5ms, total 60ms
,D/dalvikvm( 1805): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/Icing   ( 1805): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/dalvikvm( 5240): GC_FOR_ALLOC freed 3778K, 36% free 17475K/26928K, paused 33ms, total 33ms
,D/dalvikvm( 5240): GC_FOR_ALLOC freed 1244K, 36% free 17377K/26928K, paused 28ms, total 29ms
,W/jxcore-log( 5240): Initializing JXcore engine
,W/jxcore-log( 5240): JXcore engine is ready
,W/jxcore-log( 5240): Starting JXcore engine
,W/jxcore-log( 5240): Platform android
W/jxcore-log( 5240): 
,W/jxcore-log( 5240): Process ARCH arm
W/jxcore-log( 5240): 
,E/SMD     (  233): DCD ON
,I/jxcore-log( 5240): JXcore Cordova bridge is ready!
I/jxcore-log( 5240): 
,W/jxcore-log( 5240): JXcore engine is started
,I/chromium( 5240): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/AmoledAdjustTimer(  732): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/GAV2    ( 5219): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 5240): Toggling radios to true
I/jxcore-log( 5240): 
,D/BluetoothAdapter( 5240): enable(): BT is already enabled..!
,I/WifiManager( 5240): packageName : com.test.thalitest
I/WifiManager( 5240): setWifiEnabled : true
,I/WifiService(  732): setWifiEnabled: true pid=5240, uid=10179
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5240, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  732): Failed getting userId using ActivityManagerNative
W/WifiService(  732): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5240, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  732): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  732): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  732): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  732): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  732): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  732): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  732): disconnect: pid=5240, uid=10179
,I/wpa_supplicant( 1975): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5240): Radios toggled
I/jxcore-log( 5240): 
,I/jxcore-log( 5240): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5240): 
,I/jxcore-log( 5240): Perf Test app loaded loaded
I/jxcore-log( 5240): 
,I/jxcore-log( 5240): check test folder
I/jxcore-log( 5240): 
,I/jxcore-log( 5240): found test : ./testFindPeers.js
I/jxcore-log( 5240): 
,I/wpa_supplicant( 1975): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1975): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering(  732): interfaceLinkStateChanged wlan0, false
,D/Tethering(  732): interfaceStatusChanged wlan0, false
D/Tethering(  732): InitialState.processMessage what=4
I/wpa_supplicant( 1975): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1975): Cmd 35605 not handled
E/wpa_supplicant( 1975): Cmd 35605 not handled
,I/wpa_supplicant( 1975): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,E/Tethering(  732): No numeric data
I/wpa_supplicant( 1975): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1975): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1975): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1975): First Scan Start
,I/wpa_supplicant( 1975): Scan requested (ret=0) - scan timeout 30 seconds
,I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  732): interfaceLinkStateChanged wlan0, false
D/Tethering(  732): interfaceStatusChanged wlan0, false
D/Tethering(  732): interfaceLinkStateChanged wlan0, false
D/Tethering(  732): interfaceStatusChanged wlan0, false
W/Settings(  732): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  732): ignore requestNetworkTransitionWakelock airplane:true
,D/Tethering(  732): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
D/WifiP2pService(  732): InactiveState{ what=143375 }
V/NetworkStats(  732): performPollLocked(flags=0x1)
D/STATUSBAR-NetworkController_dual( 1070): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 GONE
D/WifiP2pService(  732): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  230): Clearing all IP addresses on wlan0
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,V/NetworkStats(  732): performPollLocked() took 27ms
,I/WifiTrafficPoller(  732): evaluateTrafficStatsPolling
D/ConnectivityService(  732): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  732): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  732): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController_dual( 1070): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService(  732): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  732): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  732): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/SignalClusterView_dual( 1070): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1070): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1070): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1070): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1070): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1070): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1070): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1070): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1070): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1070): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1070): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1070): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1070): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1070): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1070): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1070): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews start
D/ConnectivityService(  732): Attempting to switch to mobile
D/ConnectivityService(  732): Attempting to switch to BLUETOOTH_TETHER
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews set mobileLabel[SIM_0] =No service.
I/wpa_supplicant( 1975): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1975): Skip scan - already scanning
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1070): checkOverflow(336), More:false, Req:false Child:2
I/SELinux ( 5387): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5387):  
V/RouteController(  230): /system/bin/ip -6 route del default table 2 2>&1
I/jxcore-log( 5240): found test : ./testSendData.js
I/jxcore-log( 5240): 
,D/WifiP2pService(  732): InactiveState{ what=143375 }
,V/RouteController(  230): RTNETLINK answers: No such process
,V/RouteController(  230): /system/bin/ip -6 rule del table 2 2>&1
D/WifiP2pService(  732): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1070): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  230): RTNETLINK answers: No such file or directory
,D/CommandListener(  230): Clearing all IP addresses on wlan0
,W/NetworkManagementService(  732): route cmd failed: 
W/NetworkManagementService(  732): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  732): '
W/NetworkManagementService(  732): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  732): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  732): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  732): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  732): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  732): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  732): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  732): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  732): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  732): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  732): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  732): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  230): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller(  732): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController_dual( 1070): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set as slot1`s
I/SELinux ( 5387): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5387):  
I/SELinux ( 5387):  
I/SELinux ( 5387): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5387): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5387): >>>>> Normal User
E/dalvikvm( 5387): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
E/WifiStateMachine(  732): Error! unhandled message{ when=-90ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  732): Error! unhandled message{ when=-90ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  732): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/SELinux ( 5387): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
V/RouteController(  230): RTNETLINK answers: No such process
V/RouteController(  230): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 5387): in addTimaSignatureService
,V/RouteController(  230): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 5387): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5387): Added TimaKesytore provider
,D/NetUtils(  732): android_net_utils_resetConnections in env=0x7a981ce0 clazz=0x6a900001 iface=wlan0 mask=0x3
D/ConnectivityService(  732): resetConnections(wlan0, 3)
V/AlarmManager(  732): waitForAlarm result :4
V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/NativeCrypto( 1308): Read error: ssl=0x7bff1660: I/O error during system call, Connection timed out
,V/NativeCrypto( 1308): SSL shutdown failed: ssl=0x7bff1660: I/O error during system call, Broken pipe
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  732): stay LED for fully charged
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
D/UiModeManager(  732): mCoverManager.getCoverState() : true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
D/NtpTrustedTime(  732): currentTimeMillis() cache hit
D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
V/NetworkStats(  732): updateIfacesLocked()
V/NetworkStats(  732): performPollLocked(flags=0x1)
V/NetworkStats(  732): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/ConnectivityService(  732): handleInetConditionChange: no active default network - ignore
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
V/NetworkStats(  732): performPollLocked() took 21ms
,I/System.out( 5387): Inside WakeupProvider
,I/System.out( 5387): Inside onCreate() of WakeupTriggerProvide
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/STATUSBAR-IconMerger( 1070): checkOverflow(336), More:false, Req:false Child:2
I/chromium( 5240): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/VlingoApplication( 5387): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5387): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5387): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5387): initQueue()
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  732): Killing 4428:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,D/Headlines( 4089): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 4089): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4089): Breath 68412 latestRequest time : 1449752899496 current time : 1449752967909
,D/dalvikvm( 1308): GC_EXPLICIT freed 906K, 44% free 10786K/18992K, paused 8ms+5ms, total 54ms
,D/FactoryTest( 4731): Not factory mode
,D/FactoryTest( 4731): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4731): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4731): still no open session command from host, so toast
W/ContextImpl( 4731): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4731): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
V/ApplicationPolicy(  732): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  732): mDVFSHelper.acquire()
,D/LockPatternUtils( 1070): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2094): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2094): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1070): isPcwEnable = null
,E/MTPRx   ( 4731): started activity for popup
,E/SettingsReceiverActivity( 4731): PREF_DONT_ASK_AGAIN : false
,D/dalvikvm(  732): GC_EXPLICIT freed 7560K, 58% free 23788K/55836K, paused 7ms+14ms, total 145ms
,D/Tethering(  732): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy(  732): updateDataUsageMap
,D/Tethering(  732): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  732): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  732): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/LocSvc_java(  732): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  732): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  732): ignore wifi update if we are not in OPENING or CLOSING
D/STATUSBAR-NetworkController_dual( 1070): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set as slot1`s
,D/SettingsReceiverActivity( 4731): dev.kiessupport is : TRUE
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5120): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5120): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5120): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5120): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 3897): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5120): noConnectivity : true
,I/SELinux ( 5422): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5422):  
,I/SurfaceFlinger(  239): id=18 createSurf (1x1),1 flag=4, TettingsRec
I/SELinux ( 5422): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5422):  
I/SELinux ( 5422):  
,I/SELinux ( 5422): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
,E/SELinux ( 5422): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
E/dalvikvm( 5422): >>>>> Normal User
,E/dalvikvm( 5422): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5422): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4731): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4731): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4731): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4731): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4731): Remote Branch: 
I/Adreno-EGL( 4731): Local Patches: 
I/Adreno-EGL( 4731): Reconstruct Branch: 
,D/TimaKeyStoreProvider( 5422): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5422): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5422): Added TimaKesytore provider
,I/HWUI    ( 4731): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4731): Enabling debug mode 0
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5422, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  732): Killing 4450:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@5
,E/SMD     (  233): DCD ON
D/CustomFrequencyManagerService(  732): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
W/ActivityManager(  732): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 5438): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5438):  
,I/wpa_supplicant( 1975): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 1975): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1975): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1975): Trying to associate with  'G700'
I/wpa_supplicant( 1975): Re-associate with C0.AA.48
,I/wpa_supplicant( 1975): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering(  732): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1975): Cmd 35609 not handled
,D/Tethering(  732): interfaceStatusChanged wlan0, false
,D/dalvikvm(  246): GC_EXPLICIT freed 43K, 50% free 9511K/18992K, paused 3ms+2ms, total 29ms
,D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9511K/18992K, paused 2ms+3ms, total 18ms
,I/SELinux ( 5438): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5438):  
I/SELinux ( 5438):  
,I/SELinux ( 5438): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5438): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5438): >>>>> Normal User
,E/dalvikvm( 5438): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5438): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9511K/18992K, paused 2ms+3ms, total 20ms
,D/TimaKeyStoreProvider( 5438): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5438): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5438): Added TimaKesytore provider
,E/wpa_supplicant( 1975): Cmd 35605 not handled
I/wpa_supplicant( 1975): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1975): Associated with C0.AA.48
I/wpa_supplicant( 1975): freq(2412) increment count 2
I/wpa_supplicant( 1975): meet head of list.
,I/wpa_supplicant( 1975): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  732): interfaceLinkStateChanged wlan0, false
,D/Tethering(  732): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1975): Cmd 35847 not handled
E/wpa_supplicant( 1975): Cmd 35848 not handled
E/wpa_supplicant( 1975): Cmd 35605 not handled
,D/Tethering(  732): interfaceLinkStateChanged wlan0, false
,D/Tethering(  732): interfaceStatusChanged wlan0, false
D/Tethering(  732): interfaceLinkStateChanged wlan0, false
,D/Tethering(  732): interfaceStatusChanged wlan0, false
,D/Tethering(  732): interfaceLinkStateChanged wlan0, true
,D/Tethering(  732): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 1975): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1975): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1975): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering(  732): interfaceLinkStateChanged wlan0, true
,D/Tethering(  732): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1975): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/Tethering(  732): No numeric data
,D/Tethering(  732): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/WifiNative(  732): callSECApiVoid - ID [50]
D/Tethering(  732): interfaceLinkStateChanged wlan0, true
,D/Tethering(  732): interfaceStatusChanged wlan0, true
D/Tethering(  732): interfaceLinkStateChanged wlan0, true
,D/Tethering(  732): interfaceStatusChanged wlan0, true
I/ConnectivityService(  732): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  732): performPollLocked(flags=0x1)
,D/Tethering(  732): interfaceLinkStateChanged wlan0, true
,D/Tethering(  732): interfaceStatusChanged wlan0, true
D/STATUSBAR-NetworkController_dual( 1070): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
V/NetworkStats(  732): performPollLocked() took 29ms
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5438, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,D/WifiP2pService(  732): InactiveState{ what=143375 }
,D/WifiP2pService(  732): P2pEnabledState{ what=143375 }
,I/ActivityManager(  732): Killing 4466:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5451): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5451):  
,I/SELinux ( 5451): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5451):  
I/SELinux ( 5451):  
I/SELinux ( 5451): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5451): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5451): >>>>> Normal User
E/dalvikvm( 5451): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 5451): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5451): in addTimaSignatureService
D/TimaKeyStoreProvider( 5451): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5451): Added TimaKesytore provider
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5451, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
D/KLMS-2.3.201 : ( 5451): KLMSValidator() : checkQATesting()
I/KLMS-2.3.201 : ( 5451): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449752968946
I/KLMS-2.3.201 : ( 5451): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
I/ActivityManager(  732): Killing 1339:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 5470): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5470):  
I/dhcpcd  ( 5463): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 5463): bssid match
I/SELinux ( 5470): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5470):  
I/SELinux ( 5470):  
I/SELinux ( 5470): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5470): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5470): >>>>> Normal User
E/dalvikvm( 5470): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
E/SELinux ( 5470): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5470): in addTimaSignatureService
D/TimaKeyStoreProvider( 5470): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5470): Added TimaKesytore provider
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5470, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
D/SO_AGENT( 5470): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/SO_AGENT( 5470): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
I/SA      ( 4026): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4026): [BDLM] already registered in spp
I/SA      ( 4026): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 4026): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4026): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4026): [OR] == isSIMCardReady false ==
I/SA      ( 4026): [SCU] == networkStateCheck == false
I/SA      ( 4026): [OR] onReceive END
I/ActivityManager(  732): Killing 4600:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
I/SELinux ( 5482): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5482):  
I/SELinux ( 5482): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5482):  
I/SELinux ( 5482):  
I/SELinux ( 5482): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5482): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5482): >>>>> Normal User
E/dalvikvm( 5482): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
E/SELinux ( 5482): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5482): in addTimaSignatureService
D/TimaKeyStoreProvider( 5482): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5482): Added TimaKesytore provider
I/sCloudBackupApp( 5482): sCloudBackupApp Version Info : 3.7.3.KK_APP
I/SCloudBackupReceiver( 5482): Other Intent
D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ActivityManager(  732): Killing 4622:com.sec.android.app.voicenote/1000 (adj 15): empty #43
I/SELinux ( 5499): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5499):  
I/SELinux ( 5499): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5499):  
I/SELinux ( 5499):  
I/SELinux ( 5499): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5499): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5499): >>>>> Normal User
E/dalvikvm( 5499): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
E/SELinux ( 5499): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
D/TimaKeyStoreProvider( 5499): in addTimaSignatureService
D/TimaKeyStoreProvider( 5499): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5499): Added TimaKesytore provider
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5499, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@9
,I/ActivityManager(  732): Killing 4627:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/Headlines( 4089): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4089): getCountryCode(): countryCode = PL
,D/Headlines( 4089): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4089): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4089): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 4089): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4089): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 4089): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4089): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5531): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5531):  
,I/SELinux ( 5531): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5531):  
I/SELinux ( 5531):  
,I/SELinux ( 5531): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5531): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5531): >>>>> Normal User
,E/dalvikvm( 5531): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5531): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5531): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5531): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5531): Added TimaKesytore provider
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5531): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5531): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 5531): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5531): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5531): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,D/WifiP2pService(  732): InactiveState{ what=143375 }
,D/WifiP2pService(  732): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  732): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1070): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1070): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  732): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  732): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  732): evaluateTrafficStatsPolling
,D/WifiStateMachine(  732): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  732): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  732): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1070): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  732): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  732): mBoosterFLAG : 2
,I/WifiTrafficPoller(  732): current booster mode : BTCoexMode
D/ConnectivityService(  732): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  732): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  732): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1070): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1070): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1070): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1070): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1070): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1070): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1070): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1070): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1070): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1070): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1070): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1070): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1070): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1070): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1070): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1070): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1070): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set as slot1`s
,D/ConnectivityService(  732): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,V/RouteController(  230): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  230): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  230): RTNETLINK answers: No such file or directory
,V/RouteController(  230): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,V/WebViewChromium( 5531): Binding Chromium to the main looper Looper (main, tid 1) {422d2f48}
,I/chromium( 5531): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5531): Initializing chromium process, renderers=0
,V/RouteController(  230): /system/bin/ip route flush cached 2>&1
,W/chromium( 5531): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5531): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5531): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5531): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5531): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5531): Remote Branch: 
I/Adreno-EGL( 5531): Local Patches: 
I/Adreno-EGL( 5531): Reconstruct Branch: 
,V/RouteController(  230): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  230): RTNETLINK answers: No such process
,V/RouteController(  230): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  230): /system/bin/ip route flush cached 2>&1
,I/NSApplication( 5531): Starting up...
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
D/NtpTrustedTime(  732): currentTimeMillis() cache hit
D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
V/NetworkStats(  732): updateIfacesLocked()
V/NetworkStats(  732): performPollLocked(flags=0x1)
V/NetworkStats(  732): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5531, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
D/NtpTrustedTime(  732): currentTimeMillis() cache hit
V/NetworkStats(  732): performPollLocked() took 19ms
D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/NtpTrustedTime(  732): currentTimeMillis() cache hit
,D/QuickConnect[1.1][2] ( 3347): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3347): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3347): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42605290
I/ActivityManager(  732): Killing 4680:com.google.android.talk/u0a105 (adj 15): empty #43
,I/SELinux ( 5588): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5588):  
,I/SELinux ( 5588): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5588):  
I/SELinux ( 5588):  
,I/SELinux ( 5588): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5588): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5588): >>>>> Normal User
,E/dalvikvm( 5588): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5588): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5588): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5588): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5588): Added TimaKesytore provider
,D/RCPManagerService(  732): exchangeData() failure , invalid userId
,D/RCPManagerService(  732): exchangeData() failure , invalid userId
,D/RCPManagerService(  732): exchangeData() failure , invalid userId
,D/RCPManagerService(  732): exchangeData() failure , invalid userId
,D/RCPManagerService(  732): exchangeData() failure , invalid userId
,D/RCPManagerService(  732): exchangeData() failure , invalid userId
I/ActivityManager(  732): Killing 3043:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,I/SELinux ( 5607): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5607):  
,I/SELinux ( 5611): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5611):  
W/ActivityManager(  732): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5607): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5607):  
I/SELinux ( 5607):  
,I/SELinux ( 5607): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5607): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5607): >>>>> Normal User
,E/dalvikvm( 5607): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5607): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/SELinux ( 5611): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5611):  
I/SELinux ( 5611):  
,I/SELinux ( 5611): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/TimaKeyStoreProvider( 5607): in addTimaSignatureService
E/SELinux ( 5611): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5611): >>>>> Normal User
,E/dalvikvm( 5611): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5611): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5607): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5607): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5611): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5611): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5611): Added TimaKesytore provider
,I/ActivityManager(  732): Killing 4767:com.sec.knox.bridge/1000 (adj 15): empty #43
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5607, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5611): onCreate
,D/BadgeProvider( 5611): DatabaseHelper
,D/hcjo    ( 4180): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4180): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4180): exit::IDLE
,D/InitializeManagerStateMachine( 4180): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4180): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4180): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4180): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4180): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4180): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4180): entry::SUCCESS
,D/hcjo    ( 4180): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4180): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4180): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4180): exit::SUCCESS
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5611, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/InitializeManagerStateMachine( 4180): entry::IDLE
,D/BadgeProvider( 5611): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/ActivityManager(  732): Killing 4788:com.wssyncmldm/1000 (adj 15): empty #43
,D/BadgeProvider( 5611): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5611): sendNotify, [notify] : null
D/BadgeProvider( 5611): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5611): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5611): update, [UpdateCount] : 1
,D/Launcher.Model( 1265): reloadBadges entered.
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,D/Tethering(  732): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  732): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  732): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1070): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/LocSvc_java(  732): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  732): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  732): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1070): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1070): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3897): type=WIFI subType= reason=null isConnected=true
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1313):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1313): showing allowed
,I/SurfaceFlinger(  239): id=19 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  732): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=732
D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
I/PCWCLIENTTRACE_PushUtil( 5120): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5120): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5120): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5120): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
,I/VacuumService( 1219): Vacuum at: now=1449752970677 tag=VacuumService
,I/KLMS-2.3.201 : ( 5451): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5451): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449752970751
,I/KLMS-2.3.201 : ( 5451): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/LocationTagReadyService( 2575): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/SO_AGENT( 5470): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
D/GalaxyFinderApplication( 2575): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2575): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2575): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5470): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 5638): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5638):  
,I/GallerySearchProvider( 2424): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5642): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5642):  
,I/SELinux ( 5638): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5638):  
I/SELinux ( 5638):  
,I/SELinux ( 5638): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5638): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5638): >>>>> Normal User
,E/dalvikvm( 5638): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5638): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5638): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5638): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5638): Added TimaKesytore provider
,I/SELinux ( 5642): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5642):  
I/SELinux ( 5642):  
,I/SELinux ( 5642): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5642): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5642): >>>>> Normal User
,E/dalvikvm( 5642): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5642): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5642): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5642): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5642): Added TimaKesytore provider
,I/SA      ( 4026): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4026): [BDLM] already registered in spp
I/SA      ( 4026): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4026): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4026): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4026): [OR] == isSIMCardReady false ==
,I/SA      ( 4026): [SCU] == networkStateCheck == true
I/SA      ( 4026): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4026): isChinaCountryCode : false
,I/SA      ( 4026): [OR] == networkStateCheck true ==
,I/SA      ( 4026): [OR] GetMyCountryZoneTask
,I/SA      ( 4026): [OR] onReceive END
D/SSRMv2:SIOP(  732): SIOP:: AP = 330, Delta = 10
,I/SA      ( 4026): [SRS] prepareGetMyCountryZone
,I/SA      ( 4026): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4026): [SSP] query invoked
,I/SA      ( 4026): [TPMU] GetMccFromDB : null
,I/SA      ( 4026): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4026): [TPM] isNoProxy(default) : true
,I/SA      ( 4026): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5482): Other Intent
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,V/KVNProvider( 5642): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5642): getFindoCursor query string : 
,D/Headlines( 4089): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4089): getCountryCode(): countryCode = PL
D/Headlines( 4089): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4089): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4089): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4089): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4089): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4089): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4089): requestUpdateNewsWelcomeCard !!! no welcome card
,V/KVNProvider( 5642): getTagSearchCursor() tagSearchCursor count : 0
,I/ActivityManager(  732): Killing 4639:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
D/QuickConnect[1.1][2] ( 3347): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3347): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3347): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42605290
,D/RCPManagerService(  732): exchangeData() failure , invalid userId
,D/RCPManagerService(  732): exchangeData() failure , invalid userId
,D/hcjo    ( 4180): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4180): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4180): exit::IDLE
,D/InitializeManagerStateMachine( 4180): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4180): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4180): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4180): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4180): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4180): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4180): entry::SUCCESS
,D/hcjo    ( 4180): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4180): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4180): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4180): exit::SUCCESS
,D/InitializeManagerStateMachine( 4180): entry::IDLE
,E/SMD     (  233): DCD ON
,I/SA      ( 4026): [RC New] [v2liruge] api execute + 635
,I/SA      ( 4026): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4026): AsyncTask #2 calls detatch()
,I/SA      ( 4026): [TPMU] getNetworkMcc : 
,I/SA      ( 4026): [SCU] saveMccToPreferece Start
,I/SA      ( 4026): [SCU] RegionMCC : 260
,I/SA      ( 4026): [SSP] query invoked
,I/SA      ( 4026): [TPMU] GetMccFromDB : null
,I/SA      ( 4026): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4026): [SCU] saveMccToPreferece End
,I/SA      ( 4026): [RC New] executeRequest [v2liruge] end. 656
,I/SA      ( 4026): [RC New] Execute end
,I/SA      ( 4026): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4026): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 5240): BLE advertisement not supported: Build version is 19
I/jxcore-log( 5240): 
,I/HarmonyEASService(  732): Updating for all 1
,W/WifiP2pStateTracker(  732): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  732): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  732):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  732): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  732): updateSourceRoutes : no source routing conditions
,E/WifiStateMachine(  732): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ActivityManager(  732): Killing 4203:com.android.calendar/u0a142 (adj 15): empty #43
,I/SurfaceFlinger(  239): id=19 Removed Uoast (12/13)
,I/SurfaceFlinger(  239): id=19 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1070): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1070): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  732): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=732 (0x0)
,D/PowerManagerService(  732): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=732, ws=WorkSource{1000}) (elapsedTime=3548)
,E/SMD     (  233): DCD ON
,I/GAV2    ( 5531): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5120): mConnectivityHandler : connected
,D/AmoledAdjustTimer(  732): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,W/PCWCLIENTTRACE_AccountUtil( 5120): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5120): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5120): ================================================
I/CSTORAGE( 5120):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 5120): ================================================
,D/dalvikvm( 5120): No JNI_OnLoad found in /system/lib/libterrier.so 0x425ff448, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5120): [GetString-S]
,I/terrier ( 5120): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5120): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5120): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5120): Loaded image: APP id = 4
,D/QSEECOMAPI: ( 5120): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5120): QSEECom_shutdown_app, app_id = 4
,E/terrier ( 5120): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5120): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5120): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5120): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5120): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5120): [ensureRegistration] - No Samsung account
,V/AlarmManager(  732): waitForAlarm result :4
,V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SMD     (  233): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/Finsky  ( 3668): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3668): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PreloadUpdateManagerStateMachine( 4180): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4180): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4180): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4180): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4180): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4180): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4180): entry::IDLE
,D/CaptivePortalTracker(  732): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  732): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  732): Checking http://216.58.209.46/generate_204
,E/SMD     (  233): DCD ON
,D/CaptivePortalTracker(  732): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  732): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  732): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  732): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  732): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/SSRMv2:SIOP(  732): SIOP:: AP = 310, Delta = -20
,D/PreloadUpdateManagerStateMachine( 4180): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4180): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4180): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4180): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4180): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4180): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4180): entry::IDLE
,E/Watchdog(  732): !@Sync 4
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  732): [PWL] Off : 75s ago
,D/AmoledAdjustTimer(  732): prevTemp = 298, currTemp = 301, prevStep = 4, currStep = 5
,E/SMD     (  233): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): stay LED for fully charged
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,V/AlarmManager(  732): waitForAlarm result :8
,E/SMD     (  233): DCD ON
,D/Headlines( 4089): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4089): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4089): Breath 18561 latestRequest time : 1449752970998 current time : 1449752989560
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = -10
,E/SMD     (  233): DCD ON
,D/dalvikvm(  732): GC_EXPLICIT freed 3105K, 58% free 23752K/55836K, paused 38ms+23ms, total 506ms
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 301, currTemp = 299, prevStep = 5, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1070): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 299, currTemp = 297, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  732): !@Sync 5
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  732): [PWL] Off : 105s ago
,D/AmoledAdjustTimer(  732): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :4
,V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4089): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4089): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4089): Breath 56699 latestRequest time : 1449752970998 current time : 1449753027697
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,I/PhenotypeConfigurator( 1219): Scheduling Phenotype for one-off execution 8366 seconds from now (1449753028633)
,D/GetConfigurationSnapshotOperation( 1219): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1219): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1219): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1219): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1219): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1219): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  732): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1219): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1219): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1219): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1219): Thread-107(HTTPLog):isShipBuild true
,I/System.out( 1219): Thread-107(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1219): GC_CONCURRENT freed 1569K, 38% free 11872K/18992K, paused 6ms+8ms, total 91ms
,D/LocationManagerService(  732): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 296, currTemp = 294, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  732): !@Sync 6
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  732): waitForAlarm result :8
,D/Headlines( 4089): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4089): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4089): Breath 78552 latestRequest time : 1449752970998 current time : 1449753049550
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  732): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1070): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,W/ProcessCpuTracker(  732): Skipping unknown process pid 5737
,D/AmoledAdjustTimer(  732): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  732): !@Sync 7
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  732): waitForAlarm result :8
,D/Headlines( 4089): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4089): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4089): Breath 108550 latestRequest time : 1449752970998 current time : 1449753079549
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  732): [PWL] Off : 180s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  732): !@Sync 8
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  732): waitForAlarm result :8
,D/Headlines( 4089): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4089): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4089): Breath 138548 latestRequest time : 1449752970998 current time : 1449753109548
,D/Headlines( 4089): stop 
,E/SMD     (  233): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/Headlines( 4089): Breath.onDestroy : 
,I/ActivityManager(  732): Killing 4398:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1070): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  732): !@Sync 9
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  732): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  732): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1070): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1070): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1070):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1070): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1070): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON

```
