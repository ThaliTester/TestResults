#### Test 50650278cc6513d_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5258): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5258):  
I/SELinux ( 5258):  
I/SELinux ( 5258): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5258): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5258): >>>>> Normal User
E/dalvikvm( 5258): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 5258): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5258): in addTimaSignatureService
D/TimaKeyStoreProvider( 5258): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5258): Added TimaKesytore provider
I/SELinux ( 5284): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5284):  
--------- beginning of /dev/log/system
I/ActivityManager(  787): Killing 4037:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  253): GC_EXPLICIT freed 45K, 50% free 9507K/18908K, paused 2ms+2ms, total 32ms
I/SELinux ( 5284): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5284):  
I/SELinux ( 5284):  
I/SELinux ( 5284): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5284): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5284): >>>>> Normal User
E/dalvikvm( 5284): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
D/dalvikvm(  253): GC_EXPLICIT freed <1K, 50% free 9507K/18908K, paused 1ms+3ms, total 17ms
E/SELinux ( 5284): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  253): GC_EXPLICIT freed <1K, 50% free 9507K/18908K, paused 3ms+3ms, total 20ms
D/TimaKeyStoreProvider( 5284): in addTimaSignatureService
D/TimaKeyStoreProvider( 5284): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5284): Added TimaKesytore provider
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=5284, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5284): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ActivityManager(  787): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5284): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/SA      ( 4110): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4110): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4110): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4413): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2180): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4763): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5310): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5310):  
D/dalvikvm( 2180): GC_CONCURRENT freed 1698K, 39% free 11608K/18908K, paused 4ms+2ms, total 60ms
D/dalvikvm( 2180): WAIT_FOR_CONCURRENT_GC blocked 26ms
I/SELinux ( 5310): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5310):  
I/SELinux ( 5310):  
I/SELinux ( 5310): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5310): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5310): >>>>> Normal User
E/dalvikvm( 5310): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5310): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/ActivityManager(  787): Killing 4053:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/TimaKeyStoreProvider( 5310): in addTimaSignatureService
D/TimaKeyStoreProvider( 5310): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5310): Added TimaKesytore provider
I/IcingCorporaProvider( 2180): UpdateCorporaTask done [took 135 ms] updated apps [took 135 ms] 
D/CapabilityManagerService New( 5310): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=5310, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5323): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5323):  
I/ActivityManager(  787): Killing 4345:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5323): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5323):  
I/SELinux ( 5323):  
I/SELinux ( 5323): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5323): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5323): >>>>> Normal User
E/dalvikvm( 5323): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5323): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5323): in addTimaSignatureService
D/TimaKeyStoreProvider( 5323): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5323): Added TimaKesytore provider
,W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=5323, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
D/AndroidRuntime( 5335): 
D/AndroidRuntime( 5335): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5335): CheckJNI is OFF
D/AndroidRuntime( 5335): setted country_code = Poland
D/AndroidRuntime( 5335): setted countryiso_code = PL
D/AndroidRuntime( 5335): setted sales_code = XEO
D/AndroidRuntime( 5335): readGMSProperty: start
D/AndroidRuntime( 5335): readGMSProperty: already setted!!
D/AndroidRuntime( 5335): readGMSProperty: end
D/AndroidRuntime( 5335): addProductProperty: start
D/dalvikvm( 5335): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5335): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5335): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5335): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5335): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 5356): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5356):  
I/ActivityManager(  787): Killing 4066:com.sec.android.soagent/u0a37 (adj 15): empty #43
W/GAV2    ( 5323): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5356): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5356):  
I/SELinux ( 5356):  
I/SELinux ( 5356): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5356): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5356): >>>>> Normal User
E/dalvikvm( 5356): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/memtrack( 5335): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5335): failed to load memtrack module: -2
E/SELinux ( 5356): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5356): in addTimaSignatureService
D/TimaKeyStoreProvider( 5356): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5356): Added TimaKesytore provider
D/dalvikvm( 5335): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/PackageIntentReceiver( 5356): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5356): Not GearManger package! 
I/SELinux ( 5376): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5376):  
D/AndroidRuntime( 5335): Calling main entry com.android.commands.am.Am
I/SELinux ( 5376): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5376):  
I/SELinux ( 5376):  
I/SELinux ( 5376): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5376): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5376): >>>>> Normal User
E/dalvikvm( 5376): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5376): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5376): in addTimaSignatureService
D/TimaKeyStoreProvider( 5376): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5376): Added TimaKesytore provider
V/ApplicationPolicy(  787): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  787): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  787): mDVFSHelper.acquire()
D/MagazineService Version( 5376): Magazine-Channel: 13
D/MagazineService Version( 5376): Magazine-Provider: 13
D/MagazineService Version( 5376): Magazine-Administrator: 11
I/SELinux ( 5390): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5390):  
D/AmoledAdjustTimer(  787): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
D/LockPatternUtils( 1065): isPcwEnable = null
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=5376, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/AndroidRuntime( 5335): Shutting down VM
D/HeadlinesChannelApplication( 5376): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5376): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
D/dalvikvm( 5335): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
I/MagazineService::MagazineService( 5376): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5395): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5395):  
D/MagazineService::MagazineService( 5376): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  787): Killing 4447:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
I/SELinux ( 5390): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5390):  
I/SELinux ( 5390):  
I/SELinux ( 5390): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5390): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5390): >>>>> Normal User
E/dalvikvm( 5390): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5390): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5390): in addTimaSignatureService
W/GAV2    ( 5323): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/TimaKeyStoreProvider( 5390): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5390): Added TimaKesytore provider
I/ActivityManager(  787): Killing 4463:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
I/SELinux ( 5395): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5395):  
I/SELinux ( 5395):  
I/SELinux ( 5395): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5395): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5395): >>>>> Normal User
E/dalvikvm( 5395): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5395): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/LockPatternUtils( 1065): isPcwEnable = null
D/TimaKeyStoreProvider( 5395): in addTimaSignatureService
D/TimaKeyStoreProvider( 5395): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5395): Added TimaKesytore provider
I/SurfaceFlinger(  247): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  247): id=13 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SQLiteSecureOpenHelper( 2132): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2132): getDatabaseLocked(b,b,pwd)...
D/SurfaceWidgetView( 1261): destroyHardwareResources():1130487088
I/SurfaceFlinger(  247): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  247): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1454): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1261): onTrimMemory. Level: 20
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=5390, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=5390, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5390): Binding Chromium to the background looper Looper (main, tid 1) {426f00a8}
I/chromium( 5390): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5390): Initializing chromium process, renderers=0
,W/chromium( 5390): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5390): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5390): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5390): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5390): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5390): Remote Branch: 
I/Adreno-EGL( 5390): Local Patches: 
I/Adreno-EGL( 5390): Reconstruct Branch: 
,I/dalvikvm( 5390): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 5390): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5390): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5390): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5390): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5390): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5390): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5390): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5390): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5390): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5390): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5390): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5390): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5390): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 5390): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5390): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5390): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5390): VFY: replacing opcode 0x6e at 0x0000
,I/SELinux ( 5432): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5432):  
,D/SystemWebViewEngine( 5390): CordovaWebView is running on device made by: samsung
I/ActivityManager(  787): Killing 4476:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5432): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5432):  
I/SELinux ( 5432):  
,I/SELinux ( 5432): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5432): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5432): >>>>> Normal User
,E/dalvikvm( 5432): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5432): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5432): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5432): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5432): Added TimaKesytore provider
,I/SurfaceFlinger(  247): id=17 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5390): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 5390): Enabling debug mode 0
,W/AwContents( 5390): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=5432, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 5432): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5455): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5455):  
,I/ActivityManager(  787): Killing 3623:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/CustomFrequencyManagerService(  787): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  tag : ACTIVITY_RESUME_BOOSTER@5
,E/SMD     (  241): DCD ON
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  787): mDVFSHelper.release()
D/CustomFrequencyManagerService(  787): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  pkgName : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 5455): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5455):  
I/SELinux ( 5455):  
,I/SELinux ( 5455): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5455): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5455): >>>>> Normal User
,E/dalvikvm( 5455): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5455): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5455): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5455): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5455): Added TimaKesytore provider
,I/ActivityManager(  787): Killing 4503:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/PackageBroadcastService( 1750): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1750): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1750): Module APK com.google.android.play.games already loaded
,D/JsMessageQueue( 5390): Set native->JS mode to OnlineEventsBridgeMode
,D/ChimeraCfgMgr( 1750): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1750): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1750): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1750): Submit a task: h
,D/ChimeraCfgMgr( 1750): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/dalvikvm( 5390): Trying to load lib /data/app-lib/com.test.thalitest-13/libjxcore.so 0x42a16de0
,D/ChimeraCfgMgr( 1750): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/h       ( 1750): Processing package: com.test.thalitest
,D/dalvikvm( 5390): Added shared lib /data/app-lib/com.test.thalitest-13/libjxcore.so 0x42a16de0
D/jxcore_app_log( 5390): JniHelper::setJavaVM(0x41c634f8), pthread_self() = 1942836592
,D/JX-Cordova( 5390): jxcore cordova android initializing
,I/dalvikvm( 5390): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
,W/dalvikvm( 5390): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5390): VFY: replacing opcode 0x6e at 0x0045
,I/PeopleContactsSync( 1750): CP2 sync disabled
,D/Finsky  ( 3790): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/dalvikvm( 1750): GC_CONCURRENT freed 1920K, 38% free 11864K/18908K, paused 7ms+5ms, total 143ms
,D/dalvikvm( 1750): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/dalvikvm( 1750): WAIT_FOR_CONCURRENT_GC blocked 35ms
D/dalvikvm( 1750): WAIT_FOR_CONCURRENT_GC blocked 35ms
,W/SQLiteConnectionPool( 1750): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/GassUtils( 1750): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/h       ( 1750): Found info for package com.test.thalitest in db.
I/dalvikvm( 1750): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1750): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1750): VFY: replacing opcode 0x6e at 0x000e
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,D/dalvikvm( 1320): GC_EXPLICIT freed 893K, 42% free 11060K/18908K, paused 5ms+5ms, total 58ms
,D/dalvikvm( 5390): GC_CONCURRENT freed 4929K, 33% free 12758K/18908K, paused 1ms+2ms, total 32ms
,D/dalvikvm( 5390): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/CustomFrequencyManagerService(  787): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  tag : ACTIVITY_RESUME_BOOSTER@9
,D/dalvikvm( 5390): GC_FOR_ALLOC freed 4697K, 28% free 15765K/21704K, paused 33ms, total 34ms
,D/dalvikvm( 5390): GC_FOR_ALLOC freed 5046K, 32% free 16772K/24376K, paused 34ms, total 36ms
,I/dalvikvm-heap( 5390): Grow heap (frag case) to 21.914MB for 2459024-byte allocation
,D/dalvikvm( 5390): GC_FOR_ALLOC freed 3768K, 35% free 17453K/26780K, paused 33ms, total 33ms
,D/dalvikvm( 5390): GC_FOR_ALLOC freed 1222K, 36% free 17358K/26780K, paused 28ms, total 28ms
,W/jxcore-log( 5390): Initializing JXcore engine
,W/jxcore-log( 5390): JXcore engine is ready
,W/jxcore-log( 5390): Starting JXcore engine
,W/jxcore-log( 5390): Platform android
W/jxcore-log( 5390): 
,W/jxcore-log( 5390): Process ARCH arm
W/jxcore-log( 5390): 
,E/SMD     (  241): DCD ON
,I/jxcore-log( 5390): JXcore Cordova bridge is ready!
I/jxcore-log( 5390): 
,W/jxcore-log( 5390): JXcore engine is started
,I/chromium( 5390): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 5390): Error!: missing ) after argument list
E/jxcore  ( 5390): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5390): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1065): isPcwEnable = null
I/ActivityManager(  787): Killing 4521:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,V/AlarmManager(  787): waitForAlarm result :4
,V/AlarmManager(  787): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/CustomFrequencyManagerService(  787): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  pkgName : ACTIVITY_RESUME_BOOSTER@5
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  787): mDVFSHelper.acquire()
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=17 Removed NainActivit (7/11)
,I/SurfaceFlinger(  247): id=17 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetView( 1261): destroyHardwareResources():1130487088
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/Headlines( 4168): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1261): onRestart, Launcher: 1118550120
D/Launcher( 1261): onStart, Launcher: 1118550120
,D/Launcher.HomeView( 1261): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1454): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1454): [237392/5] SurfaceWidget drawing first frame
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1955): Disconnected process message: 10
D/Headlines( 4168): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4168): Breath 68243 latestRequest time : 1449586571772 current time : 1449586640015
,I/SurfaceFlinger(  247): id=18 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,I/SurfaceFlinger(  247): id=19 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Launcher.HomeView( 1261): onStop
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  787): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  787): mDVFSHelper.release()
D/CustomFrequencyManagerService(  787): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  pkgName : ACTIVITY_RESUME_BOOSTER@9
,I/VacuumService( 1320): Vacuum at: now=1449586640171 tag=VacuumService
,D/FactoryTest( 4829): Not factory mode
,D/FactoryTest( 4829): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4829): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4829): still no open session command from host, so toast
W/ContextImpl( 4829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  787): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/CustomFrequencyManagerService(  787): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  787): mDVFSHelper.acquire()
,D/LockPatternUtils( 1065): isPcwEnable = null
,I/SQLiteSecureOpenHelper( 2132): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2132): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1065): isPcwEnable = null
,E/MTPRx   ( 4829): started activity for popup
,E/SettingsReceiverActivity( 4829): PREF_DONT_ASK_AGAIN : false
,D/SettingsReceiverActivity( 4829): dev.kiessupport is : TRUE
,I/GAV2    ( 5323): Thread[GAThread,5,main]: No campaign data found.
,I/SurfaceFlinger(  247): id=20 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4829): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4829): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4829): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4829): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4829): Remote Branch: 
I/Adreno-EGL( 4829): Local Patches: 
I/Adreno-EGL( 4829): Reconstruct Branch: 
,I/HWUI    ( 4829): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4829): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  787): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  tag : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  787): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/CustomFrequencyManagerService(  787): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,D/CustomFrequencyManagerService(  787): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  tag : ACTIVITY_RESUME_BOOSTER@5
D/CustomFrequencyManagerService(  787): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  787): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  787): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 787  tag : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 310, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 290, currTemp = 291, prevStep = 4, currStep = 4
,I/HarmonyEASService(  787): Updating for all 1
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
V/AlarmManager(  787): waitForAlarm result :4
V/AlarmManager(  787): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3790): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3790): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = -10
,E/Watchdog(  787): !@Sync 4
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService(  787): [PWL] Off : 75s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  787): waitForAlarm result :8
,D/Headlines( 4168): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4168): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4168): Breath 90043 latestRequest time : 1449586571772 current time : 1449586661815
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  787): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  787): waitForAlarm result :8
,V/AlarmManager(  787): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  787): !@Sync 5
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService(  787): [PWL] Off : 105s ago
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,V/AlarmManager(  787): waitForAlarm result :8
,D/Headlines( 4168): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4168): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4168): Breath 120035 latestRequest time : 1449586571772 current time : 1449586691809
,D/Headlines( 4168): stop 
,D/Headlines( 4168): Breath.onDestroy : 
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/BatteryService(  787): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm(  787): GC_EXPLICIT freed 3319K, 60% free 23688K/58544K, paused 18ms+21ms, total 508ms
,I/ActivityManager(  787): Killing 4544:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  787): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  787): !@Sync 6
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  787): [PWL] Off : 140s ago
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  787): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/BatteryService(  787): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  787): waitForAlarm result :8
,V/AlarmManager(  787): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/BatteryService(  787): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  787): !@Sync 7
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  787): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  787): [PWL] Off : 180s ago
,E/SMD     (  241): DCD ON
D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/BatteryService(  787): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  787): !@Sync 8
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  787): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/BatteryService(  787): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  787): waitForAlarm result :8
,V/AlarmManager(  787): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  787): !@Sync 9
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService(  787): [PWL] Off : 225s ago
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  787): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/TimaService(  787): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  787): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  787): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  787): initializing...
,I/TLC_TIMA_PKM_initialize(  787): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  787): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  787): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  787): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  787): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  787): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  787): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  787): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  787): App is not loaded in QSEE
,D/QSEECOMAPI: (  787): Loaded image: APP id = 5
,I/TZ: qc_tlc_communication(  787): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  787): Trustlet response is completed
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  787): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  787): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  787): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  787): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  787): !@Sync 10
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  787): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager(  787): waitForAlarm result :4
,V/AlarmManager(  787): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5582): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5582):  
,I/PowerManagerService(  787): [PWL] Off : 275s ago
I/PowerManagerService(  787): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  787): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  787): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=787, ws=WorkSource{10075}) (elapsedTime=210)
,I/SELinux ( 5582): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5582):  
I/SELinux ( 5582):  
,I/SELinux ( 5582): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5582): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5582): >>>>> Normal User
,E/dalvikvm( 5582): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5582): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5582): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5582): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5582): Added TimaKesytore provider
,W/ActivityManager(  787): Permission Denial: getCurrentUser() from pid=5582, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  787): Killing 4563:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,V/AlarmManager(  787): waitForAlarm result :8
,V/AlarmManager(  787): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  787): !@Sync 11
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/BatteryService(  787): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  787): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  787): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/Watchdog(  787): !@Sync 12
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/BatteryService(  787): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  787): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  787): stay LED for fully charged
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  787): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  787): [PWL] Off : 330s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  787): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/BatteryService(  787): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  787): waitForAlarm result :8
,V/AlarmManager(  787): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  787): !@Sync 13
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  787): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  787): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  787): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  787): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  787): mCoverManager.getCoverState() : true
,D/BatteryService(  787): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1955): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1955): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON

```
