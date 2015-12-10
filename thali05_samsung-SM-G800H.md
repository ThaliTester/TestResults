#### Test 50650278d6c551a_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/PCWCLIENTTRACE_PushUtil( 5196): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5196): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5196): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_LOG( 5196): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5196): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_SYSTEMReceiver( 5196): [onReceive] - android.intent.action.PACKAGE_ADDED
I/SELinux ( 5210): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5210):  
--------- beginning of /dev/log/system
I/ActivityManager(  738): Killing 3477:com.android.email/u0a155 (adj 15): empty #43
D/SSRMv2:SIOP(  738): SIOP:: AP = 310, Delta = 0
I/SELinux ( 5210): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5210):  
I/SELinux ( 5210):  
I/SELinux ( 5210): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5210): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5210): >>>>> Normal User
E/dalvikvm( 5210): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10034 ]
E/SELinux ( 5210): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5210): in addTimaSignatureService
D/TimaKeyStoreProvider( 5210): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5210): Added TimaKesytore provider
W/System.err( 5210): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 5210): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 5210): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 5210): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 5210): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 5210): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 5210): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 5210): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 5210): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 5210): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:105)
W/System.err( 5210): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:89)
W/System.err( 5210): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 5210): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 5210): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5210): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 5210): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5210): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 5210): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 5210): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 5210): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 5210): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 5210): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 5210): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 5210): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5210): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5210): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 5210): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 5210): 	... 21 more
D/GalaxyFinderApplication( 5210): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 5210): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 5229): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5229):  
I/ActivityManager(  738): Killing 3606:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
I/SELinux ( 5229): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5229):  
I/SELinux ( 5229):  
I/SELinux ( 5229): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5229): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5229): >>>>> Normal User
E/dalvikvm( 5229): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 5229): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5229): in addTimaSignatureService
D/TimaKeyStoreProvider( 5229): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5229): Added TimaKesytore provider
I/SELinux ( 5250): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5250):  
I/ActivityManager(  738): Killing 3977:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  241): GC_EXPLICIT freed 45K, 50% free 9506K/19012K, paused 2ms+3ms, total 33ms
D/dalvikvm(  241): GC_EXPLICIT freed <1K, 50% free 9506K/19012K, paused 1ms+3ms, total 18ms
I/SELinux ( 5250): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5250):  
I/SELinux ( 5250):  
I/SELinux ( 5250): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5250): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5250): >>>>> Normal User
E/dalvikvm( 5250): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5250): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  241): GC_EXPLICIT freed <1K, 50% free 9506K/19012K, paused 2ms+2ms, total 19ms
D/TimaKeyStoreProvider( 5250): in addTimaSignatureService
D/TimaKeyStoreProvider( 5250): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5250): Added TimaKesytore provider
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5250, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5250): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ActivityManager(  738): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5250): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/SA      ( 4058): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4058): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4058): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4356): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2174): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4700): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5279): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5279):  
I/SELinux ( 5279): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5279):  
I/SELinux ( 5279):  
I/SELinux ( 5279): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5279): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5279): >>>>> Normal User
E/dalvikvm( 5279): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5279): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5279): in addTimaSignatureService
D/TimaKeyStoreProvider( 5279): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5279): Added TimaKesytore provider
I/ActivityManager(  738): Killing 3989:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/CapabilityManagerService New( 5279): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5279, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 2174): GC_CONCURRENT freed 1638K, 39% free 11651K/19012K, paused 4ms+8ms, total 133ms
D/dalvikvm( 2174): WAIT_FOR_CONCURRENT_GC blocked 8ms
I/SELinux ( 5292): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5292):  
I/ActivityManager(  738): Killing 4281:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/IcingCorporaProvider( 2174): UpdateCorporaTask done [took 223 ms] updated apps [took 222 ms] 
I/SELinux ( 5292): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5292):  
I/SELinux ( 5292):  
I/SELinux ( 5292): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5292): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5292): >>>>> Normal User
E/dalvikvm( 5292): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5292): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5292): in addTimaSignatureService
D/TimaKeyStoreProvider( 5292): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5292): Added TimaKesytore provider
D/AndroidRuntime( 5271): 
D/AndroidRuntime( 5271): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5271): CheckJNI is OFF
D/AndroidRuntime( 5271): setted country_code = Poland
D/AndroidRuntime( 5271): setted countryiso_code = PL
D/AndroidRuntime( 5271): setted sales_code = XEO
D/AndroidRuntime( 5271): readGMSProperty: start
D/AndroidRuntime( 5271): readGMSProperty: already setted!!
D/AndroidRuntime( 5271): readGMSProperty: end
D/AndroidRuntime( 5271): addProductProperty: start
D/dalvikvm( 5271): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5271): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5271): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5271): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5271): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5292, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
E/memtrack( 5271): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5271): failed to load memtrack module: -2
D/dalvikvm( 5271): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5271): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy(  738): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  738): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  738): mDVFSHelper.acquire()
I/SELinux ( 5317): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5317):  
D/LockPatternUtils( 1071): isPcwEnable = null
D/AndroidRuntime( 5271): Shutting down VM
D/dalvikvm( 5271): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
E/SMD     (  233): DCD ON
I/SELinux ( 5317): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5317):  
I/SELinux ( 5317):  
I/SELinux ( 5317): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5317): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5317): >>>>> Normal User
E/dalvikvm( 5317): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5317): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5317): in addTimaSignatureService
D/TimaKeyStoreProvider( 5317): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5317): Added TimaKesytore provider
D/LockPatternUtils( 1071): isPcwEnable = null
D/SurfaceWidgetView( 1243): destroyHardwareResources():1125860632
W/GAV2    ( 5292): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5340): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5340):  
I/SQLiteSecureOpenHelper( 2089): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2089): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  239): id=14 Removed CatteryCove (8/12)
D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  239): id=9 Removed Mauncher (7/11)
I/SurfaceFlinger(  239): id=9 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
I/SELinux ( 5340): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5340):  
I/SELinux ( 5340):  
I/SELinux ( 5340): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
E/SELinux ( 5340): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5340): >>>>> Normal User
E/dalvikvm( 5340): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5340): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1448): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1243): onTrimMemory. Level: 20
D/TimaKeyStoreProvider( 5340): in addTimaSignatureService
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5317, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
D/TimaKeyStoreProvider( 5340): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5340): Added TimaKesytore provider
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5317, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5317): Binding Chromium to the background looper Looper (main, tid 1) {42285120}
I/chromium( 5317): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5317): Initializing chromium process, renderers=0
,W/chromium( 5317): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5317): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5317): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5317): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5317): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5317): Remote Branch: 
I/Adreno-EGL( 5317): Local Patches: 
I/Adreno-EGL( 5317): Reconstruct Branch: 
,D/PackageIntentReceiver( 5340): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 5340): Not GearManger package! 
,I/SELinux ( 5368): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5368):  
I/ActivityManager(  738): Killing 4002:com.sec.android.soagent/u0a37 (adj 15): empty #43
,I/SELinux ( 5368): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5368):  
I/SELinux ( 5368):  
,I/SELinux ( 5368): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5368): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5368): >>>>> Normal User
,E/dalvikvm( 5368): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 5368): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5368): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5368): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5368): Added TimaKesytore provider
,D/MagazineService Version( 5368): Magazine-Channel: 13
,D/MagazineService Version( 5368): Magazine-Provider: 13
,D/MagazineService Version( 5368): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 5368): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 5368): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5368, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,I/dalvikvm( 5317): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5317): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5317): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5317): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5317): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5317): VFY: replacing opcode 0x6e at 0x0008
,I/MagazineService::MagazineService( 5368): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,W/dalvikvm( 5317): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5317): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5317): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5317): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5317): VFY: replacing opcode 0x6f at 0x001a
,I/SELinux ( 5383): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5383):  
,W/dalvikvm( 5317): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5317): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5317): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 5317): VFY: replacing opcode 0x6e at 0x000d
D/MagazineService::MagazineService( 5368): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/dalvikvm( 5317): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5317): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5317): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5317): CordovaWebView is running on device made by: samsung
I/ActivityManager(  738): Killing 4390:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
,W/GAV2    ( 5292): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  738): Killing 4406:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,I/SELinux ( 5383): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5383):  
I/SELinux ( 5383):  
I/SELinux ( 5383): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5383): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5383): >>>>> Normal User
E/dalvikvm( 5383): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5383): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5383): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5383): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5383): Added TimaKesytore provider
,I/SurfaceFlinger(  239): id=17 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5317): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 5317): Enabling debug mode 0
,W/AwContents( 5317): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  738): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  738): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  738): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 5408): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5408):  
I/ActivityManager(  738): Killing 4418:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5408): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5408):  
I/SELinux ( 5408):  
,I/SELinux ( 5408): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5408): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5408): >>>>> Normal User
,E/dalvikvm( 5408): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5408): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5408): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5408): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5408): Added TimaKesytore provider
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5408, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5408): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5422): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5422):  
,I/ActivityManager(  738): Killing 3593:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 5422): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5422):  
I/SELinux ( 5422):  
,I/SELinux ( 5422): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5422): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5422): >>>>> Normal User
,E/dalvikvm( 5422): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5422): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5422): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5422): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5422): Added TimaKesytore provider
,D/JsMessageQueue( 5317): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  738): Killing 4446:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/Finsky  ( 3691): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 1802): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1802): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/dalvikvm( 5317): Trying to load lib /data/app-lib/com.test.thalitest-30/libjxcore.so 0x425abf00
,D/ChimeraModuleLdr( 1802): Loading module APK com.google.android.play.games
,I/dalvikvm( 1802): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1802): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1802): VFY: replacing opcode 0x6e at 0x0053
,D/dalvikvm( 5317): Added shared lib /data/app-lib/com.test.thalitest-30/libjxcore.so 0x425abf00
,D/jxcore_app_log( 5317): JniHelper::setJavaVM(0x416e4528), pthread_self() = 1953588224
,D/JX-Cordova( 5317): jxcore cordova android initializing
,I/dalvikvm( 5317): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 5317): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5317): VFY: replacing opcode 0x6e at 0x0045
,I/dalvikvm( 1802): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1802): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1802): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1802): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1802): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1802): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1802): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1802): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1802): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1802): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1802): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1802): Submit a task: k
,D/ChimeraCfgMgr( 1802): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/BaseAppContext( 1802): Using Auth Proxy for data requests.
,W/BaseAppContext( 1802): Using Auth Proxy for data requests.
,D/dalvikvm( 5317): GC_CONCURRENT freed 4925K, 33% free 12762K/19012K, paused 3ms+3ms, total 45ms
,D/dalvikvm( 5317): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 5317): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/BaseAppContext( 1802): Using Auth Proxy for data requests.
,W/BaseAppContext( 1802): Using Auth Proxy for data requests.
,W/BaseAppContext( 1802): Using Auth Proxy for data requests.
,D/k       ( 1802): Processing package: com.test.thalitest
,D/ChimeraCfgMgr( 1802): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/BaseAppContext( 1802): Using Auth Proxy for data requests.
,D/GassUtils( 1802): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1802): Found info for package com.test.thalitest in db.
,W/dalvikvm( 1802): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1802): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
,W/dalvikvm( 1802): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1802): VFY: replacing opcode 0x6e at 0x000e
,W/dalvikvm( 1802): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1802): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1802): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1802): VFY: replacing opcode 0x6e at 0x000e
,I/dalvikvm( 1802): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1802): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1802): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1802): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
,W/dalvikvm( 1802): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1802): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1802): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1802): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1802): VFY: replacing opcode 0x6e at 0x0006
,D/CustomFrequencyManagerService(  738): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  tag : ACTIVITY_RESUME_BOOSTER@9
,I/PeopleDatabaseHelper( 1802): cleanUpNonGplusAccounts done.
,D/dalvikvm( 1324): GC_EXPLICIT freed 1006K, 44% free 10818K/19012K, paused 4ms+5ms, total 39ms
,D/ChimeraCfgMgr( 1802): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1802): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5317): GC_FOR_ALLOC freed 4724K, 28% free 15771K/21840K, paused 34ms, total 35ms
,D/dalvikvm( 5317): GC_FOR_ALLOC freed 5081K, 32% free 16784K/24528K, paused 37ms, total 39ms
,I/dalvikvm-heap( 5317): Grow heap (frag case) to 22.043MB for 2475476-byte allocation
,I/Icing   ( 1802): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1802): GC_CONCURRENT freed 1379K, 35% free 12426K/19012K, paused 6ms+5ms, total 95ms
,W/SQLiteConnectionPool( 1802): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Icing   ( 1802): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/AmoledAdjustTimer(  738): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/dalvikvm( 5317): GC_FOR_ALLOC freed 3780K, 36% free 17469K/26948K, paused 34ms, total 36ms
,E/SMD     (  233): DCD ON
,D/dalvikvm( 5317): GC_FOR_ALLOC freed 1246K, 36% free 17374K/26948K, paused 30ms, total 30ms
,W/jxcore-log( 5317): Initializing JXcore engine
,W/jxcore-log( 5317): JXcore engine is ready
,W/jxcore-log( 5317): Starting JXcore engine
,W/jxcore-log( 5317): Platform android
W/jxcore-log( 5317): 
,W/jxcore-log( 5317): Process ARCH arm
W/jxcore-log( 5317): 
,I/jxcore-log( 5317): JXcore Cordova bridge is ready!
I/jxcore-log( 5317): 
,W/jxcore-log( 5317): JXcore engine is started
,I/chromium( 5317): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GAV2    ( 5292): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  738): waitForAlarm result :4
,V/AlarmManager(  738): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4113): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4113): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4113): Breath 68013 latestRequest time : 1449754783656 current time : 1449754851669
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm(  738): GC_EXPLICIT freed 25244K, 58% free 23831K/55844K, paused 7ms+17ms, total 208ms
,D/FactoryTest( 4766): Not factory mode
,D/FactoryTest( 4766): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4766): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4766): still no open session command from host, so toast
W/ContextImpl( 4766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
I/VacuumService( 1220): Vacuum at: now=1449754852060 tag=VacuumService
V/ApplicationPolicy(  738): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  738): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  738): mDVFSHelper.acquire()
,I/SQLiteSecureOpenHelper( 2089): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2089): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1071): isPcwEnable = null
,D/LockPatternUtils( 1071): isPcwEnable = null
,E/MTPRx   ( 4766): started activity for popup
,E/SettingsReceiverActivity( 4766): PREF_DONT_ASK_AGAIN : false
,D/SettingsReceiverActivity( 4766): dev.kiessupport is : TRUE
,I/SurfaceFlinger(  239): id=18 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4766): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4766): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4766): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4766): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4766): Remote Branch: 
I/Adreno-EGL( 4766): Local Patches: 
I/Adreno-EGL( 4766): Reconstruct Branch: 
,I/HWUI    ( 4766): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4766): Enabling debug mode 0
,E/SMD     (  233): DCD ON
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  738): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  738): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  738): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,I/jxcore-log( 5317): Toggling radios to true
I/jxcore-log( 5317): 
D/BluetoothAdapter( 5317): enable(): BT is already enabled..!
I/WifiManager( 5317): packageName : com.test.thalitest
I/WifiManager( 5317): setWifiEnabled : true
I/WifiService(  738): setWifiEnabled: true pid=5317, uid=10179
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5317, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  738): Failed getting userId using ActivityManagerNative
W/WifiService(  738): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5317, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  738): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  738): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  738): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  738): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  738): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  738): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService(  738): disconnect: pid=5317, uid=10179
I/jxcore-log( 5317): Radios toggled
I/jxcore-log( 5317): 
I/jxcore-log( 5317): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5317): 
I/wpa_supplicant( 1972): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 5317): Perf Test app loaded loaded
I/jxcore-log( 5317): 
I/jxcore-log( 5317): check test folder
I/jxcore-log( 5317): 
I/jxcore-log( 5317): found test : ./testFindPeers.js
I/jxcore-log( 5317): 
I/wpa_supplicant( 1972): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1972): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1972): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  738): interfaceLinkStateChanged wlan0, false
D/Tethering(  738): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1972): Cmd 35605 not handled
E/wpa_supplicant( 1972): Cmd 35605 not handled
D/Tethering(  738): InitialState.processMessage what=4
I/wpa_supplicant( 1972): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
E/Tethering(  738): No numeric data
D/Tethering(  738): sendTetherStateChangedBroadcast 0, 0, 0
I/ConnectivityService(  738): defaultVal : 1, tetherEnabledInSettings : true
D/NtpTrustedTime(  738): currentTimeMillis() cache hit
D/Tethering(  738): interfaceLinkStateChanged wlan0, false
D/Tethering(  738): interfaceStatusChanged wlan0, false
V/NetworkStats(  738): performPollLocked(flags=0x1)
I/wpa_supplicant( 1972): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1972): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1972): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1972): First Scan Start
I/wpa_supplicant( 1972): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering(  738): interfaceLinkStateChanged wlan0, false
D/Tethering(  738): interfaceStatusChanged wlan0, false
I/jxcore-log( 5317): found test : ./testSendData.js
I/jxcore-log( 5317): 
W/Settings(  738): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  738): ignore requestNetworkTransitionWakelock airplane:true
D/NtpTrustedTime(  738): currentTimeMillis() cache hit
D/NtpTrustedTime(  738): currentTimeMillis() cache hit
D/NtpTrustedTime(  738): currentTimeMillis() cache hit
V/NetworkStats(  738): performPollLocked() took 40ms
D/WifiP2pService(  738): InactiveState{ what=143375 }
D/WifiP2pService(  738): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1071): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
D/CommandListener(  230): Clearing all IP addresses on wlan0
I/WifiTrafficPoller(  738): evaluateTrafficStatsPolling
D/ConnectivityService(  738): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  738): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  738): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  738): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  738): net.tcp.delack.default not found in system default properties
D/STATUSBAR-NetworkController_dual( 1071): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1071): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1071): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1071): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1071): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1071): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1071): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1071): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1071): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1071): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1071): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1071): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1071): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1071): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1071): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1071): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1071): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
E/ConnectivityService(  738): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
I/wpa_supplicant( 1972): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1972): Skip scan - already scanning
D/ConnectivityService(  738): Attempting to switch to mobile
D/ConnectivityService(  738): Attempting to switch to BLUETOOTH_TETHER
D/WifiP2pService(  738): InactiveState{ what=143375 }
D/WifiP2pService(  738): P2pEnabledState{ what=143375 }
I/SELinux ( 5489): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5489):  
D/STATUSBAR-IconMerger( 1071): checkOverflow(336), More:false, Req:false Child:2
D/STATUSBAR-NetworkController_dual( 1071): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
V/RouteController(  230): /system/bin/ip -6 route del default table 2 2>&1
V/RouteController(  230): RTNETLINK answers: No such process
V/RouteController(  230): /system/bin/ip -6 rule del table 2 2>&1
I/SELinux ( 5489): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5489):  
I/SELinux ( 5489):  
I/SELinux ( 5489): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5489): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5489): >>>>> Normal User
E/dalvikvm( 5489): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
E/SELinux ( 5489): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
V/RouteController(  230): RTNETLINK answers: No such file or directory
D/CommandListener(  230): Clearing all IP addresses on wlan0
I/WifiTrafficPoller(  738): evaluateTrafficStatsPolling
W/NetworkManagementService(  738): route cmd failed: 
W/NetworkManagementService(  738): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  738): '
W/NetworkManagementService(  738): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  738): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  738): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  738): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  738): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  738): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  738): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  738): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  738): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  738): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  738): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/TimaKeyStoreProvider( 5489): in addTimaSignatureService
V/RouteController(  230): /system/bin/ip -4 route del default table 2 2>&1
E/WifiStateMachine(  738): Error! unhandled message{ when=-86ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  738): Error! unhandled message{ when=-86ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  738): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1071): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
D/TimaKeyStoreProvider( 5489): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5489): Added TimaKesytore provider
V/RouteController(  230): RTNETLINK answers: No such process
V/RouteController(  230): /system/bin/ip -4 rule del table 2 2>&1
V/RouteController(  230): /system/bin/ip route flush cached 2>&1
D/NetUtils(  738): android_net_utils_resetConnections in env=0x77cf8720 clazz=0x69300001 iface=wlan0 mask=0x3
D/ConnectivityService(  738): resetConnections(wlan0, 3)
V/NativeCrypto( 1324): Read error: ssl=0x7bbf3ac0: I/O error during system call, Connection timed out
V/NativeCrypto( 1324): SSL shutdown failed: ssl=0x7bbf3ac0: I/O error during system call, Broken pipe
I/chromium( 5317): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/System.out( 5489): Inside WakeupProvider
,I/System.out( 5489): Inside onCreate() of WakeupTriggerProvide
,V/NetworkStats(  738): updateIfacesLocked()
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
V/NetworkStats(  738): performPollLocked(flags=0x1)
D/ConnectivityService(  738): handleInetConditionChange: no active default network - ignore
V/NetworkStats(  738): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/VlingoApplication( 5489): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/VlingoApplication( 5489): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5489): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
V/NetworkStats(  738): performPollLocked() took 17ms
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5489): initQueue()
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  738): Killing 4461:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,D/CustomFrequencyManagerService(  738): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 738  tag : ACTIVITY_RESUME_BOOSTER@9
,I/ApplicationPolicy(  738): updateDataUsageMap
,D/Tethering(  738): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  738): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  738): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  738): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1071): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/LocSvc_java(  738): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  738): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  738): ignore wifi update if we are not in OPENING or CLOSING,
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
,I/PCWCLIENTTRACE_PushUtil( 5196): SPPPushClient is installed : true
,I/NetworkMonitor( 3920): type=WIFI subType= reason=null isConnected=false
I/PCWCLIENTTRACE_PushUtil( 5196): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5196): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5196): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5196): noConnectivity : true
,D/accuweather( 1448): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SELinux ( 5529): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5529):  
,I/SELinux ( 5529): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5529):  
I/SELinux ( 5529):  
,I/SELinux ( 5529): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5529): >>>>> Normal User
,E/dalvikvm( 5529): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5529): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5529): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5529): Added TimaKesytore provider
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5529, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  738): Killing 4490:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/wpa_supplicant( 1972): nl80211: Received scan results (10 BSSes)
,I/wpa_supplicant( 1972): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1972): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1972): Trying to associate with  'G700'
I/wpa_supplicant( 1972): Re-associate with C0.AA.48
,I/wpa_supplicant( 1972): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1972): Cmd 35609 not handled
,D/Tethering(  738): interfaceLinkStateChanged wlan0, false
,D/Tethering(  738): interfaceStatusChanged wlan0, false
,I/SELinux ( 5544): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5544):  
,D/dalvikvm(  241): GC_EXPLICIT freed 43K, 50% free 9506K/19012K, paused 2ms+2ms, total 25ms
,D/dalvikvm(  241): GC_EXPLICIT freed <1K, 50% free 9506K/19012K, paused 1ms+2ms, total 18ms
,I/SELinux ( 5544): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5544):  
I/SELinux ( 5544):  
,I/SELinux ( 5544): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5544): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 5544): >>>>> Normal User
,E/dalvikvm( 5544): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,D/dalvikvm(  241): GC_EXPLICIT freed <1K, 50% free 9506K/19012K, paused 2ms+2ms, total 18ms
,E/SELinux ( 5544): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5544): in addTimaSignatureService
,E/wpa_supplicant( 1972): Cmd 35605 not handled
E/wpa_supplicant( 1972): Cmd 35847 not handled
E/wpa_supplicant( 1972): Cmd 35848 not handled
E/wpa_supplicant( 1972): Cmd 35605 not handled
I/wpa_supplicant( 1972): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1972): Associated with C0.AA.48
,I/wpa_supplicant( 1972): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1972): freq(2412) increment count 2
,I/wpa_supplicant( 1972): meet head of list.
,D/Tethering(  738): interfaceLinkStateChanged wlan0, false
,D/Tethering(  738): interfaceStatusChanged wlan0, false
,D/Tethering(  738): interfaceLinkStateChanged wlan0, false
,D/Tethering(  738): interfaceStatusChanged wlan0, false
,D/TimaKeyStoreProvider( 5544): Cannot add TimaSignature Service, License check Failed
,D/Tethering(  738): interfaceLinkStateChanged wlan0, false
,I/wpa_supplicant( 1972): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1972): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1972): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering(  738): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1972): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  738): interfaceLinkStateChanged wlan0, true
,D/Tethering(  738): interfaceStatusChanged wlan0, true
,D/WifiNative(  738): callSECApiVoid - ID [50]
,E/Tethering(  738): No numeric data
,D/Tethering(  738): sendTetherStateChangedBroadcast 1, 0, 0
I/ConnectivityService(  738): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/ActivityThread( 5544): Added TimaKesytore provider
V/NetworkStats(  738): performPollLocked(flags=0x1)
,D/Tethering(  738): interfaceLinkStateChanged wlan0, true
,D/Tethering(  738): interfaceStatusChanged wlan0, true
D/Tethering(  738): interfaceLinkStateChanged wlan0, true
D/Tethering(  738): interfaceStatusChanged wlan0, true
D/Tethering(  738): interfaceLinkStateChanged wlan0, true
D/Tethering(  738): interfaceStatusChanged wlan0, true
D/Tethering(  738): interfaceLinkStateChanged wlan0, true
,D/Tethering(  738): interfaceStatusChanged wlan0, true
D/STATUSBAR-NetworkController_dual( 1071): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
,D/WifiP2pService(  738): InactiveState{ what=143375 }
,D/WifiP2pService(  738): P2pEnabledState{ what=143375 }
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,V/NetworkStats(  738): performPollLocked() took 57ms
D/NtpTrustedTime(  738): currentTimeMillis() cache hit
D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5544, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  738): Killing 4506:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5562): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5562):  
,I/SELinux ( 5562): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5562):  
I/SELinux ( 5562):  
,I/SELinux ( 5562): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5562): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5562): >>>>> Normal User
,E/dalvikvm( 5562): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5562): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5562): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5562): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5562): Added TimaKesytore provider
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5562, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5562): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5562): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449754854491
,I/KLMS-2.3.201 : ( 5562): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/dhcpcd  ( 5572): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5572): bssid match
I/ActivityManager(  738): Killing 1340:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 5581): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5581):  
,I/SELinux ( 5581): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5581):  
I/SELinux ( 5581):  
,I/SELinux ( 5581): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5581): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5581): >>>>> Normal User
,E/dalvikvm( 5581): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5581): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5581): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5581): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5581): Added TimaKesytore provider
,D/SO_AGENT( 5581): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5581): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5581, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/SA      ( 4058): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4058): [BDLM] already registered in spp
,I/SA      ( 4058): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4058): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4058): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4058): [OR] == isSIMCardReady false ==
,I/SA      ( 4058): [SCU] == networkStateCheck == false
,I/SA      ( 4058): [OR] onReceive END
,I/ActivityManager(  738): Killing 4645:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1239): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1239): Phone number locator feature is dsiabled
,I/SELinux ( 5602): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5602):  
,I/SELinux ( 5602): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5602):  
I/SELinux ( 5602):  
,I/SELinux ( 5602): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5602): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5602): >>>>> Normal User
,E/dalvikvm( 5602): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5602): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5602): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5602): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5602): Added TimaKesytore provider
,I/sCloudBackupApp( 5602): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5602): Other Intent
I/ActivityManager(  738): Killing 4654:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/SSRMv2:SIOP(  738): SIOP:: AP = 330, Delta = 20
D/com.samsung.app( 1448): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1448): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5628): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5628):  
,I/SELinux ( 5628): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5628):  
I/SELinux ( 5628):  
,I/SELinux ( 5628): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5628): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5628): >>>>> Normal User
E/dalvikvm( 5628): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5628): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5628): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5628): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5628): Added TimaKesytore provider
,D/WifiP2pService(  738): InactiveState{ what=143375 }
,D/WifiP2pService(  738): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  738): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1071): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1071): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  738): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  738): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  738): evaluateTrafficStatsPolling
,D/WifiStateMachine(  738): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  738): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  738): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1071): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  738): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  738): mBoosterFLAG : 2
,I/WifiTrafficPoller(  738): current booster mode : BTCoexMode
D/ConnectivityService(  738): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  738): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  738): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1071): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1071): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1071): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1071): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1071): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1071): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1071): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1071): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1071): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1071): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1071): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1071): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1071): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1071): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1071): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1071): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1071): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5628, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  738): handleConnectivityChange: setting default proxy info 
,V/RouteController(  230): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  230): /system/bin/ip -4 rule del table 2 2>&1
I/ActivityManager(  738): Killing 4718:com.google.android.talk/u0a105 (adj 15): empty #43
,D/Headlines( 4113): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4113): getCountryCode(): countryCode = PL
D/Headlines( 4113): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 4113): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4113): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4113): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4113): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4113): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4113): requestUpdateNewsWelcomeCard !!! no welcome card
,V/RouteController(  230): RTNETLINK answers: No such file or directory
,V/RouteController(  230): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/SELinux ( 5648): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5648):  
,V/RouteController(  230): /system/bin/ip route flush cached 2>&1
,V/RouteController(  230): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  230): RTNETLINK answers: No such process
,V/RouteController(  230): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  230): /system/bin/ip route flush cached 2>&1
,I/SELinux ( 5648): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5648):  
I/SELinux ( 5648):  
,I/SELinux ( 5648): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5648): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5648): >>>>> Normal User
,E/dalvikvm( 5648): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5648): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5648): in addTimaSignatureService
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
V/NetworkStats(  738): updateIfacesLocked()
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
D/TimaKeyStoreProvider( 5648): Cannot add TimaSignature Service, License check Failed
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/ActivityThread( 5648): Added TimaKesytore provider
V/NetworkStats(  738): performPollLocked(flags=0x1)
V/NetworkStats(  738): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
V/NetworkStats(  738): performPollLocked() took 19ms
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,D/NtpTrustedTime(  738): currentTimeMillis() cache hit
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5648): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5648): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5648): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5648): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 5648): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,E/SMD     (  233): DCD ON
,V/WebViewChromium( 5648): Binding Chromium to the main looper Looper (main, tid 1) {42286f40}
,I/chromium( 5648): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5648): Initializing chromium process, renderers=0
,W/chromium( 5648): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5648): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5648): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5648): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5648): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5648): Remote Branch: 
I/Adreno-EGL( 5648): Local Patches: 
I/Adreno-EGL( 5648): Reconstruct Branch: 
,I/NSApplication( 5648): Starting up...
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5648, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  738): Killing 3048:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
I/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3365): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425b9448
,I/SELinux ( 5693): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5693):  
,I/SELinux ( 5693): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5693):  
I/SELinux ( 5693):  
,I/SELinux ( 5693): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5693): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5693): >>>>> Normal User
,E/dalvikvm( 5693): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5693): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5693): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5693): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5693): Added TimaKesytore provider
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/Tethering(  738): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  738): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  738): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1071): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/accuweather( 1448): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LocSvc_java(  738): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  738): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  738): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
,I/NetworkMonitor( 3920): type=WIFI subType= reason=null isConnected=true
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
I/ActivityManager(  738): Killing 4800:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 5718): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5718):  
,I/SELinux ( 5722): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5722):  
W/ActivityManager(  738): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5718): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5718):  
I/SELinux ( 5718):  
,I/SELinux ( 5718): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5718): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5718): >>>>> Normal User
,E/dalvikvm( 5718): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5718): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5718): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5718): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5718): Added TimaKesytore provider
I/SELinux ( 5722): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5722):  
I/SELinux ( 5722):  
,I/SELinux ( 5722): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5722): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5722): >>>>> Normal User
,E/dalvikvm( 5722): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5722): [DEBUG] seapp_context_lookup: seinfoCategory = shared
I/ActivityManager(  738): Killing 4824:com.wssyncmldm/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5722): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5722): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5722): Added TimaKesytore provider
,D/BadgeProvider( 5718): onCreate
,D/BadgeProvider( 5718): DatabaseHelper
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5718, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5718): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=5722, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5718): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5718): sendNotify, [notify] : null
,D/Launcher.Model( 1243): reloadBadges entered.
D/BadgeProvider( 5718): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5718): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5718): update, [UpdateCount] : 1
,D/hcjo    ( 4210): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4210): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4210): exit::IDLE
,D/InitializeManagerStateMachine( 4210): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4210): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4210): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4210): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4210): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 4210): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4210): entry::SUCCESS
,D/hcjo    ( 4210): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4210): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4210): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4210): exit::SUCCESS
,D/InitializeManagerStateMachine( 4210): entry::IDLE
,I/ActivityManager(  738): Killing 4677:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1309):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1309): showing allowed
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
I/PCWCLIENTTRACE_PushUtil( 5196): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5196): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5196): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5196): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  239): id=19 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  738): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=738
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,I/KLMS-2.3.201 : ( 5562): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5562): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449754856258
,I/KLMS-2.3.201 : ( 5562): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5581): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2527): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 5581): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/GalaxyFinderApplication( 2527): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2527): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2527): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 2488): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5745): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5745):  
,I/SELinux ( 5749): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5749):  
,I/SELinux ( 5745): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5745):  
I/SELinux ( 5745):  
,I/SELinux ( 5745): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5745): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5745): >>>>> Normal User
,E/dalvikvm( 5745): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5745): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5745): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5745): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5745): Added TimaKesytore provider
,I/SA      ( 4058): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SELinux ( 5749): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5749):  
I/SELinux ( 5749):  
I/SA      ( 4058): [BDLM] already registered in spp
,I/SELinux ( 5749): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/SA      ( 4058): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,E/SELinux ( 5749): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5749): >>>>> Normal User
,E/dalvikvm( 5749): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,I/SA      ( 4058): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4058): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4058): [OR] == isSIMCardReady false ==
,E/SELinux ( 5749): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 4058): [SCU] == networkStateCheck == true
I/SA      ( 4058): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4058): isChinaCountryCode : false
I/SA      ( 4058): [OR] == networkStateCheck true ==
,I/SA      ( 4058): [OR] GetMyCountryZoneTask
,I/SA      ( 4058): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1239): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1239): Phone number locator feature is dsiabled
,D/TimaKeyStoreProvider( 5749): in addTimaSignatureService
,I/SA      ( 4058): [SRS] prepareGetMyCountryZone
,I/SCloudBackupReceiver( 5602): Other Intent
,I/SA      ( 4058): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4058): [SSP] query invoked
,D/TimaKeyStoreProvider( 5749): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5749): Added TimaKesytore provider
,D/com.samsung.app( 1448): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1448): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      ( 4058): [TPMU] GetMccFromDB : null
I/SA      ( 4058): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4058): [TPM] isNoProxy(default) : true
D/Headlines( 4113): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4113): getCountryCode(): countryCode = PL
,I/SA      ( 4058): [RC New] Execute method=[GET] start
,D/Headlines( 4113): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4113): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4113): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4113): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4113): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4113): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4113): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm(  738): GC_EXPLICIT freed 2670K, 58% free 23720K/55844K, paused 7ms+13ms, total 133ms
,V/KVNProvider( 5749): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5749): getFindoCursor query string : 
,D/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3365): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425b9448
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,V/KVNProvider( 5749): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 4210): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4210): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4210): exit::IDLE
,D/InitializeManagerStateMachine( 4210): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4210): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4210): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4210): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4210): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 4210): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4210): entry::SUCCESS
,D/hcjo    ( 4210): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4210): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4210): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4210): exit::SUCCESS
,D/InitializeManagerStateMachine( 4210): entry::IDLE
I/ActivityManager(  738): Killing 4239:com.android.calendar/u0a142 (adj 15): empty #43
,I/SA      ( 4058): [RC New] [v2liruge] api execute + 670
,I/SA      ( 4058): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4058): AsyncTask #2 calls detatch()
,I/SA      ( 4058): [TPMU] getNetworkMcc : 
,I/SA      ( 4058): [SCU] saveMccToPreferece Start
,I/SA      ( 4058): [SCU] RegionMCC : 260
,I/SA      ( 4058): [SSP] query invoked
,I/SA      ( 4058): [TPMU] GetMccFromDB : null
,I/SA      ( 4058): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4058): [SCU] saveMccToPreferece End
,I/SA      ( 4058): [RC New] executeRequest [v2liruge] end. 692
I/SA      ( 4058): [RC New] Execute end
,I/SA      ( 4058): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4058): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 5317): BLE advertisement not supported: Build version is 19
I/jxcore-log( 5317): 
,I/HarmonyEASService(  738): Updating for all 1
,E/SMD     (  233): DCD ON
,E/WifiStateMachine(  738): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/AmoledAdjustTimer(  738): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,I/SurfaceFlinger(  239): id=19 Removed Uoast (12/13)
,I/SurfaceFlinger(  239): id=19 Removed Uoast (-2/13)
,I/ActivityManager(  738): Killing 4666:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  738): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=738 (0x0)
,D/PowerManagerService(  738): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=738, ws=WorkSource{1000}) (elapsedTime=3528)
,V/AlarmManager(  738): waitForAlarm result :8
,V/AlarmManager(  738): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  738): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  738): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
V/AlarmManager(  738): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,I/GAV2    ( 5648): Thread[GAThread,5,main]: No campaign data found.
,W/WifiP2pStateTracker(  738): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  738): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  738):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  738): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  738): updateSourceRoutes : no source routing conditions
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5196): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5196): [hasSamungAccount] - No Samsung Account
,E/SMD     (  233): DCD ON
,W/linker  ( 5196): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5196): ================================================
,I/CSTORAGE( 5196):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5196): ================================================
,D/dalvikvm( 5196): No JNI_OnLoad found in /system/lib/libterrier.so 0x425b3448, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5196): [GetString-S]
,I/terrier ( 5196): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5196): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5196): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5196): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5196): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5196): QSEECom_shutdown_app, app_id = 3
,E/terrier ( 5196): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5196): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5196): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5196): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5196): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5196): [ensureRegistration] - No Samsung account
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  738): waitForAlarm result :4
,V/AlarmManager(  738): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3691): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3691): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 310, Delta = -20
,D/CaptivePortalTracker(  738): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  738): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  738): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  738): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  738): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  738): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  738): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  738): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4210): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4210): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4210): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4210): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4210): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4210): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4210): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 4210): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4210): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4210): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4210): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4210): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4210): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4210): entry::IDLE
,E/Watchdog(  738): !@Sync 4
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 75s ago
,D/AmoledAdjustTimer(  738): prevTemp = 296, currTemp = 299, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  738): waitForAlarm result :8
,D/Headlines( 4113): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4113): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4113): Breath 17217 latestRequest time : 1449754856490 current time : 1449754873707
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1948): Disconnected process message: 10
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = -10
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 298, currTemp = 296, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  738): !@Sync 5
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 105s ago
,D/AmoledAdjustTimer(  738): prevTemp = 296, currTemp = 294, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  738): waitForAlarm result :8
,D/Headlines( 4113): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4113): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4113): Breath 47222 latestRequest time : 1449754856490 current time : 1449754903712
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1948): Disconnected process message: 10
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager(  738): waitForAlarm result :8
,V/AlarmManager(  738): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  738): !@Sync 6
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  738): waitForAlarm result :8
,D/Headlines( 4113): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4113): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4113): Breath 77213 latestRequest time : 1449754856490 current time : 1449754933703
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/PowerManagerService(  738): [PWL] Off : 140s ago
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1948): Disconnected process message: 10
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,I/ClearcutLoggerApiImpl( 1324): disconnect managed GoogleApiClient
,D/AmoledAdjustTimer(  738): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1948): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  738): !@Sync 7
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  738): waitForAlarm result :8
,D/Headlines( 4113): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4113): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4113): Breath 107255 latestRequest time : 1449754856490 current time : 1449754963745
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 180s ago
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1948): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager(  738): waitForAlarm result :8
,V/AlarmManager(  738): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  738): !@Sync 8
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  738): waitForAlarm result :8
,D/Headlines( 4113): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4113): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4113): Breath 137216 latestRequest time : 1449754856490 current time : 1449754993707
,D/Headlines( 4113): stop 
,D/Headlines( 4113): Breath.onDestroy : 
,I/ActivityManager(  738): Killing 4433:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  738): stay LED for fully charged
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  738): !@Sync 9
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  738): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  738): mCoverManager.getCoverState() : true
,D/BatteryService(  738): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1948): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  738): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  738): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON

```
