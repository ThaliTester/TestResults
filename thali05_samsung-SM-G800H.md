#### Test 539786637913587_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
W/System.err( 5193): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 5193): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 5193): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 5193): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 5193): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 5193): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 5193): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 5193): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 5193): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 5193): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:105)
W/System.err( 5193): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:89)
W/System.err( 5193): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 5193): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 5193): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5193): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 5193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5193): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 5193): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 5193): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 5193): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 5193): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 5193): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 5193): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 5193): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5193): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5193): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 5193): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 5193): 	... 21 more
D/GalaxyFinderApplication( 5193): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 5193): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 5215): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5215):  
--------- beginning of /dev/log/system
I/ActivityManager(  728): Killing 3596:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
I/SELinux ( 5215): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5215):  
I/SELinux ( 5215):  
I/SELinux ( 5215): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5215): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5215): >>>>> Normal User
E/dalvikvm( 5215): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 5215): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5215): in addTimaSignatureService
D/TimaKeyStoreProvider( 5215): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5215): Added TimaKesytore provider
I/SELinux ( 5232): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5232):  
I/ActivityManager(  728): Killing 3971:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  248): GC_EXPLICIT freed 46K, 50% free 9512K/18744K, paused 2ms+9ms, total 35ms
I/SELinux ( 5232): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5232):  
I/SELinux ( 5232):  
I/SELinux ( 5232): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5232): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5232): >>>>> Normal User
E/dalvikvm( 5232): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5232): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9512K/18744K, paused 1ms+3ms, total 20ms
D/TimaKeyStoreProvider( 5232): in addTimaSignatureService
D/TimaKeyStoreProvider( 5232): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5232): Added TimaKesytore provider
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9512K/18744K, paused 1ms+3ms, total 19ms
D/AmoledAdjustTimer(  728): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5232, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5232): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5232): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  728): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
I/SA      ( 4054): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4054): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4054): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4362): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2178): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4707): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5262): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5262):  
I/IcingCorporaProvider( 2178): UpdateCorporaTask done [took 84 ms] updated apps [took 83 ms] 
I/SELinux ( 5262): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5262):  
I/SELinux ( 5262):  
I/SELinux ( 5262): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5262): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5262): >>>>> Normal User
E/dalvikvm( 5262): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5262): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5262): in addTimaSignatureService
I/ActivityManager(  728): Killing 3983:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/TimaKeyStoreProvider( 5262): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5262): Added TimaKesytore provider
,D/CapabilityManagerService New( 5262): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5262, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5276): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5276):  
I/ActivityManager(  728): Killing 4284:com.sec.android.service.health/u0a16 (adj 15): empty #43
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
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5276, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
D/AndroidRuntime( 5286): 
D/AndroidRuntime( 5286): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5286): CheckJNI is OFF
D/AndroidRuntime( 5286): setted country_code = Poland
D/AndroidRuntime( 5286): setted countryiso_code = PL
D/AndroidRuntime( 5286): setted sales_code = XEO
D/AndroidRuntime( 5286): readGMSProperty: start
D/AndroidRuntime( 5286): readGMSProperty: already setted!!
D/AndroidRuntime( 5286): readGMSProperty: end
D/AndroidRuntime( 5286): addProductProperty: start
D/dalvikvm( 5286): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5286): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5286): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5286): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5286): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5286): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5286): failed to load memtrack module: -2
D/dalvikvm( 5286): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 5304): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5304):  
I/ActivityManager(  728): Killing 3996:com.sec.android.soagent/u0a37 (adj 15): empty #43
I/SELinux ( 5304): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5304):  
I/SELinux ( 5304):  
I/SELinux ( 5304): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5304): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5304): >>>>> Normal User
E/dalvikvm( 5304): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
D/AndroidRuntime( 5286): Calling main entry com.android.commands.am.Am
E/SELinux ( 5304): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/GAV2    ( 5276): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/TimaKeyStoreProvider( 5304): in addTimaSignatureService
D/TimaKeyStoreProvider( 5304): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5304): Added TimaKesytore provider
D/PackageIntentReceiver( 5304): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5304): Not GearManger package! 
I/SELinux ( 5330): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5330):  
V/ApplicationPolicy(  728): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  728): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 728  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  728): mDVFSHelper.acquire()
I/SELinux ( 5334): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5334):  
I/SELinux ( 5330): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5330):  
I/SELinux ( 5330):  
I/SELinux ( 5330): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5330): >>>>> Normal User
E/dalvikvm( 5330): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
D/LockPatternUtils( 1066): isPcwEnable = null
D/AndroidRuntime( 5286): Shutting down VM
E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm( 5286): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
D/TimaKeyStoreProvider( 5330): in addTimaSignatureService
D/TimaKeyStoreProvider( 5330): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5330): Added TimaKesytore provider
I/SELinux ( 5334): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5334):  
I/SELinux ( 5334):  
I/SELinux ( 5334): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5334): >>>>> Normal User
E/dalvikvm( 5334): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (8/12)
D/SurfaceWidgetView( 1253): destroyHardwareResources():1130969280
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 5334): in addTimaSignatureService
D/TimaKeyStoreProvider( 5334): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5334): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 2103): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2103): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtils( 1066): isPcwEnable = null
I/SurfaceFlinger(  247): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  247): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/MagazineService Version( 5330): Magazine-Channel: 13
D/Launcher( 1253): onTrimMemory. Level: 20
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1445): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/MagazineService Version( 5330): Magazine-Provider: 13
D/MagazineService Version( 5330): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5330): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5330): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5330, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5330): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5356): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5356):  
D/MagazineService::MagazineService( 5330): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  728): Killing 1333:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5334, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5334, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5356): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5356):  
I/SELinux ( 5356):  
I/SELinux ( 5356): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5356): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5356): >>>>> Normal User
E/dalvikvm( 5356): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5356): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/WebViewChromium( 5334): Binding Chromium to the background looper Looper (main, tid 1) {42766090}
I/chromium( 5334): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5334): Initializing chromium process, renderers=0
D/TimaKeyStoreProvider( 5356): in addTimaSignatureService
W/chromium( 5334): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/TimaKeyStoreProvider( 5356): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5356): Added TimaKesytore provider
I/Adreno-EGL( 5334): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5334): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5334): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5334): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5334): Remote Branch: 
I/Adreno-EGL( 5334): Local Patches: 
I/Adreno-EGL( 5334): Reconstruct Branch: 
,E/SMD     (  241): DCD ON
I/dalvikvm( 5334): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5334): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5334): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5334): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5334): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5334): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5334): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5334): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5334): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5334): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5334): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5334): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5334): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5334): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5334): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5334): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5334): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5334): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5334): CordovaWebView is running on device made by: samsung
I/SELinux ( 5383): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5383):  
I/ActivityManager(  728): Killing 4402:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
I/SELinux ( 5383): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5383):  
I/SELinux ( 5383):  
I/SELinux ( 5383): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
W/GAV2    ( 5276): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/SELinux ( 5383): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5383): >>>>> Normal User
E/dalvikvm( 5383): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 5383): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager(  728): Killing 4417:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
I/SurfaceFlinger(  247): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 5383): in addTimaSignatureService
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 5383): Cannot add TimaSignature Service, License check Failed
I/HWUI    ( 5334): EGLImpl-HWUI Protected EGL context created
D/ActivityThread( 5383): Added TimaKesytore provider
D/OpenGLRenderer( 5334): Enabling debug mode 0
W/AwContents( 5334): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5383, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 5383): Package not found : com.sec.android.app.kidshome
D/CustomFrequencyManagerService(  728): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 728  tag : ACTIVITY_RESUME_BOOSTER@5
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  728): mDVFSHelper.release()
D/CustomFrequencyManagerService(  728): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 728  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 5406): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5406):  
I/ActivityManager(  728): Killing 4429:com.sec.esdk.elm/u0a94 (adj 15): empty #43
I/SELinux ( 5406): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5406):  
I/SELinux ( 5406):  
I/SELinux ( 5406): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5406): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5406): >>>>> Normal User
E/dalvikvm( 5406): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
E/SELinux ( 5406): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5406): in addTimaSignatureService
D/TimaKeyStoreProvider( 5406): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5406): Added TimaKesytore provider
I/ActivityManager(  728): Killing 3579:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
D/Finsky  ( 3684): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/ChimeraCfgMgr( 1755): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1755): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 1755): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/dalvikvm( 1755): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1755): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x0053
D/JsMessageQueue( 5334): Set native->JS mode to OnlineEventsBridgeMode
I/dalvikvm( 1755): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1755): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1755): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1755): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1755): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1755): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1755): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1755): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/dalvikvm( 5334): Trying to load lib /data/app-lib/com.test.thalitest-59/libjxcore.so 0x42a8cd90
,D/dalvikvm( 5334): Added shared lib /data/app-lib/com.test.thalitest-59/libjxcore.so 0x42a8cd90
D/jxcore_app_log( 5334): JniHelper::setJavaVM(0x41d024f8), pthread_self() = 2033635288
,D/JX-Cordova( 5334): jxcore cordova android initializing
,D/dalvikvm( 1755): GC_CONCURRENT freed 1938K, 37% free 11876K/18744K, paused 6ms+13ms, total 113ms
,W/SQLiteConnectionPool( 1755): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ChimeraCfgMgr( 1755): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1755): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1755): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1755): Submit a task: k
,D/ChimeraCfgMgr( 1755): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/BaseAppContext( 1755): Using Auth Proxy for data requests.
,W/BaseAppContext( 1755): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1755): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1755): Processing package: com.test.thalitest
,D/GassUtils( 1755): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1755): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1755): Using Auth Proxy for data requests.
,W/BaseAppContext( 1755): Using Auth Proxy for data requests.
W/BaseAppContext( 1755): Using Auth Proxy for data requests.
W/BaseAppContext( 1755): Using Auth Proxy for data requests.
,W/BaseAppContext( 1755): Using Auth Proxy for data requests.
,W/dalvikvm( 1755): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1755): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1755): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x000e
,W/dalvikvm( 1755): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1755): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1755): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x000e
,I/dalvikvm( 1755): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1755): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1755): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1755): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1755): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1755): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1755): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1755): cleanUpNonGplusAccounts done.
,D/dalvikvm( 5334): GC_CONCURRENT freed 4914K, 32% free 12778K/18744K, paused 2ms+3ms, total 28ms
,D/dalvikvm( 5334): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/dalvikvm( 1755): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1755): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1755): Module APK com.google.android.play.games already loaded
,D/CustomFrequencyManagerService(  728): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 728  tag : ACTIVITY_RESUME_BOOSTER@9
,D/dalvikvm( 5334): GC_FOR_ALLOC freed 4730K, 27% free 15762K/21564K, paused 32ms, total 32ms
,D/dalvikvm( 5334): GC_FOR_ALLOC freed 5135K, 31% free 16793K/24292K, paused 38ms, total 42ms
,I/dalvikvm-heap( 5334): Grow heap (frag case) to 21.820MB for 2511452-byte allocation
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/Icing   ( 1755): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 1755): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/dalvikvm( 5334): GC_FOR_ALLOC freed 3809K, 35% free 17484K/26748K, paused 32ms, total 32ms
,D/dalvikvm( 5334): GC_FOR_ALLOC freed 1215K, 35% free 17419K/26748K, paused 29ms, total 30ms
,W/jxcore-log( 5334): Initializing JXcore engine
,W/jxcore-log( 5334): JXcore engine is ready
,W/jxcore-log( 5334): Starting JXcore engine
,W/jxcore-log( 5334): Platform android
W/jxcore-log( 5334): 
,W/jxcore-log( 5334): Process ARCH arm
W/jxcore-log( 5334): 
,I/PowerManagerService(  728): [PWL] Off : 50s ago
,E/SMD     (  241): DCD ON
,I/jxcore-log( 5334): JXcore Cordova bridge is ready!
I/jxcore-log( 5334): 
,W/jxcore-log( 5334): JXcore engine is started
,I/chromium( 5334): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5334): Toggling radios to true
I/jxcore-log( 5334): 
,D/BluetoothAdapter( 5334): enable(): BT is already enabled..!
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
I/WifiManager( 5334): packageName : com.test.thalitest
I/WifiManager( 5334): setWifiEnabled : true
,I/WifiService(  728): setWifiEnabled: true pid=5334, uid=10179
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5334, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  728): Failed getting userId using ActivityManagerNative
W/WifiService(  728): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5334, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  728): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  728): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  728): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  728): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  728): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  728): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService(  728): disconnect: pid=5334, uid=10179
I/jxcore-log( 5334): Radios toggled
I/jxcore-log( 5334): 
,I/wpa_supplicant( 1963): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  728): SIOP:: AP = 320, Delta = 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/wpa_supplicant( 1963): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1963): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1963): Cmd 35605 not handled
,E/wpa_supplicant( 1963): Cmd 35605 not handled
,I/wpa_supplicant( 1963): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/Tethering(  728): InitialState.processMessage what=4
I/wpa_supplicant( 1963): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1963): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1963): First Scan Start
,E/Tethering(  728): No numeric data
I/wpa_supplicant( 1963): Scan requested (ret=0) - scan timeout 30 seconds
,D/Tethering(  728): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
I/ConnectivityService(  728): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  728): performPollLocked(flags=0x1)
,W/Settings(  728): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,I/WifiStateMachine(  728): ignore requestNetworkTransitionWakelock airplane:true
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 45ms
D/WifiP2pService(  728): InactiveState{ what=143375 }
D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
I/wpa_supplicant( 1963): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1963): Skip scan - already scanning
D/ConnectivityService(  728): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  728): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  728): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  728): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  728): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  728): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService(  728): InactiveState{ what=143375 }
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
D/ConnectivityService(  728): Attempting to switch to mobile
D/ConnectivityService(  728): Attempting to switch to BLUETOOTH_TETHER
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
,D/STATUSBAR-IconMerger( 1066): checkOverflow(336), More:false, Req:false Child:2
,I/SELinux ( 5470): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5470):  
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,V/RouteController(  238): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  728): Error! unhandled message{ when=-48ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
,E/WifiStateMachine(  728): Error! unhandled message{ when=-49ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
E/WifiStateMachine(  728): Error! unhandled message{ when=-1ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip -6 rule del table 2 2>&1
,I/SELinux ( 5470): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5470):  
I/SELinux ( 5470):  
I/SELinux ( 5470): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5470): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5470): >>>>> Normal User
,E/dalvikvm( 5470): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5470): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,W/NetworkManagementService(  728): route cmd failed: 
W/NetworkManagementService(  728): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 route del src v6 2' failed with '400 38 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  728): '
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  728): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  728): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  728): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  728): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  238): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 5470): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5470): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5470): Added TimaKesytore provider
V/RouteController(  238): RTNETLINK answers: No such process
V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  728): android_net_utils_resetConnections in env=0x77e95ee8 clazz=0x6a400001 iface=wlan0 mask=0x3
D/ConnectivityService(  728): resetConnections(wlan0, 3)
,V/NativeCrypto( 1318): Read error: ssl=0x7c65d008: I/O error during system call, Connection timed out
,V/NativeCrypto( 1318): SSL shutdown failed: ssl=0x7c65d008: I/O error during system call, Broken pipe
,V/NetworkStats(  728): updateIfacesLocked()
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/ConnectivityService(  728): handleInetConditionChange: no active default network - ignore
,V/NetworkStats(  728): performPollLocked(flags=0x1)
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 17ms
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,I/System.out( 5470): Inside WakeupProvider
,I/System.out( 5470): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 5470): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5470): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5470): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/dalvikvm(  728): GC_EXPLICIT freed 3151K, 58% free 23899K/55640K, paused 7ms+15ms, total 135ms
,I/GAV2    ( 5276): Thread[GAThread,5,main]: No campaign data found.
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5470): initQueue()
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  728): Killing 4457:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,I/ApplicationPolicy(  728): updateDataUsageMap
,D/Tethering(  728): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  728): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  728): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/ConnectivityService(  728): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/LocSvc_java(  728): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  728): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  728): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1445): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=false
I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): noConnectivity : true
,I/SELinux ( 5502): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5502):  
,I/SELinux ( 5502): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5502):  
I/SELinux ( 5502):  
,I/SELinux ( 5502): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5502): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5502): >>>>> Normal User
,E/dalvikvm( 5502): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5502): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5502): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5502): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5502): Added TimaKesytore provider
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5502, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  728): Killing 4473:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/wpa_supplicant( 1963): nl80211: Received scan results (8 BSSes)
I/wpa_supplicant( 1963): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1963): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1963): Trying to associate with  'G700'
I/wpa_supplicant( 1963): Re-associate with C0.AA.48
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1963): Cmd 35609 not handled
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,I/SELinux ( 5516): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5516):  
,E/wpa_supplicant( 1963): Cmd 35605 not handled
I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1963): Associated with C0.AA.48
I/wpa_supplicant( 1963): freq(2412) increment count 2
I/wpa_supplicant( 1963): meet head of list.
I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1963): Cmd 35847 not handled
E/wpa_supplicant( 1963): Cmd 35848 not handled
,E/wpa_supplicant( 1963): Cmd 35605 not handled
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,D/dalvikvm(  248): GC_EXPLICIT freed 43K, 50% free 9512K/18744K, paused 2ms+3ms, total 30ms
I/wpa_supplicant( 1963): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1963): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative(  728): callSECApiVoid - ID [50]
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9512K/18744K, paused 2ms+2ms, total 20ms
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
I/SELinux ( 5516): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5516):  
I/SELinux ( 5516):  
,I/SELinux ( 5516): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5516): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5516): >>>>> Normal User
,E/dalvikvm( 5516): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5516): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9512K/18744K, paused 2ms+2ms, total 20ms
,E/Tethering(  728): No numeric data
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
,D/Tethering(  728): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
,I/ConnectivityService(  728): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
,D/TimaKeyStoreProvider( 5516): in addTimaSignatureService
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
V/NetworkStats(  728): performPollLocked(flags=0x1)
,D/TimaKeyStoreProvider( 5516): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5516): Added TimaKesytore provider
,D/WifiP2pService(  728): InactiveState{ what=143375 }
,D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 31ms
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5516, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  728): Killing 4498:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5529): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5529):  
,I/SELinux ( 5529): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5529):  
I/SELinux ( 5529):  
,I/SELinux ( 5529): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5529): >>>>> Normal User
,E/dalvikvm( 5529): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5529): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5529): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5529): Added TimaKesytore provider
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5529, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5529): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5529): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450442867385
,I/KLMS-2.3.201 : ( 5529): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/dhcpcd  ( 5541): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5541): bssid match
,I/ActivityManager(  728): Killing 4514:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5549): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5549):  
,I/SELinux ( 5549): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5549):  
I/SELinux ( 5549):  
,I/SELinux ( 5549): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5549): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5549): >>>>> Normal User
,E/dalvikvm( 5549): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5549): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5549): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5549): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5549): Added TimaKesytore provider
,D/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5549, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/SA      ( 4054): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4054): [BDLM] already registered in spp
I/SA      ( 4054): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4054): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4054): [OR] == isSIMCardReady false ==
,I/SA      ( 4054): [SCU] == networkStateCheck == false
,I/SA      ( 4054): [OR] onReceive END
I/ActivityManager(  728): Killing 4640:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SELinux ( 5566): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5566):  
,I/SELinux ( 5566): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5566):  
I/SELinux ( 5566):  
,I/SELinux ( 5566): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5566): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5566): >>>>> Normal User
,E/dalvikvm( 5566): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5566): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5566): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5566): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5566): Added TimaKesytore provider
,I/sCloudBackupApp( 5566): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5566): Other Intent
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/ActivityManager(  728): Killing 4654:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5595): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5595):  
,D/WifiP2pService(  728): InactiveState{ what=143375 }
,I/SELinux ( 5595): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5595):  
I/SELinux ( 5595):  
,I/SELinux ( 5595): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5595): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5595): >>>>> Normal User
,E/dalvikvm( 5595): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
E/SELinux ( 5595): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5595): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5595): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5595): Added TimaKesytore provider
,E/SMD     (  241): DCD ON
,D/WifiStateMachine(  728): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  728): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  728): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
,D/WifiStateMachine(  728): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  728): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  728): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  728): mBoosterFLAG : 2
,I/WifiTrafficPoller(  728): current booster mode : BTCoexMode
D/ConnectivityService(  728): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  728): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  728): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
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
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/ConnectivityService(  728): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/RouteController(  238): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5595, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  728): Killing 4676:com.android.providers.calendar/u0a44 (adj 15): empty #43
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,D/Headlines( 4124): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,V/RouteController(  238): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,D/HeadlinesChannelUtil( 4124): getCountryCode(): countryCode = PL
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4124): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4124): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4124): requestUpdateNewsWelcomeCard !!! no welcome card
,V/RouteController(  238): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,I/SELinux ( 5617): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5617):  
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,I/SELinux ( 5617): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5617):  
I/SELinux ( 5617):  
,I/SELinux ( 5617): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5617): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5617): >>>>> Normal User
,E/dalvikvm( 5617): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5617): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5617): in addTimaSignatureService
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): updateIfacesLocked()
V/NetworkStats(  728): performPollLocked(flags=0x1)
V/NetworkStats(  728): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/TimaKeyStoreProvider( 5617): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5617): Added TimaKesytore provider
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 19ms
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5617): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/GAV2    ( 5617): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 5617): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5617): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  228): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5617): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
W/Vold    (  228): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 5617): Binding Chromium to the main looper Looper (main, tid 1) {42765f08}
,I/chromium( 5617): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5617): Initializing chromium process, renderers=0
,W/chromium( 5617): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5617): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5617): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5617): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5617): Remote Branch: 
I/Adreno-EGL( 5617): Local Patches: 
I/Adreno-EGL( 5617): Reconstruct Branch: 
,I/NSApplication( 5617): Starting up...
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5617, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  728): Killing 4725:com.google.android.talk/u0a105 (adj 15): empty #43
,I/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3351): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a98488
,I/SELinux ( 5657): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5657):  
,I/SELinux ( 5657): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5657):  
I/SELinux ( 5657):  
,I/SELinux ( 5657): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5657): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5657): >>>>> Normal User
,E/dalvikvm( 5657): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5657): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5657): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5657): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5657): Added TimaKesytore provider
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
D/Tethering(  728): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  728): MasterInitialState.processMessage what=3
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/CaptivePortalTracker(  728): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/LocSvc_java(  728): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  728): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  728): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/accuweather( 1445): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=true
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,I/ActivityManager(  728): Killing 3027:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,I/SELinux ( 5678): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5678):  
,I/SELinux ( 5682): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5682):  
W/ActivityManager(  728): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5678): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5678):  
I/SELinux ( 5678):  
,I/SELinux ( 5678): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5678): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5678): >>>>> Normal User
,E/dalvikvm( 5678): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5678): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5678): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5678): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5678): Added TimaKesytore provider
I/SELinux ( 5682): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5682):  
I/SELinux ( 5682):  
,I/SELinux ( 5682): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5682): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5682): >>>>> Normal User
,E/dalvikvm( 5682): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5682): [DEBUG] seapp_context_lookup: seinfoCategory = shared
I/ActivityManager(  728): Killing 4809:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5682): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5682): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5682): Added TimaKesytore provider
,D/BadgeProvider( 5678): onCreate
,D/BadgeProvider( 5678): DatabaseHelper
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5678, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5682, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5678): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 1253): reloadBadges entered.
D/BadgeProvider( 5678): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5678): sendNotify, [notify] : null
D/BadgeProvider( 5678): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5678): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5678): update, [UpdateCount] : 1
,D/hcjo    ( 4216): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4216): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4216): exit::IDLE
,D/InitializeManagerStateMachine( 4216): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4216): execute::NETWORK_CHECK:NETWORK_STATE_OK
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
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1303):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1303): showing allowed
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  247): id=18 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  728): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=728
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/KLMS-2.3.201 : ( 5529): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5529): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450442869247
,I/KLMS-2.3.201 : ( 5529): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/LocationTagReadyService( 2550): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
,D/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 5705): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5705):  
,I/GallerySearchProvider( 2339): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5705): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5705):  
I/SELinux ( 5705):  
,I/SELinux ( 5705): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5705): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5705): >>>>> Normal User
,E/dalvikvm( 5705): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5705): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 5715): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5715):  
,D/TimaKeyStoreProvider( 5705): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5705): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5705): Added TimaKesytore provider
,I/SELinux ( 5715): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5715):  
I/SELinux ( 5715):  
,I/SELinux ( 5715): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5715): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5715): >>>>> Normal User
,E/dalvikvm( 5715): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5715): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5715): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5715): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5715): Added TimaKesytore provider
,I/jxcore-log( 5334): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5334): 
,I/jxcore-log( 5334): my name is : samsung-SM-G800H_PT2470
I/jxcore-log( 5334): 
,V/KVNProvider( 5715): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5715): getFindoCursor query string : 
,V/KVNProvider( 5715): getTagSearchCursor() tagSearchCursor count : 0
,I/ActivityManager(  728): Killing 4829:com.wssyncmldm/1000 (adj 15): empty #43
,I/jxcore-log( 5334): attempting to connect to test coordinator
I/jxcore-log( 5334): 
,I/jxcore-log( 5334): check test folder
I/jxcore-log( 5334): 
,I/jxcore-log( 5334): found test : ./testFindPeers.js
I/jxcore-log( 5334): 
,I/SA      ( 4054): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4054): [BDLM] already registered in spp
I/SA      ( 4054): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4054): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4054): [OR] == isSIMCardReady false ==
,I/SA      ( 4054): [SCU] == networkStateCheck == true
I/SA      ( 4054): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4054): isChinaCountryCode : false
,I/SA      ( 4054): [OR] == networkStateCheck true ==
,I/SA      ( 4054): [OR] GetMyCountryZoneTask
,I/SA      ( 4054): [OR] onReceive END
I/ActivityManager(  728): Killing 4680:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/jxcore-log( 5334): found test : ./testReConnect.js
I/jxcore-log( 5334): 
,I/SCloudBackupReceiver( 5566): Other Intent
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      ( 4054): [SRS] prepareGetMyCountryZone
,I/jxcore-log( 5334): found test : ./testSendData.js
I/jxcore-log( 5334): 
,I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4054): [SSP] query invoked
,D/Headlines( 4124): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4124): getCountryCode(): countryCode = PL
D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4124): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4124): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4124): requestUpdateNewsWelcomeCard !!! no welcome card
I/SA      ( 4054): [TPMU] GetMccFromDB : null
,I/SA      ( 4054): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4054): [TPM] isNoProxy(default) : true
,I/SA      ( 4054): [RC New] Execute method=[GET] start
,D/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3351): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a98488
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/hcjo    ( 4216): AutoUpdateManager:IDLE:execute
,I/jxcore-log( 5334): Test app app.js loaded
I/jxcore-log( 5334): 
,D/InitializeManagerStateMachine( 4216): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4216): exit::IDLE
,D/InitializeManagerStateMachine( 4216): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4216): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 4216): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4216): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4216): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4216): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4216): entry::SUCCESS
D/hcjo    ( 4216): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4216): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4216): exit::SUCCESS
,D/InitializeManagerStateMachine( 4216): entry::IDLE
,I/jxcore-log( 5334): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5334): 
,I/chromium( 5334): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/dalvikvm( 1755): GC_CONCURRENT freed 1623K, 36% free 12176K/18744K, paused 3ms+4ms, total 35ms
,I/SA      ( 4054): [RC New] [v2liruge] api execute + 677
,I/SA      ( 4054): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4054): AsyncTask #2 calls detatch()
,I/SA      ( 4054): [TPMU] getNetworkMcc : 
,I/SA      ( 4054): [SCU] saveMccToPreferece Start
,I/SA      ( 4054): [SCU] RegionMCC : 260
,I/SA      ( 4054): [SSP] query invoked
,I/SA      ( 4054): [TPMU] GetMccFromDB : null
I/SA      ( 4054): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4054): [SCU] saveMccToPreferece End
I/SA      ( 4054): [RC New] executeRequest [v2liruge] end. 695
I/SA      ( 4054): [RC New] Execute end
I/SA      ( 4054): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4054): [OR] GetMyCountryZoneTask Success
,D/AmoledAdjustTimer(  728): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/jxcore-log( 5334): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5334): 
,E/SMD     (  241): DCD ON
,W/WifiP2pStateTracker(  728): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  728): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  728):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  728): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  728): updateSourceRoutes : no source routing conditions
,E/WifiStateMachine(  728): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,V/AlarmManager(  728): waitForAlarm result :4
,V/AlarmManager(  728): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4124): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4124): Breath 2108 latestRequest time : 1450442869715 current time : 1450442871823
,I/VacuumService( 1216): Vacuum at: now=1450442871990 tag=VacuumService
,D/dalvikvm( 1318): GC_EXPLICIT freed 1407K, 43% free 10789K/18744K, paused 5ms+5ms, total 51ms
,I/PhenotypeConfigurator( 1216): Scheduling Phenotype for one-off execution 7388 seconds from now (1450442872293)
,D/GetConfigurationSnapshotOperation( 1216): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1216): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1216): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1216): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1216): Using platform SSLCertificateSocketFactory
,D/FactoryTest( 4775): Not factory mode
,D/FactoryTest( 4775): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4775): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4775): still no open session command from host, so toast
W/ContextImpl( 4775): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4775): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
V/ApplicationPolicy(  728): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  728): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 728  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  728): mDVFSHelper.acquire()
,D/LockPatternUtils( 1066): isPcwEnable = null
,I/SQLiteSecureOpenHelper( 2103): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2103): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1066): isPcwEnable = null
,E/MTPRx   ( 4775): started activity for popup
,D/dalvikvm(  728): GC_EXPLICIT freed 2820K, 58% free 23836K/55640K, paused 6ms+14ms, total 142ms
,E/SettingsReceiverActivity( 4775): PREF_DONT_ASK_AGAIN : false
,I/jxcore-log( 5334): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5334): 
,D/SettingsReceiverActivity( 4775): dev.kiessupport is : TRUE
,D/LocationManagerService(  728): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1216): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1216): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x003d
,I/SurfaceFlinger(  247): id=18 Removed Uoast (11/12)
,I/SurfaceFlinger(  247): id=18 Removed Uoast (-2/12)
,I/ActivityManager(  728): Killing 4248:com.android.calendar/u0a142 (adj 15): empty #43
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  728): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=728 (0x0)
D/PowerManagerService(  728): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=728, ws=WorkSource{1000}) (elapsedTime=3470)
,I/SurfaceFlinger(  247): id=19 createSurf (1x1),1 flag=4, TettingsRec
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4775): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4775): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4775): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4775): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4775): Remote Branch: 
I/Adreno-EGL( 4775): Local Patches: 
I/Adreno-EGL( 4775): Reconstruct Branch: 
,I/System.out( 1216): Thread-107(HTTPLog):isShipBuild true
,I/System.out( 1216): Thread-107(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/HWUI    ( 4775): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4775): Enabling debug mode 0
,I/HarmonyEASService(  728): Updating for all 1
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  728): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 728  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  728): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 728  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  728): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,W/ActivityManager(  728): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/dalvikvm( 1216): GC_CONCURRENT freed 1628K, 37% free 11862K/18744K, paused 5ms+5ms, total 51ms
,D/dalvikvm( 1216): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/LocationManagerService(  728): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/GAV2    ( 5617): Thread[GAThread,5,main]: No campaign data found.
,D/CustomFrequencyManagerService(  728): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 728  tag : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  241): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5175): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5175): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5175): ================================================
,I/CSTORAGE( 5175):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5175): ================================================
,D/dalvikvm( 5175): No JNI_OnLoad found in /system/lib/libterrier.so 0x42a92358, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5175): [GetString-S]
,I/terrier ( 5175): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5175): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5175): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5175): Loaded image: APP id = 3
,I/dalvikvm( 5334): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,D/QSEECOMAPI: ( 5175): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 5175): QSEECom_shutdown_app, app_id = 3
,W/dalvikvm( 5334): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5334): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 5334): Shutting down VM
,W/dalvikvm( 5334): threadid=1: thread exiting with uncaught exception (group=0x41d15da0)
,E/AndroidRuntime( 5334): FATAL EXCEPTION: main
E/AndroidRuntime( 5334): Process: com.test.thalitest, PID: 5334
E/AndroidRuntime( 5334): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 5334): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 5334): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 5334): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 5334): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 5334): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 5334): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 5334): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 5334): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 5334): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 5334): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5334): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5334): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5334): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 5334): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5334): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5334): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 5334): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 5334): 	at dalvik.system.NativeStart.main(Native Method)
,E/terrier ( 5175): com.sec.pcw.device: getString: failed to get string(-1)
,I/Process ( 5334): Sending signal. PID: 5334 SIG: 9
,D/CrashAnrDetector(  728): processName: com.test.thalitest
,D/CrashAnrDetector(  728): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/ActivityManager(  728): Process com.test.thalitest (pid 5334) (adj 1) has died.
,I/SurfaceFlinger(  247): id=17 Removed NainActivit (7/12)
,I/SurfaceFlinger(  247): id=17 Removed NainActivit (-2/12)
,I/WindowState(  728): WIN DEATH: Window{4351c4d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5175): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5175): [ensureRegistration] - No Samsung account
,I/SELinux ( 5799): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5799):  
,D/dalvikvm(  248): GC_EXPLICIT freed 43K, 50% free 9512K/18744K, paused 3ms+4ms, total 39ms
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9512K/18744K, paused 2ms+4ms, total 28ms
,I/SELinux ( 5799): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5799):  
I/SELinux ( 5799):  
,I/SELinux ( 5799): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5799): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5799): >>>>> Normal User
,E/dalvikvm( 5799): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
,E/SELinux ( 5799): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 50% free 9512K/18744K, paused 3ms+4ms, total 29ms
,D/TimaKeyStoreProvider( 5799): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5799): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5799): Added TimaKesytore provider
,D/InputDispatcher(  728): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  247): id=20 createSurf (720x1280),2 flag=404, TcreenshotS
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (241 us)
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5799, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5799, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,V/WebViewChromium( 5799): Binding Chromium to the background looper Looper (main, tid 1) {4276c090}
,I/chromium( 5799): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5799): Initializing chromium process, renderers=0
,W/chromium( 5799): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5799): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5799): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5799): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5799): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5799): Remote Branch: 
I/Adreno-EGL( 5799): Local Patches: 
I/Adreno-EGL( 5799): Reconstruct Branch: 
,I/dalvikvm( 5799): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5799): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5799): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5799): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5799): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5799): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5799): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5799): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5799): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5799): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5799): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5799): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5799): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5799): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 5799): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5799): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5799): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5799): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5799): CordovaWebView is running on device made by: samsung
,I/SurfaceFlinger(  247): id=21 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5799): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 5799): Enabling debug mode 0
,W/AwContents( 5799): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/WindowManager(  728): Screen frozen for +488ms due to Window{433601e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  247): id=22 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  247): id=23 createSurf (720x2560),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  247): id=24 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  247): id=25 createSurf (720x2560),-1 flag=20004, ClackSurfac
,D/InputDispatcher(  728): setInputDispatchMode: enabled=0, frozen=0
,D/SSRMv2:SIOP(  728): SIOP:: AP = 320, Delta = 0
,I/SurfaceFlinger(  247): id=20 Removed TcreenshotS (12/17)
,I/SurfaceFlinger(  247): id=20 Removed TcreenshotS (-2/17)
,I/SurfaceFlinger(  247): id=22 Removed ClackSurfac (12/16)
I/SurfaceFlinger(  247): id=22 Removed ClackSurfac (-2/16)
,I/SurfaceFlinger(  247): id=23 Removed ClackSurfac (12/15)
I/SurfaceFlinger(  247): id=23 Removed ClackSurfac (-2/15)
,I/SurfaceFlinger(  247): id=24 Removed ClackSurfac (12/14)
I/SurfaceFlinger(  247): id=24 Removed ClackSurfac (-2/14)
I/SurfaceFlinger(  247): id=25 Removed ClackSurfac (12/13)
,I/SurfaceFlinger(  247): id=25 Removed ClackSurfac (-2/13)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
V/WindowManager(  728): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/JsMessageQueue( 5799): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 5799): Trying to load lib /data/app-lib/com.test.thalitest-59/libjxcore.so 0x42a92db8
,D/dalvikvm( 5799): Added shared lib /data/app-lib/com.test.thalitest-59/libjxcore.so 0x42a92db8
,D/jxcore_app_log( 5799): JniHelper::setJavaVM(0x41d024f8), pthread_self() = 2033635888
,D/JX-Cordova( 5799): jxcore cordova android initializing
,D/dalvikvm( 5799): GC_CONCURRENT freed 4925K, 32% free 12768K/18744K, paused 4ms+4ms, total 48ms
,D/dalvikvm( 5799): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 5799): WAIT_FOR_CONCURRENT_GC blocked 26ms
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :4
,V/AlarmManager(  728): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5799): GC_FOR_ALLOC freed 4780K, 28% free 15762K/21612K, paused 52ms, total 57ms
,D/dalvikvm(  728): GC_EXPLICIT freed 705K, 58% free 23723K/55640K, paused 9ms+18ms, total 198ms
,D/Finsky  ( 3684): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3684): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/dalvikvm( 5799): GC_FOR_ALLOC freed 5167K, 32% free 16793K/24340K, paused 44ms, total 46ms
,I/dalvikvm-heap( 5799): Grow heap (frag case) to 21.820MB for 2511452-byte allocation
,D/CaptivePortalTracker(  728): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  728): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  728): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  728): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  728): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  728): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  728): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  728): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm( 5799): GC_FOR_ALLOC freed 3812K, 35% free 17481K/26796K, paused 41ms, total 41ms
,D/PreloadUpdateManagerStateMachine( 4216): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 4216): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4216): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4216): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4216): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4216): entry::IDLE
,D/dalvikvm( 5799): GC_FOR_ALLOC freed 1272K, 36% free 17388K/26796K, paused 33ms, total 33ms
,W/jxcore-log( 5799): Initializing JXcore engine
,W/jxcore-log( 5799): JXcore engine is ready
,W/jxcore-log( 5799): Starting JXcore engine
,W/jxcore-log( 5799): Platform android
W/jxcore-log( 5799): 
,W/jxcore-log( 5799): Process ARCH arm
W/jxcore-log( 5799): 
,D/PreloadUpdateManagerStateMachine( 4216): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4216): exit::IDLE
D/PreloadUpdateManagerStateMachine( 4216): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4216): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 4216): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4216): entry::IDLE
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  728): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  728): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
V/AlarmManager(  728): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 5799): JXcore Cordova bridge is ready!
I/jxcore-log( 5799): 
,W/jxcore-log( 5799): JXcore engine is started
,I/chromium( 5799): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5799): Toggling radios to true
I/jxcore-log( 5799): 
,D/BluetoothAdapter( 5799): enable(): BT is already enabled..!
,I/WifiManager( 5799): packageName : com.test.thalitest
,I/WifiManager( 5799): setWifiEnabled : true
,I/WifiService(  728): setWifiEnabled: true pid=5799, uid=10179
,W/WifiService(  728): Failed getting userId using ActivityManagerNative
W/WifiService(  728): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5799, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  728): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  728): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  728): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  728): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  728): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  728): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  728): disconnect: pid=5799, uid=10179
,I/wpa_supplicant( 1963): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5799): Radios toggled
I/jxcore-log( 5799): 
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=5799, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 1963): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1963): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1963): Cmd 35605 not handled
,E/wpa_supplicant( 1963): Cmd 35605 not handled
,I/wpa_supplicant( 1963): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 1963): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1963): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1963): First Scan Start
I/wpa_supplicant( 1963): Scan requested (ret=0) - scan timeout 30 seconds
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/Tethering(  728): InitialState.processMessage what=4
E/Tethering(  728): No numeric data
,D/Tethering(  728): sendTetherStateChangedBroadcast 0, 0, 0
,W/Settings(  728): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  728): ignore requestNetworkTransitionWakelock airplane:true
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
I/ConnectivityService(  728): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  728): performPollLocked(flags=0x1)
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/WifiP2pService(  728): InactiveState{ what=143375 }
,D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
D/AmoledAdjustTimer(  728): prevTemp = 293, currTemp = 297, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
,D/CommandListener(  238): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 54ms
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
D/ConnectivityService(  728): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  728): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  728): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  728): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  728): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  728): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837934
D/ConnectivityService(  728): Attempting to switch to mobile
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/ConnectivityService(  728): Attempting to switch to BLUETOOTH_TETHER
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
,I/wpa_supplicant( 1963): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1963): Skip scan - already scanning
D/STATUSBAR-IconMerger( 1066): checkOverflow(336), More:false, Req:false Child:2
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,V/RouteController(  238): /system/bin/ip -6 route del default table 2 2>&1
D/WifiP2pService(  728): InactiveState{ what=143375 }
D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,W/NetworkManagementService(  728): route cmd failed: 
W/NetworkManagementService(  728): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '61 route del src v6 2' failed with '400 61 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  728): '
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  728): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  728): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  728): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  728): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  238): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  728): android_net_utils_resetConnections in env=0x77e95ee8 clazz=0xa4d00001 iface=wlan0 mask=0x3
,D/ConnectivityService(  728): resetConnections(wlan0, 3)
E/WifiStateMachine(  728): Error! unhandled message{ when=-134ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
,E/WifiStateMachine(  728): Error! unhandled message{ when=-135ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  728): Error! unhandled message{ when=-7ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,V/NetworkStats(  728): updateIfacesLocked()
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked(flags=0x1)
V/NetworkStats(  728): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 16ms
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,I/ApplicationPolicy(  728): updateDataUsageMap
,D/Tethering(  728): Tethering got CONNECTIVITY_ACTION
D/Tethering(  728): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  728): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  728): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/LocSvc_java(  728): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  728): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  728): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1445): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=false
I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): noConnectivity : true
,I/KLMS-2.3.201 : ( 5529): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5529): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450442881423
,I/KLMS-2.3.201 : ( 5529): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/wpa_supplicant( 1963): nl80211: Received scan results (10 BSSes)
I/wpa_supplicant( 1963): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1963): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1963): Trying to associate with  'G700'
,I/wpa_supplicant( 1963): Re-associate with C0.AA.48
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1963): Cmd 35609 not handled
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,I/SA      ( 4054): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4054): [BDLM] already registered in spp
I/SA      ( 4054): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4054): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4054): [OR] == isSIMCardReady false ==
I/SA      ( 4054): [SCU] == networkStateCheck == false
,I/SA      ( 4054): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5566): Other Intent
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4124): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4124): getCountryCode(): countryCode = PL
D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4124): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4124): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4124): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3351): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a98488
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,E/wpa_supplicant( 1963): Cmd 35605 not handled
E/wpa_supplicant( 1963): Cmd 35847 not handled
E/wpa_supplicant( 1963): Cmd 35848 not handled
E/wpa_supplicant( 1963): Cmd 35605 not handled
I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1963): Associated with C0.AA.48
I/wpa_supplicant( 1963): freq(2412) increment count 3
I/wpa_supplicant( 1963): meet head of list.
I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1963): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1963): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/Tethering(  728): No numeric data
,D/Tethering(  728): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiNative(  728): callSECApiVoid - ID [50]
I/ConnectivityService(  728): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
D/Tethering(  728): interfaceStatusChanged wlan0, true
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
V/NetworkStats(  728): performPollLocked(flags=0x1)
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 33ms
,I/iu.Environment( 1755): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
D/WifiP2pService(  728): InactiveState{ what=143375 }
D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
I/iu.UploadsManager( 1755): num queued entries: 0
I/iu.UploadsManager( 1755): num updated entries: 0
I/iu.SyncManager( 1755): NEXT; no task
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,I/dhcpcd  ( 5904): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5904): bssid match
,E/SMD     (  241): DCD ON
,D/WifiP2pService(  728): InactiveState{ what=143375 }
,D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/WifiStateMachine(  728): VerifyingLinkState enter
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  728): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  728): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
D/ConnectivityService(  728): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  728): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine(  728): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  728): mBoosterFLAG : 2
,I/WifiTrafficPoller(  728): current booster mode : BTCoexMode
D/ConnectivityService(  728): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  728): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  728): net.tcp.delack.wifi not found in system properties. Using defaults
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
,D/ConnectivityService(  728): handleConnectivityChange: setting default proxy info 
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,I/jxcore-log( 5799): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5799): 
,I/jxcore-log( 5799): my name is : samsung-SM-G800H_PT5304
I/jxcore-log( 5799): 
,D/Toast   ( 1303):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1303): showing allowed
V/RouteController(  238): RTNETLINK answers: No such file or directory
,V/RouteController(  238): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,I/SurfaceFlinger(  247): id=26 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,V/RouteController(  238): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
D/PowerManagerService(  728): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=728
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,I/jxcore-log( 5799): attempting to connect to test coordinator
I/jxcore-log( 5799): 
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,I/jxcore-log( 5799): check test folder
I/jxcore-log( 5799): 
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/jxcore-log( 5799): found test : ./testFindPeers.js
I/jxcore-log( 5799): 
,V/NetworkStats(  728): updateIfacesLocked()
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,V/NetworkStats(  728): performPollLocked(flags=0x1)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/jxcore-log( 5799): found test : ./testReConnect.js
I/jxcore-log( 5799): 
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 20ms
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,I/jxcore-log( 5799): found test : ./testSendData.js
I/jxcore-log( 5799): 
,I/jxcore-log( 5799): Test app app.js loaded
I/jxcore-log( 5799): 
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/chromium( 5799): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 5799): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5799): 
,D/Tethering(  728): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  728): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  728): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1445): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  728): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  728): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  728): ignore wifi update if we are not in OPENING or CLOSING
,I/KLMS-2.3.201 : ( 5529): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5529): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450442884412
,I/KLMS-2.3.201 : ( 5529): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2550): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
I/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 2339): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,V/KVNProvider( 5715): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5715): getFindoCursor query string : 
,V/KVNProvider( 5715): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4054): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4054): [BDLM] already registered in spp
I/SA      ( 4054): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4054): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4054): [OR] == isSIMCardReady false ==
I/SA      ( 4054): [SCU] == networkStateCheck == true
I/SA      ( 4054): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4054): isChinaCountryCode : false
I/SA      ( 4054): [OR] == networkStateCheck true ==
,I/SA      ( 4054): [OR] GetMyCountryZoneTask
I/SA      ( 4054): [OR] onReceive END
,I/SA      ( 4054): [SRS] prepareGetMyCountryZone
,I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4054): [SSP] query invoked
,I/SA      ( 4054): [TPMU] GetMccFromDB : null
I/SA      ( 4054): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4054): [TPM] isNoProxy(default) : true
,I/SA      ( 4054): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5566): Other Intent
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4124): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4124): getCountryCode(): countryCode = PL
D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4124): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4124): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4124): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3351): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a98488
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4216): notifyNetworkActivated
,D/hcjo    ( 4216): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4216): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4216): exit::IDLE
,D/InitializeManagerStateMachine( 4216): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4216): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4216): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4216): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4216): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4216): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4216): entry::SUCCESS
,D/hcjo    ( 4216): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4216): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4216): exit::SUCCESS
,D/InitializeManagerStateMachine( 4216): entry::IDLE
,I/iu.Environment( 1755): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1755): num queued entries: 0
,I/iu.UploadsManager( 1755): num updated entries: 0
,I/iu.SyncManager( 1755): NEXT; no task
,I/jxcore-log( 5799): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5799): 
,I/SA      ( 4054): [RC New] [v2liruge] api execute + 654
,I/SA      ( 4054): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4054): AsyncTask #3 calls detatch()
,I/SA      ( 4054): [TPMU] getNetworkMcc : 
,I/SA      ( 4054): [SCU] saveMccToPreferece Start
I/SA      ( 4054): [SCU] RegionMCC : 260
,I/SA      ( 4054): [SSP] query invoked
,I/SA      ( 4054): [TPMU] GetMccFromDB : null
,I/SA      ( 4054): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4054): [SCU] saveMccToPreferece End
,I/SA      ( 4054): [RC New] executeRequest [v2liruge] end. 671
I/SA      ( 4054): [RC New] Execute end
,I/SA      ( 4054): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4054): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService(  728): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/SSRMv2:SIOP(  728): SIOP:: AP = 320, Delta = 0
,E/SMD     (  241): DCD ON
,E/WifiStateMachine(  728): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/jxcore-log( 5799): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5799): 
,I/SurfaceFlinger(  247): id=26 Removed Uoast (12/13)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  728): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=728 (0x0)
,D/PowerManagerService(  728): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=728, ws=WorkSource{1000}) (elapsedTime=3525)
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/WifiP2pStateTracker(  728): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  728): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  728):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  728): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  728): updateSourceRoutes : no source routing conditions
,E/Watchdog(  728): !@Sync 4
,I/dalvikvm( 5799): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5799): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5799): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 5799): Shutting down VM
,W/dalvikvm( 5799): threadid=1: thread exiting with uncaught exception (group=0x41d15da0)
,E/AndroidRuntime( 5799): FATAL EXCEPTION: main
E/AndroidRuntime( 5799): Process: com.test.thalitest, PID: 5799
E/AndroidRuntime( 5799): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 5799): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 5799): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 5799): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 5799): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 5799): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 5799): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 5799): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 5799): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 5799): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 5799): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5799): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5799): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5799): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 5799): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5799): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5799): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 5799): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 5799): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 5799): Sending signal. PID: 5799 SIG: 9
,D/CrashAnrDetector(  728): processName: com.test.thalitest
,D/CrashAnrDetector(  728): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,E/SMD     (  241): DCD ON
,I/ActivityManager(  728): Process com.test.thalitest (pid 5799) (adj 1) has died.
,I/WindowState(  728): WIN DEATH: Window{433601e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  247): id=21 Removed NainActivit (7/12)
,I/SurfaceFlinger(  247): id=21 Removed NainActivit (-2/12)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 6000): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6000):  
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5175): [hasSamungAccount] - No Samsung Account
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5175): [GetString-S]
,I/terrier ( 5175): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 5175): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5175): App is not loaded in QSEE
,I/SELinux ( 6000): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6000):  
I/SELinux ( 6000):  
,I/SELinux ( 6000): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6000): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6000): >>>>> Normal User
,E/dalvikvm( 6000): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
,D/QSEECOMAPI: ( 5175): Loaded image: APP id = 3
,E/SELinux ( 6000): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/QSEECOMAPI: ( 5175): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5175): QSEECom_shutdown_app, app_id = 3
E/terrier ( 5175): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5175): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5175): [ensureRegistration] - No Samsung account
,D/TimaKeyStoreProvider( 6000): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6000): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6000): Added TimaKesytore provider
,D/InputDispatcher(  728): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  247): id=27 createSurf (720x1280),2 flag=404, TcreenshotS
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=6000, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=6000, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,V/WebViewChromium( 6000): Binding Chromium to the background looper Looper (main, tid 1) {42762390}
,I/chromium( 6000): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6000): Initializing chromium process, renderers=0
,W/chromium( 6000): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6000): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6000): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 6000): Build Date: 03/21/14 Fri
I/Adreno-EGL( 6000): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 6000): Remote Branch: 
I/Adreno-EGL( 6000): Local Patches: 
I/Adreno-EGL( 6000): Reconstruct Branch: 
,I/dalvikvm( 6000): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6000): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6000): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6000): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6000): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6000): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 6000): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6000): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6000): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6000): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 6000): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 6000): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6000): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6000): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 6000): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6000): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6000): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 6000): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 6000): CordovaWebView is running on device made by: samsung
,I/PowerManagerService(  728): [PWL] Off : 75s ago
I/PowerManagerService(  728): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  728): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  728): [PWL]       PARTIAL_WAKE_LOCK              'SCREEN_FROZEN' (uid=1000, pid=728, ws=null) (elapsedTime=317)
,I/SurfaceFlinger(  247): id=28 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 6000): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6000): Enabling debug mode 0
,W/AwContents( 6000): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=29 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  247): id=30 createSurf (720x2560),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  247): id=31 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  247): id=32 createSurf (720x2560),-1 flag=20004, ClackSurfac
,D/InputDispatcher(  728): setInputDispatchMode: enabled=0, frozen=0
I/WindowManager(  728): Screen frozen for +423ms due to Window{451df7e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/JsMessageQueue( 6000): Set native->JS mode to OnlineEventsBridgeMode
,I/SurfaceFlinger(  247): id=27 Removed TcreenshotS (12/17)
I/SurfaceFlinger(  247): id=29 Removed ClackSurfac (12/16)
,I/SurfaceFlinger(  247): id=27 Removed TcreenshotS (-2/16)
I/SurfaceFlinger(  247): id=30 Removed ClackSurfac (12/15)
I/SurfaceFlinger(  247): id=29 Removed ClackSurfac (-2/15)
I/SurfaceFlinger(  247): id=31 Removed ClackSurfac (12/14)
,I/SurfaceFlinger(  247): id=30 Removed ClackSurfac (-2/14)
I/SurfaceFlinger(  247): id=32 Removed ClackSurfac (12/13)
I/SurfaceFlinger(  247): id=31 Removed ClackSurfac (-2/13)
,I/SurfaceFlinger(  247): id=32 Removed ClackSurfac (-2/13)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
V/WindowManager(  728): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/dalvikvm( 6000): Trying to load lib /data/app-lib/com.test.thalitest-59/libjxcore.so 0x42a890b8
,D/dalvikvm( 6000): Added shared lib /data/app-lib/com.test.thalitest-59/libjxcore.so 0x42a890b8
,D/jxcore_app_log( 6000): JniHelper::setJavaVM(0x41d024f8), pthread_self() = 2033221000
,D/JX-Cordova( 6000): jxcore cordova android initializing
,D/AmoledAdjustTimer(  728): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/dalvikvm( 6000): GC_CONCURRENT freed 4895K, 32% free 12798K/18744K, paused 4ms+5ms, total 64ms
,D/dalvikvm( 6000): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 6000): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/dalvikvm( 6000): GC_FOR_ALLOC freed 4768K, 28% free 15761K/21596K, paused 51ms, total 51ms
,E/SMD     (  241): DCD ON
,D/dalvikvm(  728): GC_EXPLICIT freed 2176K, 58% free 23837K/55640K, paused 8ms+17ms, total 204ms
,D/dalvikvm( 6000): GC_FOR_ALLOC freed 5170K, 31% free 16792K/24324K, paused 44ms, total 44ms
,I/dalvikvm-heap( 6000): Grow heap (frag case) to 21.819MB for 2511452-byte allocation
,D/dalvikvm( 6000): GC_FOR_ALLOC freed 3812K, 35% free 17481K/26780K, paused 41ms, total 42ms
,D/dalvikvm( 6000): GC_FOR_ALLOC freed 1276K, 36% free 17388K/26780K, paused 36ms, total 38ms
,W/jxcore-log( 6000): Initializing JXcore engine
,W/jxcore-log( 6000): JXcore engine is ready
,W/jxcore-log( 6000): Starting JXcore engine
,W/jxcore-log( 6000): Platform android
W/jxcore-log( 6000): 
,W/jxcore-log( 6000): Process ARCH arm
W/jxcore-log( 6000): 
,D/CaptivePortalTracker(  728): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  728): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  728): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  728): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  728): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  728): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  728): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  728): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/AlarmManager(  728): waitForAlarm result :8
,D/Headlines( 4124): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4124): Breath 9900 latestRequest time : 1450442884536 current time : 1450442894436
,D/PreloadUpdateManagerStateMachine( 4216): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 4216): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4216): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4216): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 4216): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4216): entry::IDLE
,I/jxcore-log( 6000): JXcore Cordova bridge is ready!
I/jxcore-log( 6000): 
,W/jxcore-log( 6000): JXcore engine is started
,I/chromium( 6000): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6000): Toggling radios to true
I/jxcore-log( 6000): 
,E/SMD     (  241): DCD ON
,D/BluetoothAdapter( 6000): enable(): BT is already enabled..!
,I/WifiManager( 6000): packageName : com.test.thalitest
I/WifiManager( 6000): setWifiEnabled : true
,I/WifiService(  728): setWifiEnabled: true pid=6000, uid=10179
,W/WifiService(  728): Failed getting userId using ActivityManagerNative
W/WifiService(  728): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6000, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  728): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  728): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  728): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  728): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  728): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  728): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  728): disconnect: pid=6000, uid=10179
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=6000, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/jxcore-log( 6000): Radios toggled
I/jxcore-log( 6000): 
I/wpa_supplicant( 1963): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1963): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1963): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1963): Cmd 35605 not handled
,E/wpa_supplicant( 1963): Cmd 35605 not handled
,I/wpa_supplicant( 1963): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/Tethering(  728): InitialState.processMessage what=4
,E/Tethering(  728): No numeric data
,D/Tethering(  728): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
I/ConnectivityService(  728): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  728): performPollLocked(flags=0x1)
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
D/Tethering(  728): interfaceStatusChanged wlan0, false
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1963): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1963): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1963): First Scan Start
,I/wpa_supplicant( 1963): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings(  728): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  728): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService(  728): InactiveState{ what=143375 }
D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,V/NetworkStats(  728): performPollLocked() took 44ms
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
D/ConnectivityService(  728): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  728): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  728): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  728): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  728): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  728): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService(  728): Attempting to switch to mobile
D/ConnectivityService(  728): Attempting to switch to BLUETOOTH_TETHER
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
,I/wpa_supplicant( 1963): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1963): Skip scan - already scanning
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/STATUSBAR-IconMerger( 1066): checkOverflow(336), More:false, Req:false Child:2
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService(  728): InactiveState{ what=143375 }
,D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,V/RouteController(  238): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
E/WifiStateMachine(  728): Error! unhandled message{ when=-61ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  728): Error! unhandled message{ when=-61ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip -6 rule del table 2 2>&1
,E/WifiStateMachine(  728): Error! unhandled message{ when=-9ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,W/NetworkManagementService(  728): route cmd failed: 
W/NetworkManagementService(  728): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '86 route del src v6 2' failed with '400 86 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  728): '
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  728): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  728): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  728): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  728): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  238): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  728): android_net_utils_resetConnections in env=0x77e95ee8 clazz=0xe2400001 iface=wlan0 mask=0x3
D/ConnectivityService(  728): resetConnections(wlan0, 3)
,V/NativeCrypto( 1318): Read error: ssl=0x7c68cdf0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1318): SSL shutdown failed: ssl=0x7c68cdf0: I/O error during system call, Broken pipe
,V/NetworkStats(  728): updateIfacesLocked()
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked(flags=0x1)
V/NetworkStats(  728): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/ConnectivityService(  728): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,V/NetworkStats(  728): performPollLocked() took 17ms
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,I/ApplicationPolicy(  728): updateDataUsageMap
,D/Tethering(  728): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  728): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  728): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  728): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  728): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  728): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1445): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  728): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): noConnectivity : true
,I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=false
,D/SSRMv2:SIOP(  728): SIOP:: AP = 310, Delta = -10
,I/KLMS-2.3.201 : ( 5529): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5529): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450442895997
,I/KLMS-2.3.201 : ( 5529): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4054): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4054): [BDLM] already registered in spp
I/SA      ( 4054): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4054): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4054): [OR] == isSIMCardReady false ==
I/SA      ( 4054): [SCU] == networkStateCheck == false
,I/SA      ( 4054): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5566): Other Intent
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/wpa_supplicant( 1963): nl80211: Received scan results (11 BSSes)
,I/wpa_supplicant( 1963): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1963): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1963): Trying to associate with  'G700'
I/wpa_supplicant( 1963): Re-associate with C0.AA.48
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1963): Cmd 35609 not handled
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
D/Headlines( 4124): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4124): getCountryCode(): countryCode = PL
,D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4124): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4124): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4124): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3351): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a98488
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,I/iu.Environment( 1755): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1755): num queued entries: 0
,I/iu.UploadsManager( 1755): num updated entries: 0
,I/iu.SyncManager( 1755): NEXT; no task
,E/wpa_supplicant( 1963): Cmd 35605 not handled
E/wpa_supplicant( 1963): Cmd 35847 not handled
E/wpa_supplicant( 1963): Cmd 35848 not handled
,E/wpa_supplicant( 1963): Cmd 35605 not handled
I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1963): Associated with C0.AA.48
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1963): freq(2412) increment count 4
,I/wpa_supplicant( 1963): meet head of list.
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1963): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1963): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering(  728): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
D/Tethering(  728): interfaceStatusChanged wlan0, true
,E/Tethering(  728): No numeric data
,D/Tethering(  728): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
,D/WifiNative(  728): callSECApiVoid - ID [50]
,I/ConnectivityService(  728): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
D/Tethering(  728): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
V/NetworkStats(  728): performPollLocked(flags=0x1)
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/WifiP2pService(  728): InactiveState{ what=143375 }
,D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 32ms
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,I/dhcpcd  ( 6101): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6101): bssid match
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  728): stay LED for fully charged
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(336), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/jxcore-log( 6000): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 6000): 
,I/jxcore-log( 6000): my name is : samsung-SM-G800H_PT5694
I/jxcore-log( 6000): 
,I/jxcore-log( 6000): attempting to connect to test coordinator
I/jxcore-log( 6000): 
,I/jxcore-log( 6000): check test folder
I/jxcore-log( 6000): 
,I/jxcore-log( 6000): found test : ./testFindPeers.js
I/jxcore-log( 6000): 
,I/jxcore-log( 6000): found test : ./testReConnect.js
I/jxcore-log( 6000): 
,I/jxcore-log( 6000): found test : ./testSendData.js
I/jxcore-log( 6000): 
,I/jxcore-log( 6000): Test app app.js loaded
I/jxcore-log( 6000): 
,I/jxcore-log( 6000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6000): 
,I/chromium( 6000): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiP2pService(  728): InactiveState{ what=143375 }
,D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  728): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  728): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  728): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
,D/WifiStateMachine(  728): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  728): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  728): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  728): mBoosterFLAG : 2
,I/WifiTrafficPoller(  728): current booster mode : BTCoexMode
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
D/ConnectivityService(  728): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  728): net.tcp.usercfg.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService(  728): net.tcp.delack.wifi not found in system properties. Using defaults
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
,D/ConnectivityService(  728): handleConnectivityChange: setting default proxy info 
,V/RouteController(  238): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,V/RouteController(  238): RTNETLINK answers: No such file or directory
V/RouteController(  238): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,V/RouteController(  238): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/Toast   ( 1303):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1303): showing allowed
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/RouteController(  238): RTNETLINK answers: No such process
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,I/SurfaceFlinger(  247): id=33 createSurf (1x1),1 flag=4, Uoast
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,V/NetworkStats(  728): updateIfacesLocked()
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked(flags=0x1)
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/PowerManagerService(  728): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=728
V/NetworkStats(  728): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 16ms
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/jxcore-log( 6000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6000): 
,D/Tethering(  728): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  728): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  728): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1445): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  728): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  728): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  728): ignore wifi update if we are not in OPENING or CLOSING
,I/KLMS-2.3.201 : ( 5529): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5529): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450442899170
,I/KLMS-2.3.201 : ( 5529): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/LocationTagReadyService( 2550): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
,D/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2339): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,V/KVNProvider( 5715): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5715): getFindoCursor query string : 
,V/KVNProvider( 5715): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4054): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4054): [BDLM] already registered in spp
I/SA      ( 4054): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4054): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4054): [OR] == isSIMCardReady false ==
I/SA      ( 4054): [SCU] == networkStateCheck == true
I/SA      ( 4054): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4054): isChinaCountryCode : false
,I/SA      ( 4054): [OR] == networkStateCheck true ==
I/SA      ( 4054): [OR] GetMyCountryZoneTask
I/SA      ( 4054): [OR] onReceive END
,I/SA      ( 4054): [SRS] prepareGetMyCountryZone
,I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4054): [SSP] query invoked
I/SA      ( 4054): [TPMU] GetMccFromDB : null
I/SA      ( 4054): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4054): [TPM] isNoProxy(default) : true
,I/SA      ( 4054): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5566): Other Intent
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4124): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4124): getCountryCode(): countryCode = PL
D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4124): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4124): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4124): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3351): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a98488
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4216): notifyNetworkActivated
,D/hcjo    ( 4216): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4216): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4216): exit::IDLE
,D/InitializeManagerStateMachine( 4216): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4216): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4216): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4216): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4216): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4216): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4216): entry::SUCCESS
,D/hcjo    ( 4216): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4216): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4216): exit::SUCCESS
,D/InitializeManagerStateMachine( 4216): entry::IDLE
,I/iu.Environment( 1755): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1755): num queued entries: 0
,I/iu.UploadsManager( 1755): num updated entries: 0
,I/iu.SyncManager( 1755): NEXT; no task
,I/SA      ( 4054): [RC New] [v2liruge] api execute + 437
,I/SA      ( 4054): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4054): AsyncTask #4 calls detatch()
,I/SA      ( 4054): [TPMU] getNetworkMcc : 
,I/SA      ( 4054): [SCU] saveMccToPreferece Start
I/SA      ( 4054): [SCU] RegionMCC : 260
,I/SA      ( 4054): [SSP] query invoked
,I/SA      ( 4054): [TPMU] GetMccFromDB : null
I/SA      ( 4054): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4054): [SCU] saveMccToPreferece End
,I/SA      ( 4054): [RC New] executeRequest [v2liruge] end. 448
I/SA      ( 4054): [RC New] Execute end
I/SA      ( 4054): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4054): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService(  728): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/AmoledAdjustTimer(  728): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/WifiP2pStateTracker(  728): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  728): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  728):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  728): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  728): updateSourceRoutes : no source routing conditions
,I/jxcore-log( 6000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6000): 
,E/SMD     (  241): DCD ON
,E/WifiStateMachine(  728): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  247): id=33 Removed Uoast (12/13)
,I/SurfaceFlinger(  247): id=33 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  728): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=728 (0x0)
,D/PowerManagerService(  728): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=728, ws=WorkSource{1000}) (elapsedTime=3516)
,I/dalvikvm( 6000): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 6000): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6000): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 6000): Shutting down VM
,W/dalvikvm( 6000): threadid=1: thread exiting with uncaught exception (group=0x41d15da0)
,E/AndroidRuntime( 6000): FATAL EXCEPTION: main
E/AndroidRuntime( 6000): Process: com.test.thalitest, PID: 6000
E/AndroidRuntime( 6000): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 6000): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 6000): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 6000): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 6000): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 6000): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 6000): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 6000): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 6000): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 6000): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 6000): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 6000): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6000): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6000): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 6000): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 6000): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 6000): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 6000): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 6000): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 6000): Sending signal. PID: 6000 SIG: 9
,D/CrashAnrDetector(  728): processName: com.test.thalitest
,D/CrashAnrDetector(  728): broadcastEvent : com.test.thalitest data_app_crash
W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,W/InputDispatcher(  728): channel ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  728): channel ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  728): Attempted to unregister already unregistered input channel
I/ActivityManager(  728): Process com.test.thalitest (pid 6000) (adj 1) has died.
I/WindowState(  728): WIN DEATH: Window{451df7e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  247): id=28 Removed NainActivit (7/12)
,I/SurfaceFlinger(  247): id=28 Removed NainActivit (-2/12)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 6203): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6203):  
,I/SELinux ( 6203): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6203):  
I/SELinux ( 6203):  
,I/SELinux ( 6203): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6203): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 6203): >>>>> Normal User
,E/dalvikvm( 6203): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
,E/SELinux ( 6203): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6203): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6203): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6203): Added TimaKesytore provider
,D/InputDispatcher(  728): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  247): id=34 createSurf (720x1280),2 flag=404, TcreenshotS
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): mConnectivityHandler : connected
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=6203, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=6203, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/PCWCLIENTTRACE_AccountUtil( 5175): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5175): [GetString-S]
I/terrier ( 5175): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5175): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5175): App is not loaded in QSEE
,V/WebViewChromium( 6203): Binding Chromium to the background looper Looper (main, tid 1) {42763300}
,I/chromium( 6203): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6203): Initializing chromium process, renderers=0
,D/QSEECOMAPI: ( 5175): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5175): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5175): QSEECom_shutdown_app, app_id = 3
E/terrier ( 5175): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5175): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5175): [ensureRegistration] - No Samsung account
,W/chromium( 6203): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6203): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6203): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 6203): Build Date: 03/21/14 Fri
I/Adreno-EGL( 6203): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 6203): Remote Branch: 
I/Adreno-EGL( 6203): Local Patches: 
I/Adreno-EGL( 6203): Reconstruct Branch: 
,I/dalvikvm( 6203): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 6203): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6203): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6203): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
,W/dalvikvm( 6203): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6203): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 6203): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 6203): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6203): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6203): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 6203): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 6203): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,I/dalvikvm( 6203): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6203): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 6203): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6203): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
,W/dalvikvm( 6203): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 6203): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 6203): CordovaWebView is running on device made by: samsung
,I/SurfaceFlinger(  247): id=35 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 6203): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6203): Enabling debug mode 0
,W/AwContents( 6203): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/WindowManager(  728): Screen frozen for +624ms due to Window{44015590 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  247): id=36 createSurf (1440x1280),-1 flag=20004, ClackSurfac
I/SurfaceFlinger(  247): id=37 createSurf (720x2560),-1 flag=20004, ClackSurfac
I/SurfaceFlinger(  247): id=38 createSurf (1440x1280),-1 flag=20004, ClackSurfac
I/SurfaceFlinger(  247): id=39 createSurf (720x2560),-1 flag=20004, ClackSurfac
D/InputDispatcher(  728): setInputDispatchMode: enabled=0, frozen=0
,D/JsMessageQueue( 6203): Set native->JS mode to OnlineEventsBridgeMode
,I/SurfaceFlinger(  247): id=34 Removed TcreenshotS (12/17)
,I/SurfaceFlinger(  247): id=36 Removed ClackSurfac (12/16)
I/SurfaceFlinger(  247): id=34 Removed TcreenshotS (-2/16)
I/SurfaceFlinger(  247): id=37 Removed ClackSurfac (12/15)
I/SurfaceFlinger(  247): id=36 Removed ClackSurfac (-2/15)
I/SurfaceFlinger(  247): id=37 Removed ClackSurfac (-2/15)
,I/SurfaceFlinger(  247): id=38 Removed ClackSurfac (12/14)
I/SurfaceFlinger(  247): id=39 Removed ClackSurfac (12/13)
,I/SurfaceFlinger(  247): id=38 Removed ClackSurfac (-2/13)
,I/SurfaceFlinger(  247): id=39 Removed ClackSurfac (-2/13)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
V/WindowManager(  728): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/dalvikvm( 6203): Trying to load lib /data/app-lib/com.test.thalitest-59/libjxcore.so 0x42a8a028
,D/dalvikvm( 6203): Added shared lib /data/app-lib/com.test.thalitest-59/libjxcore.so 0x42a8a028
,D/jxcore_app_log( 6203): JniHelper::setJavaVM(0x41d024f8), pthread_self() = 2033224808
,D/JX-Cordova( 6203): jxcore cordova android initializing
,D/dalvikvm( 6203): GC_CONCURRENT freed 4896K, 32% free 12797K/18744K, paused 3ms+3ms, total 41ms
,D/dalvikvm( 6203): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 6203): GC_FOR_ALLOC freed 4749K, 27% free 15762K/21580K, paused 33ms, total 35ms
,D/SSRMv2:SIOP(  728): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 6203): GC_FOR_ALLOC freed 5159K, 31% free 16793K/24308K, paused 34ms, total 34ms
,I/dalvikvm-heap( 6203): Grow heap (frag case) to 21.820MB for 2511452-byte allocation
,D/dalvikvm(  728): GC_EXPLICIT freed 2229K, 58% free 23908K/55640K, paused 5ms+11ms, total 132ms
,D/dalvikvm( 6203): GC_FOR_ALLOC freed 3811K, 35% free 17482K/26764K, paused 32ms, total 32ms
,D/dalvikvm( 6203): GC_FOR_ALLOC freed 1271K, 36% free 17388K/26764K, paused 28ms, total 28ms
,W/jxcore-log( 6203): Initializing JXcore engine
,W/jxcore-log( 6203): JXcore engine is ready
,W/jxcore-log( 6203): Starting JXcore engine
,E/SMD     (  241): DCD ON
,W/jxcore-log( 6203): Platform android
W/jxcore-log( 6203): 
,W/jxcore-log( 6203): Process ARCH arm
W/jxcore-log( 6203): 
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  728): mCoverManager.getCoverState() : true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 6203): JXcore Cordova bridge is ready!
I/jxcore-log( 6203): 
,W/jxcore-log( 6203): JXcore engine is started
,I/chromium( 6203): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6203): Toggling radios to true
I/jxcore-log( 6203): 
,D/BluetoothAdapter( 6203): enable(): BT is already enabled..!
,I/WifiManager( 6203): packageName : com.test.thalitest
I/WifiManager( 6203): setWifiEnabled : true
,I/WifiService(  728): setWifiEnabled: true pid=6203, uid=10179
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=6203, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  728): Failed getting userId using ActivityManagerNative
W/WifiService(  728): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6203, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  728): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  728): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  728): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  728): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  728): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  728): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService(  728): disconnect: pid=6203, uid=10179
I/wpa_supplicant( 1963): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6203): Radios toggled
I/jxcore-log( 6203): 
,I/wpa_supplicant( 1963): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1963): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,E/wpa_supplicant( 1963): Cmd 35605 not handled
E/wpa_supplicant( 1963): Cmd 35605 not handled
,I/wpa_supplicant( 1963): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
D/Tethering(  728): InitialState.processMessage what=4
,E/Tethering(  728): No numeric data
,I/ConnectivityService(  728): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  728): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked(flags=0x1)
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1963): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1963): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1963): First Scan Start
I/wpa_supplicant( 1963): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,W/Settings(  728): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  728): ignore requestNetworkTransitionWakelock airplane:true
,D/WifiP2pService(  728): InactiveState{ what=143375 }
,D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
,V/NetworkStats(  728): performPollLocked() took 49ms
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/CommandListener(  238): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
D/ConnectivityService(  728): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  728): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  728): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  728): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  728): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  728): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService(  728): Attempting to switch to mobile
D/ConnectivityService(  728): Attempting to switch to BLUETOOTH_TETHER
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
,I/wpa_supplicant( 1963): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1963): Skip scan - already scanning
,D/STATUSBAR-IconMerger( 1066): checkOverflow(336), More:false, Req:false Child:2
D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
D/WifiP2pService(  728): InactiveState{ what=143375 }
,D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,V/RouteController(  238): /system/bin/ip -6 route del default table 2 2>&1
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,D/CommandListener(  238): Clearing all IP addresses on wlan0
,W/NetworkManagementService(  728): route cmd failed: 
W/NetworkManagementService(  728): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '109 route del src v6 2' failed with '400 109 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  728): '
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  728): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  728): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  728): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  728): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  728): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  728): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  238): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
E/WifiStateMachine(  728): Error! unhandled message{ when=-87ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  728): Error! unhandled message{ when=-86ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  728): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,D/NetUtils(  728): android_net_utils_resetConnections in env=0x77e95ee8 clazz=0x1f600001 iface=wlan0 mask=0x3
D/ConnectivityService(  728): resetConnections(wlan0, 3)
,V/NativeCrypto( 1318): Read error: ssl=0x7c68cdf0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1318): SSL shutdown failed: ssl=0x7c68cdf0: I/O error during system call, Broken pipe
,D/ConnectivityService(  728): handleInetConditionChange: no active default network - ignore
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): updateIfacesLocked()
V/NetworkStats(  728): performPollLocked(flags=0x1)
V/NetworkStats(  728): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 22ms
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/CaptivePortalTracker(  728): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  728): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  728): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  728): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  728): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/ConnectivityService(  728): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/ApplicationPolicy(  728): updateDataUsageMap
,D/Tethering(  728): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  728): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  728): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  728): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  728): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  728): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  728): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1445): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): noConnectivity : true
,D/dalvikvm( 3954): GC_CONCURRENT freed 7764K, 48% free 9928K/18744K, paused 3ms+2ms, total 48ms
,D/dalvikvm( 3954): WAIT_FOR_CONCURRENT_GC blocked 36ms
,I/KLMS-2.3.201 : ( 5529): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/wpa_supplicant( 1963): nl80211: Received scan results (11 BSSes)
I/wpa_supplicant( 1963): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1963): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1963): Trying to associate with  'G700'
I/wpa_supplicant( 1963): Re-associate with C0.AA.48
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1963): Cmd 35609 not handled
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
,I/KLMS-2.3.201 : ( 5529): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450442909330
,I/KLMS-2.3.201 : ( 5529): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/PreloadUpdateManagerStateMachine( 4216): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 4216): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4216): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4216): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
D/PreloadUpdateManagerStateMachine( 4216): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 4216): entry::IDLE
,I/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4054): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4054): [BDLM] already registered in spp
I/SA      ( 4054): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4054): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4054): [OR] == isSIMCardReady false ==
I/SA      ( 4054): [SCU] == networkStateCheck == false
,I/SA      ( 4054): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5566): Other Intent
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/wpa_supplicant( 1963): Cmd 35605 not handled
E/wpa_supplicant( 1963): Cmd 35847 not handled
E/wpa_supplicant( 1963): Cmd 35848 not handled
,E/wpa_supplicant( 1963): Cmd 35605 not handled
I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1963): Associated with C0.AA.48
I/wpa_supplicant( 1963): freq(2412) increment count 5
,I/wpa_supplicant( 1963): meet head of list.
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Headlines( 4124): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1963): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1963): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering(  728): interfaceLinkStateChanged wlan0, false
D/Tethering(  728): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1963): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
D/Tethering(  728): interfaceStatusChanged wlan0, false
,D/WifiNative(  728): callSECApiVoid - ID [50]
,D/HeadlinesChannelUtil( 4124): getCountryCode(): countryCode = PL
D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4124): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4124): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4124): requestUpdateNewsWelcomeCard !!! no welcome card
,D/Tethering(  728): interfaceLinkStateChanged wlan0, false
,D/Tethering(  728): interfaceStatusChanged wlan0, false
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
,E/Tethering(  728): No numeric data
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,I/ConnectivityService(  728): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  728): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3351): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a98488
V/NetworkStats(  728): performPollLocked(flags=0x1)
,D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
D/Tethering(  728): interfaceLinkStateChanged wlan0, true
,D/Tethering(  728): interfaceStatusChanged wlan0, true
D/WifiP2pService(  728): InactiveState{ what=143375 }
D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 28ms
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,I/iu.Environment( 1755): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1755): num queued entries: 0
,I/iu.UploadsManager( 1755): num updated entries: 0
,I/iu.SyncManager( 1755): NEXT; no task
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,I/dhcpcd  ( 6292): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6292): bssid match
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,I/jxcore-log( 6203): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 6203): 
,I/jxcore-log( 6203): my name is : samsung-SM-G800H_PT584
I/jxcore-log( 6203): 
,D/WifiP2pService(  728): InactiveState{ what=143375 }
,D/WifiP2pService(  728): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  728): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  728): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  728): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
,D/WifiStateMachine(  728): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  728): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  728): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  728): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  728): mBoosterFLAG : 2
,I/WifiTrafficPoller(  728): current booster mode : BTCoexMode
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  728): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
E/ConnectivityService(  728): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  728): net.tcp.delack.wifi not found in system properties. Using defaults
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
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,I/jxcore-log( 6203): attempting to connect to test coordinator
I/jxcore-log( 6203): 
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
D/ConnectivityService(  728): handleConnectivityChange: setting default proxy info 
,I/jxcore-log( 6203): check test folder
I/jxcore-log( 6203): 
,I/jxcore-log( 6203): found test : ./testFindPeers.js
I/jxcore-log( 6203): 
,V/RouteController(  238): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): /system/bin/ip -4 rule del table 2 2>&1
,D/Toast   ( 1303):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1303): showing allowed
,I/jxcore-log( 6203): found test : ./testReConnect.js
I/jxcore-log( 6203): 
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,V/RouteController(  238): RTNETLINK answers: No such file or directory
,V/RouteController(  238): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/jxcore-log( 6203): found test : ./testSendData.js
I/jxcore-log( 6203): 
,I/SurfaceFlinger(  247): id=40 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/PowerManagerService(  728): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=728
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
V/RouteController(  238): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  238): RTNETLINK answers: No such process
,V/RouteController(  238): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,V/RouteController(  238): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/jxcore-log( 6203): Test app app.js loaded
I/jxcore-log( 6203): 
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): updateIfacesLocked()
V/NetworkStats(  728): performPollLocked(flags=0x1)
V/NetworkStats(  728): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
V/NetworkStats(  728): performPollLocked() took 19ms
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,D/NtpTrustedTime(  728): currentTimeMillis() cache hit
,I/jxcore-log( 6203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6203): 
,I/chromium( 6203): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Tethering(  728): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  728): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  728): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1445): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3908): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  728): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  728): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  728): ignore wifi update if we are not in OPENING or CLOSING
,I/KLMS-2.3.201 : ( 5529): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5529): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450442912225
,I/KLMS-2.3.201 : ( 5529): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2550): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2550): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5549): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2339): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,V/KVNProvider( 5715): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5715): getFindoCursor query string : 
,V/KVNProvider( 5715): getTagSearchCursor() tagSearchCursor count : 0
,D/dalvikvm( 1202): GC_EXPLICIT freed 411K, 47% free 10035K/18744K, paused 5ms+5ms, total 51ms
,I/SA      ( 4054): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4054): [BDLM] already registered in spp
I/SA      ( 4054): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4054): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4054): [OR] == isSIMCardReady false ==
I/SA      ( 4054): [SCU] == networkStateCheck == true
I/SA      ( 4054): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4054): isChinaCountryCode : false
I/SA      ( 4054): [OR] == networkStateCheck true ==
,I/SA      ( 4054): [OR] GetMyCountryZoneTask
I/SA      ( 4054): [OR] onReceive END
I/SA      ( 4054): [SRS] prepareGetMyCountryZone
I/SA      ( 4054): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4054): [SSP] query invoked
,I/SA      ( 4054): [TPMU] GetMccFromDB : null
I/SA      ( 4054): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4054): [TPM] isNoProxy(default) : true
,I/SA      ( 4054): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5566): Other Intent
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1445): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4124): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4124): getCountryCode(): countryCode = PL
D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4124): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4124): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4124): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4124): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3351): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3351): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a98488
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/RCPManagerService(  728): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4216): notifyNetworkActivated
,D/hcjo    ( 4216): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4216): execute::IDLE:EXECUTE
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
,I/iu.Environment( 1755): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1755): num queued entries: 0
,I/iu.UploadsManager( 1755): num updated entries: 0
,I/iu.SyncManager( 1755): NEXT; no task
,I/SA      ( 4054): [RC New] [v2liruge] api execute + 403
,I/SA      ( 4054): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4054): AsyncTask #5 calls detatch()
,I/SA      ( 4054): [TPMU] getNetworkMcc : 
,I/SA      ( 4054): [SCU] saveMccToPreferece Start
I/SA      ( 4054): [SCU] RegionMCC : 260
,I/SA      ( 4054): [SSP] query invoked
,I/SA      ( 4054): [TPMU] GetMccFromDB : null
I/SA      ( 4054): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4054): [SCU] saveMccToPreferece End
I/SA      ( 4054): [RC New] executeRequest [v2liruge] end. 412
I/SA      ( 4054): [RC New] Execute end
I/SA      ( 4054): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4054): [OR] GetMyCountryZoneTask Success
,E/SMD     (  241): DCD ON
,I/jxcore-log( 6203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6203): 
,D/ConnectivityService(  728): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  728): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  247): id=40 Removed Uoast (12/13)
,I/SurfaceFlinger(  247): id=40 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  728): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=728 (0x0)
D/PowerManagerService(  728): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=728, ws=WorkSource{1000}) (elapsedTime=3513)
,I/jxcore-log( 6203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6203): 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 310, Delta = 0
,I/dalvikvm( 6203): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 6203): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6203): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 6203): Shutting down VM
,W/dalvikvm( 6203): threadid=1: thread exiting with uncaught exception (group=0x41d15da0)
,E/AndroidRuntime( 6203): FATAL EXCEPTION: main
E/AndroidRuntime( 6203): Process: com.test.thalitest, PID: 6203
E/AndroidRuntime( 6203): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 6203): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 6203): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 6203): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 6203): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 6203): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 6203): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 6203): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 6203): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 6203): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 6203): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 6203): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6203): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6203): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 6203): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 6203): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 6203): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 6203): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 6203): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 6203): Sending signal. PID: 6203 SIG: 9
,D/CrashAnrDetector(  728): processName: com.test.thalitest
,D/CrashAnrDetector(  728): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/ActivityManager(  728): Process com.test.thalitest (pid 6203) (adj 1) has died.
,I/WindowState(  728): WIN DEATH: Window{44015590 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  247): id=35 Removed NainActivit (7/12)
,I/SurfaceFlinger(  247): id=35 Removed NainActivit (-2/12)
W/ActivityManager(  728): Force removing ActivityRecord{449e3238 u0 com.test.thalitest/.MainActivity t3}: app died, no saved state
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,W/WifiP2pStateTracker(  728): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  728): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  728):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  728): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  728): updateSourceRoutes : no source routing conditions
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5175): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5175): [GetString-S]
,I/terrier ( 5175): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5175): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5175): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5175): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5175): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5175): QSEECom_shutdown_app, app_id = 3
,E/terrier ( 5175): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5175): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5175): [ensureRegistration] - No Samsung account
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  728): !@Sync 5
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 105s ago
,D/AmoledAdjustTimer(  728): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/CaptivePortalTracker(  728): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  728): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  728): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  728): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  728): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  728): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  728): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  728): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4216): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4216): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4216): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4216): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4216): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4216): entry::IDLE
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  728): waitForAlarm result :8
,D/Headlines( 4124): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4124): Breath 12093 latestRequest time : 1450442912360 current time : 1450442924454
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = -10
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,E/SMD     (  241): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  728): prevTemp = 298, currTemp = 296, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,E/SMD     (  241): DCD ON
V/AlarmManager(  728): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  728): prevTemp = 296, currTemp = 294, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  728): !@Sync 6
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 294, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,D/Headlines( 4124): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4124): Breath 42090 latestRequest time : 1450442912360 current time : 1450442954451
,I/PowerManagerService(  728): [PWL] Off : 140s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  728): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  728): !@Sync 7
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  728): waitForAlarm result :8
,D/Headlines( 4124): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4124): Breath 72080 latestRequest time : 1450442912360 current time : 1450442984441
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  728): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,E/SMD     (  241): DCD ON
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  728): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  728): !@Sync 8
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,D/Headlines( 4124): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4124): Breath 102088 latestRequest time : 1450442912360 current time : 1450443014448
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  728): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  728): !@Sync 9
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,E/SMD     (  241): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  728): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  728): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  728): waitForAlarm result :8
,D/Headlines( 4124): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4124): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4124): Breath 132082 latestRequest time : 1450442912360 current time : 1450443044443
,D/Headlines( 4124): stop 
,D/Headlines( 4124): Breath.onDestroy : 
,I/ActivityManager(  728): Killing 4445:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  728): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  728): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService(  728): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  728): TimaServiceHandler.handleMessage what =1
,D/TimaService(  728): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  728): initializing...
,I/TLC_TIMA_PKM_initialize(  728): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  728): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  728): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  728): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  728): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  728): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  728): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  728): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  728): App is not loaded in QSEE
,D/QSEECOMAPI: (  728): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  728): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  728): Trustlet response is completed
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  728): !@Sync 10
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  728): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  728): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/dalvikvm(  728): GC_CONCURRENT freed 3420K, 57% free 24009K/55640K, paused 28ms+38ms, total 434ms
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 275s ago
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :4
,V/AlarmManager(  728): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 6431): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6431):  
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/AmoledAdjustTimer(  728): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,I/SELinux ( 6431): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6431):  
I/SELinux ( 6431):  
,I/SELinux ( 6431): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6431): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 6431): >>>>> Normal User
,E/dalvikvm( 6431): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 6431): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6431): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6431): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6431): Added TimaKesytore provider
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetView( 1253): destroyHardwareResources():1130969280
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=41 createSurf (1x1),2 flag=404, CatteryCove
,D/Launcher( 1253): onRestart, Launcher: 1119033832
,D/Launcher( 1253): onStart, Launcher: 1119033832
,D/Launcher.HomeView( 1253): onStart
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1445): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1445): [237392/5] SurfaceWidget drawing first frame
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  247): id=42 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=6431, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  728): Killing 4630:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  728): !@Sync 11
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  728): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  728): !@Sync 12
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 330s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  728): !@Sync 13
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  728): !@Sync 14
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 390s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  728): !@Sync 15
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  728): !@Sync 16
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  728): [PWL] Off : 455s ago
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  728): !@Sync 17
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 18
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 19
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 525s ago
,D/AmoledAdjustTimer(  728): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/BatteryService(  728): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService(  728): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  728): TimaServiceHandler.handleMessage what =1
,D/TimaService(  728): TIMA: TimaService scheduler is intialized. 
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 20
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,W/ContextImpl(  728): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 21
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  728): [PWL] Off : 600s ago
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 22
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 23
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  728): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  728): <AppSync3 Whitelist>
,V/AlarmManager(  728): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 24
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 680s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 25
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager(  728): waitForAlarm result :4
,I/SensorManagerA(  728): getReportingMode :: sensor.mType = 5
,D/Sensors (  728): LightSensor setDelay = 200000000
,D/LightsService(  728): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  728): LightSensor setSensorDelay = 200000000
D/Sensors (  728): Light sensor flush: not enabled 0
D/Sensors (  728): LightSensor enable = 1
D/Sensors (  728): LightSensor enableSensor = 1
D/SensorManager(  728): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  728): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/LightsService(  728): [SvcLED]  onSensorChanged::light value = 9
D/Sensors (  728): LightSensor enable = 0
D/Sensors (  728): LightSensor enableSensor = 0
,D/SensorManager(  728): unregisterListener ::   
D/LightsService(  728): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/EventLogService( 1755): Aggregate from 1450441741689 (log), 1450441741689 (data)
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 26
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  728): GC_CONCURRENT freed 3578K, 57% free 23972K/55004K, paused 20ms+37ms, total 436ms
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 27
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 765s ago
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
E/SMD     (  241): DCD ON
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 28
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 29
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService(  728): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  728): TimaServiceHandler.handleMessage what =1
,D/TimaService(  728): TIMA: checkEvent, operation: 50000 subject: 10000
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 30
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 855s ago
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 31
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  728): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 32
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 33
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 950s ago
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 34
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager(  728): waitForAlarm result :4
,V/AlarmManager(  728): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
D/ConnectivityService(  728): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 35
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  728): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 36
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 1050s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 37
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  728): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 38
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 39
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService(  728): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  728): TimaServiceHandler.handleMessage what =1
,D/TimaService(  728): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 40
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 41
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 42
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/dalvikvm(  728): GC_CONCURRENT freed 3514K, 57% free 23971K/55004K, paused 22ms+37ms, total 418ms
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,E/SMD     (  241): DCD ON
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 43
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 1265s ago
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  728): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  728): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
V/AlarmManager(  728): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 44
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,E/SMD     (  241): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  728): !@Sync 45
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,I/SensorManagerA(  728): getReportingMode :: sensor.mType = 5
,D/LightsService(  728): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  728): LightSensor setDelay = 200000000
D/Sensors (  728): LightSensor setSensorDelay = 200000000
D/Sensors (  728): Light sensor flush: not enabled 0
D/Sensors (  728): LightSensor enable = 1
D/Sensors (  728): LightSensor enableSensor = 1
D/SensorManager(  728): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  728): LightSensor enable = 0
,D/Sensors (  728): LightSensor enableSensor = 0
,D/SensorManager(  728): unregisterListener ::   
D/LightsService(  728): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/LightsService(  728): [SvcLED]  onSensorChanged::light value = 10
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/BatteryService(  728): stay LED for fully charged
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  728): !@Sync 46
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  728): !@Sync 47
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService(  728): [PWL] Off : 1380s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 48
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
E/Watchdog(  728): !@Sync 49
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/TimaService(  728): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  728): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  728): TimaServiceHandler.handleMessage what =1
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 50
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 51
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService(  728): [PWL] Off : 1500s ago
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 52
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 53
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  728): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,E/SMD     (  241): DCD ON
D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 54
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 55
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,I/PowerManagerService(  728): [PWL] Off : 1625s ago
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 56
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 57
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 58
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/dalvikvm(  728): GC_CONCURRENT freed 3513K, 57% free 23992K/55004K, paused 24ms+37ms, total 405ms
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 59
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/BatteryService(  728): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/TimaService(  728): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  728): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  728): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  728): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  728): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 60
,I/PowerManagerService(  728): [PWL] Off : 1755s ago
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 61
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,V/AlarmManager(  728): waitForAlarm result :8
,V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,I/ActivityManager(  728): Killing 4581:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1806s
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  728): Prepared write state in 117ms
,I/ProcessStatsService(  728): Prepared write state in 95ms
,I/ProcessStatsService(  728): Prepared write state in 41ms
,I/ProcessStatsService(  728): Prepared write state in 32ms
,I/ProcessStatsService(  728): Prepared write state in 30ms
,I/ProcessStatsService(  728): Prepared write state in 45ms
,I/ProcessStatsService(  728): Prepared write state in 23ms
,I/ProcessStatsService(  728): Prepared write state in 13ms
,I/ProcessStatsService(  728): Pruning old procstats: /data/system/procstats/state-2015-12-17-15-42-35.bin
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 62
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/BatteryService(  728): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/Watchdog(  728): !@Sync 63
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  728): stay LED for fully charged
,D/UiModeManager(  728): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  241): DCD ON
,D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  241): DCD ON
,E/SMD     (  241): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  728): mCoverManager.getCoverState() : true
D/BatteryService(  728): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  241): DCD ON
D/SSRMv2:SIOP(  728): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  728): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
E/SMD     (  241): DCD ON
V/AlarmManager(  728): waitForAlarm result :8
V/AlarmManager(  728): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager(  728): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  728): <AppSync3 Whitelist>
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
V/AlarmManager(  728): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
I/ActivityManager(  728): Killing 5678:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1811s
I/ActivityManager(  728): Killing 5406:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1817s
I/ActivityManager(  728): Killing 5383:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1817s
I/ActivityManager(  728): Killing 5356:com.samsung.helphub/1000 (adj 15): empty for 1818s
I/ActivityManager(  728): Killing 5330:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1818s
I/ActivityManager(  728): Killing 5304:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1818s
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
I/ActivityManager(  728): Killing 5276:com.google.android.apps.docs/u0a90 (adj 15): empty for 1818s
I/ActivityManager(  728): Killing 5262:com.sec.android.service.cm/u0a78 (adj 15): empty for 1819s
I/ActivityManager(  728): Killing 4707:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1819s
I/ActivityManager(  728): Killing 4362:com.android.mms/u0a48 (adj 15): empty for 1819s
I/ActivityManager(  728): Killing 5232:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1819s
I/ActivityManager(  728): Killing 4266:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1819s
I/ActivityManager(  728): Killing 5193:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1820s
I/ActivityManager(  728): Killing 5157:com.android.musicfx/u0a24 (adj 15): empty for 1820s
I/ActivityManager(  728): Killing 5142:com.samsung.groupcast/u0a15 (adj 15): empty for 1820s
I/ActivityManager(  728): Killing 5127:com.google.android.partnersetup/u0a14 (adj 15): empty for 1820s
I/ActivityManager(  728): Killing 5115:com.sec.android.inputmethod/1000 (adj 15): empty for 1821s
I/ActivityManager(  728): Killing 5064:com.android.defcontainer/u0a6 (adj 15): empty for 1821s
D/CountryDetector(  728): No listener is left
E/SMD     (  241): DCD ON
D/AndroidRuntime( 6829): 
D/AndroidRuntime( 6829): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6829): CheckJNI is OFF
D/AndroidRuntime( 6829): setted country_code = Poland
D/AndroidRuntime( 6829): setted countryiso_code = PL
D/AndroidRuntime( 6829): setted sales_code = XEO
D/AndroidRuntime( 6829): readGMSProperty: start
D/AndroidRuntime( 6829): readGMSProperty: already setted!!
D/AndroidRuntime( 6829): readGMSProperty: end
D/AndroidRuntime( 6829): addProductProperty: start
D/dalvikvm( 6829): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6829): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6829): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6829): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6829): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6829): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6829): failed to load memtrack module: -2
D/dalvikvm( 6829): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6829): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  728): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  728): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  728): START PACKAGE DELETE: observer{1127357216}
D/PackageManager(  728): pkg{<packageName>}
D/PackageManager(  728): user{0}
D/PersonaManagerService(  728): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  728): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  728): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  728): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
E/SMD     (  241): DCD ON
D/PackageManagerService(  728): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  728): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  728): getApplicationUninstallationEnabled
D/ApplicationPolicy(  728): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  728): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  728): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  728): [MSG] DELETE_PACKAGE_AS_USER
D/BatteryService(  728): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  728): stay LED for fully charged
D/BatteryService(  728): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  728): mCoverManager.getCoverState() : true
V/HeadsetService( 1939): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1939): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/PackageManager(  728): !@killApplicatoin: 10179, uninstall pkg
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
W/PackageSettings(  728): Skipping PackageSetting{431e39e0 com.example.hello/10181} due to missing metadata
D/PackageManager(  728): checkUidPermission - Execution time: 139 ms
D/PackageManager(  728): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1755): GC_EXPLICIT freed 528K, 34% free 12382K/18744K, paused 4ms+14ms, total 56ms
D/PackageManager(  728): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1066): action=android.intent.action.PACKAGE_REMOVED
I/InputReader(  728): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "sms"
D/QuickConnect[1.1][2] ( 3351): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 1410): GC_EXPLICIT freed 4301K, 47% free 10032K/18744K, paused 15ms+5ms, total 124ms
I/FPMS_FingerprintManagerService( 1085): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 2178): GC_EXPLICIT freed 1582K, 41% free 11227K/18744K, paused 3ms+4ms, total 172ms
W/GeofencerStateMachine( 1216): Ignoring removeGeofence because network location is disabled.
I/SELinux ( 6858): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6858):  
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "smsto"
D/dalvikvm(  728): GC_EXPLICIT freed 2512K, 57% free 24017K/55004K, paused 11ms+18ms, total 170ms
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "mms"
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  728): PackageReceiver onReceive()
I/SELinux ( 6858): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6858):  
I/SELinux ( 6858):  
I/SELinux ( 6858): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6858): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6858): >>>>> Normal User
E/dalvikvm( 6858): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6858): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "mmsto"
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService(  728): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/TimaKeyStoreProvider( 6858): in addTimaSignatureService
D/TimaKeyStoreProvider( 6858): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6858): Added TimaKesytore provider
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "sms"
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "smsto"
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=6858, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "mms"
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 6858): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6858): ELMEngine.ELMEngine( context ).
D/elm:14132( 6858): MDMBridge.setEnterpriseBridge()
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "mmsto"
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 6858): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6858): ElmAgentService : onCreate()
D/elm:14132( 6858): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6858): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6858): MDMBridge.getInstance()
D/elm:14132( 6858): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6858): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 6871): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6871):  
D/elm:14132( 6858): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/EnterpriseDeviceManagerService(  728): Package has changed for user 0
D/EnterpriseDeviceManagerService(  728): Admin package name: com.google.android.gms
D/elm:14132( 6858): ElmAgentService : onDestroy().
D/dalvikvm(  728): GC_EXPLICIT freed 762K, 57% free 24041K/55004K, paused 9ms+21ms, total 191ms
I/SELinux ( 6871): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6871):  
I/SELinux ( 6871):  
I/SELinux ( 6871): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6871): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6871): >>>>> Normal User
E/dalvikvm( 6871): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6871): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager(  728): delete sourFile : 
D/BackupManagerService(  728): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  728): removePackageParticipantsLocked: uid=10179 #1
D/TimaKeyStoreProvider( 6871): in addTimaSignatureService
D/PackageManager(  728): delete native library directory: 
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 6829): Shutting down VM
D/TimaKeyStoreProvider( 6871): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6871): Added TimaKesytore provider
D/dalvikvm( 6829): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+1ms, total 3ms
D/PackageManager(  728): return delete result to caller: 1127357216
D/PackageManager(  728): returnCode: 1
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "sms"
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "smsto"
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "mms"
I/PackageManager(  728):   Action: "android.intent.action.SENDTO"
I/PackageManager(  728):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  728):   Scheme: "mmsto"
I/PackageManager(  728): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  728): Permission Denial: getCurrentUser() from pid=6871, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 6871): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42a8d9f0, skipping init
I/SecureStorage( 6871): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6871): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6871
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6871): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 6871): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6871
I/SecureStorage(  300): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  728): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  728): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  728): clearDefaults: com.test.thalitest
D/InputReader(  728): Processing first event
W/ApplicationsProvider( 1410): Could not fetch usage stats
W/ApplicationsProvider( 1410): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1410): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1410): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1410): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1410): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1410): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1410): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
