#### Test 50650278d0426ce_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5147): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5147):  
I/SELinux ( 5147):  
I/SELinux ( 5147): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5147): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5147): >>>>> Normal User
E/dalvikvm( 5147): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10034 ]
E/SELinux ( 5147): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5147): in addTimaSignatureService
D/TimaKeyStoreProvider( 5147): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5147): Added TimaKesytore provider
--------- beginning of /dev/log/system
W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
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
W/System.err( 5147): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 5147): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 5147): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 5147): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 5147): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 5147): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 5147): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 5147): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 5147): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 5147): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:105)
W/System.err( 5147): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:89)
W/System.err( 5147): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 5147): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 5147): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5147): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 5147): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5147): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 5147): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 5147): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 5147): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 5147): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 5147): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 5147): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 5147): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5147): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5147): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 5147): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 5147): 	... 21 more
D/GalaxyFinderApplication( 5147): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 5147): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 5172): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5172):  
I/ActivityManager(  765): Killing 3569:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
I/SELinux ( 5172): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5172):  
I/SELinux ( 5172):  
I/SELinux ( 5172): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5172): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5172): >>>>> Normal User
E/dalvikvm( 5172): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 5172): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5172): in addTimaSignatureService
D/TimaKeyStoreProvider( 5172): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5172): Added TimaKesytore provider
D/AndroidRuntime( 5163): 
D/AndroidRuntime( 5163): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5163): CheckJNI is OFF
D/AndroidRuntime( 5163): setted country_code = Poland
D/AndroidRuntime( 5163): setted countryiso_code = PL
D/AndroidRuntime( 5163): setted sales_code = XEO
D/AndroidRuntime( 5163): readGMSProperty: start
D/AndroidRuntime( 5163): readGMSProperty: already setted!!
D/AndroidRuntime( 5163): readGMSProperty: end
D/AndroidRuntime( 5163): addProductProperty: start
D/dalvikvm( 5163): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5163): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5163): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5163): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5163): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 5196): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5196):  
I/ActivityManager(  765): Killing 3936:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  247): GC_EXPLICIT freed 46K, 51% free 9507K/19216K, paused 2ms+3ms, total 32ms
I/SELinux ( 5196): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5196):  
I/SELinux ( 5196):  
I/SELinux ( 5196): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5196): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5196): >>>>> Normal User
E/dalvikvm( 5196): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5196): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9507K/19216K, paused 2ms+3ms, total 20ms
D/TimaKeyStoreProvider( 5196): in addTimaSignatureService
D/TimaKeyStoreProvider( 5196): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5196): Added TimaKesytore provider
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9507K/19216K, paused 2ms+3ms, total 20ms
E/memtrack( 5163): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5163): failed to load memtrack module: -2
D/dalvikvm( 5163): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5163): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy(  765): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  765): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 765  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  765): mDVFSHelper.acquire()
I/SELinux ( 5215): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5215):  
D/LockPatternUtils( 1065): isPcwEnable = null
D/AndroidRuntime( 5163): Shutting down VM
D/dalvikvm( 5163): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
I/SELinux ( 5215): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5215):  
I/SELinux ( 5215):  
I/SELinux ( 5215): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5215): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5215): >>>>> Normal User
E/dalvikvm( 5215): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5196, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/SELinux ( 5215): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5215): in addTimaSignatureService
D/TimaKeyStoreProvider( 5215): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5215): Added TimaKesytore provider
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5196): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
D/LockPatternUtils( 1065): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2101): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2101): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  246): id=13 Removed CatteryCove (8/12)
D/SurfaceWidgetView( 1241): destroyHardwareResources():1126035288
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  765): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
I/SurfaceFlinger(  246): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  246): id=7 Removed Mauncher (-2/11)
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/ContextImpl( 5196): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1441): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1241): onTrimMemory. Level: 20
I/SA      ( 4013): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4013): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4013): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5215, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
D/Mms/PackageInstallReceiver( 4295): loadAuthorityPref(): sEnableAuthority = true
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5215, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5215): Binding Chromium to the background looper Looper (main, tid 1) {422ae388}
I/chromium( 5215): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/IcingCorporaProvider( 2179): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/BrowserProcessMain( 5215): Initializing chromium process, renderers=0
,W/chromium( 5215): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5215): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5215): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5215): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5215): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5215): Remote Branch: 
I/Adreno-EGL( 5215): Local Patches: 
I/Adreno-EGL( 5215): Reconstruct Branch: 
W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5248): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5248):  
I/SELinux ( 5248): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5248):  
I/SELinux ( 5248):  
I/SELinux ( 5248): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5248): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5248): >>>>> Normal User
E/dalvikvm( 5248): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5248): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/IcingCorporaProvider( 2179): UpdateCorporaTask done [took 116 ms] updated apps [took 116 ms] 
D/TimaKeyStoreProvider( 5248): in addTimaSignatureService
D/TimaKeyStoreProvider( 5248): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5248): Added TimaKesytore provider
I/dalvikvm( 5215): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5215): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5215): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5215): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5215): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5215): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5215): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5215): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5215): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5215): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5215): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5215): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5215): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5215): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5215): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5215): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5215): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5215): VFY: replacing opcode 0x6e at 0x0000
I/ActivityManager(  765): Killing 3948:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/SystemWebViewEngine( 5215): CordovaWebView is running on device made by: samsung
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5248, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 5248): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 5266): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5266):  
I/ActivityManager(  765): Killing 4216:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SurfaceFlinger(  246): id=16 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SELinux ( 5266): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5266):  
I/SELinux ( 5266):  
I/SELinux ( 5266): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5266): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5266): >>>>> Normal User
E/dalvikvm( 5266): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5266): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5215): EGLImpl-HWUI Protected EGL context created
D/TimaKeyStoreProvider( 5266): in addTimaSignatureService
D/TimaKeyStoreProvider( 5266): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5266): Added TimaKesytore provider
D/OpenGLRenderer( 5215): Enabling debug mode 0
W/AwContents( 5215): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PowerManagerService(  765): [PWL] Off : 50s ago
D/CustomFrequencyManagerService(  765): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 765  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  765): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  765): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 765  pkgName : ACTIVITY_RESUME_BOOSTER@9
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5266, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
E/SMD     (  240): DCD ON
D/JsMessageQueue( 5215): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 5215): Trying to load lib /data/app-lib/com.test.thalitest-23/libjxcore.so 0x425d50c0
D/dalvikvm( 5215): Added shared lib /data/app-lib/com.test.thalitest-23/libjxcore.so 0x425d50c0
D/jxcore_app_log( 5215): JniHelper::setJavaVM(0x416dc528), pthread_self() = 2032637392
D/JX-Cordova( 5215): jxcore cordova android initializing
I/dalvikvm( 5215): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 5215): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5215): VFY: replacing opcode 0x6e at 0x0045
I/SELinux ( 5297): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5297):  
I/ActivityManager(  765): Killing 3961:com.sec.android.soagent/u0a37 (adj 15): empty #43
W/GAV2    ( 5266): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5297): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5297):  
I/SELinux ( 5297):  
I/SELinux ( 5297): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5297): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5297): >>>>> Normal User
E/dalvikvm( 5297): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5297): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5297): in addTimaSignatureService
D/TimaKeyStoreProvider( 5297): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5297): Added TimaKesytore provider
D/PackageIntentReceiver( 5297): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5297): Not GearManger package! 
I/SELinux ( 5313): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5313):  
I/SELinux ( 5313): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5313):  
I/SELinux ( 5313):  
I/SELinux ( 5313): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5313): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5313): >>>>> Normal User
E/dalvikvm( 5313): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5313): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5313): in addTimaSignatureService
D/TimaKeyStoreProvider( 5313): Cannot add TimaSignature Service, License check Failed
D/dalvikvm( 5215): GC_CONCURRENT freed 4909K, 34% free 12779K/19216K, paused 2ms+2ms, total 30ms
D/dalvikvm( 5215): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/ActivityThread( 5313): Added TimaKesytore provider
D/MagazineService Version( 5313): Magazine-Channel: 13
D/MagazineService Version( 5313): Magazine-Provider: 13
D/MagazineService Version( 5313): Magazine-Administrator: 11
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5313, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/HeadlinesChannelApplication( 5313): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5313): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
I/SELinux ( 5326): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5326):  
I/MagazineService::MagazineService( 5313): [onHandleIntent] ACTION_PACKAGE_INSTALLED
D/MagazineService::MagazineService( 5313): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  765): Killing 1340:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 5326): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5326):  
I/SELinux ( 5326):  
I/SELinux ( 5326): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5326): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5326): >>>>> Normal User
E/dalvikvm( 5326): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5326): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/GAV2    ( 5266): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  765): Killing 4333:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
D/TimaKeyStoreProvider( 5326): in addTimaSignatureService
D/TimaKeyStoreProvider( 5326): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5326): Added TimaKesytore provider
I/SELinux ( 5340): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5340):  
I/ActivityManager(  765): Killing 4348:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
D/SSRMv2:SIOP(  765): SIOP:: AP = 310, Delta = 0
D/CustomFrequencyManagerService(  765): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 765  tag : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 5340): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5340):  
I/SELinux ( 5340):  
I/SELinux ( 5340): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5340): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5340): >>>>> Normal User
E/dalvikvm( 5340): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 5340): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5340): in addTimaSignatureService
D/TimaKeyStoreProvider( 5340): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5340): Added TimaKesytore provider
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5340, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 5340): Package not found : com.sec.android.app.kidshome
I/SELinux ( 5353): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5353):  
I/ActivityManager(  765): Killing 4361:com.sec.esdk.elm/u0a94 (adj 15): empty #43
I/SELinux ( 5353): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5353):  
I/SELinux ( 5353):  
I/SELinux ( 5353): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5353): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5353): >>>>> Normal User
E/dalvikvm( 5353): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
E/SELinux ( 5353): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5353): in addTimaSignatureService
D/TimaKeyStoreProvider( 5353): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5353): Added TimaKesytore provider
,D/dalvikvm( 5215): GC_FOR_ALLOC freed 4662K, 29% free 15766K/21976K, paused 34ms, total 34ms
,I/ActivityManager(  765): Killing 3557:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/Finsky  ( 3653): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1785): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/dalvikvm( 1785): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1785): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1785): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1785): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1785): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1785): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1785): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1785): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1785): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1785): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1785): Submit a task: k
D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1785): Processing package: com.test.thalitest
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,D/GassUtils( 1785): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1785): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/BaseAppContext( 1785): Using Auth Proxy for data requests.
,W/dalvikvm( 1785): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1785): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1785): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1785): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1785): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1785): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1785): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1785): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1785): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1785): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1785): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1785): cleanUpNonGplusAccounts done.
,D/dalvikvm( 5215): GC_FOR_ALLOC freed 5023K, 32% free 16773K/24648K, paused 36ms, total 40ms
,I/dalvikvm-heap( 5215): Grow heap (frag case) to 22.215MB for 2459024-byte allocation
,D/ChimeraCfgMgr( 1785): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1785): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5215): GC_FOR_ALLOC freed 3765K, 36% free 17456K/27052K, paused 31ms, total 31ms
,D/dalvikvm( 5215): GC_FOR_ALLOC freed 1203K, 36% free 17356K/27052K, paused 28ms, total 28ms
,W/jxcore-log( 5215): Initializing JXcore engine
,W/jxcore-log( 5215): JXcore engine is ready
,W/jxcore-log( 5215): Starting JXcore engine
,I/Icing   ( 1785): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,W/jxcore-log( 5215): Platform android
W/jxcore-log( 5215): 
,W/jxcore-log( 5215): Process ARCH arm
W/jxcore-log( 5215): 
,D/dalvikvm( 1785): GC_CONCURRENT freed 1311K, 36% free 12474K/19216K, paused 4ms+4ms, total 43ms
,I/Icing   ( 1785): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5215): JXcore Cordova bridge is ready!
I/jxcore-log( 5215): 
,W/jxcore-log( 5215): JXcore engine is started
,I/chromium( 5215): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5215): Toggling radios to true
I/jxcore-log( 5215): 
,D/BluetoothAdapter( 5215): enable(): BT is already enabled..!
,I/WifiManager( 5215): packageName : com.test.thalitest
,I/WifiManager( 5215): setWifiEnabled : true
I/WifiService(  765): setWifiEnabled: true pid=5215, uid=10179
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5215, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  765): Failed getting userId using ActivityManagerNative
W/WifiService(  765): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5215, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  765): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  765): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  765): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  765): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  765): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  765): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  765): disconnect: pid=5215, uid=10179
,I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5215): Radios toggled
I/jxcore-log( 5215): 
,I/wpa_supplicant( 1955): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1955): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1955): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1955): Cmd 35605 not handled
E/wpa_supplicant( 1955): Cmd 35605 not handled
,I/wpa_supplicant( 1955): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/Tethering(  765): interfaceLinkStateChanged wlan0, false
,D/Tethering(  765): interfaceStatusChanged wlan0, false
D/Tethering(  765): InitialState.processMessage what=4
E/Tethering(  765): No numeric data
D/Tethering(  765): interfaceLinkStateChanged wlan0, false
,D/Tethering(  765): interfaceStatusChanged wlan0, false
I/ConnectivityService(  765): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/Tethering(  765): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  765): interfaceLinkStateChanged wlan0, false
,D/Tethering(  765): interfaceStatusChanged wlan0, false
V/NetworkStats(  765): performPollLocked(flags=0x1)
,I/wpa_supplicant( 1955): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1955): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1955): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1955): First Scan Start
,I/wpa_supplicant( 1955): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings(  765): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  765): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService(  765): InactiveState{ what=143375 }
D/WifiP2pService(  765): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/CommandListener(  237): Clearing all IP addresses on wlan0
V/NetworkStats(  765): performPollLocked() took 36ms
,I/WifiTrafficPoller(  765): evaluateTrafficStatsPolling
D/ConnectivityService(  765): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  765): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  765): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  765): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  765): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  765): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
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
D/ConnectivityService(  765): Attempting to switch to mobile
D/ConnectivityService(  765): Attempting to switch to BLUETOOTH_TETHER
,I/wpa_supplicant( 1955): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1955): Skip scan - already scanning
D/STATUSBAR-IconMerger( 1065): checkOverflow(336), More:false, Req:false Child:2
,V/RouteController(  237): /system/bin/ip -6 route del default table 2 2>&1
D/WifiP2pService(  765): InactiveState{ what=143375 }
D/WifiP2pService(  765): P2pEnabledState{ what=143375 }
,I/SELinux ( 5405): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5405):  
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  237): RTNETLINK answers: No such process
,V/RouteController(  237): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController(  237): RTNETLINK answers: No such file or directory
,D/CommandListener(  237): Clearing all IP addresses on wlan0
,W/NetworkManagementService(  765): route cmd failed: 
W/NetworkManagementService(  765): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  765): '
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  765): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  765): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  765): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  237): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller(  765): evaluateTrafficStatsPolling
,V/RouteController(  237): RTNETLINK answers: No such process
,V/RouteController(  237): /system/bin/ip -4 rule del table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
I/SELinux ( 5405): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5405):  
I/SELinux ( 5405):  
I/SELinux ( 5405): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5405): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5405): >>>>> Normal User
E/dalvikvm( 5405): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
E/SELinux ( 5405): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/WifiStateMachine(  765): Error! unhandled message{ when=-95ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  765): Error! unhandled message{ when=-94ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  765): Error! unhandled message{ when=-7ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  765): android_net_utils_resetConnections in env=0x79c27880 clazz=0x6a800001 iface=wlan0 mask=0x3
D/TimaKeyStoreProvider( 5405): in addTimaSignatureService
,D/ConnectivityService(  765): resetConnections(wlan0, 3)
V/NativeCrypto( 1319): Read error: ssl=0x7bcfd3c8: I/O error during system call, Connection timed out
D/TimaKeyStoreProvider( 5405): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5405): Added TimaKesytore provider
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): updateIfacesLocked()
V/NetworkStats(  765): performPollLocked(flags=0x1)
V/NetworkStats(  765): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): performPollLocked() took 21ms
,D/dalvikvm(  765): GC_EXPLICIT freed 25205K, 58% free 23857K/55916K, paused 14ms+15ms, total 238ms
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,V/NativeCrypto( 1319): SSL shutdown failed: ssl=0x7bcfd3c8: I/O error during system call, Broken pipe
,D/ConnectivityService(  765): handleInetConditionChange: no active default network - ignore
,I/System.out( 5405): Inside WakeupProvider
,I/System.out( 5405): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 5405): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5405): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5405): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5405): initQueue()
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  765): Killing 4397:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/Tethering(  765): Tethering got CONNECTIVITY_ACTION
D/Tethering(  765): MasterInitialState.processMessage what=3
,I/ApplicationPolicy(  765): updateDataUsageMap
,D/CaptivePortalTracker(  765): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/ConnectivityService(  765): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/accuweather( 1441): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LocSvc_java(  765): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  765): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  765): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,I/NetworkMonitor( 3870): type=WIFI subType= reason=null isConnected=false
I/PCWCLIENTTRACE_PushUtil( 5135): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5135): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5135): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5135): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5135): noConnectivity : true
,I/SELinux ( 5434): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5434):  
,I/SELinux ( 5434): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5434):  
I/SELinux ( 5434):  
,I/SELinux ( 5434): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5434): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5434): >>>>> Normal User
,E/dalvikvm( 5434): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5434): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5434): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5434): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5434): Added TimaKesytore provider
,W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5434, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  765): Killing 4416:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,E/wpa_supplicant( 1955): Cmd 35609 not handled
I/wpa_supplicant( 1955): nl80211: Received scan results (7 BSSes)
D/Tethering(  765): interfaceLinkStateChanged wlan0, false
D/Tethering(  765): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1955): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1955): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1955): Trying to associate with  'G700'
I/wpa_supplicant( 1955): Re-associate with C0.AA.48
,I/wpa_supplicant( 1955): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/SELinux ( 5448): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5448):  
,D/dalvikvm(  247): GC_EXPLICIT freed 43K, 51% free 9507K/19216K, paused 2ms+3ms, total 26ms
,I/SELinux ( 5448): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5448):  
I/SELinux ( 5448):  
,I/SELinux ( 5448): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9507K/19216K, paused 2ms+2ms, total 19ms
,E/SELinux ( 5448): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5448): >>>>> Normal User
,E/dalvikvm( 5448): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5448): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5448): in addTimaSignatureService
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9507K/19216K, paused 3ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 5448): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5448): Added TimaKesytore provider
,E/wpa_supplicant( 1955): Cmd 35605 not handled
I/wpa_supplicant( 1955): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1955): Associated with C0.AA.48
I/wpa_supplicant( 1955): freq(2412) increment count 2
I/wpa_supplicant( 1955): meet head of list.
,I/wpa_supplicant( 1955): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1955): Cmd 35847 not handled
E/wpa_supplicant( 1955): Cmd 35848 not handled
,E/wpa_supplicant( 1955): Cmd 35605 not handled
,D/Tethering(  765): interfaceLinkStateChanged wlan0, false
,D/Tethering(  765): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1955): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1955): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1955): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering(  765): interfaceLinkStateChanged wlan0, false
D/Tethering(  765): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1955): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  765): interfaceLinkStateChanged wlan0, false
,D/Tethering(  765): interfaceStatusChanged wlan0, false
,D/Tethering(  765): interfaceLinkStateChanged wlan0, true
,D/Tethering(  765): interfaceStatusChanged wlan0, true
,D/WifiNative(  765): callSECApiVoid - ID [50]
D/Tethering(  765): interfaceLinkStateChanged wlan0, true
D/Tethering(  765): interfaceStatusChanged wlan0, true
,E/Tethering(  765): No numeric data
,D/Tethering(  765): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/Tethering(  765): interfaceLinkStateChanged wlan0, true
,D/Tethering(  765): interfaceStatusChanged wlan0, true
,D/Tethering(  765): interfaceLinkStateChanged wlan0, true
,D/Tethering(  765): interfaceStatusChanged wlan0, true
I/ConnectivityService(  765): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  765): performPollLocked(flags=0x1)
D/Tethering(  765): interfaceLinkStateChanged wlan0, true
D/Tethering(  765): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5448, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,D/WifiP2pService(  765): InactiveState{ what=143375 }
,D/WifiP2pService(  765): P2pEnabledState{ what=143375 }
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,V/NetworkStats(  765): performPollLocked() took 44ms
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,I/ActivityManager(  765): Killing 4438:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5461): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5461):  
,I/SELinux ( 5461): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5461):  
I/SELinux ( 5461):  
,I/SELinux ( 5461): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5461): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5461): >>>>> Normal User
,E/dalvikvm( 5461): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5461): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5461): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5461): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5461): Added TimaKesytore provider
,W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5461, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5461): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5461): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681225191
,I/KLMS-2.3.201 : ( 5461): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/dhcpcd  ( 5473): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5473): bssid match
I/ActivityManager(  765): Killing 4454:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5480): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5480):  
,I/SELinux ( 5480): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5480):  
I/SELinux ( 5480):  
,I/SELinux ( 5480): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5480): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5480): >>>>> Normal User
,E/dalvikvm( 5480): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5480): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5480): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5480): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5480): Added TimaKesytore provider
,D/SO_AGENT( 5480): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5480): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5480, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/GAV2    ( 5266): Thread[GAThread,5,main]: No campaign data found.
,I/SA      ( 4013): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4013): [BDLM] already registered in spp
I/SA      ( 4013): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4013): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4013): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4013): [OR] == isSIMCardReady false ==
I/SA      ( 4013): [SCU] == networkStateCheck == false
,I/SA      ( 4013): [OR] onReceive END
I/ActivityManager(  765): Killing 4569:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1236): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1236): Phone number locator feature is dsiabled
,I/SELinux ( 5494): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5494):  
,D/AmoledAdjustTimer(  765): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/SELinux ( 5494): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5494):  
I/SELinux ( 5494):  
,I/SELinux ( 5494): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5494): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5494): >>>>> Normal User
,E/dalvikvm( 5494): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5494): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5494): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5494): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5494): Added TimaKesytore provider
,I/sCloudBackupApp( 5494): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5494): Other Intent
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ActivityManager(  765): Killing 4599:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 5507): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5507):  
,I/SELinux ( 5507): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5507):  
I/SELinux ( 5507):  
,I/SELinux ( 5507): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5507): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5507): >>>>> Normal User
E/dalvikvm( 5507): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5507): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5507): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5507): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5507): Added TimaKesytore provider
,W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5507, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  765): Killing 4663:com.google.android.talk/u0a105 (adj 15): empty #43
,D/Headlines( 4062): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4062): getCountryCode(): countryCode = PL
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 4062): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4062): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4062): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 4062): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4062): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4062): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5520): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5520):  
,I/SELinux ( 5520): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5520):  
I/SELinux ( 5520):  
,I/SELinux ( 5520): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5520): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 5520): >>>>> Normal User
,E/dalvikvm( 5520): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5520): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5520): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5520): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5520): Added TimaKesytore provider
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 5520): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 5520): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5520): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5520): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5520): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,E/SMD     (  240): DCD ON
,D/dalvikvm( 1319): GC_EXPLICIT freed 958K, 44% free 10793K/19216K, paused 14ms+14ms, total 74ms
,V/WebViewChromium( 5520): Binding Chromium to the main looper Looper (main, tid 1) {422b2108}
,I/chromium( 5520): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5520): Initializing chromium process, renderers=0
,W/chromium( 5520): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5520): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5520): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5520): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5520): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5520): Remote Branch: 
I/Adreno-EGL( 5520): Local Patches: 
I/Adreno-EGL( 5520): Reconstruct Branch: 
,I/NSApplication( 5520): Starting up...
,W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5520, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  765): Killing 2999:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 3327): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3327): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3327): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425e42b0
,I/SELinux ( 5576): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5576):  
,D/WifiP2pService(  765): InactiveState{ what=143375 }
,D/WifiP2pService(  765): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  765): VerifyingLinkState enter
I/SELinux ( 5576): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5576):  
I/SELinux ( 5576):  
,I/SELinux ( 5576): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5576): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5576): >>>>> Normal User
,E/dalvikvm( 5576): >>>>> com.android.email [ userId:0 | appId:10155 ]
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
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
E/SELinux ( 5576): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5576): in addTimaSignatureService
,D/WifiStateMachine(  765): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  765): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  765): evaluateTrafficStatsPolling
,D/TimaKeyStoreProvider( 5576): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5576): Added TimaKesytore provider
,D/WifiStateMachine(  765): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  765): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  765): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  765): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  765): mBoosterFLAG : 2
,I/WifiTrafficPoller(  765): current booster mode : BTCoexMode
D/ConnectivityService(  765): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService(  765): net.tcp.usercfg.wifi not found in system properties. Using defaults
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1065): refreshSignalCluster - setNWBoosterIndicators(false)
E/ConnectivityService(  765): net.tcp.delack.wifi not found in system properties. Using defaults
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
,D/ConnectivityService(  765): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/RouteController(  237): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  237): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  237): RTNETLINK answers: No such file or directory
,V/RouteController(  237): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,V/RouteController(  237): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  237): RTNETLINK answers: No such process
,V/RouteController(  237): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,V/NetworkStats(  765): updateIfacesLocked()
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): performPollLocked() took 16ms
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
D/RCPManagerService(  765): exchangeData() failure , invalid userId
,I/SELinux ( 5611): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5611):  
,I/ActivityManager(  765): Killing 4756:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 5611): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5611):  
I/SELinux ( 5611):  
,I/SELinux ( 5611): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5611): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5611): >>>>> Normal User
,E/dalvikvm( 5611): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5611): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5611): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5611): Cannot add TimaSignature Service, License check Failed
,I/SELinux ( 5623): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5623):  
,D/ActivityThread( 5611): Added TimaKesytore provider
,I/ActivityManager(  765): Killing 4777:com.wssyncmldm/1000 (adj 15): empty #43
,W/ActivityManager(  765): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5623): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5623):  
I/SELinux ( 5623):  
,I/SELinux ( 5623): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5623): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5623): >>>>> Normal User
,E/dalvikvm( 5623): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5623): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/BadgeProvider( 5611): onCreate
,D/BadgeProvider( 5611): DatabaseHelper
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5611, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/TimaKeyStoreProvider( 5623): in addTimaSignatureService
,D/BadgeProvider( 5611): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 5623): Cannot add TimaSignature Service, License check Failed
D/BadgeProvider( 5611): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5611): sendNotify, [notify] : null
D/BadgeProvider( 5611): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5611): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5611): update, [UpdateCount] : 1
D/Launcher.Model( 1241): reloadBadges entered.
,D/ActivityThread( 5623): Added TimaKesytore provider
,W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5623, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/hcjo    ( 4153): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4153): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4153): exit::IDLE
,D/InitializeManagerStateMachine( 4153): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4153): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4153): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4153): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4153): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4153): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4153): entry::SUCCESS
,D/hcjo    ( 4153): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4153): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4153): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4153): exit::SUCCESS
,D/InitializeManagerStateMachine( 4153): entry::IDLE
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1305): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1305): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1305): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1305):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1305): showing allowed
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1305): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger(  246): id=17 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  765): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=765
V/AlarmManager(  765): waitForAlarm result :4
V/AlarmManager(  765): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4062): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4062): Breath 1275 latestRequest time : 1449681225781 current time : 1449681227056
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
D/BatteryService(  765): stay LED for fully charged
,D/Tethering(  765): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  765): MasterInitialState.processMessage what=3
D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/CaptivePortalTracker(  765): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/LocSvc_java(  765): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  765): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  765): ignore wifi update if we are not in OPENING or CLOSING
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  765): mCoverManager.getCoverState() : true
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/accuweather( 1441): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3870): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5135): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5135): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5135): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5135): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/VacuumService( 1216): Vacuum at: now=1449681227336 tag=VacuumService
,I/KLMS-2.3.201 : ( 5461): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5461): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681227409
,I/KLMS-2.3.201 : ( 5461): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5480): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2545): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2545): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2545): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2545): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5480): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2415): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5644): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5644):  
,I/SELinux ( 5644): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5644):  
I/SELinux ( 5644):  
,I/SELinux ( 5644): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5644): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5644): >>>>> Normal User
E/dalvikvm( 5644): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5644): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5644): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5644): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5644): Added TimaKesytore provider
,I/SELinux ( 5657): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5657):  
,I/SELinux ( 5657): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5657):  
I/SELinux ( 5657):  
,I/SELinux ( 5657): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5657): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5657): >>>>> Normal User
,E/dalvikvm( 5657): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5657): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 4013): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4013): [BDLM] already registered in spp
,D/TimaKeyStoreProvider( 5657): in addTimaSignatureService
I/SA      ( 4013): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4013): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/TimaKeyStoreProvider( 5657): Cannot add TimaSignature Service, License check Failed
I/SA      ( 4013): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4013): [OR] == isSIMCardReady false ==
I/SA      ( 4013): [SCU] == networkStateCheck == true
I/SA      ( 4013): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4013): isChinaCountryCode : false
,I/SA      ( 4013): [OR] == networkStateCheck true ==
D/ActivityThread( 5657): Added TimaKesytore provider
I/SA      ( 4013): [OR] GetMyCountryZoneTask
,I/SA      ( 4013): [OR] onReceive END
I/ActivityManager(  765): Killing 4616:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/FactoryTest( 4712): Not factory mode
,D/FactoryTest( 4712): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4712): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4712): still no open session command from host, so toast
W/ContextImpl( 4712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  765): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  765): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 765  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  765): mDVFSHelper.acquire()
,I/SQLiteSecureOpenHelper( 2101): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2101): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1065): isPcwEnable = null
,I/SA      ( 4013): [SRS] prepareGetMyCountryZone
,D/LockPatternUtils( 1065): isPcwEnable = null
I/SA      ( 4013): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4013): [SSP] query invoked
,E/MTPRx   ( 4712): started activity for popup
,I/SA      ( 4013): [TPMU] GetMccFromDB : null
I/SA      ( 4013): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4013): [TPM] isNoProxy(default) : true
,I/SA      ( 4013): [RC New] Execute method=[GET] start
,V/KVNProvider( 5657): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5657): getFindoCursor query string : 
,D/PhoneNumberLocatorBootCompletedReceiver( 1236): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1236): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5494): Other Intent
,V/KVNProvider( 5657): getTagSearchCursor() tagSearchCursor count : 0
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ActivityManager(  765): Killing 4182:com.android.calendar/u0a142 (adj 15): empty #43
,E/SettingsReceiverActivity( 4712): PREF_DONT_ASK_AGAIN : false
,D/Headlines( 4062): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4062): getCountryCode(): countryCode = PL
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4062): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4062): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4062): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4062): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4062): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4062): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3327): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3327): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3327): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425e42b0
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,D/hcjo    ( 4153): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4153): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4153): exit::IDLE
,D/InitializeManagerStateMachine( 4153): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4153): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4153): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4153): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4153): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4153): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4153): entry::SUCCESS
,D/hcjo    ( 4153): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4153): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4153): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4153): exit::SUCCESS
,D/InitializeManagerStateMachine( 4153): entry::IDLE
,D/dalvikvm(  765): GC_EXPLICIT freed 2501K, 58% free 23710K/55916K, paused 7ms+15ms, total 154ms
,D/SettingsReceiverActivity( 4712): dev.kiessupport is : TRUE
,I/SurfaceFlinger(  246): id=18 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4712): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4712): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4712): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4712): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4712): Remote Branch: 
I/Adreno-EGL( 4712): Local Patches: 
I/Adreno-EGL( 4712): Reconstruct Branch: 
,I/HWUI    ( 4712): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4712): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  765): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 765  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  765): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  765): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 765  pkgName : ACTIVITY_RESUME_BOOSTER@9
,I/SA      ( 4013): [RC New] [v2liruge] api execute + 673
,I/SA      ( 4013): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4013): AsyncTask #2 calls detatch()
,I/SA      ( 4013): [TPMU] getNetworkMcc : 
,I/SA      ( 4013): [SCU] saveMccToPreferece Start
I/SA      ( 4013): [SCU] RegionMCC : 260
,I/SA      ( 4013): [SSP] query invoked
,I/SA      ( 4013): [TPMU] GetMccFromDB : null
I/SA      ( 4013): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4013): [SCU] saveMccToPreferece End
I/SA      ( 4013): [RC New] executeRequest [v2liruge] end. 682
I/SA      ( 4013): [RC New] Execute end
I/SA      ( 4013): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4013): [OR] GetMyCountryZoneTask Success
,E/SMD     (  240): DCD ON
,D/CustomFrequencyManagerService(  765): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 765  tag : ACTIVITY_RESUME_BOOSTER@9
,W/WifiP2pStateTracker(  765): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  765): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  765):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  765): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  765): updateSourceRoutes : no source routing conditions
,E/WifiStateMachine(  765): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ActivityManager(  765): Killing 4604:com.android.providers.calendar/u0a44 (adj 15): empty #43
,I/SurfaceFlinger(  246): id=17 Removed Uoast (12/13)
,I/SurfaceFlinger(  246): id=17 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  765): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=765 (0x0)
D/PowerManagerService(  765): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=765, ws=WorkSource{1000}) (elapsedTime=3515)
,I/GAV2    ( 5520): Thread[GAThread,5,main]: No campaign data found.
,D/SSRMv2:SIOP(  765): SIOP:: AP = 330, Delta = 20
,I/HarmonyEASService(  765): Updating for all 1
,E/SMD     (  240): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5135): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5135): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5135): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
I/CSTORAGE( 5135): ================================================
I/CSTORAGE( 5135):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 5135): ================================================
D/dalvikvm( 5135): No JNI_OnLoad found in /system/lib/libterrier.so 0x425de348, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5135): [GetString-S]
,I/terrier ( 5135): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 5135): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5135): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5135): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5135): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5135): QSEECom_shutdown_app, app_id = 3
E/terrier ( 5135): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5135): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 5135): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5135): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5135): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5135): [ensureRegistration] - No Samsung account
,I/jxcore-log( 5215): Test app app.js loaded
I/jxcore-log( 5215): 
,I/chromium( 5215): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 289, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager(  765): waitForAlarm result :4
,V/AlarmManager(  765): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 3653): GC_FOR_ALLOC freed 1868K, 20% free 15857K/19628K, paused 249ms, total 253ms
,D/PreloadUpdateManagerStateMachine( 4153): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4153): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4153): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4153): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4153): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4153): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4153): entry::IDLE
,D/CaptivePortalTracker(  765): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  765): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  765): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/CaptivePortalTracker(  765): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  765): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  765): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  765): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ConnectivityService(  765): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3653): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3653): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/PreloadUpdateManagerStateMachine( 4153): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4153): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4153): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4153): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4153): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4153): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4153): entry::IDLE
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  765): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  765): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  765): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  765): SIOP:: AP = 310, Delta = -20
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 75s ago
,D/AmoledAdjustTimer(  765): prevTemp = 291, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  765): waitForAlarm result :8
,D/Headlines( 4062): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4062): Breath 21688 latestRequest time : 1449681227868 current time : 1449681249556
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = -10
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 292, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 5
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 105s ago
,D/AmoledAdjustTimer(  765): prevTemp = 290, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :4
,V/AlarmManager(  765): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 4062): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4062): Breath 59388 latestRequest time : 1449681227868 current time : 1449681287256
,I/PhenotypeConfigurator( 1216): Scheduling Phenotype for one-off execution 3811 seconds from now (1449681287939)
,D/GetConfigurationSnapshotOperation( 1216): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1216): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1216): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1216): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1216): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1216): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1216): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1216): Thread-110(HTTPLog):isShipBuild true
,I/System.out( 1216): Thread-110(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1216): GC_CONCURRENT freed 1505K, 39% free 11859K/19216K, paused 8ms+9ms, total 110ms
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 288, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 6
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  765): waitForAlarm result :8
,D/Headlines( 4062): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4062): Breath 81675 latestRequest time : 1449681227868 current time : 1449681309543
,I/PowerManagerService(  765): [PWL] Off : 140s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 7
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  765): waitForAlarm result :8
,D/Headlines( 4062): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4062): Breath 111672 latestRequest time : 1449681227868 current time : 1449681339540
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 8
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  765): waitForAlarm result :8
,D/Headlines( 4062): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4062): Breath 141675 latestRequest time : 1449681227868 current time : 1449681369544
,D/Headlines( 4062): stop 
,D/Headlines( 4062): Breath.onDestroy : ,
,I/ActivityManager(  765): Killing 4380:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 9
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  765): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  765): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  765): TimaServiceHandler.handleMessage what =1
,D/TimaService(  765): TIMA: checkEvent, operation: 50000 subject: 10000
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,I/TLC_TIMA_PKM_initialize(  765): initializing...
,I/TLC_TIMA_PKM_initialize(  765): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  765): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  765): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  765): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  765): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  765): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  765): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  765): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  765): App is not loaded in QSEE
,D/QSEECOMAPI: (  765): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  765): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  765): Trustlet response is completed
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  765): !@Sync 10
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 275s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager(  765): waitForAlarm result :4
,V/AlarmManager(  765): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,I/SELinux ( 5821): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5821):  
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/dalvikvm(  247): GC_EXPLICIT freed 43K, 51% free 9507K/19216K, paused 8ms+28ms, total 284ms
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9507K/19216K, paused 18ms+37ms, total 197ms
,I/SELinux ( 5821): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5821):  
I/SELinux ( 5821):  
,I/SELinux ( 5821): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5821): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5821): >>>>> Normal User
,E/dalvikvm( 5821): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5821): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9507K/19216K, paused 29ms+24ms, total 210ms
,D/TimaKeyStoreProvider( 5821): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5821): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5821): Added TimaKesytore provider
,W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5821, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  765): Killing 4556:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 11
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5215): TAP version 13
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # multiplex can send data
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,D/AmoledAdjustTimer(  765): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5215): ok 1 String should be length:200
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # basic
I/jxcore-log( 5215): 
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 2 sane
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 12
,I/jxcore-log( 5215): # another
I/jxcore-log( 5215): 
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,D/AmoledAdjustTimer(  765): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5215): ok 3 sane
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 4 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 5 null
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 6 (unnamed assert)
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 7 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 8 should not throw
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5215): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 9 (unnamed assert)
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 10 (unnamed assert)
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 11 should not throw
I/jxcore-log( 5215): 
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 5215): ok 12 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 13 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 14 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # failed to get mobile documents path
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 15 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5215): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 16 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 17 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 18 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #init should register the networkChanged event
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 19 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #startBroadcasting should throw on null device name
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 20 should throw
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 21 should throw
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 22 should throw
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 23 should throw
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #startBroadcasting should throw on negative port
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 24 should throw
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #startBroadcasting should throw on too large port
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 25 should throw
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 26 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 27 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 28 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 29 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 30 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 31 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 32 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 33 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 34 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 35 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 36 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 37 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 38 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,D/AmoledAdjustTimer(  765): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/jxcore-log( 5215): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 39 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 40 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 5215): ok 41 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 42 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5215): 
,E/SMD     (  240): DCD ON
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 43 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 44 should be equal
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5215): 
,D/dalvikvm(  765): GC_CONCURRENT freed 3478K, 58% free 23704K/55916K, paused 34ms+30ms, total 871ms
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681496609.5215
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496609.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496609.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496609.5215"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
,D/WifiP2pService(  765): InactiveState{ what=139292 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  765): P2pEnabledState add service
,D/WifiP2pService(  765): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5215): start: OK
,I/jxcore-log( 5215): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
,I/io.jxcore.node.ConnectionHelper( 5215): stop
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
D/WifiP2pService(  765): InactiveState{ what=139265 }
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
D/WifiNative(  765): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
,I/jxcore-log( 5215): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
D/WifiP2pService(  765): discovery change broadcast true
D/WifiP2pService(  765): InactiveState{ what=139298 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681496737.5215
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
D/WifiP2pService(  765): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496737.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
D/WifiP2pService(  765): remove client information from framework
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  765): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496737.5215"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496737.5215"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
D/WifiP2pService(  765): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5215): start: OK
,I/jxcore-log( 5215): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
,I/io.jxcore.node.ConnectionHelper( 5215): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/WifiP2pService(  765): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
,I/jxcore-log( 5215): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681496807.5215
D/WifiP2pService(  765): InactiveState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState add service
,D/WifiP2pService(  765): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496807.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiP2pService(  765): InactiveState{ what=139265 }
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
D/WifiNative(  765): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496807.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496807.5215"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
D/WifiP2pService(  765): discovery change broadcast true
D/WifiP2pService(  765): InactiveState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  765): P2pEnabledState clear service
I/io.jxcore.node.ConnectionHelper( 5215): start: OK
I/jxcore-log( 5215): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
I/io.jxcore.node.ConnectionHelper( 5215): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
D/WifiP2pService(  765): remove client information from framework
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState clear service request
I/jxcore-log( 5215): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681496854.5215
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
D/WifiP2pService(  765): InactiveState{ what=139268 }
D/WifiP2pService(  765): InactiveState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState add service
D/WifiP2pService(  765): add a new client
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  765): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
D/WifiP2pService(  765): InactiveState{ what=139265 }
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496854.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496854.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496854.5215"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  765): InactiveState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState clear service
,D/WifiP2pService(  765): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5215): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
,I/jxcore-log( 5215): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
I/io.jxcore.node.ConnectionHelper( 5215): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  765): P2pEnabledState clear service request
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
,I/jxcore-log( 5215): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681496897.5215
D/WifiP2pService(  765): InactiveState{ what=139268 }
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/WifiP2pService(  765): discovery change broadcast false
D/WifiP2pService(  765): InactiveState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState add service
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,D/WifiNative(  765): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
D/WifiP2pService(  765): add a new client
D/WifiP2pService(  765): InactiveState{ what=139265 }
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496897.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496897.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496897.5215"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  765): discovery change broadcast true
D/WifiP2pService(  765): InactiveState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5215): start: OK
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
,I/jxcore-log( 5215): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
,I/io.jxcore.node.ConnectionHelper( 5215): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
D/WifiP2pService(  765): remove client information from framework
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState clear service request
D/WifiP2pService(  765): InactiveState{ what=139268 }
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
,I/jxcore-log( 5215): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/WifiP2pService(  765): discovery change broadcast false
D/WifiP2pService(  765): InactiveState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState add service
D/WifiP2pService(  765): add a new client
D/WifiP2pService(  765): InactiveState{ what=139265 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681496940.5215
D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  765): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
D/WifiP2pService(  765): discovery change broadcast true
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/WifiP2pService(  765): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496940.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496940.5215"}
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496940.5215"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
D/WifiP2pService(  765): InactiveState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState clear service
D/WifiP2pService(  765): remove client information from framework
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState clear service request
D/WifiP2pService(  765): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5215): start: OK
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
,I/jxcore-log( 5215): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/WifiP2pService(  765): InactiveState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState add service
D/WifiP2pService(  765): add a new client
D/WifiP2pService(  765): InactiveState{ what=139265 }
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
I/io.jxcore.node.ConnectionHelper( 5215): stop
D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  765): callSECApiBoolean - ID [13]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
,I/jxcore-log( 5215): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
D/WifiP2pService(  765): discovery change broadcast true
D/WifiP2pService(  765): InactiveState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681496980.5215
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
D/WifiP2pService(  765): remove client information from framework
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState clear service request
D/WifiP2pService(  765): InactiveState{ what=139268 }
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  765): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496980.5215"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496980.5215"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681496980.5215"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5215): start: OK
D/WifiP2pService(  765): InactiveState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState add service
,D/WifiP2pService(  765): add a new client,
I/jxcore-log( 5215): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
I/io.jxcore.node.ConnectionHelper( 5215): stop
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1,
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117),
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
,I/jxcore-log( 5215): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative(  765): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
D/WifiP2pService(  765): InactiveState{ what=139265 }
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681497010.5215
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681497010.5215"}
,D/WifiP2pService(  765): discovery change broadcast true
D/WifiP2pService(  765): InactiveState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  765): P2pEnabledState clear service
D/WifiP2pService(  765): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681497010.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681497010.5215"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState clear service request
D/WifiP2pService(  765): InactiveState{ what=139268 }
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/WifiP2pService(  765): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5215): start: OK
,I/jxcore-log( 5215): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
I/io.jxcore.node.ConnectionHelper( 5215): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
D/WifiP2pService(  765): InactiveState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState add service
,D/WifiP2pService(  765): add a new client
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
,I/jxcore-log( 5215): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  765): callSECApiBoolean - ID [13]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681497044.5215
D/WifiP2pService(  765): InactiveState{ what=139265 }
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681497044.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
D/WifiP2pService(  765): discovery change broadcast true
D/WifiP2pService(  765): InactiveState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState clear service
D/WifiP2pService(  765): remove client information from framework
D/WifiP2pService(  765): InactiveState{ what=139307 }
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681497044.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681497044.5215"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState clear service request
D/WifiP2pService(  765): InactiveState{ what=139268 }
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/WifiP2pService(  765): discovery change broadcast false
D/WifiP2pService(  765): InactiveState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5215): start: OK
,I/jxcore-log( 5215): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
I/io.jxcore.node.ConnectionHelper( 5215): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  765): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState add service
D/WifiP2pService(  765): add a new client
D/WifiP2pService(  765): InactiveState{ what=139265 }
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
,I/jxcore-log( 5215): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681497086.5215
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
D/WifiP2pService(  765): discovery change broadcast true
D/WifiP2pService(  765): InactiveState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState clear service
D/WifiP2pService(  765): remove client information from framework
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681497086.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
D/WifiP2pService(  765): P2pEnabledState clear service request
D/WifiP2pService(  765): InactiveState{ what=139268 }
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  765): discovery change broadcast false
W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681497086.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681497086.5215"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  765): InactiveState{ what=139292 }
D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5215): start: OK
,I/jxcore-log( 5215): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
I/io.jxcore.node.ConnectionHelper( 5215): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
D/WifiP2pService(  765): P2pEnabledState add service
D/WifiP2pService(  765): add a new client
D/WifiP2pService(  765): InactiveState{ what=139265 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,I/jxcore-log( 5215): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  765): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
D/WifiP2pService(  765): discovery change broadcast true
D/WifiP2pService(  765): InactiveState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState clear service
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
D/WifiP2pService(  765): remove client information from framework
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState clear service request
D/WifiP2pService(  765): InactiveState{ what=139268 }
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/WifiP2pService(  765): discovery change broadcast false
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
,E/wpa_supplicant( 1955): Cmd 35609 not handled
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,I/jxcore-log( 5215): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681498153.5215
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681498153.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681498153.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681498153.5215"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
,D/WifiP2pService(  765): InactiveState{ what=139292 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
,D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5215): start: OK
,I/jxcore-log( 5215): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
D/WifiP2pService(  765): P2pEnabledState add service
D/WifiP2pService(  765): add a new client
,I/jxcore-log( 5215): ok 66 Cannot call startBroadcasting twice
I/jxcore-log( 5215): 
,I/io.jxcore.node.ConnectionHelper( 5215): stop
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null,
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
,I/jxcore-log( 5215): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
D/WifiP2pService(  765): InactiveState{ what=139265 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
D/WifiNative(  765): callSECApiBoolean - ID [13]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
,D/WifiP2pService(  765): discovery change broadcast true
,D/WifiP2pService(  765): InactiveState{ what=139298 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  765): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
D/WifiP2pService(  765): remove client information from framework
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
D/WifiP2pService(  765): P2pEnabledState clear service request
D/WifiP2pService(  765): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/WifiP2pService(  765): discovery change broadcast false
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/wpa_supplicant( 1955): P2P-DEVICE-FOUND 9E.BA.C5 p2p_dev_addr=9E.3A.C5 pri_dev_type=3-0050F204-5   '3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,E/wpa_supplicant( 1955): Cmd 35609 not handled
,D/WifiP2pService(  765): InactiveState{ what=147477 }
,D/WifiP2pService(  765): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  765): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  765): InactiveState{ what=139283 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  765): DefaultState{ what=139283 }
,D/WifiDisplayController(  765): Received list of peers.
,D/WifiDisplayController(  765):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,I/jxcore-log( 5215): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681499784.5215
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681499784.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681499784.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681499784.5215"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
,D/WifiP2pService(  765): InactiveState{ what=139292 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  765): P2pEnabledState add service
,D/WifiP2pService(  765): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5215): start: OK
,I/jxcore-log( 5215): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
,I/io.jxcore.node.ConnectionHelper( 5215): connect: Trying to connect to peer with ID foobar
,D/io.jxcore.node.ConnectionHelper( 5215): hasConnection: No connection with peer with ID foobar
,W/io.jxcore.node.ConnectionHelper( 5215): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,E/io.jxcore.node.ConnectionHelper( 5215): connect: Invalid Bluetooth address: foobar
,I/jxcore-log( 5215): ok 69 Should not connect to a bad peer
I/jxcore-log( 5215): 
,I/io.jxcore.node.ConnectionHelper( 5215): stop
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
,I/jxcore-log( 5215): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
D/WifiP2pService(  765): InactiveState{ what=139265 }
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  765): callSECApiBoolean - ID [13]
D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
,D/WifiP2pService(  765): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
D/WifiP2pService(  765): InactiveState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
D/WifiP2pService(  765): P2pEnabledState clear service
,D/WifiP2pService(  765): remove client information from framework
,D/WifiP2pService(  765): InactiveState{ what=139307 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  765): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
D/WifiP2pService(  765): InactiveState{ what=139268 }
,I/PowerManagerService(  765): [PWL] Off : 330s ago
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
,D/WifiP2pService(  765): InactiveState{ what=147493 }
,D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  765): discovery change broadcast false
,I/wpa_supplicant( 1955): P2P-DEVICE-FOUND 9E.BA.C5 p2p_dev_addr=9E.3A.C5 pri_dev_type=3-0050F204-5   '3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,E/wpa_supplicant( 1955): Cmd 35609 not handled
,D/WifiP2pService(  765): InactiveState{ what=147477 }
,D/WifiP2pService(  765): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  765): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  765): InactiveState{ what=139283 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  765): DefaultState{ what=139283 }
,D/WifiDisplayController(  765): Received list of peers.
,D/WifiDisplayController(  765):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,I/jxcore-log( 5215): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681501417.5215
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681501417.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681501417.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681501417.5215"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
,D/WifiP2pService(  765): InactiveState{ what=139292 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  765): P2pEnabledState add service
,D/WifiP2pService(  765): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5215): start: OK
,I/jxcore-log( 5215): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
,D/io.jxcore.node.ConnectionHelper( 5215): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
,E/io.jxcore.node.ConnectionHelper( 5215): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
,D/io.jxcore.node.ConnectionHelper( 5215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 5215): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
,I/jxcore-log( 5215): ok 72 Disconnect should fail to a non-existant peer 
I/jxcore-log( 5215): 
,I/io.jxcore.node.ConnectionHelper( 5215): stop
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: NOT_INITIALIZED
,I/jxcore-log( 5215): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 5215): 
D/WifiP2pService(  765): InactiveState{ what=139265 }
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  765): callSECApiBoolean - ID [13]
,D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
,D/WifiP2pService(  765): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
,D/WifiP2pService(  765): InactiveState{ what=139298 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  765): P2pEnabledState clear service
,D/WifiP2pService(  765): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
D/WifiP2pService(  765): P2pEnabledState clear service request
D/WifiP2pService(  765): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/WifiP2pService(  765): discovery change broadcast false
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/wpa_supplicant( 1955): Cmd 35609 not handled
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,I/jxcore-log( 5215): # ThaliEmitter can discover and connect to peers
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # teardown
I/jxcore-log( 5215): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: 38:94:96:B5:06:DC 1449681505170.5215
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5215): initialize: My bluetooth address is 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): verifyIdentityString: Identity string created: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681505170.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): start: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681505170.5215"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): start: Identity string: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"1449681505170.5215"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
,D/WifiP2pService(  765): InactiveState{ what=139292 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  765): P2pEnabledState add service
,D/WifiP2pService(  765): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5215): start: OK
,I/jxcore-log( 5215): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 5215): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): startWifiPeerDiscovery: Already started
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): restart: Restarting...
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: RUNNING
,E/SMD     (  240): DCD ON
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local service added successfully
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
D/WifiP2pService(  765): InactiveState{ what=139265 }
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  765): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
D/WifiP2pService(  765): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState clear service request
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
D/WifiP2pService(  765): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/WifiP2pService(  765): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): restart: Restarting...
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  765): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
,I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
D/WifiP2pService(  765): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
,D/AmoledAdjustTimer(  765): prevTemp = 279, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/wpa_supplicant( 1955): Cmd 35609 not handled
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,E/SMD     (  240): DCD ON
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): start: Starting peer discovery...
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
D/WifiP2pService(  765): InactiveState{ what=139265 }
D/WifiP2pService(  765): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  765): callSECApiBoolean - ID [13]
D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery started successfully
D/WifiP2pService(  765): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  240): DCD ON
,I/wpa_supplicant( 1955): P2P-DEVICE-FOUND 9E.BA.C5 p2p_dev_addr=9E.3A.C5 pri_dev_type=3-0050F204-5   '3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,E/wpa_supplicant( 1955): Cmd 35609 not handled
,D/WifiP2pService(  765): InactiveState{ what=147477 }
,D/WifiP2pService(  765): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  765): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  765): InactiveState{ what=139283 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  765): DefaultState{ what=139283 }
,D/WifiDisplayController(  765): Received list of peers.
,D/WifiDisplayController(  765):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  765): InactiveState{ what=139283 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  765): DefaultState{ what=139283 }
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/WifiP2pService(  765): InactiveState{ what=139301 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139301 }
,D/WifiP2pManager( 5215): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service request added successfully
D/WifiP2pService(  765): P2pEnabledState add service request
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/WifiP2pService(  765): InactiveState{ what=139310 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  765): P2pEnabledState discover services
,I/WifiService(  765): setWifiEnabled: true pid=765, uid=1000
,D/WifiStateMachine(  765): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  765): callSECApiBoolean - ID [13]
,D/WifiService(  765): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1955): P2P-DEVICE-FOUND 9E.BA.C5 p2p_dev_addr=9E.3A.C5 pri_dev_type=3-0050F204-5   '3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,E/wpa_supplicant( 1955): Cmd 35609 not handled
,D/WifiP2pService(  765): InactiveState{ what=147477 }
,D/WifiP2pService(  765): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  765): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  765): InactiveState{ what=139283 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  765): DefaultState{ what=139283 }
,D/WifiDisplayController(  765): Received list of peers.
,D/WifiDisplayController(  765):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,E/Watchdog(  765): !@Sync 13
,I/wpa_supplicant( 1955): P2P-DEVICE-FOUND 9E.BA.C5 p2p_dev_addr=9E.3A.C5 pri_dev_type=3-0050F204-5   '3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1955): Cmd 35609 not handled
D/WifiP2pService(  765): InactiveState{ what=147477 }
D/WifiP2pService(  765): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  765): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  765): InactiveState{ what=139283 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  765): DefaultState{ what=139283 }
,D/WifiDisplayController(  765): Received list of peers.
,D/WifiDisplayController(  765):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  240): DCD ON
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1955): Cmd 35609 not handled
,D/AmoledAdjustTimer(  765): prevTemp = 280, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1949): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1949): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/wpa_supplicant( 1955): P2P-DEVICE-FOUND 36.0A.E2 p2p_dev_addr=36.0A.E2 pri_dev_type=10-0050F204-5   's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1955): Cmd 35609 not handled
D/WifiP2pService(  765): InactiveState{ what=147477 }
D/WifiP2pService(  765): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  765): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  765): InactiveState{ what=139283 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  765): DefaultState{ what=139283 }
,D/WifiDisplayController(  765): Received list of peers.
,D/WifiDisplayController(  765):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  765):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  765): InactiveState{ what=147494 }
,D/WifiP2pService(  765): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  765): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"1449681507386.4656"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B 1449681507386.4656 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): onServiceListChanged: 1 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 5215): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: 1449681507386.4656, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
,I/io.jxcore.node.ConnectionHelper( 5215): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:9D:93:0B
,I/io.jxcore.node.ConnectionHelper( 5215): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
,D/io.jxcore.node.ConnectionHelper( 5215): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
,I/io.jxcore.node.ConnectionHelper( 5215): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,W/io.jxcore.node.ConnectionHelper( 5215): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5215): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 536)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 5215): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1949): RFCOMM connect
,D/BTIF_SOCK( 1949): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 1949): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:9d:93:0b
,D/IOP_DB_BT( 1949): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1949): db_query_add_key: key KEY_LMP_VER, value 6:16646
,D/IOP_DB_BT( 1949): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1949): db_query_execute: result 1
,D/IOP_DB_BT( 1949): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:9d:93:0b
,D/IOP_DB_BT( 1949): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1949): db_query_add_key: key KEY_LMP_VER, value 6:16646
,D/IOP_DB_BT( 1949): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1949): db_query_execute: result 1
,D/GKI_LINUX( 1949): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/BluetoothSocket( 5215): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,E/SMD     (  240): DCD ON
,D/IOP_DB_BT( 1949): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:9d:93:0b
,D/IOP_DB_BT( 1949): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1949): db_query_add_key: key KEY_LMP_VER, value 6:16646
,D/IOP_DB_BT( 1949): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1949): db_query_execute: result 1
,D/        ( 1949): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,D/KeyguardViewMediator( 1065): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1065): isGear1: device is not B1!
,E/bt-btif ( 1949): BTA_JV_DISCOVERY_COMP_EVT (error code = 0)
,E/bt-btif ( 1949): BTA_JvRfcommConnect
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btif ( 1949): RFCOMM: PORT_SUCCESS
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onSocketConnected: Authenticating next: [34:FC:EF:9D:93:0B 1449681507386.4656 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5215): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 536)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5215): onBytesWritten: 77 bytes successfully written (thread ID: 537)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5215): Outgoing connection initialized (*handshake* thread ID: 537)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5215): Exiting thread (thread ID: 536)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5215): Entering thread (ID: 537)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5215): onBytesRead: Read 77 bytes successfully (thread ID: 537)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5215): Handshake succeeded with [34:FC:EF:9D:93:0B 1449681507386.4656 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onAuthenticated: Fully connected: [34:FC:EF:9D:93:0B 1449681507386.4656 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5215): Exiting thread (ID: 537)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnected: [34:FC:EF:9D:93:0B 1449681507386.4656 34:FC:EF:9D:93:0B]
,I/io.jxcore.node.ConnectionHelper( 5215): onConnected: Outgoing connection, peer ID: 34:FC:EF:9D:93:0B, name: 1449681507386.4656, Bluetooth address: 34:FC:EF:9D:93:0B
,D/io.jxcore.node.ConnectionHelper( 5215): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
,I/io.jxcore.node.ConnectionHelper( 5215): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
,E/bt-btif ( 1949): RFCOMM: PORT_FAILURE
,I/io.jxcore.node.ConnectionHelper( 5215): onConnected: Outgoing socket thread, for peer with ID 34:FC:EF:9D:93:0B, created successfully
,D/io.jxcore.node.ConnectionHelper( 5215): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 5215): Entering thread (ID: 538)
,D/io.jxcore.node.OutgoingSocketThread( 5215): Server socket local port: 52549
,I/io.jxcore.node.OutgoingSocketThread( 5215): Now accepting connections...
,I/BTConnectionReceiver( 2179): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2179): Bluetooth Device Name: Thali Test's G2
,I/SELinux ( 5892): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5892):  
,I/io.jxcore.node.ConnectionHelper( 5215): onListeningForIncomingConnections: Outgoing connection is using port 52549 (peer ID: 34:FC:EF:9D:93:0B)
,I/jxcore-log( 5215): ok 75 Should be able to connect without error
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): ok 76 Port should be within range
I/jxcore-log( 5215): 
,D/io.jxcore.node.ConnectionHelper( 5215): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
,I/io.jxcore.node.ConnectionHelper( 5215): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:9D:93:0B
,I/io.jxcore.node.OutgoingSocketThread( 5215): close
I/io.jxcore.node.OutgoingSocketThread( 5215): closeLocalSocketAndStreams: Nothing to close
,I/io.jxcore.node.OutgoingSocketThread( 5215): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 5215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 5215): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:9D:93:0B
,E/io.jxcore.node.OutgoingSocketThread( 5215): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 5215): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 5215): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 5215): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:55)
E/io.jxcore.node.OutgoingSocketThread( 5215): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:98)
E/io.jxcore.node.OutgoingSocketThread( 5215): 	at java.net.ServerSocket.implAccept(ServerSocket.java:203)
E/io.jxcore.node.OutgoingSocketThread( 5215): 	at java.net.ServerSocket.accept(ServerSocket.java:128)
E/io.jxcore.node.OutgoingSocketThread( 5215): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:71)
,W/io.jxcore.node.ConnectionHelper( 5215): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Failed to create local streams: Socket closed
E/io.jxcore.node.ConnectionHelper( 5215): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 5215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.OutgoingSocketThread( 5215): Exiting thread (ID: 538)
,I/jxcore-log( 5215): ok 77 Should be able to disconnect without error
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): setting stopBroadcasting callback and ending test.
I/jxcore-log( 5215): 
,I/jxcore-log( 5215): # setup
I/jxcore-log( 5215): 
,E/bt-btif ( 1949): RFCOMM: PORT_SUCCESS
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Incoming connection initialized (thread ID: 539)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5215): Entering thread (ID: 539)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Waiting for incoming connections...
,D/BluetoothAdapterService(1113500352)( 1949): Get Bonded Devices being called
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): onBytesRead: Read 77 bytes successfully (thread ID: 539)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Got valid identity from [34:FC:EF:9D:93:0B 1449681507386.4656 34:FC:EF:9D:93:0B]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): onBytesWritten: 77 bytes successfully written (thread ID: 539)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): removeThreadFromList: Removing thread with ID 539
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Handshake thread disposed (thread ID: 539)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B 1449681507386.4656 34:FC:EF:9D:93:0B]
I/SELinux ( 5892): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5892):  
I/SELinux ( 5892):  
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5215): Exiting thread (ID: 539)
,I/SELinux ( 5892): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnected: [34:FC:EF:9D:93:0B 1449681507386.4656 34:FC:EF:9D:93:0B]
,I/io.jxcore.node.ConnectionHelper( 5215): onConnected: Incoming connection, peer ID: 34:FC:EF:9D:93:0B, name: 1449681507386.4656, Bluetooth address: 34:FC:EF:9D:93:0B
E/SELinux ( 5892): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/io.jxcore.node.ConnectionHelper( 5215): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
E/dalvikvm( 5892): >>>>> Normal User
E/dalvikvm( 5892): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,I/io.jxcore.node.ConnectionHelper( 5215): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
,E/SELinux ( 5892): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/io.jxcore.node.ConnectionHelper( 5215): onConnected: Incoming socket thread, for peer with ID 34:FC:EF:9D:93:0B, created successfully
,D/io.jxcore.node.ConnectionHelper( 5215): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 5215): Entering thread (ID: 540)
,D/BluetoothAdapterService(1113500352)( 1949): Get Bonded Devices being called
E/io.jxcore.node.IncomingSocketThread( 5215): Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5215): java.net.ConnectException: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5215): 	at libcore.io.IoBridge.connect(IoBridge.java:114)
E/io.jxcore.node.IncomingSocketThread( 5215): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:192)
E/io.jxcore.node.IncomingSocketThread( 5215): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:172)
E/io.jxcore.node.IncomingSocketThread( 5215): 	at java.net.Socket.startupSocket(Socket.java:566)
E/io.jxcore.node.IncomingSocketThread( 5215): 	at java.net.Socket.<init>(Socket.java:226)
E/io.jxcore.node.IncomingSocketThread( 5215): 	at io.jxcore.node.IncomingSocketThread.run(IncomingSocketThread.java:49)
E/io.jxcore.node.IncomingSocketThread( 5215): Caused by: libcore.io.ErrnoException: connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5215): 	at libcore.io.Posix.connect(Native Method)
E/io.jxcore.node.IncomingSocketThread( 5215): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:85)
E/io.jxcore.node.IncomingSocketThread( 5215): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:127)
E/io.jxcore.node.IncomingSocketThread( 5215): 	at libcore.io.IoBridge.connect(IoBridge.java:112)
E/io.jxcore.node.IncomingSocketThread( 5215): 	... 5 more
W/io.jxcore.node.ConnectionHelper( 5215): onDisconnected: Incoming connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
I/io.jxcore.node.ConnectionHelper( 5215): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 540
I/io.jxcore.node.IncomingSocketThread( 5215): closeLocalSocketAndStreams: Nothing to close
,I/io.jxcore.node.IncomingSocketThread( 5215): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 5215): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.IncomingSocketThread( 5215): Exiting thread (ID: 540)
,E/bt-btif ( 1949): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,D/TimaKeyStoreProvider( 5892): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5892): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5892): Added TimaKesytore provider
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1955): Cmd 35609 not handled
,D/UserAnalysis.PlaceProvider( 5892): Create SecureDbHelper
,D/UserAnalysis.CarAnalyzer( 5892): Create SecureDbHelper
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=5892, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  765): Killing 4515:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
,I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 1955): P2P-DEVICE-FOUND 9E.BA.C5 p2p_dev_addr=9E.3A.C5 pri_dev_type=3-0050F204-5   '3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1955): Cmd 35609 not handled
D/WifiP2pService(  765): InactiveState{ what=147477 }
D/WifiP2pService(  765): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  765): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  765): InactiveState{ what=139283 }
,D/WifiP2pService(  765): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  765): DefaultState{ what=139283 }
,D/WifiDisplayController(  765): Received list of peers.
,D/WifiDisplayController(  765):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  765):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log( 5215): Toggling radios to false
I/jxcore-log( 5215): 
,I/WifiManager( 5215): packageName : com.test.thalitest
,I/WifiManager( 5215): setWifiEnabled : false
,I/WifiService(  765): setWifiEnabled: false pid=5215, uid=10179
,D/BluetoothAdapterService(1113500352)( 1949): unRegister RemoteMessageListener
,D/HeadsetService( 1949): registerMessageListener
,D/HeadsetStateMachine( 1949): Disconnected process message: 80
,D/HeadsetStateMachine( 1949): processUnRegisterMessageListener : 2
,D/BluetoothAdapterState( 1949): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,I/BluetoothAdapterState( 1949): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1949): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 1949): updateAdapterState state is 13
,D/BluetoothAdapterService( 1949): Broadcasting updateAdapterState() to 1 receivers.
,I/BluetoothPbapService( 1949): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
,D/BluetoothAdapterService( 1949): Autoconnection is available 
,D/BluetoothAdapterService( 1949): updateAdapterState prevState = 12newState = 13
,I/jxcore-log( 5215): Radios toggled
I/jxcore-log( 5215): 
,D/BluetoothAdapterService( 1949): terminating service from this receiver
,E/SMD     (  240): DCD ON
,D/PhoneApp( 1236): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,W/InputMethodManagerService(  765): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  765): [BT Setting State] State =13
,D/STATUSBAR-IconMerger( 1065): checkOverflow(336), More:false, Req:false Child:2
,W/ContextImpl( 1949): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,I/QuickConnect[1.1][2] ( 3327): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
,I/wpa_supplicant( 1955): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1955): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1955): Skip scan - bUseNetwork false
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
,I/BluetoothAdapterState( 1949): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterState( 1949): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 1949): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/BtOppRfcommListener( 1949): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:567)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:544)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:454)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Socket is null
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onIncomingConnectionFailed: Socket is null
,E/bt-btif ( 1949): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1949): cmd socket is not created
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): onServerStopped: Restarting the server...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5215): shutdown
,W/Settings(  765): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/btif_config_util( 1949): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onConnectionFailed: Socket is null
,I/WifiStateMachine(  765): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService(  765): InactiveState{ what=143375 }
D/WifiP2pService(  765): P2pEnabledState{ what=143375 }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onBluetoothAdapterScanModeChanged: Mode changed to 20
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onBluetoothAdapterScanModeChanged: Bluetooth disabled, stopping...
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,I/BtOppRfcommListener( 1949): stopping Accept Thread
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,W/BluetoothAdapter( 5215): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1949): SOCK FLAG = 0 ***********************
E/BluetoothServiceJni( 1949): Socket listen failed: 2
,E/BluetoothAdapterService(1113500352)( 1949): Failed to create socket channel
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Failed to create the socket listener thread: Error: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): java.io.IOException: Error: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): 	at android.bluetooth.BluetoothAdapter.createNewRfcommSocketAndRecord(BluetoothAdapter.java:1229)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): 	at android.bluetooth.BluetoothAdapter.listenUsingInsecureRfcommWithServiceRecord(BluetoothAdapter.java:1166)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.<init>(BluetoothServerThread.java:73)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector.startListeningForIncomingConnections(BluetoothConnector.java:135)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector.onServerStopped(BluetoothConnector.java:312)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:121)
,I/BtOppRfcommListener( 1949): BluetoothSocket listen thread finished
,D/IOP_DB_BT( 1949): db_close: nbr users 0
,D/IOP_DB_BT( 1949): db_close: free database
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5215): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5215): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): stop: Stopping peer discovery...
D/WifiP2pService(  765): InactiveState{ what=139298 }
D/WifiP2pService(  765): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 5215): onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/WifiP2pService(  765): P2pEnabledState clear service
,D/BluetoothPbap( 1305): Proxy object disconnected
,D/PbapServerProfile( 1305): Bluetooth service disconnected
,V/BluetoothEventManager( 1305): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/CommandListener(  237): Clearing all IP addresses on wlan0
W/ContextImpl( 1305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 1305): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5215): Local services cleared successfully
,D/AuthorizationBluetoothService( 1319): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WifiP2pService(  765): InactiveState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState{ what=139307 }
D/WifiP2pService(  765): P2pEnabledState clear service request
D/WifiP2pService(  765): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Service requests cleared successfully
,I/WifiTrafficPoller(  765): evaluateTrafficStatsPolling
D/WifiP2pService(  765): InactiveState{ what=139268 }
D/ConnectivityService(  765): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  765): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  765): net.tcp.usercfg.default not found in system default properties
I/wpa_supplicant( 1955): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
,I/wpa_supplicant( 1955): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5215): Peer discovery stopped successfully
E/ConnectivityService(  765): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  765): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  765): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1065): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1065): refreshSignalCluster - setNWBoosterIndicators(false)
D/WifiP2pService(  765): InactiveState{ what=147493 }
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/WifiP2pService(  765): P2pEnabledState{ what=147493 }
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/WifiP2pService(  765): discovery change broadcast false
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/ConnectivityService(  765): Attempting to switch to mobile
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/ConnectivityService(  765): Attempting to switch to BLUETOOTH_TETHER
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  765): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  765): Error! unhandled message{ when=-9ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  765): InactiveState{ what=131204 }
D/WifiP2pService(  765): P2pEnabledState{ what=131204 }
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
D/WifiDisplayController(  765): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,V/RouteController(  237): /system/bin/ip -6 route del default table 2 2>&1
,D/QuickConnect[1.1][2] ( 3327): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiP2pService(  765): sending p2p connection changed broadcast: FAILED
W/WifiP2pStateTracker(  765): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController(  765): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter(  765): onP2pDisconnected
D/IpRemoteDisplayController(  765): disconnectWfdBridgeServer
,D/IpRemoteDisplayController(  765): WfdBridgeServer is already null
D/QuickConnect[1.1][2] ( 3327): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
E/WifiStateMachine(  765): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: FAILED
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
D/WifiP2pService(  765): sending p2p connection changed broadcast: DISCONNECTED
D/WifiDisplayController(  765): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  765): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  765): disconnect
D/WifiDisplayController(  765): updateConnection
D/WifiDisplayController(  765): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter(  765): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5215): onWifiStateChanged: State changed to 1
D/QuickConnect[1.1][2] ( 3327): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
D/QuickConnect[1.1][2] ( 3327): P2pHelper.cancelConnectPeer -  mTargetList clear all 
D/QuickConnect[1.1][2] ( 3327): P2pHelper.removeP2pConfirm - skip: false
,D/QuickConnect[1.1][2] ( 3327): CentralActionManager.removeHoldingIntentAll - all request done.
D/QuickConnect[1.1][2] ( 3327): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,V/RouteController(  237): RTNETLINK answers: No such process
,D/QuickConnect[1.1][2] ( 3327): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,V/RouteController(  237): /system/bin/ip -6 rule del table 2 2>&1
D/WifiP2pService(  765): P2pDisablingState
W/WifiP2pStateTracker(  765): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController(  765): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter(  765): onP2pDisconnected
D/IpRemoteDisplayController(  765): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  765): WfdBridgeServer is already null
,D/QuickConnect[1.1][2] ( 3327): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,D/QuickConnect[1.1][2] ( 3327): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService(  765): P2pDisablingState{ what=139283 }
D/WifiP2pService(  765): DefaultState{ what=139283 }
D/WifiDisplayController(  765): Received list of peers.
D/WifiDisplayAdapter(  765): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService(  765): P2pDisablingState{ what=139287 }
D/WifiP2pService(  765): DefaultState{ what=139287 }
D/WifiP2pService(  765): P2pDisablingState{ what=147458 }
D/WifiP2pService(  765): p2p socket connection lost
,D/QuickConnect[1.1][2] ( 3327): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,V/RouteController(  237): RTNETLINK answers: No such file or directory
D/WifiP2pService(  765): P2pDisabledState
D/WifiP2pService(  765): P2pDisabledState{ what=139376 }
D/WifiP2pService(  765): DefaultState{ what=139376 }
E/WifiP2pService(  765): Unhandled message { what=139376 }
D/WifiP2pService(  765): P2pDisabledState{ what=139287 }
,D/WifiP2pService(  765): DefaultState{ what=139287 }
D/CommandListener(  237): Clearing all IP addresses on wlan0
W/NetworkManagementService(  765): route cmd failed: 
W/NetworkManagementService(  765): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '60 route del src v6 2' failed with '400 60 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  765): '
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  765): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  765): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  765): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/RouteController(  237): /system/bin/ip -4 route del default table 2 2>&1
I/SELinux ( 5955): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5955):  
,I/WifiTrafficPoller(  765): evaluateTrafficStatsPolling
,D/WifiNative(  765): callSECApiBoolean - ID [13]
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,I/wpa_supplicant( 1955): USE_NETWORK : USE_NETWORK OFF
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  237): RTNETLINK answers: No such process
,V/RouteController(  237): /system/bin/ip -4 rule del table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1065): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1065): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1065): wifi: GONE sig=0 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: GONE sig=0 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: GONE sig=0 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1065): wifi: GONE sig=0 act=2130837934
D/SignalClusterView_dual( 1065): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1065): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,E/WifiStateMachine(  765): Error! unhandled message{ when=-62ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetUtils(  765): android_net_utils_resetConnections in env=0x79c27880 clazz=0xa5a00001 iface=wlan0 mask=0x3
,E/WifiStateMachine(  765): Error! unhandled message{ when=-64ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  765): resetConnections(wlan0, 3)
E/WifiStateMachine(  765): Error! unhandled message{ when=-44ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  765): Error! unhandled message{ when=-45ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
I/SELinux ( 5955): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5955):  
I/SELinux ( 5955):  
I/SELinux ( 5955): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5955): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5955): >>>>> Normal User
E/dalvikvm( 5955): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
E/SELinux ( 5955): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5955): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5955): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5955): Added TimaKesytore provider
,D/Tethering(  765): interfaceLinkStateChanged p2p0, false
,D/Tethering(  765): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 1955): p2p0: CTRL-EVENT-TERMINATING 
,D/FileShare-Server( 5955): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 5955): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() FAILED
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 5955): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 5955): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
,D/NearbySettings( 1305): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1305): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1305): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1305): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1305): MountReceiver.mPrefHandler - 7002
,I/ActivityManager(  765): Killing 4995:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/knox    ( 3256): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): updateIfacesLocked()
W/ContextImpl( 3256): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
V/NetworkStats(  765): performPollLocked(flags=0x1)
,V/NetworkStats(  765): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/wpa_supplicant( 1955): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1955): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1955): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  765): interfaceLinkStateChanged wlan0, false
D/Tethering(  765): interfaceStatusChanged wlan0, false
I/knox    ( 3256): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/Tethering(  765): InitialState.processMessage what=4
E/Tethering(  765): No numeric data
D/knox    ( 3256): KNOXAgentService : onCreate()
,D/knox    ( 3256): KNOXAgentService : set alarms for deniallog and usage data upload
,I/ConnectivityService(  765): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  765): interfaceLinkStateChanged wlan0, false
D/Tethering(  765): interfaceStatusChanged wlan0, false
D/knox    ( 3256): KNOXAgentService. startJobThread() start
D/Tethering(  765): interfaceLinkStateChanged wlan0, false
D/Tethering(  765): interfaceStatusChanged wlan0, false
D/Tethering(  765): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  765): interfaceLinkStateChanged wlan0, false
D/Tethering(  765): interfaceStatusChanged wlan0, false
D/knox    ( 3256): KNOXAgentService. JobThread()
D/knox    ( 3256): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3256): KNOXAgentService. startJobThread() wait
D/knox    ( 3256): KNOXAgentService : onDestroy().
D/knox    ( 3256): ModuleBase.cancelAllAlarmManageModule()
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): performPollLocked() took 32ms
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): performPollLocked() took 20ms
,D/Tethering(  765): interfaceLinkStateChanged wlan0, false
,D/Tethering(  765): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1955): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiStateMachine(  765): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,W/Settings( 1216): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/knox    ( 3256): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3256): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3256): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3256): KNOXAgentService : onCreate()
D/knox    ( 3256): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3256): KNOXAgentService. startJobThread() start
D/knox    ( 3256): KNOXAgentService. JobThread()
D/knox    ( 3256): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3256): KNOXAgentService. startJobThread() wait
D/knox    ( 3256): KNOXAgentService : onDestroy().
D/knox    ( 3256): ModuleBase.cancelAllAlarmManageModule()
,I/ApplicationPolicy(  765): updateDataUsageMap
,D/Tethering(  765): Tethering got CONNECTIVITY_ACTION
,W/Netd    (  237): No subsystem found in netlink event
D/NetlinkEvent(  237): Unexpected netlink message. type=0x11
,D/Tethering(  765): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  765): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  765): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/LocSvc_java(  765): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  765): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  765): ignore wifi update if we are not in OPENING or CLOSING
,D/Vpn     (  765): Interface removed : wlan0
,D/Tethering(  765): interfaceRemoved wlan0
,E/Tethering(  765): attempting to remove unknown iface (wlan0), ignoring
,W/Netd    (  237): No subsystem found in netlink event
D/NetlinkEvent(  237): Unexpected netlink message. type=0x11
,D/Vpn     (  765): Interface removed : p2p0
,D/Tethering(  765): interfaceRemoved p2p0
,E/Tethering(  765): attempting to remove unknown iface (p2p0), ignoring
,D/accuweather( 1441): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3870): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5135): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5135): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5135): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5135): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5135): noConnectivity : true
,I/KLMS-2.3.201 : ( 5461): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/bt-btm  ( 1949): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1949): btm_ble_resume_bg_conn 0
,E/        ( 1949): ### ASSERT : external/bluetooth/bluedroid/main/../iop_hooks/iop_db_hooks.c line 223 no handle (0) ###
,D/KeyguardViewMediator( 1065): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1065): isGear1: device is not B1!
,V/BluetoothEventManager( 1305): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1305): ACTION_ACL_DISCONNECTED
,I/KLMS-2.3.201 : ( 5461): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681522308
,I/KLMS-2.3.201 : ( 5461): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5480): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5480): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,D/WifiStateMachine(  765): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,I/SA      ( 4013): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4013): [BDLM] already registered in spp
,I/SA      ( 4013): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4013): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4013): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4013): [OR] == isSIMCardReady false ==
I/SA      ( 4013): [SCU] == networkStateCheck == false
,I/SA      ( 4013): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1236): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1236): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5494): Other Intent
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4062): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4062): getCountryCode(): countryCode = PL
,D/Headlines( 4062): Breath.onCreate
,D/Headlines( 4062): Breath timer started. interval : 30000
D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4062): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4062): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4062): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4062): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4062): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4062): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager(  765): waitForAlarm result :8
,D/QuickConnect[1.1][2] ( 3327): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3327): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3327): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425e42b0
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,I/iu.Environment( 1785): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1785): num queued entries: 0
,I/iu.UploadsManager( 1785): num updated entries: 0
,I/iu.SyncManager( 1785): NEXT; no task
,I/BTConnectionReceiver( 2179): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2179): Bluetooth Device Name: Thali Test's G2
,D/Headlines( 4062): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4062): Breath 140 latestRequest time : 1449681522453 current time : 1449681522593
,D/BluetoothAdapterState( 1949): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BtConfig.SecureMode( 1949): isSecureModeOn:false
,W/BluetoothAdapterService( 1949): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 1949): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 1949): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 1949): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 1949): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/HeadsetService( 1949): Received stop request...Stopping profile...
,D/QuickConnect[1.1][2] ( 3327): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
,W/BluetoothAdapterService( 1949): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 1949): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,E/SMD     (  240): DCD ON
,W/BluetoothAdapterService( 1949): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 1949): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/GKI_LINUX( 1949): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/BtSettings.ProfileConfig( 1949): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 1949): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 1949): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 1949): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 1949): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 1949): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 1949): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 1949): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 1949): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 1949): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 1949): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/HeadsetProfile( 1305): Bluetooth service disconnected
,D/BtSettings.ProfileConfig( 1949): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 1949): Profile still running: com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterState( 1949): Stopping profile services that were post enabled
,W/BluetoothHeadsetServiceJni( 1949): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1949): Cleaning up Bluetooth Handsfree callback object
,D/A2dpService( 1949): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1949): Exit Disconnected: -1
,D/MediaFocusControl(  765): <<< unregisterRemoteControlDisplay
,D/Avrcp   ( 1949): Unregistering previous receiver
,D/BluetoothA2dp(  765): Proxy object disconnected
,D/BluetoothA2dp( 3327): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 3327): A2dpProfile.onServiceConnected - Bluetooth service disconnected
,D/HidService( 1949): Received stop request...Stopping profile...
,D/HidService( 1949): Stopping Bluetooth HidService
,D/BluetoothInputDevice( 3327): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 3327): HidProfile.onServiceDisconnected - Bluetooth service disconnected
,D/HealthService( 1949): Received stop request...Stopping profile...
,D/PanService( 1949): Received stop request...Stopping profile...
,D/BluetoothTethering(  765): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  765): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  765): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService( 1949): Received stop request...Stopping profile...
,D/BtSettings.ProfileConfig( 1949): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 1949): Profile still running: com.android.bluetooth.hdp.HealthService
,I/GKI_LINUX( 1949): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 1949): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 1949): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BtSettings.ProfileConfig( 1949): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 1949): Profile still running: com.android.bluetooth.hdp.HealthService
,W/BluetoothHidServiceJni( 1949): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 1949): Cleaning up Bluetooth GID callback object
,D/BtSettings.ProfileConfig( 1949): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 1949): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 1949): Cleaning up Bluetooth Health Interface...
,D/BluetoothA2dp( 1305): Proxy object disconnected
,W/BluetoothHealthServiceJni( 1949): Cleaning up Bluetooth Health object
,D/BtSettings.ProfileConfig( 1949): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 1949): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothPanServiceJni( 1949): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1949): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterService( 1949): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,D/BluetoothAdapterState( 1949): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,I/BluetoothAdapterState( 1949): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1949): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 1949): updateAdapterState state is 10
,D/BluetoothAdapterService( 1949): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService( 1949): Autoconnection is available 
,D/BluetoothAdapterService( 1949): updateAdapterState prevState = 13newState = 10
,I/BluetoothAdapterState( 1949): Entering OffState
,D/A2dpProfile( 1305): Bluetooth service disconnected
,D/BluetoothA2dp( 2101): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3327): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1305): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1305): Unbinding service...
,D/BluetoothPbap( 1305): onBluetoothStateChange: up=false
,D/BluetoothMap( 1305): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  765): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3327): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 1305): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1305): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1305): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1305): Unbinding service...
,W/InputMethodManagerService(  765): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  765): [BT Setting State] State =10
,I/WifiTrafficPoller(  765): mBoosterFLAG : 0
,I/WifiTrafficPoller(  765): current booster mode : FullMode
I/InputMethodManagerService(  765): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/PhoneApp( 1236): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
,I/QuickConnect[1.1][2] ( 3327): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
,D/BluetoothA2dp( 2101): Proxy object disconnected
,V/BluetoothEventManager( 1305): Received android.bluetooth.adapter.action.STATE_CHANGED
,W/ContextImpl( 1305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 1305): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1305): onReceive
,D/AuthorizationBluetoothService( 1319): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/AmoledAdjustTimer(  765): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,I/ActivityManager(  765): Waited long enough for: ServiceRecord{446cfba0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 14
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  765): waitForAlarm result :8
,D/Headlines( 4062): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4062): Breath 30045 latestRequest time : 1449681522453 current time : 1449681552498
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 390s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 15
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,D/Headlines( 4062): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4062): Breath 60045 latestRequest time : 1449681522453 current time : 1449681582499
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 16
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,D/Headlines( 4062): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4062): Breath 90039 latestRequest time : 1449681522453 current time : 1449681612494
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  765): [PWL] Off : 455s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 17
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,D/Headlines( 4062): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4062): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4062): Breath 120042 latestRequest time : 1449681522453 current time : 1449681642495
,D/Headlines( 4062): stop 
,D/Headlines( 4062): Breath.onDestroy : 
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 18
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 19
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 525s ago
,D/AmoledAdjustTimer(  765): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/dalvikvm(  765): GC_CONCURRENT freed 3249K, 57% free 23904K/55200K, paused 25ms+62ms, total 579ms
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  765): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  765): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  765): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 20
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 21
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 600s ago
,V/AlarmManager(  765): waitForAlarm result :8
,I/SensorManagerA(  765): getReportingMode :: sensor.mType = 5
,D/Sensors (  765): LightSensor setDelay = 200000000
,D/LightsService(  765): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  765): LightSensor setSensorDelay = 200000000
D/Sensors (  765): Light sensor flush: not enabled 0
D/Sensors (  765): LightSensor enable = 1
D/Sensors (  765): LightSensor enableSensor = 1
,D/SensorManager(  765): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  765): LightSensor enable = 0
,D/Sensors (  765): LightSensor enableSensor = 0
,D/SensorManager(  765): unregisterListener ::   
D/LightsService(  765): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  765): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  765): !@Sync 22
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 23
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  765): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  765): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  765): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 24
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,I/PowerManagerService(  765): [PWL] Off : 680s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 25
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 26
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 27
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 765s ago
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 28
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 29
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  765): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  765): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  765): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  765): !@Sync 30
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 855s ago
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 31
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 32
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 33
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 950s ago
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 34
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 35
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  765): GC_CONCURRENT freed 3693K, 58% free 23729K/55200K, paused 24ms+50ms, total 545ms
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  765): stay LED for fully charged
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 36
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 1050s ago
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 37
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  765): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 38
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 39
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/TimaService(  765): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  765): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  765): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 40
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 41
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,I/SensorManagerA(  765): getReportingMode :: sensor.mType = 5
,D/Sensors (  765): LightSensor setDelay = 200000000
,D/Sensors (  765): LightSensor setSensorDelay = 200000000
,D/Sensors (  765): Light sensor flush: not enabled 0
,D/LightsService(  765): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  765): LightSensor enable = 1
D/Sensors (  765): LightSensor enableSensor = 1
D/SensorManager(  765): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  765): LightSensor enable = 0
,D/Sensors (  765): LightSensor enableSensor = 0
,D/LightsService(  765): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  765): unregisterListener ::   
D/LightsService(  765): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  765): !@Sync 42
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  765): !@Sync 43
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  765): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  765): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  765): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  765): !@Sync 44
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  765): !@Sync 45
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-15, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-13, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  765): !@Sync 46
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 47
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 1380s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  765): !@Sync 48
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  765): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  765): !@Sync 49
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  765): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  765): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  765): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  765): !@Sync 50
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  765): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 51
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 1500s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm(  765): GC_CONCURRENT freed 3461K, 58% free 23724K/55200K, paused 32ms+50ms, total 544ms
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 52
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 53
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 54
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 55
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  765): [PWL] Off : 1625s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 56
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 57
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 58
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 59
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  765): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  765): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  765): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,I/ProcessStatsService(  765): Prepared write state in 203ms
,I/ProcessStatsService(  765): Prepared write state in 163ms
,I/ProcessStatsService(  765): Pruning old procstats: /data/system/procstats/state-2015-12-09-03-34-48.bin
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  765): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  765): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 60
,I/PowerManagerService(  765): [PWL] Off : 1755s ago
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  765): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 61
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :4
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): performPollLocked(flags=0x3)
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  765): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): performPollLocked() took 195ms
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,I/SensorManagerA(  765): getReportingMode :: sensor.mType = 5
,D/LightsService(  765): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  765): LightSensor setDelay = 200000000
D/Sensors (  765): LightSensor setSensorDelay = 200000000
D/Sensors (  765): Light sensor flush: not enabled 0
D/Sensors (  765): LightSensor enable = 1
D/Sensors (  765): LightSensor enableSensor = 1
D/SensorManager(  765): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/LightsService(  765): [SvcLED]  onSensorChanged::light value = 0
D/Sensors (  765): LightSensor enable = 0
D/Sensors (  765): LightSensor enableSensor = 0
,D/SensorManager(  765): unregisterListener ::   
D/LightsService(  765): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1785): Aggregate from 1449680509721 (log), 1449680509721 (data)
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  765): waitForAlarm result :8
,V/AlarmManager(  765): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 62
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 269, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/BatteryService(  765): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  765): !@Sync 63
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  765): stay LED for fully charged
,D/UiModeManager(  765): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  765): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  765): mCoverManager.getCoverState() : true
D/BatteryService(  765): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
E/SMD     (  240): DCD ON
E/SMD     (  240): DCD ON
D/AndroidRuntime( 6355): 
D/AndroidRuntime( 6355): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6355): CheckJNI is OFF
D/AndroidRuntime( 6355): setted country_code = Poland
D/AndroidRuntime( 6355): setted countryiso_code = PL
D/AndroidRuntime( 6355): setted sales_code = XEO
D/AndroidRuntime( 6355): readGMSProperty: start
D/AndroidRuntime( 6355): readGMSProperty: already setted!!
D/AndroidRuntime( 6355): readGMSProperty: end
D/AndroidRuntime( 6355): addProductProperty: start
D/dalvikvm( 6355): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6355): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6355): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6355): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6355): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6355): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6355): failed to load memtrack module: -2
D/dalvikvm( 6355): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/SSRMv2:SIOP(  765): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  765): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
D/AndroidRuntime( 6355): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  765): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  765): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  765): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  765): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  765): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  765): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  765): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  765): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  765): getApplicationUninstallationEnabled
D/ApplicationPolicy(  765): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  765): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  765): START PACKAGE DELETE: observer{1142313368}
D/PackageManager(  765): pkg{<packageName>}
D/PackageManager(  765): user{0}
D/PackageManager(  765): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  765): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  765): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  765): Killing 5215:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/ActivityManager(  765): Killing 5657:com.sec.android.app.voicenote/1000 (adj 15): empty for 1810s
I/ActivityManager(  765): Killing 5644:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1810s
I/ActivityManager(  765): Killing 5611:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1811s
I/ActivityManager(  765): Killing 5353:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1816s
I/ActivityManager(  765): Killing 5340:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1817s
I/ActivityManager(  765): Killing 5326:com.samsung.helphub/1000 (adj 15): empty for 1817s
I/ActivityManager(  765): Killing 5313:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1817s
I/ActivityManager(  765): Killing 5297:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1817s
I/ActivityManager(  765): Killing 5266:com.google.android.apps.docs/u0a90 (adj 15): empty for 1817s
I/ActivityManager(  765): Killing 5248:com.sec.android.service.cm/u0a78 (adj 15): empty for 1818s
I/ActivityManager(  765): Killing 4644:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1818s
I/ActivityManager(  765): Killing 4295:com.android.mms/u0a48 (adj 15): empty for 1818s
I/ActivityManager(  765): Killing 5196:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1818s
I/ActivityManager(  765): Killing 4197:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1819s
I/ActivityManager(  765): Killing 5147:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1819s
I/ActivityManager(  765): Killing 5118:com.android.musicfx/u0a24 (adj 15): empty for 1819s
I/ActivityManager(  765): Killing 5105:com.samsung.groupcast/u0a15 (adj 15): empty for 1819s
I/ActivityManager(  765): Killing 5090:com.google.android.partnersetup/u0a14 (adj 15): empty for 1819s
I/ActivityManager(  765): Killing 5076:com.sec.android.inputmethod/1000 (adj 15): empty for 1820s
I/SurfaceFlinger(  246): id=16 Removed NainActivit (7/12)
I/SurfaceFlinger(  246): id=16 Removed NainActivit (-2/12)
I/WindowState(  765): WIN DEATH: Window{43cb2c40 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CountryDetector(  765): No listener is left
D/dalvikvm(  765): GC_CONCURRENT freed 3539K, 57% free 23764K/55200K, paused 4ms+10ms, total 113ms
D/dalvikvm(  765): WAIT_FOR_CONCURRENT_GC blocked 100ms
W/PackageSettings(  765): Skipping PackageSetting{42c7ace8 com.example.hello/10180} due to missing metadata
D/PackageManager(  765): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager(  765): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1785): GC_EXPLICIT freed 949K, 36% free 12340K/19216K, paused 4ms+6ms, total 46ms
W/SQLiteConnectionPool( 1785): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/AdaptiveEventManager( 1065): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3327): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/FPMS_FingerprintManagerService( 1084): onReceive: android.intent.action.PACKAGE_REMOVED
W/GeofencerStateMachine( 1216): Ignoring removeGeofence because network location is disabled.
I/SELinux ( 6383): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6383):  
D/dalvikvm( 1400): GC_EXPLICIT freed 4307K, 48% free 10028K/19216K, paused 4ms+4ms, total 77ms
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "sms"
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "smsto"
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "mms"
I/SELinux ( 6383): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6383):  
I/SELinux ( 6383):  
I/SELinux ( 6383): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6383): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6383): >>>>> Normal User
E/dalvikvm( 6383): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6383): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 2179): GC_EXPLICIT freed 1186K, 43% free 11026K/19216K, paused 5ms+4ms, total 140ms
I/InputReader(  765): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  765): PackageReceiver onReceive()
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "mmsto"
D/TimaKeyStoreProvider( 6383): in addTimaSignatureService
I/HarmonyEASService(  765): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/TimaKeyStoreProvider( 6383): Cannot add TimaSignature Service, License check Failed
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/ActivityThread( 6383): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "sms"
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "smsto"
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "mms"
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SurfaceFlinger(  246): id=19 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "mmsto"
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=6383, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6383): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6383): ELMEngine.ELMEngine( context ).
D/EnterpriseDeviceManagerService(  765): Package has changed for user 0
D/EnterpriseDeviceManagerService(  765): Admin package name: com.google.android.gms
D/elm:14132( 6383): MDMBridge.setEnterpriseBridge()
D/dalvikvm(  765): GC_EXPLICIT freed 1386K, 57% free 23830K/55200K, paused 6ms+17ms, total 273ms
D/PackageManager(  765): delete sourFile : 
D/elm:14132( 6383): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6383): ElmAgentService : onCreate()
D/elm:14132( 6383): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6383): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6383): MDMBridge.getInstance()
D/elm:14132( 6383): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6383): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 6398): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6398):  
D/elm:14132( 6383): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 6383): ElmAgentService : onDestroy().
D/PackageManager(  765): delete native library directory: 
D/AndroidRuntime( 6355): Shutting down VM
D/dalvikvm( 6355): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 2ms
D/PackageManager(  765): return delete result to caller: 1142313368
D/PackageManager(  765): returnCode: 1
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "sms"
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BackupManagerService(  765): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  765): removePackageParticipantsLocked: uid=10179 #1
I/SELinux ( 6398): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6398):  
I/SELinux ( 6398):  
I/SELinux ( 6398): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6398): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6398): >>>>> Normal User
E/dalvikvm( 6398): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6398): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "smsto"
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6398): in addTimaSignatureService
D/TimaKeyStoreProvider( 6398): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6398): Added TimaKesytore provider
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "mms"
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  765):   Action: "android.intent.action.SENDTO"
I/PackageManager(  765):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  765):   Scheme: "mmsto"
I/PackageManager(  765): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher( 1241): onRestart, Launcher: 1114101704
D/Launcher( 1241): onStart, Launcher: 1114101704
D/Launcher.HomeView( 1241): onStart
W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=6398, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1441): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1441): [237392/5] SurfaceWidget drawing first frame
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SurfaceFlinger(  246): id=20 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 6398): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425d8b10, skipping init
I/SecureStorage( 6398): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6398): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  293): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6398
I/SecureStorage(  293): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6398): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SecureStorage( 6398): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  293): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6398
I/SecureStorage(  293): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
I/CrashAnrDetector(  765): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  765): clearDefaults: com.test.thalitest
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/InputReader(  765): Processing first event
E/SMD     (  240): DCD ON
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
